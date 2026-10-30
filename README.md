# Lịch tập

Hai chương trình tập riêng, mỗi chương trình là một trang HTML tự chứa (ảnh động nhúng sẵn, không cần internet).

## Các bản

| Trang | Cho | Nội dung |
|---|---|---|
| [`vo5.html`](vo5.html) | Vợ | Lịch 2 buổi — thân trên / thân dưới, toàn máy cố định, 16 bài |
| [`thanh.html`](thanh.html) | Thanh | Lịch 3 buổi — squat, deadlift cộng máy, 22 bài, có bảng ghi tạ |

`index.html` là trang chủ để chọn giữa hai bản.

## Điểm chung

- **Thứ tự ưu tiên**: bài compound nặng và bài dễ sai tư thế đứng đầu buổi, khi thân còn khoẻ và kỹ thuật còn chuẩn.
- **Nhãn mức**: bắt buộc / phục hồi / cắt được — biết bỏ bài nào khi thiếu thời gian.
- **Mỗi bài**: nhóm cơ chính và hỗ trợ, kỹ thuật tóm tắt, các bước tập chi tiết, mục chú ý, lý do chọn bài.
- **Siêu bộ** ở những buổi cần nén thời gian.

## Đặc thù bản của Thanh

Điều chỉnh cho tình trạng đau khớp AC (đỉnh vai) khi đẩy: đã bỏ Smith shoulder press, dip machine và barbell incline press; thêm face pull và cable external rotation ba lần mỗi tuần.

## Kỹ thuật

Mỗi ảnh động được nhúng **một lần** dưới dạng CSS class `g-<slug>` rồi tái sử dụng qua `background-image`, nên bài xuất hiện ở nhiều buổi không làm tăng dung lượng trang.

Ảnh: [free-exercise-db](https://github.com/yuhonas/free-exercise-db) (giấy phép mở).
