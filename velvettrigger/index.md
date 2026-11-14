# VELVET TRIGGER プライバシーポリシー

[English](#english) ｜ [特定商取引法に基づく表記](tokushoho/) ｜ [アプリ一覧に戻る](../)

- 制定日: 2026年11月7日
- 改定日: 2026年11月14日（広告配信、補給〔リワード広告〕、アプリ内課金〔広告の非表示〕を追加）
- 運営者: KOKOAPPS
- お問い合わせ: kokoapps@outlook.jp
- 対象: Android 版（Google Play）・iOS 版（App Store）

本ポリシーは、ゲームアプリ「VELVET TRIGGER」（以下「本アプリ」）における利用者情報の取り扱いを定めるものです。

## 1. 基本方針

本アプリには利用者登録・ログインの機能はなく、運営者のサーバーはありません。運営者が利用者の情報を収集することはありません。ただし、広告を表示するため、Google LLC の広告サービス「Google AdMob」を利用しており、これにより一部の情報が Google に送信されます（第3条）。バナーと全画面広告は、アプリ内課金で非表示にできます（補給の広告は購入後も選んで見られます。第6条）。アクセス解析・クラッシュ収集のサービスは使用していません。

本アプリがインターネット通信を行うのは、広告の配信、広告のための同意の確認（第4条）、アプリ内課金の購入・確認・復元（第6条）のためだけです。

## 2. 端末内にだけ保存する情報

| 情報 | 目的 |
|---|---|
| 設定（言語・照準の操作方法と感度・ピンチでの倍率変更・音量・ボイス・振動・カットイン演出など） | アプリの動作 |
| 進行状況（クリアしたミッション、ミッションごとのベストスコアと評価） | ゲームの進行 |
| 補給（リワード広告）を受け取った回数（装弾数の追加・リロードの速さ） | 補給の内容をゲームに反映するため（第3条） |
| 広告の非表示を購入済みかどうか | 購入した利用者に、バナーと全画面広告を表示しないため（第6条） |

これらは端末内（Android: SharedPreferences ／ iOS: UserDefaults）に保存され、運営者に送信されません。アンインストールで削除され、設定画面の「進行状況をリセット」でベストスコアを消去できます。OS のバックアップ機能（Google のバックアップ、iCloud バックアップ）の対象になる場合があり、その取り扱いは各社の規約に従います。

## 3. 広告配信のために外部へ送信される情報（外部送信）

| 送信先 | 送信される情報 | 目的 |
|---|---|---|
| Google LLC（Google AdMob / Google Mobile Ads SDK・User Messaging Platform） | 広告識別子・端末の識別子（Android の広告 ID とアプリセット ID〔App Set ID〕、iOS ではアプリ・開発者ごとの端末の識別子〔IDFV など〕、該当する場合は端末にサインインしているアカウントに関連する識別子。iOS ではトラッキングの許可を求めないため IDFA は使われません）、IP アドレス（おおよその位置の推定に使われる場合があります）、端末の機種・OS・言語などの端末情報、アプリの情報、広告の表示・タップ・視聴の状況、クラッシュなどの診断情報、同意の選択の内容 | 広告の配信・効果測定・不正防止・サービス改善、同意の記録 |

- 広告は次の 3 種類です。ミッションのプレイ中には表示しません。
  - ミッション選択の画面のバナー
  - ミッションの合間の全画面広告（回数と間隔を制限しています）
  - 補給（リワード広告）：ミッション選択の画面で、受け取れる内容（装弾数の追加など）を確かめたうえで、利用者が自分で選んだときだけ表示します。最後まで見ると、その内容がゲームに反映されます。
- 本アプリは、広告の内容を「T（ティーン）」相当以下に制限して配信しています。
- 第6条の購入をストアで確認できた後は、バナーと全画面広告を表示しません。補給は、利用者が見るかどうかを選べる広告なので、購入後も見られます。購入済みで、補給も上限まで受け取った後は、本アプリは広告の読み込みと同意の確認を行いません（広告 SDK はアプリに含まれているため、起動時に SDK 自身が行う処理により、本条の情報の一部が送信される場合があります）。再インストールの直後や新しい端末で最初に起動したときなどに、ストアでの確認が間に合わない場合は、確認できるまでの間、バナーと全画面広告の表示と送信が行われることがあります。iOS では、再インストールや機種変更のあとは、設定画面の「購入を復元」を行うまで、バナーと全画面広告の表示と本条の送信が行われます。
- 情報は、暗号化された通信（TLS）で Google に送信されます。
- Google は、Google のプライバシーポリシーと、運営者と Google の間の規約（Google 広告のデータ保護規約など）に従って情報を扱います。
- 運営者は、広告 SDK が送信する情報を受け取らず、保存もしません。Google での保存期間は「Google によるデータの保持」（<https://policies.google.com/technologies/retention>）に従います。
- Google のプライバシーポリシー: <https://policies.google.com/privacy>
- Google がパートナーのサイトやアプリからの情報を使用する方法: <https://policies.google.com/technologies/partner-sites>

本条は、日本の電気通信事業法に定める外部送信規律に基づく公表を兼ねます。

## 4. 広告のパーソナライズと同意

- **欧州経済領域（EEA）・英国・スイス**: 初回起動時などに、Google 認定の同意管理ツール（UMP）で広告に関する同意を確認します。広告のパーソナライズは、同意がある場合だけ行われます。同意しない場合も広告が表示されることがありますが、選択に応じて、パーソナライズされない広告や制限付きの広告になります。
- **米国の一部の州**: 設定画面の「広告のプライバシー設定」から、個人情報の「販売・共有」をオプトアウトできます。
- 回答は、設定画面の「広告のプライバシー設定」からいつでも変更・取り消しできます（表示されるのは、同意や選択が必要な地域だけです。広告を読み込まなくなった後は表示されません）。
- **Android**: 端末の設定（「Google」→「広告」など。機種により異なります）で、広告 ID の削除・リセットができます。
- **iOS**: 本アプリは App Tracking Transparency による許可を求めず、他社のアプリやウェブサイトをまたいだトラッキングは行いません。
- Google のマイ アド センター（Google が保有する情報の確認・削除）: <https://myadcenter.google.com/>
- **EEA・英国・スイスの利用者の方へ**: 広告 SDK による情報の収集については、運営者（KOKOAPPS、kokoapps@outlook.jp）と Google がそれぞれ管理者にあたります。法的根拠は、端末への情報の保存・読み取りとパーソナライズ広告については同意（GDPR 第 6 条 1 項 (a)）、広告の配信・効果測定・不正防止については、同意管理ツールで示す範囲での正当な利益（同 (f)）です。Google LLC（米国）への移転は、Google の規約に定める保護措置（EU-米国データ・プライバシー・フレームワーク、標準契約条項など）に基づきます。利用者には、アクセス、訂正、消去、処理の制限、異議、データポータビリティの権利があり、同意はいつでも撤回できます。お住まいの国のデータ保護監督機関に苦情を申し立てることもできます。

## 5. 端末の機能・権限の利用

| 機能・権限 | 目的 | 情報の扱い |
|---|---|---|
| モーションセンサー（ジャイロ・加速度。iOS ではモーションの使用目的を表示） | 端末を傾けて照準を動かす | 端末内でその場の操作にだけ使い、記録・保存・送信しません |
| 音声合成（端末の読み上げ機能） | キャラクターのセリフの読み上げ | ゲーム内のセリフを端末の音声合成エンジンに渡します。録音・保存・送信はしません。エンジンの種類や設定によっては提供元が処理する場合があり、その取り扱いは各提供元の規約に従います |
| 画面の点灯維持・振動 | プレイ中に画面が消えないようにする・命中や爆発を振動で伝える | 情報は扱いません |
| インターネット通信（Android: INTERNET・ACCESS_NETWORK_STATE、広告 ID の AD_ID、Android のプライバシー サンドボックスの ACCESS_ADSERVICES_AD_ID・ACCESS_ADSERVICES_ATTRIBUTION・ACCESS_ADSERVICES_TOPICS。いずれも広告 SDK が追加） | 広告の表示 | 第3条のとおり Google に送信されます |
| アプリ内課金（Android: BILLING ／ iOS: App 内課金） | 広告の非表示の購入・復元 | 第6条のとおり、決済は各ストアが処理します |

WAKE_LOCK・FOREGROUND_SERVICE は、広告 SDK が内部の処理に使います（情報は扱いません）。

位置情報・カメラ・マイク・連絡先・写真などの権限は使用しません。

## 6. アプリ内課金（広告の非表示）

本アプリは、バナーと全画面広告を非表示にする機能（1 回払いの買い切り）を、App Store または Google Play のアプリ内課金で販売しています。販売の条件は「[特定商取引法に基づく表記](tokushoho/)」をご覧ください。

- 支払いは各ストア（Apple Inc.、Google LLC）が処理します。運営者は、支払い方法などの決済情報を取得しません。決済情報は、各ストアのプライバシーポリシーに従って扱われます。
- 本アプリは、購入済みかどうかを端末内に保存します。購入の確認・価格の表示・復元のため、起動時や設定画面を開いたとき、価格のボタン（購入）や「購入を復元」を押したときに、端末から各ストアに問い合わせます。購入の情報を運営者のサーバーに送信することはありません。
- 運営者は、各ストアから売上の報告として、注文番号・国・金額などの情報を受け取ることがあります。これらは、売上の管理とお問い合わせへの対応のためだけに使います。
- 購入しても、補給（リワード広告）は利用者が選んだときに見られます（第3条）。
- 購入の復元は、購入したときと同じストア（App Store または Google Play）の同じアカウントで行えます。Android と iPhone の間では引き継げません。

## 7. 第三者提供

利用者が使う OS の機能を通じたもの（第5条）、第3条の広告配信、第6条の各ストアによる決済を除き、本アプリが利用者の情報を外部へ送信したり第三者に提供したりすることはありません。運営者は、第6条の売上の報告と第10条のお問い合わせで受け取るものを除き、利用者の情報を保有していません。

## 8. 対象年齢

本アプリは銃による狙撃を題材にした描写を含み、16 歳未満の方を対象にしたものではありません。ストアの年齢区分に従ってご利用ください。13 歳未満の子どもの情報を意図して集めることはありません。

## 9. 利用者の権利

運営者は、第6条の売上の報告と第10条のお問い合わせで受け取るものを除き、利用者の情報を保有していません。端末内のデータはアンインストールで消去できます。広告に関する情報は、第4条の方法または Google の窓口から管理できます。購入の履歴は、各ストア（Apple、Google）のアカウントの画面で確認できます。

## 10. お問い合わせ時の情報

お問い合わせ（kokoapps@outlook.jp）をいただいた場合、メールアドレスとお問い合わせ内容を回答のためにのみ利用し、必要な期間を過ぎたら削除します。

## 11. 改定

本ポリシーを改定する場合は本ページを更新し、重要な変更はアプリ内またはストアの掲載ページでお知らせします。

---

<a id="english"></a>

# VELVET TRIGGER Privacy Policy (English)

[Legal notice (Japan)](tokushoho/#english) ｜ [All apps](../)

- Effective date: November 7, 2026
- Last updated: November 14, 2026 (advertising, resupply ads (rewarded ads) and the in-app purchase that removes the ads added)
- Operator: KOKOAPPS
- Contact: kokoapps@outlook.jp
- Applies to: Android (Google Play) and iOS (App Store)

## 1. Overview
VELVET TRIGGER ("the App") has no accounts and no servers, and the operator does not collect your information. The App shows ads through Google AdMob (Google LLC), which receives some information as described in Section 3. You can remove the banner and full-screen ads with an in-app purchase; resupply ads stay optional (Section 6). The App contains no analytics or crash-reporting SDKs.
The App uses the internet only to show ads, to check advertising consent (Section 4) and to buy, check and restore the in-app purchase (Section 6).

## 2. Information stored only on your device
Settings (language, aim control mode and sensitivity, pinch zoom, volumes, voice, vibration, cut-in effects, etc.), progress (cleared missions, best score and rank per mission), how many resupplies (rewarded ads) you have received (extra rounds per magazine and faster reloading) and whether you have bought the removal of the ads are stored locally (SharedPreferences / UserDefaults) and are never sent to the operator. They are deleted when you uninstall the App; best scores can also be erased with "Reset progress" in Settings. They may be included in OS backups (Google backup / iCloud backup), which are governed by those providers' terms.

## 3. Information sent for advertising
Google LLC (Google Mobile Ads SDK and User Messaging Platform) may collect: advertising and device identifiers (on Android the advertising ID and the app set ID; on iOS app- or developer-scoped device identifiers such as the IDFV; where applicable, identifiers related to accounts signed in on the device; the IDFA is not used because the App does not request tracking permission), IP address (may be used to estimate approximate location), device information (model, OS, language), app information, ad impressions, clicks and views, diagnostics such as crash data, and your consent choices — for ad delivery, measurement, fraud prevention, service improvement and consent records.
- The App shows three kinds of ads, never during a mission:
  - a banner on the mission select screen;
  - full-screen ads between missions (limited in frequency);
  - resupply ads (rewarded ads): shown only when you choose to watch one on the mission select screen after seeing what you will receive (such as an extra round per magazine). Watching to the end applies the reward in the game.
- Ad content is limited to rating "T" or lower.
- Once the store has confirmed the purchase in Section 6, the App no longer shows the banner or full-screen ads. Resupply ads are ads you choose to watch, so they stay available after the purchase. Once you have bought the removal and received every resupply, the App no longer loads ads or checks consent (the ads SDK remains part of the App, so its own start-up processing may still send some of this information). Right after a reinstall or on the first start on a new device, if the store cannot confirm the purchase in time, banners and full-screen ads may be shown and this information sent until it does. On iOS, after a reinstall or on a new device, banners and full-screen ads are shown and this information is sent until you tap "Restore purchases" in Settings.
- The information is sent to Google over encrypted connections (TLS).
- Google handles the information under the Google Privacy Policy and the terms between the operator and Google (such as the Google Ads Data Protection Terms).
- The operator does not receive or store the information the ads SDK sends. Google keeps it as described in "How Google retains data we collect" (<https://policies.google.com/technologies/retention>).
- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from sites or apps that use its services: <https://policies.google.com/technologies/partner-sites>

## 4. Personalized ads and consent
- **EEA, UK and Switzerland**: a Google-certified consent tool (UMP) asks for your consent, for example on first launch. Ads are personalized only with your consent. If you do not consent, ads may still be shown, but they are non-personalized or limited according to your choices.
- **Some US states**: you can opt out of the "sale" or "sharing" of personal information under "Ad privacy settings" in Settings.
- You can change or withdraw your choices anytime under "Ad privacy settings" in Settings (shown only in the regions that require consent or a choice, and not once the App no longer loads ads).
- **Android**: you can delete or reset your advertising ID in device settings (e.g., Google > Ads; this varies by device).
- **iOS**: the App does not request App Tracking Transparency permission and does not track you across other companies' apps or websites.
- Google My Ad Center (review or delete information Google holds): <https://myadcenter.google.com/>
- **Users in the EEA, the UK and Switzerland**: for the collection by the ads SDK, the operator (KOKOAPPS, kokoapps@outlook.jp) and Google are each controllers. Legal bases: consent (Art. 6(1)(a) GDPR) for storing and reading information on your device and for personalized ads; legitimate interests (Art. 6(1)(f) GDPR) for serving ads, measurement and fraud prevention, to the extent shown in the consent tool. Transfers to Google LLC (United States) rely on the safeguards in Google's terms (the EU-U.S. Data Privacy Framework, standard contractual clauses, etc.). You have the rights of access, rectification, erasure, restriction, objection and data portability, and you can withdraw your consent at any time. You can also lodge a complaint with your data protection authority.

## 5. Device features and permissions
- **Motion sensors** (gyroscope, accelerometer): used only on-device to aim the scope; nothing is recorded, stored or transmitted.
- **Text-to-speech**: in-game lines are passed to your device's speech engine; nothing is recorded, stored or sent. Depending on the engine, its provider may process the text under its own terms.
- **Keep screen on / vibration**: prevents the screen from turning off during play and gives haptic feedback; no data involved.
- **Internet access** (on Android: INTERNET, ACCESS_NETWORK_STATE, the advertising ID permission AD_ID and the Privacy Sandbox permissions ACCESS_ADSERVICES_AD_ID, ACCESS_ADSERVICES_ATTRIBUTION and ACCESS_ADSERVICES_TOPICS, all added by the ads SDK): used to show ads (Section 3). WAKE_LOCK and FOREGROUND_SERVICE are used by the ads SDK for internal work; no data involved.
- **In-app purchase** (BILLING on Android; In-App Purchase on iOS): buying and restoring the removal of the ads; payments are processed by the stores (Section 6).
The App does not use location, camera, microphone, contacts or photo permissions.

## 6. In-app purchase (removing the ads)
The App sells the removal of the banner and full-screen ads (a one-time purchase) through in-app purchases on the App Store or Google Play. For the terms of sale, see the [legal notice](tokushoho/#english).
- Payments are processed by the stores (Apple Inc., Google LLC). The operator does not receive payment information such as your payment method; the stores handle it under their privacy policies.
- The App stores on your device whether you have bought the removal. To check the purchase, show the price and restore the purchase, it asks the store from your device when it starts, when you open Settings and when you tap the price button (to buy) or "Restore purchases". Nothing about the purchase is sent to the operator's servers.
- The stores may send the operator sales reports with information such as order numbers, countries and amounts. They are used only to manage sales and to answer your inquiries.
- After the purchase you can still choose to watch resupply ads (Section 3).
- The purchase can be restored with the same account of the store you bought it from (App Store or Google Play). It does not carry over between Android and iPhone.

## 7. Sharing with third parties
Apart from the OS features described in Section 5, the advertising described in Section 3 and the payments processed by the stores described in Section 6, the App does not send your information outside the device or share it with third parties. Except for the sales reports in Section 6 and your inquiries in Section 10, the operator holds no information about you.

## 8. Children
The App depicts sniper shooting and is not intended for users under 16; please follow the store age rating. We do not knowingly collect information from children under 13.

## 9. Your rights
Except for the sales reports in Section 6 and your inquiries in Section 10, the operator holds no information about you. You can erase on-device data by uninstalling the App. Advertising data can be managed as described in Section 4 or via Google. Your purchase history is available in your Apple or Google account.

## 10. Contacting us
If you contact us (kokoapps@outlook.jp), your email address and message are used only to reply and are deleted when no longer needed.

## 11. Changes
We will update this page when this policy changes and announce significant changes in the App or on the store listing.
