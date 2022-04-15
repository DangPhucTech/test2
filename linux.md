 # **1. Các file và thư mục trong Unix/Linux**
Các lệnh này cho phép bạn tạo các thư mục và điều khiển các file.

|**Lệnh**|**Miêu tả**|
| :- | :- |
|cat|Hiển thị nội dung file|
|cd|Thay đổi thư mục tới dirname|
|chgrp|Thay đổi nhóm file|
|chmod|Thay đổi sự cho phép|
|cp|Sao chép file nguồn vào trong nơi đến|
|file|Xác định kiểu file|
|find|Tìm kiếm các file|
|grep|Tìm file với biểu thức quy chuẩn|
|head|Hiển thị một vài dòng đầu của file|
|ln|Tạo một link mềm trên tên cũ|
|ls|Hiển thị thông tin về kiểu file|
|mkdir|Tạo một thư mục dirname mới|
|more|Hiển thị dữ liệu trong mẫu được đánh số trang|
|mv|Di chuyển (đặt lại tên) một tên file cũ thành một tên file mới|
|pwd|In thư mục làm việc hiện tại|
|rm|Gỡ bỏ (xóa) một file|
|rmdir|Xóa một thư mục đang tồn tại|
|tail|In một vài dòng cuối của thư mục|
|touch|Cập nhật truy cập và thời gian chỉnh sửa của một file|

# **2. Thao tác dữ liệu trong Unix/Linux**
Các nội dung của file có thể dược so sánh và thay đổi với các lệnh sau:

|**Lệnh**|**Miêu tả**|
| :- | :- |
|awk|Quét mẫu và tiến trình ngôn ngữ|
|cmp|So sánh nội dung của 2 file|
|comm|So sánh dữ liệu được phân loại|
|cut|Cắt các trường được chọn trong mỗi dòng của một file|
|diff|Bộ so sánh file vi sai|
|expand|Mở rộng các tab|
|join|Kết hợp file trên một số trường phổ biến|
|perl|Ngôn ngữ thao tác dữ liệu|
|sed|Bộ soạn luồng văn bản|
|sort|Phân loại dữ liệu file|
|split|Phân chia file thành các file nhỏ hơn|
|tr|Biên dịch các ký tự|
|uniq|Báo cáo các dòng được lặp trong một file|
|wc|Tính toán số lượng từ, dòng, và ký tự|
|vi|Mở bộ soạn văn bản vi|
|vim|Mở bộ soạn văn bản vim|
|fmt|Bộ định dạng văn bản đơn giản|
|spell|Kiểm tra các lỗi chính tả văn bản|
|ispell|Kiểm tra các lỗi chính tả văn bản|
|ispell|Kiểm tra các lỗi chính tả văn bản|
|emacs|GNU dự án Emacs|
|ex, edit|Bộ soạn dòng|
|emacs|GNU dự án Emacs|
|emacs|GNU dự án Emacs|

# **3. Nén file trong Unix/Linux**
Các file có thể được nén để tiết kiệm không gian. Các file bị nén có thể được tạo và thực hành với các lệnh dưới.

|**Lệnh**|**Miêu tả**|
| :- | :- |
|compress|Nén các file|
|gunzip|Bỏ nén các file|
|gzip|Phương thức nén thay thế GNU|
|uncompress|Bỏ nén các file|
|unzip|Liệt kê, kiểm tra và giải nén các file bị nén trong tài liệu ZIP|
|zcat|Nối và liên kết các file bị nén|
|zcmp|So sánh các file bị nén|
|zdiff|So sánh các file bị nén|
|zmore|Lọc file để quan sát crt của các văn bản bị nén|

# **4. Nhận thông tin trong Unix/Linux**
Các tài liệu tra cứu và các sổ tay Unix đa dạng có sẵn trên mạng trực tuyến. Các lệnh shell sau sẽ cung cấp thông tin cho bạn:

|**Lệnh**|**Miêu tả**|
| :- | :- |
|apropos|Đặt vị trí các lệnh bằng từ khóa tra cứu.|
|info|Hiển thị thông tin lệnh trên trang trực tuyến|
|man|Hiển thị sổ tay các trang trực tuyến|
|whatis|Tìm kiếm dữ liệu whatis cho các từ đầy đủ.|
|yelp|Bộ thẩm tra sự giúp đỡ GNOME|

# **5. Giao tiếp mạng hệ thống trong Unix/Linux**
Các lệnh sau được sử dụng để gửi và nhận các file từ một host nội bộ tới một host điều khiển từ xa trên Thế giới.

|**Lệnh**|**Miêu tả**|
| :- | :- |
|ftp|Chuyển file tới chương trình|
|rcp|Điều khiển từ xa việc sao chép file|
|rlogin|Đăng nhập từ xa tới một Unix host|
|rsh|Điều khiển từ xa shell|
|tftp|Chương trình truyền tải file thường|
|telnet|Tạo kết nối terminal tới host khác|
|ssh|Bảo an shell terminal hoặc sự kết nối lệnh|
|scp|Bảo an shell từ việc sao chép file từ xa|
|sftp|Bảo an shell từ gửi file tới chương trình|

Một trong số các lệnh trên có thể bị hạn chế tại máy tính của bạn vì các lý do bảo mật.

# **6. Các thông báo giữa các người sử dụng trong Unix/Linux**
Hệ thống Unix hỗ trợ các thông báo hiển thị trên màn hình tới người sử dụng khác và gửi mail tự động trên toàn Thế giới.

|**Lệnh**|**Miêu tả**|
| :- | :- |
|evolution|Công cụ điều khiển mail GNU trên Linux|
|mail|Chương trình gửi và đọc mail đơn giản|
|mesg|Cho phép hoặc từ chối nhận các thông báo|
|parcel|Gửi các file tới người dùng khác|
|pine|Tiện ích vdu-base mail|
|talk|Nói chuyện với người sử dụng khác|
|write|Ghi thông báo tới người sử dụng khác|

