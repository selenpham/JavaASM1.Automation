# JavaASM1.Automation
Java Assignment with Maven project
# Bài tập: 

# Bài 1
Trong package java.basic.bai1: 

Tạo một class có tên: CalculateUtils
Tạo 4 phương thức tính sau (static): 
tinhCong(double x, double y) trả về giá trị x + y
tinhNhan(double x,double y) trả về giá trị x*y
tinhTru(double x, double y) trả về giá trị x –y
tinhChia(doublex, double y) trả về giá trj x/y
Tạo một class có tên: MyMainClass
Sử dụng dụng hàm main viết đoạn mã lệnh thực hiện nhập ký tự từ bàn phím:

Nhập số thứ nhất x = 
Nhập số thứ hai y =
Nhập lệnh ACTION = 
Trong đó số thứ nhất và số thứ 2 là kiểu số, nhập lệnh ACTION là một chuỗi, chuỗi nhập vào có giá trị một trong danh sách sau:  “CONG” , “TRU”,  “NHAN”, “CHIA”. So sánh chuỗi vừa nhập:

Nếu nhập vào chuỗi:

CONG thì thực hiện gọi hàm tinhCong()
TRU thì thực hiện gọi hàm tinhTru()
NHAN thì gọi hàm tinhNhan() 
CHIA  thì gọi hàm tinhChia() trong class CalculateUtils
Nếu người dùng nhập vào action không phải là các giá trị trên thì in ra thông báo: “Giá trị ACTION không hợp lệ” và kết thúc chương trình.

In kết quả vừa thực hiện được ra màn hình.

# Bài 2

Trong package java.basic.bai2

Tạo một class có tên MainScreen
Nhập vào một số nguyên bất kỳ từ bàn phím N>0. Nếu N>0 thì mới thực hiện các bước tiếp theo
Tính tổng các số chẵn và tổng các số lẻ từ 0 đến N. In kết quả ra màn hình
Đếm xem  từ 0 đến N có bao nhiều số chia hết cho 3 nhưng không chia hết cho 2
In kết quả ra màn hình.

# Bài 3

Trong package “java.basic.bai3”

Tạo một class có tên: Student với các thuộc tính 
fullName (kiểu String)
address (kiểu String)
dob (kiểu String dạng dd/mm/yyyy)
gender  (kiểu String)
finalGrade (kiểu float) - điểm tổng kết
Tạo các phương thức set, get cho các thuộc tính trên
Tạo một class có tên MainScreen có chứa hàm main. Trong hàm main viết chương trình sau:
a. Sử dụng vòng lặp WHILE hoặc DO…WHILE để nhập thông tin Student từ bàn phím.  

Sau mỗi lần nhập đầy đủ thông tin của một Student thì tiếp tục  in ra thông báo: “Do you want to continue (Y/N)?”. 

-  Nếu người dùng nhập Y thì chương trình tiếp tục cho nhập Student tiếp theo, 

- Nếu người dùng nhập N thì dừng nhập Student.  

Sử dụng mảng ArrayList để tạo danh sách lưu các Student vừa nhập

b. In ra tất cả Student trong danh sách theo định dạng:

Student 1:

FullName:…
Address: …
DOB: …
Gender: …
FinalGrade: …
Student 2:

FullName:…
Address: …
DOB: …
Gender: …
FinalGrade: …
Student N ………………………..

c. Sử dụng vòng lặp FOR để in ra danh sách vừa nhập. Xét finalGrade:

Nếu: finalGrade < 4.0 thì in ra  Học sinh  <fullName> học lực kém
Nếu  4.0 <= finalGrade < 5.0 thì in ra  Học sinh  <fullName> học lực yếu
Nếu  5.0 <= finalGrade< 5.5  thì in ra  Học sinh  <fullName> học lực  trung bình  yếu.
Nếu  5.5 <= finalGrade < 6.5 thì in ra  Học sinh  <fullName> học lực trung bình
Nếu  6.5 <= finalGrade < 7.0  thì in ra  Học sinh  <fullName> học lực trung bình khá
Nếu  7.0 <= finalGrade < 8.0   thì in ra  Học sinh  <fullName> học lực khá
Nếu  8.0 <= finalGrade < 8.5  thì in ra  Học sinh  <fullName> học lực khá giỏi
Nếu  8.5 <= finalGrade <= 10.0  thì in ra  Học sinh  <fullName> học lực giỏi
d. Tính điểm tổng kết trung bình của danh sách học sinh  (tổng điểm /số lượng)

2. Hướng dẫn các bước làm bài:

B1. Đọc hiểu, phân tích đề bài 

Assigment này sẽ bao gồm 3 bài java. Với mỗi đề bài, chúng ta cần làm rõ các ý sau:

Bài toán đặt ra là gì, có yêu cầu gì đặc biệt.
Giải pháp cho bài toán này là gì.
Phạm vi kiến thức nào cần áp dụng để giải quyết bài toán.
 B2. Xây dựng giải pháp trên giấy

Đây là một bước khá quan trọng trong việc lập trình. Đối với một bài toán nhỏ, các bạn có thể dễ dàng định hình giải pháp trong đầu và có thể bắt tay luôn vào việc viết code để giải quyết bài toán. Tuy nhiên, với những bài toán lớn hoặc có độ phức tạp nhất định, việc bắt tay vào code ngay dễ khiến chương trình phát sinh nhiều lỗi tiềm ẩn, thậm chí lệch hướng khỏi yêu cầu đề bài. Việc cần làm của chúng ta là lên ý tưởng và viết giải pháp ra giấy. Các bạn cần gạch ra những việc cần làm, từng bước nhỏ để giải quyết bài toán trên giấy, càng chi tiết càng tốt.

B3. Tiến hành viết code dựa trên giải pháp mà các bạn đã viết ra trên giấy

Sau khi đã lựa chọn, chỉnh sửa, tối ưu các bước/ việc cần phải làm để giải quyết bài toán trên giấy, các bạn cần chuyển hóa nó thành những dòng code trong chương trình của các bạn. Việc viết code cần bám sát các ý/các bước bạn đã liệt kê ra để đảm bảo không bị sót hoặc phát sinh nhiều lỗi tiềm ẩn.

B4. Chạy chương trình và kiểm tra xem đã hoạt động đúng yêu cầu của để bài.

Các bạn sẽ nhập dữ liệu đầu vào và kiểm tra  kết quả đã đáp ứng được yêu cầu của bài toán đưa ra hay chưa. Cố gắng tạo ra nhiều bộ đữ liệu đầu vào khác nhau có thể bao phủ các trường hợp có thể xảy ra.Nếu phát sinh lỗi lập tức tiến hành sửa lỗi.

B5. Lưu project trong folder và nén file để nộp bài

Sau khi đảm bảo chương trình hoạt động đúng yêu cầu và đáp ứng các tiêu chí trong Rubrics (Tiêu chí đánh giá), các bạn lưu lại file bài làm trên folder nén trước khi nộp bài. 
