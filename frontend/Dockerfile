# 使用するNode.jsのバージョンを指定。'lts'は最新のLTS(Long Term Support)バージョンを意味します。
FROM node:lts

# 作業ディレクトリを設定
WORKDIR /app

# package.jsonとpackage-lock.jsonをコピー
COPY package*.json ./

# 依存関係をインストール
RUN npm install

# すべてのファイルをコピー
COPY . .

# 開発サーバーを起動
CMD ["npm", "run", "dev"]
