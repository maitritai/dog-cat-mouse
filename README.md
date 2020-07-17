This project is just demo how to use git

mkdir 1-commit: tạo mục 1-commmit


git init: chạy git
git status: kiểm tra có sự thay đổi file hay ko
git add: gộp file vào commit
	git add . : add tất cả file mới vào
	git add (tên file 1) ( tên file 2)....: add nhiều file

git commit: đóng khung tất cả file đc gộp thành 1 object 
	vd: git commit -m "Add Cat module"
	git commit -m 'Fix: Missing exports' :  xem số thay đổi
git log: cho xem lịch sử commmit đã được tạo
git show: dùng show nd của commit
	vd: git show 8b4d863c58183870feec4e51c206d98284d6b57f( mã số của commit khi git log ra)
 git diff: xem nd của modified

 untrackfile: file mới tạo
 modified: file đã và bị chỉnh sửa