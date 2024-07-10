## How to | วิธีใช้งาน
# 1. create .env file | สร้างไฟล์ .env เพื่อใช้เก็บข้อมูลสำหรับกำหนดใน mysql
# .env
MYSQL_ROOT_PASSWORD="root_pass"
MYSQL_USER="user_db"
MYSQL_PASSWORD="mysql_password"

# 2. docker command | คำสั่ง docker-compose  เพื่อใช้สร้าง images และ container | -d ให้ทำงานเบื่องหลัง
```bash
docker compose up -d
```

# optional , config config | *ไม่จำเป็น
```bash
git config --global user.name "First Last"
git config --global user.email "demo@example.com"
git config credential.helper store
```