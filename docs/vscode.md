# Visual Studio Code

* https://code.visualstudio.com/

## テーマ

下記の色がすべて見やすいこと。そのようなテーマは現状 [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme) 程度しか存在しない。

| `editor.tokenColorCustomizations` | 概要
| --------------------------------- | ----
| `comments`                        | コメントの色とスタイルを設定します

| `workbench.colorCustomizations`       | 概要
| ------------------------------------- | ----
| `editor.selectionBackground`          | エディターの選択範囲の色。
| `editor.selectionHighlightBackground` | 選択範囲の同じコンテンツの領域の色。この色は、基本装飾が非表示にならないよう不透明にすることはできません。
| `editor.inactiveSelectionBackground`  | 非アクティブなエディターの選択範囲の色。この色は、基本装飾が非表示にならないよう不透明にすることはできません。
| `editor.findMatchForeground`          | 現在の検索一致項目のテキストの色。
| `editor.findMatchBackground`          | 現在の検索一致項目の色。
| `editor.findMatchHighlightForeground` | 他の検索一致項目の前景色。
| `editor.findMatchHighlightBackground` | その他の検索条件に一致する項目の色。この色は、基本装飾が非表示にならないよう不透明にすることはできません。
| `editorWhitespace.foreground`         | エディターのスペース文字の色。

> [!NOTE]
> `editor.findMatchForeground` と
> `editor.findMatchHighlightForeground` は内容が逆になっているバグがあるので注意。
>
> - [Swapped findMatch Foreground Colors · Issue #228782 · microsoft/vscode | GitHub](https://github.com/microsoft/vscode/issues/228782)

気分でテーマを変えることがあるので
`settings.json` を編集しなくても良いように､
テーマの設定のみで上記が完璧であること｡

完璧ではないが、その他のお気に入りのテーマは以下の通り。

* [1337 Theme](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Theme-1337)
* [3024 Theme Kit](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Theme-3024Kit)
* [Dracula Theme Official](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
* [Markdown Theme Kit](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Theme-MarkdownKit)
* [Material Theme Kit](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Theme-MaterialKit)
* [Panda Theme](https://marketplace.visualstudio.com/items?itemName=tinkertrain.theme-panda)
* [Predawn Theme Kit](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Theme-PredawnKit)
* [Tomorrow and Tomorrow Night Theme Kit](https://marketplace.visualstudio.com/items?itemName=ms-vscode.Theme-TomorrowKit)
