---
title: "StackStorm TSC Meeting 参加報告 & もくもく会のお知らせ"
date: 2020-09-28T10:15:00+09:00
tags:
  - お知らせ
author: Hiroyasu OHYAMA
author_picture_url: https://github.com/userlocalhost.png
picture_url: https://github.com/stackstorm-japan/stackstorm.jp/blob/master/static/img/20200928/thumbnail.png?raw=true
---
### StackStorm TSC Meeting 参加報告

　昨年のちょうど今頃(2019-10-7)、[Extreme Networks が StackStorm を The Linux Foundation に移管するという発表](https://investor.extremenetworks.com/news-releases/news-release-details/extreme-networks-transitions-stackstorm-linux-foundation) をしました。更に、今年の5月に [EWC (Enterprise 版 StackStorm) も The Linux Foundation に移管する](https://stackstorm.com/2020/05/27/extreme-networks-donates-ewc-to-linux-foundation/) という発表がなされました。

　それまで StackStorm 及び EWC の開発は、開発ベンダーである Extreme Networks のもとで行われてきましたが、その後 The Linux Foundation のもとで行われることになりました。

　これに伴い、以下のような開発・サポート体制の再編とガバナンスの変更が行われました。

* [2019年6月に Extreme Networks を退職した、StackStorm 創設メンバー Dimitri Zimine 氏](https://stackstorm.com/2019/06/06/dmitri-says-good-bye/) をトップに、Extreme Networks 以外のメンバーを含めた開発コミュニティを組織 (c.f. [st2/OWNERS](https://github.com/StackStorm/st2/blob/master/OWNERS.md))。
* 開発方針は Technical Steering Committee(TSC) で協議・決定。なお TSC は [st2/OWNERS](https://github.com/StackStorm/st2/blob/master/OWNERS.md) で規定されている開発コミュニティメンバーのうち、Maintainers 以上のロールのメンバーによって構成。

　この TSC Meeting は[（日本時間で）毎月第一水曜日の午前 01:30 ~ 02:30 にオンラインで開催](https://github.com/StackStorm/discussions/issues/33) され、誰でも自由に参加することができます（TSC メンバー以外の発言は制限されているため、もしご参加される際はマイクの設定をミュートにしてご参加ください）。

　[前回の TSC Meeting](https://github.com/StackStorm/discussions/issues/47) は 2020/09/02(水) の深夜 (日本時間) に開催されました。そこで、メンテナの [Eugen Cusmaunsa (@armab) 氏](https://github.com/armab) から日本のユーザコミュニティの活動について話してほしい旨の要請を受け、日本 StackStorm ユーザ会の発足経緯からこれまでの活動と、現在の活動課題についてお話をさせていただきました。以下は、その際話した内容を動画にしてものです。

{{<youtube VuF3hKA4m9Q >}}

　内容を簡単にまとめると、

```
　これまでオフラインの勉強会を通じて ST2 ユーザの交流や情報交換を図ってきましたが、参加人数の減少に伴い運営側の継続モチベーションも低下してきてしまう負のスパイラルに陥りかけている。
　今後はオンラインでの勉強会を軸に、これまで地理的な理由で参加できなかったユーザも含めた ST2 ユーザとの交流・情報交換を図っていく。
```

　といった話をさせていただきました。  

　プレゼン後 ST2 メンテナの [JP Bourget 氏](https://github.com/punkrokk) から「何か我々で協力できることはないか」といった質問を頂きました。

　これに対して『日本の勉強会にオンラインで参加してもらえると嬉しいかも』と口走ってしまいましたが、すぐに [2017 年の ST2 勉強会](https://connpass.com/event/52313/)に Dimitri Zimine 氏が来てくれた際を思い出し『ただ日本にはまだ言語障壁があるので、せっかく喋って頂いても理解されない可能性がある』と言ったところ、Dimitri から以下のコメントがありました。

![](https://github.com/stackstorm-japan/stackstorm.jp/blob/master/static/img/20200928/dimitri_message.png?raw=true)

　「ほとんどのアメリカ人も僕の言っていること理解していないよ（笑）」

　その場での具体的な提案はできませんでしたが、今回の TSC ミーティングによって開発コミュニティとの協力関係を築くことができたので、今後もゆるーく活動を続けていこうと思います。
　  
　  

### もくもく会（定期）実施のお知らせ

　こうした状況を踏まえ、気軽に StackStorm ユーザ同士がコミュニケーションや情報交換ができるよう、以下の Discord サーバをご用意致しました。

https://discord.gg/mFnsb9

　またここで、日本語でのユーザ同士の相談や簡単なオンライン勉強会が気軽にできるよう、**毎週木曜の 18:00 ~ 19:00** にもくもく会を開催致します。当該 Discord サーバの `勉強会/もくもく会` のボイスチャンネルを選択されれば、こちらにご参加いただけます。

![](https://github.com/stackstorm-japan/stackstorm.jp/blob/master/static/img/20200928/discord_ss.png?raw=true)

　開催するといっても、基本的には大山（他）がメンター役として待機し、参加者のご質問に随時お応えするという、ゆるい感じで開催致します。もし StackStorm でわからない、困ったことがあるといった方だけでなく、ST2 ユーザとして他のユーザとお喋りしたいといった方も、ぜひこちらをご活用ください。  
　またメンター役になっても良いという方も大歓迎です。メンター役を引き受けてくださった方へ、ユーザ会から素敵なプレゼントをご用意しております。

　オンサイトでの交流がしづらい状況となってしまいましたが、逆にこれまで地理的な問題でご参加いただけなかったユーザの方々もご参加頂けるよう、オンラインでのカジュアルな交流や情報交換ができるような活動を続けていきたいと思いますので、引き続きどうぞご参加・ご協力のほどお願い致します。
