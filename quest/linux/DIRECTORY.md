# ディレクトリを操作できる

Linux にログインしてターミナル上で行ってください。

## 1. 現在のディレクトリ

自分が現在いるディレクトリを表示してください。
/home/kejimarino

## 2. ルートディレクトリ

現在のディレクトリから、"/" ディレクトリに移動してください。
cd /

## 3. ホームディレクトリ

現在のディレクトリから、ホームディレクトリに移動してください。
cd

## 4. 一つ上のディレクトリ

現在のディレクトリから、一つ上の親ディレクトリに移動してください。
cd..

## 5. ディレクトリの内容

現在のディレクトリの内容を表示してください。
ls

## 6. 隠しファイル

現在のディレクトリの隠しファイルを含む全てのファイルとディレクトリを表示してください。
ls -a

## 7. 詳細なリスト形式

"/etc" ディレクトリの内容を、詳細なリスト形式で表示してください。
ls-l

なおわからない場合は、"man ls" コマンドで ls コマンドの詳細を確認することができます。"List files in the long format" といった説明のあるオプションを付けてください。

## 8. ディレクトリの作成

ホームディレクトリに移動し、"projects" という名前のディレクトリを作成してください。
mkdir projects

## 9. ディレクトリの削除

作成した "projects" ディレクトリを削除してください。
rmdir projects
