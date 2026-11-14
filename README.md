# privacy_policy

各アプリのプライバシーポリシー（日本語・英語）と、ストア申告（Google Play「データ セーフティ」／ App Store「App のプライバシー」）の回答案をまとめたリポジトリです。
GitHub Pages で公開し、各ストアのプライバシーポリシー URL 欄とアプリ内のリンクに設定します。

> 法的助言ではありません。公開前に、必要に応じて専門家の確認を受けてください。
> 各ポリシーは 2026年11月7日時点の各リポジトリのコード（依存パッケージ・AndroidManifest・Info.plist・ソース）を確認して書いています。SimpleToDoMAX2 は、2026年11月13日に、広告（AdMob）・トラッキングの確認（ATT）・アプリ内課金（広告の非表示）に合わせて更新し、特定商取引法に基づく表記を追加しました。英語道場は、2026年11月14日に、アプリ内課金（広告の非表示）・広告の内容の区分（G）・EEA などの利用者向けの記載に合わせて更新し、特定商取引法に基づく表記を追加しました。麻雀道場は、2026年11月14日に、広告（AdMob のバナー・インタースティシャル・リワード広告。ATT なし）・アプリ内課金（広告の非表示）に合わせて更新し、特定商取引法に基づく表記を追加しました。Kokoa's Prime Drops は、2026年11月14日に、prime_drop リポジトリの v0.5（バナー広告、ボムがもらえるリワード インタースティシャル広告、広告の非表示のアプリ内課金、設定の保存）に合わせて更新し、特定商取引法に基づく表記を追加しました。

## 1. 構成と公開 URL

| アプリ | ファイル | 公開 URL（GitHub Pages を有効にした場合） | 調査したリポジトリ |
|---|---|---|---|
| 一覧 | `index.md` | `https://satousatou01234-dot.github.io/privacy_policy/` | — |
| 英語道場 | `eigodojo/index.md` | `…/privacy_policy/eigodojo/` | EigoDojo |
| 英語道場（特定商取引法に基づく表記） | `eigodojo/tokushoho/index.md` | `…/privacy_policy/eigodojo/tokushoho/` | EigoDojo |
| SimpleToDoMAX2 | `simpletodomax2/index.md` | `…/privacy_policy/simpletodomax2/` | dev |
| SimpleToDoMAX2（特定商取引法に基づく表記） | `simpletodomax2/tokushoho/index.md` | `…/privacy_policy/simpletodomax2/tokushoho/` | dev |
| WBS Planner | `wbsplanner/index.md` | `…/privacy_policy/wbsplanner/` | WBSmaker |
| 麻雀道場 | `mahjongdojo/index.md` | `…/privacy_policy/mahjongdojo/` | MahjongDojo（`flutter_app/`） |
| 麻雀道場（特定商取引法に基づく表記） | `mahjongdojo/tokushoho/index.md` | `…/privacy_policy/mahjongdojo/tokushoho/` | MahjongDojo（`flutter_app/`） |
| VELVET TRIGGER | `velvettrigger/index.md` | `…/privacy_policy/velvettrigger/` | windage_sniper |
| Kokoa's Prime Drops | `primedrops/index.md` | `…/privacy_policy/primedrops/` | prime_drop |
| Kokoa's Prime Drops（特定商取引法に基づく表記） | `primedrops/tokushoho/index.md` | `…/privacy_policy/primedrops/tokushoho/` | prime_drop |

公開手順: リポジトリの Settings → Pages → Source を「Deploy from a branch」、ブランチを既定ブランチ・`/ (root)` にする。
App Store・Google Play とも、ポリシーのページはログイン不要で閲覧でき、PDF ではなくウェブページである必要があります（GitHub Pages で満たせます）。

### 記入した運営者・連絡先

