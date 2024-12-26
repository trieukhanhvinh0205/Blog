+++
date = '2024-12-26T11:41:19+07:00'
draft = false
title = 'Các thành phần cơ bản'
+++

# **Các thành phần cơ bản**

# **Chú thích (comment)**

- Là những dòng văn bản do người lập trình viết ra để chú giải cho những gì mình viết trong chương trình.

- Những dòng chú thích không được biên dịch trong quá trình thực thi chương trình.

- Có thể phục vụ trong việc sửa lỗi (debug) chương trình.

- Một dòng chú thích bắt đầu bằng dấu //; nhiều dòng bắt đầu bằng /* và kết thúc bằng */.

- Xem các ví dụ sau:

// Lệnh hiển thị dòng Hello World! ra màn hình
 
System.out.println("Hello World!");

Dòng đầu tiên là chú thích của người lập trình. Chú thích cũng có thể được viết thành nhiều dòng:

// Lệnh hiển thị
 
// dòng Hello World!
 
// ra màn hình
 
System.out.println("Hello World!");

Tương đương:

/* Lệnh hiển thị
 
dòng Hello World!
 
ra màn hình */
 
System.out.println("Hello World!");

# **Khoảng trắng (white space)**

Khoảng trắng bao gồm việc xuống dòng (phím Enter), tab (phím Tab), hay khoảng trắng (phím Spacebar). Mặc định, trình biên dịch Java sẽ 
bỏ qua các khoảng trắng nên hai lệnh sau là tương đương:

	
System.out.println("Hello World!");

Và

System  .
 
        out
 
        .
 
       println("Hello World!");

Tuy nhiên có một số ngoại lệ, cụ thể là kiểu String, trình biên dịch sẽ hiểu khoảng trắng là kí tự hay chuỗi. Do đó main và ma in là 
khác nhau.

# **Từ khoá (keywords)**
Là các từ được hỗ trợ bởi Java và người lập trình không thể thay đổi hay định nghĩa lại.

Các từ khoá trong Java:

abstract else interface switch assert enum long synchronized

boolean extends native this break false new throw byte final

null throws case finally package transient catch float private

true char for protected try class goto public void const if

return volatile continue implements short while default import

static do instanceof strictfp double int super

# **Các định danh (identifiers)**
Là tên biến, tên hằng hay tên các phương thức xuất hiện trong chương trình. Định danh có thể được định nghĩa bởi Java như main hay 
println và có thể được định nghĩa bởi người sử dụng. Định danh cấu tạo bởi các kí tự, kí số, dấu _, dấu $. Không được bắt đầu bằng kí 
số. Định danh có thể có chiều dài bất kỳ trong Java.

Một số định danh hợp lệ:

first
 
conversion
 
payRate
 
$Amount

Một số định danh không hợp lệ

First Name (định danh không có khoảng trắng)
 
Hello! (không dùng dấu ! trong định danh)
 
One+two (+ không được dùng trong định danh)
 
2nd(định danh không được bắt đầu bằng số)

# **Kiểu dữ liệu sơ cấp (primitive data types)**

Các ngôn ngữ lập trình thường cung cấp một danh sách các kiểu dữ liệu sơ cấp (primitive data types) khác nhau dùng để biểu diễn các 
kiểu thông tin khác nhau như số (numbers), thời gian (date, time), văn bản (text), v.v.

Có 3 kiểu dữ liệu sơ cấp trong Java là kiểu số nguyên, kiểu thực (dấu chấm động) và kiểu luận lý.

Kiểu số nguyên gồm các kiểu sau:

Kiểu	Kích cỡ (Byte)	Giá trị

char	2 (16 bits)	0 -> 65535

byte	1 (8 bits)	-128 -> +127

short	2 (16 bits)	-32768 -> +32767

int	4 (32 bits)	-2147483648 -> +2147483647

long	8 (64 bits)	-263 -> 263-1

# **Biến**

Để làm việc với các dữ liệu, chúng ta cần lưu trữ nó trong một biến. Cú pháp khai báo một biến là:

Kiểu_Dữ_Liệu tên_biến;

**tên_biến** là tên của biến cần khai báo gồm các kí tự, số, dấu _, và không được bắt đầu bằng số. 

**Kiểu_Dữ_Liệu** là một trong các kiểu dữ liệu sơ cấp hay kiểu do người dùng định nghĩa.

Ví dụ khai báo một biến kiểu int, tên biến là x như sau:

