> **DERIVED / NON-CANON.** DERIVED files have zero canon authority. They are convenience indexes only.
> Thứ tự ưu tiên: LOCKED / Canon Update → Bible quy định → Derived → Draft.
> Nếu Derived sai: sửa/xóa Derived; KHÔNG BAO GIỜ sửa Canon để làm Derived khớp.
> Derived Registry không bao giờ được giải quyết một mâu thuẫn Canon; chỉ được chỉ ra mâu thuẫn đó (mục "MÂU THUẪN / LỆCH").
> Trạng thái: dựng từ Canon Update Ch01–Ch22 (cuối Ch22). Đã Consistency Check + QA 30 claim (vòng 1) + sửa vòng 1.

# CHARACTER BIBLE — DERIVED (CỬU CHÂU LOẠN THẾ)

Chỉ mục nhân vật gộp từ 4 dải trích xuất (Ch01–07, Ch08–13, Ch14–18, Ch19–22). Nguồn duy nhất là `canon/CCLT_Canon_Update_ChNN.md`. Không thêm claim mới; không giải quyết mâu thuẫn Canon.

## 0. CHÚ GIẢI SOURCE TYPE (đúng 6 giá trị)

| Source Type | Nghĩa |
|---|---|
| `CANON_FACT` | Fact đã có trên trang / đã khóa trong Canon Update (mục "Canon mới", "Canon Change", fact khách quan; dòng "Biết" của Knowledge Matrix). |
| `CANON_BELIEF` | Điều một nhân vật TIN chắc (cột "Tin" / "Niềm tin" của Knowledge Matrix; có thể sai). Ai tin được ghi trong câu. |
| `CANON_SUSPICION` | Điều một nhân vật NGHI / ĐOÁN / SUY, chưa xác nhận — gồm cả cột "INFERENCE" / "suy luận" / "đoán" của Knowledge Matrix khi nói về MỘT nhân vật (ghi ai suy). Lời đồn, "NGHE / THUẬT LẠI (không xác nhận)", tin chưa xác nhận cũng dùng loại này; đầu nội dung ghi "(lời đồn)" hoặc "(nghe thuật lại)". |
| `CANON_INFERENCE` | Chỉ dành cho suy ra cấp tác giả / Canon Update (số ngày "~", "suy ra", ước tính), không phải suy luận của nhân vật. |
| `CANON_UNKNOWN` | Canon Update ghi rõ OPEN / chưa biết / không biết / chưa trả lời. Nếu chỉ OPEN theo điểm nhìn một nhân vật mà Canon đã có ở chương khác, nội dung ghi phạm vi: "OPEN với <ai> / trên trang POV <ai>; Canon đã có ở ChNN §…". |
| `PLANNING_NON_CANON` | Kế hoạch, author-truth (không lên trang), "Chapter Bible dự kiến", ràng buộc Ch+, đề xuất chưa duyệt. Chỉ nằm ở mục (c) riêng. |

## 0.1 CÁCH ĐỌC

- **Source** có dạng `Ch{NN} §{mục}` (+ `.{số mục con}`), ví dụ `Ch12 §I.7`, `Ch22 §III (Dịch)`, `Ch08 §VII`. Mỗi file Canon Update đánh số mục riêng: `§0` = Revision / Canon Sync; `§I` = Canon mới (dòng đánh số liên tục); `§II` = không phải canon / OPEN; `§III` = Knowledge Matrix; `§IV` = State Ledger; `§V` = Seed; `§VI` = Emotional Debt; `§VII` = Timeline; `§IX` = Open threads. Một số dòng ghi Source dạng `ChNN §Nguyên tắc ghi` (đoạn mở đầu file) hoặc `ChNN §đầu file` (đã chuẩn hóa từ dạng `ChNN (đầu file)` của staging).
- Mỗi nhân vật chính có 3 phần: **(a) TRẠNG THÁI CUỐI CH22** = với từng trường, các dòng staging **gần nhất** (GOAL 2, FEAR/WEAKNESS 2, LIMIT 3, RELATION mỗi bên 1, STATE 3, KNOWLEDGE tách theo Source Type tối đa 2–3 dòng/loại) cùng toàn bộ dòng APPEARANCE (có/vắng/POV). Đây là chọn lọc cơ học, KHÔNG phải tổng hợp mới; nhân vật không có dòng ở chương muộn thì giữ giá trị ở chương ghi trong cột Ch. **(b) LỊCH SỬ before → after** theo thứ tự chương; cột "Nối chuỗi" trỏ tới dòng trước cùng đề tài (cùng bên với RELATION) khi chuỗi vượt ranh giới dải (Ch07|Ch08, Ch13|Ch14, Ch18|Ch19) hoặc khi bỏ qua hàng; ghi `(Before chưa trích được)` khi dòng trước cùng trường khác đề tài và Canon Update không cho phép nối; không nối qua ranh giới bí danh chưa xác nhận (mục 2.2). Dòng ghi `(đầu dải)` nghĩa là Canon Update của chương đó không nêu trạng thái trước. **(c) PLANNING_NON_CANON** của nhân vật (nếu có).
- `⟦…⟧` = chú thích của file derived: `ST gốc` là ô Source Type nguyên văn của staging khi ô đó có ghi chú/qualifier; `ô kép → tách k/n` là dòng staging gắn 2+ Source Type trong một ô, đã tách mỗi loại một dòng; từ sửa vòng 1, nội dung mỗi dòng chỉ giữ phần đúng với loại của dòng đó (R4). Dòng gắn `[CANON CHANGE]` giữ nguyên nhãn Canon Update.
- Giá trị "khoảng/chừng/ước chừng" giữ nguyên chữ của Canon Update.
- Bảng bí danh (mục 2) chỉ liệt kê nhãn mà Canon Update dùng; cột "Đồng nhất?" là ghi chú tra cứu của file derived, không phải claim canon. Nơi Canon Update không xác nhận hai nhãn là một người thì giữ tách và trỏ tới mục `MÂU THUẪN / LỆCH`. Khối gộp nhãn chưa xác nhận mang thẻ `[BÍ DANH CHƯA XÁC NHẬN — xem CB-L-xx]` ở đầu khối; mỗi dòng mang nhãn gốc trong ngoặc vuông.

## 1. MỤC LỤC NHÂN VẬT

| # | Nhân vật chính (mục) | Chương có dòng staging (đầu → cuối) | Số dòng canon (dòng APPEARANCE ở (a) + dòng (b); sau sửa vòng 1) | Số dòng PLANNING (c) (sau sửa vòng 1) | Mức xuất hiện (suy từ các dòng APPEARANCE của staging) |
|---|---|---|---|---|---|
| 1 | [DỊCH (Thẩm Dịch / Trình Dịch / Tiêu Dịch)](#nv-dich) | Ch01 → Ch22 | 231 | 6 | POV: Ch07, 08, 09, 12, 13 (đoạn I), 15, 16, 19, 22. Không POV: Ch10, 11, 17. Vắng: Ch02, 06, 14, 18, 20, 21. Nhiều nhãn tên (mục 2). |
| 2 | [BÙI CHỈ (A Quy)](#nv-chi) | Ch01 → Ch21 | 99 | 4 | POV: Ch11, 13 (đoạn IV), 14. Có mặt không POV: Ch12. Vắng: Ch15–18, Ch20 (Ch21: chỉ qua "người đi bến", mục (d)). |
| 3 | [UYỂN (Tiêu Uyển; Vĩnh Ninh công chúa)](#nv-uyen) | Ch01 → Ch22 | 73 | 5 | POV: Ch13 (đoạn III), 18. Có mặt không POV: Ch12. Không có mặt/vắng: Ch10, 14–17, 19, 22 (Ch20: chỉ qua thư + gói). "Khả đôn" giữ tách (mục 2, CB-L-25). |
| 4 | [HOẮC CHIÊU (Hoắc Tam Lang)](#nv-chieu) | Ch01 → Ch22 | 123 | 5 | POV: Ch06, 10, 13 (đoạn II), 17. Có mặt không POV: Ch12, 15, 16, 19. Vắng: Ch08, 14, 18, 20–22. Tam Lang = Hoắc Chiêu: Canon xác nhận (Ch12 §III; Ch12 §I.29); "Hoắc quân" Ch14 còn treo (CB-L-27). |
| 5 | [TẠ VÂN CHƯƠNG](#nv-vc) | Ch01 → Ch22 | 102 | 4 | POV: Ch13 (đoạn V), 20, 21. Có mặt không POV: Ch03 (trực tiếp lần đầu), 12, 14. Vắng: Ch06–08, 15–19, 22. |
| 6 | [HẠ HẦU / HẠ HẦU LIỆT](#nv-hahau) | Ch08 → Ch22 | 22 | 2 | Không POV; không có dòng "có mặt trực tiếp"; Ch18–22 vắng/không xuất hiện. Hiện diện qua tin trạm, quân, sứ, thư. [BÍ DANH CHƯA XÁC NHẬN — CB-L-32] |
| 7 | [CHU HẠC](#nv-chuhac) | Ch01 → Ch11 | 20 | 3 | Dòng APPEARANCE: Ch10 vắng (hiện diện qua thư). Dòng canon chính ở Ch01–06; từ Ch09 trở đi chủ yếu là PLANNING / OPEN / niềm tin của người khác. |
| 8 | [HÀN (Hàn Đô úy)](#nv-han) | Ch08 → Ch22 | 40 | 0 | Có mặt không POV: Ch08, 15, 19, 22. Vắng: Ch18, Ch20–21. |
| 9 | [BÀNG](#nv-bang) | Ch09 → Ch22 | 16 | 2 | Không xuất hiện trực tiếp; chỉ qua thư/lời người khác (Ch15, 19) hoặc vắng (Ch16–18, 20–22). |
| 10 | [ÔN / THỨ SỬ](#nv-on) | Ch08 → Ch22 | 29 | 2 | Có mặt: Ch08. Chỉ qua thư/ấn: Ch16. Không xuất hiện: Ch17, 19–22. [BÍ DANH CHƯA XÁC NHẬN — CB-L-26]: dòng giữ nhãn gốc. |
| 11 | [PHÙNG THÚC / PHÙNG BẢO](#nv-phung) | Ch01 → Ch11 | 21 | 0 | Có mặt: Ch01, Ch08. Không xuất hiện: Ch11. [BÍ DANH CHƯA XÁC NHẬN — CB-L-01]: Ch01–Ch07 nhãn "Phùng thúc"; Ch04 §I.9, Ch08–Ch11 nhãn "Phùng Bảo". |
| 12 | [TÔ (Tô Biệt giá)](#nv-to) | Ch08 → Ch09 | 11 | 0 | Có mặt: Ch08. |

Nhân vật phụ và nhân vật có khối riêng thứ yếu (Hoắc Thành Lĩnh, Lão Tần, Tạ Diên, Kha Trọng, Tu Bặc Cốt, Hách Liên Chước, Tiểu Thất, "G", …) nằm ở mục 4.

## 2. BẢNG BÍ DANH / TÊN KHÁC

### 2.1 Nhãn Canon Update dùng cho nhân vật chính

| Nhân vật | Tên / nhãn (Canon Update ghi) | Source Type | Source | Đồng nhất? (ghi chú derived, không phải claim canon) |
|---|---|---|---|---|
| DỊCH | "Thẩm Dịch"; "Thẩm thư lại" | CANON_FACT | Ch01 §I.3; Ch03 §I.48; Ch04 §I.20 | — |
| DỊCH | "Tiêu Dịch" (CANON CHANGE tuổi: 17 ở Ch1, 27 ở năm 0; nhãn POV ở header nhiều chương) | CANON_FACT | Ch01 §IX; Ch12 §Nguyên tắc ghi; Ch15 §Nguyên tắc ghi; Ch16 §Nguyên tắc ghi; Ch22 §Nguyên tắc ghi | Canon Update không nêu quan hệ giữa Tiêu / Thẩm / Trình → CB-L-03 |
| DỊCH | "Trình Dịch"; "Trình tiên sinh" (ký "Trình Dịch") | CANON_FACT | Ch08 §I.1; Ch08 §I.31 | — |
| DỊCH | "Trình Dịch = Thẩm thư lại" (Chỉ biết; Chiêu biết; Uyển biết) | CANON_FACT | Ch11 §III; Ch12 §III | Canon xác nhận Thẩm = Trình qua Knowledge Matrix; không xác nhận cho "Tiêu" |
| DỊCH | "Thất điện hạ" (người khác gọi); Dịch tự nói "Ta là con của Thẩm chiêu nghi." | CANON_FACT | Ch08 §I.19; Ch08 §I.32–34 | — |
| DỊCH | "Dịch chính là con trai Thẩm chiêu nghi (Thất hoàng tử)" — Vân Chương tin rất cao, chưa xác nhận | CANON_BELIEF | Ch04 §III | Canon Ch4 không xác nhận → CB-L-02 |
| DỊCH | "Ngài là người họ Tiêu?" (người khác hỏi; Dịch không đáp) | CANON_FACT | Ch19 §I.19; Ch22 §I.25; Ch22 §I.27 | Không xác nhận họ |
| BÙI CHỈ | "A Quy" (Hoắc đặt, qua lời Tam Lang) | CANON_FACT | Ch03 §I.4 | — |
| BÙI CHỈ | "Bùi Chỉ" (nội tâm Chỉ; tin tên A Quy do cha [Hoắc] đặt) | CANON_BELIEF | Ch03 §I.5 | — |
| BÙI CHỈ | "Bùi Chỉ"; "A Quy (Chỉ)"; Chỉ nhận "A Quy" trước Dịch | CANON_FACT | Ch11 §I.16; Ch11 §III; Ch12 §III | Canon xác nhận A Quy = Bùi Chỉ (Ch11, Ch12); ở Ch03 Dịch/Uyển không biết A Quy là Bùi Chỉ (Ch03 §III, CANON_UNKNOWN) |
| BÙI CHỈ | "đương gia" (người của Chỉ gọi); "đầu lĩnh Dạ Kiêu"; "người của Dạ Kiêu" | CANON_FACT | Ch11 §IV; Ch14 §I.4; Ch12 §I.30 | — |
| UYỂN | "Tiêu Uyển"; "Vĩnh Ninh công chúa"; "Uyển" | CANON_FACT | Ch01 §I.11; Ch07 §I.18 | — |
| UYỂN | "Khả đôn"; "trướng Khả đôn" | CANON_FACT | Ch10 §III; Ch12 §III; Ch12 §IV; Ch18 §I.2; Ch18 §I.14; Ch18 §I.17 | Ch10 §III gộp "Uyển / Khả đôn"; Ch12 §III ghi chung ô "Vĩnh Ninh công chúa; Khả đôn"; Ch17 §III liệt kê "Uyển" và "Khả đôn" riêng; không có câu "=" tường minh → giữ khối "Khả đôn" tách (khối UYỂN mục (e)), CB-L-25 |
| HOẮC CHIÊU | "Hoắc Tam Lang"; "Tam công tử"; "Tam Lang" | CANON_FACT | Ch01 §I.4; Ch02 §I.23–25; Ch03 §I.48 | — |
| HOẮC CHIÊU | "A Chiêu" (cha gọi); narration gọi "nàng" từ Ch06 | CANON_FACT | Ch06 §I.20; Ch06 §I.21 | Canon xác nhận Tam Lang là nàng/A Chiêu |
| HOẮC CHIÊU | "Tam tướng quân"; "Hoắc Chiêu" ("Người hứa là Hoắc Chiêu."; "Tam Lang là Hoắc Chiêu") | CANON_FACT | Ch10 §I.4; Ch12 §I.29; Ch12 §I.30; Ch12 §III | Canon xác nhận Tam Lang = Hoắc Chiêu ở Ch12 §III (giữ gộp khối 3.4); phần còn treo: nhãn "Hoắc quân" / "Tam tướng quân" ở Ch14 → CB-L-27 |
| HOẮC CHIÊU | "Hoắc quân" (nhãn lực lượng; Ch14 không gắn tên Chiêu) | CANON_FACT | Ch12 §I.4; Ch14 §I.2; Ch14 §III | "Hoắc quân" là lực lượng; không đồng nhất tường minh với Chiêu ở Ch14 → CB-L-27 |
| TẠ VÂN CHƯƠNG | "Tạ phó sứ"; "Tạ mỗ" (tự xưng); "Tạ đại nhân" | CANON_FACT | Ch03 §I.35; Ch12 §I.30; Ch14 §I.6 | — |
| TẠ VÂN CHƯƠNG | "Tạ Vân Chương"; "Vân Chương"; "chàng" | CANON_FACT | Ch08 §I.6 | Ch14 §I.6 Chỉ gọi "Tạ đại nhân"; lời đồn "phủ lớn họ Tạ" không được nối với Vân Chương (CB-L-31) |
| PHÙNG THÚC / PHÙNG BẢO (khối 3.11) | "Phùng thúc"; "lão Phùng" (hàng xóm gọi) | CANON_FACT | Ch01 §I.13; Ch01 §VI | Nhãn "Phùng thúc"; không có câu "Phùng thúc = Phùng Bảo" tường minh → CB-L-01 |
| PHÙNG THÚC / PHÙNG BẢO (khối 3.11) | "Phùng Bảo" (sửa thói quen viết chữ "Huệ" của Dịch sau khi rời cung); có mặt, giao khóa trường mệnh | CANON_FACT | Ch04 §I.9; Ch08 §I.12; Ch08 §I.15–16 | Ch08 §V có dòng "Bọc vải của Phùng thúc (Ch7)" payoff bằng khóa trường mệnh do Phùng Bảo giao; không có câu "Phùng thúc = Phùng Bảo" tường minh (Ch04 §II ghi KHÔNG PHẢI Canon) → CB-L-01 |
| CHU HẠC | "Chu Hạc"; phó tướng Hoắc gia quân | CANON_FACT | Ch01 §I.10 | Dòng "Phó tướng Hoắc quân" vô danh ở Ch15–16 không gắn tên Chu Hạc → CB-L-34 |
| HÀN | "Hàn Đô úy"; "Hàn"; sĩ quan gọi "Đô úy" (hook Ch19) | CANON_FACT | Ch08 §I.17; Ch19 §I.22 | Có thêm "Đô úy" thành Dĩnh Xuyên (người khác) → CB-L-28 |
| BÀNG | "Bàng mỗ, trấn thủ biên tây" (người ký thư; Tây Lương); "Bàng tướng quân" | CANON_FACT | Ch09 §I.3; Ch15 §I.30 | Liên hệ Bàng – Hạ Hầu: OPEN (Ch09 §II) → CB-L-32 |
| HẠ HẦU | "Hạ Hầu Liệt" (quân Tây Lương vào Lạc Kinh); "Hạ Hầu"; "cờ / kỵ / sứ Hạ Hầu" | CANON_FACT | Ch08 §I.6; Ch15 §I.16; Ch15 §I.29–30 | Không nối tường minh "Hạ Hầu" (lực lượng) với "Hạ Hầu Liệt" ở Ch15+; sứ Hạ Hầu ≠ tướng Tây Lương gửi thư (Ch08 §IV) → CB-L-32 |
| ÔN / THỨ SỬ (khối 3.10) | "Ôn Thứ sử"; "Ôn"; "Thứ sử"; "ấn Thứ sử" | CANON_FACT | Ch08 §I.6; Ch08 §I.10; Ch16 §I.16; Ch16 §I.31 | Ch08 gọi "Ôn Thứ sử"; Ch16 dùng "Thứ sử" và "Ôn" riêng → CB-L-26 |
| TÔ | "Tô Biệt giá"; "Tô" | CANON_FACT | Ch08 §I.17 | — |

### 2.2 Cặp nhãn KHÔNG hợp nhất / Canon Update không xác nhận tường minh

Quy ước: file này không gộp hai nhãn thành một người khi Canon Update không viết rõ. Nơi mục 3 dùng một khối cho nhiều nhãn chưa xác nhận (Phùng thúc / Phùng Bảo, Ôn / Thứ sử, Hạ Hầu / Hạ Hầu Liệt, Uyển / Khả đôn, Tiêu / Thẩm / Trình), đầu khối gắn thẻ `[BÍ DANH CHƯA XÁC NHẬN]`, từng dòng giữ nhãn gốc và cột "Nối chuỗi" không nối qua ranh giới hai nhãn. Riêng Hoắc Tam Lang = Hoắc Chiêu đã được Canon xác nhận (Ch12 §III; Ch12 §I.29) nên giữ gộp.

| Nhãn A | Nhãn B | Nơi Canon Update dùng (Source) | Xử lý trong file này | L |
|---|---|---|---|---|
| Uyển | Khả đôn / trướng Khả đôn | Ch12 §III; Ch17 §III; Ch18 §I.2 | Giữ khối "Khả đôn" tách (khối UYỂN mục (e)); nội dung Ch10 §III "Uyển / Khả đôn" nằm ở khối Uyển theo cách gộp của Canon Update | CB-L-25 |
| Ôn | Thứ sử | Ch08 §I.6; Ch16 §I.16; Ch16 §I.31 | Một khối "ÔN / THỨ SỬ" gắn thẻ bí danh chưa xác nhận; từng dòng mang nhãn gốc ([Ôn], [Ôn Thứ sử] hay [Thứ sử]); không kết luận hai nhãn là một | CB-L-26 |
| Hoắc Tam Lang | Chiêu / "Hoắc quân" | Ch06 §I.21; Ch12 §III; Ch14 §I.2; Ch20 §I.2 | Một khối "HOẮC CHIÊU": Tam Lang = Hoắc Chiêu đã được Canon xác nhận (Ch12 §III; Ch12 §I.29), giữ gộp; "Hoắc quân" ở Ch14 không gắn tên Chiêu; không đồng nhất thân binh "Tam tướng quân" (Ch14) với thân binh Chiêu | CB-L-27 |
| Phùng thúc | Phùng Bảo | Ch04 §I.9; Ch08 §V | Một khối "PHÙNG THÚC / PHÙNG BẢO" gắn thẻ bí danh chưa xác nhận; từng dòng mang nhãn gốc; không nối chuỗi qua ranh giới hai nhãn; không có câu "=" tường minh (Ch08 §V chỉ payoff "Bọc vải của Phùng thúc" bằng khóa trường mệnh) | CB-L-01 |
| Tiêu Dịch | Thẩm Dịch / Trình Dịch | Ch01 §IX; Ch11 §0D; Ch12 §Nguyên tắc ghi; Ch16 §I.16 | Một khối "DỊCH" (Canon Update Ch11 §III nối Trình = Thẩm; Tiêu chỉ là nhãn header/CANON CHANGE tuổi) | CB-L-03 |
| Hạ Hầu (cờ / kỵ / sứ) | Hạ Hầu Liệt; Bàng | Ch08 §I.6; Ch09 §II; Ch15 §I.30 | Một khối "HẠ HẦU / HẠ HẦU LIỆT" gắn thẻ bí danh chưa xác nhận, dòng giữ nhãn gốc; Bàng khối riêng | CB-L-32 |
| Chỉ | "người đi bến" (Ch21) | Ch14 §I.18; Ch21 §I.9–10; Ch21 §III | Dòng nhãn "Người đi bến (Chỉ)" tách ở mục (d) của khối Chỉ | CB-L-30 |
| Kha Trọng (sổ cũ) | Kha Trọng (người bảo lãnh); "lão Kha"; "phủ lớn họ Tạ" | Ch14 §I.8; Ch14 §I.23–27; Ch14 §II | Giữ OPEN (Ch14 §II); không nối với Tạ gia của Vân Chương | CB-L-31 |
| Hàn Đô úy | Đô úy thành Dĩnh Xuyên | Ch08 §I.17; Ch19 §I.19; Ch19 §I.22 | Hai người khác nhau theo ghi chú staging; không gộp | CB-L-28 |
| "G" (tướng giữ Hổ Lao; thư xin hàng) | "Một tướng của Hạ Hầu" giữ thành đêm qua | Ch20 §I.22–23; Ch22 §I.26 | Canon Update không nói có phải một người; không gộp | CB-L-22 |
| Phó tướng Hoắc quân (Ch15–16, vô danh) | Chu Hạc (phó tướng Hoắc gia quân) | Ch01 §I.10; Ch16 §I.7 | Không gộp | CB-L-34 |
| Tiết tướng quân | "tướng giữ ải Tây" | Ch08 §I.9; Ch09 §IV | Canon Update không nêu tường minh Ch08 §I.9 là Tiết; không gộp | CB-L-33 |
| Sĩ quan Ích Châu (Ch15–16, 19, 22) | nhiều người cùng nhãn | Ch19 §I.6; Ch19 §I.13; Ch22 §0 | Một khối tra cứu, không khẳng định một người | CB-L-29 |
| Tiểu Tứ (thân binh, Ch06) | Tiểu Thất (thân binh Chiêu, Ch17) | Ch06 §I.9; Ch17 §0 | Tên khác nhau; không có câu nối; hai dòng riêng ở mục 4 | — |

## 3. NHÂN VẬT CHÍNH

### 3.1 DỊCH (Thẩm Dịch / Trình Dịch / Tiêu Dịch) <a id="nv-dich"></a>

[BÍ DANH CHƯA XÁC NHẬN — "Tiêu Dịch" ↔ Thẩm / Trình, xem CB-L-03; Thẩm = Trình đã xác nhận ở Ch11 §III]

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE | (đầu dải) → first; thư lại Hộ phòng phủ Vân Trung, được Tri phủ giao đối sổ mùa đông | Ch01 | CANON_FACT | Ch01 §I.3 |
| APPEARANCE | vắng: không có thông tin gì về sự kiện Ch2 "trong truyện" | Ch02 | CANON_FACT | Ch02 §III |
| APPEARANCE | vắng: "Không xác định trong Ch6" | Ch06 | CANON_UNKNOWN | Ch06 §IV |
| APPEARANCE | POV Thẩm Dịch | Ch07 | CANON_FACT | Ch07 §đầu file |
| APPEARANCE | POV Dịch (cả chương) | Ch08 | CANON_FACT | Ch08 §Nguyên tắc ghi |
| APPEARANCE | POV Dịch | Ch09 | CANON_FACT | Ch09 §Nguyên tắc ghi |
| APPEARANCE | Không POV; Knowledge Dịch/Vân Chương/A Quy/Bắc Môn "không đổi" so với đầu chương | Ch10 | CANON_FACT | Ch10 §III |
| APPEARANCE | Không POV (POV Bùi Chỉ); là mục tiêu của đơn Dạ Kiêu | Ch11 | CANON_FACT | Ch11 §Nguyên tắc ghi, §I.6 |
| APPEARANCE | POV Dịch | Ch12 | CANON_FACT | Ch12 §Nguyên tắc ghi |
| APPEARANCE | POV (đoạn I, đầu chương; chương POV luân phiên) | Ch13 | CANON_FACT | Ch13 §Nguyên tắc ghi, §I (I — Dịch) |
| APPEARANCE | vắng (không xuất hiện; không biết có phép thử) | Ch14 | CANON_FACT | Ch14 §III |
| APPEARANCE | POV toàn chương; Canon Update gọi "Tiêu Dịch" | Ch15 | CANON_FACT | Ch15 §Nguyên tắc ghi |
| APPEARANCE | POV toàn chương | Ch16 | CANON_FACT | Ch16 §Nguyên tắc ghi |
| APPEARANCE | không POV; tới một mình gò phía bắc Lạc Thủy (hai kỵ Ích Châu ngoài dây gác), mang cuộn giấy rồi mang về | Ch17 | CANON_FACT | Ch17 §I.3 |
| APPEARANCE | vắng | Ch18 | CANON_FACT | Ch18 §III |
| APPEARANCE | POV toàn chương (narration "Dịch"/"hắn") | Ch19 | CANON_FACT | Ch19 §Nguyên tắc ghi |
| APPEARANCE | vắng (không trên trang) | Ch20 | CANON_FACT | Ch20 §III |
| APPEARANCE | vắng | Ch21 | CANON_FACT | Ch21 §0 (Canon Sync, CC-2/DANH-A); Ch21 §III |
| APPEARANCE | POV toàn chương (narration "Dịch"/"hắn") | Ch22 | CANON_FACT | Ch22 §Nguyên tắc ghi |
| GOAL | quyết định tại cổng bến: "Đi dọc chân tường. Vào cổng bến. Giữ cổng. Chỉ giữ cổng." (lý do duy nhất nhìn thấy: "Họ nhìn ra sông.") | Ch22 | CANON_FACT | Ch22 §I.12 |
| GOAL | sáng: "Vào thành. Giữ kho." (chia bộ "Hai"); "Không." với việc đuổi cột bại quân | Ch22 | CANON_FACT | Ch22 §I.17 |
| LIMIT | cố ý: "Ai ăn số này?"/"Ngoài lương?" không hỏi lần ba; "Thuyền sao không vào bến?" không hỏi thêm | Ch22 | CANON_FACT | Ch22 §I.3, I.24 |
| LIMIT | không đáp "Ai hợp lệ?" (không ai đáp) và không đáp "Ngài là người họ Tiêu?" — "Hắn trả bút." | Ch22 | CANON_FACT | Ch22 §I.25, I.27 |
| LIMIT | không đáp sĩ quan Ích Châu về việc để cột đi / cho cầm xô | Ch22 | CANON_FACT | Ch22 §I.17, I.19 |
| RELATION(Hoắc Tam Lang) | (đầu dải) → lần đầu chạm mặt | Ch01 | CANON_FACT | Ch01 §I.4 |
| RELATION(Tiêu Uyển, Tạ Vân Chương) | chưa có tương tác với Dịch | Ch01 | CANON_FACT | Ch01 §III |
| RELATION(Chu Hạc / lính gác đêm) | lời hứa chưa trả → đã trả một phần (26/30), đóng | Ch03 | CANON_FACT | Ch03 §VII |
| RELATION(A Quy) | → thấy A Quy nắm gậy chặt tới trắng khớp ngón khi Hoắc đi ngang; không hỏi | Ch03 | CANON_FACT | Ch03 §I.33 |
| RELATION(Phùng thúc) | (như Ch1) → dìu lão suốt đường; "Hai chiều, ACTIVE" | Ch07 | CANON_FACT | Ch07 §I.13, §VI |
| RELATION(Phùng Bảo) | Phùng Bảo đứng ra làm chứng, tự đặt mình trở lại trong án cũ → DEBT thật, ACTIVE | Ch08 | CANON_FACT | Ch08 §VI |
| RELATION(Thẩm chiêu nghi) | Moral burden / identity burden, không phải debt thông thường; ACTIVE, không nói ra | Ch08 | CANON_FACT | Ch08 §VI |
| RELATION(Tô) | Dịch không trả lời "là ai, muốn gì"; Dịch đáp Tô: "Người ở ải Tây ăn lương. Không ai ăn được huyết thống." | Ch09 | CANON_FACT | Ch09 §I.24, I.27 |
| RELATION(Tam Lang) | Nợ Ch7 "được gỡ một phần", món nợ còn | Ch09 | CANON_FACT | Ch09 §VI |
| RELATION(Bùi Chỉ) | Món nợ Ch7 (không quay lại) "chạm tới" qua "Ngươi còn sống.", không nói ra; ACTIVE | Ch11 | CANON_FACT | Ch11 §VI |
| RELATION(Ôn / Hàn) | Mới: bảo chứng A Quy bằng danh Ích Châu mà không được dặn; ACTIVE | Ch12 | CANON_FACT | Ch12 §VI |
| RELATION(Uyển) | Đứng nhìn nàng tự đi (Ch7); ACTIVE, chưa chạm | Ch12 | CANON_FACT | Ch12 §VI |
| RELATION(Vân Chương) | Vân Chương viết "người tự nhận" dù biết; không báo Dịch — Mới, ACTIVE (nợ của Vân Chương → Dịch) | Ch13 | CANON_FACT | Ch13 §VI |
| RELATION(Ích Châu / Ôn / sĩ quan) | Mất cột và đoàn xe; thư Bàng bị nhắc công khai — mới, ACTIVE | Ch15 | CANON_FACT | Ch15 §VI |
| RELATION(làng trưởng) | Phiếu nợ mang tên mình — mới | Ch16 | CANON_FACT | Ch16 §VI |
| RELATION(Ôn) | muối vượt trần — ACTIVE (không đổi) | Ch22 | CANON_FACT | Ch22 §VI |
| RELATION(người mở cửa Dĩnh Xuyên) | lời hứa C1 (văn bản trong tay họ) — nợ mới, ACTIVE | Ch19 | CANON_FACT | Ch19 §VI |
| RELATION(Kim Lăng/Vân Chương) | vượt quyền ân xá: Before ACTIVE (Dịch nợ) → After "Kim Lăng đã ôm hậu quả (Dịch chưa biết)" | Ch20 | CANON_FACT | Ch20 §VI |
| RELATION(người mở cửa) | lời hứa C1: "nay có ngai đứng tên" | Ch20 | CANON_FACT | Ch20 §VI |
| RELATION(Hàn) | nợ mới của Dịch với Hàn/bộ Ích Châu: cho họ đứng một đêm trên đê không che — ACTIVE | Ch22 | CANON_FACT | Ch22 §VI |
| RELATION(sĩ quan Ích Châu) | "Chúng giết bộ ta ở cổng đêm qua. Ngươi để chúng đi." / "Ngươi cho chúng cầm xô." — Dịch không đáp; nợ mới ACTIVE | Ch22 | CANON_FACT | Ch22 §I.17, I.19; Ch22 §VI |
| RELATION(phó tướng thủy quân) | hỏi "Ai ăn số này?", "Ngoài lương?" → "Báo ghi lương." / "Lịch ghi lương."; "Thuyền chưa dỡ. Lương còn nguyên." | Ch22 | CANON_FACT | Ch22 §I.3, I.24 |
| RELATION(hàng binh Hổ Lao) | lời hứa C1 thành của triều đình; không rút được — nợ mới, ACTIVE | Ch22 | CANON_FACT | Ch22 §VI |
| RELATION(Kim Lăng) | (thuyền; sổ kho) "Một nghi vấn không đáp" — mới, ACTIVE | Ch22 | CANON_FACT | Ch22 §VI |
| RELATION(Danh) | (sứ Ích Châu, không "Tiêu"; tên trong chữ người khác) không đáp "họ Tiêu?"; chiếu có ấn — mới, ACTIVE | Ch22 | CANON_FACT | Ch22 §VI |
| RELATION(người chết / lạc) | danh sách tên (đếm lại hai lần) — ACTIVE | Ch22 | CANON_FACT | Ch22 §VI |
| RELATION(Chiêu) | vắng; gò thấp phía đông trống (một nhịp); nợ ACTIVE, "không lên trang" | Ch22 | CANON_FACT | Ch22 §I.1; Ch22 §VI |
| STATE | ký bản chép sổ kho Hổ Lao dưới dòng cuối, "chỗ người kiểm": "Trình Dịch, sứ Ích Châu." Không ấn | Ch22 | CANON_FACT | Ch22 §I.23 |
| STATE | đã đọc tên mình trong chiếu có ấn đỏ: hắn "có chữ ký, không có ấn" | Ch22 | CANON_FACT | Ch22 §I.30–31 |
| STATE | sổ người chết thêm tên (đếm lại hai lần); ghi từng tên | Ch22 | CANON_FACT | Ch22 §I.15; Ch22 §IV (Dịch) |
| KNOWLEDGE | Đã nói với Chiêu: kế hoạch, giờ, cọc; nhận ba điều kiện | Ch17 | CANON_FACT | Ch17 §III |
| KNOWLEDGE(Bàng) | Bàng nhận lương theo sổ cũ, cần cỏ, vẫn chờ tờ nhất, không hỏi người kẹt | Ch19 | CANON_FACT | Ch19 §III (Dịch) |
| KNOWLEDGE (đã thấy/nghe/làm) | lịch lương (đêm thứ ba; bốn chuyến; qua bến dưới Hổ Lao); hai sáng trinh sát; thuyền neo giữa sông; dự bị ở bãi bến mặt ra sông; cổng bến mở không ai hô; cột đi bờ phía tây có kỵ che; kho cháy một dãy; chiếu Kim Lăng có ấn nêu tên hắn, "nay triều đình xác nhận" | Ch22 | CANON_FACT | Ch22 §III (Dịch); Ch22 §I.2, I.6–7, I.10–11, I.16, I.18, I.30 |
| KNOWLEDGE(Dĩnh Xuyên) | đánh thành thì họ đốt kho thóc trước khi ta qua cổng; "ta lấy một cái thành không có thóc" (lý do không đánh) (Dịch tin) | Ch19 | CANON_BELIEF | Ch19 §I.2 |
| KNOWLEDGE(Dĩnh Xuyên) | thành mở cho lời hứa, không cho tước vị; tờ văn đã vào nội thành; Chiêu không ký (Dịch tin; Canon liệt vào cột "Biết") ⚠ xem CB-L-21 | Ch19 | CANON_BELIEF | Ch19 §III (Dịch) |
| KNOWLEDGE | Dịch suy (cột INFERENCE, Ch12 §III): Vân Chương không nhìn chỗ Uyển–Tam Lang "như người đã quen" ⟦ô kép → tách 2/3⟧ | Ch12 | CANON_SUSPICION | Ch12 §III (Dịch) |
| KNOWLEDGE(thuyền) | Dịch nghi, không kết luận (Ch22 §III: "INFERENCE (một mức, nghi, không kết luận)"): "thuyền không vào bến — lương còn nguyên"; "một câu hỏi không đáp"; không giận | Ch22 | CANON_SUSPICION | Ch22 §III (Dịch); Ch22 §II-A |
| KNOWLEDGE | không nghe được nội dung tờ thứ nhất của Bàng; "tờ nhất không bị lộ" | Ch19 | CANON_UNKNOWN | Ch19 §I.5; Ch19 §II |
| KNOWLEDGE | OPEN với Dịch / trên trang POV Dịch Ch22 — Dịch không biết: ai ra lệnh neo (Canon đã có ở Ch21 §I.12: Vân Chương giao lời miệng "Tới bến thì neo ngang sông. Một đêm."; Ch22 §III ghi nguồn lệnh neo là lời miệng Ch21 của Vân Chương); vì sao cổng bến mở / ai mở; thư Hổ Lao và điều (2) (Canon đã có ở Ch21 §I.2, §I.14–17); Vân Chương làm gì; Bàng đọc gì; số phận tướng giữ thành; chiếu có từ trước (hắn thấy lần đầu); Chiêu ở đâu | Ch22 | CANON_UNKNOWN | Ch22 §III (Dịch); Ch22 §II-A; Ch22 §III (Phó tướng thủy quân); Ch21 §I.12; Ch21 §I.2, §I.14–17 |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch01 | STATE (nơi ở) | (đầu dải) → hai gian nhà thuê trong ngõ sát tường thành phía bắc, cùng Phùng thúc | CANON_FACT | Ch01 §I.3 |  |
| Ch01 | STATE (mốc) | (đầu dải) → mùa xuân năm -10 về Vân Trung nhận chức thư lại | CANON_FACT | Ch01 §V |  |
| Ch01 | STATE (tuổi) [CANON CHANGE] | (Canon Update không nêu tuổi cũ) → "Tiêu Dịch: 17 tuổi ở Ch1, 27 tuổi ở năm 0" | CANON_FACT | Ch01 §IX |  |
| Ch01 | STATE (phương pháp) | (đầu dải) → dùng quân cờ đen/trắng đối chiếu số xe, không dọn bàn cờ | CANON_FACT | Ch01 §I.15 |  |
| Ch01 | GOAL | (đầu dải) → thu thập thêm số xe thực qua Nam Môn mỗi tối | CANON_FACT | Ch01 §VI |  |
| Ch01 | KNOWLEDGE (biết) | lương hụt tám xe qua bốn chuyến; không chuyến nào có giấy báo hao; số tồn không trừ phần hao; then Bắc Môn mới được thay; có người mặc áo lính hỏi thăm việc hắn đối sổ | CANON_FACT | Ch01 §III (THẨM DỊCH) |  |
| Ch01 | KNOWLEDGE (nghi) | hao hụt có quy luật; có người khiến số liệu tồn kho cao hơn thực tế | CANON_SUSPICION | Ch01 §III |  |
| Ch01 | KNOWLEDGE (không biết) | ai đứng sau/mục đích; hụt lương có liên hệ Bắc Môn không; người hỏi thăm thuộc phe nào; lượng tồn thực; bao lương dây mới có bất thường không | CANON_UNKNOWN | Ch01 §III |  |
| Ch01 | RELATION(Phùng thúc) | (đầu dải) → Phùng thúc lo ngại, đã khuyên "đừng đào sâu" | CANON_FACT | Ch01 §VI |  |
| Ch01 | RELATION(Hoắc Tam Lang) | (đầu dải) → lần đầu chạm mặt | CANON_FACT | Ch01 §I.4 |  |
| Ch01 | RELATION(Chu Hạc / lính gác đêm) | (đầu dải) → hứa "Ngày mai tôi sẽ nói" (xin áo bông) | CANON_FACT | Ch01 §VII |  |
| Ch01 | RELATION(Tiêu Uyển, Tạ Vân Chương) | chưa có tương tác với Dịch | CANON_FACT | Ch01 §III |  |
| Ch03 | STATE | → Hộ phòng giao đối sổ củi, than, cỏ ngựa Hoắc quân cấp cho đoàn, hai ngày một lần, tại kho quân nhu | CANON_FACT | Ch03 §I.29 |  |
| Ch03 | STATE | → mang số quân trắng thừa trong hộp cờ ở nhà đi; đặt luật: ai đến đặt một quân trắng lên mép bàn | CANON_FACT | Ch03 §I.30–31 |  |
| Ch03 | STATE (thói quen) | đưa tay kia đỡ tay áo khi đặt quân → sau khi thấy Vân Chương nhìn, đổi sang đặt một tay | CANON_FACT | Ch03 §I.32 |  |
| Ch03 | STATE | vẫn ra Nam Môn mỗi tối (kết quả không nêu) | CANON_FACT | Ch03 §VI |  |
| Ch03 | RELATION(Chu Hạc / lính gác đêm) | lời hứa chưa trả → đã trả một phần (26/30), đóng | CANON_FACT | Ch03 §VII |  |
| Ch03 | RELATION(A Quy) | → thấy A Quy nắm gậy chặt tới trắng khớp ngón khi Hoắc đi ngang; không hỏi | CANON_FACT | Ch03 §I.33 |  |
| Ch03 | RELATION(Tam Lang) | → Tam Lang gọi "Thẩm Dịch", xưng "ngươi" | CANON_FACT | Ch03 §I.48 |  |
| Ch03 | KNOWLEDGE (biết thêm) | nguyên nhân thiếu áo là lệnh Tri phủ, không phải gian lận; nhu cầu thực 30 bộ; xin từ châu mất hơn một tháng; Hắc Hà đóng băng sớm; A Quy là "người trong phủ phạm lỗi", phân loại áo/đếm giỏi; Tam Lang có băng ở tay; Vân Chương đã thấy thói quen đỡ tay áo; Phùng thúc lo về "người trong kinh" | CANON_FACT | Ch03 §III (THẨM DỊCH) |  |
| Ch03 | KNOWLEDGE (nhận thấy, chưa kết luận) | A Quy có phản ứng tiêu cực mạnh khi Hoắc tướng quân xuất hiện | CANON_SUSPICION | Ch03 §III |  |
| Ch03 | KNOWLEDGE (không biết) | A Quy là Bùi Chỉ/thích khách; nguyên nhân vết thương Tam Lang; chuyện Bùi gia; thân phận nữ của Tam Lang | CANON_UNKNOWN | Ch03 §III |  |
| Ch04 | STATE | → đến dịch quán xin số gạo đoàn đã nhận để lấy nhập trừ xuất; giấy ghi cột "Tịnh Châu"/"Nam Môn" | CANON_FACT | Ch04 §I.16–17 |  |
| Ch04 | STATE (thói quen viết) | → khi chép chữ "Huệ", ngòi bút dừng trước nét cuối một nhịp rồi thêm nét ấy; nét cuối đậm hơn | CANON_FACT | Ch04 §I.19 |  |
| Ch04 | STATE (nền) | → từng được dạy khuyết một nét khi viết chữ "Huệ"; Phùng Bảo sửa thói quen sau khi rời cung; phản xạ cũ đôi lúc bật ra, không cố ý [nhãn gốc "Phùng Bảo"; ⚠ xem CB-L-01] | CANON_FACT | Ch04 §I.9 |  |
| Ch04 | STATE | → không tránh Vân Chương; chủ động mời đánh cờ không theo thứ tự quân; nước đầu đỡ tay áo, các nước sau không (ý nghĩa: không xác định) | CANON_FACT | Ch04 §I.28–29 |  |
| Ch04 | KNOWLEDGE (biết) | Vân Chương chú ý cách viết "Huệ"; cố ý nói ra chuyện thêm nét sau; không chất vấn/gây báo động; vẫn đối xử bình thường (S4) | CANON_FACT | Ch04 §III (THẨM DỊCH) |  |
| Ch04 | KNOWLEDGE (nghi) | Vân Chương đang thử mình; có thể biết nhiều hơn vẻ ngoài; thân phận có thể đã lọt vào tầm quan sát | CANON_SUSPICION | Ch04 §III |  |
| Ch04 | KNOWLEDGE (không biết) | Vân Chương đã ghép hắn với vụ Thẩm chiêu nghi; đã thấy Phùng thúc; có báo về kinh không; mức chắc chắn của Vân Chương | CANON_UNKNOWN | Ch04 §III |  |
| Ch05 | KNOWLEDGE/ACT | được Vân Chương mời ra miếu hai lần, từ chối ("Nhà tôi chỉ có một người…"; "Ông ấy già rồi. Đi đêm không tiện."); ở nhà đêm trừ tịch theo lời Dịch; nội tâm ngoài POV, không ghi | CANON_FACT | Ch05 §I.22, §III (THẨM DỊCH) |  |
| Ch05 | RELATION(Tam Lang) | → Tam Lang thắng Dịch ba mục | CANON_FACT | Ch05 §I.24 |  |
| Ch07 | STATE (chính Tý) | → đốt pháo ở đầu ngõ với Phùng thúc; thấy qua khói hai bóng người nhấc then Bắc Môn đặt xuống đất, không thấy mặt; cửa mở trơn tru; không nghe được gì vì pháo | CANON_FACT | Ch07 §I.1–3 |  |
| Ch07 | STATE | → kéo Phùng thúc vào ngõ; không báo hàng xóm; về nhà lấy bọc vải xám; bỏ lại bàn cờ; quân trắng trong túi áo; ra khỏi ngõ bằng đầu bên kia khi tù và vang lên | CANON_FACT | Ch07 §I.6, §I.8–11 |  |
| Ch07 | STATE | → chỉ chọn ngõ hẹp sau khi thấy kỵ binh đốt theo phố rộng; dìu Phùng thúc, mang bọc; dừng ở khúc ngoặt nhìn hướng phủ tướng quân rồi đi tiếp về nam | CANON_FACT | Ch07 §I.12–15 |  |
| Ch07 | STATE | → qua lối phụ bên hông chợ; thấy Uyển tự bước sang phía Bắc Nhung; ra khỏi Vân Trung trước giờ Ngọ qua Nam Môn; không trình diện điểm danh | CANON_FACT | Ch07 §I.16–25, §I.31–34 |  |
| Ch07 | STATE (thân phận) | "Thẩm thư lại" bình thường → bị xem là mất tích/chết (P-09); không bị thương | CANON_FACT | Ch07 §I (P-09), §IV |  |
| Ch07 | KNOWLEDGE (biết, tận mắt) | Bắc Môn mở từ bên trong vào chính Tý, hai người khiêng then; kỵ binh Bắc Nhung vào thành; Bắc Nhung đòi Vĩnh Ninh công chúa; Uyển tự bước sang, không bị bắt; lệnh bắt sống A Quy của Tam công tử; phủ nha gọi điểm danh; Nam Môn xét thanh niên theo mặt và chân | CANON_FACT | Ch07 §III (THẨM DỊCH) |  |
| Ch07 | KNOWLEDGE (nghe, lời đồn) | (lời đồn) phủ tướng quân bị vây; Hoắc tướng quân đã chết (nơi chết kể khác nhau); A Quy xổng ra / cầm đao / đầy máu / "có dính vào chuyện cửa Bắc"; dãy nhà dọc tường bắc cháy sạch (⚠ xem CB-L-04) | CANON_SUSPICION | Ch07 §III |  |
| Ch07 | KNOWLEDGE (nhận ra) | các lời kể về A Quy không khớp nhau; chưa ai nói mình thấy tận mắt | CANON_FACT | Ch07 §III |  |
| Ch07 | KNOWLEDGE (không biết) | mặt hai người khiêng then; Chu Hạc ở đâu lúc chính Tý; người lính chết dưới vòm; chuyện trong thư phòng; vì sao công chúa quay lại; Vân Chương sống hay chết; Tam Lang là nữ/"A Chiêu" | CANON_UNKNOWN | Ch07 §III |  |
| Ch07 | KNOWLEDGE (không có) | nghi Chu Hạc đích danh; liên hệ cửa mở êm với lệnh bôi dầu Ch1; dữ kiện minh oan cho A Quy | CANON_UNKNOWN | Ch07 §III |  |
| Ch07 | RELATION(Phùng thúc) | (như Ch1) → dìu lão suốt đường; "Hai chiều, ACTIVE" | CANON_FACT | Ch07 §I.13, §VI | ← Ch01 RELATION(Phùng thúc) (Ch03–Ch06: Canon Update không có dòng RELATION Dịch–Phùng thúc) |
| Ch07 | LIMIT | im lặng, không làm chứng "vì làm chứng phải đứng ra bằng tên" | CANON_FACT | Ch07 §VI |  |
| Ch07 | RELATION(Vân Chương) | → không biết Vân Chương sống chết | CANON_UNKNOWN | Ch07 §III, §VI |  |
| Ch08 | STATE | (đầu dải) → làm ở phòng sổ phủ Thứ sử Ích Châu, gọi "Trình tiên sinh", có con dấu gỗ "Chuyển Thứ sử xét" | CANON_FACT | Ch08 §I.1 | ← Ch07 STATE |
| Ch08 | LIMIT | Không có quyền bác giấy, không có quyền giữ người | CANON_FACT | Ch08 §I.1 | (Before chưa trích được) |
| Ch08 | KNOWLEDGE (nghe thuật lại) | (nghe thuật lại) Luồng tin phía tây: "đã tìm được tung tích Thất hoàng tử" (Tô thuật lại, Ch08 §I.11) ⟦ô kép → tách 1/2⟧ | CANON_SUSPICION | Ch08 §III; Ch08 §I.11 | ← Ch07 KNOWLEDGE (nghe, lời đồn) |
| Ch08 | KNOWLEDGE (nghe thuật lại — phần OPEN) | Nguồn, mức độ phía tây biết, thật / giả / thăm dò, người giả danh: OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch08 §III |  |
| Ch08 | KNOWLEDGE | Lạc Kinh thất thủ; hoàng thượng băng; Tạ Vân Chương đưa ấu chủ về Kim Lăng (tin trạm) | CANON_FACT | Ch08 §III (Dịch BIẾT), §I.6 |  |
| Ch08 | KNOWLEDGE | Sứ Hạ Hầu đã tới ải Tây đòi Ích Châu dâng biểu | CANON_FACT | Ch08 §III, §I.9 |  |
| Ch08 | KNOWLEDGE | Lương, cỏ ải Tây đang bị bán qua hướng tây, qua thương lái (từ sổ + câu trả lời viên quản lương) | CANON_FACT | Ch08 §III (Dịch BIẾT), §I.3–4 |  |
| Ch08 | KNOWLEDGE (lời đồn) | (lời đồn) "Hoắc Tam Lang tử trận ở Hắc Hà" — Dịch nghe qua Phùng Bảo, dừng rót nước một nhịp, không hỏi thêm; Canon Update xếp vào "NGHE / THUẬT LẠI (không xác nhận)" và ghi "Lời đồn sai" | CANON_SUSPICION | Ch08 §I.13, §III |  |
| Ch08 | STATE | Nay giữ khóa trường mệnh bạc (Phùng Bảo đặt vào tay, đêm ngày 1) | CANON_FACT | Ch08 §I.16, §IV (Vật chứng) |  |
| Ch08 | KNOWLEDGE | Khóa trường mệnh chỉ chứng được xuất thân, không chứng danh tính (chính Dịch nói "Không có cách nào") ⟦ST gốc: "CANON_FACT (theo mục "BIẾT" của Canon Update)"⟧ | CANON_FACT | Ch08 §I.21, §III |  |
| Ch08 | STATE | Tự xưng: "tại hạ" (khi xin gọi thêm người) → "ta" (từ câu công khai trở đi) | CANON_FACT | Ch08 §I.18 |  |
| Ch08 | STATE | Công khai trong phòng kín: "Ta là con của Thẩm chiêu nghi." Không ai nói "Thất hoàng tử"/"điện hạ" | CANON_FACT | Ch08 §I.19 |  |
| Ch08 | GOAL | Lời tuyên bố: không tranh ngôi, không xưng hiệu; Ích Châu chưa dâng biểu cho ai thì "người ta phải đến mà nói chuyện với Ích Châu" ⟦ST gốc: "CANON_FACT (lời nói trên trang)"⟧ | CANON_FACT | Ch08 §I.24 | (Before chưa trích được) |
| Ch08 | STATE (quyền) | Phòng sổ → được kiểm kê các kho phủ thành, rà sổ, đề xuất điều phối trong mùa này, điều phối kho hành chính; xuất kho lớn phải có ấn Thứ sử | CANON_FACT | Ch08 §I.25 |  |
| Ch08 | LIMIT | Không xin quân quyền; không đụng kho quân các ải ("Không phải việc của ta") | CANON_FACT | Ch08 §I.25, §IV |  |
| Ch08 | STATE | Điều kiện đặt ra: lời hôm ấy giữ trong bốn bức tường tới khi Thứ sử quyết (Ôn: "Được") | CANON_FACT | Ch08 §I.26 |  |
| Ch08 | STATE | Ngày 2 chiều: bốn lính đứng trước nhà "giữ cho yên"; ngày 5: hai lính theo cách mười bước khi ra chợ; ngày 7: lệnh điều phối đầu tiên 2.000 thạch (ký "Trình Dịch", ấn đỏ Thứ sử) | CANON_FACT | Ch08 §I.28, I.30, I.31 |  |
| Ch08 | STATE | Ngày 14, công đường: thân phận đã lộ trước các quan; người đưa tin Tây Lương quỳ "Thất điện hạ" | CANON_FACT | Ch08 §I.32–34, §IV |  |
| Ch08 | KNOWLEDGE | Tin đã lọt ra ngoài phòng kín; các quan ở công đường đã nghe chữ "Thất điện hạ" | CANON_FACT | Ch08 §III |  |
| Ch08 | KNOWLEDGE | CHƯA BIẾT: việc bán lương có phải đường dây trực tiếp của Tây Lương không; ai để lộ tin; nội dung phong thư; Ôn nghiêng người vì cớ gì | CANON_UNKNOWN | Ch08 §III |  |
| Ch08 | KNOWLEDGE | KHÔNG CÓ trong Ch08: nghi mình là ai; tình cảm chú–cháu với ấu chủ; suy nghĩ về Bắc Môn; hồi tưởng về Vân Chương | CANON_UNKNOWN | Ch08 §III (KHÔNG CÓ) |  |
| Ch08 | KNOWLEDGE | Nghe tên Tạ Vân Chương: tay cầm sổ dừng một nhịp | CANON_FACT | Ch08 §I.7 |  |
| Ch08 | RELATION(Phùng Bảo) | Phùng Bảo đứng ra làm chứng, tự đặt mình trở lại trong án cũ → DEBT thật, ACTIVE | CANON_FACT | Ch08 §VI |  |
| Ch08 | RELATION(Thẩm chiêu nghi) | Moral burden / identity burden, không phải debt thông thường; ACTIVE, không nói ra | CANON_FACT | Ch08 §VI |  |
| Ch08 | RELATION(Tam Lang) | Unresolved attachment / concern; lời đồn "kích hoạt món nợ cũ từ Ch7" | CANON_FACT | Ch08 §VI | (Before chưa trích được): "món nợ cũ từ Ch7" không có dòng RELATION(Tam Lang) Ch07 |
| Ch08 | STATE | Dịch 27 tuổi | CANON_FACT | Ch08 §VII |  |
| Ch09 | STATE | Tự xưng "ta" xuyên chương (sửa A-1: ba chỗ đổi từ "tại hạ" sang "ta"); "Ta" không đồng nghĩa với tự xưng Thất điện hạ | CANON_FACT | Ch09 §0 (A-1) |  |
| Ch09 | KNOWLEDGE | Biết nội dung thư Bàng (Dịch mở, đọc to) | CANON_FACT | Ch09 §I.3, §III |  |
| Ch09 | KNOWLEDGE | Biết đường lương ải Tây trong phạm vi sổ phủ thành (nhà Đỗ, hai cặp số, gian kho thứ chín, sổ trọ) | CANON_FACT | Ch09 §I.10–17, §III |  |
| Ch09 | KNOWLEDGE | Hai câu trong thư ("đã nghe tin từ lâu", "người từng hầu trong cung") là mồi — trong văn bản chỉ là điều Dịch và Phùng Bảo đoán | CANON_SUSPICION | Ch09 §II, §III (Dịch ĐOÁN) |  |
| Ch09 | KNOWLEDGE | Dịch từng nghi Tô → tự loại Tô khỏi giả thuyết (suy luận điều tra) ⟦ST gốc: "CANON_SUSPICION → loại"⟧ | CANON_SUSPICION | Ch09 §III (Trạng thái điều tra) |  |
| Ch09 | KNOWLEDGE | Hàn là người nhắn ải Tây (Hàn tự nhận ngày 18), nhắn gì, qua ai, vì sao (lời Hàn) | CANON_FACT | Ch09 §I.19–20, §III |  |
| Ch09 | KNOWLEDGE | Tiểu kết điều tra do Dịch nêu (tin ra biên chỉ đi theo đường hàng; người đi từ phủ về ải là viên quản lương) ⟦ST gốc: "CANON_SUSPICION (được Hàn xác nhận ở §I.19–20)"⟧ | CANON_SUSPICION | Ch09 §I.18 (suy luận); Ch09 §Nguyên tắc ghi |  |
| Ch09 | KNOWLEDGE | KHÔNG BIẾT: nguồn luồng tin cũ; Tiết phản ứng ra sao; kết quả ở ải; liên hệ sứ Hạ Hầu – Bàng | CANON_UNKNOWN | Ch09 §III |  |
| Ch09 | KNOWLEDGE | KHÔNG CÓ trong Ch09: Bắc Môn; Vân Trung; tình cảm chú–cháu | CANON_UNKNOWN | Ch09 §III (Dịch, KHÔNG CÓ) |  |
| Ch09 | KNOWLEDGE | Biết Ôn phê chuẩn; ải giao Hàn; không hồi âm; quyền kiểm kê ba huyện; Hoắc Tam Lang vẫn giữ Hắc Hà | CANON_FACT | Ch09 §III, §I.26, I.30, I.32 |  |
| Ch09 | KNOWLEDGE (Ch08 → Ch09) | Lời đồn "Tam Lang tử trận" → được đính chính: "Hoắc Tam Lang vẫn giữ Hắc Hà" (tin trạm ngày 24) | CANON_FACT | Ch09 §I.32, §V |  |
| Ch09 | LIMIT / STATE | Không quân quyền; không được công nhận; vẫn là "Trình Dịch"; thêm quyền kiểm kê/rà sổ/đề xuất kho ba huyện quanh phủ thành (lệnh có ấn, Dịch giữ) | CANON_FACT | Ch09 §I.30, §IV |  |
| Ch09 | STATE (vật) | Giữ phong thư Bàng (văn bản không ghi trả lại); tờ chép thư; lệnh kiểm kê ba huyện; khóa trường mệnh | CANON_FACT | Ch09 §IV (Vật) |  |
| Ch09 | RELATION(Hàn) | Hàn tự nhận nhắn tin; Hàn nghe Dịch từ chối dùng danh ("Chưa."); Hai chiều ACTIVE, Dịch vẫn phải dè chừng | CANON_FACT | Ch09 §I.28, §VI |  |
| Ch09 | RELATION(Tô) | Dịch không trả lời "là ai, muốn gì"; Dịch đáp Tô: "Người ở ải Tây ăn lương. Không ai ăn được huyết thống." | CANON_FACT | Ch09 §I.24, I.27 |  |
| Ch09 | RELATION(Tam Lang) | Nợ Ch7 "được gỡ một phần", món nợ còn | CANON_FACT | Ch09 §VI |  |
| Ch11 | STATE | Hồ sơ Dạ Kiêu: Trình Dịch, "Trình tiên sinh", mạc liêu lo lương; chừng 27 tuổi; hai gian nhà thuê sau phủ, ở với một lão bộc già; bốn lính phủ Thứ sử trước cửa, thay ca ngày đêm | CANON_FACT | Ch11 §I.9 |  |
| Ch11 | STATE / hành vi | Đêm nhà Dịch: đọc sổ, đèn dầu đặt bên kia bàn cách một sải tay; không gọi lính; liếc xuống chân trái của kẻ đột nhập; cầm đèn lên, nhận "A Quy", nói "Ở đây người ta gọi ta là Trình." | CANON_FACT | Ch11 §I.13–18 |  |
| Ch11 | KNOWLEDGE | Nghe A Quy (Chỉ) nói: "Ta không mở cửa Bắc. Kẻ mở là tên lính trực đêm ấy. Hắn chết ngay dưới vòm." [đã sửa: dòng này là lời A Quy, không phải lời Dịch — Ch11 §III ghi đây là "kết luận mười năm của A Quy"] ⟦ST gốc: "CANON_FACT (lời nói trên trang)"⟧ | CANON_FACT | Ch11 §I.20, §III (Dịch) |  |
| Ch11 | KNOWLEDGE | Câu khóa: "Đêm đó ta thấy người khiêng then cửa Bắc có hai người. Ngươi chỉ có một." — "Ta không thấy mặt." (Dịch dừng ở đúng một dữ kiện) | CANON_FACT | Ch11 §I.21, I.23, §III (Dịch) |  |
| Ch11 | KNOWLEDGE | Biết A Quy còn sống, cầm một đám người làm việc thuê, có người đã trả tiền để giết mình, sẽ có người khác tới ("Ta biết.") | CANON_FACT | Ch11 §III (Dịch), §I.24 |  |
| Ch11 | KNOWLEDGE | UNKNOWN với Dịch: ai thuê; Dạ Kiêu tên gì, lớn tới đâu | CANON_UNKNOWN | Ch11 §III (Dịch) |  |
| Ch11 | KNOWLEDGE | Kết luận mười năm của A Quy: tên lính trực mở cửa một mình ⟦ST gốc: "CANON_FACT (điều Dịch biết qua A Quy nói)"⟧ | CANON_FACT | Ch11 §III (Dịch) |  |
| Ch11 | KNOWLEDGE | Vì sao Dịch không gọi lính: không lên trang | CANON_UNKNOWN | Ch11 §II |  |
| Ch11 | RELATION(Bùi Chỉ) | Món nợ Ch7 (không quay lại) "chạm tới" qua "Ngươi còn sống.", không nói ra; ACTIVE | CANON_FACT | Ch11 §VI |  |
| Ch11 | STATE | Ở Ích Châu; không bị thương; bốn lính vẫn đứng ngoài, không biết có người vào | CANON_FACT | Ch11 §IV |  |
| Ch12 | STATE | Sứ Ích Châu ("Sứ Ích Châu, Trình Dịch"); quyền điều phối lương / tuyến vận / hộ tống / đại diện có điều kiện; không quân riêng, không phong tướng (Ôn đặt cược có điều kiện, cuối tháng Sáu → đầu tháng Bảy năm 0) | CANON_FACT | Ch12 §I.7, §0B (CC-2), §IV |  |
| Ch12 | KNOWLEDGE | Tầng 1: nhận ra ngay Hoắc Tam Lang ở Lạc Thủy, không gọi | CANON_FACT | Ch12 §I.5 |  |
| Ch12 | KNOWLEDGE | Tam Lang là Hoắc Chiêu (chính nàng nói trong gian trong) — Dịch trước đó không biết Tam Lang là nữ (Ch12 §V: payoff "Dịch không biết Tam Lang là nữ") | CANON_FACT | Ch12 §III; Ch12 §V |  |
| Ch12 | KNOWLEDGE | Về Uyển: Vĩnh Ninh công chúa; Khả đôn; thủ lĩnh đợi nàng ngồi, im khi nàng không gật; nói tiếng Hán không thông ngôn | CANON_FACT | Ch12 §III (Dịch/Uyển), §I.9 |  |
| Ch12 | KNOWLEDGE | Dịch suy (cột INFERENCE) về Uyển: có thực quyền, ít nhất một phần Bắc Nhung nghe nàng ("thấy một phần") | CANON_SUSPICION | Ch12 §III (Dịch/Uyển) |  |
| Ch12 | KNOWLEDGE | UNKNOWN về Uyển: số bộ/quân; quan hệ thực với Hách Liên; giữ quyền bằng gì; giữ yên bao lâu; quân cờ trắng; hai nghìn kỵ rút; con của Uyển; tình cảm Uyển–Vân Chương | CANON_UNKNOWN | Ch12 §III |  |
| Ch12 | KNOWLEDGE | UNKNOWN về Chiêu: ai biết Tam Lang là nữ từ bao giờ; căn cứ Uyển biết | CANON_UNKNOWN | Ch12 §III (Dịch/Chiêu), §II |  |
| Ch12 | KNOWLEDGE | Vân Chương: nói thay Kim Lăng; Kim Lăng chưa công nhận ai ⟦ô kép → tách 1/3⟧ | CANON_FACT | Ch12 §III (Dịch/Vân Chương) |  |
| Ch12 | KNOWLEDGE | Dịch suy (cột INFERENCE): Vân Chương không nhìn chỗ Uyển–Tam Lang "như người đã quen" ⟦ô kép → tách 2/3⟧ | CANON_SUSPICION | Ch12 §III (Dịch/Vân Chương) |  |
| Ch12 | KNOWLEDGE | Dịch không biết: Vân Chương đã biết gì về mình và bằng cách nào ⟦ô kép → tách 3/3⟧ | CANON_UNKNOWN | Ch12 §III (Dịch/Vân Chương) |  |
| Ch12 | KNOWLEDGE | A Quy: nói lời Dạ Kiêu; có người dưới quyền theo dõi được ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch12 §III (Dịch/A Quy) |  |
| Ch12 | KNOWLEDGE | Dịch không biết về A Quy: tên thật; lý do thật tới đây; đầu lĩnh hay chỉ người của Dạ Kiêu (Dịch nghe "người của ta") ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch12 §III (Dịch/A Quy) |  |
| Ch12 | KNOWLEDGE | Có người lạ đếm thuyền ở bến dưới ba hôm nay ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch12 §I.14, §III |  |
| Ch12 | KNOWLEDGE | Người lạ đếm thuyền thuộc phe nào: không biết ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch12 §I.14, §III |  |
| Ch12 | KNOWLEDGE | Dịch giữ kín với bốn người kia: A Quy từng được thuê giết mình (Ch11); câu về hai người khiêng then | CANON_FACT | Ch12 §III (cuối mục Dịch) |  |
| Ch12 | STATE | Bảo chứng A Quy trong phạm vi Ích Châu ("Phần Ích Châu, ta chịu"); Hàn không dặn, Ôn chưa biết; thư báo Ôn đã niêm (không tên Chiêu/A Quy; giữ chữ "Hoắc quân") | CANON_FACT | Ch12 §I.16–17, I.31–32, §IV |  |
| Ch12 | KNOWLEDGE | Phát biểu: "Hạ Hầu không cần thắng cả bốn chúng ta. Ông ta chỉ cần mỗi bên đứng một mình." ⟦ST gốc: "CANON_FACT (lời nói trên trang)"⟧ | CANON_FACT | Ch12 §I.11 |  |
| Ch12 | RELATION(Chiêu) | Nàng trao tên thật trước mặt hắn; hắn bỏ đi đêm Vân Trung (Ch7), chưa nói; ACTIVE | CANON_FACT | Ch12 §VI |  |
| Ch12 | RELATION(Ôn / Hàn) | Mới: bảo chứng A Quy bằng danh Ích Châu mà không được dặn; ACTIVE | CANON_FACT | Ch12 §VI |  |
| Ch12 | RELATION(Uyển) | Đứng nhìn nàng tự đi (Ch7); ACTIVE, chưa chạm | CANON_FACT | Ch12 §VI |  |
| Ch12 | RELATION(Vân Chương) | Vân Chương "chưa công nhận Dịch"; việc phụng chiếu gác tới sau mùa đông | CANON_FACT | Ch12 §IV | ← Ch07 RELATION(Vân Chương) |
| Ch13 | STATE | Đưa hai xe lương mẫu lên gò phía bắc; tờ kê gồm gạo, muối, đậu, cỏ khô và dòng vải bông/bông chần (không số liệu, trong định mức Ích Châu); Chiêu ký nhận | CANON_FACT | Ch13 §I.1, I.4–5 |  |
| Ch13 | KNOWLEDGE | "Đêm ấy…" — Dịch không nói tiếp (bị ngắt bởi viên quân nhu) ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch13 §I.7, §II |  |
| Ch13 | KNOWLEDGE | Dịch định nói gì sau "Đêm ấy…": OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch13 §I.7, §II |  |
| Ch13 | KNOWLEDGE | Biết thêm: Chiêu ký tờ kê, không hỏi dòng vải bông; nàng hỏi thư ghi "Hoắc quân" thế nào | CANON_FACT | Ch13 §III (Dịch), §I.6 |  |
| Ch13 | KNOWLEDGE | Không biết: có rò tin bên trong; thư "người tự nhận" của Vân Chương; ngựa của viên quan Kim Lăng | CANON_UNKNOWN | Ch13 §III (Dịch) |  |
| Ch13 | RELATION(Chiêu) | "Đêm ấy…" rồi thôi; ACTIVE, không nói ra. Chiêu → Dịch (nợ vật tư chống rét): Mới, UNPAID | CANON_FACT | Ch13 §VI |  |
| Ch13 | RELATION(Vân Chương) | Vân Chương viết "người tự nhận" dù biết; không báo Dịch — Mới, ACTIVE (nợ của Vân Chương → Dịch) | CANON_FACT | Ch13 §VI |  |
| Ch15 | STATE | Chủ kế hoạch hội minh ở bến Lạc Thủy; quyền điều phối lương (CC-2), quyết "cắt xe" thuộc quyền lương; Hàn chỉ huy quân | CANON_FACT | Ch15 §0; Ch15 §I.3–I.4, §I.17 | ← Ch13 STATE |
| Ch15 | STATE | Qua mùa đông (off-page): Ôn giao Dịch kế hoạch/lương và cho mượn đạo Ích Châu dưới Hàn | CANON_FACT | Ch15 §VII |  |
| Ch15 | GOAL | Hội ba cột ở Hổ Lao cùng một sáng; viết "Hổ Lao" bằng than lên bản đồ giấy | CANON_FACT | Ch15 §I.4, §I.9 | (Before chưa trích được) |
| Ch15 | LIMIT | Bốn thời hạn (Chiêu: lương đủ tới hết đợt băng tan; lời hứa Khả đôn hết khi băng tan; Kim Lăng đợi thấy việc; Hàn: mỗi tuần chờ trong kinh thêm người) | CANON_FACT | Ch15 §I.7 | (Before chưa trích được) |
| Ch15 | LIMIT | "Chờ thêm, ta không còn gì để giữ họ ngồi cùng một bàn." Không ai ký gì | CANON_FACT | Ch15 §I.8 |  |
| Ch15 | KNOWLEDGE | "Kho đầy là quân ở lại trong thành lâu. Dịch nghĩ vậy." → "Họ sẽ ở trong thành." (Canon Update ghi là niềm tin sai) [chú: Dịch] | CANON_BELIEF | Ch15 §I.12 | (Before chưa trích được) |
| Ch15 | STATE | Nghĩ tới hoãn nhưng không hoãn | CANON_FACT | Ch15 §I.13 |  |
| Ch15 | STATE | Quyết định ở bến trên: "Cắt dây. Đẩy xe ngang bến."; "Người trước."; mất khoảng nghìn tám và đoàn xe lương | CANON_FACT | Ch15 §I.17–I.21 |  |
| Ch15 | KNOWLEDGE | Biết: cột lương bị chặn đúng chỗ ép; Hạ Hầu đánh chỗ nối; nghi binh không ai đuổi; Chiêu mất bảy trăm và lui; thuyền Kim Lăng trễ; Bàng nhắc thư; hai đường (đường hắn chọn / chỗ kỵ xuống) trùng nhau; vòng chỉ chạm hai bến | CANON_FACT | Ch15 §III; Ch15 §I.30–I.33 |  |
| Ch15 | KNOWLEDGE | Dịch thấy hai đường trùng nhau nhưng không kết luận gì | CANON_FACT | Ch15 §II (mục 1); Ch15 §I.33 |  |
| Ch15 | KNOWLEDGE(không biết) | Bàng đọc bằng cách nào; có rò tin không; Ch14 (lỗ văn thư; Kha Trọng) | CANON_UNKNOWN | Ch15 §III; Ch15 §II |  |
| Ch15 | KNOWLEDGE | Trước câu "ai biết cột đi hướng nào" / "nhà buôn tin": Dịch không nhận, không bác | CANON_FACT | Ch15 §I.31 |  |
| Ch15 | STATE | Uy tín giảm; sĩ quan Ích Châu liếc hắn khi nghe nhắc thư | CANON_FACT | Ch15 §IV |  |
| Ch15 | RELATION(Chiêu) | Nhận hai xe lương của Hoắc quân ghi sổ lương hội minh: "Ghi bằng tên Ích Châu."; Chiêu không nhìn Dịch; "Đêm ấy…" vẫn chưa nói | CANON_FACT | Ch15 §I.27–I.28; Ch15 §VI | ← Ch13 RELATION(Chiêu) |
| Ch15 | RELATION(Hàn) | Hàn bị thương ở hậu quân — nợ mới | CANON_FACT | Ch15 §VI | ← Ch09 RELATION(Hàn) |
| Ch15 | RELATION(Ích Châu / Ôn / sĩ quan) | Mất cột và đoàn xe; thư Bàng bị nhắc công khai — mới, ACTIVE | CANON_FACT | Ch15 §VI |  |
| Ch15 | STATE | Vật: bản đồ giấy ("Hổ Lao" bị gạch); tờ giấy trắng chưa viết; cây than và sợi chỉ | CANON_FACT | Ch15 §IV; Ch15 §I.34–I.35 |  |
| Ch16 | STATE | Danh xưng: tự xưng "Trình Dịch" với làng trưởng; hồi âm ký "Ích Châu, Trình Dịch"; Canon Update gọi POV là "Tiêu Dịch" (lệch danh xưng — xem cuối file) | CANON_FACT | Ch16 §I.16; Ch16 §I.23; Ch16 §Nguyên tắc ghi |  |
| Ch16 | GOAL | Đổi đường lương: "Có hay không, đường lương cũng phải đổi."; "Ta không hỏi." (nhận phần mình, không nói "bị lộ") | CANON_FACT | Ch16 §I.10; Ch16 §I.3 |  |
| Ch16 | LIMIT | Dịch tính, quyết đánh/không đánh thuộc Hàn ("Không đánh."); Dịch không ra lệnh quân (CC-2) | CANON_FACT | Ch16 §I.9; Ch16 §0 |  |
| Ch16 | LIMIT | "Ta không có người thứ hai trăm mốt để đổi." (từ chối trận kiếm cỏ thắng được, mất ~200) | CANON_FACT | Ch16 §I.9 |  |
| Ch16 | LIMIT | Phiếu ký Dịch + Hàn; "Ấn Thứ sử tới sau. Ba tuần."; "Nếu không tới?" — "Lấy tên ta." | CANON_FACT | Ch16 §I.16 |  |
| Ch16 | LIMIT | Thư Ôn: ấn tới hết vụ thu; muối bốn trăm bao, vải hai trăm tấm; "Quá số ấy, ngươi tự chịu." Nợ muối ~300 bao | CANON_FACT | Ch16 §I.31; Ch16 §I.29; Ch16 §IV |  |
| Ch16 | STATE | Hai trăm bốn mươi người chưa rõ sống chết; chép danh sách tên vào tay áo; Hàn: "Ba ngày. Sau đó thì ghi." | CANON_FACT | Ch16 §I.1, §I.5 |  |
| Ch16 | STATE | Hồi âm Bàng gửi (ngày 14, kỵ cờ trắng đi bắc), chỉ đáp tờ hai (lương); không mở tờ nhất ("Việc kia Thứ sử đã xem" — lời Hàn) | CANON_FACT | Ch16 §I.22–I.23, §I.27; Ch16 §IV |  |
| Ch16 | STATE | Hook: tờ giấy trắng có đường than theo dòng nước tới "Dĩnh Xuyên" | CANON_FACT | Ch16 §I.33 |  |
| Ch16 | KNOWLEDGE | Bàng biết cách xe Ích Châu chở (Hàn xác nhận giao dịch); trận kiếm cỏ thắng được nhưng không đổi thế; Hoắc quân rút nửa, hạn ba tuần; làng bán một phần ba, Hạ Hầu cũng mua một phần ba; mất một đoàn nhỏ, chín đường chạy; Hổ Lao thêm quân; ấn Ôn tối đa 400 bao / 200 tấm; hồi âm đã gửi; vừa vẽ đường lương tới Dĩnh Xuyên | CANON_FACT | Ch16 §III |  |
| Ch16 | KNOWLEDGE(không biết) | Có rò tin hay không; Ch14; Bàng phản ứng hồi âm thế nào; Dĩnh Xuyên sẽ dùng làm gì ("hắn chỉ vẽ hướng; mục đích Ch17") | CANON_UNKNOWN | Ch16 §III |  |
| Ch16 | RELATION(Chiêu) | Xin "Ba tuần"; Chiêu đặt hạn; nợ lương + nuôi kỵ nhẹ — tăng | CANON_FACT | Ch16 §I.11–I.12; Ch16 §VI |  |
| Ch16 | RELATION(Hàn) | Hàn ký kèm phiếu và hồi âm, nhận trách nhiệm — mới | CANON_FACT | Ch16 §VI |  |
| Ch16 | RELATION(Ôn) | "Làm trước, ấn sau"; tối đa 400 bao — mới | CANON_FACT | Ch16 §VI; Ch16 §0 |  |
| Ch16 | RELATION(làng trưởng) | Phiếu nợ mang tên mình — mới | CANON_FACT | Ch16 §VI |  |
| Ch16 | STATE | Uy tín: chưa hồi; thêm trách nhiệm cá nhân (phiếu mang tên mình) | CANON_FACT | Ch16 §IV |  |
| Ch17 | STATE | Trình kế hoạch Dĩnh Xuyên cho Chiêu: cảng cấp lương của Hổ Lao, đê, cổ chai; thuyền chở bộ Ích Châu; "Chắc không?" — "Không."; "Bao lâu?" — "Ta không biết." | CANON_FACT | Ch17 §I.4–I.7 |  |
| Ch17 | STATE | Im ở câu "Ta hỏi vì sao họ sẽ cứu" (chỉ đáp kho cỏ / đường đồi / đê); không đáp khi Chiêu nói "Để họ tới cứu" và khi Chiêu tự quyết làm mồi | CANON_FACT | Ch17 §I.5, §I.8, §I.10 |  |
| Ch17 | RELATION(Chiêu) | Đáp "Được" ba điều kiện của Chiêu; hạn ngày 31 bỏ; Debt: nợ lương + đã kéo nàng làm mồi (nàng bị thương) — ACTIVE, tăng, chưa trên trang | CANON_FACT | Ch17 §I.11; Ch17 §VI; Ch17 §IV |  |
| Ch17 | KNOWLEDGE | Đã nói với Chiêu: kế hoạch, giờ, cọc; nhận ba điều kiện | CANON_FACT | Ch17 §III |  |
| Ch17 | KNOWLEDGE(không biết) | Dịch ở đâu trong trận; Dịch nghĩ gì khi kéo Chiêu làm mồi | CANON_UNKNOWN | Ch17 §II; Ch17 §III ("trang không ghi") |  |
| Ch19 | STATE | (đầu dải) vị trí: gốc liễu cụt → miệng tây → gò thấp → lều Hàn → cổ chai → trước cổng Dĩnh Xuyên; không bước vào thành | CANON_FACT | Ch19 §I.1–22 | ← Ch17 STATE |
| Ch19 | STATE | thân phận/quyền: ký văn an dân "Trình Dịch, sứ Ích Châu", không ấn; "Ấn tới sau." | CANON_FACT | Ch19 §I.13 |  |
| Ch19 | STATE | hồi âm Bàng ký "Trình Dịch", không ấn, đúng sổ cũ: "Một nghìn suất. Ba trăm ngựa. Như cũ. Giao tại ải." | CANON_FACT | Ch19 §I.8 |  |
| Ch19 | GOAL | gửi một nghìn suất cho Bàng: "Để hắn có một con số." | CANON_FACT | Ch19 §I.7 | (Before chưa trích được) |
| Ch19 | LIMIT | với Bàng: "Không. Cũng không bớt." (không bán thêm một bao) | CANON_FACT | Ch19 §I.8 | (Before chưa trích được) |
| Ch19 | LIMIT | muối: "Số này quá bốn trăm. Phần quá, ta tự chịu." → ghi tên mình ở góc một tờ ngoài sổ Ích Châu (món nợ muối vượt trần Ôn) | CANON_FACT | Ch19 §I.9 | ← Ch16 LIMIT (thư Ôn: "Quá số ấy, ngươi tự chịu.") |
| Ch19 | LIMIT | với Chiêu: "Hạn của tướng quân là ngày bốn mươi hai. Ta không xin thêm." | CANON_FACT | Ch19 §I.4 |  |
| Ch19 | STATE | "đã ký điều không rút được"; lời hứa văn bản trong tay dân Dĩnh Xuyên (C1); vượt quyền ân xá (làm trước, không ấn) | CANON_FACT | Ch19 §III (Dịch); Ch19 §IV (Dịch); Ch19 §VI |  |
| Ch19 | RELATION(Chiêu) | Dịch ghi tên "Tiểu Thất"; hỏi "Ngươi có cách khác?" — "Có. Chưa chắc."; "Không xin lỗi, không tha thứ." | CANON_FACT | Ch19 §I.4 | ← Ch17 RELATION(Chiêu) |
| Ch19 | RELATION(Chiêu) | nàng đọc trên vai, "Ta không ký."; Dịch: "Ta không xin tướng quân ký."; "Ta biết." | CANON_FACT | Ch19 §I.12 |  |
| Ch19 | RELATION(Chiêu) | nợ: Tiểu Thất (tên ghi); nàng không ký — ACTIVE, "không gọi tên" | CANON_FACT | Ch19 §VI |  |
| Ch19 | RELATION(Hàn) | Dịch hỏi, không ra lệnh ("Bộ của Đô úy… vào thành ngày đầu thì sao?"); Hàn quyết bộ/hàng binh: "Ta quyết." | CANON_FACT | Ch19 §I.10; Ch19 §0 (Canon Sync, CC-2) | ← Ch16 RELATION(Hàn) |
| Ch19 | RELATION(Hàn) | Hàn: "Hết ngày bốn mươi mốt, ta kéo bộ về Lạc Thủy." — "Ta nói để ngươi biết." Dịch không cản | CANON_FACT | Ch19 §I.16 |  |
| Ch19 | RELATION(Hàn) | Hàn không ký kèm hồi âm Bàng | CANON_FACT | Ch19 §I.8 |  |
| Ch19 | RELATION(Ôn) | muối vượt trần Ôn (tự chịu) — nợ mới, ACTIVE | CANON_FACT | Ch19 §VI | ← Ch16 RELATION(Ôn) |
| Ch19 | RELATION(Kim Lăng/Vân Chương) | vượt quyền ân xá — nợ mới, ACTIVE | CANON_FACT | Ch19 §VI |  |
| Ch19 | RELATION(người mở cửa Dĩnh Xuyên) | lời hứa C1 (văn bản trong tay họ) — nợ mới, ACTIVE | CANON_FACT | Ch19 §VI |  |
| Ch19 | KNOWLEDGE(Bàng) | Bàng nhận lương theo sổ cũ, cần cỏ, vẫn chờ tờ nhất, không hỏi người kẹt | CANON_FACT | Ch19 §III (Dịch) | ← Ch16 KNOWLEDGE (Bàng biết cách xe Ích Châu chở) |
| Ch19 | KNOWLEDGE(Bàng) | nhận thức mới: "Đo bằng xe. Ta tưởng hắn không chịu viết ra." (Bàng tự viết sổ mình chậm hơn lương Ích Châu) (Dịch tin) ⚠ xem CB-L-21 | CANON_BELIEF | Ch19 §I.7; Ch19 §III (Dịch) |  |
| Ch19 | KNOWLEDGE(Dĩnh Xuyên) | đánh thành thì họ đốt kho thóc trước khi ta qua cổng; "ta lấy một cái thành không có thóc" (lý do không đánh) (Dịch tin) | CANON_BELIEF | Ch19 §I.2 |  |
| Ch19 | KNOWLEDGE(Dĩnh Xuyên) | thành mở cho lời hứa, không cho tước vị; tờ văn đã vào nội thành; Chiêu không ký (Dịch tin; Canon liệt vào cột "Biết") ⚠ xem CB-L-21 | CANON_BELIEF | Ch19 §III (Dịch) |  |
| Ch19 | KNOWLEDGE | không biết: Hạ Hầu phản ứng ra sao; Kim Lăng/Vân Chương nhận lời hứa không; trong thành thỏa thuận thế nào; Ch18 | CANON_UNKNOWN | Ch19 §III (Dịch) |  |
| Ch19 | KNOWLEDGE | không nghe được nội dung tờ thứ nhất của Bàng; "tờ nhất không bị lộ" | CANON_UNKNOWN | Ch19 §I.5; Ch19 §II |  |
| Ch20 | STATE | "vẫn là sứ Ích Châu"; chưa biết chiếu; không nhận một dòng từ Vân Chương (trạng thái "chưa biết chiếu" đóng ở Ch22 §I.30–31) | CANON_FACT | Ch20 §IV (Dịch) |  |
| Ch20 | KNOWLEDGE | chưa biết chiếu nêu tên mình ("Dịch chưa biết") — đóng ở Ch22 §I.30–31 (xem dòng Ch22 STATE và KNOWLEDGE) | CANON_UNKNOWN | Ch20 §II; Ch20 §III (Vân Chương) |  |
| Ch20 | RELATION(Kim Lăng/Vân Chương) | vượt quyền ân xá: Before ACTIVE (Dịch nợ) → After "Kim Lăng đã ôm hậu quả (Dịch chưa biết)" | CANON_FACT | Ch20 §VI |  |
| Ch20 | RELATION(người mở cửa) | lời hứa C1: "nay có ngai đứng tên" | CANON_FACT | Ch20 §VI |  |
| Ch21 | STATE | không nhận một dòng từ Vân Chương (D20-11) | CANON_FACT | Ch21 §IV (Lịch lương); Ch21 §VI |  |
| Ch22 | STATE | vị trí: bãi thóc ngoài Dĩnh Xuyên → lều Hàn/đê → chân đê/góc thành Hổ Lao (cổng bến) → bãi bến → thành chính → cổng đê | CANON_FACT | Ch22 §I.1, I.9, I.15, I.18, I.28 |  |
| Ch22 | STATE | ký bản chép sổ kho Hổ Lao dưới dòng cuối, "chỗ người kiểm": "Trình Dịch, sứ Ích Châu." Không ấn | CANON_FACT | Ch22 §I.23 |  |
| Ch22 | STATE | đã đọc tên mình trong chiếu có ấn đỏ: hắn "có chữ ký, không có ấn" | CANON_FACT | Ch22 §I.30–31 | ← Ch20 STATE ("chưa biết chiếu") |
| Ch22 | STATE | sổ người chết thêm tên (đếm lại hai lần); ghi từng tên | CANON_FACT | Ch22 §I.15; Ch22 §IV (Dịch) |  |
| Ch22 | GOAL | quyết định tại cổng bến: "Đi dọc chân tường. Vào cổng bến. Giữ cổng. Chỉ giữ cổng." (lý do duy nhất nhìn thấy: "Họ nhìn ra sông.") | CANON_FACT | Ch22 §I.12 |  |
| Ch22 | GOAL | sáng: "Vào thành. Giữ kho." (chia bộ "Hai"); "Không." với việc đuổi cột bại quân | CANON_FACT | Ch22 §I.17 |  |
| Ch22 | LIMIT | cố ý: "Ai ăn số này?"/"Ngoài lương?" không hỏi lần ba; "Thuyền sao không vào bến?" không hỏi thêm | CANON_FACT | Ch22 §I.3, I.24 |  |
| Ch22 | LIMIT | không đáp "Ai hợp lệ?" (không ai đáp) và không đáp "Ngài là người họ Tiêu?" — "Hắn trả bút." | CANON_FACT | Ch22 §I.25, I.27 |  |
| Ch22 | LIMIT | không đáp sĩ quan Ích Châu về việc để cột đi / cho cầm xô | CANON_FACT | Ch22 §I.17, I.19 |  |
| Ch22 | RELATION(Hàn) | Hàn: "Ích Châu đã mất một nghìn tám. Ta không đem thêm một người…" — Dịch: "Vậy ông đừng đem." → Hàn: "Ta đem. Ta chọn." (Hàn tự chọn, không bị Dịch bắt) | CANON_FACT | Ch22 §I.8 |  |
| Ch22 | RELATION(Hàn) | nợ mới của Dịch với Hàn/bộ Ích Châu: cho họ đứng một đêm trên đê không che — ACTIVE | CANON_FACT | Ch22 §VI |  |
| Ch22 | RELATION(sĩ quan Ích Châu) | "Chúng giết bộ ta ở cổng đêm qua. Ngươi để chúng đi." / "Ngươi cho chúng cầm xô." — Dịch không đáp; nợ mới ACTIVE | CANON_FACT | Ch22 §I.17, I.19; Ch22 §VI |  |
| Ch22 | RELATION(phó tướng thủy quân) | hỏi "Ai ăn số này?", "Ngoài lương?" → "Báo ghi lương." / "Lịch ghi lương."; "Thuyền chưa dỡ. Lương còn nguyên." | CANON_FACT | Ch22 §I.3, I.24 |  |
| Ch22 | RELATION(hàng binh Hổ Lao) | lời hứa C1 thành của triều đình; không rút được — nợ mới, ACTIVE | CANON_FACT | Ch22 §VI |  |
| Ch22 | RELATION(Kim Lăng) | (thuyền; sổ kho) "Một nghi vấn không đáp" — mới, ACTIVE | CANON_FACT | Ch22 §VI |  |
| Ch22 | RELATION(Danh) | (sứ Ích Châu, không "Tiêu"; tên trong chữ người khác) không đáp "họ Tiêu?"; chiếu có ấn — mới, ACTIVE | CANON_FACT | Ch22 §VI |  |
| Ch22 | RELATION(người chết / lạc) | danh sách tên (đếm lại hai lần) — ACTIVE | CANON_FACT | Ch22 §VI |  |
| Ch22 | RELATION(Ôn) | muối vượt trần — ACTIVE (không đổi) | CANON_FACT | Ch22 §VI | ← Ch19 RELATION(Ôn) |
| Ch22 | RELATION(Chiêu) | vắng; gò thấp phía đông trống (một nhịp); nợ ACTIVE, "không lên trang" | CANON_FACT | Ch22 §I.1; Ch22 §VI |  |
| Ch22 | KNOWLEDGE(thuyền) | Dịch nghi, không kết luận (Ch22 §III: "INFERENCE (một mức, nghi, không kết luận)"): "thuyền không vào bến — lương còn nguyên"; "một câu hỏi không đáp"; không giận | CANON_SUSPICION | Ch22 §III (Dịch); Ch22 §II-A |  |
| Ch22 | KNOWLEDGE (đã thấy/nghe/làm) | lịch lương (đêm thứ ba; bốn chuyến; qua bến dưới Hổ Lao); hai sáng trinh sát; thuyền neo giữa sông; dự bị ở bãi bến mặt ra sông; cổng bến mở không ai hô; cột đi bờ phía tây có kỵ che; kho cháy một dãy; chiếu Kim Lăng có ấn nêu tên hắn, "nay triều đình xác nhận" | CANON_FACT | Ch22 §III (Dịch); Ch22 §I.2, I.6–7, I.10–11, I.16, I.18, I.30 | ← Ch20 KNOWLEDGE (chưa biết chiếu nêu tên mình) |
| Ch22 | KNOWLEDGE | OPEN với Dịch / trên trang POV Dịch Ch22 — Dịch không biết: ai ra lệnh neo (Canon đã có ở Ch21 §I.12: Vân Chương giao lời miệng "Tới bến thì neo ngang sông. Một đêm."; Ch22 §III ghi nguồn lệnh neo là lời miệng Ch21 của Vân Chương); vì sao cổng bến mở / ai mở; thư Hổ Lao và điều (2) (Canon đã có ở Ch21 §I.2, §I.14–17); Vân Chương làm gì; Bàng đọc gì; số phận tướng giữ thành; chiếu có từ trước (hắn thấy lần đầu); Chiêu ở đâu | CANON_UNKNOWN | Ch22 §III (Dịch); Ch22 §II-A; Ch22 §III (Phó tướng thủy quân); Ch21 §I.12; Ch21 §I.2, §I.14–17 |  |

**(c) PLANNING_NON_CANON**

| Ch | Trường | Nội dung (kế hoạch / author-truth; KHÔNG phải canon trang) | Source Type | Source |
|---|---|---|---|---|
| Ch11 | KNOWLEDGE | Dịch biết có người dò hỏi mình: author-truth, không lên trang Ch11 | PLANNING_NON_CANON | Ch11 §III (ghi chú dưới bảng Dịch) |
| Ch13 | KNOWLEDGE | Nhận lời báo Dạ Kiêu qua vòng gác: author-truth, không lên trang | PLANNING_NON_CANON | Ch13 §III (Dịch) |
| Ch16 | GOAL | (author-truth, không lên trang) "Thế = điều kiện khiến kế người kia không còn đường nào để tính" | PLANNING_NON_CANON | Ch16 §Nguyên tắc ghi |
| Ch21 | KNOWLEDGE | ràng buộc cho Ch22: Dịch không biết thư Hổ Lao, điều (2), lệnh lương; chỉ nhận lịch lương | PLANNING_NON_CANON | Ch21 §IX (Trước Gate Ch22) |
| Ch22 | KNOWLEDGE | ràng buộc L2/GR22-H1: Dịch chỉ biết lịch lương (ngày · lượng · đường); mọi chiến thuật là Dịch tự đọc; không cho Dịch biết ngược về thư Hổ Lao/điều (2)/"neo ngang sông" trừ khi có nguồn trên trang | PLANNING_NON_CANON | Ch22 §II-B (L2/GR22-H1) |
| Ch22 | RELATION | chỉ dấu chương trong Emotional Debt Ch22: nợ Kim Lăng (thuyền) "→ Ch23"; nợ Ôn (muối) "→ Ch24" | PLANNING_NON_CANON | Ch22 §VI |

### 3.2 BÙI CHỈ (A Quy) <a id="nv-chi"></a>

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE | (đầu dải) → first (đột nhập phủ tướng quân đêm 3) | Ch02 | CANON_FACT | Ch02 §I.1 |
| APPEARANCE | POV Bùi Chỉ cả chương (đầu dải: không xuất hiện ở Ch08–Ch10; Ch08–Ch10 Canon Update không nêu) | Ch11 | CANON_FACT | Ch11 §Nguyên tắc ghi |
| APPEARANCE | Có mặt, không POV: đứng ngoài vòng gác Ích Châu, không binh khí, không che mặt, xin gặp bằng hai chữ "A Quy" | Ch12 | CANON_FACT | Ch12 §I.13 |
| APPEARANCE | POV đoạn IV (quá trưa, bãi lau ngoài vòng gác Ích Châu); có mặt ở đoạn II (đất trống) | Ch13 | CANON_FACT | Ch13 §Nguyên tắc ghi, §I.II, §I.IV |
| APPEARANCE | first trong dải; POV toàn chương | Ch14 | CANON_FACT | Ch14 §Nguyên tắc ghi |
| APPEARANCE | vắng (không xuất hiện) (ghi chú Canon Update Ch18: không liệt kê riêng Chỉ; liệt kê "Dịch, Chiêu, Vân Chương, Hạ Hầu, Bàng, Hàn" không xuất hiện) | Ch15–Ch18 | CANON_FACT | Ch15 §III; Ch16 §III; Ch17 §III; Ch18 §III |
| APPEARANCE | "Chỉ" không xuất hiện | Ch20 | CANON_FACT | Ch20 §III |
| GOAL | Tìm nguồn rò bằng cách phát năm tin giả (năm điểm hẹn) rồi xem tin nào quay lại: "Ta không hỏi ai nói. Ta đợi xem cái gì quay lại." | Ch14 | CANON_FACT | Ch14 §I.2, §I.4 |
| GOAL | Đọc sổ Nam Môn "để tìm những người đã ở trong thành đêm trừ tịch" | Ch14 | CANON_FACT | Ch14 §I.8 |
| LIMIT | Ba nguyên tắc Dạ Kiêu: 1 (nhận tiền, không hỏi lý do) KHÔNG PHÁ; 2 (mục tiêu không bao giờ thấy mặt) PHÁ — "hắn đưa tay kéo khăn che mặt xuống"; 3 (nhận việc thì làm) PHÁ — không giết, trả đủ hai mươi nén. [CANON CHANGE, Ch11 §0C: Dạ Kiêu "không phá cả ba nguyên tắc", chỉ "phá 2/3"; nguyên tắc "không hỏi lý do" vẫn được Chỉ tuân thủ] | Ch11 | CANON_FACT | Ch11 §0C, §IV |
| LIMIT | Lệnh về Kha Trọng: "Tìm lão ấy. Không bắt. Không lại gần." | Ch14 | CANON_FACT | Ch14 §I.28 |
| LIMIT | Người theo chân bị nhìn mặt → "Đổi người."; hắn sẽ không tới vùng ấy nữa | Ch14 | CANON_FACT | Ch14 §I.22 |
| RELATION(Hoắc Thành Lĩnh) | không đổi: vẫn thù Hoắc ("Món nợ bị hiểu sai") | Ch03 | CANON_FACT | Ch03 §VII |
| RELATION(Dạ Kiêu) | Phá 2/3 nguyên tắc với đơn này; một mình quyết; người của hắn làm theo mà không biết lý do; Mới, ACTIVE | Ch11 | CANON_FACT | Ch11 §VI |
| RELATION(Hoắc quân / biên bắc) | Mười năm mang tiếng nội ứng; hận → nghi; ACTIVE | Ch11 | CANON_FACT | Ch11 §VI, §I.20 |
| RELATION(Dịch) | Được cho vào bằng cửa trước, dưới bảo chứng Ích Châu; Mới, UNPAID | Ch12 | CANON_FACT | Ch12 §VI |
| RELATION(Chiêu) | A Quy mở miệng như định nói thêm, rồi không nói; mắt dừng ở vết sẹo; nợ A Quy → Chiêu "Điều định nói, không nói"; ACTIVE | Ch13 | CANON_FACT | Ch13 §I.11–12, §VI |
| RELATION(bốn bên) | Báo cho không, cùng một lời; Mới, ACTIVE | Ch13 | CANON_FACT | Ch13 §VI |
| RELATION(Vân Chương) | Debt: Chỉ nhờ chàng mở hai tuyến; chàng nhận không hỏi — "Mới, không gọi tên" | Ch14 | CANON_FACT | Ch14 §VI |
| RELATION(Hoắc quân) | Hoắc quân chờ lời đáp; Chỉ: "Chưa." (không giải thích); giữ im vì chưa thể nói chuyện rò — ACTIVE, mới | Ch14 | CANON_FACT | Ch14 §I.21, §VI |
| STATE | Hai tờ giấy cạnh nhau (bản chép sổ Nam Môn; mảnh chép sổ thuê ngựa Thạch Kiều); "Hắn không đóng sổ lại." | Ch14 | CANON_FACT | Ch14 §I.24, §I.29; Ch14 §IV (Vật) |
| STATE | Ra lệnh theo dõi hai người lạ: "Không. Theo." ("Bắt một người, được một cái tên. Để họ đi, được cả đường họ đi.") | Ch14 | CANON_FACT | Ch14 §I.16 |
| STATE | Chỉ chỉ đo; không K2/Kha Trọng/nguồn rò (G-1, G-2 OPEN không đụng) | Ch21 | CANON_FACT | Ch21 §0 (Sync Ch14) |
| KNOWLEDGE | Chỉ nghe lời đồn (ba tầng miệng) về "lão Kha"; Chỉ không đáp khi người giữ sổ / người ở trạm bàn về họ Tạ | Ch14 | CANON_FACT | Ch14 §I.26–I.27 |
| KNOWLEDGE (lời đồn) | (lời đồn) "lão Kha" mua tin, từng làm quản sự trong "một phủ lớn họ Tạ ở Lạc Kinh" — chưa xác nhận (Ch14 §V, §II); Canon chưa nối với Kha Trọng hay với Tạ gia của Vân Chương (⚠ xem CB-L-31) | Ch14 | CANON_SUSPICION | Ch14 §I.26; Ch14 §II |
| KNOWLEDGE | Vân Chương nhận hai chỗ hẹn (lời nhắn: "Kim Lăng đã nhận hai chỗ hẹn. Lần sau, báo một chỗ.") | Ch14 | CANON_FACT | Ch14 §I.20, §III |
| KNOWLEDGE | Chỉ đáp "Có thể." trước câu của người giữ sổ "Có thể chỉ là trùng tên" (Canon Update không ghi Chỉ tin hay nghi; chỉ ghi lời đáp) | Ch14 | CANON_FACT | Ch14 §I.25 |
| KNOWLEDGE | Chỉ (cột INFERENCE / NIỀM TIN, Ch11 §III): "Kết luận cũ 'một người' không còn đứng vững; mười năm hắn đếm thiếu" ⟦ô kép → tách 2/2⟧ | Ch11 | CANON_BELIEF | Ch11 §I.22, §III |
| KNOWLEDGE | Chu Hạc: không đổi; "Không nghi" (cột INFERENCE/NIỀM TIN) | Ch11 | CANON_BELIEF | Ch11 §III (Chu Hạc) |
| KNOWLEDGE | Chỉ nghi tiền đơn hàng có thể từ phía tây (cột NGHI, "không đổi") ⟦ô kép → tách 2/2⟧ | Ch11 | CANON_SUSPICION | Ch11 §III (Đơn hàng), §I.5 |
| RELATION(chính hắn) | Emotional Debt Ch14 §VI chép nguyên (Người · Đối tượng · Loại · Trạng thái): "Chỉ" · "Chính hắn (nghi rò tin)" · "Hai dòng 'Kha Trọng'" · "ACTIVE". Canon Update không nói "Chính hắn" là ai; nguồn rò (G-1) và Kha Trọng (G-2) là hai thread OPEN riêng, chưa được nối (Ch14 §II; Ch15 §0) | Ch14 | CANON_SUSPICION | Ch14 §VI; Ch14 §II; Ch15 §0 |
| KNOWLEDGE | Người lạ đếm thuyền là người của ai: "Không biết." ⟦ô kép → tách 2/2⟧ | Ch12 | CANON_UNKNOWN | Ch12 §I.14, §III |
| KNOWLEDGE | Không biết: ai rò | Ch13 | CANON_UNKNOWN | Ch13 §III (Chỉ) |
| KNOWLEDGE(không biết) | Ai rò; Kha Trọng (sổ cũ) có phải người bảo lãnh; Kha Trọng còn sống không; có liên quan Bắc Môn / Chu Hạc / Tạ gia không; hai người lạ là ai | Ch14 | CANON_UNKNOWN | Ch14 §III; Ch14 §II |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch01 | STATE (tuổi) [CANON CHANGE] | (Canon Update không nêu tuổi cũ) → 8 tuổi năm -20 (thoát khỏi phủ Bùi); 18 tuổi ở Ch2; 28 tuổi ở năm 0 | CANON_FACT | Ch01 §IX |  |
| Ch02 | GOAL | (đầu dải) → giết Hoắc Thành Lĩnh vì ông đã dẫn quân vây phủ Bùi | CANON_FACT | Ch02 §I.7 |  |
| Ch02 | STATE | → trinh sát phủ khoảng mười ngày (kết thúc trước ngày Tam Lang về); ở phòng trọ sau chợ Bắc; biết tin Tam công tử về qua chủ quán trọ; tự quyết không trinh sát lại, chọn đêm tuyết dày | CANON_FACT | Ch02 §I.4–5 |  |
| Ch02 | KNOWLEDGE (đã biết khi trinh sát) | giờ đổi gác, lối mái, cây hòe sát tường, khe cửa sổ phòng ngủ chính (thử dao từ đêm thứ bảy), giờ tắt đèn phòng ngủ | CANON_FACT | Ch02 §I.6 |  |
| Ch02 | LIMIT/STATE (thương tích) | → cổ chân trái bong gân nặng, tổn thương dây chằng, không gãy xương (cành hòe gãy khi vượt tường; nặng thêm khi bị giật dây) | CANON_FACT | Ch02 §I.8 |  |
| Ch02 | STATE | → bị bắt, trói ở phòng củi sau doanh, hai lính canh, không giao phủ nha, không ghi sổ; dao bị tịch thu, dây móc rơi ở hẻm; bó chân theo "lệnh tướng quân"; được đưa cháo kê nấu gừng, không ăn | CANON_FACT | Ch02 §I.9–11 |  |
| Ch02 | KNOWLEDGE (ký ức) | nhìn hàng đao qua khe cửa "cho tới khi có người kéo hắn ra"; thoát qua cửa sau không khóa | CANON_FACT | Ch02 §I.12 |  |
| Ch02 | KNOWLEDGE (biết) | Hoắc biết chi tiết bí mật về đường thoát (cửa sau); Hoắc có lý do chưa rõ để giữ hắn sống; Hoắc không phủ nhận vây phủ Bùi; "Ta ở đó"; người cầm thương là Tam công tử, con Hoắc, đã bị hắn làm bị thương; Chu tướng quân là võ quan Hoắc gia quân | CANON_FACT | Ch02 §III (BÙI CHỈ) |  |
| Ch02 | KNOWLEDGE (tin) | một người (hắn tin là gia nhân) đã kéo hắn ra và để cửa sau mở; chỉ mình hắn và "người gia nhân năm ấy" biết về cánh cửa | CANON_BELIEF | Ch02 §I.12, §III |  |
| Ch02 | KNOWLEDGE (tin) | Hoắc là kẻ thù, chưa đổi, bắt đầu lung lay | CANON_BELIEF | Ch02 §III |  |
| Ch02 | KNOWLEDGE (nghi) | Hoắc biết nhiều hơn về đêm ấy | CANON_SUSPICION | Ch02 §III |  |
| Ch02 | KNOWLEDGE (không biết) | Hoắc đã nhận ra chính xác hắn là Bùi Chỉ; nhận ra bằng vết bớt; Hoắc là người mở cửa sau; Hoắc từng xin tha cho Bùi gia; vì sao Hoắc thức ở thư phòng | CANON_UNKNOWN | Ch02 §III |  |
| Ch02 | RELATION(Hoắc Thành Lĩnh) | hận → "xuất hiện nghi vấn"; mục tiêu "Chưa đổi: giết Hoắc" | CANON_FACT | Ch02 §VI |  |
| Ch03 | STATE (tên) | không khai tên → được gọi "A Quy" (Hoắc đặt, qua lời Tam Lang: "Cha ta bảo, không nói thì gọi là A Quy"); ý nghĩa chữ "Quy" không giải thích | CANON_FACT | Ch03 §I.4 |  |
| Ch03 | KNOWLEDGE (tin) | tin tên mình do cha đặt; trong nội tâm vẫn gọi mình là Bùi Chỉ | CANON_BELIEF | Ch03 §I.5 |  |
| Ch03 | STATE (giám sát) | bị trói → không còn bị trói; ban ngày lao dịch ở kho quân nhu dưới người lính trẻ; năm cây kim (đếm khi phát/thu); gậy ngắn gỗ mềm; khám người mỗi tối; ngủ phòng củi cửa khóa | CANON_FACT | Ch03 §I.6–7 |  |
| Ch03 | LIMIT (cổ chân) | → đi quá khoảng mười bước không gậy là đau; chống gậy suốt chương | CANON_FACT | Ch03 §I.8 |  |
| Ch03 | KNOWLEDGE (quan sát) | ghi nhận Hoắc đi ngang sân tập cùng một giờ mỗi chiều; từ ô cửa thấy sân tập, lối sang hậu doanh, giờ đổi phiên lính | CANON_FACT | Ch03 §I.9–10 |  |
| Ch03 | STATE | phân loại được 8 áo từ đống áo thải; không uống bát canh gừng đầu tiên, về sau bát cạn nhưng không ai thấy hắn uống; chiều 18 tự nhặt quân trắng Uyển đặt (người lính trẻ khám thấy rồi trả lại); không nghe tin Hắc Hà | CANON_FACT | Ch03 §I.11–14 |  |
| Ch03 | KNOWLEDGE (biết thêm) | tên A Quy do Hoắc đặt; giờ Hoắc đi ngang hậu doanh; "Thẩm thư lại" kiểm trước tin sau; Dịch đi xin áo cho người khác; công chúa hòa thân; "Tạ đại nhân" khoác áo lông đánh cờ | CANON_FACT | Ch03 §III (BÙI CHỈ / A QUY) |  |
| Ch03 | KNOWLEDGE (không biết) | Dịch là hoàng tử; Tam Lang là nữ; Hoắc đã làm gì đêm Bùi gia; vì sao Hoắc giữ hắn; tin Hắc Hà. Không phản ứng với họ "Tạ" | CANON_UNKNOWN | Ch03 §III |  |
| Ch03 | RELATION(Hoắc Thành Lĩnh) | không đổi: vẫn thù Hoắc ("Món nợ bị hiểu sai") | CANON_FACT | Ch03 §VII |  |
| Ch04 | STATE | → ngày 24 vẫn chống gậy, đứng ngồi gọn hơn; về sau bỏ gậy, bước còn hơi lệch; vẫn lao dịch có giám sát (⚠ xem CB-L-05) | CANON_FACT | Ch04 §I.27, §I.32, §VI |  |
| Ch05 | STATE | → không được mời ra miếu; phủ tướng quân (hậu doanh) "Đã hồi phục chân" (⚠ xem CB-L-05) | CANON_FACT | Ch05 §I.23, §V |  |
| Ch06 | STATE | → bước ra thư phòng cầm đao quân dụng, máu từ cổ tay tới khuỷu, trên ngực áo, trên má; gạt đòn thương, bị cán thương quất trúng mạng sườn; chạy lên mái nhà kho, chân khuỵu một nhịp chỗ tiếp đất, biến vào khói | CANON_FACT | Ch06 §I.14–16 |  |
| Ch06 | STATE | → vị trí không rõ; bị truy bắt (lệnh "bắt sống"); "chân khinh công hạn chế" (⚠ xem CB-L-05) | CANON_FACT | Ch06 §IV, §I.47 |  |
| Ch06 | KNOWLEDGE (người khác về A Quy) | Chu Hạc/lính: A Quy ra khỏi chỗ giam đêm nay, đúng lúc Bắc Nhung vào, chạy ra từ thư phòng đầy máu; Chiêu tin A Quy có thể là nội ứng | CANON_BELIEF | Ch06 §I.26–27, §II, §III |  |
| Ch07 | STATE | (lời đồn) các lời kể về A Quy (xổng ra, cầm đao, đầy máu, "dính vào chuyện cửa Bắc") không khớp nhau; không phải fact | CANON_SUSPICION | Ch07 §II, §III |  |
| Ch07 | STATE | → lệnh bắt sống A Quy của Tam công tử ban ra | CANON_FACT | Ch07 §III; Ch07 §IV |  |
| Ch07 | STATE | Không rõ vị trí; bị truy bắt | CANON_UNKNOWN | Ch07 §IV |  |
| Ch11 | STATE | 28 tuổi; đầu lĩnh Dạ Kiêu; cổ chân trái nhức khi mưa lâu; đi mái, che mặt bằng khăn đen khi vào nhà Dịch | CANON_FACT | Ch11 §IV, §I.11–12 | ← Ch07 STATE |
| Ch11 | STATE | Dạ Kiêu: "Nhận tiền, không hỏi lý do. Chín năm nay vẫn thế." | CANON_FACT | Ch11 §I.7 |  |
| Ch11 | LIMIT | Ba nguyên tắc Dạ Kiêu: 1 (nhận tiền, không hỏi lý do) KHÔNG PHÁ; 2 (mục tiêu không bao giờ thấy mặt) PHÁ — "hắn đưa tay kéo khăn che mặt xuống"; 3 (nhận việc thì làm) PHÁ — không giết, trả đủ hai mươi nén. [CANON CHANGE, Ch11 §0C: Dạ Kiêu "không phá cả ba nguyên tắc", chỉ "phá 2/3"; nguyên tắc "không hỏi lý do" vẫn được Chỉ tuân thủ] | CANON_FACT | Ch11 §0C, §IV | (Before chưa trích được) |
| Ch11 | GOAL | Nhận đơn: mục tiêu "Người ở Ích Châu tự nhận là con của Thẩm chiêu nghi", hạn hai tháng; sau khi trả tiền, hạn không còn ràng buộc | CANON_FACT | Ch11 §I.6, §II | (Before chưa trích được) |
| Ch11 | GOAL | Sau khi trả đơn: lệnh điều tra "những ai đã có mặt ở Bắc Môn Vân Trung đêm trừ tịch mười năm trước; thanh then nặng bao nhiêu, mấy người mới khiêng nổi"; sổ trực gác Hoắc quân chỉ là một hướng ("Tìm cả sổ. Và mọi thứ khác…") | CANON_FACT | Ch11 §I.28–29, §V |  |
| Ch11 | STATE | Tự đi Ích Châu (người của hắn nhìn nhau, không hỏi); không giết; trả đủ hai mươi nén: "Dạ Kiêu không nhận đơn này."; đang điều tra Bắc Môn | CANON_FACT | Ch11 §I.11, I.26, §IV |  |
| Ch11 | KNOWLEDGE | Trình Dịch = Thẩm thư lại ở Vân Trung (tận mắt); gọi đúng "A Quy"; ở hai gian nhà có bốn lính | CANON_FACT | Ch11 §III (Bùi Chỉ — Trình Dịch) | (Before chưa trích được) |
| Ch11 | KNOWLEDGE | Trình Dịch có thật là con của Thẩm chiêu nghi không; Bùi gia – Thẩm chiêu nghi có liên hệ không: không biết | CANON_UNKNOWN | Ch11 §III, §II |  |
| Ch11 | KNOWLEDGE | Bắc Môn (FACT): cửa mở từ bên trong; lính trực chết dưới vòm; Trình Dịch nói hai người khiêng then, không thấy mặt | CANON_FACT | Ch11 §III (Bắc Môn), §I.20–23 |  |
| Ch11 | KNOWLEDGE | "Mười năm nay, Bùi Chỉ chỉ đếm tới một." (câu trên trang) ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch11 §I.22, §III |  |
| Ch11 | KNOWLEDGE | Chỉ (cột INFERENCE / NIỀM TIN, Ch11 §III): "Kết luận cũ 'một người' không còn đứng vững; mười năm hắn đếm thiếu" ⟦ô kép → tách 2/2⟧ | CANON_BELIEF | Ch11 §I.22, §III |  |
| Ch11 | KNOWLEDGE | Không biết: người thứ hai; then nặng bao nhiêu; mấy người khiêng nổi | CANON_UNKNOWN | Ch11 §III (Bắc Môn) |  |
| Ch11 | KNOWLEDGE | Đêm ấy trong nhà Dịch: không có tiếng gọi lính ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch11 §III, §II |  |
| Ch11 | KNOWLEDGE | Vì sao Dịch không gọi lính: không biết, "không diễn giải" ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch11 §III, §II |  |
| Ch11 | KNOWLEDGE | Đơn hàng: trung gian; hai mươi nén; khuôn vảy cá; hạn hai tháng; đã trả lại ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch11 §III (Đơn hàng), §I.5 |  |
| Ch11 | KNOWLEDGE | Chỉ nghi tiền đơn hàng có thể từ phía tây (cột NGHI, "không đổi") ⟦ô kép → tách 2/2⟧ | CANON_SUSPICION | Ch11 §III (Đơn hàng), §I.5 |  |
| Ch11 | KNOWLEDGE | Không biết người ra lệnh cuối; phản ứng của người thuê. ⟦ô kép tách thủ công 1/2; ST gốc: "CANON_UNKNOWN; K1 = PLANNING_NON_CANON"⟧ | CANON_UNKNOWN | Ch11 §III, §II |  |
| Ch11 | KNOWLEDGE | Chu Hạc: không đổi; "Không nghi" (cột INFERENCE/NIỀM TIN) | CANON_BELIEF | Ch11 §III (Chu Hạc) |  |
| Ch11 | KNOWLEDGE | Chỉ biết Tam Lang là nữ hay không: OPEN | CANON_UNKNOWN | Ch11 §II |  |
| Ch11 | STATE (Dạ Kiêu) | Vận hành như cũ; ba nguyên tắc vẫn hiệu lực; đơn bị gạch khỏi sổ; quan hệ với trung gian này "sứt" (trung gian đi không chào); hai người đi tìm dấu Bắc Môn theo nhiều hướng | CANON_FACT | Ch11 §IV, §I.26 |  |
| Ch11 | RELATION(Dịch) | Dịch nói một điều thật về Bắc Môn; đêm ấy không có tiếng gọi lính. Chỉ "ghi nhận", chưa gọi tên; Mới, UNPAID. "Ngươi còn sống." (không phải câu hỏi) — Chỉ không trả lời | CANON_FACT | Ch11 §VI, §I.24 |  |
| Ch11 | RELATION(Dạ Kiêu) | Phá 2/3 nguyên tắc với đơn này; một mình quyết; người của hắn làm theo mà không biết lý do; Mới, ACTIVE | CANON_FACT | Ch11 §VI |  |
| Ch11 | RELATION(Hoắc quân / biên bắc) | Mười năm mang tiếng nội ứng; hận → nghi; ACTIVE | CANON_FACT | Ch11 §VI, §I.20 |  |
| Ch12 | STATE | Đổi tin lấy chỗ trong gian trong; Ích Châu bảo chứng tới hết cuộc gặp, người giữ vòng gác khám A Quy; Kim Lăng nhận, Khả đôn nhận, Hoắc quân không nhận không từ chối; ngồi lưng quay vào tường | CANON_FACT | Ch12 §I.15, I.17, I.20 |  |
| Ch12 | STATE | Cuối Ch12: trong phạm vi bảo chứng Ích Châu; đã lộ danh nghĩa Dạ Kiêu trước bốn bên; hứa một kênh tin có giới hạn: "Dạ Kiêu báo tin nguy. Dạ Kiêu không làm tai mắt cho ai." | CANON_FACT | Ch12 §IV, §I.24 |  |
| Ch12 | KNOWLEDGE | Người lạ đếm thuyền ở bến dưới ba hôm nay; hỏi người của ai — "Không biết."; người của hắn chưa theo được tới chỗ người ấy về ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch12 §I.14, §III |  |
| Ch12 | KNOWLEDGE | Người lạ đếm thuyền là người của ai (phe): không biết ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch12 §I.14, §III |  |
| Ch12 | KNOWLEDGE | Tam Lang là nữ: không biết (Ch11 §II OPEN) → nay biết: Tam Lang là Hoắc Chiêu; thấy Dịch bảo chứng cho mình | CANON_FACT | Ch12 §III (A Quy (Chỉ)), §I.29 |  |
| Ch12 | RELATION(Dịch) | Được cho vào bằng cửa trước, dưới bảo chứng Ích Châu; Mới, UNPAID | CANON_FACT | Ch12 §VI |  |
| Ch12 | RELATION(Chiêu) | Kẻ bị truy mười năm ngồi cùng bàn; lời hoãn; ACTIVE (Canon Update ghi món nợ này ở dòng Chiêu, đối tượng A Quy) | CANON_FACT | Ch12 §VI |  |
| Ch13 | KNOWLEDGE | Ba mắt xích: kẻ đếm thuyền rời bến tảng sáng → quán nước ở làng bên → người bán củi vào Lạc Kinh (cửa có quân Hạ Hầu giữ, không bị khám; hôm nay vào sớm hơn). "Qua ba mắt xích, đầu dây nằm ở phía Hạ Hầu." ⟦ST gốc: "CANON_FACT (ghi "FACT, qua ba mắt xích")"⟧ | CANON_FACT | Ch13 §I.20, §III (Chỉ) |  |
| Ch13 | KNOWLEDGE | Tin giả ở bến chứa "không văn thư" → câu "Đêm nay không ai viết gì" chỉ nói trong gian trong → có người để câu lọt ra ngoài; kẻ đếm thuyền đứng ngoài bốn vòng gác, không nghe được trong. Canon: Rò tin bên trong "Có; chỉ Chỉ biết" | CANON_FACT | Ch13 §I.21–23, §III (Chỉ), §IV |  |
| Ch13 | KNOWLEDGE | Không biết: ai rò | CANON_UNKNOWN | Ch13 §III (Chỉ) |  |
| Ch13 | STATE | Quyết định báo cả bốn bên, cùng lúc, cùng một lời, không lấy giá ("tin ở bến dưới là giả; người tung là kẻ đếm thuyền; kẻ ấy về chỗ người của Hạ Hầu"); kênh cảnh báo dùng lần đầu | CANON_FACT | Ch13 §I.25, §IV |  |
| Ch13 | STATE | KHÔNG báo việc câu thật lọt ra ngoài: "Chuyện ấy không báo." — lý do: chưa có một cái tên; nói ra, bốn bên sẽ nhìn người của nhau khác đi | CANON_FACT | Ch13 §I.26 |  |
| Ch13 | STATE | Dạ Kiêu: có người theo dấu ở Lạc Thủy; biết một đường dây tới Lạc Kinh | CANON_FACT | Ch13 §IV |  |
| Ch13 | KNOWLEDGE | Ký ức: đêm qua ngồi sát tường; bốn người kia không ai bảo hắn ngồi chỗ khác | CANON_FACT | Ch13 §I.24 |  |
| Ch13 | RELATION(Chiêu) | A Quy mở miệng như định nói thêm, rồi không nói; mắt dừng ở vết sẹo; nợ A Quy → Chiêu "Điều định nói, không nói"; ACTIVE | CANON_FACT | Ch13 §I.11–12, §VI |  |
| Ch13 | RELATION(bốn bên) | Báo cho không, cùng một lời; Mới, ACTIVE | CANON_FACT | Ch13 §VI |  |
| Ch14 | STATE | Người giữ sổ gọi Chỉ là "đương gia" ("Kênh này mới dựng ba hôm, đương gia." — "Ta biết.") | CANON_FACT | Ch14 §I.4 | ← Ch13 STATE |
| Ch14 | GOAL | Tìm nguồn rò bằng cách phát năm tin giả (năm điểm hẹn) rồi xem tin nào quay lại: "Ta không hỏi ai nói. Ta đợi xem cái gì quay lại." | CANON_FACT | Ch14 §I.2, §I.4 | ← Ch11 GOAL |
| Ch14 | STATE | Chỉ giữ im chuyện rò; câu "không văn thư" đã ra khỏi gian trong, hắn không biết nó qua tay ai | CANON_FACT | Ch14 §0 (Canon Sync Ch13); Ch14 §I.1 |  |
| Ch14 | STATE | Dùng kênh cảnh báo Dạ Kiêu lần hai (thử nghiệm năm điểm hẹn, cơ chế cách ly) | CANON_FACT | Ch14 §IV |  |
| Ch14 | STATE | Có bản chép sổ cửa Nam Môn Vân Trung (mua của một thư lại phủ nha từ cuối hè); sau 28 tháng Chạp cột ngày ra gần như trống | CANON_FACT | Ch14 §I.7 |  |
| Ch14 | GOAL | Đọc sổ Nam Môn "để tìm những người đã ở trong thành đêm trừ tịch" | CANON_FACT | Ch14 §I.8 |  |
| Ch14 | KNOWLEDGE(phép thử) | Với bốn bên hỏi mình về tin giả, Chỉ đáp "Không."; với "Cả Hoắc quân?" lật hai trang không đọc rồi đáp "Cả Hoắc quân." (không giải thích, thể hiện bằng hành động) | CANON_FACT | Ch14 §I.9–I.10 | ← Ch13 KNOWLEDGE |
| Ch14 | RELATION(Vân Chương) | Gọi chàng "Tạ đại nhân"; tự nói với Vân Chương tin T4 ở bờ lau; Vân Chương không hỏi vì sao | CANON_FACT | Ch14 §I.2, §I.6 |  |
| Ch14 | RELATION(Vân Chương) | Debt: Chỉ nhờ chàng mở hai tuyến; chàng nhận không hỏi — "Mới, không gọi tên" | CANON_FACT | Ch14 §VI |  |
| Ch14 | RELATION(Hoắc quân) | Hoắc quân chờ lời đáp; Chỉ: "Chưa." (không giải thích); giữ im vì chưa thể nói chuyện rò — ACTIVE, mới | CANON_FACT | Ch14 §I.21, §VI |  |
| Ch14 | KNOWLEDGE | Năm tin đã phát; T1–T4 không ai tới (ngày 13–16 báo "Không ai"); T5 có người tới (hai người lạ ở miếu đêm 11) | CANON_FACT | Ch14 §III; Ch14 §I.14, §I.19 |  |
| Ch14 | KNOWLEDGE | Hai người lạ thuê ngựa ở trạm Thạch Kiều, "Người bảo lãnh: Kha Trọng"; sổ Nam Môn cũ có "Kha Trọng, người Lạc Kinh, buôn giấy" | CANON_FACT | Ch14 §III; Ch14 §I.23–I.24 |  |
| Ch14 | KNOWLEDGE | Chỉ nghe lời đồn (ba tầng miệng) về "lão Kha"; Chỉ không đáp khi người giữ sổ / người ở trạm bàn về họ Tạ | CANON_FACT | Ch14 §I.26–I.27 |  |
| Ch14 | KNOWLEDGE (lời đồn) | (lời đồn) "lão Kha" mua tin, từng làm quản sự trong "một phủ lớn họ Tạ ở Lạc Kinh" — chưa xác nhận (Ch14 §V, §II); Canon chưa nối với Kha Trọng hay với Tạ gia của Vân Chương (⚠ xem CB-L-31) | CANON_SUSPICION | Ch14 §I.26; Ch14 §II |  |
| Ch14 | KNOWLEDGE | Vân Chương nhận hai chỗ hẹn (lời nhắn: "Kim Lăng đã nhận hai chỗ hẹn. Lần sau, báo một chỗ.") | CANON_FACT | Ch14 §I.20, §III |  |
| Ch14 | RELATION(chính hắn) | Emotional Debt Ch14 §VI chép nguyên (Người · Đối tượng · Loại · Trạng thái): "Chỉ" · "Chính hắn (nghi rò tin)" · "Hai dòng 'Kha Trọng'" · "ACTIVE". Canon Update không nói "Chính hắn" là ai; nguồn rò (G-1) và Kha Trọng (G-2) là hai thread OPEN riêng, chưa được nối (Ch14 §II; Ch15 §0) | CANON_SUSPICION | Ch14 §VI; Ch14 §II; Ch15 §0 |  |
| Ch14 | KNOWLEDGE | Chỉ đáp "Có thể." trước câu của người giữ sổ "Có thể chỉ là trùng tên" (Canon Update không ghi Chỉ tin hay nghi; chỉ ghi lời đáp) | CANON_FACT | Ch14 §I.25 |  |
| Ch14 | KNOWLEDGE(không biết) | Ai rò; Kha Trọng (sổ cũ) có phải người bảo lãnh; Kha Trọng còn sống không; có liên quan Bắc Môn / Chu Hạc / Tạ gia không; hai người lạ là ai | CANON_UNKNOWN | Ch14 §III; Ch14 §II |  |
| Ch14 | LIMIT | Lệnh về Kha Trọng: "Tìm lão ấy. Không bắt. Không lại gần." | CANON_FACT | Ch14 §I.28 | (Before chưa trích được) |
| Ch14 | LIMIT | Người theo chân bị nhìn mặt → "Đổi người."; hắn sẽ không tới vùng ấy nữa | CANON_FACT | Ch14 §I.22 |  |
| Ch14 | STATE | Hai tờ giấy cạnh nhau (bản chép sổ Nam Môn; mảnh chép sổ thuê ngựa Thạch Kiều); "Hắn không đóng sổ lại." | CANON_FACT | Ch14 §I.24, §I.29; Ch14 §IV (Vật) |  |
| Ch14 | STATE | Ra lệnh theo dõi hai người lạ: "Không. Theo." ("Bắt một người, được một cái tên. Để họ đi, được cả đường họ đi.") | CANON_FACT | Ch14 §I.16 |  |
| Ch21 | STATE | Chỉ chỉ đo; không K2/Kha Trọng/nguồn rò (G-1, G-2 OPEN không đụng) | CANON_FACT | Ch21 §0 (Sync Ch14) | ← Ch14 STATE |

**(c) PLANNING_NON_CANON**

| Ch | Trường | Nội dung (kế hoạch / author-truth; KHÔNG phải canon trang) | Source Type | Source |
|---|---|---|---|---|
| Ch11 | KNOWLEDGE | K1: phía Hạ Hầu — author-truth, không phải điều nhân vật biết ⟦ô kép tách thủ công 2/2⟧ | PLANNING_NON_CANON | Ch11 §III, §II |
| Ch12 | KNOWLEDGE | Lý do thật A Quy tới (đường tới Hoắc quân vì Bắc Môn): author-truth, không lên trang | PLANNING_NON_CANON | Ch12 §II |
| Ch13 | KNOWLEDGE | Nhận lời báo Dạ Kiêu (Dịch/Chiêu/Uyển phía nhận): author-truth, không lên trang | PLANNING_NON_CANON | Ch13 §III |
| Ch11 | GOAL | ràng buộc chương sau: hạn hai tháng của đơn không dùng làm đồng hồ đếm ngược cho Ch12+ trừ khi có Gate | PLANNING_NON_CANON | Ch11 §II |

**(d) DÒNG NHÃN "Người đi bến (Chỉ)" (Ch21) — giữ tách khỏi lịch sử trực tiếp của Chỉ** (người đi bến gọi Chỉ là "đương gia", Ch21 §I.10; xem CB-L-30)

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch21 | APPEARANCE | người đi bến: áo ngắn người khiêng hàng, tay dính dầu, vào cửa sau; báo "Ba ngày."; "Đương gia dặn thêm… Gửi năm lời… xem lời nào quay lại." | CANON_FACT | Ch21 §I.9–10 |  |
| Ch21 | KNOWLEDGE | (nghe thuật lại qua người đi bến — "[P] suy", off-page) Vân Chương chọn một lời, không năm ⟦ô kép → tách 1/2⟧ | CANON_SUSPICION | Ch21 §III (Người đi bến (Chỉ)) |  |
| Ch21 | KNOWLEDGE | Vân Chương dùng số để làm gì: không biết ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch21 §III (Người đi bến (Chỉ)) |  |

### 3.3 UYỂN (Tiêu Uyển; Vĩnh Ninh công chúa) <a id="nv-uyen"></a>

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE/STATE | (đầu dải) → first; Vĩnh Ninh công chúa, con Hoài Nam vương, "khoảng 17–18 tuổi"; trong thành cùng đoàn, nơi ở chưa xác định | Ch01 | CANON_FACT | Ch01 §I.11, §VI |
| APPEARANCE | Không có mặt; xuất hiện qua sứ giả "người của trướng Khả đôn" và lời Khả đôn (Canon Update Ch10 gộp "Uyển / Khả đôn" ở §III) [nhãn gốc "Khả đôn"; ⚠ xem CB-L-25] | Ch10 | CANON_FACT | Ch10 §I.25–28, §III |
| APPEARANCE | Có mặt, không POV: nhìn Dịch lâu; áo lông cáo, tóc tết lối thảo nguyên | Ch12 | CANON_FACT | Ch12 §I.8 |
| APPEARANCE | POV đoạn III (gần trưa, thuyền Kim Lăng) | Ch13 | CANON_FACT | Ch13 §Nguyên tắc ghi, §I.III |
| APPEARANCE | vắng ("Dịch, Chiêu, Uyển: Không xuất hiện") | Ch14 | CANON_FACT | Ch14 §III |
| APPEARANCE | vắng | Ch15 | CANON_FACT | Ch15 §III |
| APPEARANCE | vắng | Ch16 | CANON_FACT | Ch16 §III |
| APPEARANCE | vắng; Gate Ch17: không Uyển/Bắc Nhung hành động ở Ch17 | Ch17 | CANON_FACT | Ch17 §III; Ch17 §IX |
| APPEARANCE | first trong dải; POV toàn chương (narration "Uyển"/"nàng") | Ch18 | CANON_FACT | Ch18 §Nguyên tắc ghi |
| APPEARANCE | không xuất hiện | Ch19 | CANON_FACT | Ch19 §III |
| APPEARANCE | chỉ qua thư một dòng (giấy Hán, không ký tên): "Một bộ trái lời. Đã xử. Trướng giữ." + gói vỏ quýt không chữ (tới chiều nay, chậm hơn thư nhiều ngày) | Ch20 | CANON_FACT | Ch20 §I.4, I.19 |
| APPEARANCE | không xuất hiện | Ch22 | CANON_FACT | Ch22 §III |
| GOAL | Xuống thuyền Kim Lăng "vì việc": đường tin mùa đông nếu có bộ nào trái lời; đường: trướng → Hắc Hà → Vân Trung → Kim Lăng | Ch13 | CANON_FACT | Ch13 §I.15 |
| GOAL | Luật mùa cỏ, bốn điều: ngựa chiến/thịt khô chỉ đi qua chợ biên có sổ, thuế một phần mười; không cướp chợ biên, không giết thương nhân dưới cờ chợ; không vượt sông; bộ theo luật được đồng cỏ gần sông và nước giếng. Lý do nói ra: "Ngựa gầy. Giá rớt thì bộ nào cũng thiệt. Chợ còn thì còn chỗ bán." | Ch18 | CANON_FACT | Ch18 §I.6 |
| LIMIT | Khi xử: không nêu bạc, không nêu Hạ Hầu; tay trong tay áo nơi có nén bạc, không lấy ra; trên trang nàng không nói "Hạ Hầu" | Ch18 | CANON_FACT | Ch18 §I.18; Ch18 §II |
| LIMIT | Xử vì cờ chợ (luật 2), không vì bán ngựa; đường tuân luật là thật (đàn bộ nhỏ đăng sổ đi qua giếng) | Ch18 | CANON_FACT | Ch18 §0 (GR18-3); Ch18 §I.10 |
| LIMIT | "Không hỏi lần hai" khi thủ lĩnh bộ nhỏ hỏi "đưa đi đâu?" mà không ai đáp | Ch18 | CANON_FACT | Ch18 §I.7 |
| RELATION(A Quy) | → đếm người trong phòng, bảo mang thêm canh cho người lính trẻ và A Quy; mỗi chiều đặt một quân trắng ở góc bàn gần chỗ A Quy, tối mang về cùng quân của mình | Ch03 | CANON_FACT | Ch03 §I.42–43 |
| RELATION(Chiêu) | Rót nước cho Tam Lang trước; hỏi con ngựa hồng năm ấy; ngồi sát bên, không giữ khoảng cách khách sáo | Ch12 | CANON_FACT | Ch12 §I.26–27 |
| RELATION(Dịch) | Dịch đứng nhìn nàng tự đi (Ch7); ACTIVE, chưa chạm (nợ Dịch → Uyển) | Ch12 | CANON_FACT | Ch12 §VI |
| RELATION(Tu Bặc Cốt) | Không hỏi chuyện mũ ("Ta không hỏi ngươi chuyện mũ. Ta hỏi ngươi chuyện người chết."), không xác nhận, không phủ nhận lời hắn → gật cho thủ lĩnh râu rậm đọc luật; "Luật nói chết" → Tu Bặc Cốt chết | Ch18 | CANON_FACT | Ch18 §I.17–I.18; Ch18 §I.20 |
| RELATION(bộ nhỏ) | Oán thật do luật của nàng (nửa giá); thủ lĩnh bộ nhỏ ngồi xuống "không cúi đầu" rồi dẫn người đi, không ở lại ăn lửa — mới, ACTIVE | Ch18 | CANON_FACT | Ch18 §I.19, §I.21; Ch18 §VI |
| RELATION(Hách Liên Chước) | "Cớ trao tay" — mới, ACTIVE; người của Hách Liên nhìn nàng một lần rồi đi | Ch18 | CANON_FACT | Ch18 §VI; Ch18 §I.9, §I.21 |
| RELATION(người chết) | Hai mạng vì luật (thương nhân Hán; Tu Bặc Cốt) — mới | Ch18 | CANON_FACT | Ch18 §VI |
| RELATION(ông già sứ) | Ông ngồi ngoài vòng lửa, không ăn; nàng rót nước, đặt chén ở mép lửa, không ép — mới, không giải | Ch18 | CANON_FACT | Ch18 §I.22; Ch18 §VI |
| RELATION(Vân Chương) | Gói vỏ quýt đi sau thư; câu chàng không hỏi — ACTIVE, không gọi tên; trên trang không tên Vân Chương | Ch18 | CANON_FACT | Ch18 §VI; Ch18 §I.24; Ch18 §0 |
| STATE | Cuối Ch18: giữ được hội; mất bộ Tu Bặc Cốt, một nửa bộ nhỏ (nửa giá), người của Hách Liên, kỵ độc lập; còn trướng quân + kỵ các bộ theo nàng; nén bạc trong tay áo | Ch18 | CANON_FACT | Ch18 §IV |
| STATE | Gửi thư một dòng ("Một bộ trái lời. Đã xử. Trướng giữ.") qua bốn chặng tin về Kim Lăng; gói vỏ quýt "Đi sau." | Ch18 | CANON_FACT | Ch18 §I.23–I.24; Ch18 §IV |
| STATE | Uyển chưa biết Kim Lăng nhận thư | Ch20–Ch21 | CANON_FACT | Ch20 §IV (Uyển); Ch21 §IV (Uyển) |
| KNOWLEDGE | Biết: ngựa đi tây qua Tu Bặc Cốt; bạc dấu kho Hán; người mua giọng miền tây (đã thả); Tu Bặc Cốt giết thương nhân dưới cờ chợ; đàn giữ ở giếng; mình đã xử hắn; thư ngắn + gói đã đi; Hách Liên Chước tập hợp quân | Ch18 | CANON_FACT | Ch18 §III |
| KNOWLEDGE | (nghe thuật lại) người già bộ nhỏ (người đã đặt nén bạc) rạng sáng báo: Hách Liên cho thổi tù và dọc bờ bắc; các bộ thân với Tu Bặc Cốt kéo về doanh hắn; nàng không hỏi bao nhiêu người (Canon Update ghi Hách Liên "Đang tập hợp quân (tin; chưa hành động)") | Ch18 | CANON_SUSPICION | Ch18 §I.26; Ch18 §IV |
| KNOWLEDGE | Uyển nói "Đi sau." với thị nữ (Ch18); Vân Chương không nghe | Ch20 | CANON_FACT | Ch20 §0 (Sync Ch18) |
| KNOWLEDGE | cảm nhận "Thẩm thư lại không giống thư lại" ⟦ô kép → tách 1/2⟧ | Ch04 | CANON_BELIEF | Ch04 §I.24–25, §III (TIÊU UYỂN) |
| KNOWLEDGE | cảm nhận Vân Chương có chuyện ⟦ô kép → tách 2/3⟧ | Ch05 | CANON_BELIEF | Ch05 §III (TIÊU UYỂN) |
| KNOWLEDGE(không biết) | Hách Liên có sai Tu Bặc Cốt không; mục tiêu Hách Liên; Hạ Hầu đáp ra sao; Ch17, Ch19 | Ch18 | CANON_UNKNOWN | Ch18 §III; Ch18 §II |
| KNOWLEDGE(không biết) | Số ngựa/quân/bộ; số phận nén bạc; Kim Lăng/Vân Chương phản ứng với thư + gói; người mua là ai/của ai (trên trang không nêu phe) | Ch18 | CANON_UNKNOWN | Ch18 §II |
| KNOWLEDGE | Uyển nghĩ gì khi nhận lại; câu Vân Chương không hỏi Uyển | Ch20–Ch21 | CANON_UNKNOWN | Ch20 §II; Ch21 §III (Vân Chương) |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch01 | RELATION(Dịch) | chưa có tương tác | CANON_FACT | Ch01 §III |  |
| Ch03 | STATE | → ở dịch quán Vân Trung; tự xin học cưỡi ngựa ở sân tập phủ tướng quân, Tam Lang dạy | CANON_FACT | Ch03 §I.27, §I.40 |  |
| Ch03 | GOAL/LIMIT | → hỏi "Người của đoàn còn đủ áo không?" trước khi trả áo; nói "Vốn cũng không phải của ta để ban." | CANON_FACT | Ch03 §I.41 |  |
| Ch03 | RELATION(A Quy) | → đếm người trong phòng, bảo mang thêm canh cho người lính trẻ và A Quy; mỗi chiều đặt một quân trắng ở góc bàn gần chỗ A Quy, tối mang về cùng quân của mình | CANON_FACT | Ch03 §I.42–43 |  |
| Ch03 | KNOWLEDGE (biết thêm) | lính gác thiếu áo vì áo đã giữ cho đoàn của nàng; A Quy là người bị phạt | CANON_FACT | Ch03 §III (TIÊU UYỂN) |  |
| Ch03 | KNOWLEDGE (không biết) | A Quy là thích khách; chuyện Bùi gia; thân phận Dịch và Tam Lang | CANON_UNKNOWN | Ch03 §III |  |
| Ch04 | KNOWLEDGE | cảm nhận "Thẩm thư lại không giống thư lại" ⟦ô kép → tách 1/2⟧ | CANON_BELIEF | Ch04 §I.24–25, §III (TIÊU UYỂN) |  |
| Ch04 | KNOWLEDGE | thấy tro giấy trong chậu than của Vân Chương, gạt xuống dưới than mới, không hỏi (không biết đó là gì) ⟦ô kép → tách 2/2⟧ | CANON_FACT | Ch04 §I.24–25, §III (TIÊU UYỂN) |  |
| Ch04 | STATE | → cưỡi được một vòng sân tập; thị nữ mang thuốc sắc cho Vân Chương | CANON_FACT | Ch04 §I.32–33 |  |
| Ch05 | STATE | → tự cưỡi con ngựa hồng mượn từ sân tập hậu doanh; thắp hương, vọng bái ba lần về phía nam; nói "Mấy hôm nay Tạ đại nhân ho không phải vì lạnh." | CANON_FACT | Ch05 §I.26–27 |  |
| Ch05 | KNOWLEDGE | biết Vân Chương quay vào thành với lý do "quên đồ" và để lệnh "không được vào" ⟦ô kép → tách 1/3⟧ | CANON_FACT | Ch05 §III (TIÊU UYỂN) |  |
| Ch05 | KNOWLEDGE | cảm nhận chàng có chuyện ⟦ô kép → tách 2/3⟧ | CANON_BELIEF | Ch05 §III (TIÊU UYỂN) |  |
| Ch05 | KNOWLEDGE | không biết nội dung thư / Bắc Môn ⟦ô kép → tách 3/3⟧ | CANON_UNKNOWN | Ch05 §III (TIÊU UYỂN) |  |
| Ch06 | STATE | → Bắc Nhung đòi Vĩnh Ninh công chúa (người chạy tin; Ch06 §III xếp vào "biết thật") | CANON_FACT | Ch06 §I.34; Ch06 §III |  |
| Ch06 | STATE | (nghe thuật lại tới Chiêu) công chúa đã về thành và "tự sang bên kia chiến lũy. Tự đi, không ai bắt." | CANON_SUSPICION | Ch06 §I.37 |  |
| Ch06 | STATE (cuối chương) | (nghe thuật lại) → "Đã đi theo Bắc Nhung (theo tin truyền lại)" | CANON_SUSPICION | Ch06 §IV |  |
| Ch07 | STATE | → đoàn hộ vệ khoảng hai trăm người, người khoác áo choàng mũ trùm (đám đông hô "Công chúa về thành rồi!"); tướng hộ tống + mười hộ vệ đưa ra giữa khoảng trống; nàng đi tiếp một mình, dừng chỉnh mũ trùm, không quay đầu; ngựa Bắc Nhung khép quanh, đi về phía bắc | CANON_FACT | Ch07 §I.19, §I.22–24 |  |
| Ch07 | KNOWLEDGE (Dịch không thấy mặt) | Dịch không thấy mặt người khoác áo choàng khi đoàn tới | CANON_FACT | Ch07 §I.19 |  |
| Ch07 | KNOWLEDGE (không biết) | vì sao quay lại; điều kiện nàng đưa ra | CANON_UNKNOWN | Ch07 §II, §III |  |
| Ch07 | STATE | → theo Bắc Nhung về phía bắc | CANON_FACT | Ch07 §IV |  |
| Ch10 | STATE | Các bộ dưới trướng Khả đôn đã rời quân Hách Liên (cớ trong lời sứ giả: đồng cỏ mùa đông, súc vật đói); đề nghị đình chiến mười ngày; trả mũ trụ; quân cờ trắng; dặn "Đừng đuổi qua sông." [nhãn gốc "Khả đôn" (Ch10); ⚠ xem CB-L-25] | CANON_FACT | Ch10 §I.26–27, I.38 | (không nối qua ranh giới bí danh "Khả đôn" — xem CB-L-25) |
| Ch10 | KNOWLEDGE | Lời Khả đôn (qua sứ giả): "Lửa bên này sông mà cháy to, thì cả thảo nguyên sẽ muốn tràn xuống. Khả đôn không muốn thế." ⟦ST gốc: "CANON_FACT (lời nói trên trang)"⟧ [nhãn gốc "Khả đôn" (Ch10); ⚠ xem CB-L-25] | CANON_FACT | Ch10 §I.28 | (không nối qua ranh giới bí danh "Khả đôn" — xem CB-L-25) |
| Ch10 | KNOWLEDGE | Uyển biết gì về Tam Lang; tình cảm/mục đích; có biết toàn bộ chuyện Vân Trung: OPEN | CANON_UNKNOWN | Ch10 §II, §III |  |
| Ch12 | STATE | Ảnh hưởng (tận mắt): thủ lĩnh Bắc Nhung đợi nàng ngồi mới ngồi; người râu rậm định nói, nàng không gật, người ấy im; nói tiếng Hán không qua thông ngôn | CANON_FACT | Ch12 §I.9 |  |
| Ch12 | STATE | Lập trường: trướng Khả đôn vì hòa ước và chợ biên; giữ các bộ theo mình; mùa đông này không mở chiến dịch vượt sông; "Ta không nói thay Hách Liên. Ta không nói thay cả Bắc Nhung." | CANON_FACT | Ch12 §I.10, I.24 |  |
| Ch12 | STATE | Cuối Ch12: Khả đôn; đang vắng Bắc cảnh (Gate R3: Hách Liên biết); đã cam kết giữ các bộ theo mình qua mùa đông | CANON_FACT | Ch12 §IV |  |
| Ch12 | KNOWLEDGE | Trình Dịch = Thẩm thư lại (nhìn lâu); ĐÃ BIẾT Tam Lang là nữ (P-01); nghe "Dạ Kiêu" | CANON_FACT | Ch12 §III (Uyển) |  |
| Ch12 | KNOWLEDGE | Căn cứ Uyển biết Tam Lang là nữ: OPEN | CANON_UNKNOWN | Ch12 §II |  |
| Ch12 | KNOWLEDGE | Nghe "Người hứa là Hoắc Chiêu." — Uyển không ngạc nhiên (tay đặt lên mép ấm nước) | CANON_FACT | Ch12 §I.29 |  |
| Ch12 | RELATION(Chiêu) | Rót nước cho Tam Lang trước; hỏi con ngựa hồng năm ấy; ngồi sát bên, không giữ khoảng cách khách sáo | CANON_FACT | Ch12 §I.26–27 |  |
| Ch12 | RELATION(Dịch) | Dịch đứng nhìn nàng tự đi (Ch7); ACTIVE, chưa chạm (nợ Dịch → Uyển) | CANON_FACT | Ch12 §VI | ← Ch01 RELATION(Dịch) |
| Ch12 | KNOWLEDGE | Dịch không biết: số bộ/quân; quan hệ thực với Hách Liên; giữ quyền bằng gì; giữ yên bao lâu; con của Uyển; Khả hãn hiện tại; quan hệ huyết thống Hoài Nam vương | CANON_UNKNOWN | Ch12 §III (Dịch/Uyển), §II |  |
| Ch13 | GOAL | Xuống thuyền Kim Lăng "vì việc": đường tin mùa đông nếu có bộ nào trái lời; đường: trướng → Hắc Hà → Vân Trung → Kim Lăng | CANON_FACT | Ch13 §I.15 | (Before chưa trích được) |
| Ch13 | STATE | "Giữ được những người theo ta." (đáp Vân Chương) | CANON_FACT | Ch13 §I.16 |  |
| Ch13 | RELATION(Vân Chương) | Thị nữ bưng chén nước vỏ quýt đặt trước Vân Chương, Uyển không nói gì; chàng nhìn nàng lâu, Uyển đứng dậy trước; ACTIVE, không gọi tên | CANON_FACT | Ch13 §I.17–18, §VI |  |
| Ch13 | KNOWLEDGE | Nghe hai người chèo thuyền nói nhỏ, một người nhắc Kim Lăng; không nghe rõ; không dừng lại ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch13 §I.19, §III (Uyển) |  |
| Ch13 | KNOWLEDGE | Không biết: rò tin bên trong ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch13 §I.19, §III (Uyển) |  |
| Ch18 | GOAL | Luật mùa cỏ, bốn điều: ngựa chiến/thịt khô chỉ đi qua chợ biên có sổ, thuế một phần mười; không cướp chợ biên, không giết thương nhân dưới cờ chợ; không vượt sông; bộ theo luật được đồng cỏ gần sông và nước giếng. Lý do nói ra: "Ngựa gầy. Giá rớt thì bộ nào cũng thiệt. Chợ còn thì còn chỗ bán." | CANON_FACT | Ch18 §I.6 | ← Ch13 GOAL |
| Ch18 | STATE | Quyền: thủ lĩnh các bộ đợi nàng ngồi mới ngồi; có trướng quân (chỉ huy trướng quân vô danh); đặt người ở giếng "cho mọi đàn" | CANON_FACT | Ch18 §I.3, §I.5; Ch18 §II | ← Ch13 STATE |
| Ch18 | STATE | Nhận nén bạc có dấu đúc (bốn chữ niên hiệu + một chữ "kho") từ người già bộ nhỏ; đọc ngay, không dừng; nén bạc vào tay áo; chưa dùng | CANON_FACT | Ch18 §I.2; Ch18 §IV; Ch18 §V |  |
| Ch18 | LIMIT | Khi xử: không nêu bạc, không nêu Hạ Hầu; tay trong tay áo nơi có nén bạc, không lấy ra; trên trang nàng không nói "Hạ Hầu" | CANON_FACT | Ch18 §I.18; Ch18 §II |  |
| Ch18 | LIMIT | Xử vì cờ chợ (luật 2), không vì bán ngựa; đường tuân luật là thật (đàn bộ nhỏ đăng sổ đi qua giếng) | CANON_FACT | Ch18 §0 (GR18-3); Ch18 §I.10 |  |
| Ch18 | LIMIT | "Không hỏi lần hai" khi thủ lĩnh bộ nhỏ hỏi "đưa đi đâu?" mà không ai đáp | CANON_FACT | Ch18 §I.7 |  |
| Ch18 | STATE | Đề nghị Tu Bặc Cốt đêm trước hội (ngựa qua chợ biên, đăng sổ, thuế một phần mười, bạc giữ nửa mức cũ, đồng cỏ gần sông cho bộ hắn): hắn không nhận, không từ chối | CANON_FACT | Ch18 §I.4 |  |
| Ch18 | RELATION(Tu Bặc Cốt) | Không hỏi chuyện mũ ("Ta không hỏi ngươi chuyện mũ. Ta hỏi ngươi chuyện người chết."), không xác nhận, không phủ nhận lời hắn → gật cho thủ lĩnh râu rậm đọc luật; "Luật nói chết" → Tu Bặc Cốt chết | CANON_FACT | Ch18 §I.17–I.18; Ch18 §I.20 |  |
| Ch18 | STATE | Giao hội cho ông già sứ tối ngày hội đầu, lên ngựa cùng toán nhỏ ra giếng; sáng ngày thứ ba tới giếng; rạng hôm sau về bãi hội (hai ngày ngựa); phiên xử trưa ngày thứ sáu | CANON_FACT | Ch18 §I.9–I.10, §I.15–I.16; Ch18 §0 |  |
| Ch18 | STATE | Ở giếng: giữ đàn Tu Bặc Cốt; "Đàn này giữ ở giếng. Người ở lại. Ta về hội, mang hắn theo."; thả ba người áo bụi tay không | CANON_FACT | Ch18 §I.14–I.15 |  |
| Ch18 | STATE | Cuối Ch18: giữ được hội; mất bộ Tu Bặc Cốt, một nửa bộ nhỏ (nửa giá), người của Hách Liên, kỵ độc lập; còn trướng quân + kỵ các bộ theo nàng; nén bạc trong tay áo | CANON_FACT | Ch18 §IV |  |
| Ch18 | STATE | Gửi thư một dòng ("Một bộ trái lời. Đã xử. Trướng giữ.") qua bốn chặng tin về Kim Lăng; gói vỏ quýt "Đi sau." | CANON_FACT | Ch18 §I.23–I.24; Ch18 §IV |  |
| Ch18 | KNOWLEDGE | Biết: ngựa đi tây qua Tu Bặc Cốt; bạc dấu kho Hán; người mua giọng miền tây (đã thả); Tu Bặc Cốt giết thương nhân dưới cờ chợ; đàn giữ ở giếng; mình đã xử hắn; thư ngắn + gói đã đi; Hách Liên Chước tập hợp quân | CANON_FACT | Ch18 §III | (Before chưa trích được) |
| Ch18 | KNOWLEDGE(không biết) | Hách Liên có sai Tu Bặc Cốt không; mục tiêu Hách Liên; Hạ Hầu đáp ra sao; Ch17, Ch19 | CANON_UNKNOWN | Ch18 §III; Ch18 §II |  |
| Ch18 | KNOWLEDGE(không biết) | Số ngựa/quân/bộ; số phận nén bạc; Kim Lăng/Vân Chương phản ứng với thư + gói; người mua là ai/của ai (trên trang không nêu phe) | CANON_UNKNOWN | Ch18 §II |  |
| Ch18 | RELATION(bộ nhỏ) | Oán thật do luật của nàng (nửa giá); thủ lĩnh bộ nhỏ ngồi xuống "không cúi đầu" rồi dẫn người đi, không ở lại ăn lửa — mới, ACTIVE | CANON_FACT | Ch18 §I.19, §I.21; Ch18 §VI |  |
| Ch18 | RELATION(Hách Liên Chước) | "Cớ trao tay" — mới, ACTIVE; người của Hách Liên nhìn nàng một lần rồi đi | CANON_FACT | Ch18 §VI; Ch18 §I.9, §I.21 |  |
| Ch18 | RELATION(người chết) | Hai mạng vì luật (thương nhân Hán; Tu Bặc Cốt) — mới | CANON_FACT | Ch18 §VI |  |
| Ch18 | RELATION(ông già sứ) | Ông ngồi ngoài vòng lửa, không ăn; nàng rót nước, đặt chén ở mép lửa, không ép — mới, không giải | CANON_FACT | Ch18 §I.22; Ch18 §VI |  |
| Ch18 | RELATION(Vân Chương) | Gói vỏ quýt đi sau thư; câu chàng không hỏi — ACTIVE, không gọi tên; trên trang không tên Vân Chương | CANON_FACT | Ch18 §VI; Ch18 §I.24; Ch18 §0 | ← Ch13 RELATION(Vân Chương) |
| Ch18 | KNOWLEDGE | (nghe thuật lại) người già bộ nhỏ (người đã đặt nén bạc) rạng sáng báo: Hách Liên cho thổi tù và dọc bờ bắc; các bộ thân với Tu Bặc Cốt kéo về doanh hắn; nàng không hỏi bao nhiêu người (Canon Update ghi Hách Liên "Đang tập hợp quân (tin; chưa hành động)") | CANON_SUSPICION | Ch18 §I.26; Ch18 §IV |  |
| Ch20 | KNOWLEDGE | Uyển nói "Đi sau." với thị nữ (Ch18); Vân Chương không nghe | CANON_FACT | Ch20 §0 (Sync Ch18) | ← Ch18 STATE (gói vỏ quýt "Đi sau.") |
| Ch20–Ch21 | STATE | Uyển chưa biết Kim Lăng nhận thư | CANON_FACT | Ch20 §IV (Uyển); Ch21 §IV (Uyển) | ← Ch18 STATE |
| Ch20–Ch21 | KNOWLEDGE | Uyển nghĩ gì khi nhận lại; câu Vân Chương không hỏi Uyển | CANON_UNKNOWN | Ch20 §II; Ch21 §III (Vân Chương) |  |

**(c) PLANNING_NON_CANON**

| Ch | Trường | Nội dung (kế hoạch / author-truth; KHÔNG phải canon trang) | Source Type | Source |
|---|---|---|---|---|
| Ch10 | KNOWLEDGE | Sứ giả có biết ý nghĩa quân cờ không: author-truth (không) | PLANNING_NON_CANON | Ch10 §II |
| Ch13 | KNOWLEDGE | Nhận lời báo Dạ Kiêu: author-truth, không lên trang | PLANNING_NON_CANON | Ch13 §III (Uyển) |
| Ch18 | GOAL | (author-truth, không lên trang) "Muốn không có chiến tranh lớn, nàng phải làm một việc… giết một người trước mặt những người còn lại" | PLANNING_NON_CANON | Ch18 §Nguyên tắc ghi |
| Ch16 | STATE (Khả đôn) | chỉ dấu chương: phản ứng Khả đôn khi hết băng tan "→ Ch18" | PLANNING_NON_CANON | Ch16 §II |
| Ch18 | KNOWLEDGE | chỉ dấu chương: phản ứng Kim Lăng / Vân Chương với thư + gói "→ Ch20" | PLANNING_NON_CANON | Ch18 §II |

**(e) [BÍ DANH CHƯA XÁC NHẬN — xem CB-L-25] KHỐI "KHẢ ĐÔN / TRƯỚNG KHẢ ĐÔN" — giữ tách theo staging Ch14–18** (Canon Update Ch17 §III liệt kê "Uyển" và "Khả đôn" riêng; Ch18 lời thoại gọi Uyển là "Khả đôn"; xem CB-L-25)

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch14 | RELATION | Có một thông ngôn trướng Khả đôn (T3, điểm C, đêm 13); hắn hỏi Chỉ: "người Hán ngồi cùng một bàn đêm trước, sáng sau đã bán nhau ở bến"; còn nhận một chỗ hẹn miệng | CANON_FACT | Ch14 §I.2, §I.9; Ch14 §III |  |
| Ch15 | STATE | Khả đôn giữ lời: suốt mùa đông bờ bắc sông không có một lều bộ nào dựng lên | CANON_FACT | Ch15 §I.2 |  |
| Ch15 | LIMIT | Lời hứa của trướng Khả đôn hết hạn khi băng tan (không ai nói ra, ai cũng biết) | CANON_FACT | Ch15 §I.7 |  |
| Ch16 | STATE | Phản ứng Khả đôn khi hết băng tan: chưa có; lời hứa không nhắc thành lời | CANON_UNKNOWN | Ch16 §II; Ch16 §0 |  |
| Ch17 | STATE | Phản ứng Khả đôn khi hết băng tan: Ch18; "Khả đôn" không xuất hiện | CANON_UNKNOWN | Ch17 §IX; Ch17 §III |  |
| Ch18 | STATE | Trên trang Ch18 người khác nói với Uyển "Nếu Khả đôn muốn nghe…", "Khả đôn nhầm chỗ", "Khả đôn nói thay người Hán"; heading cảnh I-V Ch18: "trướng Khả đôn" | CANON_FACT | Ch18 §I.2, §I.14, §I.17; Ch18 §I (tiêu đề cảnh I, V) |  |

### 3.4 HOẮC CHIÊU (Hoắc Tam Lang) <a id="nv-chieu"></a>

[Canon xác nhận Tam Lang = Hoắc Chiêu: Ch12 §III ("Tam Lang là Hoắc Chiêu"), Ch12 §I.29 — giữ gộp; nhãn "Hoắc quân" / thân binh "Tam tướng quân" ở Ch14 vẫn không gắn tên Chiêu, xem CB-L-27]

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE | (đầu dải) → cổ áo dựng cao, giọng khàn trầm, chai tay người luyện thương, dấu chân nông hơn các kỵ binh khác | Ch01 | CANON_FACT | Ch01 §I.14 |
| APPEARANCE | POV Chiêu | Ch06 | CANON_FACT | Ch06 §đầu file |
| APPEARANCE | Vắng; chỉ được nhắc qua lời đồn "Hoắc Tam Lang tử trận ở Hắc Hà" (Phùng Bảo nghe ở chợ từ người buôn da; Canon Update ghi "Lời đồn sai") — dòng lời đồn: CANON_SUSPICION ở khối Dịch / Phùng Bảo | Ch08 | CANON_FACT | Ch08 §I.13, §III |
| APPEARANCE | POV Chiêu cả chương. CHƯƠNG LÙI THỜI GIAN (năm 0, tháng Giêng → đầu tháng Hai; trước Ch8) | Ch10 | CANON_FACT | Ch10 §Nguyên tắc ghi |
| APPEARANCE | Có mặt, không POV. Dịch nhận ra ngay "Hoắc Tam Lang" đang đi quanh vòng gác (Tầng 1), không gọi; tại đình: không đổi sắc mặt, không rời mắt khỏi Dịch | Ch12 | CANON_FACT | Ch12 §I.5, I.8 |
| APPEARANCE | POV đoạn II (giữa sáng, đất trống giữa hai vòng gác); có mặt ở đoạn I | Ch13 | CANON_FACT | Ch13 §Nguyên tắc ghi, §I.I–II |
| APPEARANCE | vắng (Ch14 chỉ nhắc "Hoắc quân" / thân binh "Tam tướng quân"; Canon Update không gắn tên Chiêu) | Ch14 | CANON_FACT | Ch14 §III; Ch14 §I.2 |
| APPEARANCE | first trong dải (không POV); có mặt ở hội (Chiêu) và tới doanh Dịch sáng ngày thứ tám | Ch15 | CANON_FACT | Ch15 §I.3, §I.25 |
| APPEARANCE | không POV; ngồi cuối bàn hội, từ đầu chưa nói câu nào | Ch16 | CANON_FACT | Ch16 §I.11 |
| APPEARANCE | POV toàn chương (narration "Chiêu"/"nàng") | Ch17 | CANON_FACT | Ch17 §Nguyên tắc ghi |
| APPEARANCE | vắng; chỉ bị nhắc trong lời Tu Bặc Cốt: "Ngươi trả mũ cho tướng Hoắc. Ngươi đặt quân cờ trắng lên bàn người Hoắc." (Canon Update ghi chú "không tên Chiêu") | Ch18 | CANON_FACT | Ch18 §III; Ch18 §I.17 |
| APPEARANCE | có mặt (gò thấp; lều Dịch) | Ch19 | CANON_FACT | Ch19 §I.4, I.12 |
| APPEARANCE | vắng; chỉ qua báo cáo ("kỵ nhẹ của Hoắc Tam Lang không vào") | Ch20 | CANON_FACT | Ch20 §I.2; Ch20 §III |
| APPEARANCE | vắng | Ch21 | CANON_FACT | Ch21 §III |
| APPEARANCE | vắng; gò thấp phía đông trống (một nhịp) | Ch22 | CANON_FACT | Ch22 §I.1; Ch22 §IV (Chiêu/Hoắc) |
| GOAL | Việc của Chiêu (kế hoạch Dịch nêu): vây ngoài thành, không công thành, đốt kho bến, ở lại, ở chỗ họ thấy | Ch17 | CANON_FACT | Ch17 §I.5 |
| GOAL | Tự quyết làm mồi: "Họ phải nhận ra ta."; "Tiểu Thất. Lấy mũ." | Ch17 | CANON_FACT | Ch17 §I.10 |
| LIMIT | "Nuôi cả quân ba tuần, ta không nuôi nổi. Nuôi một nửa thì nuôi được." Một nửa Hoắc quân về biên trong ba ngày do phó tướng dẫn; kỵ nhẹ ở lại với nàng ăn lương Ích Châu; hết ba tuần kể từ hôm hội, chưa thấy gì thì nửa còn lại cũng về | Ch16 | CANON_FACT | Ch16 §I.12 |
| LIMIT | Ba điều kiện: (1) chỗ đứng kỵ nhẹ nàng chọn (không trong thành, không dưới đáy cổ chai, không sát nước); (2) mặt trời lặn chưa thấy đèn thuyền ở cọc → đốt một nén hương; hương tàn chưa thấy → rút; nợ lương ghi tên Ích Châu; (3) hết trận kỵ nhẹ về biên, không quá ngày 42; hạn ngày 31 bỏ | Ch17 | CANON_FACT | Ch17 §I.11 |
| LIMIT | "Ta không ký." / "Kỵ nhẹ của ta không vào thành. Không ai của ta tự vào. Không phải vì tờ giấy." | Ch19 | CANON_FACT | Ch19 §I.12 |
| RELATION(Hoắc Thành Lĩnh) | → Hoắc nắm tay con, nói "A Chiêu", rồi "…quân…", rồi mất; bốn lính ở cửa không nghe | Ch06 | CANON_FACT | Ch06 §I.20 |
| RELATION(cha) | Mũ trụ rơi vào tay giặc, được người khác trả lại; ACTIVE, không nói ra | Ch10 | CANON_FACT | Ch10 §VI |
| RELATION(Chu Hạc) | Nợ chính danh bị hiểu sai (Canon Ch6), CỦNG CỐ bằng niềm tin vào số liệu; Ẩn | Ch10 | CANON_FACT | Ch10 §VI |
| RELATION(Khương lão tướng / tướng trẻ) | Khương: muốn lui, ủng hộ nhận đình chiến. Tướng trẻ: muốn đánh, không vừa lòng với đình chiến | Ch10 | CANON_FACT | Ch10 §III (Các nhân vật khác), §I.35–37 |
| RELATION(Uyển) | Uyển rót nước cho Tam Lang trước; hỏi con ngựa hồng năm ấy — Tam Lang: "Không. Ngựa sân tập, không ai giữ được lâu."; Uyển ngồi sát bên Tam Lang, không giữ khoảng cách khách sáo | Ch12 | CANON_FACT | Ch12 §I.26–27 |
| RELATION(A Quy) | Hoãn, không tha; deadline mùa đông; ACTIVE | Ch13 | CANON_FACT | Ch13 §VI |
| RELATION(hội minh) | Lui, quay lại tìm cột; mất bảy trăm — "Mới, không gọi tên" | Ch15 | CANON_FACT | Ch15 §VI |
| RELATION(Tiểu Thất) | Chi phí tác chiến; không dựng nhịp riêng — mới | Ch17 | CANON_FACT | Ch17 §VI |
| RELATION(Hoắc quân) | Kỵ nhẹ hao ("cánh trái trống nhiều chỗ") — mới | Ch17 | CANON_FACT | Ch17 §VI; Ch17 §I.28 |
| RELATION(Dịch) | Dịch không xin lỗi, nàng không tha thứ; "Ta biết." | Ch19 | CANON_FACT | Ch19 §I.4, I.12 |
| STATE | ngồi trên ngựa Tiểu Thất; tay trái buộc dải vải sẫm; tay áo phải phồng (ống hương) | Ch19 | CANON_FACT | Ch19 §I.4; Ch19 §IV (Chiêu, Vật) |
| STATE | kỵ nhẹ lùi xa, đứng yên trên gò thấp, không vào thành; hạn ngày 42 (chưa dùng) | Ch19 | CANON_FACT | Ch19 §I.18, I.21; Ch19 §IV (Chiêu) |
| STATE | không gia hạn, không kỵ Hoắc trên trang | Ch22 | CANON_FACT | Ch22 §0 (Sync Ch17/Ch19) |
| KNOWLEDGE | Biết: Hổ Lao đã dàn quân đủ; Hoắc quân mất bảy trăm; cột Ích Châu còn ba ngày lương | Ch15 | CANON_FACT | Ch15 §III |
| KNOWLEDGE | Biết: đường than (giấy không ở lại); Dĩnh Xuyên là cảng cấp lương, kho, đê, cổ chai, tháp hiệu, đường đồi có đồn; thuyền tới cọc trong một nén hương; viện quân hai khối bị chặn/phá một phần; Tiểu Thất chết; hồi âm chỉ lương (đội trưởng báo); "Lệnh còn." | Ch17 | CANON_FACT | Ch17 §III |
| KNOWLEDGE | biết: kỵ nhẹ lùi, không vào thành; không ký; hạn 42 (chưa dùng) | Ch19 | CANON_FACT | Ch19 §III (Chiêu) |
| KNOWLEDGE | Tin con số của Chu Hạc: "mười năm nay, con số nào Chu Hạc đưa lên, nàng chưa thấy sai" — "Số liệu của ông ta đáng tin; ông ta đáng tin" ⟦ST gốc: "CANON_BELIEF (Chiêu)"⟧ | Ch10 | CANON_BELIEF | Ch10 §I.23, §III (Chu Hạc) |
| KNOWLEDGE(chính mình) | "Có. Chưa chắc." (có cách khác ngoài hạn ngày 42) ⟦ST gốc: "CANON_BELIEF (Chiêu)"⟧ | Ch19 | CANON_BELIEF | Ch19 §I.4 |
| KNOWLEDGE (thoáng không khớp, "không phải suy luận") | xác người Bắc Nhung trong thư phòng | Ch06 | CANON_SUSPICION | Ch06 §III |
| KNOWLEDGE(không biết) | Vì sao Dịch chắc họ sẽ cứu; cách Bàng đọc liên minh; ai chỉ huy viện; Dịch ở đâu trong trận; ý đồ hồi âm; A Quy ở đâu; rò (Ch14) | Ch17 | CANON_UNKNOWN | Ch17 §III |
| KNOWLEDGE | không biết: điều Dịch viết trước khi vào lều | Ch19 | CANON_UNKNOWN | Ch19 §III (Chiêu) |
| KNOWLEDGE | kỵ nhẹ/hạn 42: Chiêu về biên hay ở lại; có tin phương bắc không | Ch20–Ch22 | CANON_UNKNOWN | Ch19 §II; Ch20 §IX; Ch21 §II-A; Ch22 §IX |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch01 | STATE | (đầu dải) → đi đồn Hắc Hà từ tháng Năm, về thành cùng ngày với đoàn hòa thân (vào từ phía Bắc); về phủ tướng quân cùng khoảng hai mươi kỵ binh | CANON_FACT | Ch01 §I.4, §V, §VI |  |
| Ch01 | RELATION(Dịch) | → lần đầu chạm mặt | CANON_FACT | Ch01 §I.4 |  |
| Ch01 | KNOWLEDGE | biết có một thư lại lạ mặt nhìn mình và trả lời "mới thấy một người" | CANON_FACT | Ch01 §III (HOẮC TAM LANG) |  |
| Ch02 | STATE | → đi tuần nội phủ khoảng canh ba với đèn lồng và trường thương; phát hiện Chỉ nhờ vết tuyết tan trên sàn hành lang; dùng cán thương, rồi truy ra sân; dùng mũi thương giật dây móc từ dưới hẻm | CANON_FACT | Ch02 §I.18–20 |  |
| Ch02 | STATE (thương tích) | → bị Chỉ rạch tay áo và cánh tay, chảy máu, nhẹ đến trung bình; được cha bảo đi băng lại | CANON_FACT | Ch02 §I.21 |  |
| Ch02 | KNOWLEDGE | biết cha cố ý giữ sát thủ sống ngoài sổ sách; sát thủ muốn vào khu thư phòng | CANON_FACT | Ch02 §III (HOẮC TAM LANG) |  |
| Ch02 | KNOWLEDGE (không biết) | sát thủ là ai; lý do của cha; nội dung cuộc gặp gần sáng giữa Hoắc và Chỉ | CANON_UNKNOWN | Ch02 §III |  |
| Ch02 | STATE | → nhìn cha với một câu hỏi, không hỏi trước mặt lính | CANON_FACT | Ch02 §I.22 |  |
| Ch03 | STATE | → chịu trách nhiệm chung giám sát A Quy; băng tay còn (lộ hai lần, không xác định tay nào); luôn đứng cách A Quy khoảng một cây thương; nói "Người trong phủ phạm lỗi, đang chịu phạt."; ký nhận 18 bộ áo | CANON_FACT | Ch03 §I.6, §I.21, §I.44–47 |  |
| Ch03 | STATE (vật) | dao và dây móc của Chỉ: (Ch2: "người giữ chưa xác định") → Tam Lang giữ | CANON_FACT | Ch03 §VI; Ch02 §VI |  |
| Ch03 | STATE (tính cách/ván cờ) | không bỏ nhóm quân nào khi đánh cờ | CANON_FACT | Ch03 §I.49 |  |
| Ch03 | KNOWLEDGE | biết thêm Dịch giữ lời, làm việc theo sổ; A Quy phân loại áo giỏi, đếm đúng | CANON_FACT | Ch03 §III (HOẮC TAM LANG) |  |
| Ch03 | KNOWLEDGE (không biết) | A Quy là Bùi Chỉ; lý do cha giữ A Quy | CANON_UNKNOWN | Ch03 §III |  |
| Ch03 | STATE | → chiều ngày 18 nhận tin Hắc Hà, nói "Sông đóng thì ngựa qua được", rời phòng trực, để quân trắng giữ lượt trên mép bàn | CANON_FACT | Ch03 §I.50 |  |
| Ch03 | STATE (thân phận) | Dịch/Chỉ không biết "thân phận nữ của Tam Lang" (Canon Update Ch3 ghi như điều Dịch không biết) | CANON_UNKNOWN | Ch03 §III |  |
| Ch04 | STATE | → lên đồn Hắc Hà ngày 19, về thành chiều ngày 23; đặt quân trắng xuống cuối hàng quân chờ lượt; báo cáo: băng dày ngang một bàn tay, đồn tăng người, lính gác đổi ca nửa canh giờ một lần | CANON_FACT | Ch04 §I.3, §I.26, §I.31 |  |
| Ch04 | KNOWLEDGE | biết tình trạng Hắc Hà (tận mắt); quan sát Dịch mời Vân Chương không theo thứ tự quân và Vân Chương đánh giữ quân, không suy luận; nói "Tạ đại nhân hôm nay tiếc quân quá." | CANON_FACT | Ch04 §III (HOẮC TAM LANG), §I.30 |  |
| Ch05 | STATE | → được mời một lần, từ chối ("Đêm ấy cha ta ăn tất niên với lính trong phủ. Ta phải ở đó."); thắng Dịch ba mục; trả lời Vân Chương "Có. Cha ta không thích ồn. Nhưng lính thích." | CANON_FACT | Ch05 §I.21, §I.24–25 |  |
| Ch06 | RELATION(Hoắc Thành Lĩnh) | → cha chỉnh cổ áo, dặn "Mùng một theo cha ra đồn phía tây…" và "Đừng uống nhiều."; nhớ lại câu hỏi pháo của Vân Chương, không nghĩ thêm | CANON_FACT | Ch06 §I.3, §I.6 |  |
| Ch06 | STATE (báo động) | → thấy quầng lửa phía Bắc Môn; quay về thư phòng một bước rồi dừng; sai thân binh Tiểu Tứ tới báo cha, mình ở lại tập hợp lính; giữ được cổng phủ trước đợt đầu; Tiểu Tứ không quay lại | CANON_FACT | Ch06 §I.8–12 |  |
| Ch06 | STATE (thư phòng) | → thấy A Quy bước ra cầm đao dính máu; giao thủ một đòn (đâm/gạt, cán thương quất sườn A Quy); không đuổi; vào thư phòng: Hoắc trọng thương, xác một người Bắc Nhung nằm sấp gần cửa sổ, thoáng "có gì đó không khớp" | CANON_FACT | Ch06 §I.14–19 |  |
| Ch06 | RELATION(Hoắc Thành Lĩnh) | → Hoắc nắm tay con, nói "A Chiêu", rồi "…quân…", rồi mất; bốn lính ở cửa không nghe | CANON_FACT | Ch06 §I.20 |  |
| Ch06 | STATE (thân phận) | Tam Lang (nam theo cách gọi trước) → từ đây narration gọi "nàng"; "Mười mấy năm rồi, chỉ có ông còn gọi nàng như thế." | CANON_FACT | Ch06 §I.21 |  |
| Ch06 | STATE (quyền) | → nhận nửa hổ phù từ Lão Tần; Chu Hạc công khai "Hoắc gia quân nghe lệnh Tam công tử"; chiến bào đỏ sẫm, mũ trụ chùm lông đen của Hoắc (quá dài/lỏng); dựng tướng kỳ nền đen chữ Hoắc | CANON_FACT | Ch06 §I.23–24, §I.28–30 |  |
| Ch06 | STATE (lệnh) | → lệnh đầu: tam đội phá góc phố phía đông, nhị đội giữ cổng, cung thủ lên mái kho (góc phố phía đông vỡ, vòng vây ở cổng lỏng); nghe phòng củi trống, không hỏi ai mở; đuổi theo vòng vây rút với 200 người và 30 ngựa; không đuổi ra ngoài thành; lệnh "Đóng Bắc Môn."; "A Quy. Bắt sống." | CANON_FACT | Ch06 §I.31–32, §I.39–47 |  |
| Ch06 | KNOWLEDGE (biết thật) | Hoắc Thành Lĩnh đã chết; A Quy bước ra thư phòng với đao/máu rồi chạy; có xác thích khách Bắc Nhung trong thư phòng; Bắc Môn mở từ bên trong, then và bản lề không bị phá; lính gác trẻ chết tại vòm; phòng củi trống, khóa mở; Bắc Nhung đòi Vĩnh Ninh công chúa; tin truyền lại Uyển đã tự đi sang Bắc Nhung; nắm quyền chỉ huy thực tế lực lượng Hoắc tại Vân Trung; cha gọi nàng "A Chiêu" | CANON_FACT | Ch06 §III (HOẮC CHIÊU) |  |
| Ch06 | KNOWLEDGE (tin/suy diễn) | A Quy có liên quan cuộc tập kích; có thể là nội ứng; có thể đã dẫn đường/giúp Bắc Nhung tiếp cận cha; Uyển đã tự chọn đi theo Bắc Nhung | CANON_BELIEF | Ch06 §III, §II |  |
| Ch06 | KNOWLEDGE (thoáng không khớp, "không phải suy luận") | xác người Bắc Nhung trong thư phòng | CANON_SUSPICION | Ch06 §III |  |
| Ch06 | KNOWLEDGE (không biết) | ai mở Bắc Môn; Chu Hạc ở đâu lúc chính Tý; người lính thứ hai đã làm gì; ai mở khóa phòng củi; chuyện thật trong thư phòng/vì sao có xác Bắc Nhung/A Quy thực sự đã làm gì; Vân Chương ở đâu; Dịch ở đâu; tên thật của A Quy | CANON_UNKNOWN | Ch06 §III |  |
| Ch06 | STATE (thương tích/tinh thần) | → kiệt sức; nắm nửa hổ phù | CANON_FACT | Ch06 §IV |  |
| Ch06 | STATE (CANON CHANGE, sync) | Gate mục 5: Hoắc "sai một thân binh chạy đi gọi Tam Lang" → Hoắc không sai ai đi; giữ cả hai thân binh ở cửa; Tiểu Tứ (do Tam Lang sai) không quay lại, số phận OPEN [CANON CHANGE] | CANON_FACT | Ch06 §0A |  |
| Ch07 | STATE | → Vân Trung, cầm quân; lệnh bắt sống A Quy lan tới nửa nam khi trời sáng hẳn ("Tam công tử có lệnh! Tên tù A Quy… Bắt sống!") | CANON_FACT | Ch07 §I.27, §IV |  |
| Ch07 | KNOWLEDGE (người khác) | Tam Lang không có thông tin mới nào về Dịch | CANON_UNKNOWN | Ch07 §III |  |
| Ch09 | STATE | Lời đồn tử trận → đính chính: "Hoắc Tam Lang vẫn giữ Hắc Hà" (tin trạm phương Bắc, ngày 24) | CANON_FACT | Ch09 §I.32 | ← Ch07 STATE |
| Ch10 | STATE | Đội mũ trụ chùm lông đen của cha; quân gọi "Tam tướng quân"; chỉ huy đục dải nước mở dọc bến chính | CANON_FACT | Ch10 §I.2, I.4 |  |
| Ch10 | STATE | Ngựa trúng giáo, ngã, sườn trái đập đá, mũ trụ văng; dựng lại cờ, đứng dưới cờ không ngựa, đầu để trần | CANON_FACT | Ch10 §I.10–13 |  |
| Ch10 | STATE | → gãy hai xương sườn; không cưỡi ngựa ít nhất nửa tháng → tại hook: vẫn chỉ huy tại đồn Hắc Hà, không cưỡi ngựa | CANON_FACT | Ch10 §I.17, §IV |  |
| Ch10 | STATE | Trên bàn trong trướng: mũ trụ (gãy một chùm lông, một vết lõm mới), quân cờ trắng, thư Chu Hạc | CANON_FACT | Ch10 §I.26, §IV (Vật) |  |
| Ch10 | GOAL | Giữ đồn: "Không lui." (đáp Khương lão tướng cuối tháng Giêng) | CANON_FACT | Ch10 §I.21 |  |
| Ch10 | GOAL | Decision Ch10: "Nhận. Mười ngày. Không qua sông." — Canon Change Chapter Bible đã duyệt: đồng ý đình chiến ngắn sau khi xác minh dữ kiện quân sự | CANON_FACT | Ch10 §I.36, §I (Chapter Bible Canon Change) |  |
| Ch10 | STATE (lực lượng) | Hơn ba trăm người cước, không cầm được rìu; xác chưa chôn vì đất đóng băng; lương hai mươi ngày đã hết mười hai (còn ~tám ngày — Canon Update ghi "khoảng tám ngày"); băng khoảng mười ngày nữa nứt ⟦ST gốc: "CANON_FACT (số theo Ch10 §I.31–33); "khoảng" tại §IV"⟧ | CANON_FACT | Ch10 §I.31–33, §IV |  |
| Ch10 | STATE (quân tâm) | Quân tâm "giữ được nhờ Chiêu còn đứng đó, nhưng đã xuất hiện rạn nứt" (tướng trẻ và vài người quay mặt đi) | CANON_FACT | Ch10 §I.37, §IV |  |
| Ch10 | KNOWLEDGE | Tin con số của Chu Hạc: "mười năm nay, con số nào Chu Hạc đưa lên, nàng chưa thấy sai" — "Số liệu của ông ta đáng tin; ông ta đáng tin" ⟦ST gốc: "CANON_BELIEF (Chiêu)"⟧ | CANON_BELIEF | Ch10 §I.23, §III (Chu Hạc) | (Before chưa trích được) |
| Ch10 | KNOWLEDGE | Cánh trái từng tưởng nàng chết (cờ đổ, mũ trụ trên giáo); đã thấy nàng sống, lời đồn trong quân tắt | CANON_FACT | Ch10 §I.15–16, §III |  |
| Ch10 | KNOWLEDGE | Lời đồn đã theo đoàn buôn da đi xuống phía nam: nàng KHÔNG nghĩ tới (ký sổ, gật đầu) | CANON_UNKNOWN | Ch10 §III (Lời đồn tử trận), §I.18 |  |
| Ch10 | KNOWLEDGE | Các bộ theo Khả đôn rút khỏi Hách Liên (trinh sát: chừng mười lăm trại dỡ lều; ước chừng gần hai nghìn kỵ đi); Khả đôn trả mũ trụ; không muốn chiến tranh lan rộng ⟦ST gốc: "CANON_FACT (ước chừng theo trinh sát)"⟧ | CANON_FACT | Ch10 §I.27–30, §III (Uyển / Khả đôn) |  |
| Ch10 | KNOWLEDGE | Quân cờ trắng: người gửi biết luật giữ lượt của bàn cờ Vân Trung ("Người gửi quân cờ này biết luật ấy") ⟦ST gốc: "CANON_FACT (theo bảng FACT)"⟧ | CANON_FACT | Ch10 §I.38–40, §III (Quân cờ trắng) |  |
| Ch10 | KNOWLEDGE | Quân cờ trắng KHÔNG xác nhận: tình cảm/mục đích của Uyển; việc Uyển biết Chiêu nghĩ gì; việc Uyển biết toàn bộ chuyện Vân Trung. Chiêu không biết "mọi điều hơn thế" | CANON_UNKNOWN | Ch10 §II, §III |  |
| Ch10 | KNOWLEDGE | Không biết: Uyển biết gì về Tam Lang; mục đích cá nhân của Uyển | CANON_UNKNOWN | Ch10 §III (Uyển / Khả đôn) |  |
| Ch10 | KNOWLEDGE | Lời sứ giả: "Trung Nguyên đang có binh đao"; Chiêu chưa biết Lạc Kinh thất thủ (cột UNKNOWN: "Lạc Kinh chưa thất thủ (chưa xảy ra)") | CANON_UNKNOWN | Ch10 §III (Trung Nguyên) |  |
| Ch10 | KNOWLEDGE | Dịch, Vân Chương, A Quy, Bắc Môn: không đổi so với đầu chương | CANON_FACT | Ch10 §III |  |
| Ch10 | RELATION(Uyển) | Nhận ơn từ bên kia sông; Mới, UNPAID | CANON_FACT | Ch10 §VI |  |
| Ch10 | RELATION(Hoắc quân) | Người cước, người chết vì dải băng; một phần quân quay mặt đi; ACTIVE | CANON_FACT | Ch10 §VI |  |
| Ch10 | RELATION(cha) | Mũ trụ rơi vào tay giặc, được người khác trả lại; ACTIVE, không nói ra | CANON_FACT | Ch10 §VI |  |
| Ch10 | RELATION(Chu Hạc) | Nợ chính danh bị hiểu sai (Canon Ch6), CỦNG CỐ bằng niềm tin vào số liệu; Ẩn | CANON_FACT | Ch10 §VI |  |
| Ch10 | RELATION(Khương lão tướng / tướng trẻ) | Khương: muốn lui, ủng hộ nhận đình chiến. Tướng trẻ: muốn đánh, không vừa lòng với đình chiến | CANON_FACT | Ch10 §III (Các nhân vật khác), §I.35–37 |  |
| Ch12 | STATE | Hoắc quân trên gò phía bắc, tướng kỳ họ Hoắc; lập trường (giọng trầm, khàn): không xuống nam khi phía bắc chưa yên; không có lương cũng không đi | CANON_FACT | Ch12 §I.4, I.10 |  |
| Ch12 | STATE | Tên thật đã nói trong gian trong ("Người hứa là Hoắc Chiêu."), KHÔNG công khai, KHÔNG văn thư; đã nói cho bốn người; ra theo danh phận "Tam tướng quân" | CANON_FACT | Ch12 §I.29–30, §III (Chiêu), §IV |  |
| Ch12 | STATE | Giọng trong gian trong: "thấp và rõ", không còn trầm, khàn | CANON_FACT | Ch12 §I.23 |  |
| Ch12 | LIMIT | Đứng dậy, tay lên chuôi kiếm khi Ích Châu bảo chứng A Quy: "Hết cuộc gặp này." — kiếm vẫn trong vỏ. Lệnh bắt A Quy hoãn tới hết cuộc gặp | CANON_FACT | Ch12 §I.17, I.19, §IV |  |
| Ch12 | GOAL | Lời Hoắc quân: nếu phía bắc yên qua mùa đông, sẽ xét việc đưa quân xuống nam; không rời biên ngay; không đứng dưới cờ ai ⟦ST gốc: "CANON_FACT (lời từng bên)"⟧ | CANON_FACT | Ch12 §I.24 |  |
| Ch12 | KNOWLEDGE | Trình Dịch = Thẩm thư lại; A Quy còn sống, nói lời của Dạ Kiêu; biết trước Khả đôn được mời (Gate R4); đã nói tên thật cho bốn người | CANON_FACT | Ch12 §III (Chiêu) |  |
| Ch12 | KNOWLEDGE | Ai biết nàng là nữ từ bao giờ; căn cứ Uyển biết: OPEN | CANON_UNKNOWN | Ch12 §II, §III (Dịch/Chiêu) |  |
| Ch12 | RELATION(Uyển) | Uyển rót nước cho Tam Lang trước; hỏi con ngựa hồng năm ấy — Tam Lang: "Không. Ngựa sân tập, không ai giữ được lâu."; Uyển ngồi sát bên Tam Lang, không giữ khoảng cách khách sáo | CANON_FACT | Ch12 §I.26–27 |  |
| Ch12 | RELATION(Dịch) | Nhìn thẳng vào Dịch sau câu "Người hứa là Hoắc Chiêu.", không giải thích | CANON_FACT | Ch12 §I.29 | ← Ch01 RELATION(Dịch) |
| Ch12 | RELATION(A Quy) | Kẻ bị truy mười năm ngồi cùng bàn; lời hoãn; ACTIVE | CANON_FACT | Ch12 §VI |  |
| Ch13 | STATE | Tự ra xem hàng: giáp nhẹ, không mũ trụ; rạch bao gạo, bốc, ngửi; nếm muối; hỏi từng chặng đường vận mùa đông | CANON_FACT | Ch13 §I.2 |  |
| Ch13 | STATE | Ký nhận tờ kê, KHÔNG hỏi dòng vải bông, gấp cất vào trong áo, không lấy ra xem lại; hỏi "Thư về Ích Châu, Hoắc quân được ghi thế nào?" — "Hoắc quân." | CANON_FACT | Ch13 §I.5–6, I.14 |  |
| Ch13 | LIMIT | Không vào vòng gác Ích Châu: "Nàng không bước qua lời bảo chứng của người khác." | CANON_FACT | Ch13 §I.8 |  |
| Ch13 | STATE | Với A Quy (ba câu): lệnh bắt sống vẫn còn; mùa đông này Hoắc quân không truy, Dạ Kiêu đứng trong lời hứa đêm qua; qua mùa đông hoặc lời hứa vỡ thì khác. Lệnh bắt: Còn; chạy lại khi hết mùa đông hoặc thỏa thuận vỡ | CANON_FACT | Ch13 §I.10, §IV |  |
| Ch13 | STATE | Vết sẹo cũ chạy dọc cánh tay (tay áo trái bị gió vén); A Quy nhìn; nàng kéo tay áo xuống; quay đi trước; không hỏi đêm ấy hắn ở đâu. Canon Update (Sync) nối với Ch3: vết thương trên cánh tay Tam Lang do A Quy rạch | CANON_FACT | Ch13 §I.12–13, §0 (Canon Sync, Ch3) |  |
| Ch13 | KNOWLEDGE | Biết thêm: đã nói điều kiện với A Quy; A Quy đáp "Ta biết"; vải bông đã vào kho ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch13 §III (Chiêu) |  |
| Ch13 | KNOWLEDGE | Không biết: rò tin bên trong; hai người khiêng then ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch13 §III (Chiêu) |  |
| Ch13 | RELATION(Dịch) | Nhận vật tư chống rét; cất tờ kê, không nói; Mới, UNPAID | CANON_FACT | Ch13 §VI |  |
| Ch13 | RELATION(A Quy) | Hoãn, không tha; deadline mùa đông; ACTIVE | CANON_FACT | Ch13 §VI |  |
| Ch15 | LIMIT | Lương: "Lương của ta ở đây đủ tới hết đợt băng tan." | CANON_FACT | Ch15 §I.7 | (Before chưa trích được) |
| Ch15 | STATE | Hoắc quân mất bảy trăm (chết, bị thương, lạc; chưa đếm xong); lui; lương còn sáu ngày trước khi giao hai xe (⚠ xem CB-L-17) | CANON_FACT | Ch15 §I.26; Ch15 §IV | ← Ch13 STATE |
| Ch15 | STATE | Giao hai xe cho cột Ích Châu, ghi sổ lương hội minh; "Ta không đánh Hổ Lao một mình. Ta quay lại." | CANON_FACT | Ch15 §I.26–I.27 |  |
| Ch15 | KNOWLEDGE | Biết: Hổ Lao đã dàn quân đủ; Hoắc quân mất bảy trăm; cột Ích Châu còn ba ngày lương | CANON_FACT | Ch15 §III | (Before chưa trích được) |
| Ch15 | KNOWLEDGE(không biết) | Ai báo tin (nếu có); Bàng đọc bằng cách nào | CANON_UNKNOWN | Ch15 §III |  |
| Ch15 | RELATION(Dịch) | Không nhìn Dịch; quay đi trước; "Hổ Lao còn đó. Hạ Hầu cũng vậy." — "Phải." | CANON_FACT | Ch15 §I.28 | ← Ch13 RELATION(Dịch) |
| Ch15 | RELATION(hội minh) | Lui, quay lại tìm cột; mất bảy trăm — "Mới, không gọi tên" | CANON_FACT | Ch15 §VI |  |
| Ch16 | GOAL | Hoắc quân (qua phó tướng): "Ta không rút khi vừa thua. Cho ta một trận." — Chiêu không phát biểu muốn trận | CANON_FACT | Ch16 §I.7 | ← Ch12 GOAL |
| Ch16 | LIMIT | "Nuôi cả quân ba tuần, ta không nuôi nổi. Nuôi một nửa thì nuôi được." Một nửa Hoắc quân về biên trong ba ngày do phó tướng dẫn; kỵ nhẹ ở lại với nàng ăn lương Ích Châu; hết ba tuần kể từ hôm hội, chưa thấy gì thì nửa còn lại cũng về | CANON_FACT | Ch16 §I.12 |  |
| Ch16 | STATE | Chiêu quyết riêng cho Hoắc quân (CC-2); kiểm sổ lương ba tuần qua thân binh; hỏi "hạn còn hai ngày. Có gì để thấy chưa?" | CANON_FACT | Ch16 §0; Ch16 §I.32; Ch16 §III |  |
| Ch16 | KNOWLEDGE(không biết) | Nội dung toàn văn hồi âm Bàng (chỉ có đội trưởng kỵ nhẹ nghe); Dĩnh Xuyên | CANON_UNKNOWN | Ch16 §III |  |
| Ch17 | GOAL | Việc của Chiêu (kế hoạch Dịch nêu): vây ngoài thành, không công thành, đốt kho bến, ở lại, ở chỗ họ thấy | CANON_FACT | Ch17 §I.5 |  |
| Ch17 | STATE | "Lệnh còn." — hạn hoãn lệnh bắt sống đã hết từ lúc băng tan; một dòng, không tên, không hành động, không nối Dĩnh Xuyên (Canon Update gắn với "Lệnh bắt A Quy" ở §II/§IV) | CANON_FACT | Ch17 §I.1; Ch17 §0; Ch17 §II; Ch17 §IV |  |
| Ch17 | GOAL | Tự quyết làm mồi: "Họ phải nhận ra ta."; "Tiểu Thất. Lấy mũ." | CANON_FACT | Ch17 §I.10 |  |
| Ch17 | LIMIT | Ba điều kiện: (1) chỗ đứng kỵ nhẹ nàng chọn (không trong thành, không dưới đáy cổ chai, không sát nước); (2) mặt trời lặn chưa thấy đèn thuyền ở cọc → đốt một nén hương; hương tàn chưa thấy → rút; nợ lương ghi tên Ích Châu; (3) hết trận kỵ nhẹ về biên, không quá ngày 42; hạn ngày 31 bỏ | CANON_FACT | Ch17 §I.11 |  |
| Ch17 | STATE | Quyết định độc lập: "Không đụng tháp. Để nó cháy."; chọn chỗ thấp phía đông miệng cổ chai; đường rút (bờ đất khô) cũng là đường kỵ Hạ Hầu có thể cắt — nàng không nói ra | CANON_FACT | Ch17 §I.18–I.19 |  |
| Ch17 | STATE | Rạng ngày 35: vây, đốt kho bến; mũ có vết lõm, gãy một chùm lông | CANON_FACT | Ch17 §I.20; Ch17 §0 |  |
| Ch17 | STATE | Ngày 36: ngựa trúng giáo vào ức, quỵ, nàng bị hất xuống; Tiểu Thất nhường ngựa và đứng vào khe; nàng bị rạch dọc cánh tay trái, tự buộc | CANON_FACT | Ch17 §I.27 |  |
| Ch17 | STATE | Cuối Ch17: bị thương cánh tay trái; mất ngựa (đang cưỡi ngựa Tiểu Thất); mũ nguyên (vết lõm, gãy một chùm); mất Tiểu Thất; ở gò thấp phía đông miệng cổ chai; ống hương trong tay áo | CANON_FACT | Ch17 §IV (State Ledger); Ch17 §I.30, §I.37 |  |
| Ch17 | KNOWLEDGE | Biết: đường than (giấy không ở lại); Dĩnh Xuyên là cảng cấp lương, kho, đê, cổ chai, tháp hiệu, đường đồi có đồn; thuyền tới cọc trong một nén hương; viện quân hai khối bị chặn/phá một phần; Tiểu Thất chết; hồi âm chỉ lương (đội trưởng báo); "Lệnh còn." | CANON_FACT | Ch17 §III |  |
| Ch17 | KNOWLEDGE(không biết) | Vì sao Dịch chắc họ sẽ cứu; cách Bàng đọc liên minh; ai chỉ huy viện; Dịch ở đâu trong trận; ý đồ hồi âm; A Quy ở đâu; rò (Ch14) | CANON_UNKNOWN | Ch17 §III |  |
| Ch17 | RELATION(Dịch) | "Tin có điều kiện, đã được giữ (đèn lên đúng cọc, trong hương); chưa nói thành lời" — chuyển động | CANON_FACT | Ch17 §VI |  |
| Ch17 | RELATION(Tiểu Thất) | Chi phí tác chiến; không dựng nhịp riêng — mới | CANON_FACT | Ch17 §VI |  |
| Ch17 | RELATION(Hoắc quân) | Kỵ nhẹ hao ("cánh trái trống nhiều chỗ") — mới | CANON_FACT | Ch17 §VI; Ch17 §I.28 | ← Ch10 RELATION(Hoắc quân) |
| Ch19 | STATE | ngồi trên ngựa Tiểu Thất; tay trái buộc dải vải sẫm; tay áo phải phồng (ống hương) | CANON_FACT | Ch19 §I.4; Ch19 §IV (Chiêu, Vật) | ← Ch17 STATE |
| Ch19 | STATE | kỵ nhẹ lùi xa, đứng yên trên gò thấp, không vào thành; hạn ngày 42 (chưa dùng) | CANON_FACT | Ch19 §I.18, I.21; Ch19 §IV (Chiêu) |  |
| Ch19 | LIMIT | "Ta không ký." / "Kỵ nhẹ của ta không vào thành. Không ai của ta tự vào. Không phải vì tờ giấy." | CANON_FACT | Ch19 §I.12 | ← Ch17 LIMIT |
| Ch19 | KNOWLEDGE(chính mình) | "Có. Chưa chắc." (có cách khác ngoài hạn ngày 42) ⟦ST gốc: "CANON_BELIEF (Chiêu)"⟧ | CANON_BELIEF | Ch19 §I.4 | (Before chưa trích được) |
| Ch19 | KNOWLEDGE | biết: kỵ nhẹ lùi, không vào thành; không ký; hạn 42 (chưa dùng) | CANON_FACT | Ch19 §III (Chiêu) |  |
| Ch19 | KNOWLEDGE | không biết: điều Dịch viết trước khi vào lều | CANON_UNKNOWN | Ch19 §III (Chiêu) |  |
| Ch19 | RELATION(Dịch) | Dịch không xin lỗi, nàng không tha thứ; "Ta biết." | CANON_FACT | Ch19 §I.4, I.12 | ← Ch17 RELATION(Dịch) |
| Ch20–Ch22 | KNOWLEDGE | kỵ nhẹ/hạn 42: Chiêu về biên hay ở lại; có tin phương bắc không | CANON_UNKNOWN | Ch19 §II; Ch20 §IX; Ch21 §II-A; Ch22 §IX |  |
| Ch22 | STATE | không gia hạn, không kỵ Hoắc trên trang | CANON_FACT | Ch22 §0 (Sync Ch17/Ch19) |  |

**(c) PLANNING_NON_CANON**

| Ch | Trường | Nội dung (kế hoạch / author-truth; KHÔNG phải canon trang) | Source Type | Source |
|---|---|---|---|---|
| Ch01 | STATE (đề xuất) | Chapter Bible Ch6: "Chiêu trở thành Hoắc Tam Lang" → đề xuất sửa "Hoắc Tam Lang tiếp nhận quyền lãnh đạo Hoắc gia quân" (chờ duyệt; Ch6 không ghi rõ đã duyệt) | PLANNING_NON_CANON | Ch01 §II; Ch03 §VIII; Ch05 §VIII.7 |
| Ch06 | STATE (Chapter Bible cost, "đã đổi") | → mất người cuối cùng gọi nàng bằng tên thật; "Hoắc Tam Lang" là danh phận duy nhất nàng có thể công khai sống bằng | PLANNING_NON_CANON | Ch06 §VI |
| Ch13 | KNOWLEDGE | Nhận lời báo Dạ Kiêu: author-truth, không lên trang | PLANNING_NON_CANON | Ch13 §III (Chiêu) |
| Ch17 | GOAL | (author-truth, không lên trang) "Ở Dĩnh Xuyên, Dịch làm cho người kia chỉ còn một con đường để đọc, và Chiêu đứng ở cuối con đường ấy" | PLANNING_NON_CANON | Ch17 §Nguyên tắc ghi |
| Ch10 | RELATION(Chu Hạc) | nhãn "tới Ch29" của nợ Chiêu–Chu Hạc (Canon Update ghi ở file seeds) | PLANNING_NON_CANON | Ch10 §VI |

### 3.5 TẠ VÂN CHƯƠNG <a id="nv-vc"></a>

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE | (đầu dải) → hiện diện gián tiếp: ngồi xe thứ hai, ho, "không chịu được gió"; chưa tính xuất hiện trực tiếp | Ch01 | CANON_FACT | Ch01 §I.12 |
| APPEARANCE | → xuất hiện trực tiếp lần đầu: trẻ, gầy, da trắng gần như không còn màu máu, áo lông, lò sưởi tay bằng đồng; tự xưng "Tạ mỗ" | Ch03 | CANON_FACT | Ch03 §I.35 |
| APPEARANCE | vắng: "Không xác định trong Ch6" | Ch06 | CANON_UNKNOWN | Ch06 §IV |
| APPEARANCE | vắng: "Không xác định trong Ch7" | Ch07 | CANON_UNKNOWN | Ch07 §IV |
| APPEARANCE | Vắng (chỉ được nhắc qua tin trạm) | Ch08 | CANON_FACT | Ch08 §I.6 |
| APPEARANCE | Có mặt, không POV: chào Dịch đúng lễ chào sứ thần; áo quan màu tím; ho (khi viên quan Kim Lăng nhìn chàng) | Ch12 | CANON_FACT | Ch12 §I.8, I.10 |
| APPEARANCE | POV đoạn V (cuối chương); có mặt ở đoạn III (thuyền Kim Lăng) | Ch13 | CANON_FACT | Ch13 §Nguyên tắc ghi, §I.III, §I.V |
| APPEARANCE | first trong dải; không POV; xuất hiện ở bờ lau (T4) và qua lời nhắn qua người đi bến | Ch14 | CANON_FACT | Ch14 §I.2, §I.6, §I.20 |
| APPEARANCE | vắng | Ch15–Ch17 | CANON_FACT | Ch15 §III; Ch16 §III; Ch17 §III |
| APPEARANCE | vắng khỏi trang; chỉ "nhận thư + gói, ngoài trang" (Canon Update tự ghi) | Ch18 | CANON_FACT | Ch18 §III |
| APPEARANCE | vắng (không xuất hiện) | Ch19 | CANON_FACT | Ch19 §III |
| APPEARANCE | POV toàn chương (narration "Vân Chương"/"chàng") | Ch20 | CANON_FACT | Ch20 §Nguyên tắc ghi |
| APPEARANCE | POV toàn chương | Ch21 | CANON_FACT | Ch21 §Nguyên tắc ghi |
| APPEARANCE | vắng (Ch22 không POV; không xuất hiện) | Ch22 | CANON_FACT | Ch22 §III; Ch22 §VI (Vân Chương) |
| GOAL | → hiểu chỗ khác thường trong thư (23 tháng Chạp) | Ch04 | CANON_FACT | Ch04 §VI |
| FEAR/WEAKNESS | ho: một cơn ngắn → cơn dài che bằng tay áo → khô và dài; "ho nặng hơn (chưa máu, chưa ngất)"; thầy thuốc: "nên nghỉ ba ngày" — "Mai." | Ch20 | CANON_FACT | Ch20 §I.1, I.9, I.18–19; Ch20 §IV (Vân Chương) |
| FEAR/WEAKNESS | ho: bút rơi một lần; thư lại ghi thay từ đêm thứ ba; gói vỏ quýt còn một nắm; "chưa máu, chưa ngất"; tay đặt ngăn kéo, không kéo | Ch21 | CANON_FACT | Ch21 §I.16, I.19, I.21; Ch21 §IV (Vân Chương) |
| LIMIT | "đây là văn thư của Kim Lăng, và Kim Lăng chưa công nhận Dịch" | Ch13 | CANON_FACT | Ch13 §I.30 |
| RELATION(Chỉ) | Nhận hai chỗ hẹn; "Lần sau, báo một chỗ." | Ch14 | CANON_FACT | Ch14 §I.20 |
| RELATION(Dịch) | nợ mới: chiếu nêu tên Dịch, không báo trước — ACTIVE | Ch20 | CANON_FACT | Ch20 §VI |
| RELATION(triều Kim Lăng) | ba nhóm nhượng một phần; ông áo tía không hài lòng (đứng yên khi chào chiếu); hôn thư đóng ấn cùng ngày | Ch20 | CANON_FACT | Ch20 §IV (Triều Kim Lăng); Ch20 §I.13, I.15 |
| RELATION(quan huyện vô danh) | nợ mới: chiếu → cái chết (hai dòng, không nối nhân quả) — ACTIVE | Ch20 | CANON_FACT | Ch20 §VI; Ch20 §I.18 |
| RELATION(chính mình) | nợ mới: không rời Kim Lăng — ACTIVE | Ch20 | CANON_FACT | Ch20 §VI |
| RELATION(Chỉ/người đi bến) | dùng chỗ hẹn gọi người đi bến; "Một lời." vs "gửi năm lời" (Chỉ); chàng không hỏi khi hắn đứng thêm một nhịp | Ch21 | CANON_FACT | Ch21 §I.8–10; Ch21 §0 (Sync Ch14) |
| RELATION(liên quân) | nợ mới: dùng họ mà không nói (điều (2), lịch lương không giải thích) — ACTIVE | Ch21 | CANON_FACT | Ch21 §VI |
| RELATION(tướng giữ Hổ Lao) | nợ mới: nhận bằng chữ một điều có thể không giữ được — ACTIVE | Ch21 | CANON_FACT | Ch21 §VI |
| RELATION(thủy quân/phó tướng) | nợ mới: đặt thuyền neo ngang sông, không biết bên kia đọc ra sao — ACTIVE | Ch21 | CANON_FACT | Ch21 §VI |
| RELATION(Kim Lăng) | nợ mới: lương thật xuất kho nửa tháng; thất bại thì liên minh tan | Ch21 | CANON_FACT | Ch21 §VI |
| RELATION(Uyển) | không thư; không đáp; gói vỏ quýt còn một nắm | Ch21 | CANON_FACT | Ch21 §I.19; Ch21 §II-A; Ch21 §VI |
| STATE | thư Hổ Lao (3 điều) đã đáp: tự viết, "Dấu của ta.", "Không." (không vào sổ), không chép bản; đáp "Nhận ba điều." / "Đêm hẹn: đêm thứ sáu kể từ đêm nay." | Ch21 | CANON_FACT | Ch21 §I.14–17; Ch21 §IV (Thư Hổ Lao, Điều (2)) |
| STATE | lương thật xuất kho (số suất gấp ba số thủy thủ; sổ gạch nửa tháng lương); thuyền rời bến Kim Lăng; chàng không ra bến | Ch21 | CANON_FACT | Ch21 §I.11, I.18; Ch21 §IV (Lương) |
| STATE | lịch lương (ngày–lương–đường) + lời miệng "Tới bến thì neo ngang sông. Một đêm." giao thủy quân; "Ngày ta tự viết." nét cuối run | Ch21 | CANON_FACT | Ch21 §I.12 |
| KNOWLEDGE | Chỉ báo "Đường văn thư – trạm ngựa Kim Lăng có lỗ."; Chỉ đã thử hai tuyến Kim Lăng (miệng: T4 trực tiếp; giấy: T5) | Ch14 | CANON_FACT | Ch14 §I.18; Ch14 §III |
| KNOWLEDGE | Dĩnh Xuyên mở từ bên trong; tờ văn ký "Trình Dịch, sứ Ích Châu" không ấn; Chiêu không vào thành; Hổ Lao còn Hạ Hầu; thư Uyển "một bộ trái lời, đã xử, trướng giữ"; chiếu đóng ấn đi hai đường; một quan huyện đọc chiếu rồi bị Hạ Hầu xử (chỉ hai việc); một tướng giữ Hổ Lao xin hàng | Ch20 | CANON_FACT | Ch20 §III (Vân Chương); Ch20 §I.2–4, I.17, I.22–23 |
| KNOWLEDGE | ba điều của thư; độ trễ trạm hở ba ngày; lệnh lương đi trạm, lương xuất kho, thuyền đã đi; báo cũ "thuyền neo ngang sông; Hổ Lao dồn quân ra phía bến"; "Cổng thành mở." | Ch21 | CANON_FACT | Ch21 §III (Vân Chương); Ch21 §I.2, I.9, I.22, I.25 |
| KNOWLEDGE (vẫn tin rất cao, chưa xác nhận, từ Ch4) | Dịch có liên hệ với Thẩm chiêu nghi | Ch05 | CANON_BELIEF | Ch05 §III |
| KNOWLEDGE | Ý nghĩ: "Ở Kim Lăng, không ai hỏi người ở Ích Châu thật hay giả. Người ta chỉ hỏi ai sẽ ngồi ở đâu." ⟦ST gốc: "CANON_BELIEF (Vân Chương)"⟧ | Ch13 | CANON_BELIEF | Ch13 §I.31 |
| KNOWLEDGE | Dịch suy (cột INFERENCE, Ch12 §III): chàng không nhìn chỗ Uyển–Tam Lang "như người đã quen" | Ch12 | CANON_SUSPICION | Ch12 §III (Dịch/Vân Chương) |
| KNOWLEDGE(Uyển) | Vân Chương suy (Ch20 §I.4): "một bộ, không phải nhiều" | Ch20 | CANON_SUSPICION | Ch20 §I.4; Ch20 §III (Vân Chương) |
| KNOWLEDGE | Vân Chương suy, một mức (Ch21 §III, cột "INFERENCE (một mức)"): "Thư riêng đã tới tay người giữ chức" — cùng ô §III cũng liệt câu này ở phần "FACT"; §I.4 narration nêu như dữ kiện; §0 ghi "xác nhận … chỉ ở mức Hổ Lao" ⚠ xem CB-L-20 (chưa quyết; không gắn FACT) | Ch21 | CANON_SUSPICION | Ch21 §III (Vân Chương); Ch21 §I.4; Ch21 §0 |
| KNOWLEDGE(không biết) | Phản ứng của Kim Lăng/Vân Chương với thư ngắn + gói vỏ quýt: OPEN | Ch18 | CANON_UNKNOWN | Ch18 §II |
| KNOWLEDGE | không biết: thật/trá thư xin hàng; vì sao quan huyện bị xử; thư riêng tới tay ai; Dịch phản ứng; Ôn; Hách Liên tập quân; nguồn rò; Kha Trọng; chuỗi người mở cổng Dĩnh Xuyên; muối vượt trần; Chiêu "Ta không ký"; ai trong triều báo Hạ Hầu | Ch20 | CANON_UNKNOWN | Ch20 §III (Vân Chương); Ch20 §II |
| KNOWLEDGE | không biết: thật/trá của thư; ai mở cổng, vì sao; người bên kia ở đâu; bẫy hay thắng; thư có bị chép không; Dịch/Hàn/Chiêu làm gì (có đọc lịch lương không); G là ai, số phận G; tên Bàng; nguồn rò; Kha Trọng; K2; Hách Liên; Uyển nghĩ gì | Ch21 | CANON_UNKNOWN | Ch21 §III (Vân Chương) |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch01 | STATE | (đầu dải) → trong thành cùng đoàn; sức khỏe kém vì gió lạnh | CANON_FACT | Ch01 §VI |  |
| Ch03 | STATE | → nhớ số liệu của đoàn không cần mở sổ; đề nghị ghi "đoàn hòa thân hoàn trả phần dư"; có bàn cờ gỗ gấp (mất quân trắng "dọc đường", bổ sung bằng quân của Dịch); chờ Uyển học ngựa trong phòng trực vì không chịu được gió | CANON_FACT | Ch03 §I.36–39 |  |
| Ch03 | KNOWLEDGE (quan sát) | thói quen đỡ tay áo của Dịch (lệch hình ảnh thư lại); dáng đi và cổ chân băng của A Quy; A Quy là người bị phạt. "Nghi ngờ ≠ biết. Chưa có kết luận nào về Dịch." | CANON_SUSPICION | Ch03 §III (TẠ VÂN CHƯƠNG) |  |
| Ch04 | STATE (nền) | → từng theo cha vào cung vài lần khi nhỏ; nhớ hành lang, dáng bước, dáng cúi của người hầu nội đình, không nhớ mặt ai | CANON_FACT | Ch04 §I.6 |  |
| Ch04 | KNOWLEDGE (công khai) | → năm -21 Thẩm chiêu nghi bị kết tội; con trai bà sáu tuổi biến mất khỏi cung trong đêm; không tìm thấy xác | CANON_FACT | Ch04 §I.7 |  |
| Ch04 | KNOWLEDGE | → chữ "Huệ" trong tên Thẩm chiêu nghi bị người hầu kẻ hạ tránh bằng cách bỏ một nét | CANON_FACT | Ch04 §I.8 |  |
| Ch04 | STATE | → ra Bắc Môn xem đường (ngày 20); thấy cảnh Phùng thúc cúi thấp; không nhận ra danh tính; Dịch và Phùng thúc không thấy xe chàng | CANON_FACT | Ch04 §I.10–15 |  |
| Ch04 | STATE | → nói "Chữ này, lần sau Thẩm thư lại viết đủ nét ngay từ đầu…" (phép thử, ngày 21) | CANON_FACT | Ch04 §I.20 |  |
| Ch04 | STATE | → viết chữ "Thẩm" trong thư gửi cha rồi đốt tờ giấy; thư viết lại không nhắc Dịch; thư nhà gửi mười ngày một lần, chưa lỡ lần nào | CANON_FACT | Ch04 §I.21–22 |  |
| Ch04 | STATE | → đánh giữ quân (khác lối bỏ quân), thua bảy mục (chủ ý: không xác định) | CANON_FACT | Ch04 §I.30 |  |
| Ch04 | STATE | → ho nặng hơn (tháng Mười một–Chạp); nhận thuốc sắc vỏ quýt từ thị nữ của Uyển | CANON_FACT | Ch04 §I.32–33 |  |
| Ch04 | KNOWLEDGE (biết, quan sát) | Dịch mang họ Thẩm, khoảng mười bảy tuổi, khớp một phần hồ sơ cũ; thói quen đỡ tay áo; người ở cùng Dịch gợi nhớ người hầu nội đình; phản xạ dừng nét "Huệ"; Dịch tự dựng lại lượng tồn kho (tám xe hụt, chuyến 11 đủ); Dịch không tránh mình; nhà Dịch cửa thứ hai ngõ sát tường bắc | CANON_FACT | Ch04 §III (TẠ VÂN CHƯƠNG) |  |
| Ch04 | KNOWLEDGE (tin rất cao, chưa xác nhận) | Dịch có liên hệ trực tiếp với Thẩm chiêu nghi; Dịch chính là con trai Thẩm chiêu nghi (Thất hoàng tử) | CANON_BELIEF | Ch04 §III |  |
| Ch04 | KNOWLEDGE (tự nêu cách giải thích khác) | họ Thẩm không hiếm; người rời cung về quê không hiếm; con của người từng hầu trong cung cũng có thể được dạy tránh chữ "Huệ" | CANON_SUSPICION | Ch04 §III |  |
| Ch04 | KNOWLEDGE (chưa có) | giấy tờ; nhân chứng độc lập; vật chứng; người xác nhận trực tiếp | CANON_UNKNOWN | Ch04 §III |  |
| Ch04 | KNOWLEDGE (không biết) | Phùng thúc là ai; ai đưa đứa trẻ ra cung; Dịch có biết thân phận thật không; vai trò thật của Tạ Diên năm -21; Bùi gia; ai rút lương; Bắc Môn; Chu Hạc; ý nghĩa Dịch đỡ tay áo ở S4; nội dung đầy đủ thư cha | CANON_UNKNOWN | Ch04 §III |  |
| Ch04 | GOAL | → hiểu chỗ khác thường trong thư (23 tháng Chạp) | CANON_FACT | Ch04 §VI |  |
| Ch05 | STATE | → được cha đưa bộ sử chép tay 12 quyển năm lên bảy ("Muốn đọc thư của cha thì phải thuộc nó trước"); mang theo, cất đáy rương bọc vải xanh | CANON_FACT | Ch05 §I.1 |  |
| Ch05 | STATE | → giải mười chữ đêm 23 tháng Chạp gần canh ba (Trừ tịch. Tý. Bắc. Môn. Bất quan. Nhi. Xuất. Nam. Vật. Lưu.); đốt mảnh giấy chép trước sáng | CANON_FACT | Ch05 §I.4–6 |  |
| Ch05 | STATE | → viết "Hoắc tướng quân…" rồi dừng, kẹp vào quyển bảy; đêm 30 lấy ra, viết thêm một dòng (nội dung: chưa Canon), cầm trong tay tới chính Tý, chưa tới tay Hoắc | CANON_FACT | Ch05 §I.7–10 |  |
| Ch05 | STATE | → ngày 24 trình Uyển cớ vọng bái; ngày 25 Tri phủ chỉ cấp lệnh bài cho danh sách (công chúa, thị nữ, hộ vệ Mạnh tướng quân, phó sứ); ra Nam Môn chạng vạng 30, vào lại sáng mùng một, không cho vào ban đêm | CANON_FACT | Ch05 §I.11–14 |  |
| Ch05 | STATE | → mời "chư vị" ra miếu (Tam Lang từ chối một lần, Dịch hai lần; A Quy không được mời, chàng nhận ra mình không tính tới hắn và không sửa) | CANON_FACT | Ch05 §I.20–23 |  |
| Ch05 | STATE | → đầu giờ Hợi ra lệnh Mạnh tướng quân "Giữ công chúa ở đây tới sáng…"; nói với Uyển "Tạ mỗ quên một thứ ở dịch quán"; rời miếu cùng một tùy tùng; vào Nam Môn qua cửa ngách cho một người; tùy tùng ở lại ngoài | CANON_FACT | Ch05 §I.28–32 |  |
| Ch05 | STATE (chính Tý) | → giữa phố lớn, chưa qua chợ và miếu Thành Hoàng, một mình dắt ngựa, đang ho, cầm thư; nghe âm thanh trầm, dài, không dứt từ phía bắc (chưa biết là gì) | CANON_FACT | Ch05 §I.33–35, §V |  |
| Ch05 | KNOWLEDGE (biết, từ thư) | đêm trừ tịch giờ Tý cửa Bắc không đóng; cha muốn con ra cửa Nam, không ở lại; cha đã biết trước ngày giờ | CANON_FACT | Ch05 §III (TẠ VÂN CHƯƠNG) |  |
| Ch05 | KNOWLEDGE (suy luận) | Vân Chương suy (cột "SUY LUẬN", Ch05 §III): có người bên trong; Tạ gia có liên quan; cha biết con còn ở Vân Trung nhờ thư nhà của chính con | CANON_SUSPICION | Ch05 §III |  |
| Ch05 | FEAR/WEAKNESS | sợ Dịch ở sát Bắc Môn (không phải thông tin) | CANON_FACT | Ch05 §III |  |
| Ch05 | KNOWLEDGE (vẫn tin rất cao, chưa xác nhận, từ Ch4) | Dịch có liên hệ với Thẩm chiêu nghi | CANON_BELIEF | Ch05 §III |  |
| Ch05 | KNOWLEDGE (biết, quan sát) | Tam Lang, Hoắc, Dịch, Phùng thúc, A Quy đều trong thành đêm trừ tịch; phu xe của đoàn ở dịch quán | CANON_FACT | Ch05 §III |  |
| Ch05 | KNOWLEDGE (không biết) | ai mở cửa; ai vào; quy mô; mục tiêu; Chu Hạc; Bắc Nhung; Tạ Diên có tìm Dịch hay không | CANON_UNKNOWN | Ch05 §III |  |
| Ch07 | STATE | "Vân Chương ở đâu đêm ấy"; có gặp Uyển đêm ấy không | CANON_UNKNOWN | Ch07 §IX |  |
| Ch08 | STATE | (đầu dải) → phò ấu chủ ra khỏi kinh thành, xuôi về Kim Lăng (tin trạm; Canon Update ghi "Đã payoff (tin trạm)") | CANON_FACT | Ch08 §I.6, §V | ← Ch07 STATE |
| Ch08 | KNOWLEDGE | CHƯA nhận tin "Thất hoàng tử ở Ích Châu"; chuỗi suy luận năm 0 (Gate) chưa bắt đầu | CANON_UNKNOWN | Ch08 §III (TẠ VÂN CHƯƠNG) | ← Ch05 KNOWLEDGE |
| Ch08 | RELATION(Dịch) | Món nợ Vân Chương → Dịch (nhãn Canon Update: "(Gate)"): "Ta đã có thể đi tìm… Ta đã chọn không đi." — UNPAID | CANON_FACT | Ch08 §VI |  |
| Ch09 | RELATION(Dịch) | Món nợ trên: UNPAID, không đổi | CANON_FACT | Ch09 §VI |  |
| Ch12 | KNOWLEDGE | Chuỗi suy luận về Dịch hoàn tất NGOÀI MÀN trước Ch12 (Gate Ch8 §6: "xảy ra ở chương POV Vân Chương đầu tiên Quyển II" → "hoàn tất ngoài màn trước Ch12; Ch13 chỉ thể hiện kết quả nhận thức; không flashback") [CANON CHANGE CC-1] | CANON_FACT | Ch12 §0B (CC-1), §III (Vân Chương) |  |
| Ch12 | KNOWLEDGE | Tam Lang là nữ: trước Ch12 → nghi, chưa xác nhận | CANON_SUSPICION | Ch12 §III (Những người khác — Vân Chương) |  |
| Ch12 | KNOWLEDGE | Tam Lang là nữ: nghi → "nay đã được xác nhận" (sau câu "Người hứa là Hoắc Chiêu." chàng cúi mắt) | CANON_FACT | Ch12 §III, §I.29 |  |
| Ch12 | STATE | Nói thay Kim Lăng: "Việc phụng chiếu, để sau mùa đông. Kim Lăng chưa công nhận ai." (không nhìn Dịch khi nói); chưa công nhận Dịch; việc phụng chiếu gác tới sau mùa đông | CANON_FACT | Ch12 §I.24, §IV |  |
| Ch12 | STATE | Đứng tên cho cuộc bàn; hứa đưa tin, phối hợp đường lương | CANON_FACT | Ch12 §I.24 |  |
| Ch12 | RELATION(Uyển) | Nhìn ngọn đèn "như người đã quen không nhìn" khi Uyển ngồi sát Tam Lang | CANON_FACT | Ch12 §I.27 |  |
| Ch12 | KNOWLEDGE | Dịch suy (cột INFERENCE, Ch12 §III): chàng không nhìn chỗ Uyển–Tam Lang "như người đã quen" | CANON_SUSPICION | Ch12 §III (Dịch/Vân Chương) |  |
| Ch12 | KNOWLEDGE | Tình cảm Uyển–Vân Chương: Dịch không biết | CANON_UNKNOWN | Ch12 §III (Dịch/Uyển) |  |
| Ch12 | RELATION(Dịch) | Gate VC "chọn không tìm" → nay chọn chưa công nhận; ACTIVE, không nói ra | CANON_FACT | Ch12 §VI |  |
| Ch13 | KNOWLEDGE | Biết: tin giả; lời báo Dạ Kiêu; viên quan Kim Lăng gửi ngựa trước giờ Ngọ, không hỏi chàng; chính chàng đã viết "người tự nhận" | CANON_FACT | Ch13 §III (Vân Chương), §I.27–29 |  |
| Ch13 | KNOWLEDGE | "Chàng biết người ấy là ai." (narration; Canon Update ghi đây là bản v2 sau khi bỏ câu "đã biết từ trước khi rời Kim Lăng") | CANON_FACT | Ch13 §I.30, §0 (Tightening v2) |  |
| Ch13 | LIMIT | "đây là văn thư của Kim Lăng, và Kim Lăng chưa công nhận Dịch" | CANON_FACT | Ch13 §I.30 |  |
| Ch13 | KNOWLEDGE | Ý nghĩ: "Ở Kim Lăng, không ai hỏi người ở Ích Châu thật hay giả. Người ta chỉ hỏi ai sẽ ngồi ở đâu." ⟦ST gốc: "CANON_BELIEF (Vân Chương)"⟧ | CANON_BELIEF | Ch13 §I.31 |  |
| Ch13 | KNOWLEDGE | Không biết: ai rò tin; viên quan gửi cho ai (chỉ "Gửi về triều") | CANON_UNKNOWN | Ch13 §III (Vân Chương), §I.29 |  |
| Ch13 | STATE | Viết thư gửi triều ("Kim Lăng chưa công nhận ai. Người ở Ích Châu vẫn là người tự nhận."), ngòi bút dừng ở "tự nhận"; ký, ấn, niêm; không sai người sang doanh Ích Châu; ho một lần | CANON_FACT | Ch13 §I.30, I.32 |  |
| Ch13 | RELATION(Uyển) | Uống chén nước vỏ quýt, không cảm ơn, không nhắc; nhìn nàng lâu như có câu hỏi, Uyển đứng dậy trước, câu hỏi không nói ra; hỏi nàng "Trướng Khả đôn giữ được bao nhiêu người qua mùa đông?" — "Giữ được những người theo ta." | CANON_FACT | Ch13 §I.16–18, §VI |  |
| Ch13 | RELATION(Dịch) | Viết "người tự nhận" dù biết; không báo Dịch — Mới, ACTIVE | CANON_FACT | Ch13 §VI |  |
| Ch13 | KNOWLEDGE | Có thể phải phản bội Dịch: Đã gieo, CHƯA QUYẾT | CANON_UNKNOWN | Ch13 §V (New info) |  |
| Ch14 | STATE | Ho một lần; nhắc lại "Đêm mười lăm. Lò gạch bỏ. Từ canh hai."; không hỏi vì sao | CANON_FACT | Ch14 §I.6 | ← Ch13 STATE |
| Ch14 | KNOWLEDGE | Chỉ báo "Đường văn thư – trạm ngựa Kim Lăng có lỗ."; Chỉ đã thử hai tuyến Kim Lăng (miệng: T4 trực tiếp; giấy: T5) | CANON_FACT | Ch14 §I.18; Ch14 §III | ← Ch13 KNOWLEDGE |
| Ch14 | KNOWLEDGE(không biết) | Vì sao Chỉ chọn Kim Lăng; Chỉ nghi ai (G-3); Kha Trọng | CANON_UNKNOWN | Ch14 §III |  |
| Ch14 | RELATION(Chỉ) | Nhận hai chỗ hẹn; "Lần sau, báo một chỗ." | CANON_FACT | Ch14 §I.20 |  |
| Ch14 | RELATION(Dịch) | Debt "Viết 'người tự nhận' (Ch13)" — ACTIVE (không đổi) | CANON_FACT | Ch14 §VI | ← Ch13 RELATION(Dịch) |
| Ch14 | KNOWLEDGE(không biết) | Vân Chương có làm gì với hai chỗ hẹn; vì sao nhận cả hai; chàng nghĩ gì | CANON_UNKNOWN | Ch14 §II |  |
| Ch18 | RELATION(Uyển) | Gói vỏ quýt khô "đi sau" thư; câu chàng không hỏi — ACTIVE, không gọi tên (tên Vân Chương không có trên trang) | CANON_FACT | Ch18 §VI; Ch18 §I.24 | ← Ch13 RELATION(Uyển) |
| Ch18 | KNOWLEDGE(không biết) | Phản ứng của Kim Lăng/Vân Chương với thư ngắn + gói vỏ quýt: OPEN | CANON_UNKNOWN | Ch18 §II |  |
| Ch20 | STATE | không rời Kim Lăng; nắm ấn tước/chứng ấn; quan giữ ấn: "Hạ quan chỉ giữ ấn, không chứng." | CANON_FACT | Ch20 §IV (Triều/Vân Chương); Ch20 §I.20 | ← Ch14 STATE |
| Ch20 | STATE | thủ tục: đứng thấp hơn ngai một bậc, đọc chiếu; đóng ấn lên từng bản phong tước | CANON_FACT | Ch20 §I.10, I.16 |  |
| Ch20 | STATE | dùng đường trạm hở có chủ ý cho bản công khai; không truy nguồn, không nêu K2/Kha Trọng | CANON_FACT | Ch20 §I.16; Ch20 §0 (Sync Ch14) |  |
| Ch20 | FEAR/WEAKNESS | ho: một cơn ngắn → cơn dài che bằng tay áo → khô và dài; "ho nặng hơn (chưa máu, chưa ngất)"; thầy thuốc: "nên nghỉ ba ngày" — "Mai." | CANON_FACT | Ch20 §I.1, I.9, I.18–19; Ch20 §IV (Vân Chương) | ← Ch04 STATE (ho nặng hơn tháng Mười một–Chạp) |
| Ch20 | STATE | uống hết bát nước vỏ quýt; tờ "Xin ra tuyến trước, Lạc Thủy." gấp, cất ngăn kéo cùng tờ giấy Hán của Uyển | CANON_FACT | Ch20 §I.20–21 |  |
| Ch20 | RELATION(Dịch) | không gửi một dòng riêng: "Chiếu đi đường nào thì đi đường ấy."; chiếu "nhận việc, không nhận người" | CANON_FACT | Ch20 §I.6, I.8; Ch20 §0 (Sync Ch13) | ← Ch14 RELATION(Dịch) |
| Ch20 | RELATION(Dịch) | nợ mới: chiếu nêu tên Dịch, không báo trước — ACTIVE | CANON_FACT | Ch20 §VI |  |
| Ch20 | RELATION(Uyển) | nhận chữ trước khi đọc nghĩa; đọc hai lần; cất ngăn kéo; "Không." (không thư đáp); không đáp, không nhắc | CANON_FACT | Ch20 §I.4, I.21 | ← Ch18 RELATION(Uyển) |
| Ch20 | RELATION(triều Kim Lăng) | ba nhóm nhượng một phần; ông áo tía không hài lòng (đứng yên khi chào chiếu); hôn thư đóng ấn cùng ngày | CANON_FACT | Ch20 §IV (Triều Kim Lăng); Ch20 §I.13, I.15 |  |
| Ch20 | RELATION(quan huyện vô danh) | nợ mới: chiếu → cái chết (hai dòng, không nối nhân quả) — ACTIVE | CANON_FACT | Ch20 §VI; Ch20 §I.18 |  |
| Ch20 | RELATION(chính mình) | nợ mới: không rời Kim Lăng — ACTIVE | CANON_FACT | Ch20 §VI |  |
| Ch20 | KNOWLEDGE | Dĩnh Xuyên mở từ bên trong; tờ văn ký "Trình Dịch, sứ Ích Châu" không ấn; Chiêu không vào thành; Hổ Lao còn Hạ Hầu; thư Uyển "một bộ trái lời, đã xử, trướng giữ"; chiếu đóng ấn đi hai đường; một quan huyện đọc chiếu rồi bị Hạ Hầu xử (chỉ hai việc); một tướng giữ Hổ Lao xin hàng | CANON_FACT | Ch20 §III (Vân Chương); Ch20 §I.2–4, I.17, I.22–23 | ← Ch18 KNOWLEDGE |
| Ch20 | KNOWLEDGE(Uyển) | Vân Chương suy (Ch20 §I.4): "một bộ, không phải nhiều" | CANON_SUSPICION | Ch20 §I.4; Ch20 §III (Vân Chương) |  |
| Ch20 | KNOWLEDGE | không biết: thật/trá thư xin hàng; vì sao quan huyện bị xử; thư riêng tới tay ai; Dịch phản ứng; Ôn; Hách Liên tập quân; nguồn rò; Kha Trọng; chuỗi người mở cổng Dĩnh Xuyên; muối vượt trần; Chiêu "Ta không ký"; ai trong triều báo Hạ Hầu | CANON_UNKNOWN | Ch20 §III (Vân Chương); Ch20 §II |  |
| Ch21 | STATE | thư Hổ Lao (3 điều) đã đáp: tự viết, "Dấu của ta.", "Không." (không vào sổ), không chép bản; đáp "Nhận ba điều." / "Đêm hẹn: đêm thứ sáu kể từ đêm nay." | CANON_FACT | Ch21 §I.14–17; Ch21 §IV (Thư Hổ Lao, Điều (2)) |  |
| Ch21 | STATE | lương thật xuất kho (số suất gấp ba số thủy thủ; sổ gạch nửa tháng lương); thuyền rời bến Kim Lăng; chàng không ra bến | CANON_FACT | Ch21 §I.11, I.18; Ch21 §IV (Lương) |  |
| Ch21 | STATE | lịch lương (ngày–lương–đường) + lời miệng "Tới bến thì neo ngang sông. Một đêm." giao thủy quân; "Ngày ta tự viết." nét cuối run | CANON_FACT | Ch21 §I.12 |  |
| Ch21 | FEAR/WEAKNESS | ho: bút rơi một lần; thư lại ghi thay từ đêm thứ ba; gói vỏ quýt còn một nắm; "chưa máu, chưa ngất"; tay đặt ngăn kéo, không kéo | CANON_FACT | Ch21 §I.16, I.19, I.21; Ch21 §IV (Vân Chương) |  |
| Ch21 | RELATION(Chỉ/người đi bến) | dùng chỗ hẹn gọi người đi bến; "Một lời." vs "gửi năm lời" (Chỉ); chàng không hỏi khi hắn đứng thêm một nhịp | CANON_FACT | Ch21 §I.8–10; Ch21 §0 (Sync Ch14) |  |
| Ch21 | RELATION(liên quân) | nợ mới: dùng họ mà không nói (điều (2), lịch lương không giải thích) — ACTIVE | CANON_FACT | Ch21 §VI |  |
| Ch21 | RELATION(tướng giữ Hổ Lao) | nợ mới: nhận bằng chữ một điều có thể không giữ được — ACTIVE | CANON_FACT | Ch21 §VI |  |
| Ch21 | RELATION(thủy quân/phó tướng) | nợ mới: đặt thuyền neo ngang sông, không biết bên kia đọc ra sao — ACTIVE | CANON_FACT | Ch21 §VI |  |
| Ch21 | RELATION(Kim Lăng) | nợ mới: lương thật xuất kho nửa tháng; thất bại thì liên minh tan | CANON_FACT | Ch21 §VI |  |
| Ch21 | RELATION(Uyển) | không thư; không đáp; gói vỏ quýt còn một nắm | CANON_FACT | Ch21 §I.19; Ch21 §II-A; Ch21 §VI |  |
| Ch21 | KNOWLEDGE | ba điều của thư; độ trễ trạm hở ba ngày; lệnh lương đi trạm, lương xuất kho, thuyền đã đi; báo cũ "thuyền neo ngang sông; Hổ Lao dồn quân ra phía bến"; "Cổng thành mở." | CANON_FACT | Ch21 §III (Vân Chương); Ch21 §I.2, I.9, I.22, I.25 |  |
| Ch21 | KNOWLEDGE | Vân Chương suy, một mức (Ch21 §III, cột "INFERENCE (một mức)"): "Thư riêng đã tới tay người giữ chức" — cùng ô §III cũng liệt câu này ở phần "FACT"; §I.4 narration nêu như dữ kiện; §0 ghi "xác nhận … chỉ ở mức Hổ Lao" ⚠ xem CB-L-20 (chưa quyết; không gắn FACT) | CANON_SUSPICION | Ch21 §III (Vân Chương); Ch21 §I.4; Ch21 §0 |  |
| Ch21 | KNOWLEDGE | không biết: thật/trá của thư; ai mở cổng, vì sao; người bên kia ở đâu; bẫy hay thắng; thư có bị chép không; Dịch/Hàn/Chiêu làm gì (có đọc lịch lương không); G là ai, số phận G; tên Bàng; nguồn rò; Kha Trọng; K2; Hách Liên; Uyển nghĩ gì | CANON_UNKNOWN | Ch21 §III (Vân Chương) |  |

**(c) PLANNING_NON_CANON**

| Ch | Trường | Nội dung (kế hoạch / author-truth; KHÔNG phải canon trang) | Source Type | Source |
|---|---|---|---|---|
| Ch07 | KNOWLEDGE (về Dịch; Canon Update ghi "ĐÃ KHÓA (Gate trước Ch8)", chưa lên trang) | biết nhà cháy, Hộ phòng ghi mất tích, không có xác, Nam Môn từng mở; KHÔNG CHẮC Dịch sống/chết; chọn không tìm (Phương án C) | PLANNING_NON_CANON | Ch07 §III (NGƯỜI KHÁC VỀ DỊCH), §IX |
| Ch07 | STATE (author-truth Gate trước Ch8) | ở lại Vân Trung ít nhất vài ngày sau mùng một | PLANNING_NON_CANON | Ch07 §IV, §IX |
| Ch18 | KNOWLEDGE | chỉ dấu chương: phản ứng Kim Lăng / Vân Chương với thư + gói "→ Ch20" | PLANNING_NON_CANON | Ch18 §II |
| Ch21 | RELATION(liên quân) | chỉ dấu chương: nợ "dùng họ mà không nói" "→ Ch23" | PLANNING_NON_CANON | Ch21 §VI |

### 3.6 HẠ HẦU / HẠ HẦU LIỆT <a id="nv-hahau"></a>

[BÍ DANH CHƯA XÁC NHẬN — xem CB-L-32: "Hạ Hầu" (cờ / kỵ / sứ / lực lượng) và "Hạ Hầu Liệt" giữ nhãn gốc từng dòng]

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE | vắng; Uyển không nói "Hạ Hầu" trên trang; Canon Update ghi seed "Hạ Hầu mua lương dân → mua ngựa (cùng mạch bạc)" đóng một phần [chú: ghi chú Canon Update; trên trang không nêu tên Hạ Hầu] (⚠ xem CB-L-18) | Ch18 | CANON_FACT | Ch18 §III; Ch18 §0; Ch18 §II; Ch18 §V |
| APPEARANCE (từ bảng "Nhân vật phụ" của staging) | không xuất hiện | Ch19–Ch22 | CANON_FACT | Ch19 §III; Ch20 §III; Ch21 §III; Ch22 §III |
| GOAL | (khung của Canon Update) "Hạ Hầu đang đánh con đường mà thành đứng trên đó"; seed "Hạ Hầu đánh đường, không đánh thành" — Core [chú: trục chương/seed do Canon Update ghi; Dịch chưa kết luận trên trang] | Ch15 | CANON_FACT | Ch15 §Nguyên tắc ghi; Ch15 §V; Ch15 §II |
| RELATION(Ích Châu) | Sứ Hạ Hầu dưới cờ trắng trả thương binh Ích Châu bị bắt hôm bến trên; nhắc thư Bàng đủ to cho sĩ quan nghe | Ch15 | CANON_FACT | Ch15 §I.29–I.30 |
| STATE | Dĩnh Xuyên là cảng cấp lương của Hổ Lao (lời Dịch); kỵ Hạ Hầu đi lại trên đê (trinh sát Chiêu); hai trinh sát Hạ Hầu nhìn chùm lông đen rất lâu rồi quay đi; khói tháp báo; kỵ viện và bộ viện tới (kỵ đi đêm, bộ đi gấp); hiệu thổi muộn; hàng bộ viện đứt đôi; "cờ Hạ Hầu dừng lại, và không đi tiếp được nữa" | Ch17 | CANON_FACT | Ch17 §I.4, §I.16, §I.22, §I.24–I.38 |
| STATE | Hạ Hầu chuyển từ chủ động sang phản ứng (đi đêm, đi gấp, hiệu muộn, hàng đứt) — seed Major | Ch17 | CANON_FACT | Ch17 §V |
| STATE | Hổ Lao vẫn giữ (không đèn nào tắt); Dĩnh Xuyên chưa hạ, cổng không mở; viện quân chưa diệt | Ch17 | CANON_FACT | Ch17 §IV (State Ledger); Ch17 §I.36 |
| KNOWLEDGE | Dịch nói: "Hạ Hầu không cần thắng cả bốn chúng ta. Ông ta chỉ cần mỗi bên đứng một mình." ⟦ô kép → tách 1/2⟧ | Ch12 | CANON_FACT | Ch12 §I.11, §II |
| KNOWLEDGE(không biết) | Vì sao Hạ Hầu mua lương dân (chiến lược tiếp tế): không giải thích trên trang (author-truth cho Ch18) | Ch16 | CANON_UNKNOWN | Ch16 §II |
| KNOWLEDGE(không biết) | Ai chỉ huy viện; số quân hai khối; thương vong; số phận Đô úy Dĩnh Xuyên; Hạ Hầu/Bàng phản ứng sau Dĩnh Xuyên | Ch17 | CANON_UNKNOWN | Ch17 §II |
| KNOWLEDGE(không biết) | Hạ Hầu/Bàng phản ứng việc mất một phần ngựa; người mua (giọng miền tây, bạc dấu kho) của ai: không nêu phe | Ch18 | CANON_UNKNOWN | Ch18 §II; Ch18 §IX |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch08 | STATE | Quân Tây Lương của Hạ Hầu Liệt đã vào Lạc Kinh (tin trạm); sứ của Hạ Hầu tới ải Tây đòi Ích Châu dâng biểu về Lạc Kinh. Sứ Hạ Hầu ở ải Tây ≠ tướng Tây Lương gửi thư ở biên ("không nhập làm một") ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch08 §I.6, I.9, §IV |  |
| Ch08 | STATE | Liên hệ giữa sứ Hạ Hầu ở ải Tây và tướng Tây Lương gửi thư ở biên: OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch08 §I.6, I.9, §IV |  |
| Ch09 | STATE | Thư Bàng: Hạ Hầu "phò chính Lạc Kinh" ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch09 §I.3, §II |  |
| Ch09 | STATE | Liên hệ sứ Hạ Hầu – Bàng: OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch09 §I.3, §II |  |
| Ch12 | KNOWLEDGE | Dịch nói: "Hạ Hầu không cần thắng cả bốn chúng ta. Ông ta chỉ cần mỗi bên đứng một mình." ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch12 §I.11, §II |  |
| Ch12 | KNOWLEDGE | Hạ Hầu có biết cuộc gặp không: OPEN; không mở tuyến Tây Lương / Hạ Hầu ở Ch12 ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch12 §I.11, §II |  |
| Ch13 | STATE | Chỉ: đầu dây của kẻ đếm thuyền nằm ở phía Hạ Hầu (qua ba mắt xích; cửa Lạc Kinh có quân Hạ Hầu giữ) ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch13 §I.20, §III (Chỉ), §II |  |
| Ch13 | STATE | Hạ Hầu làm gì tiếp sau tin giả: OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch13 §I.20, §III (Chỉ), §II |  |
| Ch15 | STATE | Hạ Hầu giữ Hổ Lao, dàn quân đủ; kỵ Hạ Hầu từ bờ đất, không trống, đánh vào chỗ nối của cột Ích Châu; rút theo thứ tự sau ba tiếng trống chậm, không đuổi | CANON_FACT | Ch15 §I.16, §I.20; Ch15 §IV | ← Ch13 STATE |
| Ch15 | GOAL | (khung của Canon Update) "Hạ Hầu đang đánh con đường mà thành đứng trên đó"; seed "Hạ Hầu đánh đường, không đánh thành" — Core [chú: trục chương/seed do Canon Update ghi; Dịch chưa kết luận trên trang] | CANON_FACT | Ch15 §Nguyên tắc ghi; Ch15 §V; Ch15 §II |  |
| Ch15 | RELATION(Ích Châu) | Sứ Hạ Hầu dưới cờ trắng trả thương binh Ích Châu bị bắt hôm bến trên; nhắc thư Bàng đủ to cho sĩ quan nghe | CANON_FACT | Ch15 §I.29–I.30 |  |
| Ch15 | KNOWLEDGE(không biết) | Thương vong Hạ Hầu: không nêu; ai ra lệnh ba tiếng trống: không nêu | CANON_UNKNOWN | Ch15 §II | (Before chưa trích được) |
| Ch16 | STATE | Hổ Lao: Hạ Hầu thêm quân, thêm người giữ tuyến cỏ (trinh sát đếm không hết); mỗi sáng một toán kiếm cỏ khoảng hai trăm người, hộ tống ít | CANON_FACT | Ch16 §I.8, §I.30; Ch16 §IV |  |
| Ch16 | STATE | Hạ Hầu cũng mua lương dân mùa đông: trả bạc, lấy luôn xe, một phần ba (lời làng trưởng; Dịch gật, không bình luận) | CANON_FACT | Ch16 §I.18; Ch16 §0 (GR16-16) |  |
| Ch16 | KNOWLEDGE(không biết) | Vì sao Hạ Hầu mua lương dân (chiến lược tiếp tế): không giải thích trên trang (author-truth cho Ch18) | CANON_UNKNOWN | Ch16 §II |  |
| Ch17 | STATE | Dĩnh Xuyên là cảng cấp lương của Hổ Lao (lời Dịch); kỵ Hạ Hầu đi lại trên đê (trinh sát Chiêu); hai trinh sát Hạ Hầu nhìn chùm lông đen rất lâu rồi quay đi; khói tháp báo; kỵ viện và bộ viện tới (kỵ đi đêm, bộ đi gấp); hiệu thổi muộn; hàng bộ viện đứt đôi; "cờ Hạ Hầu dừng lại, và không đi tiếp được nữa" | CANON_FACT | Ch17 §I.4, §I.16, §I.22, §I.24–I.38 |  |
| Ch17 | STATE | Hạ Hầu chuyển từ chủ động sang phản ứng (đi đêm, đi gấp, hiệu muộn, hàng đứt) — seed Major | CANON_FACT | Ch17 §V |  |
| Ch17 | STATE | Hổ Lao vẫn giữ (không đèn nào tắt); Dĩnh Xuyên chưa hạ, cổng không mở; viện quân chưa diệt | CANON_FACT | Ch17 §IV (State Ledger); Ch17 §I.36 |  |
| Ch17 | KNOWLEDGE(không biết) | Ai chỉ huy viện; số quân hai khối; thương vong; số phận Đô úy Dĩnh Xuyên; Hạ Hầu/Bàng phản ứng sau Dĩnh Xuyên | CANON_UNKNOWN | Ch17 §II |  |
| Ch18 | KNOWLEDGE(không biết) | Hạ Hầu/Bàng phản ứng việc mất một phần ngựa; người mua (giọng miền tây, bạc dấu kho) của ai: không nêu phe | CANON_UNKNOWN | Ch18 §II; Ch18 §IX |  |

**(c) PLANNING_NON_CANON**

| Ch | Trường | Nội dung (kế hoạch / author-truth; KHÔNG phải canon trang) | Source Type | Source |
|---|---|---|---|---|
| Ch11 | STATE | K1 (người ra lệnh cuối đơn Dạ Kiêu = phía Hạ Hầu): author-truth, nhân vật POV không biết | PLANNING_NON_CANON | Ch11 §II |
| Ch17 | KNOWLEDGE | chỉ dấu chương: Hạ Hầu / Bàng phản ứng sau Dĩnh Xuyên "→ Ch19+" | PLANNING_NON_CANON | Ch17 §II |

### 3.7 CHU HẠC <a id="nv-chuhac"></a>

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE | Vắng; hiện diện qua thư từ Vân Trung (quân báo, ống tre) | Ch10 | CANON_FACT | Ch10 §I.22 |
| GOAL | Động cơ riêng của Chu Hạc: author-truth Gate D, không dựng; OPEN | Ch10 | CANON_UNKNOWN | Ch10 §II, Ch11 §IX, Ch12 §IX, Ch13 §IX |
| STATE | → tới sau (giáp sứt vai, máu khô trên má, đao mẻ), hỏi "Chuyện gì xảy ra?"; nói lời nghi A Quy (nguyên văn nhiều câu, kết "Mà trong này lại có một tên Bắc Nhung."); công khai "Từ giờ, Hoắc gia quân nghe lệnh Tam công tử."; cạnh Chiêu ở Bắc Môn, nói "Thằng bé này đêm nay trực ở đây." | Ch06 | CANON_FACT | Ch06 §I.25–28, §I.44, §IV |
| STATE | Vân Trung (theo Canon Ch6) | Ch07 | CANON_FACT | Ch07 §IV |
| STATE | Thư: kho chỉ chuyển lên thêm chừng hai mươi ngày lương; đường vận đóng băng; "nếu có cách thôi đánh trước khi băng tan, thì nên tìm" | Ch10 | CANON_FACT | Ch10 §I.22 |
| KNOWLEDGE (biết) | mặt Chỉ; Chỉ đột nhập phủ; Hoắc không giao Chỉ phủ nha, không ghi sổ; nơi giam Chỉ | Ch02 | CANON_FACT | Ch02 §III (CHU HẠC) |
| KNOWLEDGE | biết thêm Dịch lên tường đếm; áo bổ sung đến từ đoàn hòa thân qua Hộ phòng và kho quân nhu | Ch03 | CANON_FACT | Ch03 §III (CHU HẠC) |
| KNOWLEDGE | biết thêm lời kể của lính về A Quy; nàng nắm binh phù. "Author-truth của Chu Hạc: xem Gate" | Ch06 | CANON_FACT | Ch06 §III (bảng) |
| KNOWLEDGE | Chiêu tin số liệu và con người ông ta ⟦ST gốc: "CANON_BELIEF (Chiêu)"⟧ | Ch10 | CANON_BELIEF | Ch10 §I.23, §III |
| KNOWLEDGE | Chỉ không nghi Chu Hạc ⟦ô kép tách thủ công 2/2; tin: Chỉ⟧ | Ch11 | CANON_BELIEF | Ch11 §II, §III |
| KNOWLEDGE (người khác) | Vân Chương không biết Chu Hạc | Ch04 | CANON_UNKNOWN | Ch04 §III; Ch05 §III |
| KNOWLEDGE (không biết, từ Chiêu) | Chiêu không biết Chu Hạc ở đâu lúc chính Tý | Ch06 | CANON_UNKNOWN | Ch06 §III |
| KNOWLEDGE | Dịch có nghi Chu Hạc không: OPEN (hạn khóa trước Ch11) | Ch10 | CANON_UNKNOWN | Ch10 §IX |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch01 | STATE | (đầu dải) → phó tướng Hoắc gia quân, lo thành phòng mặt bắc, "ngày nào cũng đi tuần tường thành"; đang xin phủ ba mươi bộ áo bông cho lính gác đêm | CANON_FACT | Ch01 §I.10 |  |
| Ch01 | STATE | → ra lệnh bôi dầu then và khung sắt (then Bắc Môn mới); phụ trách Bắc Môn, lịch hẹn "mai qua xem lại" then cửa | CANON_FACT | Ch01 §I.9, §VI |  |
| Ch01 | KNOWLEDGE | biết Dịch vừa từ Tịnh Châu về và có hỏi về then cửa | CANON_FACT | Ch01 §III (CHU HẠC) |  |
| Ch01 | KNOWLEDGE (không hiển thị) | những gì Chu Hạc biết thêm: chưa hiển thị trong truyện | CANON_UNKNOWN | Ch01 §III |  |
| Ch02 | STATE | → đêm Ch2 trên tường thành, nghe hiệu báo động, dẫn một toán lính vào phủ bằng cổng bên; gọi người cầm thương là "Tam công tử"; đề nghị giao phủ nha xét hỏi, bị Hoắc bác, ngừng một chút rồi tuân lệnh. Không tạo Canon rằng đêm nào ông cũng tuần | CANON_FACT | Ch02 §I.23–25 |  |
| Ch02 | KNOWLEDGE (biết) | mặt Chỉ; Chỉ đột nhập phủ; Hoắc không giao Chỉ phủ nha, không ghi sổ; nơi giam Chỉ | CANON_FACT | Ch02 §III (CHU HẠC) |  |
| Ch02 | KNOWLEDGE (không biết) | danh tính Chỉ; lý do Hoắc giữ Chỉ; chưa có lý do nghi Hoắc | CANON_UNKNOWN | Ch02 §III |  |
| Ch03 | STATE | → hai lá đơn xin áo cách nhau chín ngày nằm ngăn "chờ" Hộ phòng; đêm ngày 5 cầm sổ ca trực ở cầu thang tường bắc, đưa Dịch xem; nhận 26 bộ áo, nói "Hai mươi sáu. Còn bốn." (⚠ xem CB-L-07); thái độ trung tính | CANON_FACT | Ch03 §I.16, §I.52 |  |
| Ch03 | KNOWLEDGE | biết thêm Dịch lên tường đếm; áo bổ sung đến từ đoàn hòa thân qua Hộ phòng và kho quân nhu | CANON_FACT | Ch03 §III (CHU HẠC) |  |
| Ch04 | KNOWLEDGE (người khác) | Vân Chương không biết Chu Hạc | CANON_UNKNOWN | Ch04 §III; Ch05 §III |  |
| Ch06 | STATE | → tới sau (giáp sứt vai, máu khô trên má, đao mẻ), hỏi "Chuyện gì xảy ra?"; nói lời nghi A Quy (nguyên văn nhiều câu, kết "Mà trong này lại có một tên Bắc Nhung."); công khai "Từ giờ, Hoắc gia quân nghe lệnh Tam công tử."; cạnh Chiêu ở Bắc Môn, nói "Thằng bé này đêm nay trực ở đây." | CANON_FACT | Ch06 §I.25–28, §I.44, §IV |  |
| Ch06 | KNOWLEDGE (không biết, từ Chiêu) | Chiêu không biết Chu Hạc ở đâu lúc chính Tý | CANON_UNKNOWN | Ch06 §III |  |
| Ch06 | KNOWLEDGE | biết thêm lời kể của lính về A Quy; nàng nắm binh phù. "Author-truth của Chu Hạc: xem Gate" | CANON_FACT | Ch06 §III (bảng) |  |
| Ch07 | STATE | Vân Trung (theo Canon Ch6) | CANON_FACT | Ch07 §IV |  |
| Ch10 | STATE | Thư: kho chỉ chuyển lên thêm chừng hai mươi ngày lương; đường vận đóng băng; "nếu có cách thôi đánh trước khi băng tan, thì nên tìm" | CANON_FACT | Ch10 §I.22 | ← Ch07 STATE |
| Ch10 | KNOWLEDGE | Chiêu tin số liệu và con người ông ta ⟦ST gốc: "CANON_BELIEF (Chiêu)"⟧ | CANON_BELIEF | Ch10 §I.23, §III | (Before chưa trích được) |
| Ch10 | GOAL | Động cơ riêng của Chu Hạc: author-truth Gate D, không dựng; OPEN | CANON_UNKNOWN | Ch10 §II, Ch11 §IX, Ch12 §IX, Ch13 §IX |  |
| Ch10 | KNOWLEDGE | Dịch có nghi Chu Hạc không: OPEN (hạn khóa trước Ch11) | CANON_UNKNOWN | Ch10 §IX |  |
| Ch11 | KNOWLEDGE | Chỉ không nghi Chu Hạc ⟦ô kép tách thủ công 2/2; tin: Chỉ⟧ | CANON_BELIEF | Ch11 §II, §III |  |

**(c) PLANNING_NON_CANON**

| Ch | Trường | Nội dung (kế hoạch / author-truth; KHÔNG phải canon trang) | Source Type | Source |
|---|---|---|---|---|
| Ch09 | STATE | Nêu ở "Open threads chuyển tiếp" (trước Ch10): "Chu Hạc trong bộ máy Hoắc, 'người đưa ra lời khuyên từ phía sau'" (nhãn Chapter Bible của Canon Update) | PLANNING_NON_CANON | Ch09 §IX |
| Ch11 | KNOWLEDGE | Suy luận riêng của Dịch về Bắc Môn (D1): không lên trang, "không xác nhận Chu Hạc" ⟦ô kép tách thủ công 1/2; ST gốc: "PLANNING_NON_CANON (D1) / CANON_BELIEF (Chỉ)"⟧ | PLANNING_NON_CANON | Ch11 §II, §III |
| Ch13 | STATE | Hướng người rò tin (author-truth): "tuyến dẫn về người từng phục vụ Tạ gia (Chapter Bible Ch14). Không chỉ Chu Hạc." | PLANNING_NON_CANON | Ch13 §II, §IX |

### 3.8 HÀN (Hàn Đô úy) <a id="nv-han"></a>

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE | Có mặt (S2, S4, S6) | Ch08 | CANON_FACT | Ch08 §I.9, I.17, I.32 |
| APPEARANCE | first trong dải; không POV | Ch15 | CANON_FACT | Ch15 §I.2 |
| APPEARANCE | vắng | Ch18 | CANON_FACT | Ch18 §III |
| APPEARANCE | có mặt, không POV; vai còn băng, cung sau lưng | Ch19 | CANON_FACT | Ch19 §I.1 |
| APPEARANCE | vắng | Ch20–Ch21 | CANON_FACT | Ch20 §III; Ch21 §III |
| APPEARANCE | có mặt, không POV; vai còn băng | Ch22 | CANON_FACT | Ch22 §I.4; Ch22 §IV (Hàn) |
| LIMIT | Quyết đánh/không đánh thuộc Hàn: "Không đánh."; "Đi." cho sĩ quan xin áp tải thương binh | Ch16 | CANON_FACT | Ch16 §I.9; Ch16 §I.26 |
| LIMIT | hạn riêng: "Hết ngày bốn mươi mốt, ta kéo bộ về Lạc Thủy." — hạn riêng "không dùng" cuối chương | Ch19 | CANON_FACT | Ch19 §I.16; Ch19 §IV (Hàn) |
| LIMIT | "Ích Châu đã mất một nghìn tám. Ta không đem thêm một người đi chỉ vì ngươi đoán." → (nhìn bản đồ lâu) "Ta đem. Ta chọn. Bộ ta đứng một đêm trên đê, không che." | Ch22 | CANON_FACT | Ch22 §I.8 |
| RELATION(Dịch) | đọc tờ lịch lâu; hỏi "Kim Lăng muốn gì?" — "Tờ không nói."; khi sĩ quan trách Dịch, Hàn nhìn Dịch, không nói | Ch22 | CANON_FACT | Ch22 §I.4, I.21 |
| STATE | giữ hàng binh bộ viện (vài trăm, ăn cháo, không bị giết); trại cách thành ba dặm; đứng ngoài thành | Ch19 | CANON_FACT | Ch19 §I.10, I.14; Ch19 §IV (Hàng binh, Hàn) |
| STATE | danh xưng: sĩ quan Ích Châu gọi "Đô úy." ở hook cuối chương (Dịch cũng nói "Bộ của Đô úy" khi hỏi Hàn) | Ch19 | CANON_FACT | Ch19 §I.22; Ch19 §I.10 |
| STATE | giữ cổng bến suốt đêm; vào thành chính sáng hôm sau; ra lệnh mở cổng đê; sổ người chết thêm tên; "Ta cần cả bộ ở đây." | Ch22 | CANON_FACT | Ch22 §I.13, I.15, I.17–18, I.28; Ch22 §IV (Hàn) |
| KNOWLEDGE | Bàng biết thói quen vận lương Ích Châu (giao dịch); đã ký hồi âm; Ôn đã xem tờ nhất thư Bàng | Ch16 | CANON_FACT | Ch16 §III |
| KNOWLEDGE | biết: quyết bộ, hàng binh; hạn riêng hết ngày 41 | Ch19 | CANON_FACT | Ch19 §III (Hàn) |
| KNOWLEDGE | biết: tự chọn đi; thấy cổng bến mở; giữ thành; sổ người chết thêm tên; chiếu có tên Dịch | Ch22 | CANON_FACT | Ch22 §III (Hàn) |
| KNOWLEDGE(không biết) | Mục đích sâu của Dịch (không nói) | Ch17 | CANON_UNKNOWN | Ch17 §III |
| KNOWLEDGE | không biết: mục đích sâu của Dịch | Ch19 | CANON_UNKNOWN | Ch19 §III (Hàn) |
| KNOWLEDGE | không biết: vì sao Hạ Hầu mở; thuyền chở gì | Ch22 | CANON_UNKNOWN | Ch22 §III (Hàn) |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch08 | STATE | Báo trước công đường quân giữ thành 2.800; chuyển thư tướng giữ ải Tây: sứ Hạ Hầu đã tới ải đòi Ích Châu dâng biểu; không bình ⟦ST gốc: "CANON_FACT (2.800: số chính thức do Hàn báo)"⟧ | CANON_FACT | Ch08 §I.9, §II |  |
| Ch08 | KNOWLEDGE | Biết như Ôn; không hỏi về huyết thống; biết Dịch không xin quân quyền, không đụng kho quân ải; hỏi "Tiên sinh muốn gì?" | CANON_FACT | Ch08 §I.22, §III (Hàn) |  |
| Ch08 | STATE | Cuối Ch08: chưa rõ nghiêng về đâu | CANON_FACT | Ch08 §IV |  |
| Ch09 | STATE | Ngày 18: tự đứng dậy "Là ta nhắn cho ải Tây."; Hàn không xin tha, không ngồi xuống | CANON_FACT | Ch09 §I.19, I.21 |  |
| Ch09 | KNOWLEDGE | Lời Hàn: Tiết tướng quân cùng Hàn đi lính từ năm mười sáu tuổi; sợ Tiết dâng biểu vội; nhắn miệng, không viết giấy; không nói tên (chỉ "một mạc liêu trong phủ"); nhắn qua viên quản lương sắp về ải | CANON_FACT | Ch09 §I.20 |  |
| Ch09 | STATE | Được giao việc ải Tây ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch09 §I.26, §IV |  |
| Ch09 | STATE | Kết quả việc ải Tây: OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch09 §I.26, §IV |  |
| Ch09 | RELATION(Dịch) | Hành lang ngày 19: "Quân ở ải nghe một cái danh nhanh hơn nghe sổ lương… Tiên sinh có cái danh ấy." Dịch: "Chưa." Hàn gật đầu, không rõ đồng ý hay chỉ đã nghe | CANON_FACT | Ch09 §I.28 |  |
| Ch09 | RELATION(Dịch) | Đồng minh quân sự rạn; "Chưa." | CANON_FACT | Ch09 §V (Seed "Hàn: đồng minh quân sự rạn"), §VI |  |
| Ch12 | KNOWLEDGE | "Hàn Đô úy không dặn việc này" (bảo chứng A Quy) — theo lời đội trưởng hộ tống ⟦ST gốc: "CANON_FACT (lời đội trưởng)"⟧ | CANON_FACT | Ch12 §I.16 |  |
| Ch15 | STATE | Mặc giáp quân Ích Châu, ngồi bên phải Dịch; chỉ huy quân; cưỡi ngựa đi đầu cột | CANON_FACT | Ch15 §I.2; Ch15 §0; Ch15 §I.10 | ← Ch09 STATE |
| Ch15 | LIMIT | Hàn quyết ngày hội (bên chậm nhất = Ích Châu); "Mỗi tuần chờ, trong kinh thêm người."; cầu phao không chịu nổi xe nặng khi băng tan | CANON_FACT | Ch15 §I.4–I.5, §I.7 |  |
| Ch15 | STATE | Bị mũi giáo xẹt vai, không dừng; sáng ngày thứ tám vai quấn băng, mặt xám, nằm cạnh lửa; còn chỉ huy | CANON_FACT | Ch15 §I.19, §I.24; Ch15 §IV |  |
| Ch15 | KNOWLEDGE | Biết bị thương; cột mất; Bàng nhắc thư | CANON_FACT | Ch15 §III | (Before chưa trích được) |
| Ch16 | STATE | Xác nhận giao dịch với Bàng nhiều năm ("Họ biết một xe của ta chở bao nhiêu."); "Từ đầu đông, bên Bàng không tới nhận lương ải Tây nữa. Sổ vẫn mở." — chỉ giao dịch, không về người báo tin (GR16-11) | CANON_FACT | Ch16 §I.2, §I.4; Ch16 §0 |  |
| Ch16 | LIMIT | Quyết đánh/không đánh thuộc Hàn: "Không đánh."; "Đi." cho sĩ quan xin áp tải thương binh | CANON_FACT | Ch16 §I.9; Ch16 §I.26 |  |
| Ch16 | RELATION(Dịch) | Tên Hàn ký sẵn trên phiếu (nét hơi run); ký hồi âm bằng tay còn lành; "Việc kia Thứ sử đã xem." | CANON_FACT | Ch16 §I.16; Ch16 §I.24; Ch16 §I.22 | ← Ch09 RELATION(Dịch) |
| Ch16 | KNOWLEDGE | Bàng biết thói quen vận lương Ích Châu (giao dịch); đã ký hồi âm; Ôn đã xem tờ nhất thư Bàng | CANON_FACT | Ch16 §III |  |
| Ch16 | KNOWLEDGE(không biết) | Mục đích hồi âm của Dịch (không nói) | CANON_UNKNOWN | Ch16 §III |  |
| Ch17 | STATE | Vai còn băng; "Ta quyết." (quyết gửi bộ đi thuyền); "Nếu ta rút ở nén hương cuối?" — "Thuyền quay."; không đi vì vai chưa nâng nổi cung | CANON_FACT | Ch17 §I.13 |  |
| Ch17 | STATE | Cuối Ch17: bộ Ích Châu đã giao chiến thật ở cổ chai; Hàn tự chịu quyết gửi bộ | CANON_FACT | Ch17 §IV; Ch17 §VI |  |
| Ch17 | KNOWLEDGE(không biết) | Mục đích sâu của Dịch (không nói) | CANON_UNKNOWN | Ch17 §III |  |
| Ch19 | STATE | giữ hàng binh bộ viện (vài trăm, ăn cháo, không bị giết); trại cách thành ba dặm; đứng ngoài thành | CANON_FACT | Ch19 §I.10, I.14; Ch19 §IV (Hàng binh, Hàn) | ← Ch17 STATE |
| Ch19 | STATE | danh xưng: sĩ quan Ích Châu gọi "Đô úy." ở hook cuối chương (Dịch cũng nói "Bộ của Đô úy" khi hỏi Hàn) | CANON_FACT | Ch19 §I.22; Ch19 §I.10 |  |
| Ch19 | LIMIT | hạn riêng: "Hết ngày bốn mươi mốt, ta kéo bộ về Lạc Thủy." — hạn riêng "không dùng" cuối chương | CANON_FACT | Ch19 §I.16; Ch19 §IV (Hàn) | ← Ch16 LIMIT |
| Ch19 | RELATION(Dịch) | Hàn quyết bộ và hàng binh ("Ta quyết."; "Ta tự xử."); không ký kèm; "Ta nói để ngươi biết." | CANON_FACT | Ch19 §I.8, I.10, I.16 | ← Ch16 RELATION(Dịch) |
| Ch19 | RELATION(Dịch) | nợ: Hàn giữ hàng binh — ACTIVE | CANON_FACT | Ch19 §VI |  |
| Ch19 | KNOWLEDGE | biết: quyết bộ, hàng binh; hạn riêng hết ngày 41 | CANON_FACT | Ch19 §III (Hàn) | (Before chưa trích được) |
| Ch19 | KNOWLEDGE | không biết: mục đích sâu của Dịch | CANON_UNKNOWN | Ch19 §III (Hàn) |  |
| Ch22 | LIMIT | "Ích Châu đã mất một nghìn tám. Ta không đem thêm một người đi chỉ vì ngươi đoán." → (nhìn bản đồ lâu) "Ta đem. Ta chọn. Bộ ta đứng một đêm trên đê, không che." | CANON_FACT | Ch22 §I.8 |  |
| Ch22 | STATE | giữ cổng bến suốt đêm; vào thành chính sáng hôm sau; ra lệnh mở cổng đê; sổ người chết thêm tên; "Ta cần cả bộ ở đây." | CANON_FACT | Ch22 §I.13, I.15, I.17–18, I.28; Ch22 §IV (Hàn) |  |
| Ch22 | RELATION(Dịch) | đọc tờ lịch lâu; hỏi "Kim Lăng muốn gì?" — "Tờ không nói."; khi sĩ quan trách Dịch, Hàn nhìn Dịch, không nói | CANON_FACT | Ch22 §I.4, I.21 |  |
| Ch22 | KNOWLEDGE | biết: tự chọn đi; thấy cổng bến mở; giữ thành; sổ người chết thêm tên; chiếu có tên Dịch | CANON_FACT | Ch22 §III (Hàn) |  |
| Ch22 | KNOWLEDGE | không biết: vì sao Hạ Hầu mở; thuyền chở gì | CANON_UNKNOWN | Ch22 §III (Hàn) |  |

**(c) PLANNING_NON_CANON**

Không có dòng PLANNING_NON_CANON cho nhân vật này trong staging.

### 3.9 BÀNG <a id="nv-bang"></a>

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE | không xuất hiện trực tiếp; qua lời sứ Hạ Hầu dưới cờ trắng: "Bàng tướng quân nhờ hỏi: thư ông ấy gửi, đến nay Ích Châu chưa có hồi âm." | Ch15 | CANON_FACT | Ch15 §I.30; Ch15 §II ("Bàng không xuất hiện") |
| APPEARANCE | không xuất hiện; chỉ qua hồi âm Dịch viết | Ch16 | CANON_FACT | Ch16 §III |
| APPEARANCE | "Bàng" chỉ một lần trên trang (hồi âm); không "Bàng nghĩ" | Ch17 | CANON_FACT | Ch17 §0 (GR17-04) |
| APPEARANCE | vắng; Bàng/Hạ Hầu phản ứng việc mất một phần ngựa: OPEN (Ch19 mặc định không nối) | Ch18 | CANON_UNKNOWN | Ch18 §III; Ch18 §II; Ch18 §IX |
| APPEARANCE | chỉ qua thư (sứ Hạ Hầu cờ trắng đưa) | Ch19 | CANON_FACT | Ch19 §I.5; Ch19 §III |
| APPEARANCE | không xuất hiện; Ch22: "Bàng không lên trang" | Ch20–Ch22 | CANON_FACT | Ch20 §III; Ch21 §III; Ch22 §II-A |
| GOAL | thư: "Việc lương: nhận… Ta cần cỏ trước vụ hè… Tờ thứ nhất, ta vẫn chờ. Thư này chỉ bàn việc lương." | Ch19 | CANON_FACT | Ch19 §I.5 |
| STATE (từ bảng "Nhân vật phụ" của staging) | Người ký thư gửi "Thất điện hạ"; không nhận hồi âm; Knowledge không đổi so với Gate B0 | Ch09 | CANON_FACT | Ch09 §I.3, §III (TÂY LƯƠNG), §IV |
| STATE | Thư Bàng (Ch9) chưa hồi âm; sứ nhắc công khai | Ch15 | CANON_FACT | Ch15 §IV; Ch15 §0 |
| STATE | "Hạ Hầu: mất cảng cấp lương; Hổ Lao vẫn giữ; Bàng cần cỏ, không hỏi người kẹt, chờ tờ nhất" | Ch19 | CANON_FACT | Ch19 §IV (Hạ Hầu) |
| KNOWLEDGE | Bàng biết cách xe Ích Châu chở (Hàn xác nhận: giao dịch nhiều năm); "Từ đầu đông, bên Bàng không tới nhận lương ải Tây nữa. Sổ vẫn mở." | Ch16 | CANON_FACT | Ch16 §I.2, §I.4; Ch16 §III |
| KNOWLEDGE(Dịch về Bàng) | Thư Bàng: "Lương của ngài đi nhanh hơn sổ của ta"; Dịch nhận ra Bàng tự viết sổ mình chậm hơn lương Ích Châu ("Đo bằng xe. Ta tưởng hắn không chịu viết ra.") (Dịch tin) ⚠ xem CB-L-21 | Ch19 | CANON_BELIEF | Ch19 §I.5, I.7; Ch19 §III (Dịch) |
| KNOWLEDGE(không biết) | Bàng phản ứng hồi âm thế nào; ý đồ thật của hồi âm; có rò tin hay không | Ch16 | CANON_UNKNOWN | Ch16 §II; Ch16 §III |
| KNOWLEDGE(không biết) | Cách Bàng đọc liên minh; hồi âm Bàng chưa đáp | Ch17 | CANON_UNKNOWN | Ch17 §II; Ch17 §III |
| KNOWLEDGE | Bàng đổi cách đo hay không; phản công; tờ nhất thư Bàng | Ch20–Ch22 | CANON_UNKNOWN | Ch19 §II; Ch20 §II; Ch22 §II-A |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch09 | STATE (từ bảng "Nhân vật phụ" của staging) | Người ký thư gửi "Thất điện hạ"; không nhận hồi âm; Knowledge không đổi so với Gate B0 | CANON_FACT | Ch09 §I.3, §III (TÂY LƯƠNG), §IV |  |
| Ch15 | STATE | Thư Bàng (Ch9) chưa hồi âm; sứ nhắc công khai | CANON_FACT | Ch15 §IV; Ch15 §0 | ← Ch09 STATE |
| Ch15 | KNOWLEDGE(không biết) | Bàng đọc đường lương bằng cách nào: không lên trang (author-truth Gate Ch15 mục 4); trên trang Dịch thấy hai đường trùng nhau, không kết luận | CANON_UNKNOWN | Ch15 §II |  |
| Ch16 | KNOWLEDGE | Bàng biết cách xe Ích Châu chở (Hàn xác nhận: giao dịch nhiều năm); "Từ đầu đông, bên Bàng không tới nhận lương ải Tây nữa. Sổ vẫn mở." | CANON_FACT | Ch16 §I.2, §I.4; Ch16 §III |  |
| Ch16 | KNOWLEDGE(không biết) | Bàng phản ứng hồi âm thế nào; ý đồ thật của hồi âm; có rò tin hay không | CANON_UNKNOWN | Ch16 §II; Ch16 §III |  |
| Ch17 | KNOWLEDGE(không biết) | Cách Bàng đọc liên minh; hồi âm Bàng chưa đáp | CANON_UNKNOWN | Ch17 §II; Ch17 §III |  |
| Ch19 | GOAL | thư: "Việc lương: nhận… Ta cần cỏ trước vụ hè… Tờ thứ nhất, ta vẫn chờ. Thư này chỉ bàn việc lương." | CANON_FACT | Ch19 §I.5 |  |
| Ch19 | KNOWLEDGE(Dịch về Bàng) | Thư Bàng: "Lương của ngài đi nhanh hơn sổ của ta"; Dịch nhận ra Bàng tự viết sổ mình chậm hơn lương Ích Châu ("Đo bằng xe. Ta tưởng hắn không chịu viết ra.") (Dịch tin) ⚠ xem CB-L-21 | CANON_BELIEF | Ch19 §I.5, I.7; Ch19 §III (Dịch) | (Before chưa trích được) |
| Ch19 | STATE | "Hạ Hầu: mất cảng cấp lương; Hổ Lao vẫn giữ; Bàng cần cỏ, không hỏi người kẹt, chờ tờ nhất" | CANON_FACT | Ch19 §IV (Hạ Hầu) | ← Ch15 STATE |
| Ch20–Ch22 | KNOWLEDGE | Bàng đổi cách đo hay không; phản công; tờ nhất thư Bàng | CANON_UNKNOWN | Ch19 §II; Ch20 §II; Ch22 §II-A |  |

**(c) PLANNING_NON_CANON**

| Ch | Trường | Nội dung (kế hoạch / author-truth; KHÔNG phải canon trang) | Source Type | Source |
|---|---|---|---|---|
| Ch21–Ch22 | KNOWLEDGE | author-truth: Bàng "học quá kỹ" từ Dĩnh Xuyên; đọc lệnh lương gấp ba + thuyền neo ngang sông như thuyền quân → dồn dự bị ra bến; sai một điểm (thuyền chỉ chở lương); Bàng tự ra lệnh mở cổng (mở ≠ đầu hàng); Bàng không điều khiển G | PLANNING_NON_CANON | Ch21 §II-B; Ch22 §II-B |
| Ch16–Ch17 | KNOWLEDGE | chỉ dấu chương: Bàng phản ứng hồi âm / hồi âm chưa đáp "→ Ch19" | PLANNING_NON_CANON | Ch16 §II; Ch17 §II |

### 3.10 ÔN / THỨ SỬ <a id="nv-on"></a>

[BÍ DANH CHƯA XÁC NHẬN — xem CB-L-26: mỗi dòng mang nhãn gốc ([Ôn], [Ôn Thứ sử], [Thứ sử]); không kết luận hai nhãn là một]

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE | [Ôn Thứ sử] Có mặt (S2 đọc tin trạm; S4 phòng kín; S6 công đường) | Ch08 | CANON_FACT | Ch08 §I.6, I.17, I.32 |
| APPEARANCE | [Ôn] Ôn chỉ qua thư; không xuất hiện | Ch16 | CANON_FACT | Ch16 §III |
| APPEARANCE | [Ôn] không xuất hiện; chưa biết thêm chi phí Dĩnh Xuyên (nợ ~300/400 bao muối theo Ch16) | Ch17 | CANON_UNKNOWN | Ch17 §III; Ch17 §IX |
| APPEARANCE | [Ôn] không xuất hiện | Ch19–Ch22 | CANON_FACT | Ch19 §III; Ch20 §III; Ch22 §III |
| LIMIT | [Ôn] cap 400 bao muối ("Ôn nói bốn trăm.") | Ch19 | CANON_FACT | Ch19 §I.9; Ch19 §0 (Sync) |
| RELATION(Dịch) | [Ôn] Dịch nợ Ôn muối vượt trần — ACTIVE (không đổi) | Ch22 | CANON_FACT | Ch22 §VI |
| STATE | [Ôn] Cuối tháng Sáu → đầu tháng Bảy năm 0: Ôn "đặt cược có điều kiện" — Dịch có quyền điều phối vận lương, tuyến vận, đội hộ tống, quyền đại diện có điều kiện; không quân riêng, không phong tướng (nối tiếp, không xóa, D7) | Ch12 | CANON_FACT | Ch12 §0B (CC-2) |
| STATE | [Ôn] Qua mùa đông (off-page): Ôn giao Dịch kế hoạch/lương và cho mượn đạo Ích Châu dưới Hàn | Ch15 | CANON_FACT | Ch15 §VII |
| STATE | [Ôn] Thư Ôn (tới chiều ngày 28; chữ nhỏ, chặt; ấn đóng ở đầu): "Phiếu nợ có ấn, tới hết vụ thu. Muối bốn trăm bao, vải hai trăm tấm. Quá số ấy, ngươi tự chịu." | Ch16 | CANON_FACT | Ch16 §I.31 |
| KNOWLEDGE | [Ôn] Hỏi "Tiết đã dâng biểu chưa?" — Hàn: "Chưa có tin." | Ch09 | CANON_FACT | Ch09 §I.22 |
| KNOWLEDGE | [Ôn] Chưa biết chuyện bảo chứng A Quy (Dịch bảo chứng ngoài dặn dò) | Ch12 | CANON_FACT | Ch12 §IV (Dịch), §VI |
| KNOWLEDGE | [Ôn (Ch16 §III, §II); trên trang Ch16 §I.22 Hàn nói "Thứ sử"] Ôn đã xem tờ nhất thư Bàng ("việc kia") ⚠ xem CB-L-26 ⟦ô kép → tách 1/2⟧ | Ch16 | CANON_FACT | Ch16 §III; Ch16 §II |
| KNOWLEDGE | [Ôn] Ôn tin Dịch hay không: OPEN, không được biểu lộ | Ch08 | CANON_UNKNOWN | Ch08 §III (Ôn) |
| KNOWLEDGE(không biết) | [Ôn] Thái độ Ôn sau thất bại: OPEN (Ch16) | Ch15 | CANON_UNKNOWN | Ch15 §II |
| KNOWLEDGE | [Ôn (Ch16 §III, §II); trên trang Ch16 §I.22 Hàn nói "Thứ sử"] Ôn đã quyết gì về tờ nhất: không ghi ⟦ô kép → tách 2/2⟧ | Ch16 | CANON_UNKNOWN | Ch16 §III; Ch16 §II |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch08 | STATE | [Ôn Thứ sử] Tin Lạc Kinh: không nói theo ai; hỏi quân giữ thành và kho; giữ phong thư Tây Lương chưa mở; chưa tuyên bố theo ai (⚠ xem CB-L-08) | CANON_FACT | Ch08 §I.10, §IV |  |
| Ch08 | KNOWLEDGE | [Ôn] Biết: Trình Dịch tự nhận là con Thẩm chiêu nghi; thấy khóa trường mệnh; thấy Phùng Bảo (dáng người hầu nội đình) trả lời câu thử | CANON_FACT | Ch08 §III (Ôn) |  |
| Ch08 | KNOWLEDGE | [Ôn] Ôn tin Dịch hay không: OPEN, không được biểu lộ | CANON_UNKNOWN | Ch08 §III (Ôn) |  |
| Ch08 | STATE (quyền) | [Ôn Thứ sử] Trao Dịch quyền kho hành chính có giới hạn (xuất kho lớn cần ấn Thứ sử); nhận điều kiện giữ kín "Được." | CANON_FACT | Ch08 §I.25–26, §III (Ôn) |  |
| Ch08 | STATE | [Ôn] Ôn nhìn Phùng Bảo trước rồi mới nhìn Dịch; định gọi "Trình…" rồi thôi | CANON_FACT | Ch08 §I.20, I.27 |  |
| Ch08 | STATE | [Ôn] Ngày 14: không đáp người đưa tin; nghiêng người sang một bên ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch08 §I.34, §III (Chưa biết) |  |
| Ch08 | STATE | [Ôn] Lý do Ôn nghiêng người: OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch08 §I.34, §III (Chưa biết) |  |
| Ch09 | STATE | [Ôn] Ôn không nhận thư bằng tay, "Thư gửi ai thì người ấy mở."; hỏi Dịch thấy sao (⚠ xem CB-L-08) | CANON_FACT | Ch09 §I.1–2, I.4 |  |
| Ch09 | KNOWLEDGE | [Ôn] Biết toàn bộ điều Dịch trình ngày 18; biết Hàn là người nhắn | CANON_FACT | Ch09 §III (Ôn) |  |
| Ch09 | STATE | [Ôn] Phê ba việc đầu (lương 1.000 suất, cỏ 300 ngựa, thu hồi thông hành nhà Đỗ); phê "niêm" việc thứ tư (gian kho thứ chín); "Việc ải Tây, giao Hàn Đô úy." | CANON_FACT | Ch09 §I.26 |  |
| Ch09 | STATE | [Ôn] Quyết định (Gate D7): giữ Dịch, không công nhận, không quân quyền, không gửi Kim Lăng; không hồi âm Tây Lương; "chọn trì hoãn" ⟦ST gốc: "CANON_FACT (các hành vi); động cơ là author-truth"⟧ | CANON_FACT | Ch09 §III (Ôn), §IV |  |
| Ch09 | STATE (quyền Dịch) | [Ôn] Ngày 24: giao lệnh có ấn kiểm kê kho ba huyện quanh phủ thành (không chữ nào về quân; gọi "Trình Dịch") | CANON_FACT | Ch09 §I.30 |  |
| Ch09 | KNOWLEDGE | [Ôn] Hỏi "Tiết đã dâng biểu chưa?" — Hàn: "Chưa có tin." | CANON_FACT | Ch09 §I.22 |  |
| Ch12 | STATE | [Ôn] Cuối tháng Sáu → đầu tháng Bảy năm 0: Ôn "đặt cược có điều kiện" — Dịch có quyền điều phối vận lương, tuyến vận, đội hộ tống, quyền đại diện có điều kiện; không quân riêng, không phong tướng (nối tiếp, không xóa, D7) | CANON_FACT | Ch12 §0B (CC-2) |  |
| Ch12 | KNOWLEDGE | [Ôn] Chưa biết chuyện bảo chứng A Quy (Dịch bảo chứng ngoài dặn dò) | CANON_FACT | Ch12 §IV (Dịch), §VI |  |
| Ch15 | STATE | [Ôn] Qua mùa đông (off-page): Ôn giao Dịch kế hoạch/lương và cho mượn đạo Ích Châu dưới Hàn | CANON_FACT | Ch15 §VII | ← Ch12 STATE |
| Ch15 | RELATION(Dịch) | [Ôn] Debt: Dịch → Ích Châu (Ôn, sĩ quan): mất cột và đoàn xe; thư Bàng bị nhắc công khai — mới, ACTIVE | CANON_FACT | Ch15 §VI |  |
| Ch15 | KNOWLEDGE(không biết) | [Ôn] Thái độ Ôn sau thất bại: OPEN (Ch16) | CANON_UNKNOWN | Ch15 §II | (Before chưa trích được) |
| Ch16 | STATE | [Ôn] Thư Ôn (tới chiều ngày 28; chữ nhỏ, chặt; ấn đóng ở đầu): "Phiếu nợ có ấn, tới hết vụ thu. Muối bốn trăm bao, vải hai trăm tấm. Quá số ấy, ngươi tự chịu." | CANON_FACT | Ch16 §I.31 |  |
| Ch16 | RELATION(Dịch) | [Ôn] "Làm trước, ấn sau"; tối đa 400 bao — mới | CANON_FACT | Ch16 §0; Ch16 §VI |  |
| Ch16 | KNOWLEDGE | [Ôn (Ch16 §III, §II); trên trang Ch16 §I.22 Hàn nói "Thứ sử"] Ôn đã xem tờ nhất thư Bàng ("việc kia") ⚠ xem CB-L-26 ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch16 §III; Ch16 §II |  |
| Ch16 | KNOWLEDGE | [Ôn (Ch16 §III, §II); trên trang Ch16 §I.22 Hàn nói "Thứ sử"] Ôn đã quyết gì về tờ nhất: không ghi ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch16 §III; Ch16 §II |  |
| Ch19 | LIMIT | [Ôn] cap 400 bao muối ("Ôn nói bốn trăm.") | CANON_FACT | Ch19 §I.9; Ch19 §0 (Sync) |  |
| Ch19 | RELATION(Dịch) | [Ôn] Dịch nợ Ôn muối vượt trần (tự chịu) — ACTIVE; thư Ôn: ấn tới hết vụ thu | CANON_FACT | Ch19 §VI; Ch19 §IX | ← Ch16 RELATION(Dịch) |
| Ch22 | RELATION(Dịch) | [Ôn] Dịch nợ Ôn muối vượt trần — ACTIVE (không đổi) | CANON_FACT | Ch22 §VI | ← Ch19 RELATION(Dịch) |

**(c) PLANNING_NON_CANON**

| Ch | Trường | Nội dung (kế hoạch / author-truth; KHÔNG phải canon trang) | Source Type | Source |
|---|---|---|---|---|
| Ch09 | KNOWLEDGE | Lý do Ôn không cầm thư; lý do Ôn nghiêng người (Ch8): author-truth, không diễn giải | PLANNING_NON_CANON | Ch09 §II, §III (Ôn) |
| Ch20 | GOAL | phản ứng của Ôn với chiếu: "Ôn 'không theo ai'; Ch24" (ghi chú kế hoạch/chưa lên trang) | PLANNING_NON_CANON | Ch20 §II |

### 3.11 PHÙNG THÚC / PHÙNG BẢO <a id="nv-phung"></a>

[BÍ DANH CHƯA XÁC NHẬN — xem CB-L-01: Canon Update dùng "Phùng thúc" (Ch01–Ch07; Ch04 §I.13, §III) và "Phùng Bảo" (Ch04 §I.9; Ch08–Ch11); mỗi dòng mang nhãn gốc; không nối chuỗi qua ranh giới hai nhãn; trạng thái cuối không gộp hai danh tính]

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE/STATE | [Phùng thúc] (đầu dải) → ngoài sáu mươi, không râu, giọng mỏng, cúi quá mức với một thư lại; hàng xóm gọi lão Phùng; ở cùng Dịch | Ch01 | CANON_FACT | Ch01 §I.13, §VI |
| APPEARANCE | [Phùng Bảo] Có mặt (S3 nhà Dịch; S4 phòng kín) | Ch08 | CANON_FACT | Ch08 §I.12, I.17 |
| APPEARANCE | [Phùng Bảo] Không xuất hiện | Ch11 | CANON_FACT | Ch11 §IV |
| RELATION(Dịch → Phùng Bảo) | [Phùng Bảo] Dịch nợ Phùng Bảo (DEBT thật): Phùng Bảo đứng ra làm chứng, tự đặt mình trở lại trong án cũ | Ch08 | CANON_FACT | Ch08 §VI |
| STATE | [Phùng Bảo] Trả lời câu thử của Tô: hai cây quế; cành gãy buộc dây gai vẫn ra hoa; Tô chấp nhận Phùng Bảo từng ở bên Thẩm chiêu nghi | Ch08 | CANON_FACT | Ch08 §I.23, §III (Tô) |
| STATE | [Phùng Bảo] Cuối Ch08: nhà ở Ích Châu; đã làm chứng | Ch08 | CANON_FACT | Ch08 §IV |
| STATE | [Phùng Bảo] Nhà ở Ích Châu | Ch09 | CANON_FACT | Ch09 §IV |
| KNOWLEDGE | [Phùng Bảo] (lời đồn) nghe ở chợ, từ người buôn da từ phía bắc: "Hoắc Tam Lang tử trận ở Hắc Hà" (Canon Update ghi "Lời đồn sai") | Ch08 | CANON_SUSPICION | Ch08 §I.13, §III (Phùng Bảo) |
| KNOWLEDGE | [Phùng Bảo] Biết mọi điều Dịch biết về tin Lạc Kinh và lời Tô (Dịch kể lại) | Ch08 | CANON_FACT | Ch08 §III (Phùng Bảo) |
| KNOWLEDGE | [Phùng Bảo] Biết nội dung thư Bàng (Dịch đọc) | Ch09 | CANON_FACT | Ch09 §III (Phùng Bảo) |
| KNOWLEDGE | [Phùng Bảo] Đoán câu "người từng hầu trong cung" là mồi; nói: "Có người ấy thật, thì họ đã viết tên người ấy ra." | Ch09 | CANON_SUSPICION | Ch09 §I.7, §III (Phùng Bảo) |
| KNOWLEDGE (không biết) | [Phùng thúc] không biết mình đã bị Vân Chương nhìn thấy | Ch04 | CANON_UNKNOWN | Ch04 §III (PHÙNG THÚC) |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch01 | KNOWLEDGE | [Phùng thúc] lo ngại, đã khuyên "đừng đào sâu" | CANON_FACT | Ch01 §VI |  |
| Ch01 | RELATION(Dịch) | [Phùng thúc] (đầu dải) → "Trách nhiệm bảo hộ", chưa hiển thị nguồn gốc (Ẩn) | CANON_UNKNOWN | Ch01 §VII |  |
| Ch03 | KNOWLEDGE | [Phùng thúc] biết Dịch đánh cờ với Tạ phó sứ; chỉ nói "Người trong kinh." | CANON_FACT | Ch03 §I.34 |  |
| Ch04 | STATE | [Phùng thúc] → Vân Chương thấy lão khoác áo cho Dịch, cúi rất thấp, giữ tư thế thêm một nhịp; nói "Cậu đi cẩn thận" giọng mỏng | CANON_FACT | Ch04 §I.13 |  |
| Ch04 | KNOWLEDGE (không biết) | [Phùng thúc] không biết mình đã bị Vân Chương nhìn thấy | CANON_UNKNOWN | Ch04 §III (PHÙNG THÚC) |  |
| Ch04 | STATE (nền) | [Phùng Bảo] "Phùng Bảo sửa thói quen" viết chữ "Huệ" của Dịch sau khi rời cung (Canon Update không nêu rõ Phùng thúc = Phùng Bảo; ⚠ xem CB-L-01) | CANON_FACT | Ch04 §I.9 |  |
| Ch07 | STATE | [Phùng thúc] → lôi từ gầm giường bọc vải xám buộc chéo hai nút (nút cứng, bụi bám; nội dung OPEN); trượt ngã, được Dịch dìu; kiệt sức; không thấy cảnh cửa mở (đang châm pháo) | CANON_FACT | Ch07 §I.8, §I.13, §III (PHÙNG THÚC), §IV |  |
| Ch07 | KNOWLEDGE (lời nói) | [Phùng thúc] ba câu: "Sau đêm nay, trong kinh sẽ cho người xuống." / "Người ta sẽ lật từng cuốn sổ." / "Nhà cháy rồi, cậu." (lời nói trên trang; "nhà cháy" chưa kiểm chứng, Ch07 §II — ⚠ xem CB-L-04) | CANON_FACT | Ch07 §I.30 |  |
| Ch08 | STATE | [Phùng Bảo] (đầu dải) → lưng còng nhiều, đi từ cửa vào bàn phải dừng một lần; vẫn đốt lò than, đợi cửa; ngoài bảy mươi tuổi | CANON_FACT | Ch08 §I.12, §VII | (không nối qua ranh giới bí danh Phùng thúc → Phùng Bảo — xem CB-L-01) |
| Ch08 | KNOWLEDGE | [Phùng Bảo] (lời đồn) nghe ở chợ, từ người buôn da từ phía bắc: "Hoắc Tam Lang tử trận ở Hắc Hà" (Canon Update ghi "Lời đồn sai") | CANON_SUSPICION | Ch08 §I.13, §III (Phùng Bảo) | (không nối qua ranh giới bí danh Phùng thúc → Phùng Bảo — xem CB-L-01) |
| Ch08 | STATE | [Phùng Bảo] Đã giao khóa trường mệnh cho Dịch ("Lão giữ nó để có ngày này.") | CANON_FACT | Ch08 §I.15–16, §III |  |
| Ch08 | STATE | [Phùng Bảo] Trả lời câu thử của Tô: hai cây quế; cành gãy buộc dây gai vẫn ra hoa; Tô chấp nhận Phùng Bảo từng ở bên Thẩm chiêu nghi | CANON_FACT | Ch08 §I.23, §III (Tô) |  |
| Ch08 | KNOWLEDGE | [Phùng Bảo] Biết mọi điều Dịch biết về tin Lạc Kinh và lời Tô (Dịch kể lại) | CANON_FACT | Ch08 §III (Phùng Bảo) |  |
| Ch08 | RELATION(Dịch) | [Phùng Bảo] Dịch nợ Phùng Bảo (DEBT thật): Phùng Bảo đứng ra làm chứng, tự đặt mình trở lại trong án cũ | CANON_FACT | Ch08 §VI | (không nối qua ranh giới bí danh Phùng thúc → Phùng Bảo — xem CB-L-01) |
| Ch08 | STATE | [Phùng Bảo] Cuối Ch08: nhà ở Ích Châu; đã làm chứng | CANON_FACT | Ch08 §IV |  |
| Ch09 | KNOWLEDGE | [Phùng Bảo] Biết nội dung thư Bàng (Dịch đọc) | CANON_FACT | Ch09 §III (Phùng Bảo) |  |
| Ch09 | KNOWLEDGE | [Phùng Bảo] Đoán câu "người từng hầu trong cung" là mồi; nói: "Có người ấy thật, thì họ đã viết tên người ấy ra." | CANON_SUSPICION | Ch09 §I.7, §III (Phùng Bảo) |  |
| Ch09 | STATE | [Phùng Bảo] Nhà ở Ích Châu | CANON_FACT | Ch09 §IV |  |

**(c) PLANNING_NON_CANON**

Không có dòng PLANNING_NON_CANON cho nhân vật này trong staging.

### 3.12 TÔ (Tô Biệt giá) <a id="nv-to"></a>

**(a) TRẠNG THÁI CUỐI CH22** (dòng staging gần nhất theo từng trường; xem cách đọc ở 0.1)

| Trường | Giá trị (dòng staging gần nhất) | Ch | Source Type | Source |
|---|---|---|---|---|
| APPEARANCE | Có mặt (S2, S4, S6) | Ch08 | CANON_FACT | Ch08 §I.8, I.17, I.32 |
| RELATION(Dịch) | Hỏi "Tiên sinh muốn Ích Châu tin mình, mà bắt đầu bằng sổ lương?"; 17 tờ giấy thông hành nhà họ Tô đều xuôi đông (Dịch gạch "Nhà họ Tô", rồi tự loại Tô) | Ch09 | CANON_FACT | Ch09 §I.10, I.27, §III (Dịch) |
| STATE | Nói "Ấu chủ ở Kim Lăng. Chính thống ở Kim Lăng." (nghiêng Kim Lăng) | Ch08 | CANON_FACT | Ch08 §I.8, §IV |
| STATE | Đề nghị đưa Trình tiên sinh về Kim Lăng — bị gác | Ch09 | CANON_FACT | Ch09 §I.4 (S1 "Chuyện này phải để Kim Lăng xét"), I.23, §IV |
| KNOWLEDGE | Chấp nhận: Phùng Bảo thực sự từng ở bên Thẩm chiêu nghi | Ch08 | CANON_FACT | Ch08 §I.23, §III (Tô) |
| KNOWLEDGE | Hỏi Dịch làm sao biết người trước mặt là đứa trẻ năm ấy; Tô thuật lại một luồng tin Tây Lương (lời nói trên trang) ⟦ô kép → tách 1/2⟧ | Ch08 | CANON_FACT | Ch08 §I.11, I.21 |
| KNOWLEDGE | Biết đề xuất của Dịch và việc Ôn phê ⟦ô kép → tách 1/2⟧ | Ch09 | CANON_FACT | Ch09 §III (Tô) |
| KNOWLEDGE | Chưa nói "tin" Dịch là đứa trẻ năm ấy (Canon Update chỉ ghi "chưa nói tin"; không ghi Tô tin hay không tin) | Ch08 | CANON_UNKNOWN | Ch08 §I.23, §III (Tô) |
| KNOWLEDGE | (nghe thuật lại) "Bên Tây Lương đang truyền rằng họ đã tìm được tung tích Thất hoàng tử năm xưa"; nguồn / thật-giả: OPEN (Ch08 §III) ⟦ô kép → tách 2/2⟧ | Ch08 | CANON_SUSPICION | Ch08 §I.11; Ch08 §III |
| KNOWLEDGE | KHÔNG biết Dịch từng nghi mình; chưa nói "tin" ⟦ô kép → tách 2/2⟧ | Ch09 | CANON_UNKNOWN | Ch09 §III (Tô) |

**(b) LỊCH SỬ before → after** (theo thứ tự chương; không gồm APPEARANCE, đã nằm ở (a); PLANNING nằm ở (c))

| Ch | Trường | Giá trị / Before → After | Source Type | Source | Nối chuỗi |
|---|---|---|---|---|---|
| Ch08 | STATE | Nói "Ấu chủ ở Kim Lăng. Chính thống ở Kim Lăng." (nghiêng Kim Lăng) | CANON_FACT | Ch08 §I.8, §IV |  |
| Ch08 | KNOWLEDGE | Biết như Ôn; tự tay xem khóa trường mệnh, dấu nội phủ | CANON_FACT | Ch08 §III (Tô) |  |
| Ch08 | KNOWLEDGE | Chấp nhận: Phùng Bảo thực sự từng ở bên Thẩm chiêu nghi | CANON_FACT | Ch08 §I.23, §III (Tô) |  |
| Ch08 | KNOWLEDGE | Chưa nói "tin" Dịch là đứa trẻ năm ấy (Canon Update chỉ ghi "chưa nói tin"; không ghi Tô tin hay không tin) | CANON_UNKNOWN | Ch08 §I.23, §III (Tô) |  |
| Ch08 | KNOWLEDGE | Hỏi Dịch làm sao biết người trước mặt là đứa trẻ năm ấy; Tô thuật lại một luồng tin Tây Lương (lời nói trên trang) ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch08 §I.11, I.21 |  |
| Ch08 | KNOWLEDGE | (nghe thuật lại) "Bên Tây Lương đang truyền rằng họ đã tìm được tung tích Thất hoàng tử năm xưa"; nguồn / thật-giả: OPEN (Ch08 §III) ⟦ô kép → tách 2/2⟧ | CANON_SUSPICION | Ch08 §I.11; Ch08 §III |  |
| Ch09 | STATE | Đề nghị đưa Trình tiên sinh về Kim Lăng — bị gác | CANON_FACT | Ch09 §I.4 (S1 "Chuyện này phải để Kim Lăng xét"), I.23, §IV |  |
| Ch09 | KNOWLEDGE | Biết đề xuất của Dịch và việc Ôn phê ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch09 §III (Tô) |  |
| Ch09 | KNOWLEDGE | KHÔNG biết Dịch từng nghi mình; chưa nói "tin" ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch09 §III (Tô) |  |
| Ch09 | RELATION(Dịch) | Hỏi "Tiên sinh muốn Ích Châu tin mình, mà bắt đầu bằng sổ lương?"; 17 tờ giấy thông hành nhà họ Tô đều xuôi đông (Dịch gạch "Nhà họ Tô", rồi tự loại Tô) | CANON_FACT | Ch09 §I.10, I.27, §III (Dịch) |  |

**(c) PLANNING_NON_CANON**

Không có dòng PLANNING_NON_CANON cho nhân vật này trong staging.

## 4. NHÂN VẬT PHỤ

### 4.1 Nhân vật có khối riêng thứ yếu trong staging (rút gọn: dòng vai/lần đầu và dòng trạng thái cuối mà Canon Update nêu)

| Nhân vật | Vai / nhãn (theo staging) | Ch | Ghi nhận (dòng staging) | Source Type | Source |
|---|---|---|---|---|---|
| Hoắc Thành Lĩnh | Hoắc tướng quân; "cha" của Tam Lang | Ch01 | mốc cũ "15 năm trước"/"14 năm trước" (Canon Update không nói mốc nào ứng việc nào) → năm -20: dẫn quân vây phủ Bùi và bí mật để cửa sau mở | CANON_FACT | Ch01 §IX |
| ↳ |  | Ch02 | (đầu dải) → first; tóc bạc quá nửa, dáng cao, lưng thẳng | CANON_FACT | Ch02 §I.13 |
| ↳ |  | Ch06 | → hai thân binh chết trước cửa; ông nằm cạnh bàn, giáp khoác nửa, tay phải nắm chuôi đao, trọng thương dưới sườn; nắm tay con, nói "A Chiêu", "…quân…", rồi mất | CANON_FACT | Ch06 §I.13, §I.18, §I.20 |
| ↳ |  | Ch07 | (lời đồn) Hoắc tướng quân đã chết (nơi chết kể hai cách) | CANON_SUSPICION | Ch07 §III, §II |
| Lão Tần | (heading staging không ghi vai) | Ch06 | (đầu dải) → first; thân binh trưởng của Hoắc, theo Hoắc từ trước khi nàng ra đời, tóc bạc trắng; vào thư phòng, quỳ, chạm trán xuống sàn, không nói | CANON_FACT | Ch06 §I.22 |
| ↳ |  | Ch06 | → lấy từ ngăn dưới cùng tủ gỗ sau bàn hộp bọc da chứa nửa hổ phù đồng mòn góc; quỳ một gối trước bảy, tám đội trưởng: "Binh phù của Hoắc gia quân, giao cho Tam công tử."; khoác chiến bào, đưa mũ trụ | CANON_FACT | Ch06 §I.23–24, §I.29 |
| Tôn Đức | quản kho; bên giao kho Vân Trung | Ch01 | → đã cất sổ kho vào trong; giữ sổ kho gốc ở kho lương | CANON_FACT | Ch01 §VI |
| ↳ |  | Ch04 | bên giao trong sổ đoàn là kho Vân Trung (Tôn Đức); bên nhận quản lương đoàn Tào Huệ | CANON_FACT | Ch04 §I.18 |
| Tạ Diên | cha của Vân Chương | Ch04 | (đầu dải) → ở tầng cao triều đình từ năm -21 (không ghi chức danh) | CANON_FACT | Ch04 §I.5 |
| ↳ |  | Ch05 | → đưa Vân Chương bộ sử chép tay 12 quyển; thư trang hai nhắc rượu mơ ủ bảy bình, mai nở sớm hai mươi ngày, tuyết dày bốn tấc; mật mã quyển-trang-dòng-chữ, chữ đã tra không mã hóa lại; nội dung giải: Trừ tịch. Tý. Bắc. Môn. Bất quan. Nhi. Xuất. Nam. Vật. Lưu. | CANON_FACT | Ch05 §I.1–5 |
| ↳ |  | Ch08 | Chết (năm -4 → -2) | CANON_FACT | Ch08 §VII |
| Mạnh tướng quân | tướng hộ tống đoàn họ Mạnh | Ch01 | (đầu dải) → tướng hộ tống đoàn, họ Mạnh | CANON_FACT | Ch01 §I.11 |
| ↳ |  | Ch05 | → hộ vệ do ông dẫn có lệnh bài; nhận lệnh "Giữ công chúa ở đây tới sáng…"; ở miếu ngoài thành cùng hộ vệ | CANON_FACT | Ch05 §I.12, §I.28, §V |
| Viên quan Kim Lăng | vô danh | Ch12 | Tại đình: "Bệ hạ muốn các nơi phụng chiếu trước." — nhìn Vân Chương rồi thôi; ngồi sau Vân Chương | CANON_FACT | Ch12 §I.10, Ch13 §I.28 |
| ↳ |  | Ch13 | Đã sai một người phi ngựa về Kim Lăng từ trước giờ Ngọ; nói "Hạ quan nghe ở bến. Sợ triều đình biết muộn."; gửi "về triều", không tên | CANON_FACT | Ch13 §I.28–29, §IV |
| Viên quản lương ải Tây | vô danh | Ch08 | Xin thêm lương mùa hè (lý do "đường bên Tây Lương có biến"); khi Dịch hỏi "Hàng đi qua ải?" thì khựng lại, nói lảng; hỏi và biết họ "Trình" | CANON_FACT | Ch08 §I.2, I.4–5, §III |
| ↳ |  | Ch09 | Trọ nhà Đỗ ngày 1 → ngày 4 (ngày 4 trả phòng, về ải); là mắt xích Hàn nhờ nhắn miệng cho ải Tây (không nói tên Dịch) | CANON_FACT | Ch09 §I.17, I.20 |
| Kẻ đếm thuyền | người lạ ở bến dưới Lạc Thủy; vô danh | Ch13 | Rời bến tảng sáng ngày 3 → quán nước ở làng bên → người bán củi; đứng ngoài bốn vòng gác, không nghe được gì bên trong | CANON_FACT | Ch13 §I.20, I.23, §VII |
| ↳ |  | Ch13 | Đầu dây phía Hạ Hầu (theo Chỉ, qua ba mắt xích; Canon Update ghi FACT) | CANON_FACT | Ch13 §III (Chỉ) |
| Kha Trọng | còn gọi "lão Kha" theo lời đồn — Canon Update chưa xác nhận cùng một người (CB-L-31) | Ch14 | Sổ Nam Môn: "Kha Trọng, người Lạc Kinh, buôn giấy, vào ngày 26 tháng Chạp" | CANON_FACT | Ch14 §I.8; Ch14 §I.24 |
| ↳ |  | Ch14 | Sổ thuê ngựa Thạch Kiều: "Người bảo lãnh: Kha Trọng"; người giữ trạm nói lão ấy bảo lãnh người lạ ở đây không phải lần đầu (lời người giữ trạm) | CANON_FACT | Ch14 §I.23 |
| ↳ |  | Ch14 | Chưa kết luận: cùng một người (sổ cũ = sổ thuê ngựa = lão Kha); còn sống; liên quan Bắc Môn; liên quan Chu Hạc; Tạ gia đứng sau; chủ mưu | CANON_UNKNOWN | Ch14 §II (G-2) |
| Tu Bặc Cốt | thủ lĩnh bộ lớn nhất phía đông | Ch18 | Thủ lĩnh bộ lớn nhất phía đông, kết thân với Hách Liên Chước | CANON_FACT | Ch18 §I.4 |
| ↳ |  | Ch18 | Bị xử theo luật "Kẻ giết thương nhân dưới cờ chợ, đền bằng mạng": đã chết, không mô tả hành hình; người giữ sổ gạch tên; đàn đợt ba sung chợ biên | CANON_FACT | Ch18 §I.18, §I.20; Ch18 §0; Ch18 §IV |
| Hách Liên Chước | (heading staging không ghi vai) | Ch10, Ch12 | Ch10: thử bến chính ban ngày, toán kỵ đi đầu sụt qua băng, chìm; sau dựng trại dọc bờ bắc. Ch12: Uyển "Ta không nói thay Hách Liên"; Gate R3: Hách Liên biết Uyển vắng Bắc cảnh | CANON_FACT | Ch10 §I.19; Ch12 §I.24, §IV |
| ↳ |  | Ch18 | Người của hắn đứng dậy trước, nhìn Uyển một lần, đi | CANON_FACT | Ch18 §I.21 |
| ↳ |  | Ch18 | (nghe thuật lại qua người già bộ nhỏ) rạng sáng: Hách Liên cho thổi tù và dọc bờ bắc, các bộ thân Tu Bặc Cốt kéo về doanh hắn; Canon Update ghi "Đang tập hợp quân (tin; chưa hành động); có cớ" | CANON_SUSPICION | Ch18 §I.26; Ch18 §IV |
| ↳ |  | Ch18 | Quân số; mục tiêu; có sai Tu Bặc Cốt không; quan hệ với Hạ Hầu | CANON_UNKNOWN | Ch18 §II |
| ↳ |  | Ch19–Ch22 | không xuất hiện; Ch20: Vân Chương chưa biết (tập quân) ⟦ô kép tách thủ công 1/2; ST gốc: CANON_FACT; "→ Ch25" là PLANNING_NON_CANON⟧ | CANON_FACT | Ch19 §II; Ch20 §II; Ch21 §II-A; Ch22 §IX |
| Tiểu Thất | thân binh của Chiêu; đã chết (Ch17) | Ch17 | first có tên; đọc sổ hạn; nhận lệnh "Tiểu Thất. Lấy mũ."; đốt thử một nén hương; giữ ống hương buộc ở yên | CANON_FACT | Ch17 §I.1, §I.10, §I.14, §I.30 |
| ↳ |  | Ch17 | Nhường ngựa cho Chiêu, đứng vào khe giữa nàng và kỵ viện; chết, nằm lại trên bờ đất ("Tiểu Thất chết rồi." — "Ta biết.") | CANON_FACT | Ch17 §I.27–I.28; Ch17 §0 |
| ↳ |  | Ch19 | đã chết (Ch17); Chiêu ngồi trên ngựa Tiểu Thất; Dịch ghi tên vào sổ người chết | CANON_FACT | Ch19 §0 (Sync Ch17); Ch19 §I.4; Ch19 §II (Tên) |
| "G" — Tướng giữ Hổ Lao | vô danh; chỉ qua thư và người đưa thư | Ch20 | (đầu dải) chỉ qua người đưa thư (bụi đường, hai tay trống, "Đường riêng"); phong thư niêm sáp có dấu chức, không tên: "Tướng giữ Hổ Lao."; dòng đầu "Hổ Lao xin hàng." | CANON_FACT | Ch20 §I.22–23 |
| ↳ |  | Ch21 | thư lên trang: "Ba điều… Được cả ba, xin định một đêm. Thuyền Kim Lăng tới bến, tướng ra nhận." Ký chức "Tướng giữ Hổ Lao." (không tên); thư không hứa mở cổng | CANON_FACT | Ch21 §I.2 |
| ↳ |  | Ch22 | "Ai giữ thành đêm qua?" — "Một tướng của Hạ Hầu. Không thấy từ đêm qua." (lời quan cũ) ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch22 §I.26; Ch22 §II-A; Ch22 §IX |
| ↳ |  | Ch22 | Tướng giữ thành đêm qua có là G không: Canon Update không nói (⚠ xem CB-L-22) ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch22 §I.26; Ch22 §II-A; Ch22 §IX |
| Phó tướng thủy quân | vô danh | Ch19 | thuyền Kim Lăng dỡ thóc ở bãi kho cháy: "Thóc. Ba chuyến. Mỗi chuyến hai ngày."; "Dỡ ở bãi cháy."; "Giá chợ cũ."; thuyền "chưa công nhận ai" | CANON_FACT | Ch19 §I.9, I.15; Ch19 §IV (Thuyền Kim Lăng) |
| ↳ |  | Ch22 | báo lịch ("Thuyền tới vào đêm thứ ba kể từ đêm nay. Lương bằng bốn chuyến mọi kỳ cộng lại."); "Sông do thủy quân giữ. Ta ghi sổ."; "Sổ kho Hổ Lao. Một bản, gửi Kim Lăng."; "Thuyền chưa dỡ. Lương còn nguyên." | CANON_FACT | Ch22 §I.2, I.22, I.24 |
| Sĩ quan Ích Châu | vô danh; trên trang có thể là nhiều người (CB-L-29) | Ch19 | một sĩ quan nghe thư Bàng: "Bán lương cho kẻ vừa..." — Dịch gõ "Một nghìn suất", im | CANON_FACT | Ch19 §I.6 |
| ↳ |  | Ch22 | "người từng đứng sau lưng Dịch trước cổng Dĩnh Xuyên" (vô danh) hô "Hàng binh không giết, có ăn!"; "Đuổi."; "Chúng giết bộ ta ở cổng đêm qua. Ngươi để chúng đi."; "Ngươi cho chúng cầm xô."; "Ai đổ máu, người ấy giữ." | CANON_FACT | Ch22 §0 (Sync Ch19); Ch22 §I.14, I.16–17, I.19, I.21 |
| Ấu đế | không tên húy; chỉ Ch20 trong dải | Ch20 | ngồi trên ngai quá lớn, hai chân không chạm đất; bàn tay nhỏ đặt lên ấn, quan giữ ấn đặt tay lên trên, ấn xuống | CANON_FACT | Ch20 §I.10, I.15 |
| ↳ |  | Ch20 | chiếu nêu tên Dịch; "nay có ngai đứng tên" | CANON_FACT | Ch20 §VI |

### 4.2 Nhân vật phụ khác (gộp từ 4 bảng "Nhân vật phụ" của staging; 1 dòng staging / 1 nhân vật hoặc nhóm)

| Nhân vật / vai (theo Canon Update) | Ch | Trạng thái / ghi nhận (dòng staging) | Source Type | Source |
|---|---|---|---|---|
| Tri phủ (Vân Trung) | Ch01, Ch03, Ch05 | ngoài năm mươi, béo, cẩn thận (Ch5); giao Dịch đối sổ mùa đông (Ch1); ra lệnh giữ toàn bộ áo bông dự trữ cho đoàn trước ngày 0 (Ch3); ngày 25 Chạp từ chối cho cả đoàn ra, chỉ cấp lệnh bài theo danh sách (Ch5) | CANON_FACT | Ch01 §I.3; Ch03 §I.15; Ch05 §I.12 |
| Người mặc áo lính hỏi thăm Dịch | Ch01 | biết Dịch đi Tịnh Châu và đang đối sổ; danh tính chưa xác định | CANON_UNKNOWN | Ch01 §III |
| Thẩm chiêu nghi (Thẩm Chiêu Nghi) | Ch01, Ch04 | bị vu tội/kết tội năm -21; tên chứa chữ "Huệ" (người hầu tránh bằng bỏ một nét); mẹ của Vân Chương: không có thông tin (không liên quan) | CANON_FACT | Ch01 §IX; Ch04 §I.7–8 |
| Chủ quán trọ (sau chợ Bắc) | Ch02 | kể Chỉ tin Tam công tử về thành; "không có dữ liệu gì về người này" | CANON_FACT | Ch02 §I.5 |
| Người gia nhân năm ấy | Ch02 | còn sống hay đã chết: không khóa; danh tính người kéo Chỉ ra: không khóa | CANON_UNKNOWN | Ch02 §II |
| Chủ sự Hộ phòng | Ch03 | nói xin thêm áo từ châu "nhanh cũng qua tháng" | CANON_FACT | Ch03 §I.18 |
| Lão quản kho (hậu doanh, vô danh) | Ch03 | ước áo thải "ba bốn cái"; biết A Quy là kẻ đột nhập, làm theo lệnh | CANON_FACT | Ch03 §I.11, §III |
| Người lính trẻ (hậu doanh, vô danh) | Ch03, Ch06 | người đã bó chân cho Chỉ ở Ch2; giám sát A Quy, thu kim, khám người; chạng vạng Ch6 mang bát cơm tất niên cho A Quy | CANON_FACT | Ch03 §I.6; Ch06 §I.5 |
| Tào Huệ (Tào quản sự) | Ch04 | quản lương của đoàn, bên nhận trong sổ đoàn | CANON_FACT | Ch04 §I.18 |
| Thị nữ của Uyển | Ch04, Ch05 | mang thuốc sắc vỏ quýt cho Vân Chương; theo Uyển ở miếu | CANON_FACT | Ch04 §I.33; Ch05 §V |
| Tùy tùng của Vân Chương | Ch05 | rời miếu cùng chàng; ở lại ngoài Nam Môn, được dặn nếu tới sáng chưa ra thì về miếu báo ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch05 §I.29–31, §II |
| Tùy tùng của Vân Chương | Ch05 | có về báo hay không: không phải Canon ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch05 §I.29–31, §II |
| Thủ môn quan Nam Môn | Ch05 | đang ăn tất niên, còn say; mở cửa ngách cho một người | CANON_FACT | Ch05 §I.30 |
| Phu xe, người hầu, tạp dịch của đoàn | Ch05 | ở lại dịch quán đêm trừ tịch | CANON_FACT | Ch05 §I.14 |
| Tiểu Tứ (thân binh) | Ch06 | do Tam Lang sai báo cha; không quay lại; số phận OPEN | CANON_UNKNOWN | Ch06 §I.9, §I.12, §0A |
| Người lính trông phòng củi | Ch06 | không thấy đâu; số phận OPEN | CANON_UNKNOWN | Ch06 §I.32, §II |
| Lính gác trẻ chết dưới vòm Bắc Môn | Ch06 | khoảng 17–18 tuổi, áo bông kép cấp cho lính gác đêm, một tay giơ ra trước, vết chém ở cổ ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch06 §I.42, §II |
| Lính gác trẻ chết dưới vòm Bắc Môn | Ch06 | đã làm gì: không phải Canon ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch06 §I.42, §II |
| Xác người Bắc Nhung (thư phòng) | Ch06 | áo da cừu, tóc tết nhiều bím, tay nắm dao cong ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch06 §I.19, §II |
| Xác người Bắc Nhung (thư phòng) | Ch06 | ai giết: không phải Canon ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch06 §I.19, §II |
| Hai người khiêng then (Ch7) | Ch07 | hai bóng người dưới hai ngọn đuốc, không thấy mặt ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch07 §I.2, §II |
| Hai người khiêng then (Ch7) | Ch07 | danh tính: không phải Canon ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch07 §I.2, §II |
| Thông ngôn Bắc Nhung | Ch07 | đọc điều kiện đòi Vĩnh Ninh công chúa, đọc lại thêm hai lần (giữa giờ Sửu) | CANON_FACT | Ch07 §I.18 |
| Hàng xóm trong ngõ | Ch07 | Dịch không báo; lúc Dịch rời đi vẫn xem pháo ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch07 §I.6, §III |
| Hàng xóm trong ngõ | Ch07 | không rõ ai còn sống ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch07 §I.6, §III |
| Lính xét ở Nam Môn (Hoắc gia quân) | Ch07 | bắt đàn ông trẻ bỏ mũ, đi vài bước, nhìn mặt/chân, không hỏi tên; cho Dịch qua | CANON_FACT | Ch07 §I.33 |
| Người đưa tin Tây Lương | Ch08–Ch09 | Ch08: vào công đường, quỳ "Thất điện hạ"; chỉ biết có "Thất điện hạ ở Ích Châu", nhận ra Dịch theo phản ứng của Ôn. Ch09: nghỉ ở dịch quán; rời thành hôm sau ngày tới (ngày 15), tay không | CANON_FACT | Ch08 §I.32–34, §III; Ch09 §I.1, I.29 |
| Viên quan già | Ch08–Ch09 | Ch08: "chuyện ấy năm nào cũng có người đồn". Ch09: nghiêng hồi âm mềm mỏng cho Bàng; biết các đề xuất đã được phê | CANON_FACT | Ch08 §I.11; Ch09 §I.23, §III |
| Thư lại trẻ phòng sổ | Ch08–Ch09 | Ch08: vẫn gọi "Trình tiên sinh" nhưng lùi xa một bước. Ch09: cùng Dịch và một lính canh kho kiểm kê gian thứ chín | CANON_FACT | Ch08 §I.29; Ch09 §I.15 |
| Thẩm chiêu nghi | Ch08–Ch11 | Dịch: "Ta là con của Thẩm chiêu nghi." (Ch08). Hai cây quế, cành gãy buộc dây gai (lời Phùng Bảo). Đơn Dạ Kiêu nhắm "người tự nhận là con của Thẩm chiêu nghi" (Ch11) ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch08 §I.19, I.23; Ch11 §I.6, §III |
| Thẩm chiêu nghi | Ch08–Ch11 | Bùi gia – Thẩm chiêu nghi: Chỉ không biết liên hệ ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch08 §I.19, I.23; Ch11 §I.6, §III |
| Ấu chủ | Ch08 | Được Vân Chương phò ra khỏi kinh, xuôi về Kim Lăng; "Ấu chủ ở Kim Lăng. Chính thống ở Kim Lăng." (lời Tô) ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch08 §I.6, I.8, §III |
| Ấu chủ | Ch08 | tình cảm chú–cháu của Dịch: KHÔNG CÓ trong Ch08 ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch08 §I.6, I.8, §III |
| Hoàng thượng (hoàng huynh của Dịch) | Ch08 | Băng (tin Lạc Kinh thất thủ); phụ hoàng của Dịch băng khoảng năm -6, hoàng huynh kế vị | CANON_FACT | Ch08 §I.6, §VII |
| Tiết tướng quân (ải Tây, Ch09 §IV) | Ch09 | "Tiết tướng quân cùng Hàn đi lính từ năm mười sáu tuổi" (lời Hàn); Hàn sợ Tiết dâng biểu vội. Canon Update không ghi rõ Tiết = "tướng giữ ải Tây" ở Ch08 §I.9; chỉ ghi "Tiết tướng quân (ải Tây)" ở Ch09 §IV (⚠ xem CB-L-33) ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch09 §I.20, §IV, §II |
| Tiết tướng quân (ải Tây, Ch09 §IV) | Ch09 | phản ứng của Tiết, việc Hàn xử lý ải Tây: OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch09 §I.20, §IV, §II |
| Nhà Đỗ | Ch09 | Tên lặp lại nhiều nhất trên giấy thông hành đi tây; thuê gian thứ chín ba năm; bị thu hồi giấy thông hành, gian bị niêm (theo phê của Ôn) | CANON_FACT | Ch09 §I.11, I.14, §IV |
| Khương lão tướng | Ch10 | Râu bạc; muốn lui; đề nghị bỏ đồn lui về Vân Trung (cuối tháng Giêng); ủng hộ nhận đình chiến ("Nhận rồi còn đường về") | CANON_FACT | Ch10 §I.5, I.21, I.35, §III |
| Tướng trẻ (vô danh) | Ch10 | Muốn đánh qua sông; cùng vài người cạnh quay mặt đi khi Chiêu nhận đình chiến ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch10 §I.35, I.37, §II |
| Tướng trẻ (vô danh) | Ch10 | tên: OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch10 §I.35, I.37, §II |
| Sứ giả của Khả đôn (ông già Bắc Nhung) | Ch10 | Qua sông dưới cờ trắng; dâng mũ trụ; đặt quân cờ trắng lên mép bàn; "Đừng đuổi qua sông." ⟦ô kép tách thủ công 1/2; ST gốc: CANON_FACT; "không biết nghĩa" PLANNING_NON_CANON⟧ | CANON_FACT | Ch10 §I.25–26, I.38, §II |
| Cánh trái (đội trưởng) | Ch10 | Từng lùi về bến chính vì thấy cờ đổ và mũ trụ trên giáo giặc; thấy Chiêu sống, vào hàng | CANON_FACT | Ch10 §I.15–16 |
| Trung gian (đưa đơn Dạ Kiêu) | Ch11 | Trung niên, áo vải xám; không hỏi khi bị trả tiền; đếm lại, nhìn lâu, đi không chào; quan hệ với Dạ Kiêu "sứt" | CANON_FACT | Ch11 §I.4, I.26, §IV |
| Chủ quán (quán trọ ba gian ở bến sông) | Ch11 | Giữ đầu mối Dạ Kiêu; gạch một hàng ký hiệu khi đơn bị trả | CANON_FACT | Ch11 §I.1, I.26 |
| Người dò tin bị bắt (người của Dạ Kiêu) | Ch11 | Bị lính giữ thành bắt ở cửa kho phía nam; chưa khai, chỉ biết chủ quán ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch11 §I.10, I.27, §IV; Ch13 §IX |
| Người dò tin bị bắt (người của Dạ Kiêu) | Ch11 | số phận: OPEN (Ch13 §IX giữ OPEN) ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch11 §I.10, I.27, §IV; Ch13 §IX |
| Lão bộc già (nhà Dịch) | Ch11 | Ở cùng Dịch trong hai gian nhà thuê sau phủ | CANON_FACT | Ch11 §I.9 |
| Đội trưởng hộ tống Ích Châu (vô danh) | Ch12 | Nói "Hàn Đô úy không dặn việc này" khi Dịch bảo chứng A Quy | CANON_FACT | Ch12 §I.2, I.16 |
| Viên quân nhu (Hoắc quân) | Ch13 | Gọi to một con số, ngắt câu "Đêm ấy…" của Dịch | CANON_FACT | Ch13 §I.7 |
| Thị nữ của Uyển | Ch13 | Bưng chén nước vỏ quýt đặt trước Vân Chương (callback Ch4) | CANON_FACT | Ch13 §I.17, §0 |
| Hai người chèo thuyền | Ch13 | Nói nhỏ, một người nhắc Kim Lăng; Uyển không nghe rõ | CANON_FACT | Ch13 §I.19 |
| Người bán củi / quán nước ở làng bên | Ch13 | Hai mắt xích trong đường dây tới Lạc Kinh; người bán củi qua cửa có quân Hạ Hầu giữ, không bị khám | CANON_FACT | Ch13 §I.20 |
| Người giữ sổ (thuộc hạ Chỉ) | Ch14 | Đứng cửa nhìn từng người ra, không hỏi; gọi Chỉ "đương gia"; "Có thể chỉ là trùng tên."; "Họ Tạ ở Lạc Kinh không ít."; vô danh | CANON_FACT | Ch14 §I.3–I.4, §I.25, §I.27; Ch14 §II |
| Người đi bến (thuộc hạ Chỉ) | Ch14 | Chuyển câu "Đường văn thư – trạm ngựa Kim Lăng có lỗ." tới Vân Chương và đem về lời nhắn; không hỏi lỗ ở đâu | CANON_FACT | Ch14 §I.18, §I.20 |
| Hai người canh (thuộc hạ Chỉ) | Ch14 | Nhận chỗ và đêm vào tai lúc chập tối; người canh thứ nhất theo hai người lạ, chậm một nhịp | CANON_FACT | Ch14 §I.13, §I.17 |
| Người theo chân (thuộc hạ Chỉ) | Ch14 | Bị một người lạ nhìn thẳng mặt đủ nhớ; Chỉ: "Đổi người." | CANON_FACT | Ch14 §I.22 |
| Người ở trạm Thạch Kiều (người của Chỉ) | Ch14 | Mang mảnh giấy chép sổ thuê ngựa; kể người giữ trạm nói lão bảo lãnh người lạ không phải lần đầu | CANON_FACT | Ch14 §I.23 |
| Người giữ trạm Thạch Kiều; chủ quán gần đó | Ch14 | Hai tầng đầu trong ba tầng miệng lời đồn lão Kha | CANON_FACT | Ch14 §I.26 |
| Hai người lạ ở miếu / trạm Thạch Kiều | Ch14 | Ngồi sẵn trên bậc miếu đêm 11; thuê hai ngựa đi Lạc Kinh ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch14 §I.14, §I.22–I.23; Ch14 §II |
| Hai người lạ ở miếu / trạm Thạch Kiều | Ch14 | ai là, ai sai: OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch14 §I.14, §I.22–I.23; Ch14 §II |
| Người giữ ngựa ở trạm gần bến | Ch14 | Không biết chữ; nhận tờ giấy T5 đưa người đưa thư đoàn Kim Lăng | CANON_FACT | Ch14 §I.2 |
| Đội trưởng hộ tống Ích Châu (T1) | Ch14 | Hỏi Chỉ "miệng nào bên thuyền Kim Lăng nói ra ngoài?"; nhận một chỗ hẹn miệng | CANON_FACT | Ch14 §I.2, §I.9; Ch14 §III |
| Thân binh Tam tướng quân / Hoắc quân (T2) | Ch14 | Hỏi Chỉ "tin ở bến, Dạ Kiêu biết nó giả từ lúc nào?"; nhận một chỗ hẹn miệng | CANON_FACT | Ch14 §I.2, §I.9; Ch14 §III |
| Viên quan Kim Lăng (K2, theo Ch15 §II) | Ch14, Ch15–Ch18 | Hỏi Chỉ "người ở Ích Châu có sai người tung tin công nhận hay không?" ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch14 §I.9 |
| Viên quan Kim Lăng (K2, theo Ch15 §II) | Ch14, Ch15–Ch18 | "K2 (viên quan Kim Lăng)" giữ OPEN (Ch15–Ch16) ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch15 §II; Ch16 §II |
| Hoắc quân (tập thể; "Hoắc quân chờ lời đáp") | Ch14 | Chờ lời đáp của Chỉ; Chỉ: "Chưa." (nhãn "Hoắc quân" ở Ch14 không gắn tên Chiêu) | CANON_FACT | Ch14 §I.21; Ch14 §IV |
| A Quy (qua "Lệnh bắt A Quy") | Ch14–Ch17 | Chỉ qua lệnh: Ch14 "Còn; hoãn qua mùa đông"; Ch17 "Lệnh còn." ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch14 §IV; Ch17 §I.1 |
| A Quy (qua "Lệnh bắt A Quy") | Ch14–Ch17 | Ch15: lệnh bắt OPEN; A Quy ở đâu: OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch15 §V; Ch17 §II |
| Chu Hạc; Tiết tướng quân; Khương lão tướng; Lão Tần; quân trắng; Hách Liên Chước (OPEN list) | Ch14–Ch18 | Chỉ nằm trong danh sách giữ OPEN; Ch14 §II: Kha Trọng "liên quan Chu Hạc" chưa kết luận; không thêm dữ liệu | CANON_UNKNOWN | Ch14 §II; Ch15 §IX; Ch16 §IX; Ch17 §IX; Ch18 §IX |
| Lão phu đầu | Ch15, Ch16 | Ch15: "Lương, tiên sinh…" — "Người trước."; Ch16: có mặt cùng đoàn tới làng, không lời | CANON_FACT | Ch15 §I.17; Ch16 §I.14; Ch16 §0 |
| Sĩ quan Ích Châu (người liếc Dịch; người đòi trả đũa; một người xin về) | Ch15–Ch16 | Liếc Dịch khi nghe nhắc thư; "Ích Châu đã mất một nghìn tám."; "Bán lương cho kẻ vừa giết một nghìn tám?"; xin áp tải thương binh, Hàn: "Đi."; vô danh | CANON_FACT | Ch15 §I.22, §I.30; Ch16 §I.8, §I.25–I.26; Ch16 §0 |
| Phó tướng Hoắc quân | Ch15, Ch16 | Ch16: "Cho ta một trận."; "Còn kẻ báo tin?"; dẫn nửa quân về biên trong ba ngày; Ch15: "Ai biết cột ấy đi hướng nào?" | CANON_FACT | Ch15 §I.31; Ch16 §I.7, §I.10, §I.12 |
| Phó tướng thủy quân Kim Lăng | Ch15–Ch17 | "Kim Lăng đợi thấy việc."; "Băng trôi."; ghi sổ "Thuyền Kim Lăng chở lương đường sông cho liên quân"; cọc là gốc liễu cụt; vô danh | CANON_FACT | Ch15 §I.7, §I.31; Ch16 §I.13; Ch17 §I.14 |
| Tô; Phùng Bảo | Ch15–Ch17 | Ch16: Ôn, Tô, Hàn, Dịch đã xem "việc kia"; Ch16, Ch17: Tô, Phùng Bảo không xuất hiện ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch16 §II; Ch16 §III; Ch17 §III |
| Tô; Phùng Bảo | Ch15–Ch17 | Tô: nhắc trong §IX Ch15 ("Phản ứng của Ôn; Tô") — giữ OPEN ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch15 §IX |
| Làng trưởng (làng ven sông) | Ch16 | Bán một phần ba, giữ thóc giống; phiếu nợ ký Dịch + Hàn; nhắc "chợ Dĩnh Xuyên"; vô danh | CANON_FACT | Ch16 §I.14–I.20; Ch16 §III |
| Đội trưởng kỵ nhẹ Hoắc quân | Ch16, Ch17 | Nghe hồi âm ở cửa lều; báo Chiêu hồi âm chỉ lương | CANON_FACT | Ch16 §I.21, §I.27; Ch17 §I.2 |
| Thân binh (vô danh) của Chiêu ở hoàng hôn ngày 36 | Ch17 | Hỏi "Rút?" — "Chưa."; báo Tiểu Thất chết | CANON_FACT | Ch17 §I.28, §I.32 |
| Hai kỵ trinh sát Hạ Hầu | Ch17 | Nhìn chùm lông đen rất lâu rồi quay đi | CANON_FACT | Ch17 §I.22 |
| Đô úy giữ Dĩnh Xuyên; quan coi kho | Ch17 | Vô danh, không xuất hiện; số phận không nêu | CANON_UNKNOWN | Ch17 §I.4; Ch17 §II |
| Người chèo thuyền Kim Lăng | Ch17 | Xuôi hai chuyến, thấy kho (nguồn tin của Dịch) | CANON_FACT | Ch17 §I.4 |
| Ông già sứ (râu tết hai bím) | Ch18 | Giữ hội khi Uyển ra giếng; ngồi ngoài vòng lửa; vô danh | CANON_FACT | Ch18 §0; Ch18 §I.9, §I.22 |
| Người già bộ nhỏ phía đông (áo da sờn vai) | Ch18 | Đưa nén bạc, báo ngựa đi tây; rạng sáng báo tin Hách Liên; ở lại sau phiên xử | CANON_FACT | Ch18 §I.2, §I.21, §I.26 |
| Thủ lĩnh bộ nhỏ (có ngựa chưa nhận bạc) | Ch18 | Hỏi ở hội "đưa đi đâu?"; nhận nửa giá; dẫn người đi | CANON_FACT | Ch18 §I.7, §I.19, §I.21 |
| Thủ lĩnh râu rậm | Ch18 | Lần này nàng gật; ông đọc luật; ở lại sau phiên xử | CANON_FACT | Ch18 §I.18, §I.21; Ch18 §0 |
| Người của Hách Liên Chước (hàng sau cùng) | Ch18 | Giáp da, không nói, rời hội sau phiên xử | CANON_FACT | Ch18 §I.5, §I.8, §I.21 |
| Thương nhân Hán sống sót; chủ đoàn buôn (đã chết) | Ch18 | Kể "Cờ chợ. Họ không xem cờ."; dải vải đỏ và xanh; "Chủ ta chết." | CANON_FACT | Ch18 §I.11, §I.16 |
| Ba người áo bụi (giọng miền tây, một người tay có vết mực) | Ch18 | Đi giữa đàn Tu Bặc Cốt; "Khả đôn nhầm chỗ."; đi tay không, không ai chặn | CANON_FACT | Ch18 §I.12, §I.14 |
| Toán kỵ độc lập | Ch18 | "Giếng này không cho qua." — quay ngựa rời giếng (không ai trả công) | CANON_FACT | Ch18 §I.13, §I.21 |
| Thị nữ; chỉ huy trướng quân; người giữ sổ (Ch18) | Ch18 | Thị nữ hỏi về gói vỏ quýt; trướng quân dẫn Tu Bặc Cốt ra rìa bãi; người giữ sổ gạch tên hắn; vô danh | CANON_FACT | Ch18 §I.4, §I.20, §I.24 |
| Đô úy thành Dĩnh Xuyên | Ch19 | hiện một lần, nhìn Dịch, nhìn cổ chai; không giơ tay, không nói; sau cổng "Đô úy?" — tay buông; số phận OPEN | CANON_FACT | Ch19 §I.19; Ch19 §II |
| Quan coi kho (Dĩnh Xuyên) | Ch19–Ch20 | "Ta coi kho bến. Kho cháy dưới tay ta."; "Ai hỏi tội kho cháy, ta đọc câu ấy."; ra trước khi cổng mở; Ch20: đứng đầu những người mở cửa cùng hào chợ (thư lại thành chép) | CANON_FACT | Ch19 §I.19; Ch20 §I.3 |
| Hào chợ (Dĩnh Xuyên) | Ch19–Ch20 | áo dày, túi muối bên thắt lưng; "Chợ Dĩnh Xuyên hỏi. Ngài là người họ Tiêu?"; "Mở."; Ch20: nằm trong báo cáo | CANON_FACT | Ch19 §I.19; Ch20 §I.3 |
| Làng trưởng | Ch19 | tới bằng xuồng nhỏ, mua thóc bằng muối Ích Châu đã nhận từ trước; "Tôi ăn rồi." | CANON_FACT | Ch19 §I.15, I.19 |
| Thư lại thành (Dĩnh Xuyên) | Ch19 | dán tờ văn nhàu dính bùn lên cổng bằng chén hồ; ai nhặt/lúc nào Dịch không thấy | CANON_FACT | Ch19 §I.20 |
| Sứ Hạ Hầu (một kỵ cờ trắng) | Ch19 | đưa thư Bàng: "Thư chỉ bàn việc lương." | CANON_FACT | Ch19 §I.5–6 |
| Thư lại soạn (Kim Lăng) | Ch20–Ch21 | soạn chiếu; hỏi "Nhận người hay nhận việc?"; Ch21: đối sổ, gạch nửa tháng lương, ghi thay Vân Chương từ đêm thứ ba | CANON_FACT | Ch20 §I.5–8; Ch21 §I.11, I.19 |
| Quan giữ ấn | Ch20–Ch21 | "Hạ quan chỉ giữ ấn, không chứng."; Ch21: "Thư này đóng ấn nào?" — "Dấu của ta." — "Vào sổ?" — "Không." | CANON_FACT | Ch20 §I.15, I.20; Ch21 §I.15 |
| Ông áo tía (ngoại thích) | Ch20 | "Ấn tước, ai giữ?"; hôn thư cùng ngày; đứng yên khi cúi chào chiếu; không hài lòng; Ch21 vắng | CANON_FACT | Ch20 §I.13, I.15; Ch20 §IV; Ch21 §II-A |
| Tướng râu quai nón (võ tướng) | Ch20–Ch21 | "Quân ta ăn lương của ai?"; hôn thư (con trai ông); Ch21: sĩ quan của võ tướng xem sổ kho, không nói | CANON_FACT | Ch20 §I.12–13; Ch21 §I.20 |
| Ông già tóc bạc (văn quan) | Ch20 | "Ân xá rộng như vậy là bỏ pháp."; "Hạ Hầu có nhận chiếu này không?" — không ai đáp | CANON_FACT | Ch20 §I.11, I.14 |
| Quan trạm | Ch20–Ch21 | "Đường ấy có thể bị đọc." — "Phải."; Ch21: nhận ống tre lệnh lương "Theo trạm" | CANON_FACT | Ch20 §I.16; Ch21 §I.13 |
| Quan huyện (phía tây) | Ch20 | đọc chiếu cho dân trước cửa huyện; "Treo ở cổng huyện. Hạ Hầu xử." ⟦ô kép → tách 1/2⟧ | CANON_FACT | Ch20 §I.17–18; Ch20 §II |
| Quan huyện (phía tây) | Ch20 | vì sao bị xử: không canon ⟦ô kép → tách 2/2⟧ | CANON_UNKNOWN | Ch20 §I.17–18; Ch20 §II |
| Người đưa thư (Hổ Lao) | Ch20–Ch21 | ba câu đo; hai bàn tay nứt vì dây cương; "Đại nhân không hỏi thư thật hay không?" — "Không."; ra cổng tây, không qua trạm | CANON_FACT | Ch20 §I.22; Ch21 §I.5, I.7, I.17 |
| Người hầu | Ch20–Ch21 | truyền lời; "đứng thêm một nhịp, như muốn khuyên" | CANON_FACT | Ch20 §I.19, I.22; Ch21 §I.8, I.18 |
| Thầy thuốc | Ch20–Ch21 | "nên nghỉ ba ngày" (Ch20); "nên nằm" (Ch21) — Vân Chương không đáp | CANON_FACT | Ch20 §I.19; Ch21 §I.21 |
| Quan cũ Hổ Lao (áo xám) | Ch22 | chép bản sổ kho; "Ai nhận thành?"; "Ai hợp lệ?"; "Ngài là người họ Tiêu?" | CANON_FACT | Ch22 §I.23, I.25–27 |
| Thư lại Hổ Lao (gầy, tay áo lấm mực) | Ch22 | giấu chiếu "từ ngày huyện bên bị treo", dán lên cổng đê | CANON_FACT | Ch22 §I.29 |
| Trinh sát (Hàn) | Ch22 | "Bến dưới thêm người."; "Hổ Lao dồn quân ra phía bến."; "Dự bị đứng ở bãi bến. Mặt ra sông."; "Họ đốt kho."; "Một cột đi bờ phía tây. Có kỵ che hai bên." | CANON_FACT | Ch22 §I.6–7, I.10, I.16 |

### 4.3 PLANNING_NON_CANON của nhân vật phụ (tách riêng; KHÔNG phải canon trang)

| Nhân vật | Ch | Nội dung (kế hoạch / author-truth) | Source Type | Source |
|---|---|---|---|---|
| Hoắc Thành Lĩnh | Ch02 | lý do thức ở thư phòng (tác giả biết: quân báo Hắc Hà do Tam Lang mang về, truyện chưa nói) ⟦ô kép tách thủ công 2/2⟧ | PLANNING_NON_CANON | Ch02 §II |
| Tạ Diên | Ch05 | Debt Matrix: "Cứu con bằng cách để cả thành chết" | PLANNING_NON_CANON | Ch05 §VII |
| Sứ giả của Khả đôn (ông già Bắc Nhung) | Ch10 | không biết nghĩa quân cờ (author-truth) ⟦ô kép tách thủ công 2/2⟧ | PLANNING_NON_CANON | Ch10 §I.25–26, I.38, §II |
| Hách Liên Chước | Ch19–Ch22 | → Ch25 ⟦ô kép tách thủ công 2/2⟧ | PLANNING_NON_CANON | Ch18 §II; Ch19 §II; Ch20 §II; Ch21 §II-A; Ch22 §IX |
| "G" — Tướng giữ Hổ Lao | Ch20 | ba điều kiện: không lên trang Ch20 (author-truth Gate Ch20: ân xá đúng chữ chiếu; giữ binh giữ chức, không giao binh người ngoài; tờ phong tước như chiếu) | PLANNING_NON_CANON | Ch20 §II; Ch20 §IX |
| "G" — Tướng giữ Hổ Lao | Ch21–Ch22 | author-truth: thư thật (G thật sự bất mãn, muốn hàng); G không phải nội gián; người đưa thư không biết thư bị chép; Bàng không điều khiển/ép/sai G | PLANNING_NON_CANON | Ch21 §II-B (D21-1); Ch22 §II-B |
| A Quy (lệnh bắt) | Ch15 | chỉ dấu chương: lệnh bắt A Quy OPEN "→ Ch17" | PLANNING_NON_CANON | Ch15 §V; Ch15 §IX |

## 5. MÂU THUẪN / LỆCH

Gộp từ staging 4 dải, đã dedupe (mục lệch danh xưng Dịch ở Ch11/Ch12/Ch15/Ch16 gộp thành CB-L-03). Mọi mục: **CHƯA QUYẾT — chờ chị**; file này không đề xuất đáp án thay chị, chỉ nêu cách đọc A / cách đọc B khi staging có nêu. ID dùng tiền tố `CB-L-xx` (Registry: `RG-L-xx`; Timeline: `TL-L-xx`); "(= …)" là mục cùng nội dung ở file khác, đối chiếu bằng nội dung.

| ID | Đề tài | Bên A (Source + trích) | Bên B (Source + trích) | ST bên A | ST bên B | Cách đọc A / B (nếu có) | Nhân vật liên quan | Trạng thái |
|---|---|---|---|---|---|---|---|---|
| CB-L-01 | Phùng thúc ↔ Phùng Bảo; "Dịch từng ở cung" (= RG-L-05; liên quan TL-L-20) | Ch04 §I.9: "Sau khi rời cung, Phùng Bảo sửa thói quen này" (thói quen viết khuyết nét "Huệ" của Dịch). | Ch04 §II: "Phùng thúc là Phùng Bảo trong nhận thức của Vân Chương" — ghi KHÔNG PHẢI Canon; Ch04 (đầu file): không mục nào mang nghĩa "Dịch là Thất hoàng tử". Ch08 §V: dòng "Bọc vải của Phùng thúc (Ch7)" payoff bằng khóa trường mệnh. | CANON_FACT | CANON_BELIEF | A: Phùng thúc và Phùng Bảo là một người, nối ngầm qua Ch08 §V + Ch08 §I.15–16. B: ở Ch04 chỉ là nhận thức của Vân Chương, chưa phải canon. File: khối 3.11 gắn thẻ bí danh chưa xác nhận, dòng giữ nhãn gốc, không nối chuỗi qua ranh giới. | Phùng Bảo, Dịch, Vân Chương | CHƯA QUYẾT — chờ chị |
| CB-L-02 | "Tiêu Dịch" ↔ "Thất hoàng tử" (= RG-L-17; TL-L-20) | Ch01 §IX [CANON CHANGE]: "Tiêu Dịch: 17 tuổi ở Ch1, 27 tuổi ở năm 0." | Ch04 §II: "Dịch là Thất hoàng tử… Canon Ch4 không xác nhận" (Vân Chương chỉ tin, Ch04 §III CANON_BELIEF). Ch08 §I.19: Dịch nói "Ta là con của Thẩm chiêu nghi." | CANON_FACT | CANON_UNKNOWN | A: tên "Tiêu Dịch" đã được Canon Update dùng từ Ch01 §IX. B: thân phận Thất hoàng tử chưa được xác nhận ở Ch04. | Dịch | CHƯA QUYẾT — chờ chị |
| CB-L-03 | Tên Dịch: Tiêu / Thẩm / Trình | Ch11 §0D: "Thẩm Dịch" ("chơi chậm, đếm"); Ch08–Ch13 dùng "Trình Dịch"; Ch11 §III: "Trình Dịch = Thẩm thư lại". | Ch12 §Nguyên tắc ghi: "POV Tiêu Dịch"; Ch16 §I.16: ký "Ích Châu, Trình Dịch" (Ch16 §Nguyên tắc ghi vẫn ghi POV "Tiêu Dịch"). | CANON_FACT | CANON_FACT | Canon Update không nêu quan hệ giữa ba nhãn; không có Canon Change. Không đề xuất. | Dịch | CHƯA QUYẾT — chờ chị |
| CB-L-04 | Nhà Dịch / dãy nhà sát tường bắc có cháy hay không (= RG-L-03; TL-L-21) | Ch07 §I (P-09, "Canon từ Approval"): "Dãy nhà sát tường bắc cháy sạch." | Ch07 §II: "Bàn cờ và căn nhà có thật sự cháy hay không… không phải Canon"; Ch07 §III/§IV ghi là lời đồn. | CANON_FACT | CANON_UNKNOWN | A: dòng P-09 là canon trang. B: chỉ là lời đồn (CANON_BELIEF). | Dịch, Phùng thúc | CHƯA QUYẾT — chờ chị |
| CB-L-05 | Chân của A Quy | Ch05 §V: "Đã hồi phục chân" (hậu doanh). | Ch06 §IV: "chân khinh công hạn chế"; Ch04 §VI: "bước còn hơi lệch"; Ch06 §I.16: "Chân khuỵu một nhịp". | CANON_FACT | CANON_FACT | — | Bùi Chỉ | CHƯA QUYẾT — chờ chị |
| CB-L-06 | Số người khiêng then Bắc Môn (= RG-L-02) | Ch01 §I.9: "gỗ sồi đen bọc sắt, hai người khiêng". | Ch06 §I.48: "Bốn lính khiêng then đặt lại vào khung". | CANON_FACT | CANON_FACT | Theo staging: có thể không xung đột; ghi nhận để tra. | Bắc Môn, Chiêu, Dịch | CHƯA QUYẾT — chờ chị |
| CB-L-07 | Mốc 26 bộ áo bông (= RG-L-04; TL-L-05) | Ch03 §I.52: "Đêm ngày 5 … Nhận 26 bộ áo". | Ch03 §I.2/§V: "Ngày 9: 26 bộ áo lên tường thành". | CANON_FACT | CANON_FACT | — | Chu Hạc, Dịch | CHƯA QUYẾT — chờ chị |
| CB-L-08 | Ôn "giữ" thư Tây Lương hay "không nhận thư bằng tay" (= RG-L-22; TL-L-08) | Ch08 §III (Ôn): "đang giữ phong thư Tây Lương chưa mở"; Ch08 §IV: "Ôn giữ, chưa mở". | Ch09 §I.1: "Ôn không nhận thư bằng tay"; Ch09 §II: "Thư gửi ai thì người ấy mở." | CANON_FACT | CANON_FACT | Ch09 §0 ghi "Khớp" với Ch8; lệch nhẹ ở chữ "giữ". | Ôn | CHƯA QUYẾT — chờ chị |
| CB-L-09 | Khoảng cách giữa Lạc Kinh thất thủ và Ch8 ngày 1 (= RG-L-20; TL-L-01) | Ch08 §VII: "Lạc Kinh thất thủ… trước ngày 1 khoảng 10–14 ngày" (năm 0, cuối xuân). | Ch10 §VII / Ch11 §VII: "Đầu tháng Ba" (thất thủ) và "Cuối tháng Ba" (Ch8 ngày 1). | CANON_FACT | CANON_FACT | Ch10 §VII ghi nguồn "Gate Ch8" cho dòng thất thủ. Mốc timeline. | Hạ Hầu, Dịch | CHƯA QUYẾT — chờ chị |
| CB-L-10 | Viên quản lương về ải ngày 4 (= TL-L-06; RG-L-09 nêu cùng điểm) | Ch09 §0: "Timeline Canon Ch8 (tin lọt ngày 3–5; viên quản lương về ải ngày 4)… Khớp". | Ch08 §VII: không có dòng viên quản lương về ải; chỉ "Ngày 3–5: Tin lọt…". | CANON_FACT | CANON_FACT | Ngày 4 có ở Ch09 §I.17 (sổ trọ). | Dịch, Hàn | CHƯA QUYẾT — chờ chị |
| CB-L-11 | Ch9 ngày 24 so với "giữa tháng Tư" (= RG-L-21; TL-L-02) | Ch11 §VII: "Cuối tháng Ba → giữa tháng Tư" cho Ch8 (ngày 1–14) → Ch9 (ngày 14–24). | Ch10 §VII: "Cuối tháng Ba" cho Ch8 ngày 1 và "Ch8 ngày 24" cho Ch9. | CANON_FACT | CANON_FACT | Ngày 1 cuối tháng Ba + 24 ngày không rơi vào "giữa tháng Tư". Mốc timeline. | Dịch | CHƯA QUYẾT — chờ chị |
| CB-L-12 | "Đầu xuân năm 1": trên trang hay suy ra (= TL-L-09) | Ch15 §I.1: "Băng trên Lạc Thủy đã vỡ… Đầu xuân năm 1." | Ch15 §VII: "Văn bản không nêu tháng; 'đầu xuân năm 1' là suy ra theo 'băng tan'." | CANON_FACT | CANON_INFERENCE | Canon Update tự đánh dấu suy ra (CANON_INFERENCE). | Dịch, Chiêu | CHƯA QUYẾT — chờ chị |
| CB-L-13 | Chiêu tới Hổ Lao "đúng ngày" và tới doanh Dịch ngày thứ tám (= TL-L-10) | Ch15 §I.26: "Hổ Lao. Ta tới đúng ngày." | Ch15 §VII: "Hổ Lao → doanh ~hai ngày cưỡi thường". | CANON_FACT | CANON_INFERENCE | Canon Update tự ghi: chỉ khớp nếu Chiêu cưỡi gấp; "không xung đột canon". | Chiêu | CHƯA QUYẾT — chờ chị |
| CB-L-14 | Gốc đếm ngày: "ngày 1 của hội" vs "sau Hổ Lao" (= TL-L-12) | Ch15 §VII: "Đầu xuân năm 1 (băng tan), ngày 1… Ngày thứ tám". | Ch16 §VII: "Sau Hổ Lao, ngày 9, sáng"; Ch17 §VII: "Sau Hổ Lao, ngày 30". | CANON_INFERENCE | CANON_INFERENCE | Cùng dãy số nối tiếp nhưng gốc đếm Ch16–17 gọi "sau Hổ Lao"; Canon Update không nêu gốc. | Dịch, Chiêu | CHƯA QUYẾT — chờ chị |
| CB-L-15 | Hạn ngày 31: nhãn chủ hạn (= RG-L-10; TL-L-14) | Ch16 §IV: "Hoắc quân… hạn: hết ba tuần kể từ hội ngày 10"; Ch16 §III: "nàng đặt hạn". | Ch17 §I.1: "hạn Ích Châu hết ngày ba mươi mốt, còn hai ngày"; Ch17 §I.11: "Hạn ngày 31 bỏ." | CANON_FACT | CANON_FACT | Cùng ngày 31; nhãn "Ích Châu" vs "Hoắc quân" khác nhau. | Chiêu, Dịch | CHƯA QUYẾT — chờ chị |
| CB-L-16 | "Còn hai ngày" ở hai ngày liên tiếp (= TL-L-13) | Ch16 §I.32: ngày 29 đêm, thân binh: "hạn còn hai ngày." | Ch17 §I.1: sáng ngày 30, "còn hai ngày". | CANON_FACT | CANON_FACT | Cách đếm khác nhau cho cùng mốc ngày 31 (INFERRED). | Chiêu | CHƯA QUYẾT — chờ chị |
| CB-L-17 | Lương Hoắc quân "sáu ngày" → "bốn ngày" | Ch15 §IV: "lương còn sáu ngày (trước khi giao hai xe)". | Ch16 §I.7: "lương còn bốn ngày" (ngày 10); Ch16 §0 ghi tự sửa v1. | CANON_FACT | CANON_FACT | Staging xếp là Revision của Ch16, không phải Canon Change; không tự quyết. | Chiêu | CHƯA QUYẾT — chờ chị |
| CB-L-18 | Hạ Hầu và "mua ngựa" (= RG-L-12) | Ch18 §V: seed "Hạ Hầu mua lương dân → mua ngựa (cùng mạch bạc)" đóng một phần. | Ch18 §0, §II: "Trên trang không nêu 'Hạ Hầu'/'Tây Lương'"; Uyển không nói "Hạ Hầu". | CANON_FACT | CANON_FACT | Canon Update nối seed; trang không nêu tên phe. | Hạ Hầu, Uyển | CHƯA QUYẾT — chờ chị |
| CB-L-19 | Ngày tuyệt đối của Ch14 (= TL-L-16) | Ch14 §VII: "Ngày 4 (từ cuối tháng Chín), sáng… ngày-tháng tuyệt đối là suy ra: ~ngày 1–2 tháng Mười". | Ch14 §I.II: "đầu tháng Mười"; Ch14 §I.11: "đêm mười một, còn chín đêm". | CANON_INFERENCE | CANON_FACT | Canon Update tự ghi suy ra (CANON_INFERENCE). | Chỉ | CHƯA QUYẾT — chờ chị |
| CB-L-20 | Ch21: "thư riêng đã tới tay người giữ chức" là FACT hay INFERENCE | Ch21 §I.4: narration nêu như dữ kiện; Ch21 §III (Vân Chương), phần "FACT" của cùng ô cũng liệt "thư riêng đã tới tay người giữ chức (chữ trong thư)"; Ch21 §0: "xác nhận OPEN Ch20 'tới tay ai', chỉ ở mức Hổ Lao". | Ch21 §III (Vân Chương): cùng ô ghi riêng "INFERENCE (một mức): 'Thư riêng đã tới tay người giữ chức'". | CANON_FACT | CANON_SUSPICION | Cùng một ô Knowledge Matrix liệt claim ở cả FACT lẫn INFERENCE (một mức). Theo ánh xạ R2, phía INFERENCE về một nhân vật = CANON_SUSPICION (Vân Chương). Các dòng dùng claim này (3.5, Ch21 KNOWLEDGE) gắn CANON_SUSPICION kèm ⚠, không gắn FACT. Registry OP-115 dùng cùng claim. | Vân Chương | CHƯA QUYẾT — chờ chị |
| CB-L-21 | Ch19 §III: cột "Biết" của Dịch chứa cách đọc/diễn giải | Ch19 §III (Dịch), cột "Biết": "thành mở cho lời hứa, không cho tước vị". | Nguyên tắc Belief ≠ Fact: đây là cách đọc của Dịch. | CANON_FACT | CANON_BELIEF | Staging gắn CANON_BELIEF (Dịch) cho các dòng loại này; ghi lại để chị cân nhắc. | Dịch | CHƯA QUYẾT — chờ chị |
| CB-L-22 | Tướng giữ thành Hổ Lao đêm qua có phải "G" không | Ch22 §I.26: "Một tướng của Hạ Hầu. Không thấy từ đêm qua." (trả lời "Ai giữ thành đêm qua?"). | Ch21 §II-A / Ch22 §IX: "Số phận G và tướng giữ Hổ Lao (vô danh)" (G ký thư "Tướng giữ Hổ Lao.", Ch21 §I.2). | CANON_FACT | CANON_UNKNOWN | Canon Update không nói hai nhân vật có là một; không gộp. | G, Hạ Hầu | CHƯA QUYẾT — chờ chị |
| CB-L-23 | Ngày gói vỏ quýt tới Kim Lăng | Ch20 §VII: "gói vỏ quýt tới" ở "~Ngày 50". | Ch20 §I.19: "gói tới chiều nay" (cảnh đêm, ~Ngày 51, đêm). | CANON_INFERENCE | CANON_INFERENCE | Chênh một ngày; cả hai là suy ra (CANON_INFERENCE). | Uyển, Vân Chương | CHƯA QUYẾT — chờ chị |
| CB-L-24 | Ch21–22: lệch so với kế hoạch đã duyệt (Canon Update tự ghi) (= TL-L-17; TL-L-19) | Kế hoạch (chỉ biết qua Canon Update): Gate §1 Ch21 "chín–mười ngày" (Ch21 §VII, ghi chú); Scene Bible Ch22 Production Check: bộ Hàn đi đê ~58 (Ch22 §0). | Ch21 §VII (ghi chú): theo khoảng cách của Gate §1 ra "~13 ngày" (SY-13: chỉ sửa Production Check, không sửa chữ trên trang); Ch22 §0, §VII: chỉnh thành ~59 (cùng đêm thuyền tới). "Mọi số ngày là suy ra." | PLANNING_NON_CANON | CANON_INFERENCE | Canon Update ghi không phải Canon Change; bên A là kế hoạch. | Vân Chương, Hàn | CHƯA QUYẾT — chờ chị |
| CB-L-25 | Uyển ↔ Khả đôn | Ch17 §III: liệt kê riêng "Vân Chương, Uyển, Chỉ, A Quy, … Khả đôn". | Ch18 §I.2, §I.14, §I.17: người khác gọi Uyển là "Khả đôn"; Ch12 §III: "Vĩnh Ninh công chúa; Khả đôn" cùng ô; Ch10 §III: gộp "Uyển / Khả đôn". | CANON_FACT | CANON_FACT | A: hai nhãn tách trong ma trận Ch17. B: cùng một người theo Ch12 §III / Ch18 lời thoại. File giữ khối "Khả đôn" tách ở 3.3(e). | Uyển | CHƯA QUYẾT — chờ chị |
| CB-L-26 | Ôn ↔ Thứ sử (= RG-L-11) | Ch16 §I.16: "Ấn Thứ sử tới sau. Ba tuần."; Ch16 §I.22: "Việc kia Thứ sử đã xem". | Ch16 §I.31: "Thư Ôn… ấn đóng ở đầu"; Ch08 §I.6: "Ôn Thứ sử đọc to". | CANON_FACT | CANON_FACT | Ch08 gọi "Ôn Thứ sử"; Ch14–18 dùng "Ôn" và "Thứ sử" riêng, không ghi rõ Ôn = Thứ sử. File dùng một khối ÔN / THỨ SỬ gắn thẻ bí danh chưa xác nhận; dòng giữ nhãn gốc. | Ôn | CHƯA QUYẾT — chờ chị |
| CB-L-27 | Hoắc Tam Lang ↔ Chiêu ↔ "Hoắc quân" | Ch12 §III: "Tam Lang là Hoắc Chiêu (chính nàng nói, trong gian trong)"; Ch12 §I.29: "Người hứa là Hoắc Chiêu."; Ch06 §I.21: narration gọi "nàng" — Canon đã xác nhận Tam Lang = Chiêu (giữ gộp khối 3.4). | Ch14 §III / §I.2: chỉ "Hoắc quân" / thân binh "Tam tướng quân", không gắn tên Chiêu; Ch20 §I.2: "kỵ nhẹ của Hoắc Tam Lang không vào". | CANON_FACT | CANON_FACT | Phần còn treo: nhãn lực lượng "Hoắc quân" và thân binh "Tam tướng quân" ở Ch14 có gắn với Chiêu hay không. Tam Lang = Chiêu không còn là điểm treo (Ch12 §III). | Chiêu | CHƯA QUYẾT — chờ chị |
| CB-L-28 | Hàn "Đô úy" ↔ "Đô úy" thành Dĩnh Xuyên | Ch19 §I.22: sĩ quan Ích Châu: "Đô úy. Sổ đêm qua không thêm tên." (Ch19 §I.10: Dịch nói "Bộ của Đô úy…"). | Ch19 §I.19: Đô úy thành Dĩnh Xuyên, hiện một lần; sau cổng "Đô úy?" — tay buông; số phận OPEN. | CANON_FACT | CANON_FACT | Staging: không dòng nào gán chức "Đô úy" cho Hàn tường minh trong Ch19–22; Ch08 §I.17 gọi "Hàn Đô úy". Hai người khác nhau, không gộp. | Hàn | CHƯA QUYẾT — chờ chị |
| CB-L-29 | Sĩ quan Ích Châu: một hay nhiều người | Ch19 §I.6, §I.13–14, §I.22: ít nhất ba lần nhắc (nghe thư Bàng; "đã đòi trả đũa hôm qua"; hook cuối chương). | Ch22 §0 (Sync Ch19) / Ch22 §I.14: "người từng đứng sau lưng Dịch trước cổng Dĩnh Xuyên". | CANON_FACT | CANON_FACT | Canon Update không khẳng định đồng nhất; file gom một khối tra cứu. | Dịch, Hàn | CHƯA QUYẾT — chờ chị |
| CB-L-30 | Chỉ ↔ "người đi bến" (Ch21) | Ch21 §III: hàng "Người đi bến (Chỉ)" (Vân Chương chọn một lời — "[P] suy", off-page). | Ch21 §I.10: người đi bến: "Đương gia dặn thêm…"; Ch14 §I.18: người đi bến là thuộc hạ Chỉ. | CANON_FACT | CANON_FACT | Dòng này được tách ở 3.2(d); không gộp vào lịch sử trực tiếp của Chỉ. | Chỉ, Vân Chương | CHƯA QUYẾT — chờ chị |
| CB-L-31 | Kha Trọng ↔ "lão Kha" ↔ "phủ lớn họ Tạ" (Tạ gia) | Ch14 §I.8, §I.23: "Kha Trọng, người Lạc Kinh, buôn giấy" (sổ Nam Môn); "Người bảo lãnh: Kha Trọng" (sổ thuê ngựa). | Ch14 §I.26: (lời đồn) "lão Kha… quản sự trong phủ lớn họ Tạ"; Ch14 §II (G-2): cùng một người / còn sống / liên quan Bắc Môn, Chu Hạc, Tạ gia — chưa kết luận. | CANON_FACT | CANON_SUSPICION | Canon Update ghi OPEN (CANON_UNKNOWN); không nối "họ Tạ" với Vân Chương. | Kha Trọng, Chỉ, Vân Chương | CHƯA QUYẾT — chờ chị |
| CB-L-32 | Hạ Hầu (cờ/kỵ/sứ) ↔ Hạ Hầu Liệt ↔ Bàng | Ch08 §I.6: "Quân Tây Lương của Hạ Hầu Liệt đã vào Lạc Kinh"; Ch08 §IV: sứ Hạ Hầu ở ải Tây ≠ tướng Tây Lương gửi thư ở biên, "không nhập làm một". | Ch09 §II: liên hệ sứ Hạ Hầu – Bàng: OPEN; Ch09 §I.3: thư Bàng — Hạ Hầu "phò chính Lạc Kinh"; Ch15 §I.30: sứ Hạ Hầu: "Bàng tướng quân nhờ hỏi". | CANON_FACT | CANON_UNKNOWN | Canon Update không nối tường minh các nhãn; khối HẠ HẦU và khối BÀNG giữ riêng. | Hạ Hầu, Bàng | CHƯA QUYẾT — chờ chị |
| CB-L-33 | Tiết tướng quân ↔ "tướng giữ ải Tây" | Ch08 §I.9: Hàn chuyển thư tướng giữ ải Tây (sứ Hạ Hầu đòi Ích Châu dâng biểu). | Ch09 §IV: "Tiết tướng quân (ải Tây)"; Ch09 §I.20: "Tiết tướng quân cùng Hàn đi lính từ năm mười sáu tuổi". | CANON_FACT | CANON_FACT | Canon Update không ghi tường minh người ở Ch08 §I.9 là Tiết; không gộp. | Hàn | CHƯA QUYẾT — chờ chị |
| CB-L-34 | Phó tướng Hoắc quân (Ch15–16, vô danh) ↔ Chu Hạc | Ch01 §I.10: Chu Hạc là phó tướng Hoắc gia quân. | Ch16 §I.7: phó tướng Hoắc quân: "Cho ta một trận."; Ch15 §I.31: "Ai biết cột ấy đi hướng nào?" — không gắn tên. | CANON_FACT | CANON_FACT | Canon Update không nêu tên; không gộp. | Chu Hạc, Chiêu | CHƯA QUYẾT — chờ chị |

## 6. GHI CHÚ ĐỘ TIN CẬY

1. **Cách dựng (a).** Bảng "TRẠNG THÁI CUỐI CH22" là chọn lọc cơ học từ dòng staging gần nhất theo trường (xem 0.1), không phải tổng hợp mới. Với nhân vật vắng ở chương muộn (Chu Hạc, Phùng Bảo, Tô, Bàng, Ôn…), "trạng thái cuối" thực chất là trạng thái ở chương ghi trong cột Ch.
2. **Nối chuỗi.** Cột "Nối chuỗi" trỏ tới dòng trước cùng đề tài (cùng bên với RELATION). Sửa vòng 1: 29 con trỏ trước đây chỉ khớp tên trường nhưng khác đề tài được đổi thành `(Before chưa trích được)` hoặc trỏ lại đúng dòng; thêm con trỏ khi bỏ qua hàng (Dịch Ch07 RELATION(Phùng thúc)) và khi trạng thái Ch20 đóng ở Ch22 (Dịch "chưa biết chiếu" → Ch22 §I.30–31); không nối qua ranh giới bí danh chưa xác nhận (Phùng thúc → Phùng Bảo; Uyển → "Khả đôn"). File không kiểm khớp chữ After(trước) = Before(sau) ngoài các điểm này. Những chỗ Before/After vênh mà staging đã nêu ở mục 5 (CB-L-05, CB-L-08, CB-L-17), không tự sửa.
3. **Ô Source Type kép.** Các dòng staging gắn 2+ loại trong một ô đã tách mỗi loại một dòng (đánh dấu `⟦ô kép → tách k/n⟧`); sửa vòng 1 cắt nội dung mỗi dòng chỉ còn phần đúng với loại của dòng đó (R4). Năm dòng có lẫn PLANNING_NON_CANON được tách văn bản thủ công theo ranh giới câu trong chính dòng staging: Ch02 §II (Hoắc Thành Lĩnh), Ch11 §II/§III (Bùi Chỉ, K1), Ch11 §II/§III (Chu Hạc, D1), Ch10 §I/§II (sứ giả Khả đôn), Ch19–22 §II/§IX (Hách Liên Chước, "→ Ch25"). Dòng có ghi chú ngoài 6 giá trị nhưng chỉ một token (vd "CANON_FACT (lời nói trên trang)") được giữ nguyên một dòng kèm `⟦ST gốc⟧`; riêng dòng có chữ "OPEN" trong qualifier đã tách thêm một dòng CANON_UNKNOWN (Ch08 §III Dịch nghe tung tích Thất hoàng tử; Ch08 §I.11/I.21 Tô; Ch08 §I.6, I.9, §IV Hạ Hầu).
4. **Kém chắc về Source Type.** (i) Dòng "Biết" của Knowledge Matrix gắn CANON_FACT, kể cả cột "Sự thật" của Debt Matrix Ch02 §VII (Hoắc Thành Lĩnh) — có thể thực chất là author-truth. (ii) Ch09 §III/§IV (Ôn, "động cơ là author-truth") giữ CANON_FACT cho phần hành vi. (iii) Ch19 §III: các dòng "Biết" của Dịch mang tính diễn giải gắn CANON_BELIEF kèm ⚠ CB-L-21. (iv) Ánh xạ thống nhất từ sửa vòng 1: lời đồn / "NGHE / THUẬT LẠI" / tin chưa xác nhận → CANON_SUSPICION có tiền tố "(lời đồn)" / "(nghe thuật lại)" (Ch06 tin Uyển tự đi; Ch07, Ch08, Ch14 lời đồn; Ch18 tin Hách Liên); cột "INFERENCE" / "suy luận" của Knowledge Matrix về một nhân vật → CANON_SUSPICION có ghi ai suy (Ch05, Ch12, Ch21, Ch22); CANON_INFERENCE chỉ còn ở bảng mâu thuẫn cho suy ra cấp Canon Update (số ngày). (v) Cột "INFERENCE / NIỀM TIN" (Ch11) và "TIN / SUY DIỄN" (Ch06) giữ CANON_BELIEF.
5. **Đồng nhất nhân vật.** Bảng 2.1 và 2.2 chỉ là ghi chú tra cứu. Khối gộp nhãn chưa xác nhận mang thẻ `[BÍ DANH CHƯA XÁC NHẬN — xem CB-L-xx]`: Phùng thúc / Phùng Bảo (CB-L-01), Ôn / Thứ sử (CB-L-26), Uyển / "Khả đôn" (CB-L-25; khối (e) tách), Hạ Hầu / Hạ Hầu Liệt (CB-L-32), Tiêu / Thẩm / Trình (CB-L-03); mỗi dòng mang nhãn gốc, chuỗi không nối qua ranh giới. Hoắc Tam Lang = Hoắc Chiêu được Canon xác nhận (Ch12 §III; Ch12 §I.29) nên giữ gộp; chỉ nhãn "Hoắc quân" / "Tam tướng quân" ở Ch14 còn treo (CB-L-27). Dòng staging gán nhãn "Chỉ" cho "người đi bến" (Ch21) được tách ở 3.2(d).
6. **Nhân vật phụ có khối riêng.** Ở mục 4.1 mỗi người chỉ giữ 2–4 dòng (lần đầu / trạng thái cuối mà Canon Update nêu); chi tiết đầy đủ nằm ở staging, không nằm trong repo. Các dòng PLANNING của nhân vật phụ ở 4.3.
7. **Nhân vật chính của dải 14–22 và nhãn tên.** Staging dải Ch14–22 đặt tiêu đề khối Dịch là "Tiêu Dịch" theo nhãn POV ở Canon Update; Ch19 §Nguyên tắc ghi không ghi tên, tên "Tiêu Dịch" chỉ dựa trên Ch12/15/16/22 (xem 2.1).
8. **Tuổi / mốc năm (Ch01 §IX).** "Tiêu Dịch 17 → 27", "Bùi Chỉ 8/18/28" được ghi như [CANON CHANGE] nhưng Canon Update không nêu giá trị tuổi cũ; mốc cũ "15 năm trước"/"14 năm trước" của Hoắc Thành Lĩnh cũng không nói mốc nào ứng việc nào.
9. **Chuẩn hóa Source.** Các Source dạng `ChNN (đầu file)`, `ChNN (Nguyên tắc ghi)`, `ChNN (toàn bộ)` của staging được viết thành `ChNN §đầu file` / `§Nguyên tắc ghi` / `§toàn bộ`. Hai ô Source có chú thích trong ngoặc đã bỏ chú thích khỏi cột Source: Hoắc Chiêu Ch06 (staging ghi thêm "niềm tin của Chiêu" sau `§II`) và Bùi Chỉ Ch15–Ch18 APPEARANCE (chú thích Canon Update Ch18 chuyển vào ô nội dung).
10. **Staging đã tự sửa một lỗi gán.** Câu "Ta không mở cửa Bắc… Hắn chết ngay dưới vòm." (Ch11 §I.20) là lời A Quy (kết luận mười năm của Chỉ), không phải lời Dịch; dòng trong khối Dịch ghi là điều Dịch nghe từ Chỉ.
11. **Số liệu ước lượng.** Chữ "khoảng/chừng/ước chừng" giữ nguyên; các mốc ngày INFERRED nằm ở file timeline, không ở file này.
12. **QA.** Đã qua Consistency Check và QA 30 claim (vòng 1; mẫu CB 10 dòng, 8 MATCH) và sửa vòng 1 (xem mục NHẬT KÝ SỬA VÒNG 1). Các dòng ngoài mẫu chưa được đối chiếu từng dòng với Canon Update gốc; ánh xạ R2 đã áp cho toàn file theo nhãn cột Canon Update.

## NHẬT KÝ SỬA VÒNG 1

Số dòng ghi theo bản trước khi sửa (1580 dòng). Luật theo FIX_RULES vòng 1.

- **R1 (ID).** Mọi `L-xx` → `CB-L-xx` (bảng mục 5, mục 2, các dòng ⚠). Mục 5 thêm đối chiếu chéo theo nội dung: CB-L-01 (= RG-L-05), 02 (= RG-L-17, TL-L-20), 04 (= RG-L-03, TL-L-21), 06 (= RG-L-02), 07 (= RG-L-04, TL-L-05), 08 (= RG-L-22, TL-L-08), 09 (= RG-L-20, TL-L-01), 10 (= TL-L-06), 11 (= RG-L-21, TL-L-02), 12 (= TL-L-09), 13 (= TL-L-10), 14 (= TL-L-12), 15 (= RG-L-10, TL-L-14), 16 (= TL-L-13), 18 (= RG-L-12), 19 (= TL-L-16), 24 (= TL-L-17, TL-L-19), 26 (= RG-L-11). Giả định hai file kia giữ nguyên số sau khi đổi tiền tố.
- **R2 (Source Type, 37 dòng).** Lời đồn / nghe thuật lại → CANON_SUSPICION có tiền tố: 215, 224, 229, 426/521 (tách), 468, 584, 609 (tách), 610, 652, 1281, 1300, 1328, 1340, 1359, 1381 (tách). Cột INFERENCE / suy luận về nhân vật → CANON_SUSPICION ghi ai suy: 168, 169, 278, 282, 383, 890, 891, 892, 926, 942, 974, 987. OPEN theo POV Dịch ghi phạm vi và nơi Canon đã có (Ch21 §I.12): 172, 385. Chú giải mục 0: 16–19.
- **R3.** Không còn ô Source Type có chú thích; bảng mục 5 thêm hai cột ST bên A / ST bên B (mỗi bên một loại).
- **R4 (98 dòng).** Cắt nội dung các dòng tách từ ô kép: 168, 224–225, 281–287, 296–297, 429, 431, 433, 468, 479–485, 495–496, 545–546, 586–587, 602–608, 609, 630–631, 800–801, 1010, 1019–1026, 1133–1134, 1227, 1230, 1241–1242, 1256–1257, 1325–1329, 1339–1343, 1381, 1389–1390, 1412–1505 (16 cặp mục 4.2).
- **R5.** 432, 523: dòng "Nghi rò tin … Kha Trọng" chép sát Ch14 §VI, đổi trường thành RELATION(chính hắn), ghi Canon chưa nối G-1 với G-2 (Ch14 §II; Ch15 §0).
- **R6 (bí danh).** Thẻ `[BÍ DANH CHƯA XÁC NHẬN]` cho khối Dịch (106), Khả đôn (665), Hạ Hầu (997), Ôn (1210), Phùng (1268); nhãn gốc từng dòng khối Ôn (1216–1259) và Phùng (1274–1308); bỏ gộp ngầm ở 2.1 (74, 75, 80) và 2.2 (85, 90–94); không nối chuỗi qua ranh giới: 615, 616, 1299, 1300, 1304; Chiêu giữ gộp, ghi nguồn xác nhận Ch12 §III (37, 70, 91, 676, CB-L-27); tên "Tiết tướng quân (tướng giữ ải Tây)" → "(ải Tây, Ch09 §IV)" (1436–1437).
- **R7 (⚠, 20 dòng).** CB-L-01: 202, 1296. CB-L-04: 215, 1298. CB-L-05: 463, 464 (trước trỏ nhầm "#4"), 466. CB-L-07: 1077 (trước trỏ nhầm "#6"). CB-L-08: 1236, 1243. CB-L-17: 805. CB-L-18: 1003. CB-L-20: 892, 987 (không gắn FACT; mục CB-L-20 bổ sung §III cột FACT và §0 "chỉ ở mức Hổ Lao"). CB-L-21: 167, 358, 360, 1184, 1200. CB-L-22: 1390. CB-L-25: 555, 615, 616.
- **R8 (planning, 27 dòng).** Bỏ chỉ dấu chương khỏi bảng canon và chuyển vào (c) / 4.3: 473 (ràng buộc Ch12+), 589, 646, 672, 704, 783 ("tới Ch29"), 877, 981 ("→ Ch23"), 893, 961, 1012, 1037, 1185, 1186, 1197, 1198, 1382, 1469; dòng (c) mới sau 395, 538, 663, 845, 995, 1044, 1208, 1522; 1520 thêm nguồn Ch18 §II. CB-L-24: bên kế hoạch gắn PLANNING_NON_CANON.
- **R9.** 412, 472: bỏ trỏ "Gate Ch11 §1C", trỏ Ch11 §0C. 276: "(Gate Ch8)" → Ch12 §V. CB-L-24: nguồn "Ch21 §0 (SY-13)" sửa thành "Ch21 §VII (ghi chú)". Source bỏ chú thích "…" / "(cột INFERENCE)": 118, 128, 129, 278, 340, 563, 863, 866.
- **R10 (chuỗi, 42 dòng).** B-3: xóa dòng Ch20 "chưa biết chiếu nêu tên mình" khỏi (a) Dịch (171); 363, 364 ghi điểm đóng Ch22 §I.30–31; 370, 384 nối về Ch20. Thêm nợ Ch22 §VI còn thiếu: (a) Dịch 151, sau 158; (b) Dịch sau 381; Ôn 1221, sau 1259. Con trỏ khác đề tài → `(Before chưa trích được)`: 223, 234, 246, 304, 305, 307, 343, 344, 472, 473, 476, 526, 627, 644, 771, 804, 807, 831, 1030, 1085, 1141, 1155, 1200, 1253; trỏ lại đúng dòng: 224, 345, 357, 653, 965; S-6: 219 (bỏ hàng Ch03–Ch06), 499 (ô after vỡ), 1200 (ô after vỡ); 155, 378 bỏ mũi tên gây vỡ chuỗi.
- **R11.** Dòng Trạng thái (5); số liệu mục lục tính lại (canon = APPEARANCE ở (a) + dòng (b); PLANNING = dòng (c)); ghi chú 2, 3, 4, 5, 12 của mục 6.
- **Không sửa được trong file này:** REG:430 (OP-115) gắn FACT cho claim CB-L-20, REG:439 (OP-121b), REG:513 (D-54b), REG:134, REG:442 (B-4) và các lỗi TL — thuộc file khác. Đối chiếu chéo RG-L / TL-L giả định hai file kia chỉ đổi tiền tố, không đánh số lại.


<!-- END -->