# **7. Các chương trình tiện ích trong Unix/Linux**
Bảng dưới là các công cụ và ngôn ngữ mà có sẵn dựa trên những gì bạn cài đặt trên hệ thống Unix của bạn:

|**Lệnh**|**Miêu tả**|
| :- | :- |
|dbx|Chương trình chỉnh lỗi Sun|
|gdb|Chương trình chỉnh lỗi GNU (GNU debugger)|
|make|Duy trì các nhóm chương trình và các chương trình biên dịch|
|nm|In danh sách tên chương trình|
|size|In kích cỡ của chương trình|
|strip|Dỡ bỏ bảng ký tự và đặt lại vị trí các bit|
|cb|Bộ viết đúng (beautifier) chương trình C|
|cc|Bộ biên dịch ANSI C cho các hệ thống Suns SPARC|
|ctrace|Chương trình chỉnh lỗi C|
|gcc|Bộ biên dịch GNU ANSI C|
|indent|Sắp chữ thụt vào và định dạng của nguồn chương trình C|
|bc|Bộ xử lý ngôn ngữ số học tương tác|
|gcl|GNU Common Lisp|
|perl|Ngôn ngữ mục đích chung|
|php|Trang web ngôn ngữ được nhúng|
|py|Bộ phiên dịch ngôn ngữ Python|
|asp|Trang web ngôn ngữ được nhúng|
|CC|Bộ biên dịch C++ cho các hệ thống Suns SPARC|
|g++|Bộ biên dịch GNU C++|
|javac|Bộ biên dịch JAVA|
|appletvieweir|Bộ thẩm tra vi mã JAVA|
|netbeans|Tích hợp môi trường phát triển JAVA trên Linux|
|sqlplus|Chạy bộ phiên dịch Oracle SQL|
|sqlldr|Chạy bộ tải dữ liệu Oracle SQL|
|mysql|Chạy bộ phiên dịch mysql SQL|

# **8. Các lệnh hỗn hợp trong Unix/Linux**
Dưới đây là các lệnh và thông tin thay đổi về hệ thống:

|**Lệnh**|**Miêu tả**|
| :- | :- |
|chfn|Thay đổi thông tin lệnh finger của bạn|
|chgrp|Thay đổi sở hữu nhóm của một file|
|chown|Thay đổi người sở hữu|
|date|In ngày|
|determin|Tự động tìm kiếm kiểu terminal|
|du|In dung lượng đĩa sử dụng|
|echo|Phản xạ các đối số tới các chức năng tiêu chuẩn|
|exit|Thoát khỏi hệ thống|
|finger|In thông tin về những người sử dụng đã đăng nhập vào|
|groupadd|Tạo một nhóm người sử dụng|
|groups|Chỉ các thành viên của nhóm|
|homequota|Chỉ hạn ngạch và dung lượng file sử dụng|
|iostat|Báo cáo các thống kế I/O|
|kill|Gửi một signal tới một chương trình|
|last|Hiển thị các đăng nhập cuối của những người sử dụng|
|logout|Thoát khỏi Unix|
|lun|Liệt kê các tên người dùng hoặc ID đăng nhập|
|netstat|Chỉ trạng thái của mạng hệ thống|
|passwd|Thay đổi mật khẩu của người sử dụng cá nhân|
|passwd|Thay đổi mật khẩu đăng nhập của bạn|
|printenv|Hiển thị giá trị của một biến shell|
|ps|Hiển thị trạng thái của các tiến trình hiện tại|
|ps|In các thống kê trạng thái của tiến trình|
|quota -v|Hiển thị dung lượng sử dụng đĩa và các giới hạn|
|reset|Thiết lập lại chế độ terminal|
|script|Giữ scritp của khu vực terminal|
|script|Lưu giữ kết quả đầu ra của một lệnh hoặc một tiến trình|
|setenv|Thiết lập các biến môi trường|
|stty|Thiết lập các chức năng terminal|
|time|Thời gian của một lệnh|
|top|Hiển thị tất cả các tiến trình hệ thống|
|tset|Thiết lập chế độ terminal|
|tty|In tên terminal hiện tại|
|umask|Chỉ các sự cho phép mà được cung cấp để quan sát các file theo mặc định|
|uname|Hiển thị tên của hệ thống hiện tại|
|uptime|Nhận thời gian hoạt động của hệ thống|
|useradd|Tạo một tài khoản sử dụng cá nhân|
|users|In tên của những người sử dụng đã đăng nhập|
|vmstat|Báo cáo các thống kê bộ nhớ thực|
|w|Chỉ những gì mà người dùng đã đăng nhập đang thực hiện|
|who|Liệt kê danh sách những người dùng đã đăng nhập|


Dưới đây là bảng liệt kê các biến đặc biệt mà bạn có thể sử dụng trong Shell script:

|**Biến**|**Miêu tả**|
| :- | :- |
|**$0**|Tên file của script hiện tại.|
|**$n**|Những biến này tương ứng với các tham số mà một script được gọi. Tại đây n là số thập phân nguyên dương tương ứng với vị trí của một tham số (tham số đầu tiên là $1, tham số thứ hai là $2…).|
|**$#**|Số các tham số cung cấp cho một script.|
|**$\***|Tất cả các tham số được trích dẫn kép. Nếu một script nhận hai tham số, $\* là tương đương với $1 $2.|
|**$@**|Tất cả các tham số được trích dẫn kép riêng rẽ. Nếu một script nhận 2 tham số, $@ là tương đương với $1 $2.|
|**$?**|Trạng thái thoát ra của lệnh trước được chạy.|
|**$$**|Số tiến trình của shell hiện tại. Đối với Shell script, đây là số Process ID mà chúng đang chạy.|
|**$!**|Số tiến trình của lệnh background trước.|

