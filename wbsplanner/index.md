# WBS Planner プライバシーポリシー

[English](#english) ｜ [アプリ一覧に戻る](../)

- 制定日: 2026年11月7日
- 運営者: 【運営者名】
- お問い合わせ: 【連絡先メールアドレス】
- 対象: Android 版（Google Play）・iOS 版（App Store）

本ポリシーは、スケジュール作成アプリ「WBS Planner」（以下「本アプリ」）における利用者情報の取り扱いを定めるものです。

## 1. 基本方針

本アプリには利用者登録・ログインの機能はなく、運営者のサーバーはありません。本アプリはインターネット通信を行わず、入力したデータは利用者の端末内にだけ保存されます。広告・アクセス解析・クラッシュ収集のサービスは使用していません。

## 2. 端末内にだけ保存する情報

| 情報 | 目的 |
|---|---|
| プロジェクト・ゴール・タスク・依存関係・工数・進捗・メモ | WBS・スケジュール・クリティカルパスの算出 |
| 担当者（利用者が入力した名前・役割・稼働率・休暇日・表示色） | 割り当て・負荷の算出 |
| 会社休日・カレンダー連携の設定・表示設定・アプリロックの設定 | アプリの動作 |
| 端末カレンダーに作成した予定の識別子 | 予定の更新・削除 |

データは端末内のデータベース（SQLite）に保存されます。Android 版では OS のバックアップ・端末間の移行の対象外に設定しています。アンインストールすると削除されます。

担当者として他の方の名前等を入力する場合は、その方の了解を得たうえで、必要な範囲でご利用ください。

## 3. 端末の機能・権限の利用

| 機能・権限 | 目的 | 情報の扱い |
|---|---|---|
| カレンダー（Android: READ_CALENDAR / WRITE_CALENDAR ／ iOS: カレンダー） | 作成したスケジュールを、利用者が選んだ端末のカレンダーに登録・更新する。カレンダーから休日を読み込む | 本アプリが作成した予定だけを更新・削除します。読み込んだ予定は休日の登録にのみ使い、外部送信しません。カレンダーのアカウントを通じた同期は各サービスの規約に従います |
| 生体認証（Android: USE_BIOMETRIC ／ iOS: Face ID・Touch ID） | アプリのロック解除（任意） | 認証は OS が行い、本アプリが受け取るのは成功・失敗の結果だけです。指紋・顔のデータを取得・保存することはありません |
| ファイル選択 | バックアップ・プロジェクトの JSON の読み込み | 利用者が選んだファイルだけを読み込みます |
| 共有（Excel・CSV・JSON の出力、バックアップ） | データの書き出し | 利用者が選んだ共有先（メール・クラウドストレージ等）にのみ渡され、その後の扱いは共有先の規約に従います |

各権限は、その機能を使うときにだけ許可を求めます。許可しなくても、その機能以外は使えます。

## 4. 外部送信・第三者提供

本アプリが利用者の情報を外部へ送信したり、第三者に提供したりすることはありません。

## 5. 対象年齢

本アプリは13歳未満の子どもを対象にしたものではありません。なお、本アプリはどなたの情報も収集しません。

## 6. 利用者の権利

運営者は利用者の情報を保有していないため、開示・訂正・削除の対象となる情報はありません。端末内のデータは、アプリ内での削除またはアンインストールで消去できます。

## 7. お問い合わせ時の情報

お問い合わせいただいた場合、メールアドレスとお問い合わせ内容を回答のためにのみ利用し、必要な期間を過ぎたら削除します。

## 8. 改定

本ポリシーを改定する場合は本ページを更新し、重要な変更はアプリ内またはストアの掲載ページでお知らせします。

---

<a id="english"></a>

# WBS Planner Privacy Policy (English)

- Effective date: November 7, 2026
- Operator: [Operator name]
- Contact: [Contact email]
- Applies to: Android (Google Play) and iOS (App Store)

## 1. Overview
WBS Planner ("the App") has no accounts and no servers, does not use the internet, and stores your data only on your device. It contains no advertising, analytics or crash-reporting SDKs.

## 2. Information stored only on your device
Projects, goals, tasks, dependencies, effort, progress and notes; members you enter (name, role, availability, days off, color); company holidays and app settings including app lock; and identifiers of calendar events the App created. Data is kept in a local SQLite database. On Android, the App is excluded from OS backup and device-to-device transfer. Uninstalling the App deletes the data. If you enter other people as members, please do so with their consent and only as needed.

## 3. Device features and permissions
- **Calendar** (READ/WRITE_CALENDAR; iOS Calendars): registers and updates your schedule in the calendar you choose and reads holidays from a calendar. The App only updates or deletes events it created; events it reads are used only to register holidays and are never transmitted.
- **Biometrics** (USE_BIOMETRIC; Face ID / Touch ID): optional app lock. Authentication is performed by the OS; the App only receives success or failure and never accesses fingerprint or face data.
- **File picker**: reads only the backup/JSON file you select.
- **Share** (Excel, CSV, JSON, backup): files go only to the destination you choose, governed by that destination's terms.
Permissions are requested only when you use the related feature.

## 4. Transmission and sharing
The App does not send your information outside the device or share it with third parties.

## 5. Children
The App is not directed at children under 13. The App does not collect anyone's information.

## 6. Your rights
The operator holds no information about you. You can erase on-device data within the App or by uninstalling it.

## 7. Contacting us
If you contact us, your email address and message are used only to reply and are deleted when no longer needed.

## 8. Changes
We will update this page when this policy changes and announce significant changes in the App or on the store listing.
