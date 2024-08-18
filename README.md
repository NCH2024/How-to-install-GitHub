# How to install GitHub

## Trước khi tải cần chú ý:
- Quyền quản trị viên
- Truy cập dòng lệnh
- Trình soạn thảo code
- Tên người dùng và mật khẩu GitHub (Tùy chọn)

## Tiến hành cài đặt theo các bước sau:
### Bước 1: Truy cập trang web Git chính thức
Truy cập trang web chính thức của [Git](https://git-scm.com/) và nhấp vào nút **Tải xuống [phiên bản] cho Windows** (Download [version] for Windows). Quá trình tải xuống sẽ được bắt đầu tự động sau khi nhấp vào nút.

![Trang chủ git và hình ảnh cài đặt](/assets/img/Trang-chu-git.png)

Nhấp vào **Click here to download** để trình tải xuống bắt đầu.

![tải xuống phần mềm](/assets/img/Tai-xuong.png)

### Bước 2: Chạy tệp đã tải xuống
Sau khi bạn đã tải xuống tệp thực thi, hãy nhấp vào tệp đó để chạy trình cài đặt. Một cửa sổ bật lên yêu cầu quyền thực hiện các thay đổi đối với thiết bị sẽ được hiển thị. Bấm vào **Yes** để chấp nhận. Sau đó, cửa sổ Cài đặt Git sẽ được mở.

Đọc kỹ Giấy phép và sau đó khi bạn đã sẵn sàng, hãy nhấp vào nút **Tiếp theo (Next)**.

![cài đặt bước 2 lần 1](/assets/img/Cai-dat-b2.png)

### Bước 3: Chọn vị trí cài đặt
Nhấp vào nút **Browse…**  để chọn vị trí đích mà bạn muốn cài đặt Git. Theo mặc định, nó sẽ cài đặt vào **C:\Program Files\Git.** Nhấp vào nút **Tiếp theo (Next)** sau khi bạn đã chọn vị trí cài đặt của mình.

![cài đặt bước 3](/assets/img/cai-dat-b3.png)

### Bước 4: Chọn các thành phần
Nhấp vào hộp để cài đặt các thành phần bổ sung như biểu tượng trên màn hình. Nhưng nếu muốn, bạn có thể tiếp tục với cài đặt mặc định. Ngoài ra, hãy đảm bảo rằng hộp _“Git Bash Here”_ đã được chọn. Nhấn vào **Next** để chuyển sang bước tiếp theo.

![cài đặt bước 4](/assets/img/cai-dat-b4.png)

### Bước 5: Chọn thư mục Menu Bắt đầu
Nếu muốn, bạn có thể thay đổi tên thư mục menu bắt đầu. Nhấn **Next** để tiếp tục các bước tiếp theo.

![cài đặt bước 5](/assets/img/cai-dat-b5.png)

### Bước 6: Chọn Trình chỉnh sửa mặc định mà Git sẽ sử dụng
Chọn trình soạn thảo văn bản mặc định mà bạn muốn Git sử dụng. Các tùy chọn có sẵn là Vim, Atom, Visual Studio Code, Sublime Text, Notepad, Wordpad, v.v.

Bạn nên sử dụng Visual Studio Code hoặc Atom làm trình chỉnh sửa mặc định vì chúng được sử dụng rộng rãi nhất và có nhiều tính năng thú vị. Tuy nhiên, Vim hơi phức tạp với người mới bắt đầu.

Nhấp vào nút **Tiếp theo (Next)** để tiếp tục.

![cài đặt bước 6](/assets/img/cai-dat-b6.png)

### Bước 7: Điều chỉnh tên của nhánh ban đầu trong kho lưu trữ mới
Bạn nên chọn **Ghi đè tên nhánh mặc định cho các kho lưu trữ mới** (Override the default branch name for new repositories) và sử dụng **main** làm tên nhánh ban đầu mặc định.

Lệnh “git init” sẽ sử dụng cùng một tên nhánh ban đầu trong khi khởi tạo các kho lưu trữ. Bạn cũng có thể sử dụng bất kỳ tên nhánh ban đầu nào khác như “mặc định” (default), “phát triển” (develop), “phát hành” (release), v.v. 

Cuối cùng, nhấp vào nút **Tiếp theo (Next)** để tiếp tục sau khi chỉ định tên chi nhánh.

![cài đặt bước 7](/assets/img/cai-dat-b7.png)

### Bước 8: Điều chỉnh môi trường PATH của bạn
Chọn tùy chọn thứ 2 **Git từ dòng lệnh và cả từ phần mềm bên thứ 3** (Git from the command line and also from 3rd-party software). Bằng cách chọn tùy chọn này, bạn sẽ có thể sử dụng **Git** từ **Git Bash**, Command Prompt, Windows Powershell hoặc bất kỳ phần mềm bên thứ 3 nào khác đang tìm kiếm Git trong PATH.

Nhấn nút **Tiếp theo (Next)** để tiếp tục.

![cài đặt bước 8](/assets/img/cai-dat-b8.png)

### Bước 9: Chọn HTTPS Transport Backend
Chọn tùy chọn Sử dụng thư viện **OpenSSL** (Use the OpenSSL Library) và nhấp vào **Tiếp theo** (Next).

![cài đặt bước 9](/assets/img/cai-dat-b9.png)

### Bước 10: Định cấu hình chuyển đổi kết thúc dòng
Tiếp tục với tùy chọn được chọn theo mặc định **Checkout Windows-style**, **commit Unix-style line endings** và sau đó nhấp vào **Tiếp theo (Next)**.

![cài đặt bước 10](/assets/img/cai-dat-b10.png)

### Bước 11: Định cấu hình Trình mô phỏng đầu cuối để sử dụng với Git Bash
Một lần nữa tiếp tục với tùy chọn được chọn mặc định Sử dụng **MinTTY** (thiết bị đầu cuối mặc định của MSYS2) (Use MinTTY (the default terminal of MSYS2)) và sau đó nhấp vào **Tiếp theo (Next)**.

![cài đặt bước 11](/assets/img/cai-dat-b11.png)

### Bước 12: Chọn Hành vi mặc định của “git pull”
Chọn tùy chọn đầu tiên **Mặc định** (tua nhanh hoặc hợp nhất) (Default (fast-forward or merge)). Bằng cách chọn tùy chọn này, khi “git pull” được sử dụng, nó sẽ chuyển tiếp nhanh nhánh hiện tại sang nhánh đã tìm nạp. Nếu không thể làm như vậy, nó sẽ tạo một merge commit. 

![cài đặt bước 12](/assets/img/cai-dat-b12.png)

### Bước 13: Chọn một Credential Helper
Bạn nên chọn tùy chọn đầu tiên, **Git Credential Manager Core**, vì tùy chọn này cung cấp trải nghiệm xác thực nhất quán trên tất cả các nền tảng.

Sau đó, nhấp vào nút **Tiếp theo (Next)** để tiếp tục.

![cài dặt bước 13](/assets/img/cai-dat-b13.png)

### Bước 14: Định cấu hình các tùy chọn bổ sung
Tiếp tục với các tùy chọn được chọn theo mặc định và sau đó nhấp vào Tiếp theo (Next).

![cài đặt bước 14](/assets/img/cai-dat-b14.png)

### Bước 15: Định cấu hình Tùy chọn Thử nghiệm
Nếu bạn muốn kích hoạt một số tính năng vượt trội với cài đặt này thì bạn có thể chọn bất kỳ tùy chọn nào có sẵn. Cuối cùng, nhấp vào nút **Cài đặt (Install)**.

### Bước 16: Đợi cài đặt
Đợi vài phút để **Git** và **Git Bash** được cài đặt trên hệ thống của bạn. Sau khi cài đặt xong nhấn **Finish** để thoát khỏi Setup.

![cài đăt bước 16](/assets/img/cai-dat-b16.png)

Bây giờ Git và Git Bash đã được cài đặt thành công trên máy của bạn!

### Xác nhận rằng Git đã được cài đặt thành công
Mở Command Prompt và nhập lệnh `git --version` để xác minh rằng Git đã cài đặt thành công.

![xác nhận thành công](/assets/img/xac-nhan-thanh-cong.png)

## Hỗ trợ
Trong quá trình cài đặt nếu có vấn đề hãy liên hệ với tôi để được hướng dẫn cụ thể. Liên hệ qua zalo: +840357379334 hoặc Facebook [Nguyễn Chánh Hiệp](https://www.facebook.com/NChanhHiep). Xin cảm ơn!