Dưới đây là bảng một số siêu ký tự phải biết để kết nối lệnh và mở rộng với tên, mô tả và ví dụ của chúng để thực hành:

|**Tên**|**Sự miêu tả**|**Thí dụ**|
| :- | :- | :- |
|\* (Dấu hoa thị):|Đối sánh một hoặc nhiều lần xuất hiện của một ký tự||
|? (Dấu chấm hỏi):|Khớp một ký tự đơn hoặc một lần xuất hiện mẫu||
|[ ] (Dấu ngoặc vuông):|Khớp với bất kỳ số, ký hiệu hoặc bảng chữ cái được phân tách bằng dấu gạch nối nào được chỉ định bên trong dấu ngoặc vuông||
|Ống ("|")|Kết nối đầu ra lệnh làm đầu vào cho lệnh khác.|cat / etc / passwd | gốc grep|
|Dấu chấm phẩy (;)|Cho phép thực hiện các lệnh tuần tự, lần lượt.|cd / vv; ls -la; chmod + x /tmp/script.php|
|Ký hiệu và (&)|Chạy các quy trình hoặc lệnh trong nền.|find / -perm -u = s -type f &|
|Đô la ($)|Mở rộng biểu thức số học và chuyển nó vào shell|echo “tổng số tệp trong thư mục này là: $ (ls | wc -l)”|
|Chuyển hướng rỗng (2>)|Hướng thông báo lỗi chuẩn đến tệp / dev / null|your\_command 2> / dev / null|
|Circumflex (^)|Khớp với bất kỳ mẫu nào bắt đầu bằng biểu thức theo sau là ^|cd / etc / ssh; ls | grep ^ s|

# **9. Stdin – Stdout – Stderr và pipes trong shell script**

**a. Stdin – Stdout – Stderr và pipes**

Bash shell trong Linux có 3 dòng dữ liệu (stream) cơ bản đó là **stdin (0)**,**stdout (1)** và **stderr (2)**.

- **stdin (0)**: Thường là những thiết bị nhập input cho Shell ví dụ như bàn phím.
- **stdout (1)**: Hiển thị **kết quả** các lệnh lên terminal (hoặc màn hình) cho chúng ta thấy.
- **stderr (2)**: Hiển thị ra các **lỗi** trong quá trình thực hiện một lệnh hoặc một công việc nào đó.
- **pipes** trong Linux được ký hiệu là dấu gạch đứng “**|**“. Đường ống dẫn này cho phép chúng ta lấy kết quả của lệnh phía trước nó làm input cho lệnh phía sau nó

**b. Một số ký hiệu dùng để chuyển hướng input/output**
- "<" file : có nghĩa là mở một tệp tin đọc vào thay cho stdin.
- "<<" token : sử dụng dòng dữ liệu nhập hiện tại cho stdin cho đến khi gặp mã nhận dạng (token).
- ">" file : có nghĩa là ở một tệp tin để ghi, ghi đè nếu nó đã có dữ liệu, tệp tin này nhận dữ liệu từ stdout.
- ">>" file : cũng giống như trên nhưng dữ liệu sẽ được nối thêm vào chứ không ghi đè lên.
- "n>&m" : có nghĩa là chuyển hướng FD n đặt vào FD m. Ví dụ, 2>&1 nghĩa là sẽ dùng để chuyển hướng stderr sang stdout.

# **10. Các toán tử số học trong [Unix/Linux**](https://quantrimang.com/unix-va-linux "Tìm hiểu Unix và Linux")**
Các toán tử số học sau được hỗ trợ bởi Bourne shell.

Giả sử biến a giữ giá trị 10 và biến b giữ giá trị 20, thì khi đó:

**Ví dụ:**

|**Toán tử**|**Miêu tả**|**Ví dụ**|
| :- | :- | :- |
|+|Phép cộng – thêm giá trị ở mỗi bên vào toán tử|`expr $a + $b` kết quả là 30|
|-|Phép trừ – trừ giá trị bên phải của toán tử bên trái|`expr $a - $b` kết quả là -10|
|\*|Phép nhân – nhân giá trị ở trên mỗi bên với toán tử.|`expr $a \\* $b` kết quả là 200|
|/|Phép chia – chia giá trị bên phải cho giá trị bên trái|`expr $b / $a` kết quả là 2|
|%|Lấy số dư – lấy phần còn lại sau khi đã chia giá trị trái cho giá trị bên phải|`expr $b % $a` kết quả là 0|
|=|Phép gán – gán toán hạng trái cho toán hạng phải|a=$b sẽ gán giá trị của b cho a|
|==|Phép bằng – so sánh hai số, nếu cả hai đều giống nhau thì kết quả trả về là true.|`[ $a == $b ]` sẽ trả về kết quả False.|
|!=|Phép không cân bằng – so sánh hai số, nếu cả hai số khác nhau thì giá trị trả về là true.|`[ $a != $b ]` sẽ trả về kết quả True.|

Nó là rất quan trọng để ghi nhớ rằng tại đây tất cả các sự diễn đạt có điều kiện sẽ được đặt trong hai dấu ngoặc ôm vuông ([ ]) với một dấu cách trống quanh chúng, ví dụ `[$a == $b ]` là đúng, và `[$a==$b]` là không đúng.

Tất cả các toán tử số học được thực hiện sử dụng các số nguyên dài.

# **11. Các toán tử quan hệ trong Unix/Linux**
Bourne shell hỗ trợ các toán tử quan hệ sau mà là riêng với các giá trị số. Những toán tử này không làm việc cho chuỗi trừ khi giá trị của nó là số.

Ví dụ, các toán tử sau sẽ kiểm tra một quan hệ giữa 10 và 20, cũng là giữa "10" và "20" nhưng không giữa "ten" và "twenty'.

