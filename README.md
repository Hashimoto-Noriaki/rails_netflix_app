## 環境構築(docker)
### ビルド
```
docker compose build
```

### 起動
```
docker compose up -d
```

### サーバー起動
```
 docker compose run web rails s
 docker compose run web rails server
```

### サーバー停止
```
docker compose down
```

### DB作成とマイグレーション実行
```
 docker compose run web rails db:create
```
