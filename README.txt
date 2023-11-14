____________________ Leader ____________________
B1: Tạo kho lưu trữ > terminal > git init > git add . > git commit -m"message"
B2: Tạo Repo mới trên Github
B3: Dán 3 dòng lệnh ở dưới vào terminal của kho lưu trữ >>> đẩy kho lưu trữ lên Github
	git remote add origin https://github.com/minhkhanh-coder/MyMedi.git
	git branch -M main
	git push -u origin main
B4: Tải code về
	git pull origin main 


____________________ Member ____________________
B1: fork (tạo repo mới)
B2: git clone <link fork Github>
B3" git remote add leader https://github.com/minhkhanh-coder/MyMedi.git
B4: git remote -v
B5: git checkout -b <nhánh phụ>
B6: git push origin <nhánh phụ>
B7: git pull

____________________ commit ____________________
git commit -m"message"
Tạo cái mới: Create <file>.<đuôi> hoặc folder <tên folder>
Chỉnh sửa: Update <file>.<đuôi>