Giả sử biến a giữ giá trị 10 và biến b giữ giá trị 20 thì khi đó:

**Ví dụ**

|**Toán tử**|**Miêu tả**|**Ví dụ**|
| :- | :- | :- |
|-eq|Kiểm tra giá trị của hai toán hạng là cân bằng hoặc không, nếu có thì điều kiện trở lên đúng.|`[ $a -eq $b ]` là không đúng.|
|-ne|Kiểm tra giá trị của hai toán hạng là cân bằng hoặc không, nếu không cân bằng thì điều kiện trở lên đúng.|`[ $a -ne $b ]` là đúng.|
|-gt|Kiểm tra nếu giá trị của toán hạng trái lớn hơn giá trị của toán hạng phải, nếu đúng thì điều kiện trở nên đúng.|`[ $a -gt $b ]` là không đúng.|
|-lt|Kiểm tra nếu giá trị của toán hạng trái nhỏ hơn giá trị của toán hạng phải, nếu đúng thì điều kiện trở nên đúng.|`[ $a -lt $b ]`là đúng.|
|-ge|Kiểm tra nếu giá trị của toán hạng trái lớn hơn hoặc bằng giá trị của toán hạng phải, nếu đúng thì điều kiện trở nên đúng.|`[ $a -ge $b ]` là không đúng.|
|-le|Kiểm tra nếu giá trị của toán hạng trái nhỏ hơn hoặc bằng giá trị của toán hạng phải, nếu đúng thì điều kiện trở nên đúng.|`[ $a -le $b ]` là đúng.|

*Nó là rất quan trọng để ghi nhớ rằng tại đây tất cả các sự diễn đạt có điều kiện sẽ được đặt trong dấu ngoặc ôm vuông ([]) với dấu cách trống quanh chúng, ví dụ [ $a <= $b ] là đúng và [$a<=$b] là không đúng.*

# **12. Các toán tử logic trong Unix/Linux**
Có các toán tử logic sau được hỗ trợ bởi Bourne Shell

Giả sử biến a giữ giá trị 10 và biến b giữ giá trị 20, thì dưới đây là ví dụ sử dụng tất cả các toán tử logic.

**Ví dụ**

|**Toán tử**|**Miêu tả**|**Ví dụ**|
| :- | :- | :- |
|!|Phép phủ định. Nếu điều kiện đúng thì giá trị là sai và ngược lại.|`[ ! false ]` là true.|
|-o|Phép hoặc. Nếu một trong các toán hạng là đúng thì điều kiện là đúng.|`[ $a -lt 20 -o $b -gt 100 ]` là true.|
|-a|Phép và. Nếu cả hai toán hạng đều đúng thì điều kiện là đúng, ngoài ra là sai..|`[ $a -lt 20 -a $b -gt 100 ]` là false.|

# **13. Các toán tử chuỗi trong Unix/Linux**
Các toán tử chuỗi sau được hỗ trợ bởi Bourne Shell.

Giả sử biến a giữ giá trị "abc" và biến b giữ giá trị "efg":

**Ví dụ**

|**Toán tử**|**Miêu tả**|**Ví dụ**|
| :- | :- | :- |
|=|Kiểm tra nếu giá trị của hai toán hạng là cân bằng hoặc không, nếu có thì điều kiện là đúng.|`[ $a = $b ]` là không đúng.|
|!=|Kiểm tra nếu giá trị của hai toán hạng có cân bằng hoặc không, nếu không cân bằng thì điều kiện là đúng.|`[ $a != $b ]` là đúng.|
|-z|Kiểm tra nếu cỡ toán hạng chuỗi đã cho là 0. Nếu nó có độ dài là 0 thì nó trả về là đúng.|`[ -z $a ]` là không đúng.|
|-n|Kiểm tra nếu cỡ toán hạng chuỗi đã cho là khác 0. Nếu độ dài khác 0 thì nó trả về là đúng.|`[ -z $a ]` là không đúng.|
|str|Kiểm tra nếu str không là chuỗi trống. Nếu là chuỗi trống thì nó trả về là sai.|`[ $a ]` là không sai.|

# **14. Các toán tử kiểm tra file trong Unix/Linux**
Các toán tử sau để kiểm tra các sở hữu cơ bản liên kết với một **file** Unix.

Giả sử một biến file giữ một tên file đang tồn tại là "test" với kích cỡ là 100 byte và được cho phép đọc, viết và chạy.

**Ví dụ**

|**Toán tử**|**Miêu tả**|**Ví dụ**|
| :- | :- | :- |
|-b file|Kiểm tra nếu file là một file khối đặc biệt, nếu đúng thì điều kiện là đúng.|`[ -b $file ]` là sai.|
|-c file|Kiểm tra nếu file là một file ký tự đặc biệt, nếu đúng thì điều kiện là đúng.|`[ -c $file ]`là sai.|
|-d file|Kiểm tra nếu file là một thư mục, nếu đúng thì điều kiện là đúng.|`[ -d $file ]` là không đúng.|
|-f file|Kiểm tra nếu file là file thường như trái ngược với thư mục hoặc là file đặc biệt, nếu đúng thì điều kiện là đúng.|`[ -f $file ]` là đúng.|
|-g file|Kiểm tra nếu file có ID nhóm thiết lập (SGID), nếu đúng thì điều kiện là đúng.|`[ -g $file ]` là sai.|
|-k file|Kiểm tra nếu file có thiết lập sticky bit, nếu đúng thì điều kiện là đúng.|`[ -k $file ]` là sai.|
|-p file|Kiểm tra nếu file là một pipe được đặt tên, nếu đúng thì điều kiện là đúng.|`[ -p $file ]` là sai.|
|-t file|Kiểm tra nếu ký hiệu để nhận diện file được mở và liên kết với một terminal, nếu đúng thì điều kiện là đúng.|`[ -t $file ]` là sai.|
|-u file|Kiểm tra nếu file có SUID, nếu đúng thì điều kiện là đúng.|`[ -u $file ]` là sai.|
|-r file|Kiểm tra nếu file là đọc được, nếu đúng thì điều kiện là đúng.|`[ -r $file ]` là đúng.|
|-w file|Kiểm tra nếu file là viết được, nếu đúng thì điều kiện là đúng.|`[ -w $file ]` là đúng.|
|-x file|Kiểm tra nếu file là chạy được, nếu đúng thì điều kiện là đúng.|`[ -x $file ]` là đúng.|
|-s file|Kiểm tra nếu file là chạy được, nếu đúng thì điều kiện là đúng.|`[ -s $file ]` là đúng.|
|-e file|Kiểm tra nếu file tồn tại, vẫn đúng ngay cả khi file là một thư mục nhưng tồn tại.|`[ -e $file ]` là đúng.|

