

## 依存関係を入れる
yarn install

## ローカルビルド方法

export NODE_OPTIONS=--openssl-legacy-provider
yarn build

### ローカルで確認

npx serve -s build


## デプロイ

Netlifyへデプロイされます。設定済み。

