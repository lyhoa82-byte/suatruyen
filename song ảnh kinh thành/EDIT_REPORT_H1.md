# SONG ẢNH KINH THÀNH
## EDIT_REPORT_H1 — Hồi I: Người chết trong lồng Vô Tướng

Căn cứ: MASTER_STORY_BIBLE.md, EDITING_PROTOCOL.md, story handbook.md, CANON_DECISIONS.md (LOCKED), TIMELINE_LOCKED.md.
Phạm vi: chỉ `ep1.md`. Không chạm Hồi II–VI, không sửa handbook, không sửa CANON_DECISIONS / TIMELINE_LOCKED.

**Trạng thái: CHỜ TÁC GIẢ DUYỆT** (Protocol §1: dừng sau mỗi tập).

---

## 0. Lượt 2 — Chuyển hoàn toàn screenplay → văn xuôi tự sự (Edge Read Aloud)

Lượt 1 (commit b784e3b) đã bỏ nhãn, nhưng vẫn để 230 lượt thoại đứng riêng một dòng, không có người nói, theo kiểu đối thoại kịch bản. Lượt 2 viết lại toàn bộ Hồi I thành văn xuôi liên tục:

- Mỗi lượt thoại nằm trong một câu có chủ ngữ hoặc câu dẫn ("Hạ Tử Khiêm hỏi", "nàng đáp", "áo đỏ hét"…). Không câu thoại nào đứng trơ một mình.
- Dòng tiếng động (Keng / Cộc / Cốc / Cạch) đưa vào câu tường thuật ("Tiếng chuông thứ nhất vang lên", "ba tiếng trống, cốc, cốc, cốc", "Ổ khóa thứ nhất kêu cạch một tiếng").
- Cụm cụt kiểu chỉ dẫn sân khấu ("Đèn tắt.", "Lục Thanh La.", "Nữ nhân áo đen. Mặt nạ đỏ.", "Là máu.", "Nước lên tới mắt cá chân. Đầu gối. Thắt lưng.") viết thành câu đầy đủ.
- Chuyển cảnh: dấu `***` (5 lần) và câu mở định vị thời gian/không gian.
- Tiêu đề viết thành một câu đọc được: "Song Ảnh Kinh Thành. Hồi một: Người chết trong lồng Vô Tướng."
- Giữ nguyên plot, mystery, canon, thứ tự sự kiện. Không tóm tắt, không cắt, không thêm cảnh. Kiểm tra: bản gốc có 230 nhãn người nói; bản mới có 239 lời thoại trong ngoặc kép (230 lượt thoại + 9 tiếng hô của đám đông/người trong hậu đài, câu "Ta là…", lời khẩu hình "Đừng gọi tên ta", giọng nói trong bóng tối) — không mất câu thoại nào.

**Nhãn và dấu vết screenplay đã loại bỏ (so với bản gốc):**

| Loại | Bản gốc | Lượt 1 | Lượt 2 (hiện tại) |
|---|---|---|---|
| Nhãn cảnh (CẢNH / INT / EXT) | 6 | 0 | **0** |
| Nhãn người nói đứng riêng dòng | 230 (+ 8 dòng tiêu đề/nhãn viết hoa khác) | 1 | **0** |
| Markdown / ngăn cách kịch bản (`---`, `##`, `**`, HẾT HỒI) | 18 | 0 | **0** |
| Thoại đứng riêng, không có người nói | 9 | 230 | **0** |
| Dòng chỉ có tiếng động | 16 | 3 | **0** |
| Cụm cụt kiểu chỉ dẫn sân khấu (≤ 3 từ) | (gộp trong nhãn) | 10 | **0** |
| **Tổng dấu vết còn sót** | — | 244 | **0** |

Cách đếm: script quét từng đoạn của `ep1.md` (các nhóm ở bảng trên); dấu `***` được phép theo yêu cầu nên không tính.

---

## 1. Độ dài

Đo nội dung thực tế, không tính tiêu đề, nhãn cảnh, nhãn người nói, markdown, dấu `***`.

| | Ký tự nội dung |
|---|---|
| Bản gốc (screenplay) | ~21.900 |
| Lượt 1 | ~22.900 |
| Lượt 2 (hiện tại) | ~25.700 |

