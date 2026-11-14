# WBS Planner プライバシーポリシー

[English](#english) ｜ [特定商取引法に基づく表記](tokushoho/) ｜ [アプリ一覧に戻る](../)

- 制定日: 2026年11月7日
- 改定日: 2026年11月14日（広告配信と同意管理、アプリ内課金（広告の非表示）、メールの作成、担当者のメールアドレス・単価、予算・実績を追加）
- 運営者: KOKOAPPS
- お問い合わせ: kokoapps@outlook.jp
- 対象: Android 版（Google Play）・iOS 版（App Store）

本ポリシーは、スケジュール作成アプリ「WBS Planner」（以下「本アプリ」）における利用者情報の取り扱いを定めるものです。

## 1. 基本方針

本アプリには利用者登録・ログインの機能はなく、運営者のサーバーもありません。利用者が入力したデータ（プロジェクト・タスク・担当者など）は利用者の端末内にだけ保存され、運営者や第三者に送信されることはありません。

ただし、本アプリは無料で提供するために、Google LLC の広告サービス「Google AdMob」を利用しています。広告の表示に伴い、端末やアプリの利用に関する一部の情報が Google に送信されます（第4条）。広告は、アプリ内課金で非表示にできます（第6条）。アクセス解析・クラッシュ収集のサービスは使用していません。

## 2. 端末内にだけ保存する情報

| 情報 | 目的 |
|---|---|
| プロジェクト・ゴール・タスク・依存関係・工数・バッファ・進捗・実績・メモ・予算 | WBS・スケジュール・クリティカルパス・コストの算出 |
| 担当者（利用者が入力した名前・役割・稼働率・休暇日・表示色・メールアドレス・単価） | 割り当て・負荷・コストの算出、メールの宛先の候補 |
| 会社休日（繰り返しの休日を含む）・カレンダー連携の設定・表示設定・通貨・アプリロックの設定 | アプリの動作 |
| 端末カレンダーに作成した予定の識別子 | 予定の更新・削除 |
| 広告の同意の状態（同意管理ツールが保存するもの） | 同意の内容に従って広告を表示するため |
| 広告の非表示を購入済みかどうか | 購入した利用者に広告を表示しないため（第6条） |

データは端末内のデータベース（SQLite）に保存されます。Android 版では OS のバックアップ・端末間の移行の対象外に設定しています。iOS 版では、利用者が iCloud バックアップやパソコン（Finder・iTunes）へのバックアップを有効にしている場合、他のアプリのデータと同様にこのデータベースもそのバックアップに含まれ、復元した端末に戻ります（バックアップは利用者のアカウントで Apple の仕組みにより管理され、運営者は受け取りません）。本アプリの JSON バックアップのファイルには、購入済みかどうかの情報は含まれません。

アンインストールすると端末内のデータは削除されます。ただし、本アプリが端末のカレンダーに作成した予定はカレンダー側のデータのため、アンインストール後も残ります（カレンダーのアカウントで同期している場合は同期先にも残ります）。不要な場合は、アンインストールの前に本アプリのカレンダー連携をオフにして予定を削除するか、カレンダーアプリで削除してください。

担当者として他の方の名前・メールアドレス・単価等を入力する場合は、その方の了解を得たうえで、必要な範囲でご利用ください。単価・予算は機密情報になり得るため、端末の管理（画面ロック・本アプリの生体認証ロック等）にご注意ください。

## 3. 端末の機能・権限の利用

| 機能・権限 | 目的 | 情報の扱い |
|---|---|---|
| カレンダー（Android: READ_CALENDAR / WRITE_CALENDAR ／ iOS: カレンダー） | 作成したスケジュールを、利用者が選んだ端末のカレンダーに登録・更新する。カレンダーから休日を読み込む | 本アプリが作成した予定だけを更新・削除します。読み込んだ予定は休日の登録にのみ使い、外部送信しません。カレンダーのアカウントを通じた同期は各サービスの規約に従います |
| 生体認証（Android: USE_BIOMETRIC ／ iOS: Face ID・Touch ID） | アプリのロック解除（任意） | 認証は OS が行い、本アプリが受け取るのは成功・失敗の結果だけです。指紋・顔のデータを取得・保存することはありません |
| ファイル選択 | バックアップ・プロジェクトの JSON の読み込み | 利用者が選んだファイルだけを読み込みます |
| 共有（Excel・CSV・JSON の出力、バックアップ） | データの書き出し | 利用者が選んだ共有先（メール・クラウドストレージ等）にのみ渡され、その後の扱いは共有先の規約に従います。出力・バックアップのファイルには、担当者のメールアドレス・単価・予算・コストなども含まれる場合があります |
| メールの作成（出力ファイルの送信・担当者へのメール・進捗レポート） | 利用者がメールを送るための下書きの作成 | 件名・本文・添付ファイル・宛先（利用者が担当者のメールアドレスから選んだもの）を、利用者が選んだメールアプリ（使えない場合は共有シート）に渡すだけで、本アプリ自身がメールを送信したり、内容を運営者に送ったりすることはありません。送信するかどうかは利用者がメールアプリで決め、その後の扱いはメールのサービスの規約に従います。添付ファイルを渡すため、端末内のアプリ専用の一時領域にファイルのコピーを作成することがあります |
| インターネット通信（Android: INTERNET・ACCESS_NETWORK_STATE、広告 ID の AD_ID など） | 広告の表示と、広告に関する同意の管理（第4条・第5条）、各ストアへの購入の確認（第6条） | 本アプリが入力データを送信するために使うことはありません |
| アプリ内課金（Android: BILLING ／ iOS: App 内課金） | 広告の非表示の購入・復元 | 第6条のとおり、決済は各ストアが処理します |

各権限は、その機能を使うときにだけ許可を求めます（インターネット・アプリ内課金は許可の確認がない権限です）。許可しなくても、その機能以外は使えます。

## 4. 広告配信のために外部へ送信される情報（外部送信）

| 送信先 | 送信される情報 | 目的 |
|---|---|---|
| Google LLC（Google AdMob。Google Mobile Ads SDK・User Messaging Platform SDK） | IP アドレス（おおよその位置の推定に使われる場合があります）、広告識別子などの端末の識別子（Android の広告 ID・アプリセット ID など。iOS ではトラッキングの許可を求めないため IDFA は使われません）、端末の機種・OS・言語などの端末情報、アプリの情報、広告の表示・タップなどの操作の情報、アプリの起動時間などの性能やクラッシュに関する診断情報、広告に関する同意の状態 | 広告の配信・効果測定・不正防止・分析・サービス改善、同意の内容に従った広告の配信 |

- 本アプリが、利用者が入力したデータ（プロジェクト・タスク・担当者の名前・メールアドレス・単価・予算など）を Google に送信することはありません。
- Android 版では、端末が対応し利用者が許可している場合に、Android の広告関連の機能（広告 ID・プライバシー サンドボックスの Topics API やアトリビューション レポートなど）が広告 SDK によって使われることがあります。
- 広告の内容は「PG」（保護者の指導のもとで子どもも見られる）相当以下に制限しています。
- 第6条の購入をストアで確認できた後は、本アプリは広告 SDK を使用せず、本条の送信も行いません。再インストールの直後や新しい端末で最初に起動したときなどに、ストアでの確認が間に合わない場合は、確認できるまでの間、広告の表示と送信が行われることがあります。
- 情報は、暗号化された通信（TLS）で Google に送信されます。
- Google は、Google のプライバシーポリシーと、運営者と Google の間の規約（Google 広告のデータ保護規約など）に従って情報を扱います。運営者は、これらの規約により、Google が本ポリシーと同等以上の保護を行うことを確認しています。
- 運営者は、広告 SDK が送信する情報を受け取らず、保存もしません。Google での保存期間は「Google によるデータの保持」（<https://policies.google.com/technologies/retention>）に従います。
- Google のプライバシーポリシー: <https://policies.google.com/privacy>
- Google がパートナーのサイトやアプリからの情報を使用する方法: <https://policies.google.com/technologies/partner-sites>

本条は、日本の電気通信事業法に定める外部送信規律に基づく公表を兼ねます。

## 5. 広告のパーソナライズと同意

- **欧州経済領域（EEA）・英国・スイス**: 初回起動時などに、Google 認定の同意管理ツール（User Messaging Platform）で広告に関する同意を確認します。広告のパーソナライズは、同意がある場合だけ行われます。同意しない場合も広告が表示されることがありますが、選択に応じて、パーソナライズされない広告や制限付きの広告になります。
- **米国の一部の州など、法令により選択の機会が必要な地域**: 設定画面の「広告のプライバシー設定」から、個人情報の「販売・共有」のオプトアウトなどを選択できます。
- 回答は、設定画面の「広告のプライバシー設定」からいつでも変更・取り消しできます（表示されるのは、上記の同意や選択が必要な地域だけです）。
- **Android**: 端末の設定（「プライバシー」→「広告」など。機種により異なります）で、広告 ID の削除・リセットや、広告に関する機能の設定ができます。
- **iOS**: 本アプリは App Tracking Transparency による許可を求めず、他社のアプリやウェブサイトをまたいだトラッキングは行いません。
- Google のマイ アド センター（Google が保有する情報の確認・削除）: <https://myadcenter.google.com/>
- 同意画面・設定は Google の同意管理ツールが表示するもので、同意の内容は端末内に保存され、広告のリクエスト時に Google に送られます。生体認証ロックを有効にしている場合、同意画面はロックを解除した後に表示します。
- **EEA・英国・スイスの利用者の方へ**: 広告 SDK による情報の収集については、運営者（KOKOAPPS、kokoapps@outlook.jp）と Google がそれぞれ管理者にあたります。法的根拠は、端末への情報の保存・読み取りとパーソナライズ広告については同意（GDPR 第 6 条 1 項 (a)）、広告の配信・効果測定・不正防止については、同意管理ツールで示す範囲での正当な利益（同 (f)）です。Google LLC（米国）への移転は、Google の規約に定める保護措置（EU-米国データ・プライバシー・フレームワーク、標準契約条項など）に基づきます。利用者には、アクセス、訂正、消去、処理の制限、異議、データポータビリティの権利があり、同意はいつでも撤回できます。お住まいの国のデータ保護監督機関に苦情を申し立てることもできます。

## 6. アプリ内課金（広告の非表示）

本アプリは、広告を非表示にする機能（1 回払いの買い切り）を、App Store または Google Play のアプリ内課金で販売しています。販売の条件は「[特定商取引法に基づく表記](tokushoho/)」をご覧ください。

- 支払いは各ストア（Apple Inc.、Google LLC）が処理します。運営者は、支払い方法などの決済情報を取得しません。決済情報は、各ストアのプライバシーポリシーに従って扱われます。
- 本アプリは、購入済みかどうかを端末内に保存します。購入の確認と復元のため、端末から各ストアに問い合わせます（Android 版は起動時と「購入を復元」の操作時、iOS 版は購入時と「購入を復元」の操作時）。購入の情報を運営者のサーバーに送信することはありません。
- 運営者は、各ストアから売上の報告として、注文番号・国・金額などの情報を受け取ることがあります。これらは、売上の管理とお問い合わせへの対応のためだけに使います。
- 購入をストアで確認できた後は、本アプリは広告 SDK を使用せず、広告の同意の確認も表示しません。確認が間に合わない場合（第4条）は、確認できるまでの間、これらが表示されることがあります。
- 購入の復元は、購入したときと同じストア（App Store または Google Play）の同じアカウントで行えます。Android と iPhone の間では引き継げません。

## 7. 第三者提供

第4条の広告配信、第6条の各ストアによる決済、第3条で利用者が選んだ共有先・メールアプリへの受け渡しを除き、本アプリが利用者の情報を外部へ送信したり第三者に提供したりすることはありません。運営者は、第6条の売上の報告と第11条のお問い合わせで受け取るものを除き、利用者の情報を保有していません。

## 8. 対象年齢

本アプリは13歳以上の方を対象としており、13歳未満の子どもを対象にしたものではありません。

## 9. 利用者の権利

運営者は、第6条の売上の報告と第11条のお問い合わせで受け取るものを除き、利用者の情報を保有していません。端末内のデータは、アプリ内での削除またはアンインストールで消去できます。広告に関する情報は、第5条の方法または Google の窓口から管理できます。購入の履歴は、各ストア（Apple、Google）のアカウントの画面で確認できます。

## 10. このページについて

本ページは GitHub Pages で公開しており、本アプリの設定画面のリンクから、端末のブラウザで開きます。ページの閲覧には GitHub のプライバシーに関する声明が適用されます。

## 11. お問い合わせ時の情報

お問い合わせ（kokoapps@outlook.jp）をいただいた場合、メールアドレスとお問い合わせ内容を回答のためにのみ利用し、必要な期間を過ぎたら削除します。

## 12. 改定

本ポリシーを改定する場合は本ページを更新し、重要な変更はアプリ内またはストアの掲載ページでお知らせします。

- 2026年11月7日: 制定
- 2026年11月14日: 広告（Google AdMob）と同意管理、アプリ内課金（広告の非表示）、メールの作成、担当者のメールアドレス・単価、予算・実績に合わせて改定

---

<a id="english"></a>

# WBS Planner Privacy Policy (English)

[Legal notice](tokushoho/#english) ｜ [All apps](../)

- Effective date: November 7, 2026
- Last updated: November 14, 2026 (added advertising and consent management, the in-app purchase to remove the ads, email drafts, members' email addresses and cost rates, and budgets/actuals)
- Operator: KOKOAPPS
- Contact: kokoapps@outlook.jp
- Applies to: Android (Google Play) and iOS (App Store)

## 1. Overview
WBS Planner ("the App") has no accounts and no servers of its own. The data you enter (projects, tasks, members, etc.) is stored only on your device and is never sent to the operator or to third parties. To keep the App free, it shows ads through Google AdMob (Google LLC), which receives some information about your device and your use of the App as described in Section 4. You can remove the ads with an in-app purchase (Section 6). The App contains no analytics or crash-reporting services.

## 2. Information stored only on your device
- Projects, goals, tasks, dependencies, effort, buffers, progress, actuals, notes and budgets.
- Members you enter: name, role, availability, days off, color, email address and cost rate.
- Company holidays (including recurring ones), calendar-sync settings, display settings, currency and app-lock settings.
- Identifiers of calendar events the App created, the ad-consent status saved by the consent tool, and whether you have bought the removal of the ads (Section 6).

Data is kept in a local SQLite database. On Android, the App is excluded from OS backup and device-to-device transfer. On iOS, if you have turned on iCloud Backup or backups to a computer (Finder or iTunes), this database is included in those backups like other app data and comes back when you restore a device (the backups are managed by Apple under your account; the operator never receives them). The App's own JSON backup files do not include whether you have bought the removal of the ads.

Uninstalling the App deletes the data on the device. However, calendar events the App created belong to your calendar, so they remain after you uninstall the App (and in any calendar account they sync to). If you no longer need them, turn off calendar sync in the App to remove them before uninstalling, or delete them in your calendar app. If you enter other people as members (including their email addresses or cost rates), please do so with their consent and only as needed. Cost rates and budgets may be confidential; please protect your device (screen lock, the App's biometric lock, etc.).

## 3. Device features and permissions
- **Calendar** (READ/WRITE_CALENDAR; iOS Calendars): registers and updates your schedule in the calendar you choose and reads holidays from a calendar. The App only updates or deletes events it created; events it reads are used only to register holidays and are never transmitted.
- **Biometrics** (USE_BIOMETRIC; Face ID / Touch ID): optional app lock. Authentication is performed by the OS; the App only receives success or failure and never accesses fingerprint or face data.
- **File picker**: reads only the backup/JSON file you select.
- **Share** (Excel, CSV, JSON, backup): files go only to the destination you choose, governed by that destination's terms. Exported files and backups may include members' email addresses, cost rates, budgets and costs.
- **Email drafts** (sending exported files, emailing members, progress reports): the App only hands the subject, body, attachments and the recipients you pick from your members' email addresses to the mail app you choose (or the share sheet if no mail app is available). The App never sends email by itself or sends the content to the operator; you decide in your mail app whether to send it. To pass attachments, the App may create temporary copies of the files in its private storage on the device.
- **Internet** (Android INTERNET, ACCESS_NETWORK_STATE, the advertising-ID permission AD_ID, etc.): used only for ads and ad consent (Sections 4 and 5) and for checking purchases with the stores (Section 6), never to send the data you enter.
- **In-app purchase** (Android BILLING; iOS In-App Purchase): buying and restoring the removal of the ads; payments are processed by the stores (Section 6).

Permissions are requested only when you use the related feature (internet and in-app purchase need no prompt). If you decline, everything else still works.

## 4. Information sent for advertising (external transmission)
Google LLC (Google AdMob: Google Mobile Ads SDK and User Messaging Platform SDK) may receive: IP address (may be used to estimate approximate location); device identifiers such as advertising identifiers (Android advertising ID, app set ID, etc.; on iOS the IDFA is not used because the App does not request tracking permission); device information (model, OS, language); app information; ad impressions, taps and other interactions; diagnostics such as app launch time, performance and crash data; and your ad-consent status — for ad delivery, measurement, fraud prevention, analytics, service improvement and serving ads according to your consent choices.
- The App never sends the data you enter (projects, tasks, members' names, email addresses, cost rates, budgets, etc.) to Google.
- On Android, where supported and allowed by you, the ads SDK may use Android's advertising features (advertising ID, Privacy Sandbox Topics API, attribution reporting, etc.).
- Ad content is limited to rating "PG" or lower.
- Once the store has confirmed the purchase in Section 6, the App no longer uses the ads SDK and sends nothing described in this section. Right after reinstalling or on the first launch on a new device, if the store cannot confirm the purchase in time, ads may be shown and this information sent until it does.
- The information is sent to Google over encrypted connections (TLS).
- Google handles the information under its privacy policy and the terms between the operator and Google (such as the Google Ads Data Processing Terms); through these terms the operator has confirmed that Google provides protection at least equivalent to this policy.
- The operator neither receives nor stores the information sent by the ads SDK. Google's retention follows "How Google retains data we collect" (<https://policies.google.com/technologies/retention>).
- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from sites or apps that use its services: <https://policies.google.com/technologies/partner-sites>

This section also serves as the public notice required by Japan's Telecommunications Business Act regarding external transmission of user information.

## 5. Personalized ads and consent
- **EEA, UK and Switzerland**: a Google-certified consent tool (User Messaging Platform) asks for your consent, for example on first launch. Ads are personalized only with your consent. If you do not consent, ads may still be shown, but they are non-personalized or limited according to your choices.
- **Certain US states and other regions where the law requires a choice**: you can opt out of the "sale" or "sharing" of personal information and make other choices under "Ad privacy settings" in Settings.
- You can change or withdraw your choices anytime under "Ad privacy settings" in Settings (shown only in the regions above that require consent or a choice).
- **Android**: you can delete or reset your advertising ID and manage ad-related features in device settings (e.g., Privacy > Ads; this varies by device).
- **iOS**: the App does not request App Tracking Transparency permission and does not track you across other companies' apps or websites.
- Google My Ad Center (review or delete information Google holds): <https://myadcenter.google.com/>
- The consent form and settings are provided by Google's consent tool; your choice is stored on the device and sent to Google with ad requests. If the App's biometric lock is enabled, the consent form is shown after you unlock the App.
- **Users in the EEA, the UK and Switzerland**: for the collection by the ads SDK, the operator (KOKOAPPS, kokoapps@outlook.jp) and Google are each controllers. Legal bases: consent (Art. 6(1)(a) GDPR) for storing and reading information on your device and for personalized ads; legitimate interests (Art. 6(1)(f) GDPR) for serving ads, measurement and fraud prevention, to the extent shown in the consent tool. Transfers to Google LLC (United States) rely on the safeguards in Google's terms (the EU-U.S. Data Privacy Framework, standard contractual clauses, etc.). You have the rights of access, rectification, erasure, restriction, objection and data portability, and you can withdraw your consent at any time. You can also lodge a complaint with your data protection authority.

## 6. In-app purchase (removing the ads)
The App sells the removal of the ads (a one-time purchase) through in-app purchases on the App Store or Google Play. For the terms of sale, see the [legal notice](tokushoho/#english).
- Payments are processed by the stores (Apple Inc., Google LLC). The operator does not receive payment information such as your payment method; the stores handle it under their privacy policies.
- The App stores on your device whether you have bought the removal. To check and restore the purchase, it asks the store from your device (on Android when it starts and when you tap "Restore purchases"; on iOS when you buy and when you tap "Restore purchases"). Nothing about the purchase is sent to the operator's servers.
- The stores may send the operator sales reports with information such as order numbers, countries and amounts. They are used only to manage sales and to answer your inquiries.
- Once the store has confirmed the purchase, the App no longer uses the ads SDK and no longer shows the ad consent form. If the store cannot confirm it in time (Section 4), they may appear until it does.
- The purchase can be restored with the same account of the store you bought it from (App Store or Google Play). It does not carry over between Android and iPhone.

## 7. Sharing with third parties
Apart from the advertising described in Section 4, the payments processed by the stores described in Section 6 and the hand-off to the share destinations and mail apps you choose (Section 3), the App does not send your information outside the device or share it with third parties. Except for the sales reports in Section 6 and your inquiries in Section 11, the operator holds no information about you.

## 8. Children
The App is intended for users aged 13 and over and is not directed at children under 13.

## 9. Your rights
Except for the sales reports in Section 6 and your inquiries in Section 11, the operator holds no information about you. You can erase on-device data within the App or by uninstalling it. Advertising data can be managed as described in Section 5 or via Google. Your purchase history is available in your store account (Apple or Google).

## 10. This page
This page is hosted on GitHub Pages and opens in your browser from the link in the App's Settings. GitHub's privacy statement applies to viewing the page.

## 11. Contacting us
If you contact us (kokoapps@outlook.jp), your email address and message are used only to reply and are deleted when no longer needed.

## 12. Changes
We will update this page when this policy changes and announce significant changes in the App or on the store listing.
- November 7, 2026: established.
- November 14, 2026: revised for ads (Google AdMob) and consent management, the in-app purchase to remove the ads, email drafts, members' email addresses and cost rates, and budgets/actuals.
