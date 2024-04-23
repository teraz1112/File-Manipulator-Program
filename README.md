# File-Manipulator-Program

## 概要
コマンド入力を利用してファイル操作ができるスクリプト

## デモ
![output](https://github.com/Aki158/File-Manipulator-Program/assets/119317071/1fd77005-e743-4fce-bfc1-37ea19c7c4ab)

## 説明
コマンド入力を利用してファイル操作ができるスクリプトです。

コマンドは、下記の4つを利用することができます。

- reverse
- copy
- duplicate-contents
- replace-string


## インストール

1. リポジトリをクローンする
```
git clone https://github.com/teraz1112/Video-Compressor-Service.git
```

2. クローンしたリポジトリへ移動する
```
cd Video-Compressor-Service
```

## 使用方法
1. ファイルを用意する
2. スクリプトを実行する
3. 生成されたファイルを確認する

## 使用技術
<table>
<tr>
  <th>カテゴリ</th>
  <th>技術スタック</th>
</tr>
<tr>
  <td>開発言語</td>
  <td>Python</td>
</tr>
<tr>
  <td rowspan=2>インフラ</td>
  <td>Ubuntu</td>
</tr>
<tr>
  <td>VirtualBox</td>
</tr>
<tr>
  <td rowspan=2>その他</td>
  <td>Git</td>
</tr>
<tr>
  <td>Github</td>
</tr>
</table>

## 機能一覧
| 機能 | 内容 |
| ------- | ------- |
| reverse | inputpathにあるファイルを受け取り、outputpathにinputpathの内容を逆にした新しいファイルを作成します。 |
| copy | inputpathにあるファイルのコピーを作成し、outputpathとして保存します。 |
| duplicate-contents | inputpathにあるファイルの内容を読み込み、その内容を複製し、複製されたinputにn回複製します。 |
| replace-string | inputpathにあるファイルの内容から文字列'needle'を検索し、'needle'を'newstring'に置き換えます。 |
| エラーハンドリング | コマンドが正しく入力されていない場合は、`Command not found...`というメッセージが表示されて終了します。<br>コマンドの入力は、認識されていないため、ファイルは生成されません。 |

## 📑参考文献
### 公式ドキュメント
- [Python](https://docs.python.org/ja/3/)

### 参考にしたサイト
- [Python_Download](https://www.python.org/downloads/)
