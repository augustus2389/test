# Terms

Repository (Repo): là thư mục dự án. Ở đây có thể hiểu là Folder Test là dự án thư mực và cũng là 1 Repo

Conflict: Xung đột

# Command

- git init: biến Repo của mình thành Git Repo và tạo thư mục con ẩn là .git

- git status: Trạng thái

- git add: Chuẩn bị lưu lại thời điểm của dự án

- git remote: Cho phép tạo, xem sửa xoá kết nối với Repo

- git commit --amend -m "Tên commit mới" : Thay đổi commit cuối

- git branch:

* git branch -m <Tên branch mới> : đổi tên branch
* git branch -d <Tên branch>: xoá local branch
* git branch -D <Tên branch>: cách xoá -d sẽ bị lỗi nếu như branch cần xoá chưa gộp thay đổi với branch khác sẽ lập tức báo lỗi vào yêu cầu gộp với
  branch khác thì với "-D" sẽ lập tức bị xoá kể cả chưa gộp với nhanh khác

- "--all" : Sẽ push lên tất cả các nhánh

* git push:

- git push delete <tên remote> <tên branch> : Xoá branch trên remote

- git push <Tên remote> <Tên branch>:<Tên remote branch>: Đổi tên remote branch

-- Helo
-- push
-adsad
ádasdsadasd
