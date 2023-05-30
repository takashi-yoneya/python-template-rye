# Pythonプロジェクトテンプレート

Projectで汎用的に活用可能なテンレートです。

パッケージ管理ツールとして、Ryeを使用しています。

# 前提ソフトウェア

以下のソフトウェアを使用しますので、事前にインストールしてください。

- rye

以下はryeを使用して自動的にインストールされます。
- python 3.10+
- pre-commit


# How to use

envファイルをコピーして作成する。

```bash
cp .env.example .env
```

必要パッケージ等をインストールする。

```bash
make install
```

動作確認のために、main.pyを実行します。

```bash
make run_main
```
