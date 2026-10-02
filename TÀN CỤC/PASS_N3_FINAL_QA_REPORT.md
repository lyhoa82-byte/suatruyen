# PASS N3 — BÁO CÁO QA CUỐI

N3 là QA giới hạn, không phải viết lại, không nén. Không mở lại AD-01–04, AD-N2-01–11, khóa EP7, cấu trúc phòng ngừa EP8–EP9, payoff Lạc Thủy. Không thêm canon, bí ẩn, payoff; không gán danh tính; không đổi mạch mở.
Điểm xuất phát: `ce23d47`.

**Giới hạn của phương pháp (nói rõ).** Phần "đọc thành tiếng" là rà soát văn bản theo góc nhìn người nghe tại các điểm nóng đã nêu, không phải buổi nghe thật. QA kỹ thuật chạy bằng script trên toàn bộ EP1–EP9. Kiểm tra mốc ngày dùng neo ngày tháng trong văn bản. Không đọc lại toàn văn EP1–EP7 và EP9 để tìm lỗi mới ngoài phạm vi trên.

---

## 1. Executive verdict

**N3 hoàn tất. Bản thảo sẵn sàng cho sản xuất / đọc thành tiếng cuối.**

- 8 chỉnh sửa bản thảo, đều nhỏ, đều là sửa lỗi thật hoặc làm rõ người nói / thời điểm. Không đổi chronology nền, sự kiện, tri thức nhân vật.
- 12 chỉnh sửa tài liệu ở 3 tệp (đồng bộ, không viết lại lịch sử).
- Không còn HIGH, không còn MEDIUM. Còn MINOR: xem mục 8.

---

## 2. Manuscript changes made

Định dạng: `EP / cảnh hoặc dòng / chữ cũ / chữ mới / lý do`. Số dòng là số dòng hiện tại trong tệp.

| # | EP / dòng | Chữ cũ | Chữ mới | Lý do |
|---|---|---|---|---|
| 1 | `EP1.txt:573` | "Kiếp trước Tử Khiêm **chết đầu tiên**. Bị chém." | "Kiếp trước Tử Khiêm **chết sau cha**. Bị chém." | R-01. Khóa canon: cha chết trước, Tử Khiêm sau. Khớp `EP1.txt:37` (cha ba ngày trước, anh hai ngày trước). Không đổi ngày hay sự kiện xung quanh |
| 2 | `ep5.txt:751` | "Nàng nhìn. **Còn mười ngày.**" | "Nàng nhìn. **Còn hơn mười ngày.**" | R-02. Neo ngày: cảnh này là đêm 20/7 (xem mục 3), tới 3/8 còn 14 ngày. Dùng đúng cách nói đã có ở `ep5.txt:365` ("Còn hơn mười ngày") |
| 3 | `ep5.txt:857` | "rằng **mười ngày nữa** ông ấy chết" | "rằng **hơn mười ngày nữa** ông ấy chết" | R-02. Cảnh này ngày 21/7, còn 13 ngày |
| 4 | `EP4.txt:733` | "Tên tuyến: **Bắc Lộ** — doanh Trấn Viễn." | "… **Bắc lộ** …" | Thuật ngữ không nhất quán: 27 chỗ viết "Bắc lộ", 3 chỗ ở EP4 viết "Bắc Lộ" |
| 5 | `EP4.txt:1525` | "Tập **Bắc Lộ** vẫn ở đó." | "Tập **Bắc lộ** vẫn ở đó." | như trên |
| 6 | `EP4.txt:1551` | "cầm tập **Bắc Lộ** lên" | "cầm tập **Bắc lộ** lên" | như trên |
| 7 | `ep8.txt:2113` | "Trên Nam lộ, Phùng Mậu nhận được tin…" | "**Đêm ấy**, trên Nam lộ, Phùng Mậu nhận được tin…" | Khôi phục mốc "đêm" N2B đã bỏ. Các cảnh liền trước là "Chiều…" và một câu "Đêm đó" nằm trong cảnh hiệu bạc; người nghe có thể không nối được thời điểm. Tránh lặp "Cùng đêm ấy" (ep8 còn hai chỗ) |
| 8 | `ep8.txt:3081` | "“Phùng Mậu bán sổ.”" | "Bùi Tấn nói tiếp: “Phùng Mậu bán sổ.”" | Người nói. Ba câu liệt kê "Phùng Mậu bán sổ / Hứa Nghiêm sửa số / Tôn Tứ tìm người ép Hàn Dực" nằm không thẻ sau "Ta mua vài người." và trước "Cố Văn Lâm?"; người nghe có thể tưởng người thẩm vấn nói. Tài liệu tác giả đã đọc đó là lời Bùi Tấn (`AUTHOR_DECISIONS.md`, N2A prep). Chỉ thêm thẻ, không đổi chữ nào khác |

