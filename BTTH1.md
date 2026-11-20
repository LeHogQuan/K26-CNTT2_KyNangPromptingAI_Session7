Vấn đề: 
Sinh viên lớp học lập trình, khó khăn trong việc tìm hiểu các cấu trúc dữ liệu như linked, binary tree. Cần xây dựng prompting để giải thích cho sinh viên hiểu về các cấu trúc dữ liệu đó bằng ngôn ngữ python?

Yêu cầu:
1. Viết prompt dùng kỹ thuật feynman
2. Viết rubric (tiêu chí) để AI chấm điểm chính xác không chấm theo khác quan

Cách làm:
1. Kỹ thuật feynman là
 Gồm 4 bước

Bước 1: Chọn chủ đề chưa hiểu  cần học
Bước 2: Hỏi AI giải thích dễ hiểu ( ví dụ giải thích cho học sinh lớp 6 có thể hiểu vấn đè)
Bước 3: Lỗ hổng kiến thức ( Hỏi lại AI những vấn đề mà mình chưa hiểu)
Bước 4: Đi giải thích lại theo ý hiểu của mình cho AI đánh giá

Prompt: Bạn là chuyên gia về cấu trúc dữ liệu và giải thuật , tôi là sinh viên mới học lập trình đang cần tìm hiểu các cấu trúc dữ liệu ( linked list, binary tree) bằng ngôn ngữ python.
Hãy giải thích các cấu trúc dữ liệu trên cho đứa trẻ 10 tuổi cũng hiểu được. 
-> đợi AI trả về kết quả
-> sau đó hỏi lại AI những vấn đề mình chưa hiểu (lỗ hổng kiến thức) 
...
giải thích lại theo ý kiểu của mình cho AI nhận xét

2. Xây dựng rubric (tiêu chí) để AI chấm điểm
   Thiết lập bảng tiêu chí chấm điểm dựa vào 4 tiêu chí
   2.1 tính đúng đắn(40%)
   + chương trình có gặp bug gì không
   + chương trình chạy được nhưng kết quả có bị sai hay không?
   2.2 độ tối ưu thuật toán(30%)
   + Thuật toán chạy có nhanh hay không?
   + Thuật toán có tốn nhiều dung lượng hay không?
   2.3 phong cách viết code(20%)
   + Đặt tên biến, hàm có dễ hiểu hay không?
   + Đặt tên biến, hàm có đúng theo quy tắc hay không?
   + Code có gọn gàng dễ đọc hơn không?
   + Đặt tên có chuyên nghiệp hay không?
   2.4 xử lí ngoại lệ (10%)
   + danh sách không có phần tử thì sao?
   + danh sách có 1 phần tử thì sao?
   form đăng kí SĐT
  các trường hợp ngoại lệ: chữ cái, kí tự đặc biệt, không đúng định dạng