Tăng khoảng 3.800 ký tự so với bản gốc, gần như toàn bộ do câu dẫn thoại thay cho nhãn người nói (bắt buộc để người nghe biết ai đang nói). Không thêm cảnh, không thêm tình tiết.
Độ dài câu trung bình ~53 ký tự (tham chiếu Protocol §4: 50–60).

---

## 2. Các thay đổi đã thực hiện

### 2.1. Chuyển format kịch bản → văn xuôi (Bible §9, Protocol §4; nhóm A #29)

- Bỏ toàn bộ nhãn "CẢNH 1 → CẢNH 6", nhãn người nói (ÁO ĐỎ, VÂN CƠ, HẠ TỬ KHIÊM…), dấu `---`, `##`, `**`, dòng "HẾT HỒI I".
- Thoại chuyển thành lời trong ngoặc kép; thêm câu dẫn ở những chỗ người nghe có thể không biết ai đang nói (đặc biệt cảnh 1 và đoạn đối thoại nhiều lượt).
- Các dòng chữ viết (thiếp mời, chữ trên cánh hoa, mảnh giấy ở chân chim sẻ, bốn chữ trên mặt hồ) chuyển thành câu tường thuật, bỏ in đậm.
- Tiêu đề truyện và tiêu đề hồi gộp thành một câu đọc được ở đầu file.

### 2.2. Tín hiệu chuyển cảnh (Protocol §4)

Mỗi nhãn cảnh được thay bằng dấu `***` và một câu mở định vị thời gian/không gian:

| Cảnh cũ | Câu mở mới |
|---|---|
| Cảnh 1 | "Mười ba năm trước, trong hậu đài của Vô Tướng Ban…" |
| Cảnh 2 | "Một giọt nước rơi xuống hồ. Sóng lan ra. Mười ba năm sau, trên hồ sen của Thủy Nguyệt Các…" |
| Cảnh 3 | "Về tới phòng thay y phục, Vân Cơ đóng cửa lại." |
| Cảnh 4 | "Sáng hôm sau, Hạ Tử Khiêm tới La Sinh Đài." |
| Cảnh 5 | "Chạng vạng, Vân Cơ tới La Sinh Đài trước giờ diễn." |
| Cảnh 6 | "Giờ Tý đêm ấy, trời không trăng." |

### 2.3. Giảm narrator giải thích / exposition lặp (Bible §5, §6)

| Vị trí | Trước | Sau | Lý do |
|---|---|---|---|
| Cảnh 1 | "Hắn đang tìm Mẫu Kính." | "…như đang tìm một thứ biết chắc là có ở đây." | Narrator không đoán hộ; người nghe tự nối khi Cố đập gương ngay sau đó |
| Cảnh 6 | "Đó không còn là một thói quen vô thức. Thanh La đang cố ý cho nàng nhìn thấy." | "Lần này, Thanh La đang nhìn thẳng về phía nàng." | Cùng ý được Vân Cơ nói ra ở cuối cảnh ("Người bước vào lồng cố ý co ngón út…"). Bỏ lần giải thích thứ nhất, thể hiện bằng hành động |
| Cảnh 6 | "Đó là dấu hiệu của Thủy Nguyệt Các." | "Đóa trà trắng là dấu hiệu của Thủy Nguyệt Các." | Giữ thông tin (cần cho người nghe khi Hạ hỏi "Đóa trà?"), chỉ làm rõ chủ ngữ cho audio |
| Cảnh 3 | Hai dòng thoại tách rời của Hạ ("…đúc tám chiếc khóa…" / "Mất tích ba ngày trước.") | Gộp một lượt thoại | Bỏ nhịp chờ thừa |
| Cảnh 6 | "Chén trà… Khói từ lư hương đã tắt… Trên bàn chỉ còn…" + "Mặt gương quay về phía sân khấu." | Gộp thành một đoạn | Bớt câu cụt liên tiếp không tạo thêm nhịp |

### 2.4. Làm rõ cho người nghe (audio-first, không thêm thông tin mới)

- "A Yên, cô đồ đệ không nói được của Thanh La" ở lần xuất hiện đầu (handbook: A Yên là đồ đệ, câm).
- "Quốc sư Phí Kinh Hồng" ở lần xuất hiện đầu (chức danh đã có trong thoại "Quốc sư").
- "Hạ Tử Khiêm của Đại Lý Tự" ở lần xuất hiện đầu.
- Sửa câu tự mâu thuẫn: "ông chưa nhìn sân khấu lần nào. Ông chỉ quan sát chiếc lồng" (chiếc lồng nằm trên sân khấu) → "ông chưa nhìn người diễn lần nào. Ông chỉ quan sát chiếc lồng."