# **15. Quyền đặc biệt (Special Permissions)**

|MODE|MÔ TẢ|
| :- | :- |
|**Sticky bit**|Được sử dụng cho các thư mục chia sẻ, mục đích là ngăn chặn việc người dùng này xóa file của người dùng kia. Chỉ duy nhất owner file (và root) mới có quyền rename hay xóa các file, thư mục khi nó đã được set sticky bit. sticky bit được môt tả bằng chữ cái “t” ở dòng cuối cùng của hiển thị permission.|
|**SUID**|SUID hay Set user ID, được sử dụng trên các file thực thi (executable files) để cho phép việc thực thi được thực hiện dưới owner của file thay vì thực hiện như user đang loggin trong hệ thống.SUID cũng có thể được sử dụng để thay đổi ownership của files được tạo hoặc di chuyển nó đến một thư mục mà owner của nó sẽ là owner của thư mục chuyển đến thay vì là owner nó được tạo ra.|
|**SGID**|SGID hay Set group ID, cũng tương tự như SUID, được sử dụng trên các file thực thi (executable files) để cho phép việc thực thi được thực hiện dưới owner group của file thay vì thực hiện như group đang loggin trong hệ thống.SGID cũng có thể được sử dụng để thay đổi ownership group của files được tạo hoặc di chuyển nó đến một thư mục mà owner group của nó sẽ là owner group của thư mục chuyển đến thay vì là group nó được tạo ra.|

#### *a. SUID (Set User ID)*
SUID (***Set owner User ID up on execution***): *Người thực thi file sẽ được **mượn** quyền hạn của người sở hữu tại thời điểm thực thi.*

#### *b. SGID (Set Group ID)*
SGID (Set Group ID) Bit: SGID bit rất hữu ích khi bạn phải trao quyền truy cập directory cho một nhóm các users trong 1 group. Khi SGID bit được kích hoạt trên 1 directory, toàn bộ file/directory cấp dưới được tạo bởi bất cứ người dùng nào đều có group permission giống với parent directory.

#### *c. sticky bit*
*Sticky Bit is mainly used on folders in order to avoid deletion of a folder and it’s content by other users though they having write permissions on the folder contents. If Sticky bit is enabled on a folder, the folder contents are deleted by only owner who created them and the root user. No one else can delete other users data in this folder(Where sticky bit is set). This is a security measure to avoid deletion of critical folders and their content(sub-folders and files), though other users have full permissions.*

**Sticky Bit** được sinh ra như một công cụ giúp giải quyết vấn đề chia sẻ file hay folder giữa các người dùng. Một khi sticky bit được kích hoạt, chỉ owner của file đó mới có thể remove hoặc rename file, bất chấp những người sử dụng khác có full permission trên file đó.



Dưới đây, chúng ta có bảng tổng kết cách **chmod** SUID, SGID, Sticky Bit (Cả thư mục và file)

|PERMISSION|SYMBOLIC MODE|NUMBERIC MODE|
| :- | :- | :- |
|**sticky Bit**|`chmod +t file\_name`|`chmod 1xxx file\_name`|
|**SUID Bit**|`chmod u+s file\_name`|`chmod 4xxx file\_name`|
|**SGID Bit**|`chmod g+s file\_name`|`chmod 2xxx file\_name`|

#### *Tổng kết*

Linux là một môi trường đa người dùng đồng thời, vì vậy, việc giới hạn quyền và chia sẻ tài nguyên là một việc hết sức cần thiết nhằm đảm bảo tính an toàn nhưng vẫn linh hoạt của hệ thống. **SUID**, **SGID**, **Sticky bit** sẽ giúp đảm bảo những điều nêu trên một cách rõ ràng và chặt chẽ hơn:

