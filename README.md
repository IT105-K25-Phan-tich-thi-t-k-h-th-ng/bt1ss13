# BÁO CÁO RÀ SOÁT NHANH MÀN HÌNH YÊU CẦU ĐỔI/TRẢ HÀNG FASTMART-ONLINE

> 👤 **Học viên:** Đỗ Hoàng Sơn | **Mã SV:** PTIT-HCM-066
> 🏫 **Môn học:** IT105-K25-Phan-tich-thi-t-k-h-th-ng

---

## Phần 1 — Phân biệt UI/UX

Phân tích nhanh sự khác biệt giữa lỗi giao diện (UI) và lỗi trải nghiệm người dùng (UX) trong tính năng 'Yêu cầu Đổi/Trả hàng':

| Lỗi thuộc về UI (giao diện) | Lỗi thuộc về UX (trải nghiệm) |
| --- | --- |
| Nút 'Gửi yêu cầu' và nút 'Hủy bỏ' dùng cùng màu xám nhạt giống hệt nhau, không tạo sự phân biệt trực quan giữa hành động chính và phụ. | Màn hình ép người dùng cuộn danh sách thả xuống 15 lựa chọn và xếp chồng 4 bước cùng cỡ chữ khiến khách hàng bối rối và bỏ dở luồng thao tác. |

## Phần 2 — Nhận diện nguyên tắc UI vi phạm

Đánh giá các hiện tượng bất hợp lý trên giao diện dựa trên 6 nguyên tắc thiết kế UI cơ bản:

| Hiện tượng trong tình huống | Nguyên tắc UI bị vi phạm | Vì sao |
| --- | --- | --- |
| 4 bước thao tác cùng 1 kích cỡ chữ, không phân biệt chính-phụ | Hierarchy | Thiếu phân cấp thị giác làm người dùng khó nhận biết thứ tự các bước và thông tin trọng tâm. |
| Ô nhập số lượng không phản hồi gì sau khi nhập | Feedback | Hệ thống không cung cấp tín hiệu phản hồi ngay để thông báo dữ liệu nhập là hợp lệ hay bị lỗi. |
| Nút 'Gửi yêu cầu' và 'Hủy bỏ' cùng màu xám giống hệt nhau | Clarity | Thiếu độ tương phản trực quan khiến người dùng không thể phân biệt rõ nút xác nhận chính và nút hủy bỏ. |

## Phần 3 — Chọn đúng thành phần UI

Lựa chọn các thành phần giao diện chuẩn xác tương ứng với từng tình huống nghiệp vụ cụ thể:

| Tình huống | Thành phần UI phù hợp |
| --- | --- |
| Chọn 1 lý do từ danh sách 15 lựa chọn | Dropdown List |
| Nhập số lượng sản phẩm cần đổi/trả | Number Input Field |
| Tải lên ảnh chụp sản phẩm lỗi | File Uploader |
| Thông báo 'Gửi yêu cầu thành công' tự động biến mất sau vài giây | Toast Notification |

## Phần 4 — Ánh xạ Use Case sang UI

Ánh xạ chi tiết các bước trong Use Case sang các thành phần giao diện UI Element tương ứng:

| Bước Use Case | UI Element |
| --- | --- |
| 1. Khách hàng chọn 1 lý do đổi/trả | Dropdown List |
| 2. Khách hàng nhập số lượng sản phẩm | Number Input Field |
| 3. Khách hàng tải lên ảnh sản phẩm lỗi | File Uploader |
| 4. Khách hàng nhấn nút xác nhận gửi yêu cầu | Primary Button |

## Phần 5 — Phân biệt Wireframe/Mockup/Prototype

Xác định đúng thuật ngữ thiết kế tương ứng với từng mức độ hoàn thiện của sản phẩm:

| Mô tả | Thuật ngữ |
| --- | --- |
| Bản phác thảo đen trắng, chỉ có khối và chữ giả, dùng để chốt bố cục | Wireframe |
| Bản thiết kế tĩnh, đầy đủ màu sắc và font chữ thật, dùng để chốt thẩm mỹ | Mockup |
| Mockup có thêm tương tác (bấm nút chuyển màn hình), dùng để mô phỏng trải nghiệm thực tế | Prototype |

---

## 📁 Danh sách tệp tin nộp bài trong Repository
- 📝 `bt1.docx`: Báo cáo tài liệu phân tích nghiệp vụ hoàn chỉnh.
