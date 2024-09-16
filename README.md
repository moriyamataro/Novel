# novel
- これはgitコマンドやGitHubやマークダウン記法が使える人向けの小説テンプレートです。
- 小説執筆用テンプレート。エディタはVScode、VScodeプラグインは[novel-writer](https://marketplace.visualstudio.com/items?itemName=TaiyoFujii.novel-writer)を想定。 
- ライセンスは[MITライセンス](https://licenses.opensource.jp/MIT/MIT.html)

# Usage
## 1. テンプレートのレポジトリをクローン
``
git clone https://github.com/moriyamataro/novel.git
``
- ローカルのPCに保存するだけの人は問題ないが、GitHubレポジトリなどを用いてリモートリポジトリで管理する人はプライベートリポジトリ（非公開）にして使うことを推奨。
- 一番簡単なのは、GitHubのRepository templateの機能を使う方法である。このレポジトリをフォークして、SettingのところでTemplate repository にチェックを入れる。それ以降は作品を作るたびに、フォークしたレポジトリをテンプレートに指定して、Privateにチェックを入れて、レポジトリを立てれば良い

## ネタだし
- 紙のメモにメモを書きまくる、1_Today/Today.mdに整理する。Today.mdには今日の日記みたいなことも書いて良い。なんでも書いて良い
- 今日はネタが浮かばないとか、作品に関連する情報などをマークダウンに投げるように書く。紙のメモも書く。
- その日の作業が終わったら、2_Memo/Memo.mdにコピーして、Today.mdの中の文章は消す。次の日また同じように書く。
- vscode上でマークダウンでメモ書きしているので「折りたたみ」できるのがこのやり方の良いところで

## ブロック分け
- ネタが溢れてきたら、小説をブロック分けする。2_Memo/Block.mdに書いてみてください。
- 詳しいことは[円城塔先生の記事](https://scrapbox.io/enjoetoh/20230825_%E3%82%B2%E3%83%B3%E3%83%AD%E3%83%B3SF%E8%AC%9B%E5%BA%A7%E7%94%A8)に書いてありました。

## 初稿
- 3_jissaku/title.txtに書いてください。
- novel-writerのプラグインを入れたvscodeなら、色々アシストしてもらえます。

## 改稿
- 改稿が多い場合は最初にgit cloneした後に、ブランチで「1.0」とか「draft」とか書いて、ブランチを切っておきましょう。
- 改稿のたびに、ブランチを作成して、適宜mainブランチにマージさせましょう

## 投稿
- 人間に提出した原稿は齟齬が起きないよう、4_submitブランチ内に.txtと提出したファイル（PDF）と共に保管しておきましょう