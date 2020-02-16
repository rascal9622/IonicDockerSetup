# IonicDockerSetup

## 各種使い方

### セットアップ方法
下記の環境変数を変更し、以下のコマンドを実行  
./setup

### 削除方法
./unset

### 接続方法
./bin/exec

### 環境変数
vi env  
 export IMAGE_NAME="ImageName"  
 export PROD="ionic"  
 export PORT="PortNumber"  

### 日本語対応
export LANG=C.UTF-8  
export LANGUAGE=en_US:

## ionicコマンド(簡易)

### プロジェクト作成
ionic start --type=ionic-angular

### WebAppとして実行
ionic serve --external

### iOSアプリとしてビルド
ionic cordova build ios --prod