- 運営者: KOKOAPPS、連絡先: kokoapps@outlook.jp（2026年11月13日に全ページへ記入）。ストアの「デベロッパーの連絡先」にも同じものを設定することを推奨します。
- 特定商取引法に基づく表記（SimpleToDoMAX2・英語道場・麻雀道場・Kokoa's Prime Drops）では、運営責任者・所在地・電話番号を「請求があれば遅滞なく開示」としています。請求があったときにすぐ提供できるよう、準備しておいてください。屋号だけでは事業者の表示として足りないとされることもあるため、公開前に専門家に確認することを推奨します。
- SimpleToDoMAX2 を EU・英国で配信し、EU 代理人・英国代理人（GDPR 第 27 条）を置く場合は、第6条（英語版も）に名称と連絡先を追記してください（dev リポジトリの `doc/LEGAL_REVIEW.md` §5 の 8a）。麻雀道場・Kokoa's Prime Drops も同じで、追記する場所はそれぞれのポリシーの第6条（英語版も。Kokoa's Prime Drops は `primedrops/index.md`）です。

記入漏れは、次のコマンドで確認できます。

```bash
grep -rn -e '【' -e '\[Operator' -e '\[Contact' --include=*.md .
```

## 2. アプリごとの調査結果

| アプリ | 通信 | 広告・解析 SDK | 主な権限・機能 | 端末内の保存 |
|---|---|---|---|---|
| 英語道場 | あり（AdMob、アプリ内課金のストアへの問い合わせ） | google_mobile_ads（UMP 同意、ATT なし、広告レーティング G）、in_app_purchase（Google Play Billing・StoreKit 2） | INTERNET、BILLING、TTS | SharedPreferences（広告の非表示を購入済みかどうかを含む） |
| SimpleToDoMAX2 | あり（AdMob、アプリ内課金のストアへの問い合わせ） | google_mobile_ads（UMP 同意、ATT あり、広告レーティング G）、in_app_purchase（Google Play Billing・StoreKit 2） | INTERNET、BILLING、通知・正確なアラーム・起動時再予約、カレンダー読書き、マイク・音声認識、メール起動、共有 | SQLite（広告の非表示を購入済みかどうかを含む） |
| WBS Planner | なし | なし | カレンダー読書き、生体認証、ファイル選択、共有 | SQLite（`allowBackup=false`） |
| 麻雀道場（Flutter 版） | あり（AdMob、アプリ内課金のストアへの問い合わせ。生成 AI 機能は削除済み） | google_mobile_ads（UMP 同意、ATT なし、広告レーティング T、開始画面のバナー・対局後のインタースティシャル・利用者が選んだときだけのリワード広告〔テンパイ時の即ツモ・即ロンの特典〕）、in_app_purchase（Google Play Billing・App Store。商品 ID `mahjongdojo_remove_ads`） | INTERNET、ACCESS_NETWORK_STATE、AD_ID（広告 SDK が追加）、BILLING | アプリ専用領域のファイル（牌譜・成績・段位・ドリルの結果・設定・BGM の順番・error.log。広告の非表示を購入済みかどうかを含む） |
| VELVET TRIGGER | なし | なし | モーションセンサー、TTS、画面点灯維持 | SharedPreferences |
| Kokoa's Prime Drops | Android 版はあり（AdMob、アプリ内課金のストアへの問い合わせ）。Windows 版はなし | google_mobile_ads（UMP 同意、ATT なし〔iOS 版なし〕、広告レーティング G、バナーとリワード インタースティシャル）、in_app_purchase（Google Play Billing） | INTERNET・ACCESS_NETWORK_STATE・AD_ID・ACCESS_ADSERVICES_AD_ID／ATTRIBUTION／TOPICS・WAKE_LOCK・FOREGROUND_SERVICE（広告 SDK が追加）、BILLING、振動。設定から特定商取引法に基づく表記にもリンク（prime_drop の `lib/src/ui/app_info.dart` の `legalNoticeUrl`） | SharedPreferences（音量・言語、広告の非表示を購入済みかどうか）。得点は保存しない |

麻雀道場の WPF 版（Windows、Gemini・OpenAI・Claude の API を利用）は Android / Apple 向けではないため対象外です。Microsoft Store 等で配信する場合は、API キーの保存と各 AI 事業者への送信を記載した別のポリシーが必要です。

