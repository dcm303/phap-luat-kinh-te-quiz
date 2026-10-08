# Ôn tập Pháp luật kinh tế

Bản rà soát 05/10/2026, phiên bản 2026-10-05-v4.

- Chương 1: 70 câu; chương 2, 4, 5: mỗi chương 80 câu.
- 4 đề tổng hợp, mỗi đề 40 câu, 10 câu mỗi chương.
- Câu hỏi và lựa chọn viết như đề thi; số slide chỉ xuất hiện trong phần giải thích và căn cứ.
- Giải thích từng phương án, phân tích đề, bẫy và trích đoạn căn cứ bài giảng.
- Phông Segoe UI/Arial hỗ trợ tiếng Việt; toàn bộ văn bản chuẩn hóa Unicode NFC.
- Quy tắc chọn đáp án dựa trên slide và ghi chú PowerPoint. Tình huống được biên soạn để vận dụng.

## Sử dụng

Trang chính `index.html` chạy hoàn toàn trong trình duyệt. Có chế độ luyện từng câu,
đề tổng hợp chấm sau khi nộp và bản lý thuyết theo chương. Tiến độ lưu trên trình duyệt.
Tiến độ từ ngân hàng cũ 303 câu không được tự chuyển sang ngân hàng mới có nội dung và mã câu khác.

## Tài liệu

- [Lý thuyết PDF](ly-thuyet.pdf)
- [Lý thuyết HTML](ly-thuyet.html)
- [Lý thuyết Markdown](ly-thuyet.md)
- [310 câu và lời giải](310-cau-va-loi-giai.md)
- [4 đề tổng hợp và lời giải](4-de-tong-hop-va-loi-giai.md)
- [Báo cáo rà soát nguồn](ra-soat-nguon.md)
- [Hướng dẫn và ma trận](huong-dan.md)

## Render

Giữ service Static Site đang liên kết repository này, nhánh `main`.
Publish directory là thư mục gốc (`.`). Không cần cài thư viện, database hoặc biến môi trường.
Với Auto Deploy đang bật, commit mới trên `main` sẽ tự triển khai.

## Ngân hàng ôn theo review — cập nhật 08/10/2026

- [Ôn theo review](review.html): 352 câu duy nhất, chia 14 chủ đề; lý thuyết, phân biệt, vận dụng và tình huống.
- Gộp 411 mục nguồn thành 176 bài luyện giữ lại; thêm 86 bài từ ngân hàng theo slide và 90 câu mới biên soạn, gồm 30 tình huống mới. Không tạo bài luyện riêng khi review nhắc lại cùng câu; các câu cùng chủ đề chỉ giữ riêng khi kiểm tra điều kiện, ngoại lệ hoặc thao tác khác nhau.
- 285 câu có căn cứ slide; 67 câu có dùng nguồn bổ sung từ leak/review, tài liệu ôn tập và/hoặc luật kiểm chứng. Có nhãn riêng và bộ lọc nguồn.
- [Làm riêng 30 tình huống thực tế mới](review.html?set=case30): 8 doanh nghiệp, 6 hợp tác xã, 9 hợp đồng và bảo đảm, 7 phục hồi/phá sản. Cả 30 có căn cứ trực tiếp trong nội dung/ghi chú slide; tình huống tự biên soạn theo các trọng tâm review. Mỗi câu có 4 lựa chọn, phân tích theo bước, giải thích từng lựa chọn và bẫy. Tải [30 tình huống và cách xử lý](30-tinh-huong-thuc-te-va-loi-giai.md).
- Giải thích từng lựa chọn, phân tích đề, bẫy, lý thuyết và trích nội dung/ghi chú slide. Các mục review gốc liên quan nằm trong phần lời giải, gồm đáp án gợi ý và ghi chú mâu thuẫn/thiếu dữ kiện.
- [411 mục review nguyên văn](review-nguyen-van.md) giữ nguyên thứ tự nguồn, gồm câu lặp; bản nguồn không phải danh sách bài luyện.
- Bộ lọc mức độ nhận biết, thông hiểu, vận dụng; câu sai, chưa làm, đánh dấu và tìm kiếm.
- Bài luyện giữ nguyên được chuyển tiến độ từ bản 411 mục. Dữ liệu bản cũ vẫn lưu. Tên người học chỉ phân tách lưu trên trình duyệt, không đồng bộ thiết bị.
- Tải [ngân hàng và toàn bộ lời giải](review-va-loi-giai.md), [đối chiếu và nguồn](doi-chieu-review.md).
- Bộ 470 câu theo chương/4 đề tổng hợp trước đó giữ nguyên.

## 11 đề ôn tập theo review — 40 câu / 30 phút

- [Đề 11 — Đề ôn tập riêng](review-exams.html?exam=11): 40 câu / 30 phút, không có câu hợp tác xã; phần 7 câu được bù sang doanh nghiệp, hợp đồng và phục hồi/phá sản. Phân bố 13 doanh nghiệp, 11 hợp đồng/bảo đảm, 9 phục hồi/phá sản, 3 tranh chấp, 3 tổng quan, 1 tài chính. Có 9 tình huống mới lấy từ nhóm 30 câu thực tế. Tải [đề 11 và toàn bộ lời giải](de-11-on-tap-rieng-va-loi-giai.md).
- [Làm đề](review-exams.html): giữ nguyên bộ 10 đề trước và thêm đề 11. Bộ 10 đề trước dùng 290 câu khác nhau trong 400 lượt câu; phiên làm đề đang lưu được giữ khi thêm đề mới. Không lặp trong cùng đề; có thể lặp giữa các đề.
- Mỗi đề: 14 nhận biết, 16 thông hiểu, 10 vận dụng; 24 câu 4 lựa chọn, 16 câu đúng/sai. Đề 1–10 có cả hợp tác xã; đề 11 ôn riêng các nội dung còn thi theo yêu cầu người học.
- Đồng hồ 30 phút tiếp tục khi tải lại/rời trang; tự nộp hết giờ, xác nhận nộp sớm, khóa đáp án sau nộp và cho làm lại.
- Sau nộp: số đúng/sai/bỏ trống, điểm, kết quả theo mức độ; đầy đủ phân tích, lý thuyết, bẫy và nguồn như ngân hàng mới.
- Tiến độ ngân hàng 322 câu được giữ khi thêm 30 tình huống nhờ mã câu ổn định; câu và đáp án của 10 đề trước không thay đổi, tiến độ được chuyển khi thêm đề 11.
- Tải [11 đề và lời giải](review-exams-solutions.md), [dữ liệu bộ đề](review-exams-data.json).
