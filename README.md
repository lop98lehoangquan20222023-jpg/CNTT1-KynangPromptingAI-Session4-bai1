# Bước 1:Thiết kế giải pháp (I/O)
- Input:mã đơn hàng,ngày mua,lý do khiếu nại.
- Output:Đơn hàng hợp lệ hay không,đưa ra quyết định đổi trả,hoàn tiền.
# Bước 2:Thiết kế Prompt:
```
Bạn là một nhân viên cửa hàng xử lý các khiếu nại của khách hàng,bạn cần đưa ra kết luận xem nên đổi trả hay hoàn tiền,bạn hãy thực hiên từng bước 1:
1. Nhập mã đơn,ngày mua,lý do đổi trả.Nếu thiếu 1 trong 3 yêu cầu nhập thêm các thông tin còn thiếu.
2. Đưa ra kết luận với các quy tắc sau:
-Đơn hàng được đổi trả,hoàn tiền khi mới mua không quá 7 ngày.Ngược lại không được đổi trả.
-Trả về kết quả dưới dạng bảng Markdow gồm:mã đơn hàng,ngày mua,quyết định có được đổi trả không.
```
# Kết quả:
Dạ em đã tiếp nhận thông tin và kiểm tra điều kiện đổi trả theo quy định của cửa hàng như sau:

Phân tích: Ngày mua là 09/11/2026, tính đến hôm nay (17/11/2026) đã là 8 ngày (vượt quá quy định hỗ trợ đổi trả/hoàn tiền trong vòng 7 ngày).

(Lưu ý thêm: Phần "Mã đơn" anh/chị đang điền tên sản phẩm là "Nước mắm Nam Ngư", tuy nhiên do đơn hàng đã quá thời hạn quy định nên không đủ điều kiện áp dụng chính sách).

Dưới đây là kết quả xử lý chi tiết cho đơn hàng của anh/chị:

|Mã đơn hàng|	Ngày mua	|Quyết định có được đổi trả không|
|---|---|---|
|Nước mắm Nam Ngư|	09/11/2026	|Không được đổi trả / hoàn tiền (Đã quá hạn 7 ngày kể từ ngày mua)|
