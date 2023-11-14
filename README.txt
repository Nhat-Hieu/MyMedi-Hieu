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
B2: git clone <link fork Github của Member>
B3: cd <folder>/
>>> Chuyển sang thư mục làm việc
B4: git remote add leader https://github.com/minhkhanh-coder/MyMedi.git
B5: git remote -v
B6: git checkout -b <nhánh phụ>
B7: code .
>>> Mở folder - chỉnh sửa
B8: git add .
B9: git commit -m"message"
B10: git push origin <nhánh phụ>
>>> Push code lên Github
B11: git pull
>>> Pull code về máy

____________________ Pull code Leader về fork Member ____________________


____________________ Commit ____________________
$ git commit -m"message"
Tạo cái mới: Create <file>.<đuôi> hoặc folder <tên folder>
Chỉnh sửa: Update <file>.<đuôi>

____________________ Video Tutorial ____________________
Link video: https://drive.google.com/file/d/1l0NgA9hdfluyVHUaP9EtMhRb6rC6Or4V/view?usp=drive_link

____________________ Note ____________________
Phần push code lên của Leader cũng giống như Member
> Đều phải $ git add .
> Với $ git commit -m"message"

____________________ End ____________________
Have a nice day! Dear Khanh.
