---
layout: post
title: "Rubyとの付き合い"
date: 2013-03-18
comments: true
categories: [life]
---
もうすぐ社会人になってから4年が経とうとしている。

 <!--more-->

その社会人生活の中で「Ruby」という素晴らしいツールと触れていた時間がとても多かった

振り返ってみたので、形に残そうと思う。

長文になっちゃいそうだ

### ボクはRubyが好きだ
`Rubyをキメると気持ちいい`

RubyKaigi2008のときにまつもとゆきひろさんの名言

Rubyを書いていると楽しい

Rubyっぽく書けたらすごく嬉しい

ボクはRubyが好きだ。

Rubyを使っている人たちも好きだ

Rubyコミュニティが好きだ

### 仕事の武器としてのRuby

現在Rubyを1つの武器として、仕事をしている。

最近の嬉しいニュースとして

2012年の12月に片手間で進んだプロジェクトが最近リリースされ、はじめてのユーザーがついたらしい。嬉しい。

学生時代はRubyを触ったことなんかなかったが、今や立派な武器になっている。

#### きっかけ
2009年の4月、アルバイトをしていた現在の会社に新入社員として入社した。

当時は日本の家庭に配布されるWindowsアプリケーションの検証作業をしていた。

大黒柱的な存在のプロジェクトの一員として時間を過ごしていた。（はず）

ただ、Excelの表を埋める作業というのはボクは好きになれず、楽しくはないのでモヤモヤしてた。

風通しのよい職場なので日報や呑み会の席で「コード書きたい！」的なことを延々と言ってた。

時には社長に、時には開発の責任者に、時にはプロジェクトのマネージャに

今思うと、よく言ってたなぁ

そしたら6月の夜中に、当時のマネージャから異動の話をもらった。

そのシーンがすごく印象的で今でも覚えている。Rubyと付き合い始めるきっかけである。

異動先のプロジェクトは研究開発プロジェクト。

そこで[Ruby on Rails](http://rubyonrails.org)を使って世界を変えるアプリケーションの開発をすることになった。

#### 挑戦と野望

 * 当時のスキルセット
  * C/C++ (学校で習う程度)
  * C# (趣味でアプリケーション作る程度)
  * Windows (Win32 API叩いて遊ぶ程度)
  * Linux (基本的な操作がCUIでできる程度)
  * HTML/CSS/Javascript (趣味でホームページ作る程度)

そこはとても苦しく、楽しい世界だった。

 * Ruby
 * Ruby on Rails
 * Webアプリケーション
 * MVC
 * MySQL

全てが新鮮で、全てが力不足で、全てが刺激的だった.

環境構築には当たり前のように躓き、貧弱な`.vimrc`で戦っていたなぁ…

当時は`bundler`なんてなかったから、アプリケーションの起動にすら苦労した記憶がある

若いメンバーで構成されているプロジェクトで、社内にRubyのエンジニアはほとんどいなかった。

なるべくして、Rails Wayから外れたアプリケーションになっていた。

ボクとしては、すごくチャンスに感じていて

これなら、社内で(Ruby on Railsの)エンジニアとしてトップに立てるんじゃないかと思って、そこからRubyとの激しい付き合いが始まった。

社内で勉強会を開催したり、趣味でアプリケーションを作ってみたり、来週作るであろう機能を家でプロトタイピングしてみたり

とにかく手を動かしていた印象がある。

未熟者のボクに多くのことを教えてくださった、

プロジェクトのメインプログラマの人たちがやめるタイミングが1つの進化のきっかけだったのかもしれない。

よりRubyやRailsの知識が求められるようになって、より高度なことを任せてもらえるようになった。

疑問の答えを持っている人が社内にいなくなったときに、外の世界へ飛び出した。

 * RubyKaigi
 * Coffee.rb
 * デブサミ
 * etc...

外の世界は刺激的で、何かを患っている人がいっぱいいて、仲間がいて、楽しかった。

#### 暗黒魔法
Ruby on RailsにはPluginという機構がある。

事業の拡大とともにアプリケーションを使ってくれる人が増え、要望も増え

ブランチ開発にも飽きたのでプラグインで差分を吸収できるようにしたかった。

Pluginを使うにはRails2.3に上げる必要があったので、脱線しているRailsレガシープロジェクトを2.3に上げる必要が出てきた。

すげー苦しかった。(笑)

 * そもそもアプリケーションが起動しない
 * ありがちなメソッド名のヘルパーがRailsに追加されて(プロジェクトで使ってて)動かなかった
 * 動かないGemは出てきてモンキーパッチを当てる
 * そもそも通ってないテストコードがいっぱいいた
 * 嘘をついているコメント
 * 意図が分からないコード

こんな状態なので作業自体が見積もれなくて、進捗も分からなかったし有識者もいなくて、困った。

結果的にプロジェクトへの理解は深まったし、Railsにも少し詳しくなれた気がする。

そうそう、この時のハイライトといったらとある目的を達成するために

`image_path`とか`image_tag`に`alias_method_chain`とかしてる当たりがエグい

黒魔術とかそういう次元じゃなくて暗黒魔法だった。今もそれを利用されてて、泣きたい。

#### 自由な空
2年目の3月に大きな挑戦のチャンスをもらえた。

スマートフォンの法人利用が増えてきて、新たなビジネスの波が生まれた。

そのとき、以前から関わっているプロジェクトのスマートフォン対応が必要になった。

ユースケースも、機能も違うこともあり、レガシープロジェクトにそれをのっけるよりは

新たなプロジェクトとして１から作ることになった。

当時でてきたRails3での初プロジェクト、多くの部分を開発させてもらえた。

多少の不安と、ワクワク、ドキドキに支配された時間だった。

なにより、足枷がない、フットワークが軽い状態の開発は初めてで、とても幸せな時間を過ごしていたんだなと、今になって思う。

当然エンジニアがいないから、開発は楽じゃなかったけどこの経験は今の生活にも活きてきている。

この時バージョン管理はGitになったし、Hamlを標準で使うようになったし、Hudson(現Jenkins)を導入した。

#### 進化の速度
作ったプロダクトが基盤となって、いろんなプロダクトが生まれた。

当時の流行りは今の流行りじゃないことが多くて、そのまま利用されると少し恥ずかしさが残ってしまう。

ただ、進化が速いところはとても好きだ。

Ruby on RailsやWebはいつでもボクを挑戦者にしてくれる。

2ヶ月前のbetterは今のdefactだったり、オワコンだったりと怠けるとすぐに時代遅れになってしまう。

とても楽しい世界だ

#### 楽をする

人生は短い

自分のやりたいことをやるに人生は短すぎる。

ボクには面倒な作業で楽をするためのツールとしてRubyがいた

毎日5分かかってた作業が30秒で終わるようになったらそれはとても素晴らしいことで

素晴らしいことを大好きなRubyで行えるということはとても素晴らしいことだと思う。

毎日の退屈な5分間を無くすために、好きなエディタ、好きな言語で楽しくプログラミングをして、時間を使うのはとても有意義だ。

テスト用のアプリ、オレオレ７つ道具、Rubyで解決できる問題も手段もいっぱいある。


## なぜRubyだったんだろう まとめ
 * まとまらない
 * Ruby on Railsで社内でトップになれるんじゃないかという野望
 * Rubyを取り巻く環境が好き
 * Rubyを書いていると楽しい
 * 継続は力なり
 * 人生は短い!
 * これからもRubyと付き合って行きたい

全然まとまらなかった。

とりあえずこのへんで

押忍!!
