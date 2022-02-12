# docker-doc


## docker compose

### 執行
docker-compose up

### 背景執行
docker-compose up -d

### 停止
docker-compose stop

### 移除 docker compose
docker-compose down

### 移除volume
docker-compose down -v

### 列出containers
docker-compose ps

### 查 log
docker-compose logs

### 持續監控 log
docker-compose logs -f

### 相當於 docker exec (會配置一個 TTY)
docker-compose exec 

### 獲得一個 shell
docker-compose exec web sh

### 顯示執行程序
docker-compose top






