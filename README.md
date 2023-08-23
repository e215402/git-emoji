
## Emoji Prefix

commitメッセージのテンプレート<br>
メッセージの頭に追加する

## 設定方法

```.commit_template```ファイルをダウンロード
gitconfigファイルに以下を追加
```
$ vim ~/.gitconfig
```
以下を書き込む
```
[commit]
    template = ダウンロードしたディレクトリ/.commit_template

```
これでgit commitしたときに，emojiのチートシートを表示してくれる

## commitの時に使用するエディタ

いつも```git commit -m```でcommitしていたから気が付かなかったが<br> 
git commitで使用されるエディタがnanoであり使いずらかったので
以下のコマンドでvimに変更した

```
$git config --global core.editor "vim"

```
## 使用例

今回READMEを編集した場合commitメッセージは```:book: edit READEME```となる


## 絵文字一覧
| type                          | emoji |
|-------------------------------|-------|
| 初めてのコミット（Initial Commit）      | 🎉    |
| バージョンタグ（Version Tag）        | 🔖    |
| 新機能（New Feature）              | ✨    |
| バグ修正（Bugfix）                 | 🐛    |
| リファクタリング(Refactoring)      | ♻️    |
| ドキュメント（Documentation）       | 📚    |
| デザインUI/UX(Accessibility)       | 🎨    |
| パフォーマンス（Performance）       | 🐎    |
| ツール（Tooling）                 | 🔧    |
| テスト（Tests）                   | 🚨    |
| 非推奨追加（Deprecation）          | 💩    |
| 削除（Removal）                   | 🗑️    |
| WIP(Work In Progress)            | 🚧    |
|誤字の修正(FIx typos)              | ✏️    |
|簡単な修正(Simple fix)             | 🩹  |