## **Cấu trúc cây thư mục trong Linux**
### 1. / - Root
Đúng với tên gọi của mình: nút gốc (root) đây là nơi bắt đầu của tất cả các file và thư mục. Chỉ có root user mới có quyền ghi trong thư mục này. Chú ý rằng /root là thư mục home của root user chứ không phải là /.
### 2. /bin - Chương trình của người dùng
Thư mục này chứa các chương trình thực thi. Các chương trình chung của Linux được sử dụng bởi tất cả người dùng được lưu ở đây. Ví dụ như: ps, ls, ping...
### 3. /sbin - Chương trình hệ thống
Cũng giống như /bin, /sbinn cũng chứa các chương trình thực thi, nhưng chúng là những chương trình của admin, dành cho việc bảo trì hệ thống. Ví dụ như: reboot, fdisk, iptables...
### 4. /etc - Các file cấu hình
Thư mục này chứa các file cấu hình của các chương trình, đồng thời nó còn chứa các shell script dùng để khởi động hoặc tắt các chương trình khác. Ví dụ: /etc/resolv.conf, /etc/logrolate.conf
### 5. /dev - Các file thiết bị
Các phân vùng ổ cứng, thiết bị ngoại vi như USB, ổ đĩa cắm ngoài, hay bất cứ thiết bị nào gắn kèm vào hệ thống đều được lưu ở đây. Ví dụ: /dev/sdb1 là tên của USB bạn vừa cắm vào máy, để mở được USB này bạn cần sử dụng lệnh mount với quyền root: # mount /dev/sdb1 /tmp
### 6. /tmp - Các file tạm
Thư mục này chứa các file tạm thời được tạo bởi hệ thống và các người dùng. Các file lưu trong thư mục này sẽ bị xóa khi hệ thống khởi động lại.
### 7. /proc - Thông tin về các tiến trình
Thông tin về các tiến trình đang chạy sẽ được lưu trong /proc dưới dạng một hệ thống file thư mục mô phỏng. Ví dụ thư mục con /proc/{pid} chứa các thông tin về tiến trình có ID là pid (pid ~ process ID). Ngoài ra đây cũng là nơi lưu thông tin về về các tài nguyên đang sử dụng của hệ thống như: /proc/version, /proc/uptime...
### 8. /var - File về biến của chương trình
Thông tin về các biến của hệ thống được lưu trong thư mục này. Như thông tin về log file: /var/log, các gói và cơ sở dữ liệu /var/lib...
### 9. /usr - Chương trình của người dùng
Chứa các thư viện, file thực thi, tài liệu hướng dẫn và mã nguồn cho chương trình chạy ở level 2 của hệ thống. Trong đó