## 3. ストア申告の回答案

### 3.1 Google Play「データ セーフティ」

| アプリ | データの収集・共有 | 申告内容 |
|---|---|---|
| 英語道場 | **収集する・共有する（広告 SDK）** | 位置情報：おおよその位置（IP から）／ アプリのアクティビティ：アプリの操作 ／ アプリの情報とパフォーマンス：クラッシュログ・診断 ／ デバイスまたはその他の ID：広告 ID・アプリセット ID。目的は「広告またはマーケティング」「不正行為防止・セキュリティ・コンプライアンス」「分析」。送信時の暗号化：はい。削除リクエスト：運営者は保有しない（広告 ID は端末でリセット可能）。アプリ内課金: 購入済みかどうかは端末内だけに保存し、アプリは送信しない。決済は Google Play が処理する（Google Play の課金システムが扱うデータの申告の要否は、Play Console のヘルプで最新の内容を確認すること）。※ Google の AdMob 用の申告ガイドで最新の内容を確認すること |
| SimpleToDoMAX2 | **収集する・共有する（広告 SDK）** | 英語道場と同じ（広告 SDK の分）。アプリ内課金: 購入済みかどうかは端末内だけに保存し、アプリは送信しない。決済は Google Play が処理する（Google Play の課金システムが扱うデータの申告の要否は、Play Console のヘルプで最新の内容を確認すること）。音声は OS の音声認識サービスが処理し、アプリ・アプリの SDK は送信しない。カレンダーへの書き込みは端末内の操作。※ Google の AdMob 用の申告ガイドで最新の内容を確認すること |
| WBS Planner | 収集しない・共有しない | 通信なし |
| 麻雀道場 | **収集する・共有する（広告 SDK）** | 英語道場と同じ（広告 SDK の分。デバイスまたはその他の ID は、広告 ID とアプリセット ID）。アプリ内課金: 購入済みかどうかは端末内だけに保存し、アプリは送信しない。決済は Google Play が処理する（Google Play の課金システムが扱うデータの申告の要否は、Play Console のヘルプで最新の内容を確認すること）。リワード広告の特典の回数・error.log は端末内だけで、送信しない。※ Google の AdMob 用の申告ガイドで最新の内容を確認すること |
| VELVET TRIGGER | 収集しない・共有しない | 通信なし |
| Kokoa's Prime Drops | **収集する・共有する（広告 SDK）** | 英語道場と同じ（広告 SDK の分）。アプリ内課金: 購入済みかどうかは端末内だけに保存し、アプリは送信しない。決済は Google Play が処理する。リワード広告で渡すのはゲーム内のボムだけ。※ Google の AdMob 用の申告ガイドで最新の内容を確認すること |

あわせて: 英語道場・SimpleToDoMAX2・麻雀道場・Kokoa's Prime Drops は「広告」の宣言で「はい（広告を含む）」、広告 ID の使用宣言で「広告・マーケティング」を選ぶ。ほかのアプリは「広告を含まない」。英語道場・SimpleToDoMAX2・麻雀道場の「アプリ内購入あり」は、Play Console で商品を登録するとストアに表示される。Kokoa's Prime Drops の広告の非表示（管理対象のアイテム `remove_ads`、200 円）も Play Console で登録する。
ターゲット年齢は 13 歳以上（Kokoa's Prime Drops を子ども向けに含める場合はファミリー ポリシーへの対応が必要。広告を入れたので、ファミリー向けの認定を受けた広告 SDK の設定〔子ども向けとして扱う指定など〕とポリシーの書き直しが要る。今は広告レーティングを G に制限しているだけ）。

### 3.2 App Store Connect「App のプライバシー」

