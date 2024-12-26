+++
date = '2024-12-26T11:41:19+07:00'
draft = false
title = 'Đặc điểm nổi bật'
+++

# 7 đặc điểm nổi bật của ngôn ngữ lập trình Java

# **1. Máy ảo Java (JVM - Java Virtual Machine)**

Tất cả các chương trình muốn thực thi được thì phải được biên dịch ra mã máy. Mã máy của từng kiến trúc CPU
của mỗi máy tính là khác nhau (tập lệnh mã máy của CPU Intel, CPU Solarix, CPU Macintosh ... là khác nhau), vì
vậy trước đây một chương trình sau khi được biên dịch xong chỉ có thể chạy được trên một kiến trúc CPU cụ thể
nào đó. Đối với CPU Intel chúng ta có thể chạy các hệ điều hành như Microsoft Windows, Unix, Linux, OS/2, ...

Chương trình thực thi được trên Windows được biên dịch dưới dạng file có đuôi .EXE còn trên Linux thì được biên
dịch dưới dạng file có đuôi .ELF, vì vậy trước đây một chương trình chạy được trên Windows muốn chạy được trên
hệ điều hành khác như Linux chẳng hạn thì phải chỉnh sửa và biên dịch lại.

Ngôn ngữ lập trình Java ra đời, nhờ vào máy ảo Java mà khó khăn nêu trên đã được khắc phục. Một chương trình
viết bằng ngôn ngữ lập trình Java sẽ được biên dịch ra mã của máy ảo java (mã java bytecode). Sau đó máy ảo Java
chịu trách nhiệm chuyển mã java bytecode thành mã máy tương ứng.Sun Microsystem chịu trách nhiệm phát
triển các máy ảo Java chạy trên các hệ điều hành trên các kiến trúc CPU khác nhau.

# **2. Thông dịch**

Java là một ngôn ngữ lập trình vừa biên dịch vừa thông dịch. Chương trình nguồn viết bằng ngôn ngữ lập trình
Java có đuôi *. java đầu tiên được biên dịch thành tập tin có đuôi *. class và sau đó sẽ được trình thông dịch thông
dịch thành mã máy.

# **3. Độc lập nền**

Một chương trình viết bằng ngôn ngữ Java có thể chạy trên nhiều máy tính có hệ điều hành khác nhau (Windows,
Unix, Linux, ... ) với điều kiện ở đó có cài đặt máy ảo java (Java Virtual Machine).

# **4. Hướng đối tượng**

Hướng đối tượng trong Java tương tự như C++ nhưng Java là một ngôn ngữ lập trình hướng đối tượng hoàn toàn.
Tất cả mọi thứ đề cập đến trong Java đều liên quan đến các đối tượng được định nghĩa trước, thậm chí hàm chính
của một chương trình viết bằng Java (đó là hàm main) cũng phải đặt bên trong một lớp. Hướng đối tượng trong
Java không có tính đa kế thừa (multi inheritance) như trong C++ mà thay vào đó Java đưa ra khái niệm interface để
hỗ trợ tính đa kế thừa.

# **5. Đa nhiệm - đa luồng (MultiTasking - Multithreading)**

Java hỗ trợ lập trình đa nhiệm, đa luồng cho phép nhiều tiến trình, tiểu trình có thể chạy song song cùng một thời
điểm và tương tác với nhau.

# **6. Khả chuyển (portable)**

Chương trình ứng dụng viết bằng ngôn ngữ Java chỉ cần chạy được trên máy ảo Java là có thể chạy được trên bất
kỳ máy tính, hệ điều hành nào có máy ảo Java. "Viết một lần, chạy mọi nơi" (Write Once, Run Anywhere).

# **7. Hỗ trợ mạnh cho việc phát triển ứng dụng**

Công nghệ Java phát triển mạnh mẽ nhờ vào "đại gia Sun Microsystem" cung cấp nhiều công cụ, thư viện lập trình
phong phú hỗ trợ cho việc phát triển nhiều loại hình ứng dụng khác nhau cụ thể như:

- J2SE (Java 2 Standard Edition) hỗ trợ phát triển những ứng dụng đơn, ứng dụng client-server.

- J2EE (Java 2 Enterprise Edition) hỗ trợ phát triển các ứng dụng thương mại.

- J2ME (Java 2 Micro Edition) hỗ trợ phát triển các ứng dụng trên các thiết bị di động, không dây, ...

Có thể nói rằng sự ra đời của Java đánh dấu một cuộc cách mạng mới trong lĩnh vực Công Nghệ Thông Tin. Cuộc
cách mạng này kéo theo một loạt những thay đổi: các ứng dụng dần được thay thế bằng Java, các thế hệ máy tính
sử dụng những vi mạch có khả năng hỗ trợ Java, ... Làm quen với Java sẽ giúp chúng ta tiếp cận được với những
công nghệ mới nhất của Công Nghệ Thông Tin.