# Full Source Code - Web Tiếng Anh

## Video Demo: https://www.youtube.com/watch?v=LO9gdY8DdhI

## Members

- Huỳnh Anh Tiên (Backend): https://www.topcv.vn/xem-cv/VwMCVwBVBwBbBwYMBFBVUwsCBwACAFkHUwkEAAddfa.
- Trần Hoàng Phúc (Frontend): https://i.topcv.vn/tranhoangphuc?ref=4882010.
- Nguyễn Trần Nhật Hào (Frontend): https://i.topcv.vn/nguyentrannhathao?ref=4880057.
## Deploy

- Yêu cầu: có cài Docker
- File nginx.conf: dòng 23 sửa lại thành tên miền của mình.
- Folder ssl: cung cấp key để chứng thực ssl tên miền.
- File docker-compose.yml: cung cấp env cho mấy cái để trống. 
- Tạo 2 folder chứa data cùng cấp với file docker-compose.yml:  mongo-database, mysql-database
- Chạy lệnh: docker-compose up -d.