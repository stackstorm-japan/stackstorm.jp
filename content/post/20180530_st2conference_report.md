---
title: "第4回 StackStorm 勉強会レポート"
date: 2018-05-30T17:56:18+09:00
tags:
  - 勉強会
draft: true
author: Hiroyasu OHYAMA
author_picture_url: https://github.com/userlocalhost.png
---

ソフトバンクさま主催の [TechNight @Shiodome](https://techsio.connpass.com/event/83273/) にて、第4回 StackStorm 勉強会を開催していただきました。

多数のご来場いただきありがとうございました。\\
また大変興味深い発表をしてくださった発表者の皆さま、会場をご提供くださいましたソフトバンクさま、差し入れをくださいました Extreme Networks さまに改めて感謝申し上げます。

以下、それぞれの発表者（敬称略）の資料とサマリになります。

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

<資料>

---
### NW機器・サーバ機器の設定自働化に向けたst2機能の活用案
**(福田 晴元 / NTTソフトウエアイノベーションセンタ)**

StackStorm v2.4.0 から導入されたワークフロー処理を中断＆再開する機能がアプライアンスのデプロイをする際に良かったというお話をしていただきました。

<資料>

---
### st2-docker ことはじめ
**(杉本 周 / インターネットマルチフィード 技術部)**

st2-docker を商用環境で利用されている立場から、st2-docker を使って HA でスケースする環境を作るにはどうするか、その場合の共有ストレージ環境をどう作るかといった、st2-docker にまつわるさまざまな運用 TIPS についてお話いただきました。

<iframe src="//www.slideshare.net/slideshow/embed_code/key/6WDfnslNop4DTT" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/shusugimoto1986/st2docker" title="st2-docker ことはじめ" target="_blank">st2-docker ことはじめ</a> </strong> from <strong><a href="https://www.slideshare.net/shusugimoto1986" target="_blank">Shu Sugimoto</a></strong> </div>

---
### StackStorm アップデート＆ロードマップ
**(Lindsay Hill / Extreme Networks)**

StackStorm v3.0 までのロードマップ (k8s HA のサポートや、各 GNU/Linux ディストリビューションのサポートスケジュールなど) についてお話いただきました。

<資料>

---
次回もどうぞお楽しみに。