Đã ghi và **chủ ý không sửa**: `ep5.txt:1381` (mốc "cùng lúc" bỏ ở N2B), "trên bảng" (`ep8.txt:1501`) — tùy chọn, không ép; xem mục 4.

Kiểm tra sau sửa: ngoặc “ ” cân (EP1 499/499, EP4 640/640, ep5 623/623, ep8 1350/1350); CRLF nguyên (LF = CR ở tất cả); chỉ đổi đúng các dòng trên (đối chiếu `git diff`).

---

## 3. Timeline verification

| Mục | Kết quả | Hành động |
|---|---|---|
| **EP1 R-01** (cha chết trước hay Tử Khiêm chết trước) | `EP1.txt:37`: cha ba ngày trước, anh hai ngày trước. `EP1.txt:573` nói "chết đầu tiên" → mâu thuẫn thật với khóa canon | **Sửa** (#1) |
| **EP5 "còn mười ngày / mười một ngày"** | Neo: 19/7 (lễ cầu phúc, `ep5.txt:369`); chuỗi "Sáng hôm sau… Trưa hôm ấy… Chiều đó… Tối hôm ấy" (`:759`–`:905`); "Sáng hai ngày sau" (`:923`) = 23/7 → "Tối hôm ấy" = 21/7 → đêm "Còn mười ngày" (`:749`) = 20/7. Kiếp trước 3/8 → còn 14 ngày, không phải mười. Hai chỗ nói "mười ngày" (`:751` và `:857`, ngày 21/7, còn 13). "Sai lệch, mười một ngày" (`:1047`: 23/7 so với 3/8) **đúng**; "Còn hơn mười ngày" (`:365`) đúng | **Sửa** hai chỗ bằng "hơn" (#2, #3). Không đổi ngày nào. Các biểu thức ước lượng khác giữ nguyên |
| **EP9 đình chức cuối tháng Tám vs 20/9** | `ep9.txt:749`: cuối tháng Tám Tĩnh An nhận quyết định, tạm đình chức sáu tháng; cảnh sau "ở nhà đã ngày thứ ba". `ep9.txt:877`: sổ **kiếp trước** ghi "Hai mươi tháng Chín, cha bị đình chức. Điều này lại xảy ra, nhưng vì lý do khác". Ngày 20/9 là ngày trong sổ ký ức (kiếp trước); việc xảy ra lại ở kiếp này vào cuối tháng Tám. Không có câu nào nói hai ngày trùng | **Giữ nguyên** (không phải mâu thuẫn thật; đã nêu trong mục 8) |
| **17/10 LK23, Thẩm phủ bị niêm phong ở kiếp trước** | Nhất quán ở `ep9.txt:975`, `:1085`, `:1165` ("Mười bảy tháng Mười, Thẩm phủ bị phong"); đếm ngược "Mười một ngày" từ đầu tháng Mười (`:~1000`); "Mười bảy" Hoài Xuyên phiên hỏi Phùng Mậu (`:1027`); cảnh Chiêu Ninh nói ngày với Hoài Xuyên có mặt trước khi anh nhắc lại ở `:1241`. `EP1.txt:191` "Bốn tháng trước ngày Thẩm phủ bị niêm phong" khớp với 11/6 → 17/10. Không còn mốc ngày khác cho sự kiện này trong EP1–EP8 (`grep "tháng Mười"`) | Không sửa |

Không có biểu thức ước lượng nào bị chuẩn hóa ngoài #2 và #3.

---

## 4. Audio hot-spot verification

Đọc theo hướng nghe, từng điểm nóng. Chỉ sửa khi người nghe có thể nhầm người nói, người hành động, nơi chốn, thời điểm hoặc ý nghĩa mã.

| Điểm nóng | Kết quả | Hành động |
|---|---|---|
| **EP7 HX-4 / Hòm Xét** (`ep7.txt:~1615`–`1830`) | Mỗi mã được giới thiệu rồi định nghĩa trong cảnh ("HX-4 là Hòm Xét số bốn", "Không phải người. Là đường chứng cứ…"); người nói rõ nhờ Hoài Xuyên / Chiêu Ninh / viên lại già luân phiên | Không sửa |
| **EP8 K7 / D2 / N4 / N-4 / BT-3** (cụm `ep8.txt:283`–`:683`) | Mỗi mã đi kèm giải thích tại chỗ ("Đừng đoán từ chữ", "chữ giống không có nghĩa cùng thứ"). Ba nghĩa của mã được văn bản tự đóng khung; không đổi tên, không thêm giải thích | Không sửa |
| **Nam 4 / Nam tứ / Ninh Tứ / Kho Bốn** | "Không phải Ninh Tứ." / "Hoặc cả hai." / "Khớp với thẻ Tôn Tứ." đủ để theo dõi | Không sửa |
| **H4 / HX-4 / Hạng bốn** | Văn bản nói thẳng "Không phải HX-4. Chỉ H4." và Tĩnh An giải thích "Hạng bốn" | Không sửa |
| **Tôn Tứ / Tứ gia** | "Cha ta gọi là Tứ gia" → "Người thiếu ngón được xác định. Tên Tôn Tứ"; không gây nhầm về người hành động | Không sửa |
| **Chuỗi hỏi–đáp dài trong EP8** (Tề Phương, Phùng Mậu về nhẫn, Hoài Xuyên–Cố, Bùi Tấn liệt kê tên) | Người hỏi và người đáp luân phiên rõ, trừ một chỗ: ba câu liệt kê của Bùi Tấn | **Sửa #8** (thẻ "Bùi Tấn nói tiếp") |
| **Hai mốc thời gian N2B bỏ** | `ep8.txt:2113`: người nghe có thể không nối được thời điểm → khôi phục "Đêm ấy," (**#7**). `ep5.txt:1381` ("Ở Binh bộ, Trần Quảng ngồi một mình."): cảnh liền trước là đêm của Chiêu Ninh; không gây nhầm | `ep5` giữ nguyên |
| **"trên bảng"** (`ep8.txt:1501`) | Tùy chọn của N2B; không ảnh hưởng nghe | Không ép; giữ nguyên |

Không có chỗ nào cần thêm giải thích kiểu trình bày.

---

## 5. Technical QA — EP1–EP9

Script chạy trên cả chín tệp.

| Kiểm tra | Kết quả |
|---|---|
| Ngoặc kép “ ” | Cân ở mọi tệp và mọi đoạn (không có đoạn mất cân); không có ngoặc thẳng `"` hay `«»` |
| Nhãn / tiêu đề kịch bản | Không có (không `INT./EXT.`, `CẢNH`, `**`, nhãn `TÊN:` viết hoa, nhãn `Tên: “…”` không động từ, dòng "…" im lặng) |
| Dấu hiệu `* * *` | Chỉ là dấu ngắt cảnh |
| Đoạn / câu lặp liền nhau | Không có |
| Khoảng trắng thừa | Không có khoảng trắng đôi, không khoảng trắng cuối dòng, không BOM |
| CRLF | Mọi tệp EP1–EP9: LF = CR, không có LF/CR lẻ |
| Tên nhân vật / địa danh | Không phát hiện lỗi chính tả (quét các từ viết hoa hiếm; mọi cái hiếm đều là tên hợp lệ) |
| Thuật ngữ không nhất quán do chuyển đổi | Một chỗ: "Bắc Lộ" ↔ "Bắc lộ" (3 chỗ EP4) → **đã sửa** (#4–#6). Các thuật ngữ khác (Đại Lý Tự, Binh bộ, Hộ bộ, Hình bộ, Hòm Xét, Lạc Thủy, Tây Uyển, Tấn Ký, Vĩnh Thái, Nam tứ, Hạng bốn, Bắc Tam…) nhất quán |
| Chữ số trong văn xuôi | Chỉ còn trong mã (HX-4, K7, D2, N4, N-4, BT-3, Nam 4, PM-6) |

Ngoài lề, **giữ nguyên:** `ep8.txt:2599` (bảng cuối) có dấu ngoặc đơn trong mục Tôn Tứ (AD-N2-02b). Là cách viết hợp lệ và là chữ đã khóa; không sửa.

---

## 6. Documentation sync

Chỉ cập nhật tài liệu **sai thực tế**, không viết lại lịch sử. Phần thân của các tài liệu Pass A giữ nguyên làm hồ sơ; thêm khối "N3 SYNC" đọc trước và sửa các điểm sai.

| Tệp | Thay đổi |
|---|---|
| `MASTER_TIMELINE.md` (7) | Thêm khối "N3 SYNC" (khóa hiện hành; số dòng cũ; nhãn pre-B1 là lỗi thời; chi tiết đã cắt/thêm ở N2B; chỉnh N3). Bảng 0.1: AD-01-SUB "chưa khóa" → đã khóa (phương án C); AD-03 và AD-04 "chưa quyết" → khóa ở B1. Dòng Trịnh Hành 3/8: bỏ "mất bản sớ" (đã cắt). Dòng chuỗi Trịnh Hành: đơn nặc danh đã cắt. Dòng cuối thu: "ba ngày sau anh bị chém" → "một ngày sau", khớp `EP1` mở đầu |
| `KNOWLEDGE_MAP.md` (3) | Thêm khối "N3 SYNC" (nhãn `CONTRADICTORY`/`SUSPECTED` gắn AD-01/AD-02 là trạng thái trước B1; tri thức đã đổi do N2B). R22 (hai chỗ): "năm phụ thuộc AD-01-SUB" → "LK23, đã khóa ở B1" |
| `AUTHOR_DECISIONS.md` (2) | Thêm khối "N3 SYNC" (AD-01…04 và AD-01-SUB đã khóa; phân tích phương án là hồ sơ lịch sử; tiền tố `AD-N2-`). Dòng `EP3` "Từ Kính khẽ siết tay": ghi chú đã cắt ở N2B (AD-N2-03b) |

**Không sửa (có chủ ý):**
- `PASS_B1_REPORT.md`, `B1_VERIFICATION_REPORT.md`, `PASS_N1A_REPORT.md`, `N1A_REVIEW_REPORT.md`, `PASS_N1B_REPORT.md`, `N1B_REVIEW_REPORT.md`, `PASS_N2A_*`, `N2B_*`, `PASS_N2B_*`, `PASS_N2C_N3_SCOPE_AUDIT.md`, `EDIT_SCOPE_REPORT.md`, `STORY_STATUS_REPORT.md`: hồ sơ lịch sử, giữ nguyên (ghi chú H-12 ở `PASS_N1B_REPORT.md` đã được `N1B_REVIEW_REPORT.md` ghi nhận là không có căn cứ; không viết lại).
- `STORY HANDBOOK.txt`, `MASTER_STORY_BIBLE.md`, `EDITING_PROTOCOL.md`: tài liệu canon do tác giả kiểm soát; không thuộc phạm vi N3. `PASS_B1_REPORT.md` đã nêu Handbook cần đồng bộ (mục 8).

Số chỉnh sửa tài liệu: **12** (7 + 3 + 2) ở **3** tệp.

---

## 7. Remaining intentional open threads (không chạm)

Tây Uyển (chưa gán ai; "Cùng một cách, chưa chắc cùng một người"); nhóm chưa rõ mặt (áo nâu bến Phúc An, giọng kinh thành, kẻ trói Hàn Dực, kẻ đốt xe) chỉ "có thể thuộc nhóm giữ người ấy"; Từ Kính; Mã Tam; chủ Tấn Ký; em gái Hàn Dực; nguyên nhân chết của Trịnh Hành; HX-4 "Ba chuyện, cùng một cửa… Chưa biết"; con dấu mẻ (đã bỏ); Bùi Tấn và Nhị hoàng tử xuất hiện từ EP8 (không thêm dấu hiệu sớm); K7/D2/N4 với nhiều nghĩa; hộp trong Binh bộ "Không biết"; người mua sổ bù "người của phủ"; "Người khởi đầu? Có thể đã chết."; nhẫn ngọc đen; Nhị hoàng tử "không chắc"; Tam hoàng tử "Ta sẽ tra"; Thẩm phu nhân "Năm đó ông giấu ta"; hook EP1 ("Phía trên đã có lệnh", "Bắc môn có động!"); chủ kho số ba; bốn hiệu bạc; dấu Ty Thông hành "nét khuyết"; vết thương trán Lục Trầm; kết ep8 "Chưa."; hai điểm neo luận đề `ep6` sc.49 và `ep9` sc.6; khóa EP7; khóa EP8–EP9; Lạc Thủy "Đê không vỡ."

---

## 8. Deferred issues

| ID | Vấn đề | Mức | Ghi chú |
|---|---|---|---|
| D-1 | `STORY HANDBOOK.txt` chưa đồng bộ các khóa B1/AD-N2 (knowledge state, setup mở, kết quả AD-01/03/04, mốc 17/10) | MINOR | Tài liệu canon của tác giả; `PASS_B1_REPORT.md` đã nêu. Cần tác giả quyết định |
| D-2 | Phần thân `MASTER_TIMELINE.md`, `KNOWLEDGE_MAP.md`, `AUTHOR_DECISIONS.md` vẫn còn số dòng cũ và nhãn pre-B1 | MINOR | Đã có khối "N3 SYNC" đọc trước; viết lại toàn bộ sẽ xóa dấu vết lịch sử |
| D-3 | "trên bảng" (`ep8.txt:1501`) lệch nhẹ "giấy chia bốn phần" → "bảng" | MINOR | Tùy chọn của N2B, không ép |
| D-4 | `ep5.txt:1381` bỏ "cùng lúc" | MINOR | Không gây nhầm; giữ nguyên |
| D-5 | `ep9.txt:749` và `:877` (đình chức) đọc được như mốc kiếp này (cuối tháng Tám) và mốc kiếp trước (20/9) | MINOR (thấp) | Không phải mâu thuẫn thật; giữ nguyên |
| D-6 | Dấu ngoặc đơn trong mục Tôn Tứ của bảng cuối (`ep8.txt:2599`) | MINOR (thấp) | Đã khóa theo AD-N2-02b; đọc thành tiếng chấp nhận được |

---

## 9. Final recommendation

- **Bản thảo sẵn sàng cho sản xuất / đọc thành tiếng cuối.** Không còn HIGH, không còn MEDIUM.
- Rủi ro duy nhất còn lại là mức audio (mật độ mã/tên ở EP8) và chỉ kiểm hẳn được bằng một buổi nghe thật.
- Nếu tác giả muốn, có thể xử lý D-1 (đồng bộ Handbook) bằng một việc riêng do tác giả duyệt.

**Số liệu cuối:**
- Chỉnh sửa bản thảo: **8** (`EP1` 1, `EP4` 3, `ep5` 2, `ep8` 2).
- Chỉnh sửa tài liệu: **12** (3 tệp).
- HIGH còn lại: **0**. MEDIUM còn lại: **0**. MINOR còn lại: **6** (D-1…D-6), tất cả tùy chọn.

STOP: không bắt đầu pass cấu trúc khác, không tạo N4, không viết lại, không nén thêm.