### 2.5. Không thay đổi

- Toàn bộ plot, thứ tự sự kiện, thoại gốc (ngoài các điểm liệt kê ở mục 2 và 3).
- Mọi setup của Hồi I: đường ngầm bịt 3 lần / đào 4 lần, 300 lượng, bướm, "Đoán.", thói quen ngón cái miết chén, ngón út co, hạt ngọc tai trái, kim dấu mây, đóa trà, tiếng chuông thứ tư, khe sàn hút khói, mộ trống, khóa thứ chín, "Đừng tin khuôn mặt ta", "Ta chỉ trả lại… Tên", câu hỏi "Nếu có ngày tỷ không còn nhớ mặt ta…".
- Cách gọi nhân vật chính là "Vân Cơ" (bí mật đổi tên mở ở Hồi II).

---

## 3. Continuity đã sửa

| ID | Vấn đề | Căn cứ | Sửa |
|---|---|---|---|
| **#4** | Khi ghép hai nửa Mẫu Kính, gương chỉ phản chiếu Thanh La, Vân Cơ không có bóng — trái luật "Mẫu Kính không phản chiếu người đã cho máu vào nó" (Hồi III), trong khi Thanh La mới là người thừa nhận đã dùng máu | B-03 (LOCKED), nhóm A | Đảo lại: "mặt gương chỉ phản chiếu Vân Cơ. Thanh La ngồi ngay trước gương mà không có bóng." Câu hỏi ngay sau đó ("Muội dùng máu gọi Kính Ảnh?") giờ có căn cứ trực tiếp |
| **B-04** | Mắt thi thể sáng, khói từ miệng, giọng nói trong bóng tối mang màu siêu nhiên, trái luật tàn ảnh | B-04 (a) (LOCKED) | Không giải thích trong Hồi I (giữ mystery), chỉ đặt dấu vật lý dùng material có sẵn: mắt "một lớp trắng đục bắt ánh đèn như mặt gương" (thay "lớp sáng trắng"); khói "màu tím nhạt" (khớp Bế Tâm Sa, lửa tím ở Hồi II); giọng nói "như vọng lên từ khe sàn ngay dưới chân" (khe sàn đã có ở cảnh Phí dịch lư hương; ống truyền âm là kỹ thuật có ở Hồi III). Câu "Không ai khác có vẻ đã nghe thấy" giữ nguyên |
| **#19** | Bóng người có vệt đỏ ở cổ tay, người trong lồng thì không — chi tiết không có giải thích ở bất kỳ hồi nào, nhưng lại là thứ khiến Vân Cơ bật dậy | Nhóm A | Thay bằng quan sát có căn cứ trong canon: "Các bóng người… tóc và tay áo vẫn bay. Chỉ có bóng người trong lồng đã thôi cử động." Khớp lời Tô Mạn ở Hồi II (tim ngừng vào khoảng tiếng chuông thứ sáu – bảy). Bóng tay ghép hình con chim được giữ như hiệu ứng biểu diễn |
| **#11** | Hộp "mười hai mảnh kim loại giống răng khóa" gợi ý một payoff không tồn tại (dễ bị hiểu là 12 tấm gương) | Nhóm A | Giảm trọng lượng: "mấy mảnh kim loại trông giống răng khóa". Sợi tóc bị thuốc ăn màu và chấm máu trên cánh hoa giữ nguyên (đã nối với tóc thi thể ở Hồi III và với việc Thanh La dùng máu gọi Kính Ảnh ở cảnh 5) |
| Xưng hô | Đường Tiểu Sơn xưng "ta" với Hạ Tử Khiêm ("Ta gõ hết rồi") | Handbook: Đường Tiểu Sơn xưng "thuộc hạ" | → "Thuộc hạ gõ hết rồi." |
| B-01 | Phản ứng của Phí Kinh Hồng ở tiếng chuông thứ tư | B-01 (b) (LOCKED): ở Hồi I hắn bất ngờ thật | Đã khớp sẵn với bản thảo; giữ nguyên, không thêm chi tiết |
| B-05 | "Từ lúc hai đứa sáu tuổi", "hai thiếu nữ mười sáu tuổi", "mười ba năm" | TIMELINE_LOCKED | Đã khớp; giữ nguyên |