- /usr/bin chứa các file thực thi của người dùng như: at, awk, cc, less... Nếu bạn không tìm thấy chúng trong /bin hãy tìm trong /usr/bin
- /usr/sbin chứa các file thực thi của hệ thống dưới quyền của admin như: atd, cron, sshd... Nếu bạn không tìm thấy chúng trong /sbin thì hãy tìm trong thư mục này.
- /usr/lib chứa các thư viện cho các chương trình trong /usr/bin và /usr/sbin
- /usr/local chứa các chương tình của người dùng được cài từ mã nguồn. Ví dụ như bạn cài apache từ mã nguồn, nó sẽ được lưu dưới /usr/local/apache2
### 10. /home - Thư mục người của dùng
Thư mục này chứa tất cả các file cá nhân của từng người dùng. Ví dụ: /home/john, /home/marie
### 11. /boot - Các file khởi động
Tất cả các file yêu cầu khi khởi động như initrd, vmlinux. grub được lưu tại đây. Ví dụ vmlixuz-2.6.32-24-generic
### 12. /lib - Thư viện hệ thống
Chứa cá thư viện hỗ trợ cho các file thực thi trong /bin và /sbin. Các thư viện này thường có tên bắt đầu bằng ld\* hoặc lib\*.so.\*. Ví dụ như ld-2.11.1.so hay libncurses.so.5.7
### 13. /opt - Các ứng dụng phụ tùy chọn
Tên thư mục này nghĩa là optional (tùy chọn), nó chứa các ứng dụng thêm vào từ các nhà cung cấp độc lập khác. Các ứng dụng này có thể được cài ở /opt hoặc một thư mục con của /opt
### 14. /mnt - Thư mục để mount
Đây là thư mục tạm để mount các file hệ thống. Ví dụ như # mount /dev/sda2 /mnt
### 15. /media - Các thiết bị gắn có thể gỡ bỏ
Thư mục tạm này chứa các thiết bị như CdRom /media/cdrom. floppy /media/floopy hay các phân vùng đĩa cứng /media/Data (hiểu như là ổ D:/Data trong Windows)
### 16. /srv - Dữ liệu của các dịch vụ khác
Chứa dữ liệu liên quan đến các dịch vụ máy chủ như /srv/svs, chứa các dữ liệu liên quan đến CVS.
### 17. /etc/passwd
File passwd trong Linux là file cấu hình chứa thông tin chi tiết về người dùng. Một đặc điểm quan trọng của file passwd là nó là file văn bản ASCII mà người dùng có thể chỉnh sửa dễ dàng bằng bất kỳ trình soạn thảo văn bản nào như [Nano và Vim](https://quantrimang.com/so-sanh-vim-va-nano-172113 "Vim hay nano là trình soạn thảo Terminal tốt nhất?").



## **Làm quen với tài khoản**
Các lệnh này sẽ giúp người dùng Linux mới làm quen với tài khoản Linux của mình.

|**Lệnh**|**Chức năng**|**Ví dụ**|
| :- | :- | :- |
|pwd|Hiển thị vị trí hiện tại trong hệ thống file.|pwd|
|whoami|Hiển thị tên người dùng - hữu ích nhất nếu chuyển đổi người dùng bằng lệnh su và cần được nhắc nhở về tài khoản nào đang được sử dụng|whoami|
|ls|Cung cấp một danh sách file. Với tham số **-a,** lệnh hiển thị các file có tên bắt đầu bằng dấu chấm (ví dụ: .bashrc). Với tham số **-l,** lệnh hiển thị quyền, kích thước file và ngày/giờ cập nhật mới nhất.|ls<br>ls -a<br>ls -l|
|env|Hiển thị cài đặt môi trường người dùng (ví dụ: đường dẫn tìm kiếm, kích thước phần lịch sử được lưu lại, thư mục chính, v.v...)|env|
|echo|Lặp lại phần văn bản mà người dùng cung cấp hoặc hiển thị giá trị của một số biến.|echo hello<br>echo $PATH|
|history|Liệt kê các lệnh đã đưa ra trước đó.|history<br>history | tail -5|
|passwd|Thay đổi mật khẩu. Lưu ý rằng các yêu cầu phức tạp có thể được thi hành.|passwd<br>history | tail -5|

## **Tạo và chỉnh sửa các file**
Các hệ thống Linux cung cấp các lệnh để tạo các file. Người dùng có thể chọn trình soạn thảo văn bản mong muốn. Một số lệnh yêu cầu người dùng phải thành thạo trước khi sử dụng, còn những lệnh khác thì khá đơn giản.

|**Lệnh**|**Chức năng**|**Ví dụ**|
| :- | :- | :- |
|nano|Một trình chỉnh sửa văn bản dễ sử dụng, yêu cầu người dùng di chuyển trong file bằng các phím mũi tên và cung cấp các chuỗi điều khiển để định vị văn bản, lưu các thay đổi, v.v.|nano myfile|
|vi|Một trình chỉnh sửa tinh vi hơn, cho phép người dùng nhập các lệnh để tìm và thay đổi văn bản, thực hiện các thay đổi tổng thể, v.v...|vi myfile|
|ex|Một trình soạn thảo văn bản được thiết kế cho các lập trình viên và có cả chế độ trực quan và dòng lệnh.|ex myfile|
|touch|Tạo một file nếu nó chưa tồn tại hoặc cập nhật timestamp nếu nó đã được tạo.|touch newfile<br>touch updatedfile|
|>|Tạo file bằng cách hướng đầu ra cho chúng. > tạo một file trong khi >> gắn với một file hiện có.|cal > calendar<br>ps > myprocs<br>date >> date.log|

## **Đọc một số file**

|**Lệnh**|**Chức năng**|**Ví dụ**|
| :- | :- | :- |
|cat|Hiển thị toàn bộ nội dung của một file văn bản.|cat .bashrc|
|more|Hiển thị nội dung của file văn bản. Nhấn phím cách để di chuyển đến từng đoạn bổ sung.|more .bash\_history|
|less|Hiển thị nội dung của file văn bản, nhưng cho phép quay trở lại bằng phím mũi tên lên trên.|less .bash\_history|
|file|Xác định các file theo loại (ví dụ: văn bản ASCII, file thực thi, hình ảnh, thư mục)|file myfile<br>file ~/.bashrc<br>file /bin/echo|

## **Tìm file**
Có hai lệnh có thể giúp người dùng tìm file trên Linux, nhưng chúng hoạt động rất khác nhau. Một lệnh tìm kiếm hệ thống file, còn lệnh kia xem xét cơ sở dữ liệu được xây dựng trước đó.

|**Lệnh**|**Chức năng**|**Ví dụ**|
| :- | :- | :- |
|find|Định vị các file dựa trên các tiêu chí được cung cấp (tên, loại, chủ sở hữu, quyền, kích thước file, v.v...). Trừ khi được cung cấp một vị trí để bắt đầu tìm kiếm, còn nếu không lệnh này chỉ tìm trong thư mục hiện hành.|find . -name myfile<br>find /tmp -type d|
|locate|Định vị các file bằng cách sử dụng nội dung của **/var/lib/mlocate/mlocate.db** được cập nhật bằng lệnh **updateb** chạy qua cron. Không yêu cầu vị trí bắt đầu.|locate somefile<br>locate "\*.html" -n 20|

**Các lệnh xử lý tập tin trên Linux**

Lệnh để di chuyển xung quanh hệ thống file Linux là ls, nhưng có nhiều biến thể.

|**Lệnh Linux**|**Nhiệm vụ lệnh sẽ làm**|
| :- | :- |
|ls|Liệt kê nội dung thư mục hiện tại|
|ls -al|Liệt kê nội dung thư mục bao gồm cả file ẩn|
|cd dir|Di chuyển từ thư mục hiện tại sang thư mục dir|
|cd|Chuyển từ thư mục hiện tại về thư mục riêng (thường là [Tên User] ở Home)|
|cd ..|Di chuyển lên (về /) một thư mục từ vị trí hiện tại.|
|cd <location>|<p>Đưa người dùng đến vị trí được chỉ định. Nếu vị trí bắt đầu bằng **/,** nó được coi là tương đối với thư mục gốc và vị trí hiện tại. Ký tự ~ đại diện cho thư mục Home. Ví dụ:</p><p>cd /tmp<br>cd Documents<br>cd ~/Documents</p>|
|pwd|Hiện thư mục hiện tại|
|mkdir quantrimang|Tạo thư mục mới có tên là quantrimang|
|rm filemuonxoa|Xóa file có tên là filemuonxoa|
|rm -r thumuccanxoa|Xóa thư mục có tên là quantrimang|
|rm -f filecanxoa|Bắt xóa file có tên là filecanxoa|
|rm -rf thumuccanxoa|Bắt xóa thư mục có tên là thumuccanxoa|
|cp file1 file2|Sao chép file1 sang file2|
|cp -r dir1 dir2|Sao chép thư mục dir1 sang dir2 và tạo dir2 nếu chưa có dir2|
|mv file1 file2|Di chuyển file1 đến chỗ file2 hoặc đổi tên file1 thành file2. Nếu file2 có sẵn thì di chuyển file1 vào file2|
|ln -s tenfile link|Tạo liên kết biểu tượng có tên là link đến file có tên là tenfile|
|touch filecantao|Tạo hoặc cập nhật tập tin filecantao|
|cat > tenfile|Nhập từ bàn phím (đầu vào chuẩn - standard input) vào tập tin tenfile mới|
|more tenfile|Hiện nội dung file có tên là tenfile|
|head tenfile|Hiện 10 dòng đầu của tập tin tenfile|
|tail tenfile|Hiện 10 dòng cuối của tập tin tenfile|
|tail -f tenfile|Hiện nội dung của tập tin tenfile và cập nhật liên tục trong thời gian thực|
|tail -f -n N tenfile|Hiện nội dung của tập tin tenfile và cập nhật liên tục, giới hạn N dòng|

**Đo hiệu suất hệ thống**

Sau đây là một số công cụ hữu ích để kiểm tra hiệu năng hệ thống.

|**Lệnh**|**Chức năng**|**Ví dụ**|
| :- | :- | :- |
|top|Hiển thị các tiến trình đang chạy cùng với việc sử dụng tài nguyên và dữ liệu hiệu suất hệ thống. Có thể hiển thị các tiến trình cho một người dùng đã chọn hoặc tất cả người dùng. Các tiến trình có thể được sắp xếp theo các tiêu chí khác nhau (theo mặc định là mức độ sử dụng CPU).|top<br>top jdoe|
|atop|Tương tự như lệnh trên nhưng hướng nhiều đến hiệu năng hệ thống hơn so với các tiến trình riêng lẻ.|atop|
|free|Hiển thị bộ nhớ và trao đổi tổng bộ nhớ, phần đã sử dụng và còn trống.|free|
|df|Hiển thị việc sử dụng không gian ổ đĩa hệ thống của file.|df<br>df -h|

**Quản lý người dùng và nhóm**

Các lệnh để tạo và xóa tài khoản người dùng và các nhóm khá đơn giản.

|**Lệnh**|**Chức năng**|**Ví dụ**|
| :- | :- | :- |
|useradd|Thêm tài khoản người dùng mới vào hệ thống. Tên người dùng là bắt buộc. Các trường khác (mô tả người dùng, shell, mật khẩu ban đầu, v.v...) có thể được chỉ định. Thư mục chính sẽ mặc định là /home/username.|useradd -c "John Doe" jdoe<br>useradd -c "Jane Doe" -g admin -s /bin/bash jbdoe|
|userdel|Xóa tài khoản người dùng khỏi hệ thống. Tùy chọn -f mạnh mẽ hơn, xóa các file chính và file người dùng khác ngay cả khi người dùng vẫn đăng nhập.|userdel jbdoe<br>userdel -f jbdoe|
|groupadd|Thêm một nhóm người dùng mới vào hệ thống, cập nhật **/etc/group**.|groupadd developers|
|groupdel|Xóa nhóm người dùng khỏi hệ thống.|groupdel developers|

**Thiết lập và chạy các tiến trình theo lịch**

Các tác vụ có thể được lên lịch để chạy định kỳ bằng cách sử dụng lệnh được liệt kê dưới đây.

|**Lệnh**|**Chức năng**|**Ví dụ**|
| :- | :- | :- |
|crontab|Thiết lập và quản lý các tiến trình theo lịch. Với tùy chọn **-l,** các công việc định kỳ được liệt kê. Với tùy chọn **-e,** các công việc định kỳ có thể được thiết lập để chạy ở các khoảng thời gian đã chọn.|crontab -l<br>crontab -l -u username<br>crontab -e|
|anacron|Cho phép người dùng chỉ chạy các công việc theo lịch trình hàng ngày. Nếu hệ thống bị tắt khi một công việc được đặt lịch chạy, nó sẽ chạy khi hệ thống khởi động.|sudo vi /etc/anacrontab|

**Cập nhật, cài đặt và liệt kê các ứng dụng**

Các lệnh để cài đặt và cập nhật ứng dụng tùy thuộc vào phiên bản Linux đang sử dụng, cụ thể là dựa trên nền tảng Debian hay RPM.

|**Lệnh**|**Chức năng**|**Ví dụ**|
| :- | :- | :- |
|apt update|Trên các hệ thống dựa trên Debian, lệnh này cập nhật danh sách các gói có sẵn và các phiên bản của chúng, nhưng không cài đặt hoặc nâng cấp bất kỳ gói nào|sudo apt update|
|apt upgrade|Trên các hệ thống dựa trên Debian, lệnh này cài đặt các phiên bản mới hơn của các gói đã có.|sudo apt upgrade|
|apt list|Liệt kê tất cả các gói được cài đặt trên hệ thống dựa trên Debian. Với tùy chọn **--upgradable,** nó chỉ hiển thị các gói có bản nâng cấp.|apt list<br>apt list --installed<br>apt list --upgradable|
|apt install|Trên các hệ thống dựa trên Debian, lệnh này cài đặt gói được yêu cầu.|sudo apt install apache2|
|yum update|Trên các hệ thống dựa trên RPM, lệnh này cập nhật tất cả hoặc các gói được chỉ định.|sudo yum update<br>yum update mysql|
|yum list|Trên các hệ thống dựa trên RPM, lệnh này liệt kê các gói.|sudo yum update mysql|
|yum install|Trên các hệ thống dựa trên RPM, lệnh này cài đặt gói được yêu cầu.|sudo yum -y install firefox|
|yum list|Trên các hệ thống dựa trên RPM, lệnh này liệt kê các gói đã biết và đã cài đặt.|sudo yum list<br>sudo yum list --installed|

**Tắt và khởi động lại**

Các lệnh tắt và khởi động lại hệ thống Linux yêu cầu quyền admin. Các tùy chọn như **+15** là số phút mà lệnh sẽ đợi trước khi yêu cầu tắt máy được thực hiện.


|**Lệnh**|**Chức năng**|**Ví dụ**|
| :-: | :-: | :-: |
|shutdown|Tắt hệ thống tại thời điểm yêu cầu. Tùy chọn **-H** tạm dừng hệ thống, còn tùy chọn **-P** sẽ tắt nguồn.|sudo shutdown -H now<br>shutdown -H +15<br>shutdown -P +5|
|halt|Tắt hệ thống tại thời điểm yêu cầu.|sudo halt<br>sudo halt -p<br>sudo halt --reboot|
|poweroff|Ngắt nguồn khỏi hệ thống tại thời điểm yêu cầu.|sudo shutdown -H now<br>sudo shutdown -H +15<br>sudo shutdown -P +5|
