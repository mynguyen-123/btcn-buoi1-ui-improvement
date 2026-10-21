# AI Usage Log

## 1. Công cụ AI
Tên công cụ: Gemini

## 2. Mục đích sử dụng
Hỗ trợ phân tích vấn đề UX/UI dựa trên dữ liệu khảo sát và cung cấp khung mã nguồn HTML/CSS cho lưới sản phẩm.

## 3. Prompt đã sử dụng
- "Bạn là chuyên gia phân tích nghiệp vụ và thiết kế... Hãy giúp tôi lập bảng phân tích 5 khu vực..."
- "Tôi đang thực hiện bài tập phát triển giao diện... Tôi muốn cải tiến khu vực thẻ sản phẩm. Hãy đề xuất cấu trúc và tạo HTML/CSS."

## 4. Kết quả AI đề xuất
- Chỉ ra nguyên nhân làm rối mắt là do nhãn khuyến mãi (badge) lồng ghép.
- Đề xuất dùng CSS Grid cho danh sách sản phẩm để tối ưu hiển thị Mobile.

## 5. Kiểm tra và điều chỉnh
- Tôi đã kiểm tra code hiển thị tốt trên Chrome DevTools (cả Mobile và PC).
- Thay đổi nội dung thẻ HTML để khớp với ngành hàng mỹ phẩm của Hasaki.

## 6. Phần tôi hiểu và có thể giải thích
- Nắm rõ cách sử dụng `display: grid` và `grid-template-columns` trong CSS để tự động bẻ dòng sản phẩm.
- Hiểu cách dùng `position: absolute` để đặt thẻ `-20%` nổi lên trên góc phải của hình ảnh sản phẩm.