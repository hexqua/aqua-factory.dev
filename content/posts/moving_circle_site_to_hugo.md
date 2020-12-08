---
title: "へろうわーるど的な"
date: 2020-12-08T12:13:01+09:00
weight : 1
tags: ["雑記"]
author: "Aquid"
showToc: false
TocOpen: false
draft: false
hidemeta: false
disableShare: false
comments: false
---

# 経緯とか

とりあえずレンタルサーバーにHTML書いて置くのは流石にちょっと時代を感じてしまうので[相方のページに感化され](https://www.agate-pris.dev)作成。

個人SNSアカウントは日常的な物が多いので、いわゆる実績系はこちらにホイホイ置いて進捗報告してもいいのやもしれません。 運用は未定。

# 作りとか

大方[相方のページ](https://www.agate-pris.dev/posts/get-domain-with-google-and-build-website-with-hugo/)を参考に[Hugo](https://gohugo.io/)を採用し、[Google Domains](https://domains.google/)でドメイン取得して設定。

ページ管理は[GitHub](https://github.com/)上にて、デプロイは[GitHub Pages](https://docs.github.com/ja/free-pro-team@latest/github/working-with-github-pages/about-github-pages)に対して[GitHub Actions](https://github.co.jp/features/actions)を使ってあれこれ。 リポジトリはどうせ公開情報しかないため、1個publicで運用。

テーマはあまり個人サイトじみないように、且つブログっぽくも扱え独立したページも生成できるように[PaperMod](https://github.com/adityatelange/hugo-PaperMod)を採択。 なんかシンボルマークみたいなのがあればアイコンをババーンと出す[PaperModのProfileモード](https://adityatelange.github.io/hugo-PaperMod/posts/papermod/papermod-features/#profile-mode)みたいなのも使ってみたいんですが、共用のソーシャルアカウントとかもないので取りやめ。

DNS周りでトラブル引いたりイマイチデプロイ周りの仕組みを理解してなかったりテーマのCSSが適用されんかったりでほぼ丸一日取られた形になりました。 つらい。

# とりあえず今後

今の[レンタルサーバーのページ](https://aquafactory.x0.com/)は半年ぐらいは残しておく予定です。 [ぷろりぷのページ]({{< link url="repliser/" >}})はこのまま動けば使い続けます。 ニコニコ動画の埋め込みが機能してないのはニコニコ側が悪いと思うので対応しません。

Hugoの運用辺り慣れてきたらもうちょっとテーマなりなんなり差し替えたりしたいかなとは思いますが、技術的なものはほぼ書く予定はありません。 日常は気が向いて長文を書きたくなったらこちらを使うかもしれませんが、基本は制作進捗で運用したいなぁとは思ってます。

現状の制作進捗はそろそろイラスト発注をしたいところ。 発注にあたって1年以上放置されてるページでは流石にまずかろうというのもあって今回のサイト移転が絡んでたりします。 見栄っ張りですね。