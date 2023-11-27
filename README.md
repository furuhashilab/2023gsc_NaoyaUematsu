# 2022gsc_Naoya-Uematsu
## 2022年度 ゼミ論　レポシトリー

青山学院大学 地球社会共生学部 地球社会共生学科

植松尚哉/Naoya Uematsu

学生番号 1A120023

指導教員 古橋大地 教授

© Furuhashi LaboratoryNaoya Uematsu, CC BY 4.0

## 古橋ゼミ公式 LINE bot制作

## Abustract
本研究は古橋ゼミ公式のLINEbotを作成し、ゼミ生、古橋ゼミに興味を持ってくれれいる人に向けた快適な情報取得サービスの役割を提供することが目的である。

## Introduction
今回私が取り組んだのはLINEで使える古橋ゼミ公式bot作りである。LINE botとはLINE上にて自動でユーザーと会話し、ユーザーを助けてくれるプログラムのことである。一般的なメリットとしてコニュニケーションの活性化、ユーザーが気軽に意見を伝えてくれるようになる、ユーザーのニーズがわかりやすくなる、ユーザーが問い合わせをする心理的負担を軽減できる、多数のアクティブユーザーにリーチが可能であるというメリットが挙げられる。またそのようなLINE botを古橋研究室で作る意義としてはゼミ生を始め、ゼミに興味を持ってくれている人が便利になるという点が挙げらる。

## Method
今回LINE botを開発するにあたり大きく3つのプログラムを活用した。

### LINE Developers

一つ目はLINE Developers。これはLINEが提供しているさまざまな「プロダクト」を使って開発を行う、外部のデベロッパー向けのポータルサイトである。

### Make

二つ目はMake。Make (formerly Integromat)とは、ノーコードで異なるWebサービスやアプリケーションを連携させ、タスクの自動化の行うツールである。

### Google Apps Script
三つ目はGoogle Apps Scriptである。これはGoogleが提供する各種サービスの自動化、連携を行うためのローコード開発ツールである。

### 古橋bot
![EDE04071-701C-48D2-9644-2A2FF41EB9E0](https://user-images.githubusercontent.com/93098277/216643178-96800f58-3018-4520-91f3-05981b9d14c2.jpeg)

今回開発にMakeを使用したのは誰もが編集できるLINE botにしたかったからである。
![4F209B9E-5F2A-4866-A280-5C49D85EF43A](https://user-images.githubusercontent.com/93098277/216643308-ab59a825-b6db-4320-ab60-21e9e9037dbc.png)
Google スプレッドシートを仲介して返信するから仕組みで作ったため、スプレッドシートのURLを知っている人なら誰でもLINE botに語彙を追加できるようになっています。

また公式LINE独自のシステムであるリッチメニューも作成した。
![EB8B7AC0-BBAD-4154-BEC6-163013DD90F3](https://user-images.githubusercontent.com/93098277/216643520-b904f23d-b0a4-4220-b98f-8b71040750c6.jpeg)


VF画像保存用bot
![5358F229-476E-48E1-8BA1-C2924D9DBE7B](https://user-images.githubusercontent.com/93098277/216643559-2342dc38-e5c4-4040-967c-f83174d28212.jpeg)

今回はもう一つLINE上で送った画像をGoogleドライブに保存するシステムを持ったLINEbotを作成した。なぜこのbotを作ったのかというと撮った写真をGoogleドライブに保存し、共有する際スマートフォンであるとやりにくいからである。
![A280304A-1092-483B-AF45-9B9F23A26308](https://user-images.githubusercontent.com/93098277/216643676-1fba3050-2a0c-4e32-aabb-945122735d10.jpeg)

これはGASを使ってローコード開発し、送られた画像はドライブに保存されることに加え、スプレッドシートに記録される。

## Results
古橋bot
![D2F7761C-4703-4877-A251-A70AE4503EC0](https://user-images.githubusercontent.com/93098277/216643792-85664587-e0f7-4031-837d-a77a74d32733.jpeg)

VF画像保存用bot
 ![0E7E8F5B-6FCA-4209-AACB-E6CFC674BDBE](https://user-images.githubusercontent.com/93098277/216643929-7254a516-0d15-4c63-afb0-085c26e5f595.jpeg)


## Discussion
二つのbotの機能を一つのbotにまとめなかったのはLINE Developersで設定できるwebhookURLが一つだけだったからである。この課題を解決するためにはより高度なプログラミング技術が必要になる。

### 新規性
新規性という観点ではスプレッドシート経由にしたことにより、誰でもアクセスできるため新しいデータ保存の形になるのではないかと考えている。

## Conclusion
このLINE bot開発を通して私自身ノーコード、ローコードを使用した開発ノウハウ、ノーコードプログラムに関する興味、可能性、最低限のプログラミング知識の三点を学ことができた。また今後の展望としては
語彙を増やす
文字判定の強化
機能の追加（動画の保存、応募書類などを扱えるようにする）
2つのbot機能を合わせ持ったようなbot開発
の四点を考えている。

## 謝辞

本研究を進めるにあたり青山学院大学の古橋大地教授をはじめ多くの方々より多大な助言を賜 りました。厚く感謝を申し上げます。

## 参考文献・資料リスト

https://docs.google.com/spreadsheets/d/1-KPeyyQF3KV4s_NmFaP3G623imfeXKokKHbaBMsOPKA/edit

## プロジェクト管理

https://github.com/furuhashilab/2022gsc_Naoya-Uematsu

スライド

https://docs.google.com/presentation/d/1vEueKi70pyikVhniQt50v4zoqEtjzaMdIHcTpcf8eRs/edit

メディウム

https://medium.com/furuhashilab/古橋ゼミ公式-line-bot-df092748baed
