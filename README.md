1) Find and replace "yourdomain.com" and "www.yourdomain.com"

2) Open your "hosts" file and append:
127.0.0.1  yourdomain.com    www.yourdomain.com

3) Edit variables in .env file

4) Run cmd "docker-compose up -d"

P.S. If you want to reset MYSQL database, you need to delete folder "/DOCKER/MYSQL/data" and run cmd "docker-compose up -d"
