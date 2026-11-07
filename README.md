# privacy_policy

各アプリのプライバシーポリシー（日本語・英語）と、ストア申告（Google Play「データ セーフティ」／ App Store「App のプライバシー」）の回答案をまとめたリポジトリです。
GitHub Pages で公開し、各ストアのプライバシーポリシー URL 欄とアプリ内のリンクに設定します。

> 法的助言ではありません。公開前に、必要に応じて専門家の確認を受けてください。
> 各ポリシーは 2026年11月7日時点の各リポジトリのコード（依存パッケージ・AndroidManifest・Info.plist・ソース）を確認して書いています。

## 1. 構成と公開 URL

| アプリ | ファイル | 公開 URL（GitHub Pages を有効にした場合） | 調査したリポジトリ |
|---|---|---|---|
| 一覧 | `index.md` | `https://satousatou01234-dot.github.io/privacy_policy/` | — |
| 英語道場 | `eigodojo/index.md` | `…/privacy_policy/eigodojo/` | EigoDojo |
| SimpleToDoMAX2 | `simpletodomax2/index.md` | `…/privacy_policy/simpletodomax2/` | dev |
| WBS Planner | `wbsplanner/index.md` | `…/privacy_policy/wbsplanner/` | WBSmaker |
| 麻雀道場 | `mahjongdojo/index.md` | `…/privacy_policy/mahjongdojo/` | MahjongDojo（`flutter_app/`） |
| VELVET TRIGGER | `velvettrigger/index.md` | `…/privacy_policy/velvettrigger/` | windage_sniper |
| Kokoa's Prime Drops | `primedrops/index.md` | `…/privacy_policy/primedrops/` | prime_drop |

公開手順: リポジトリの Settings → Pages → Source を「Deploy from a branch」、ブランチを既定ブランチ・`/ (root)` にする。
App Store・Google Play とも、ポリシーのページはログイン不要で閲覧でき、PDF ではなくウェブページである必要があります（GitHub Pages で満たせます）。

### 公開前に必ず埋める箇所

- `【運営者名】` / `[Operator name]`
- `【連絡先メールアドレス】` / `[Contact email]`（ストアの「デベロッパーの連絡先」と同じものを推奨）

```bash
grep -rn -e '【' -e '\[Operator' -e '\[Contact' --include=*.md .
```

## 2. アプリごとの調査結果

| アプリ | 通信 | 広告・解析 SDK | 主な権限・機能 | 端末内の保存 |
|---|---|---|---|---|
| 英語道場 | あり（AdMob のみ） | google_mobile_ads（UMP 同意、ATT なし、広告レーティング T） | INTERNET、TTS | SharedPreferences |
| SimpleToDoMAX2 | アプリ自身はなし | なし | 通知・正確なアラーム・起動時再予約、カレンダー読書き、マイク・音声認識、メール起動、共有 | SQLite |
| WBS Planner | なし | なし | カレンダー読書き、生体認証、ファイル選択、共有 | SQLite（`allowBackup=false`） |
| 麻雀道場（Flutter 版） | なし（生成 AI 機能は削除済み） | なし | なし | アプリ専用領域のファイル |
| VELVET TRIGGER | なし | なし | モーションセンサー、TTS、画面点灯維持 | SharedPreferences |
| Kokoa's Prime Drops | なし | なし | なし（効果音のみ） | なし |

麻雀道場の WPF 版（Windows、Gemini・OpenAI・Claude の API を利用）は Android / Apple 向けではないため対象外です。Microsoft Store 等で配信する場合は、API キーの保存と各 AI 事業者への送信を記載した別のポリシーが必要です。

## 3. ストア申告の回答案

### 3.1 Google Play「データ セーフティ」

| アプリ | データの収集・共有 | 申告内容 |
|---|---|---|
| 英語道場 | **収集する・共有する（広告 SDK）** | 位置情報：おおよその位置（IP から）／ アプリのアクティビティ：アプリの操作 ／ アプリの情報とパフォーマンス：クラッシュログ・診断 ／ デバイスまたはその他の ID：広告 ID。目的は「広告またはマーケティング」「不正行為防止・セキュリティ・コンプライアンス」「分析」。送信時の暗号化：はい。削除リクエスト：運営者は保有しない（広告 ID は端末でリセット可能）。※ Google の AdMob 用の申告ガイドで最新の内容を確認すること |
| SimpleToDoMAX2 | 収集しない・共有しない | 音声は OS の音声認識サービスが処理し、アプリ・アプリの SDK は送信しないため「収集しない」で申告。カレンダーへの書き込みは端末内の操作 |
| WBS Planner | 収集しない・共有しない | 通信なし |
| 麻雀道場 | 収集しない・共有しない | 通信なし |
| VELVET TRIGGER | 収集しない・共有しない | 通信なし |
| Kokoa's Prime Drops | 収集しない・共有しない | 通信なし |

あわせて: 英語道場は「広告」の宣言で「はい（広告を含む）」、広告 ID の使用宣言で「広告・マーケティング」を選ぶ。ほかのアプリは「広告を含まない」。
ターゲット年齢は 13 歳以上（Kokoa's Prime Drops を子ども向けに含める場合はファミリー ポリシーへの対応が必要。データは収集しないので対応しやすい）。

### 3.2 App Store Connect「App のプライバシー」

| アプリ | 回答 |
|---|---|
| 英語道場 | 「データを収集する」。**トラッキングに使用されるデータ：なし**（ATT を求めず IDFA を使わないため）。収集するデータ：位置情報（おおよその場所）、識別子（デバイス ID）、使用状況データ（製品の操作・広告データ）、診断（クラッシュ・パフォーマンス）。用途：サードパーティ広告・分析・App の機能（不正防止）。ユーザーへのリンク：なし。※ Google の「Google Mobile Ads SDK のデータ開示」ページで最新の内容を確認すること |
| SimpleToDoMAX2 | 「データを収集しない」（音声認識は Apple の機能で、開発者は音声を受け取らない） |
| WBS Planner | 「データを収集しない」 |
| 麻雀道場 | 「データを収集しない」 |
| VELVET TRIGGER | 「データを収集しない」 |
| Kokoa's Prime Drops | 「データを収集しない」 |

## 4. アプリ側でやること（参考）

- 各アプリの設定画面などに、該当ページへのリンクを置く（両ストアとも、アプリ内からポリシーを見られることを求めています）。
- 英語道場は `assets/legal/privacy_policy.txt`（アプリ内表示）にも同じ内容があり、運営者名・連絡先・制定日が未記入です。本リポジトリの `eigodojo/index.md` と内容をそろえてください。
- 広告・クラッシュ収集・クラウド同期などを追加したら、ポリシーとストア申告を必ず更新する。
