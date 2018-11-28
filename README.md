## 環境要求
1. docker-Engine 18.09.0
2. docekr-compose 1.23.1
3. Mac

## 安裝環境
1. Apache2
2. php 7.0-fpm
3. Mysql 5.7.22
4. RabbitMQ last version
4. phpMyadmin last version
5. Memcached last version
6. Workspace last version 

## 使用方法 
1. git clone 相對應版本的程式。
2. 至安裝系統目錄 ``` cd ./laradock/ ```
3. 修改 .env 設定 
    1. ``` APP_CODE_PATH_HOST=程式目錄  ```
    2. ``` DATA_PATH_HOST=資料庫目錄 ```
3. 啟用 Server ``` sh start.sh ```
4. 執行 migrate(第一次) ``` sh migrate.sh ``` 

## 指令集
啟用Server
``` sh start.sh ```

關閉Server
``` sh stop.sh ```

執行migrate
``` sh migrate.sh ```

啟用Consumer
``` sh consumer.sh ```

刪除All Docker ps
``` sh rmps.sh ```

刪除All Docker Image
``` sh rmimage.sh ```

使用phpmyadmin
``` http://localhost:9001/```


