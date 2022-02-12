# 我的 docker 文件


## docker compose

### 執行 compose
docker-compose up

### 背景執行 compose
docker-compose up -d

### 停止 compose
docker-compose stop

### 移除 compose
docker-compose down

### 移除 compose volume
docker-compose down -v

### 列出 containers
docker-compose ps

### 查 compose log
docker-compose logs

### 持續監控 compose log
docker-compose logs -f

### 執行 compose (會配置一個 TTY)
docker-compose exec 

### 獲得一個 shell
docker-compose exec web sh

### 顯示執行程序
docker-compose top

### Docker Compose 環境變數

```
 environment:
  RACK_ENV: development
  SHOW: 'true'
  SESSION_SECRET:
```
  
```
environment:
  - RACK_ENV=development
  - SHOW=true
  - SESSION_SECRET
```





