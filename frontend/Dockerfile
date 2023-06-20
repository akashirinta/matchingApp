# ベースとなるイメージを指定
FROM node:14

# 作業ディレクトリを設定
WORKDIR /app

# 依存関係をインストール
COPY package.json package-lock.json /app/
RUN npm install

# プロジェクトファイルをコピー
COPY . /app/
