# 麻雀道場（MahjongDojo）プライバシーポリシー

[English](#english) ｜ [特定商取引法に基づく表記](tokushoho/) ｜ [アプリ一覧に戻る](../)

- 制定日: 2026年11月7日
- 改定日: 2026年11月14日（広告配信・リワード広告・アプリ内課金〔広告の非表示〕を追加）
- 運営者: KOKOAPPS
- お問い合わせ: kokoapps@outlook.jp
- 対象: Android 版（Google Play）・iOS 版（App Store）

本ポリシーは、麻雀の学習アプリ「麻雀道場」（以下「本アプリ」）のスマートフォン・タブレット版における利用者情報の取り扱いを定めるものです。

## 1. 基本方針

本アプリには利用者登録・ログインの機能はなく、運営者のサーバーはありません。外部の生成 AI サービスは使用しておらず、解析・解説・キャラクターのセリフはすべて端末内で処理します。対局の記録や成績は利用者の端末内にだけ保存され、運営者が収集することはありません。ただし、広告を表示するため、Google LLC の広告サービス「Google AdMob」を利用しており、これにより一部の情報が Google に送信されます（第4条）。広告は、アプリ内課金で非表示にできます（第7条）。本アプリ自体は、アクセス解析・クラッシュ収集のサービスを組み込んでいません（第4条の広告 SDK が送る診断情報を除きます）。本アプリでは、実際のお金・景品を賭けることはできません。

## 2. 端末内にだけ保存する情報

| 情報 | 目的 |
|---|---|
| 対局の記録（牌譜）・成績・段位・ドリルの結果 | 牌譜検討・成績分析 |
| 設定（言語・ルール・キャラクター・音量・アシストの表示など）・BGM の再生順 | アプリの動作 |
| エラーの記録（error.log） | 不具合の記録（どこにも送信しません） |
| 広告の非表示を購入済みかどうか | 購入した利用者に広告を表示しないため（第7条） |

データは端末内のアプリ専用領域に保存され、運営者に送信されません。アンインストールすると削除されます。OS のバックアップ機能の対象になる場合があり、その取り扱いは各社の規約に従います。

## 3. 端末の機能・権限の利用

| 機能・権限 | 目的 | 情報の扱い |
|---|---|---|
| インターネット通信（Android: INTERNET・ACCESS_NETWORK_STATE、広告 ID の AD_ID） | 広告の表示 | 第4条のとおり Google に送信されます |
| アプリ内課金（Android: BILLING ／ iOS: App 内課金） | 広告の非表示の購入・復元 | 第7条のとおり、決済は各ストアが処理します |

AD_ID は、本アプリが組み込んでいる広告 SDK（Google Mobile Ads SDK）が追加する権限です。本アプリは、位置情報・カメラ・マイク・連絡先・写真などの権限を使用しません。音声・BGM はアプリに同梱したものを再生します。iOS では、トラッキングの許可（App Tracking Transparency）を求めません（第6条）。

## 4. 広告配信のために外部へ送信される情報（外部送信）

| 送信先 | 送信される情報 | 目的 |
|---|---|---|
| Google LLC（Google AdMob / Google Mobile Ads SDK） | 広告識別子（Android の広告 ID。iOS ではトラッキングの許可を求めないため、IDFA は使われません）、アプリセット ID（Android）、IP アドレス（おおよその位置の推定に使われる場合があります）、端末の機種・OS・言語などの端末情報、アプリの情報、広告の表示・タップの状況、クラッシュなどの診断情報 | 広告の配信・広告のパーソナライズ（第6条で認められる場合だけ）・効果測定・不正防止・サービス改善 |

- 本アプリは、対局の記録・成績・設定の内容を広告 SDK に渡しません。
- 広告の内容は、「T（ティーン）」相当以下に制限しています。
- 第7条の購入をストアで確認できた後は、本アプリは広告の読み込み・表示をやめ、次の起動からは広告 SDK を初期化しません（そのため、本条の送信は行われなくなります）。再インストールの直後や新しい端末では、購入を復元するまでの間、広告の表示と送信が行われることがあります。
- 情報は、暗号化された通信（TLS）で Google に送信されます。
- Google は、Google のプライバシーポリシーと、運営者と Google の間の規約（Google 広告のデータ保護規約など）に従って情報を扱います。運営者は、これらの規約により、Google が本ポリシーと同等以上の保護を行うことを確認しています。
- 運営者は、広告 SDK が送信する情報を受け取らず、保存もしません。Google での保存期間は「Google によるデータの保持」（<https://policies.google.com/technologies/retention>）に従います。
- Google のプライバシーポリシー: <https://policies.google.com/privacy>
- Google がパートナーのサイトやアプリからの情報を使用する方法: <https://policies.google.com/technologies/partner-sites>

本条は、日本の電気通信事業法に定める外部送信規律に基づく公表を兼ねます。

## 5. 広告を表示する場所

| 広告の種類 | 表示する場所・タイミング |
|---|---|
| バナー広告 | 開始画面（タイトル画面）の下部 |
| インタースティシャル広告（全画面の広告） | 対局を終えて開始画面に戻るとき。対局中・ドリル中には表示しません。表示は 4 分に 1 回までとし、1 分未満で終わった対局のあとには表示しません |
| リワード広告（動画などの広告） | 利用者が特典を受け取るために、自分で視聴を選んだときだけ |

リワード広告について:

- 特典は、手牌がテンパイしているときに、その局をすぐにアガれる（即ツモまたは即ロン）ボタンです。
- 使える回数は、半荘戦では東場・南場でそれぞれ 1 回、東風戦では 1 対局に 1 回、1局戦では 1 回です。
- 特典は、広告を最後まで視聴したときに受け取れます。アガリ牌が山に残っていない、役がない、フリテン（即ロンのとき）などの場面では使えません。
- 視聴するかどうかは任意です。リワード広告は、利用者が自分で視聴を選んだときにだけ表示し、勝手に再生することはありません。視聴しなくても、特典以外の機能はすべて使えます。
- 特典は対局の中だけのもので、金銭的な価値はありません。特典だけを購入することもできません（広告の非表示を購入した場合は、広告を視聴せずに、同じ回数だけ使えます。第7条）。

## 6. 広告のパーソナライズと同意

- **欧州経済領域（EEA）・英国・スイス**: 初回起動時などに、Google 認定の同意管理ツール（UMP）で広告に関する同意を確認します。広告のパーソナライズは、同意がある場合だけ行われます。同意しない場合も広告が表示されることがありますが、選択に応じて、パーソナライズされない広告や制限付きの広告になります。
- **米国の一部の州**: 運営者が AdMob で米国の州のプライバシー法向けの設定を行い、お住まいの州で選択が求められる場合は、設定画面（「データ」）に「広告のプライバシー設定」が表示され、そこから個人情報の「販売・共有」をオプトアウトできます。
- **その他の地域**: 広告は、既定でパーソナライズされることがあります。Android では、下記の方法で広告 ID を削除・リセットできます。
- 回答は、設定画面（「データ」）の「広告のプライバシー設定」からいつでも変更・取り消しできます（このボタンが表示されるのは、上記の同意や選択が必要な地域だけです。広告の非表示を購入した後は、広告 SDK を使わないため表示されません）。
- **Android**: 端末の設定（「Google」→「広告」など。機種により異なります）で、広告 ID の削除・リセットができます。
- **iOS**: 本アプリは、App Tracking Transparency によるトラッキングの許可を求めず、IDFA を使用しません。他社のアプリやウェブサイトをまたいだトラッキングは行いません。
- Google のマイ アド センター（Google が保有する情報の確認・削除）: <https://myadcenter.google.com/>
- **EEA・英国・スイスの利用者の方へ**: 広告 SDK による情報の収集については、運営者（KOKOAPPS、kokoapps@outlook.jp）と Google がそれぞれ管理者にあたります。法的根拠は、端末への情報の保存・読み取りとパーソナライズ広告については同意（GDPR 第 6 条 1 項 (a)）、広告の配信・効果測定・不正防止については、同意管理ツールで示す範囲での正当な利益（同 (f)）です。Google LLC（米国）への移転は、Google の規約に定める保護措置（EU-米国データ・プライバシー・フレームワーク、標準契約条項など）に基づきます。利用者には、アクセス、訂正、消去、処理の制限、異議、データポータビリティの権利があり、同意はいつでも撤回できます。お住まいの国のデータ保護監督機関に苦情を申し立てることもできます。

## 7. アプリ内課金（広告の非表示）

本アプリは、広告を非表示にする機能（1 回払いの買い切り。日本では 200 円〔税込〕）を、App Store または Google Play のアプリ内課金で販売しています。設定画面に、購入のボタン（ストアの価格を表示します）と「購入を復元」のボタンがあります。販売の条件は「[特定商取引法に基づく表記](tokushoho/)」をご覧ください。

- 支払いは各ストア（Apple Inc.、Google LLC）が処理します。運営者は、支払い方法などの決済情報を取得しません。決済情報は、各ストアのプライバシーポリシーに従って扱われます。
- 本アプリは、購入済みかどうかだけを端末内に保存します。購入の確認と復元のため、端末から各ストアに問い合わせます。Android では、購入が確認できていない間は、起動するたびに Google Play に過去の購入を問い合わせます（画面には何も表示しません）。また、価格を表示するため、起動時に各ストアに商品の情報を問い合わせます。iOS では、「購入を復元」を押したときと、App Store から未処理の取引が届いたときに確認します。購入の情報を運営者に送信することはありません。
- 運営者は、各ストアから売上の報告として、注文番号・国・金額などの情報を受け取ることがあります。これらは、売上の管理とお問い合わせへの対応のためだけに使います。
- 購入をストアで確認できた後は、本アプリは広告の読み込み・表示をやめ、次の起動からは広告 SDK を初期化しません。バナー広告・インタースティシャル広告・リワード広告と、広告の同意の確認（第6条）は表示されません。第5条の特典は、広告を視聴せずに、同じ回数だけ使えます。
- 再インストールの直後や新しい端末では、購入を復元するまでの間、広告が表示されることがあります。
- 購入の復元は、購入したときと同じストア（App Store または Google Play）の同じアカウントで行えます。Android と iOS（iPhone・iPad）の間では引き継げません。

## 8. 第三者提供

第4条の広告配信と、第7条の各ストアによる決済・購入の確認を除き、本アプリが利用者の情報を外部へ送信したり第三者に提供したりすることはありません。運営者は、第7条の売上の報告と第11条のお問い合わせで受け取るものを除き、利用者の情報を保有していません。

## 9. 対象年齢

本アプリは13歳以上の方を対象としており、13歳未満の子どもを対象にしたものではありません。

## 10. 利用者の権利

運営者は、第7条の売上の報告と第11条のお問い合わせで受け取るものを除き、利用者の情報を保有していません。端末内のデータは、アンインストールで消去できます。広告に関する情報は、第6条の方法または Google の窓口から管理できます。購入の履歴は、各ストア（Apple、Google）のアカウントの画面で確認できます。

## 11. お問い合わせ時の情報

お問い合わせ（kokoapps@outlook.jp）をいただいた場合、メールアドレスとお問い合わせ内容を回答のためにのみ利用し、必要な期間を過ぎたら削除します。

## 12. 改定

本ポリシーを改定する場合は本ページを更新し、重要な変更はアプリ内またはストアの掲載ページでお知らせします。

---

<a id="english"></a>

# MahjongDojo Privacy Policy (English)

[Legal notice (Japan)](tokushoho/#english) ｜ [All apps](../)

- Effective date: November 7, 2026
- Last updated: November 14, 2026 (advertising, rewarded ads and the in-app purchase for removing the ads added)
- Operator: KOKOAPPS
- Contact: kokoapps@outlook.jp
- Applies to: Android (Google Play) and iOS (App Store)

## 1. Overview
MahjongDojo ("the App") has no accounts and no servers of its own and uses no external generative-AI services; all analysis, explanations and character lines are processed on your device. Your game records and statistics are stored only on your device and are not collected by the operator. The App shows ads through Google AdMob (Google LLC), which receives some information as described in Section 4. You can remove the ads with an in-app purchase (Section 7). The App itself contains no analytics or crash-reporting SDKs (apart from the diagnostics the ads SDK in Section 4 sends). No real money or prizes can be wagered in the App.

## 2. Information stored only on your device
Game records, statistics and rank, drill results, settings (language, rules, characters, volume, assist display, etc.), the BGM play order, an error log (error.log, which is never sent anywhere) and whether you have bought the removal of the ads are stored in the App's private storage and never sent to the operator. Uninstalling the App deletes them. They may be included in OS backups, governed by those providers' terms.

## 3. Device features and permissions
- **Internet access** (INTERNET, ACCESS_NETWORK_STATE and the advertising ID permission AD_ID on Android): used to show ads (see Section 4). AD_ID is added by the ads SDK (Google Mobile Ads SDK) the App includes.
- **In-app purchase** (BILLING on Android; In-App Purchase on iOS): buying and restoring the removal of the ads; payments are processed by the stores (see Section 7).

The App does not use location, camera, microphone, contacts or photo permissions. Voices and music are bundled with the App. On iOS, the App does not ask for tracking permission (App Tracking Transparency; see Section 6).

## 4. Information sent for advertising
Google LLC (Google Mobile Ads SDK) may collect: advertising identifiers (the Android advertising ID; on iOS the IDFA is not used because the App does not ask for tracking permission), the app set ID (Android), IP address (may be used to estimate approximate location), device information (model, OS, language), app information, ad impressions and clicks, and diagnostics such as crash data — for ad delivery, ad personalization (only where allowed under Section 6), measurement, fraud prevention and service improvement.
- The App does not pass the content of your game records, statistics or settings to the ads SDK.
- Ad content is limited to rating "T" (teen) or lower.
- Once the store has confirmed the purchase in Section 7, the App stops loading and showing ads, and from the next start it does not initialize the ads SDK (so nothing described in this section is sent any more). Right after a reinstall or on a new device, ads may be shown and this information sent until the purchase is restored.
- The information is sent to Google over encrypted connections (TLS).
- Google handles the information under the Google Privacy Policy and the terms between the operator and Google (such as the Google Ads Data Protection Terms). Through these terms the operator has confirmed that Google protects the information at least as well as this policy does.
- The operator does not receive or store the information the ads SDK sends. Google keeps it as described in "How Google retains data we collect" (<https://policies.google.com/technologies/retention>).
- Google Privacy Policy: <https://policies.google.com/privacy>
- How Google uses information from sites or apps that use its services: <https://policies.google.com/technologies/partner-sites>

This section also serves as the public notice required by Japan's Telecommunications Business Act (rules on external transmission).

## 5. Where ads are shown
- **Banner ad**: at the bottom of the start (title) screen.
- **Interstitial ad (full screen)**: when you return to the start screen after finishing a game. It is never shown during play or drills, at most once every 4 minutes, and not after games shorter than 1 minute.
- **Rewarded ad (video or other full-screen ad)**: only when you choose to watch one to receive the in-game bonus below.

About the rewarded ads:
- The bonus is a button that lets you win the current hand instantly (instant tsumo or ron) when your hand is ready (tenpai).
- It can be used once in the East round and once in the South round of a half game (hanchan), once per game in an East-only game (tonpu), and once in a one-hand game.
- The bonus is given only after you watch the ad to the end. It cannot be used in some situations, e.g., when no winning tile is left in the wall, the hand has no yaku, or (for ron) you are furiten.
- Watching is optional. A rewarded ad is shown only when you choose to watch it; it never plays on its own. Every feature other than the bonus works without watching.
- The bonus exists only within the game and has no monetary value. It cannot be bought on its own (if you have bought the removal of the ads, you can use it the same number of times without watching an ad; see Section 7).

## 6. Personalized ads and consent
- **EEA, UK and Switzerland**: a Google-certified consent tool (UMP) asks for your consent, for example on first launch. Ads are personalized only with your consent. If you do not consent, ads may still be shown, but they are non-personalized or limited according to your choices.
- **Some US states**: if the operator has configured AdMob's US state privacy settings and your state requires a choice, "Ad privacy settings" appears in Settings ("Data" section), where you can opt out of the "sale" or "sharing" of personal information.
- **Other regions**: ads may be personalized by default. On Android, you can delete or reset your advertising ID as described below.
- You can change or withdraw your choices anytime under "Ad privacy settings" in Settings ("Data" section). The button is shown only in the regions above that require consent or a choice. It is not shown after you buy the removal of the ads, because the App then no longer uses the ads SDK.
- **Android**: you can delete or reset your advertising ID in device settings (e.g., Google > Ads; this varies by device).
- **iOS**: the App does not ask for tracking permission through App Tracking Transparency and does not use the IDFA. It does not track you across other companies' apps or websites.
- Google My Ad Center (review or delete information Google holds): <https://myadcenter.google.com/>
- **Users in the EEA, the UK and Switzerland**: for the collection by the ads SDK, the operator (KOKOAPPS, kokoapps@outlook.jp) and Google are each controllers. Legal bases: consent (Art. 6(1)(a) GDPR) for storing and reading information on your device and for personalized ads; legitimate interests (Art. 6(1)(f) GDPR) for serving ads, measurement and fraud prevention, to the extent shown in the consent tool. Transfers to Google LLC (United States) rely on the safeguards in Google's terms (the EU-U.S. Data Privacy Framework, standard contractual clauses, etc.). You have the rights of access, rectification, erasure, restriction, objection and data portability, and you can withdraw your consent at any time. You can also lodge a complaint with your data protection authority.

## 7. In-app purchase (removing the ads)
The App sells the removal of the ads (a one-time purchase; ¥200 including tax in Japan) through in-app purchases on the App Store or Google Play. Settings has a purchase button (showing the store's price) and a "Restore purchase" button. For the terms of sale, see the [legal notice](tokushoho/#english).
- Payments are processed by the stores (Apple Inc., Google LLC). The operator does not receive payment information such as your payment method; the stores handle it under their privacy policies.
- The App stores on your device only whether you have bought the removal. To check and restore the purchase, it asks the store from your device: on Android, while the purchase has not been confirmed, it asks Google Play for past purchases every time it starts (without showing anything); on iOS, it checks when you tap "Restore purchase" and when the App Store delivers pending transactions. It also asks the store for the product's price when it starts. Nothing about the purchase is sent to the operator.
- The stores may send the operator sales reports with information such as order numbers, countries and amounts. They are used only to manage sales and to answer your inquiries.
- Once the store has confirmed the purchase, the App stops loading and showing ads and, from the next start, does not initialize the ads SDK: no banner, interstitial or rewarded ads and no ad consent form (Section 6) are shown. The bonus in Section 5 can then be used the same number of times without watching an ad.
- Right after a reinstall or on a new device, ads may be shown until the purchase is restored.
- The purchase can be restored with the same account of the store you bought it from (App Store or Google Play). It does not carry over between Android and iOS (iPhone/iPad).

## 8. Sharing with third parties
Apart from the advertising described in Section 4 and the payments and purchase checks handled by the stores described in Section 7, the App does not send your information outside the device or share it with third parties. Except for the sales reports in Section 7 and your inquiries in Section 11, the operator holds no information about you.

## 9. Children
The App is intended for users aged 13 and over and is not directed at children under 13.

## 10. Your rights
Except for the sales reports in Section 7 and your inquiries in Section 11, the operator holds no information about you. You can erase on-device data by uninstalling the App. Advertising data can be managed as described in Section 6 or via Google. Your purchase history is available in your Apple or Google account.

## 11. Contacting us
If you contact us (kokoapps@outlook.jp), your email address and message are used only to reply and are deleted when no longer needed.

## 12. Changes
We will update this page when this policy changes and announce significant changes in the App or on the store listing.
