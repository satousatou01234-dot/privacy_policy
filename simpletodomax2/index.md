# SimpleToDoMAX2 プライバシーポリシー

[English](#english) ｜ [アプリ一覧に戻る](../)

- 制定日: 2026年11月7日
- 運営者: 【運営者名】
- お問い合わせ: 【連絡先メールアドレス】
- 対象: Android 版（Google Play）・iOS 版（App Store）

本ポリシーは、ToDo アプリ「SimpleToDoMAX2」（以下「本アプリ」）における利用者情報の取り扱いを定めるものです。

## 1. 基本方針

本アプリには利用者登録・ログインの機能はなく、運営者のサーバーはありません。入力したタスクは利用者の端末内にだけ保存され、運営者が収集することはありません。本アプリは広告・アクセス解析・クラッシュ収集のサービスを使用していません。

## 2. 端末内にだけ保存する情報

| 情報 | 目的 |
|---|---|
| タスク（タイトル・メモ・期限・重要度・属性・繰り返し・通知の設定・完了結果） | ToDo の管理・通知 |
| 設定（言語・既定の通知・自動削除の日数・メールの既定の宛先など） | アプリの動作 |
| 端末カレンダーに作成した予定の識別子 | 予定の更新・削除 |

データは端末内のデータベース（SQLite）に保存されます。完了から設定日数を過ぎたタスクは自動で削除され、アンインストールですべて削除されます。OS のバックアップ機能の対象になる場合があり、その取り扱いは各社の規約に従います。

## 3. 端末の機能・権限の利用

| 機能・権限 | 目的 | 情報の扱い |
|---|---|---|
| 通知（Android: POST_NOTIFICATIONS、起動時の再予約 RECEIVE_BOOT_COMPLETED、正確なアラーム SCHEDULE_EXACT_ALARM ／ iOS: 通知の許可） | 期限のリマインド | 端末内の予約通知。外部送信なし |
| カレンダー（Android: READ_CALENDAR / WRITE_CALENDAR ／ iOS: カレンダー） | 期限付きタスクを、利用者が選んだ端末のカレンダーに予定として追加・更新・削除 | 本アプリが作成した予定のみ操作します。カレンダーのアカウント（Google・iCloud・Outlook など）を通じた同期は、各カレンダーサービスの規約に従います |
| マイク・音声認識（Android: RECORD_AUDIO ／ iOS: マイク・音声認識） | 音声でタスクを入力 | 下記第4条 |
| メールアプリの起動 | 完了結果をメールで送信 | 件名・本文を入れた状態で端末のメールアプリを開くだけで、送信は利用者がメールアプリで行います |
| 共有（ICS ファイルの書き出し） | 他のカレンダーアプリへの取り込み | 利用者が選んだ共有先にのみ渡されます |

各権限は、その機能を使うときにだけ許可を求めます。許可しなくても、その機能以外は使えます。

## 4. 音声入力

音声入力では、OS の音声認識機能（Android は端末の音声認識サービス〔多くの端末で Google〕、iOS は Apple の音声認識）を使います。話した音声は、OS の設定や言語によって、それぞれの提供元のサーバーで文字に変換される場合があります。その取り扱いは Google・Apple のプライバシーポリシーに従います。本アプリが音声を録音・保存・送信することはなく、変換後の文字をタスクの入力欄に入れるだけです。

- Google プライバシーポリシー: <https://policies.google.com/privacy>
- Apple プライバシーポリシー: <https://www.apple.com/legal/privacy/>

## 5. 外部送信・第三者提供

第3条・第4条のとおり、利用者が使う OS の機能を通じたものを除き、本アプリが利用者の情報を外部へ送信したり第三者に提供したりすることはありません。

## 6. 対象年齢

本アプリは13歳未満の子どもを対象にしたものではありません。なお、本アプリはどなたの情報も収集しません。

## 7. 利用者の権利

運営者は利用者の情報を保有していないため、開示・訂正・削除の対象となる情報はありません。端末内のデータは、アプリ内での削除またはアンインストールで消去できます。

## 8. お問い合わせ時の情報

お問い合わせいただいた場合、メールアドレスとお問い合わせ内容を回答のためにのみ利用し、必要な期間を過ぎたら削除します。

## 9. 改定

本ポリシーを改定する場合は本ページを更新し、重要な変更はアプリ内またはストアの掲載ページでお知らせします。

---

<a id="english"></a>

# SimpleToDoMAX2 Privacy Policy (English)

- Effective date: November 7, 2026
- Operator: [Operator name]
- Contact: [Contact email]
- Applies to: Android (Google Play) and iOS (App Store)

## 1. Overview
SimpleToDoMAX2 ("the App") has no accounts and no servers. Your tasks are stored only on your device and are not collected by the operator. The App contains no advertising, analytics or crash-reporting SDKs.

## 2. Information stored only on your device
Tasks (title, notes, due date, priority, category, repeat and reminder settings, completion results), settings (language, default reminders, auto-delete period, default email recipient) and identifiers of calendar events the App created are stored in a local SQLite database. Completed tasks are deleted automatically after the period you choose; all data is removed when you uninstall the App. Data may be included in OS backups, governed by those providers' terms.

## 3. Device features and permissions
- **Notifications** (POST_NOTIFICATIONS, RECEIVE_BOOT_COMPLETED, SCHEDULE_EXACT_ALARM on Android; notification permission on iOS): local reminders only, nothing is sent.
- **Calendar** (READ/WRITE_CALENDAR; iOS Calendars): adds, updates and deletes events for tasks with due dates in the calendar you choose. The App only modifies events it created. Sync through your calendar account (Google, iCloud, Outlook, etc.) is governed by that service.
- **Microphone and speech recognition**: voice input (see Section 4).
- **Email app**: opens your mail app with a pre-filled subject and body; you send the email yourself.
- **Share (ICS export)**: the file goes only to the destination you choose.
Permissions are requested only when you use the related feature; the rest of the App works without them.

## 4. Voice input
Voice input uses your OS speech recognition (the device's recognition service on Android — Google on most devices — and Apple's speech recognition on iOS). Depending on OS settings and language, audio may be processed on the provider's servers under Google's or Apple's privacy policies. The App itself does not record, store or transmit audio; it only inserts the recognized text into the input field.
- Google: <https://policies.google.com/privacy> / Apple: <https://www.apple.com/legal/privacy/>

## 5. Transmission and sharing
Apart from the OS features described above that you choose to use, the App does not send your information outside the device or share it with third parties.

## 6. Children
The App is not directed at children under 13. The App does not collect anyone's information.

## 7. Your rights
The operator holds no information about you. You can erase on-device data within the App or by uninstalling it.

## 8. Contacting us
If you contact us, your email address and message are used only to reply and are deleted when no longer needed.

## 9. Changes
We will update this page when this policy changes and announce significant changes in the App or on the store listing.
