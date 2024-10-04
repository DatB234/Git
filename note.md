#Terms
Repository(Repo) // Là thư mục dự án của chúng ta
Branch // Là nhánh và trong 1 dự án sẽ có nhiều nhánh khác nhau và nhánh mặc định của chúng ta là master
Conflict // Có nghĩa là xung đột
Local // Là những gì nằm trên máy tính của chúng ta
Remote // Là những gì trên một sever nào đó sẽ là 1 remote 
# Commands
- git init // Lệnh này sẽ làm dự án của chúng ta thành 1 Git.
cách mở TERMINAL trong vsc ctrl + j với window | cmd + j với mac
- git status // Lệnh này sẽ cho chúng ta thấy được trạng thái của dự án.
- git add // Lệnh này cho phép chúng ta chuẩn bị lưu lại thời điểm hiện tại của dự án.(để lưu lại tất cả các file ta gõ " git add .")
- git reset // Lệnh này sẽ cho phép chúng ta lấy ra file chuẩn bị lưu 
- git commit -m 'ghi chú'  // Lệnh này sẽ cho chúng ta chính thức lưu các file lại, lệnh này đặc biệt khi chúng ta cần ghi chú trước khi lưu 
- git log  // Lệnh này sẽ cho ta xem những thời điểm mà ta đã lưu.
- git log --oneline // Lệnh này cũng như lệnh " git log" nhưng nó sẽ trả về thông báo gọn hơn.(Gõ phím q để out ra).
- git checkout id // Lệnh này sẽ cho phép người dùng trở về 1 thời điểm ban đầu 
- git  checkout "branch name"// Lệnh này sẽ cho phép người dùng trở về thời điểm mới nhất.
- git branch // Lệnh này sẽ giúp cho người dùng biết branch mặc định là gì.
- git checkout -b"branch name" // Lệnh này sẽ giúp người dùng tạo ra 1 branch mới
- git merge "branch name người dùng muốn tổng hợp"// Lệnh này sẽ cho phép người dùng tổng hợp lại branch của người dùng.
- git branch -d "branch name" // Lệnh này cho phép người dùng xóa đi một branch.
// Lưu ý khi giải quyết xung đột xong ta xử dụng lệnh ( git commit) chúng ta sẽ không cần ghi lại chú thích vì chúng ta đang xử lý xung đột.
// Lưu ý để thoát ra các lệnh git ta sẽ gõ ( :q).