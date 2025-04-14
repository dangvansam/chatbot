## Hệ thống phầm mềm Chatbot và Xử lý văn bản đa năng

### I. Hướng dẫn cài đặt
#### 1. Download Model
Tải file sau: https://drive.google.com/file/d/1QPJ2JvJsQ_7ULFfI6EjSjwrvLqqEFT0B/view?usp=sharing lưu vào thư mục [./docker](./docker)
```bash
cd docker
unzip volumes.zip
```

#### 2. Build Docker Image
```bash
cd docker
docker compose build --parallel
```

#### 3. Khởi chạy API (lần đầu cần kết nối Internet)
```bash
cd docker
docker compose up -d
```

#### 4. Khởi chạy API (Offline)
```bash
cd docker
docker compose -f docker-compose-offline.yaml up -d
```

### II. Hướng dẫn sử dụng
#### 1. Phần mềm xử lý văn bản
1.1. Sửa lỗi chính tả
1.2. Tóm tắt văn bản