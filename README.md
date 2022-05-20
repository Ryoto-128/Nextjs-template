# Nextjs-template

## 必要要件
- Docker
- Docker-compose

## 実行手順
### 実行モードの設定
実行モードに合わせて、コメントアウトを変更
```
# kikicomi-prototype-front_end_server/.env

~
# exec type
NEXTJS_EXEC_TYPE=dev
# NEXTJS_EXEC_TYPE=build
# NEXTJS_EXEC_TYPE=start
# NEXTJS_EXEC_TYPE=lint
```

### 初期実行
```
# bash
docker-compose run --rm nextjs cd kikicomi-prototype-front_end_server && npm install
docker-compoes up --build -d
```

### 通常実行
```
#bash
docker-compose up -d
```

## 開発モード（dev）でのアクセス方法
```
localhost:3000
```
