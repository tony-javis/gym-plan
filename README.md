# Lịch tập

Ba chương trình riêng, mỗi chương trình là một trang HTML tự chứa (ảnh động nhúng sẵn, không cần internet).

## Các trang

| Trang | Cho | Ghi tạ |
|---|---|---|
| [`vo.html`](vo.html) | Thảo Vy | Chỉ xem |
| [`yen.html`](yen.html) | Yến Nhi | Chỉ xem |
| [`tony.html`](tony.html) | Tony | Ghi được, cho cả ba người |

`index.html` là trang chủ để chọn.

Lịch của Yến Nhi tạm thời giống Thảo Vy, sẽ điều chỉnh sau khi tập thử.

## Cách ghi mức tạ

Chỉ trang `tony.html` có ô nhập. Bấm chip chọn người, gõ số vào bảng — tự lưu bằng localStorage, không cần bấm nút.

Mỗi người có bộ cột riêng vì hai lịch không trùng bài:

- **Tony:** Squat · Deadlift · Bench máy · Cable row · Đẩy vai · Vai 0-10 · Ghi chú
- **Thảo Vy / Yến Nhi:** Hip thrust · Leg press · Pulldown · Bench máy · Cable row · Ghi chú

## Chia sẻ để xem

Bấm **Tạo link** trên trang của Tony → dữ liệu của người đó được mã hoá vào phần `#d=...` của URL và copy sẵn. Gửi qua Zalo, mở trên máy khác là thấy số.

Link là ảnh chụp tại thời điểm tạo: ghi thêm thì phải tạo link mới. Muốn tự đồng bộ phải có server.

## Sao lưu

Nút **Xuất JSON** tải toàn bộ dữ liệu ba người về máy. **Nhập JSON** nạp lại. Nên xuất mỗi 2-3 tuần — dữ liệu nằm trong Safari, xoá dữ liệu trang web là mất.

Trên iPhone nên "Thêm vào MH chính": Safari tự xoá dữ liệu trang web sau khoảng 7 ngày không mở, thêm vào màn hình chính thì được miễn trừ.

## Điểm chung của ba lịch

- **Thứ tự ưu tiên**: bài compound nặng và bài dễ sai tư thế đứng đầu buổi.
- **Nhãn mức**: bắt buộc / phục hồi / cắt được.
- **Mỗi bài**: nhóm cơ chính và hỗ trợ, kỹ thuật tóm tắt, các bước tập chi tiết, mục chú ý, lý do chọn bài.
- **Siêu bộ** ở buổi cần nén thời gian.

## Đặc thù lịch của Tony

Điều chỉnh cho đau khớp AC (đỉnh vai) khi đẩy: bỏ Smith shoulder press, dip machine, barbell incline press; thêm face pull và cable external rotation ba lần mỗi tuần.

## Kỹ thuật

Mỗi ảnh động nhúng **một lần** dưới dạng CSS class `g-<slug>` rồi tái sử dụng qua `background-image`, nên bài xuất hiện ở nhiều buổi không làm tăng dung lượng.

Ảnh: [free-exercise-db](https://github.com/yuhonas/free-exercise-db) (giấy phép mở).
