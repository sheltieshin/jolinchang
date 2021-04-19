# jolinchang

version: '2'
services:
  db:
     image: mysql
     environment:
        MYSQL_ROOT_PASSWORD: 123456
  admin:
     image: adminer
     ports:
       - 8080:8080


ctrl+c: shut down powershell
terminal分成前端後端
ctrl+c:shut down結束前端

瀏覽器輸入localhost:8080 叫出mysql資料庫


docker-compose -f dockercompose.yml -d  ()

d
