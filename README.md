# Javaで出来ること

####どんなパソコンでも動く！
- パソコンのプログラムというのは、OSやCPUが違うと動きません。なぜなら、CPUが理解できる命令や、OSの中に用意されているさまざまな機能というのはOSやCPUが異なればまったく違ってしまうからです。ですから、例えばWindowsのソフトをMacにコピーして動かそうとしてもできないのですね。ところが、Javaで作ったプログラムは、どんなOS、どんなCPUでも実行でいるという不思議な性質を持っています。Javaで作ったプログラムは、全く同じものをWindowsからMacにコピーすれば、そのまま動いてしまうのです。


####Javaは「ソフトパソコン」で動く
- なぜ、そんな不思議なことができるのか？　それは、Javaの中に「架空のパソコン」が用意されているからです。……つまり、Javaのプログラムは、パソコンの中にソフトウェアのパソコンを作り、その中で動くようになっているのですね。このため、どんなパソコンであっても、そのパソコン用の「ソフトパソコン」さえインストールしてあれば、全く同じJavaのプログラムが動いてしまう、というわけです。このソフトパソコンは、専門用語で「Java仮想マシン（Java Virtual Machine、略してJVM）」と呼ばれています。


####パソコンでなくても動く！
- ということは、「ソフトパソコン」さえあれば、別にパソコンでなくてもいいんじゃ？なんて思った人。実は、その通り！　一番身近なものとしては「Javaのソフトパソコンを組み込んだ携帯電話」がありますね。また、最近ではカーナビにJavaを組み込んだりしたものも登場しています。Javaが使える機器はどんどん拡大しているのです。


####インターネットと仲がいい
- Javaのもう一つの特徴、それは、インターネットととても相性がいい点です。「どんなパソコンでも（パソコンでなくても）動く」というのですから、インターネットのサーバ（インターネットのさまざまなサイトやサービスを実行しているコンピュータ）でも動かないはずはありません。そんなわけで、インターネットの世界で何かのプログラムを作ろうというのにJavaはうってつけなのです。


# javaScriptで出来ること

####JavaScriptは、Webコンテンツに動きを与えた
- JavaScriptの登場以前、Webブラウザは文章や画像などの静的なWebコンテンツしか扱えませんでした。1995年、Netscapeのブレンダン・アイク（Brendan Eich）は、Webコンテンツを動的に扱うためのスクリプト言語としてLiveScriptを発表し、Netscape Navigator 2.0というWebブラウザに搭載しました。NetscapeはJavaを開発していたサン・マイクロシステムズと技術提携を行い、LiveScriptはJavaScriptという名前に変更されました。勘違いされやすいのですが、JavaScriptとJavaは言語としてはそれほど似ていません。JavaScriptという名前は、「Javaよりも初心者やデザイナーが容易に利用できる言語である」という当時のマーケティング的な思惑から付けられたのです。


####JavaScriptを使うことで表現力が向上する
- JavaScriptが搭載される以前のWebブラウザでは、URIを直接指定するか、ハイパーリンクをクリックした時にのみ、Webサーバと通信して新しいコンテンツを取得します。また、新しいコンテンツを取得した場合は、Webブラウザに表示されているコンテンツ全体が新しいものに置き換わります。この仕組みは、非常に単純で理解しやすいのですが、Webアプリケーションを作る場合には、デスクトップアプリケーションに比べて、必ずコンテンツ全体が置き換わってしまうという制約がありました。これに対してJavaScriptを利用すると、Webサーバと通信しなくてもコンテンツを更新することができます。このように、クライアントマシンで利用されるJavaScriptをクライアントサイドJavaScriptと呼びます。
