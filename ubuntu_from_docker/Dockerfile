# Docker イメージの指定
FROM python:3.8

# イメージにメタデータを追加
## 開発者情報やバージョンなどを書くと良さげ
LABEL maintainer="ta-ryo"

# apt-getを用いてライブラリのインストール
RUN apt-get update && apt-get install -y \
    apt-utils \
    mecab libmecab-dev mecab-ipadic-utf8 \
    git curl make sudo \
