"minio"が何かを簡潔に紹介する
詳細な説明は[minio](https://min.io/)をご覧ください。

# DEMO
 
GUIで操作/確認可能。
<img width="1440" alt="スクリーンショット 2021-03-01 21 18 14" src="https://user-images.githubusercontent.com/54725215/109496183-a895a680-7ad3-11eb-92ac-7ed7ac443111.png">

 
# Features
 
S3と同じ環境ををローカル環境で無料で使用可能。
プログラムからの操作はaws-sdkを使用することができる。
詳細な説明は[aws-sdk](https://aws.amazon.com/jp/getting-started/tools-sdks/)をご覧ください。
 
# Requirement

* docker
* docker-compose
installなどは[docker](https://hub.docker.com/)をご覧ください。
 
# Installation
 
```bash
docker-compose up -d
```
 
# Usage

```bash
git clone https://github.com/Hidemasa-Kajita/docker-minio.git
cd docker-minio
docker-compose up -d
```

ブラウザで[localhost:9000](http://localhost:9000)へアクセス。
ACCESS_KEYとSECRET_KEYを入力しログインして使用する。
 
# Note
 
特になし。
