# ClearVisionMod
BetterDiscord用テーマです。Zerthox氏のClearVisionをベースに、日本語環境用にカスタマイズ、軽量化を行っています。

# テーマの提要
基本的に最新版のClearVision_Mod.theme.cssを使用します。
ファイルの個別ページ（ https://github.com/rexent-gx/ClearVisionMod/blob/master/ClearVision_Mod.theme.css ）にアクセスした後、右上の「Raw」を右クリックし、「名前をつけてリンク先を保存」して下さい。
ダウンロードが終わったらCSSファイルをBetterDiscordのテーマフォルダにぶち込んで有効化して下さい。
色なんかはCSSをいじれば好みの色に変更できますので、背景に合った配色にすれば気持ちよくなれます。

# よくあるアレ
(´・ω・｀)「テーマフォルダってどこ…？」
BetterDiscord起動後、「設定→BETTERDISCORD欄のThemes→Open Theme Folder」でテーマフォルダがエクスプローラで開かれます。

(´・ω・｀)「背景画像変えたいンゴ」
CSS開いてbackground-imageのurl()部分のURLを好きな画像のものへ変えて下さい。HTTPSリンクじゃないと上手く表示されないよ！！
あるいは画像をBase64エンコードしてCSSに直接記述しちゃうと楽かも。早いし。ツール色々あるから探してみて下さい。( https://syncer.jp/base64-encoder とか)

(´・ω・｀)「テーマが一覧に表示されないんだけど」
再起しないと反映・読み込みされないよ。とりあえず再起動してみて下さい。
あるいは「.theme.css」が末尾にあるファイルしか読み込まれないので、ミスって「～.css」とかになってないかチェックしてみて下さい。
