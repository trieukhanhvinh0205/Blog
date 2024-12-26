+++
date = '2024-12-26T11:41:19+07:00'
draft = false
title = 'Chương trình Java'
+++

# **Chương trình Java**
Như đã đề cập ở chương I, một chương trình Java sẽ được chuyển sang mã trung gian bởi một chương trình gọi là trình biên dịch (compiler) trước khi được một chương trình khác gọi là JVM (Java Virtual Machine) chuyển sang mã máy.

Chương trình Java có một số đặc điểm:

- Chương trình Java gồm các dòng mã thực thi một nhiệm vụ nào đó.

- Chương trình Java phải đảm bảo các thành phần cơ bản của ngôn ngữ để chương trình có thể thực thi.

- Các thành phần cơ bản của Java sẽ được tìm hiểu trong các phần sau của bài giảng, nhưng để một chương trình Java thực thi cần đảm bảo một số thành phần cơ bản như trong ví dụ HelloWorld sau:

package Chap01;
 
public class HelloWorld {
 
    public static void main(String[] args) {
 
          // TODO Auto-generated method stub
 
          System.out.println("Hello World!");
 
    }
 
}

Như đã đề cập qua trong chương I, một dự án Java sẽ chứa nhiều gói (package), mỗi gói sẽ chứa nhiều lớp và trong lớp sẽ chứa nhiều thành phần như phương thức, thuộc tính, dữ liệu, v.v.

Đoạn mã của tập tin HelloWorld.java gồm:

- Dòng lệnh đầu tiên khai báo gói Chap01 bằng từ khoá package

- Dòng lệnh kế tiếp là khai báo lớp HelloWorld bằng từ khoá class. Từ khoá public chỉ phạm vi truy cập của lớp HelloWorld (sẽ tìm hiểu trong chương sau).

- Dòng lệnh khai báo phương thức main – là phương thức quan trọng và là đầu ra của chương trình.

- Dòng chú thích

- Dòng lệnh hiển thị chuỗi Hello World! ra màn hình bằng phương thức println.

# **Một số lưu ý:**

- Dự án của chúng ta gồm một gói Chap01, gói Chap01 chứa lớp HelloWorld và lớp HelloWorld chứa phương thức main. Phương thức main chứa một lệnh dùng để hiển  thị chuỗi Hello World! ra màn hình.

- Chúng ta cùng xem lại lệnh gọi phương thức println:

**System.out.println("Hello World!");**

**prinln** là phương thức chứa trong lớp **System.out** (giống như lớp **HelloWorld** chứa **main**). Lớp **System.out** chứa trong gói **java.lang.**











































































































