| アプリ | 回答 |
|---|---|
| 英語道場 | 「データを収集する」。**トラッキングに使用されるデータ：なし**（ATT を求めず IDFA を使わないため）。収集するデータ：位置情報（おおよその場所）、識別子（デバイス ID）、使用状況データ（製品の操作・広告データ）、診断（クラッシュ・パフォーマンス）。用途：サードパーティ広告・分析・App の機能（不正防止）。ユーザーへのリンク：Google Mobile Ads SDK のプライバシーマニフェストに合わせる（Xcode の Organizer の「Generate Privacy Report」で確認。13.12.0 では、識別子（デバイス ID）・おおよその場所・広告データ・製品の操作が「ユーザーにリンク」とされている）。「トラッキングに使用されるデータ：なし」も、同じレポートと Google の開示の案内で確かめてから回答する。App 内課金の決済は Apple が処理し、アプリは購入情報を送信しない。年齢区分は 4+ の見込み（広告の上限 G と合わせる）。※ Google の「Google Mobile Ads SDK のデータ開示」ページで最新の内容を確認すること（iOS 版は広告ユニットの作成後） |
| SimpleToDoMAX2 | 「データを収集する」。**トラッキングに使用されるデータ：あり**（アプリが ATT のダイアログを表示し、許可されれば IDFA を広告に使う。Google の案内で「トラッキング」に使うとされるデータ（デバイス ID など）を申告する）。収集するデータと用途は、Google Mobile Ads SDK のプライバシーマニフェストに合わせる（Xcode の Organizer の「Generate Privacy Report」で確認。13.12.0 では、識別子（デバイス ID）・おおよその場所・広告データ・製品の操作が「ユーザーにリンク」とされている）。App 内課金の決済は Apple が処理し、アプリは購入情報を送信しない。音声認識は Apple の機能で、開発者は音声を受け取らない。年齢区分は 4+ の見込み（広告の上限 G と合わせる） |
| WBS Planner | 「データを収集しない」 |
| 麻雀道場 | 「データを収集する」。**トラッキングに使用されるデータ：なし**（ATT を求めず IDFA を使わないため。`NSUserTrackingUsageDescription` もない）。収集するデータ：位置情報（おおよその場所）、識別子（デバイス ID）、使用状況データ（製品の操作・広告データ）、診断（クラッシュ・パフォーマンス）。用途：サードパーティ広告・分析・App の機能（不正防止）。ユーザーへのリンクの有無は、Google Mobile Ads SDK のプライバシーマニフェストに合わせる（Xcode の Organizer の「Generate Privacy Report」で確認）。App 内課金の決済は Apple が処理し、アプリは購入情報を送信しない。年齢区分は、対象年齢（13 歳以上）と広告の上限（T）に合わせる。※ Google の「Google Mobile Ads SDK のデータ開示」ページで最新の内容を確認すること |
| VELVET TRIGGER | 「データを収集しない」 |
| Kokoa's Prime Drops | iOS 版は未提供（広告・課金は Android 版だけに実装）。iOS で配信する場合は、SimpleToDoMAX2 と同様の申告とポリシーの追記が必要 |

## 4. アプリ側でやること（参考）

- 各アプリの設定画面などに、該当ページへのリンクを置く（両ストアとも、アプリ内からポリシーを見られることを求めています）。SimpleToDoMAX2 は、設定画面からプライバシーポリシーと特定商取引法に基づく表記にリンク済み（dev リポジトリの `lib/config/release_config.dart`）。英語道場も、設定画面からリンク済み（EigoDojo リポジトリの `lib/core/app_info.dart`）。麻雀道場は、「このソフトについて」と設定 → データからプライバシーポリシーにリンク済み（MahjongDojo リポジトリの `flutter_app/lib/ui/privacy.dart`。日本語以外の表示では `#english` を開く）。特定商取引法に基づく表記（`…/mahjongdojo/tokushoho/`）へは、設定 → データの［特定商取引法に基づく表記］から直接開ける（日本語以外は `#english`）。ポリシーの冒頭からもたどれる。
- 英語道場は `assets/legal/privacy_policy_<言語>.txt`（アプリ内表示、11言語）にも同じ内容があります（2026年11月14日に本リポジトリの `eigodojo/index.md` とそろえました）。ポリシーを変えるときは、両方を同じ内容にしてください。
- 広告・クラッシュ収集・クラウド同期などを追加したら、ポリシーとストア申告を必ず更新する。
