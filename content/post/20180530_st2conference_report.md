---
title: "第四回 StackStorm 勉強会レポート"
date: 2018-06-01T10:30:18+09:00
tags:
  - 勉強会
author: Hiroyasu OHYAMA
author_picture_url: https://github.com/userlocalhost.png
picture_url: https://raw.githubusercontent.com/userlocalhost/official-page/master/static/img/20180529_st2_conference.png
---
ソフトバンクさま主催の [TechNight @Shiodome](https://techsio.connpass.com/event/83273/) にて、第四回 StackStorm 勉強会を開催していただきました。

多数のご来場いただきありがとうございました。\\
また大変興味深い発表をしてくださった発表者の皆さま、会場をご提供くださいましたソフトバンクさま、差し入れをくださいました Extreme Networks さまに改めて感謝申し上げます。

以下、それぞれの発表者（敬称略）の資料とサマリになります。各セッションの内容については [@w4yh さんのレポート記事](http://w4yh.hatenablog.com/entry/2018/06/01/043757) が詳しいので併せてご覧ください。

---
### 明日からできる、st2のActionの作り方
**(萬治 渉 / NTTテクノクロス株式会社 IoTイノベーション事業部)**

Action の実装方法について詳しく解説いただきました。詳しくは資料をご参照ください。

<div style='width: 595px;'>
<script async class="speakerdeck-embed" data-id="3eb199555a30443fbf7321c96f847aab" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>
</div>

---
### データの民主化のためにStackStormを活用した事例
**(佐伯 嘉康 / リクルートテクノロジーズ)**

社内の様々な部署で蓄積されたデータを共有の場所に蓄積し、共通の方法で自由に取得できるようにするプラットフォームを作ったという事例についてご紹介いただきました。

<iframe src="//www.slideshare.net/slideshow/embed_code/key/fTvb1ChqjDRQWz" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/laclefyoshi/stackstorm-99437154" title="データの民主化のために StackStorm を活用した事例" target="_blank">データの民主化のために StackStorm を活用した事例</a> </strong> from <strong><a href="https://www.slideshare.net/laclefyoshi" target="_blank">Yoshiyasu SAEKI</a></strong> </div>

---
### 3万台のリスクから会社を守る。st2で24時間リモートワイプ
**(森 正樹 / ソフトバンク株式会社 IT本部 ネットワーク統括部 ネットワーク部 ネットワーク運用課)**

社内の情報システム部門が通常行っている PC の紛失に伴う VPN 証明書の失効処理を IFTTT 化させることで、それまで平日/日中対応だった紛失対応を 24-365 で自動対応化でき、運用コストが低減しセキュリティレベルが向上したというお話をしていただきました。

<iframe src="//www.slideshare.net/slideshow/embed_code/key/9wmG9XkABantyG" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/MasakiMori6/3st224" title="3万台のリスクから会社を守るST2で24時間リモートワイプ" target="_blank">3万台のリスクから会社を守るST2で24時間リモートワイプ</a> </strong> from <strong><a href="https://www.slideshare.net/MasakiMori6" target="_blank">Masaki Mori</a></strong> </div>

---
### NW機器・サーバ機器の設定自働化に向けたst2機能の活用案
**(福田 晴元 / NTTソフトウエアイノベーションセンタ)**

StackStorm v2.4.0 から導入された [ワークフロー処理を中断＆再開する機能](https://stackstorm.com/2017/08/24/whats-stackstorm-2-4-already/) が、アプライアンスのデプロイをする際に良かったというお話をしていただきました。

<iframe src="//www.slideshare.net/slideshow/embed_code/key/IpstphUUgD7cHO" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/HarumotoFukuda/nwst2-99682441" title="NW機器の設定自働化に向けたST2機能の活用" target="_blank">NW機器の設定自働化に向けたST2機能の活用</a> </strong> from <strong><a href="https://www.slideshare.net/HarumotoFukuda" target="_blank">Harumoto Fukuda</a></strong> </div>

---
### st2-docker ことはじめ
**(杉本 周 / インターネットマルチフィード 技術部)**

[st2-docker](https://github.com/StackStorm/st2-docker) を商用環境で利用されている立場から、st2-docker を使って HA でスケースする環境を作るにはどうするか、その場合の共有ストレージ環境をどう作るかといった、st2-docker にまつわるさまざまな運用 TIPS についてお話いただきました。

<iframe src="//www.slideshare.net/slideshow/embed_code/key/6WDfnslNop4DTT" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/shusugimoto1986/st2docker" title="st2-docker ことはじめ" target="_blank">st2-docker ことはじめ</a> </strong> from <strong><a href="https://www.slideshare.net/shusugimoto1986" target="_blank">Shu Sugimoto</a></strong> </div>

---
### StackStorm アップデート＆ロードマップ
**(Lindsay Hill / Extreme Networks)**

StackStorm v3.0 までのロードマップ (k8s HA のサポートや、各 GNU/Linux ディストリビューションのサポートスケジュールなど) についてお話いただきました。

<iframe src="//www.slideshare.net/slideshow/embed_code/key/bImzTPntVJlwuJ" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/ExtrJP/st2-community-update-99664789" title="ST2 Community Update" target="_blank">ST2 Community Update</a> </strong> from <strong><a href="https://www.slideshare.net/ExtrJP" target="_blank">エクストリーム ネットワークス / Extreme Networks Japan</a></strong> </div>

---
次回もどうぞお楽しみに。