---

## 4. Những mục còn để Hồi II xử lý

| ID | Việc | Ghi chú |
|---|---|---|
| **B-04** | Hồi II cảnh 7 (bóng người trong gương của Phí) đang khớp luật. Dòng xác nhận cơ chế giọng nói / khói / mắt ở Hồi I có thể đặt ở Hồi II (Tô Mạn khám nghiệm, đường hầm dưới sân khấu) hoặc Hồi III | Còn mở câu hỏi phụ: **ai** nói qua ống truyền âm (CANON_DECISIONS B-04) — cần tác giả chốt trước khi viết dòng xác nhận |
| **#12** | Ai gửi con chim sẻ đe dọa | Theo đề xuất nhóm A: một dòng trong lời khai A Yên (Hồi II cảnh 11) |
| **#13** | "Chiếc khóa thứ chín" (trong mộ) và chìa số chín (dưới lưỡi Trương Đồng) | Hồi I giữ chữ "chiếc khóa". Làm rõ ở Hồi II (thư của Thanh La đã nói nàng thu thập các chiếc khóa: "chiếc khóa thứ tư ở nhà Tôn quản sự") |
| **#14** | Trương Đồng chết thế nào | Hồi II cảnh 12 + Hồi VI |
| **#15** | Sở Mậu | Hồi II cảnh 11 |
| **B-06 / B-07** | Bảy tàn ảnh mang mặt Thanh La; hộp sắt "VÂN CƠ", đốt xương; mốc "đêm mười lăm" | Hồi II cảnh 9–10 theo B-06 (c), B-07 (a), TIMELINE_LOCKED |
| **B-02** | Lọ thuốc giải A Yên giữ có mùi Thanh Tâm Lộ thật | Hồi II cảnh 11 theo B-02 (a): lọ gốc còn cặn thuốc thật |
| **B-03** | Lần Vân Cơ dùng máu mở cửa đá (Hồi II cảnh 10): tàn ảnh ngắn, đúng luật B-03 (b) | Kiểm tra khi biên tập |
| **#29** | Chuyển format văn xuôi | Áp dụng chuẩn của Lượt 2 (mục 0) cho Hồi II ngay từ đầu, kiểm bằng cùng script đếm dấu vết |
| **#20** | Sẹo bán nguyệt ở cổ tay, vết thương vai (nhóm C) | Giữ nguyên trừ khi tác giả yêu cầu |

**Lưu ý cho Hồi II:** câu "Không cửa ngầm. Không vách kép." mà Đường Tiểu Sơn đọc trước khán giả ở Hồi I được giữ nguyên vì đó là lời công bố chính thức; Hồi II phát hiện cát và hộp sắt trong mặt thứ năm — không mâu thuẫn, nhưng nên giữ nhất quán rằng khoang cát được Đại Lý Tự coi là bộ phận giữ thăng bằng, không phải vách kép.

---

## 5. Đề xuất cập nhật handbook (CHƯA ÁP DỤNG)

Protocol §1 yêu cầu cập nhật handbook sau mỗi tập. Theo chỉ thị hiện tại, editor không sửa handbook. Các mục đề xuất để tác giả cập nhật:

- **Xưng hô:** Vân La (Vân Cơ) là tỷ, Tạ Vân Cơ (Thanh La) là muội. Đường Tiểu Sơn xưng "thuộc hạ" với Hạ Tử Khiêm.
- **Chi tiết mới được xác nhận ở Hồi I:**
  - Thanh La (Tạ Vân Cơ thật) đã dùng máu gọi Kính Ảnh một lần trước buổi diễn; vì vậy Mẫu Kính không phản chiếu nàng.
  - Khói từ miệng thi thể có màu tím nhạt; giọng nói trong bóng tối vọng lên từ khe sàn.
- **Món nợ cảm xúc mới gieo:** "Nếu có ngày tỷ không còn nhớ mặt ta, tỷ còn nhận ra không?" (payoff Hồi VI); 300 lượng; đường ngầm 3 lần bịt / 4 lần đào.
- **Món nợ cảm xúc còn tồn đọng:** Vân Cơ không ngăn được Thanh La bước vào lồng.