int x;

Sau khi khai báo biến, chúng ta có thể gán giá trị cho chúng, ví dụ gán giá trị 5 đến biến x:

int x;
 
x = 5;

Chúng ta cũng có thể kết hợp khai báo và gán giá trị cho biến như ví dụ:

int x = 5;

**Một số chú ý khi đặt tên biến:**

- Không bắt đầu bằng số

- Không trùng với các từ khoá (keywords), là các từ vựng có sẵn trong ngôn ngữ.

- Đặt theo mục đích, ví dụ firstName, age.

- Tuân theo chuẩn camel case, tức là nếu tên biến gồm nhiều từ như firstName (gồm first và Name) thì từ đầu tiên viết thường tất cả các 

- kí tự, các từ kế tiếp sẽ viết hoa kí tự đầu tiên, như firstName.

# **Hằng (constant)**

Hằng là vùng nhớ chứa nội dung không thay đổi (khác với biến chứa nội dung có thể thay đổi) trong quá trình chương trình thực thi.

Khai báo hằng trong Java:

[static] final Kiểu_dữ_liệu Tên_hằng = giá_trị_khởi tạo;

Từ khoá static có thể dùng trong một số trường hợp đặc biệt, final bắt buộc; Kiểu_dữ_liệu là kiểu dữ liệu của hằng; Tên_hằng là tên của 
hằng; giá_trị_khởi_tạo là các giá trị tương ứng với kiểu dữ liệu Kiểu_dữ_liệu (hay còn gọi là literal).

Các ví dụ:

final double PI = 3.14;
final int NO_OF_STUDENTS = 20;

# **Kiểu chuỗi (string)**

Kiểu chuỗi (string) không phải là kiểu dữ liệu sơ cấp nhưng thường được sử dụng phổ biến với các kiểu dữ liệu sơ cấp khác. Một chuỗi là 
một dãy các ký tự và có thể được dùng để thể hiện các văn bản (text), số (numbers), các kí hiệu Unicode. Chuỗi được chứa trong cặp nháy 
kép.

Trong Java, một biến kiểu chuỗi sẽ được khai báo kiểu String. Ví dụ biến str

String str = "This is a string variable!";

Các chuỗi có thể kết hợp với nhau bằng toán tử +, ví dụ:

String str = "Hello, " + "Minh!" ;// Hello, Minh!

Một chuỗi cũng có thể được định nghĩa trên nhiều dòng như ví dụ sau

String description = "Strings can " +

"be defined on multiple " +

"lines with the + operator!";

Không thể gán trực tiếp một giá trị kiểu String vào một biến có kiểu dữ liệu sơ cấp dạng số như int, float. Ví dụ sau sẽ gây ra lỗi:

String j ="7";

int i = 10 + j;

Giải pháp cho vấn đề này là dùng các phương thức chuyển kiểu chuỗi sang kiểu dữ liệu sơ cấp dạng số tương ứng như Integer.parseInt hay 
Float.parseFloat. Ví dụ trên được viết lại:

String j ="7";
int i = 10 + Integer.parseInt(j);// 17

# **Ép kiểu (casting)**

Ép kiểu trong Java là thay đổi giá trị của một biến hay một giá trị (literals) sang kiểu dữ liệu sơ cấp khác. Để ép kiểu, chúng ta chỉ 
cần đặt kiểu cần chuyển đến trong cặp dấu ngoặc đặt ngay trước giá trị cần ép kiểu. Các ví dụ sau sẽ giúp chúng ta dễ hình dung hơn:

int i = (int) 7.8; // chuyển giá trị 7.8 kiểu double sang kiểu integer
 
double d = (double) 89.7f; // chuyển giá trị 89.7f kiểu float sang kiểu double
 
short q = (short) (i*d); // chuyển giá trị i*d kiểu double sang kiểu short
 
System.out.println(i);
 
System.out.println(d);
 
System.out.println(q);

Kết quả:

7
 
89.69999694824219
 
7

Mỗi một kiểu dữ liệu sơ cấp như int, float, double, v.v. sẽ có một kiểu lớp tương ứng như Integer, Float, Double, v.v. quá trình chuyển 
kiểu từ kiểu sơ cấp sang kiểu lớp tương ứng, như chuyển int sang Integer, gọi là boxing. Quá trình ngược lại, như từ Integer sang int, 
gọi là unboxing. Xem thêm về autoboxing.










