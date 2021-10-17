## Tạo repository trên máy và đồng bộ lên repository trên mạng
- git init: tạo repository trên máy local
- git add . (add tất cả các file có thay đổi) / git add file1(tên file)
- git commit -m "tom tat noi dung của commit"
- git branch -M main (đổi tên master thành main)
Sau đó đăng nhập vào github tạo repository và sao chép địa chỉ liên kết ssh
- git remote add (tên liên kết) (địa chỉ liên kết ssh)
- git push -u (tên liên kết) main: dua code len github, gitlab


## Các lệnh git khác
- git log: viết tắt gl: xem lại lịch sử đã commit trên branch đang thao tác
- git reflog: xem lại tất cả lịch sử hoạt động, kể cả những commit đã xóa
- git reset --hard (commit id): reset chỉnh cả file và trạng thái file (trạng thái file gồm: U-untrack, M-modify, A-added, D-deleted đã được cho vào commit thì không hiện chữ gì)
- git reset (commit id): File vẫn giữ nguyên, lịch sử commit về đúng commit id mà nhập vào, trạng thái file đổi về đúng trái của commit id
- git checkout -b tenbranchmoi : tạo ra branch mới
- git tag (chưa rõ, search cach dung sau)
- git checkout (tên branch, commit id, tag): xem lại repository và chuyển tất cả file, và trạng thái về commit tương ứng
- git branch: xem tất cả branch đang có ở local, branch hiện màu xanh, có dấu *)
- git merge (tên branch): ghép branch vào branch hiện tại