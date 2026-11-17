# SimpleToDoMAX2 プライバシーポリシー

[English](#english) ｜ [アプリ一覧に戻る](../)

- 制定日: 2026年11月7日
- 改定日: 2026年11月17日（アプリ内課金〔広告の非表示〕を廃止。2026年11月13日に広告配信・トラッキングの確認を追加）
- 運営者: KOKOAPPS
- お問い合わせ: kokoapps@outlook.jp
- 対象: Android 版（Google Play）・iOS 版（App Store）

本ポリシーは、ToDo アプリ「SimpleToDoMAX2」（以下「本アプリ」）における利用者情報の取り扱いを定めるものです。

## 1. 基本方針

本アプリには利用者登録・ログインの機能はなく、運営者のサーバーはありません。入力したタスクは利用者の端末内にだけ保存され、運営者が収集することはありません。ただし、広告を表示するため、Google LLC の広告サービス「Google AdMob」を利用しており、これにより一部の情報が Google に送信されます（第5条）。表示する広告はバナー広告だけで、アプリ内課金はありません。アクセス解析・クラッシュ収集のサービスは使用していません。

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
| インターネット通信（Android: INTERNET・ACCESS_NETWORK_STATE、広告 ID の AD_ID） | 広告の表示 | 第5条のとおり Google に送信されます |
| トラッキングの確認（iOS: App Tracking Transparency） | IDFA を広告に使うかの確認 | 第6条 |

各権限は、その機能を使うときにだけ許可を求めます。許可しなくても、その機能以外は使えます。

## 4. 音声入力

音声入力では、OS の音声認識機能（Android は端末の音声認識サービス〔多くの端末で Google〕、iOS は Apple の音声認識）を使います。話した音声は、OS の設定や言語によって、それぞれの提供元のサーバーで文字に変換される場合があります。その取り扱いは Google・Apple のプライバシーポリシーに従います。本アプリが音声を録音・保存・送信することはなく、変換後の文字をタスクの入力欄に入れるだけです。

- Google プライバシーポリシー: <https://policies.google.com/privacy>
- Apple プライバシーポリシー: <https://www.apple.com/legal/privacy/>

## 5. 広告配信のために外部へ送信される情報（外部送信）

| 送信先 | 送信される情報 | 目的 |
|---|---|---|
| Google LLC（Google AdMob / Google Mobile Ads SDK） | 広告識別子（Android の広告 ID、iOS の IDFA。iOS の IDFA は、利用者がトラッキングを許可した場合だけ）、アプリセット ID（Android）、IP アドレス（おおよその位置の推定に使われる場合があります）、端末の機種・OS・言語などの端末情報、アプリの情報、広告の表示・タップの状況、クラッシュなどの診断情報 | 広告の配信・広告のパーソナライズ・効果測定・不正防止・サービス改善 |

- 本アプリは、タスクの内容（タイトル・メモ・完了結果など）を広告 SDK に渡しません。
- 表示する広告は、ホーム画面の下部のバナー広告だけです。広告の内容は、全年齢向け（G）に制限しています。
- 情報は、暗号化された通信（TLS）で Google に送信されます。
- Google は、Google のプライバシーポリシーと、運営者と Google の間の規約（Google 広告のデータ保護規約など）に従って情報を扱います。運営者は、これらの規約により、Google が本ポリシーと同等以上の保護を行うことを確認しています。
- 運営者は、広告 SDK が送信する情報を受け取らず、保存もしません。Google での保存期間は「Google によるデータの保持」（<https://policies.google.com/technologies/retention>）に従います。
- Google のプライバシーポリシー: <https://policies.google.com/privacy>
- Google がパートナーのサイトやアプリからの情報を使用する方法: <https://policies.google.com/technologies/partner-sites>

本条は、日本の電気通信事業法に定める外部送信規律に基づく公表を兼ねます。

## 6. 広告のパーソナライズと同意

- **欧州経済領域（EEA）・英国・スイス**: 初回起動時などに、Google 認定の同意管理ツール（UMP）で広告に関する同意を確認します。広告のパーソナライズは、同意がある場合だけ行われます。同意しない場合も広告が表示されることがありますが、選択に応じて、パーソナライズされない広告や制限付きの広告になります。
- **米国の一部の州**: 設定画面の「広告のプライバシー設定」から、個人情報の「販売・共有」をオプトアウトできます。
- **その他の地域**: 広告は既定でパーソナライズされます。下記の方法で、広告 ID を削除・リセットできます。
- 回答は、設定画面の「広告のプライバシー設定」からいつでも変更・取り消しできます（表示されるのは、上記の同意や選択が必要な地域だけです）。
- **Android**: 端末の設定（「Google」→「広告」など。機種により異なります）で、広告 ID の削除・リセットができます。
- **iOS**: 広告を表示する前に、他社のアプリやウェブサイトをまたいだトラッキングを許可するかを確認するダイアログ（App Tracking Transparency）を表示します。IDFA が広告に使われるのは、許可した場合だけです。許可しない場合、他社のアプリやウェブサイトをまたいだトラッキングは行いません。許可しなくても、本アプリのすべての機能を利用でき、広告も表示されます。許可は iOS の「設定」→「プライバシーとセキュリティ」→「トラッキング」でいつでも変更できます。EEA・英国・スイスで、同意管理ツールの「端末への情報の保存・アクセス」に同意しなかった場合は、このダイアログを表示しません（広告は端末の識別子を使いません）。
- Google のマイ アド センター（Google が保有する情報の確認・削除）: <https://myadcenter.google.com/>
- **EEA・英国・スイスの利用者の方へ**: 広告 SDK による情報の収集については、運営者（KOKOAPPS、kokoapps@outlook.jp）と Google がそれぞれ管理者にあたります。法的根拠は、端末への情報の保存・読み取りとパーソナライズ広告については同意（GDPR 第 6 条 1 項 (a)）、広告の配信・効果測定・不正防止については、同意管理ツールで示す範囲での正当な利益（同 (f)）です。Google LLC（米国）への移転は、Google の規約に定める保護措置（EU-米国データ・プライバシー・フレームワーク、標準契約条項など）に基づきます。利用者には、アクセス、訂正、消去、処理の制限、異議、データポータビリティの権利があり、同意はいつでも撤回できます。お住まいの国のデータ保護監督機関に苦情を申し立てることもできます。

## 7. 第三者提供

利用者が使う OS の機能を通じたもの（第3条・第4条）と第5条の広告配信を除き、本アプリが利用者の情報を外部へ送信したり第三者に提供したりすることはありません。運営者は、第10条のお問い合わせで受け取るものを除き、利用者の情報を保有していません。

## 8. 対象年齢

本アプリは13歳以上の方を対象としており、13歳未満の子どもを対象にしたものではありません。

## 9. 利用者の権利

運営者は、第10条のお問い合わせで受け取るものを除き、利用者の情報を保有していません。端末内のデータは、アプリ内での削除またはアンインストールで消去できます。広告に関する情報は、第6条の方法または Google の窓口から管理できます。

## 10. お問い合わせ時の情報

お問い合わせ（kokoapps@outlook.jp）をいただいた場合、メールアドレスとお問い合わせ内容を回答のためにのみ利用し、必要な期間を過ぎたら削除します。

## 11. 改定

本ポリシーを改定する場合は本ページを更新し、重要な変更はアプリ内またはストアの掲載ページでお知らせします。

---

<a id="english"></a>

# SimpleToDoMAX2 Privacy Policy (English)

[All apps](../)

- Effective date: November 7, 2026
- Last updated: November 17, 2026 (the in-app purchase that removed the ads was discontinued; advertising and the tracking question were added on November 13, 2026)
- Operator: KOKOAPPS
- Contact: kokoapps@outlook.jp
- Applies to: Android (Google Play) and iOS (App Store)

## 1. Overview
SimpleToDoMAX2 ("the App") has no accounts and no servers. Your tasks are stored only on your device and are not collected by the operator. The App shows ads through Google AdMob (Google LLC), which receives some information as described in Section 5. The only ads are banner ads, and the App has no in-app purchases. The App contains no analytics or crash-reporting SDKs.

## 2. Information stored only on your device
Tasks (title, notes, due date, priority, category, repeat and reminder settings, completion results), settings (language, default reminders, auto-delete period, default email recipient), and identifiers of calendar events the App created are stored in a local SQLite database. Completed tasks are deleted automatically after the period you choose; all data is removed when you uninstall the App. Data may be included in OS backups, governed by those providers' terms.

## 3. Device features and permissions
- **Notifications** (POST_NOTIFICATIONS, RECEIVE_BOOT_COMPLETED, SCHEDULE_EXACT_ALARM on Android; notification permission on iOS): local reminders only, nothing is sent.
- **Calendar** (READ/WRITE_CALENDAR; iOS Calendars): adds, updates and deletes events for tasks with due dates in the calendar you choose. The App only modifies events it created. Sync through your calendar account (Google, iCloud, Outlook, etc.) is governed by that service.
- **Microphone and speech recognition**: voice input (see Section 4).
- **Email app**: opens your mail app with a pre-filled subject and body; you send the email yourself.
- **Share (ICS export)**: the file goes only to the destination you choose.
- **Internet access** (INTERNET, ACCESS_NETWORK_STATE and the advertising ID permission AD_ID on Android): used to show ads (see Section 5).
- **Tracking permission** (App Tracking Transparency on iOS): asks whether the IDFA may be used for ads (see Section 6).
Permissions are requested only when you use the related feature; the rest of the App works without them.

## 4. Voice input
Voice input uses your OS speech recognition (the device's recognition service on Android — Google on most devices — and Apple's speech recognition on iOS). Depending on OS settings and language, audio may be processed on the provider's servers under Google's or Apple's privacy policies. The App itself does not record, store or transmit audio; it only inserts the recognized text into the input field.
- Google: <https://policies.google.com/privacy> / Apple: <https://www.apple.com/legal/privacy/>

## 5. Information sent for advertising
Google LLC (Google Mobile Ads SDK) may collect: advertising identifiers (Android advertising ID; the iOS IDFA only if you allow tracking), the app set ID (Android), IP address (may be used to estimate approximate location), device information (model, OS, language), app information, ad impressions and clicks, and diagnostics such as crash data — for ad delivery, ad personalization, measurement, fraud prevention and service improvement.
- The App does not pass the content of your tasks (titles, notes, completion results) to the ads SDK.
- The only ads are banner ads at the bottom of the home screen. Ad content is limited to general audiences (rating "G").
- The information is sent to Google over encrypted connections (TLS).
- Google handles the information under the Google Privacy Policy and the terms between the operator and Google (such as the Google Ads Data Protection Terms). Through these terms the operator has confirmed that Google protects the information at least as well as this policy does.
- The operator does not receive or store the information the ads SDK sends. Google keeps it as described in "How Google retains data we collect" (<https://policies.google.com/technologies/retention>).
- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from sites or apps that use its services: <https://policies.google.com/technologies/partner-sites>

## 6. Personalized ads and consent
- **EEA, UK and Switzerland**: a Google-certified consent tool (UMP) asks for your consent, for example on first launch. Ads are personalized only with your consent. If you do not consent, ads may still be shown, but they are non-personalized or limited according to your choices.
- **Some US states**: you can opt out of the "sale" or "sharing" of personal information under "Ad privacy settings" in Settings.
- **Other regions**: ads are personalized by default. You can delete or reset your advertising ID as described below.
- You can change or withdraw your choices anytime under "Ad privacy settings" in Settings (shown only in the regions above that require consent or a choice).
- **Android**: you can delete or reset your advertising ID in device settings (e.g., Google > Ads; this varies by device).
- **iOS**: before showing ads, the App asks whether you allow tracking across other companies' apps and websites (App Tracking Transparency). The IDFA is used for ads only if you allow it. If you do not, the App does not track you across other companies' apps or websites; you can still use every feature of the App, and ads are still shown. You can change this anytime in iOS Settings > Privacy & Security > Tracking. In the EEA, the UK and Switzerland, the App does not ask if you did not consent to storing or accessing information on your device in the consent tool (ads then use no device identifiers).
- Google My Ad Center (review or delete information Google holds): <https://myadcenter.google.com/>
- **Users in the EEA, the UK and Switzerland**: for the collection by the ads SDK, the operator (KOKOAPPS, kokoapps@outlook.jp) and Google are each controllers. Legal bases: consent (Art. 6(1)(a) GDPR) for storing and reading information on your device and for personalized ads; legitimate interests (Art. 6(1)(f) GDPR) for serving ads, measurement and fraud prevention, to the extent shown in the consent tool. Transfers to Google LLC (United States) rely on the safeguards in Google's terms (the EU-U.S. Data Privacy Framework, standard contractual clauses, etc.). You have the rights of access, rectification, erasure, restriction, objection and data portability, and you can withdraw your consent at any time. You can also lodge a complaint with your data protection authority.

## 7. Sharing with third parties
Apart from the OS features described above that you choose to use (Sections 3 and 4) and the advertising described in Section 5, the App does not send your information outside the device or share it with third parties. Except for your inquiries in Section 10, the operator holds no information about you.

## 8. Children
The App is intended for users aged 13 and over and is not directed at children under 13.

## 9. Your rights
Except for your inquiries in Section 10, the operator holds no information about you. You can erase on-device data within the App or by uninstalling it. Advertising data can be managed as described in Section 6 or via Google.

## 10. Contacting us
If you contact us (kokoapps@outlook.jp), your email address and message are used only to reply and are deleted when no longer needed.

## 11. Changes
We will update this page when this policy changes and announce significant changes in the App or on the store listing.
