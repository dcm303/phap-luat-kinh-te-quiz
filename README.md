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


## Nguyên lý thống kê — 8 chương

- [Trang môn học](nguyen-ly-thong-ke/index.html), [luyện tập](nguyen-ly-thong-ke/luyen-tap.html), [lý thuyết tổng hợp](nguyen-ly-thong-ke/ly-thuyet.html).
- 337 câu chính / 532 ý trả lời, giữ nguyên đề bằng ảnh từ tài liệu ôn tập và xếp theo chương, số câu. Ghép lại các đoạn bị tách và ghi chú những chỗ thiếu hoặc mâu thuẫn.
- Chọn đáp án, bấm **Xem kết quả** để đọc lời giải, phân tích từng lựa chọn, công thức và bẫy. Mở được đúng trang slide gốc ngay trong trang học.
- Quy đổi chương sách 1–4 sang slide 1–4; sách 5–8 sang slide 6–9.
- Ba vị trí thiếu trong PDF: chương 4 câu 27–28, chương 5 câu 6. Câu có dữ kiện/lựa chọn không khớp được ghi chú và không chấm đoán.
- Tiến độ lưu riêng trên từng trình duyệt, có xuất/nhập JSON. Khi chuyển từ tệp ngoại tuyến hoặc địa chỉ LAN, xuất tiến độ ở trang cũ rồi nhập ở trang mới.
- Ảnh nguồn dùng chung và tải khi cần; toàn bộ phần thống kê khoảng 67 MB. Không cần cài thư viện hoặc thêm dịch vụ. Giữ cấu hình Render hiện có: nhánh `main`, publish directory `.`.


## Nguyên lý thống kê — 7 đề luyện thi từ leak/review

- [7 đề](nguyen-ly-thong-ke/review-exams.html): mỗi đề 20 câu, 6–7 lý thuyết và 13–14 tính toán; tùy chọn 45 phút hoặc không giới hạn. Không lặp câu giữa các đề.
- **Đề 1–3 thuần leak, không tự sinh:** mỗi đề 7 lý thuyết +13 bài tính, 60 câu nguồn khác nhau. Đề 4–7 dùng 29 câu nguồn còn lại và 51 câu bổ sung. Có 42 bài tính nguồn nên tối đa 3 đề thuần leak không lặp.
- 89 câu nguồn hợp lệ (47 lý thuyết, 42 tính toán), 51 bài tính toán tự sinh và gắn nhãn trên từng câu. Đây là số bổ sung tối thiểu để dùng hết lý thuyết với giới hạn 7 câu/đề.
- Nộp cả đề mới hiển thị đáp án, cách nhận diện bài, công thức/ký hiệu, thay số/làm tròn, phân tích từng lựa chọn, bẫy và nút mở đúng trang slide gốc.
- 161 câu/mảnh nguồn được kiểm kê: 89 đưa vào đề, 57 câu/mảnh thống kê giữ riêng (thiếu/lỗi/giả thiết/bản lặp), 15 mục Kế toán/Sinh học giữ nguyên văn và chưa giải. Ghép R118 từ các đoạn có dữ kiện và lựa chọn trùng khớp.
- [Đối chiếu](nguyen-ly-thong-ke/review-doi-chieu.md), [tin nhắn nguồn nguyên trạng](nguyen-ly-thong-ke/review-nguon-nguyen-van.txt), [bản hiển thị](nguyen-ly-thong-ke/review-nguon-hien-thi.md). Giữ theo bản chép người dùng gửi; không có ảnh gốc để xác nhận OCR. Bản đảo lựa chọn của cùng câu không tạo thêm lượt thi.
- Khi xếp lại đề, lựa chọn và dấu đánh dấu của bố cục cũ chuyển theo mã câu; đề mới chưa nộp và không giới hạn giờ. Bản tiến độ cũ giữ nguyên, có nút xuất sao lưu.
- Tiến độ, dấu đánh dấu, đồng hồ và kết quả lưu bằng khóa riêng; xuất/nhập JSON để chuyển thiết bị. Đồng hồ tiếp tục khi tải lại; tự nộp hết giờ nếu chọn chế độ 45 phút.
- KaTeX và font được lưu tại `nguyen-ly-thong-ke/vendor/katex/`, kèm giấy phép MIT; không dùng CDN. Giữ dịch vụ/cấu hình hiện có, chỉ đẩy GitHub.


## Nguyên lý thống kê — Câu dễ ra

- [Câu dễ ra](nguyen-ly-thong-ke/cau-de-ra.html): toàn bộ 55 câu/mảnh từ file ưu tiên, đúng thứ tự, kể cả câu thiếu/lỗi và bản lặp. Không thêm câu tự sinh.
- 34 câu có lựa chọn để chấm; 21 mục còn lại vẫn hiện nguyên văn và có nút mở phân tích/giả thiết, không ép đáp án hoặc tính điểm.
- Chọn đáp án rồi xem kết quả từng câu, hoặc nộp tất cả để mở đầy đủ lời giải, công thức, phân tích lựa chọn, bẫy và trang slide. Tiến độ riêng, có xuất/nhập JSON.
- [File nguồn nguyên văn](nguyen-ly-thong-ke/priority-nguon-nguyen-van.txt) được sao chép nguyên trạng.
