# よくつかうコマンド

## ファイルやディレクトリ（フォルダ）

ディレクトリ（フォルダ）移動
```bash
# XXXへ移動 ※XXXは移動先のディレクトリ
cd XXX
# ひとつ上のディレクトリへ移動
cd ..
```

ディレクトリ（フォルダ）作成
```bash
# XXXというディレクトリを作成 ※XXXはディレクトリの名前
mkdir XXX
```

ファイル作成
```bash
# XXXというファイルを作成 ※XXXはファイルの名前
touch XXX
```

ファイル一覧を確認
```bash
ls
```

## Python

Pythonのプログラムを実行
```bash
# XXXというファイルを実行 ※XXXはファイルの名前
python XXX
```

Pythonの仮想環境（作業場所）を作成
```bash
# ディレクトリを作成
mkdir XXX
# ディレクトリを移動
cd XXX
# 仮想環境を作成
python -m venv .venv
# 仮想環境を有効化
. .venv/Scripts/activate
# 仮想環境を無効化
deactivate
```

Pythonのモジュール（拡張機能）をインストールする
```bash
# XXXというモジュール（拡張機能）をインストール ※XXXはモジュールの名前
pip install XXX
```

## Git

クローン（最初に作業場所をもってくる）
```bash
# XXXというリポジトリを自分のパソコンにもってくる
git clone XXX
```

作業場所にはいる
```bash
# XXXというリポジトリにはいる
cd XXX
```

インターネットのファイルをもってくる
```bash
git pull
```

インターネットにファイルをアップロードする
```bash
git add .
git commit -m "update"
git push
```
