# Khởi tạo Git trong thư mục local
git init

# Thêm tất cả các file vào khu vực chuẩn bị (Staging area)
git add .

# Lưu lại các thay đổi kèm theo ghi chú
git commit -m "Nộp bài tập lần đầu"

# Kết nối với repository trên GitHub (Thay link bằng link bạn vừa tạo)
git remote add origin https://github.com/ten-user/ten-repo.git

# Đẩy mã nguồn lên GitHub
git push -u origin main
