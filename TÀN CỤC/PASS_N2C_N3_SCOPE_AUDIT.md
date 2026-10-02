# PASS N2C / N3 — SCOPE AUDIT (REVIEW ONLY)

Không sửa EP1–EP9. Không chạy N2C, không chạy N3. Không mở lại AD-01–04, AD-N2-01–11, khóa EP7, cấu trúc phòng ngừa EP8–EP9, vụ Thẩm không xảy ra ở dòng hiện tại, payoff Lạc Thủy, không Final Boss / không một chủ mưu Tây Uyển.
Trạng thái nguồn: HEAD `bd15676` (N2B `4d1749c`, N2B review `bd15676`).

**Cơ sở bằng chứng (nói rõ giới hạn).** Đã đọc: `PASS_N2A_AUDIT.md`, `PASS_N2A_AUTHOR_DECISION_PREP.md`, `N2B_DECISION_EXECUTION_REPORT.md`, `PASS_N2B_REPORT.md`, `PASS_N2B_REVIEW_REPORT.md`, bảng AD-N2 và mục continuity (§7) của bản prep. Đọc lại toàn bộ `ep8.txt` ở lượt N2B, và lượt này kiểm tra trực tiếp trong bản thảo hiện tại: `ep5` (mốc ngày), `ep9` (đình chức, 17/10, mở tập, kết tập, cảnh Thẩm phu nhân), `EP1:37/573`, `EP4:1607`, số lần xuất hiện của "Bùi Tấn"/"Nhị hoàng tử" theo tập. **Không** đọc lại toàn văn EP1–EP7 và EP9 trong lượt này; các nhận định về ranh giới tri thức ở những tập đó dựa trên N1B review, N2A audit và diff N2B (chỉ chạm ep5/ep6/ep8/ep9, mỗi tập ở ep5/ep6/ep9 chỉ một dòng).

---

## 1. Executive verdict

**N2C NOT NECESSARY.**

N2B is approved. No structural N2C pass is required. Proceed to N3 final QA with the limited scope listed above.

- Không có mục **MUST FIX BEFORE N3**.
- Còn lại: 3 điểm continuity ngày tháng/thứ tự (mức MINOR, đã có từ nguồn, không do N2B gây ra), một nhóm rủi ro audio chỉ kiểm được bằng nghe-đọc thành tiếng, và việc đồng bộ tài liệu cũ. Tất cả vừa với N3 giới hạn.
- Một số micro-fix tùy chọn (mục 2, mã `OPT`) có thể gói vào N3 nếu tác giả muốn; không cái nào cần một pass riêng.

---

## 2. Remaining issues table

Phân loại hành động: **MUST FIX BEFORE N3** · **OPTIONAL MICRO-FIX** · **SAFE TO LEAVE** · **N3 ONLY**.

| ID | Issue | Severity | Category | Action |
|---|---|---|---|---|
| R-01 | `EP1.txt:37` ("Ba ngày trước cha chết trong ngục. Hai ngày trước anh trai bị chém") ↔ `EP1.txt:573` ("Kiếp trước Tử Khiêm chết đầu tiên"). Một người nghe có thể thấy hai câu không khớp thứ tự cái chết. ("đầu tiên" cũng có thể đọc là "người đầu tiên bị chém", nên chưa chắc là mâu thuẫn cứng.) Tài liệu cũ lại ghi "ba ngày sau anh bị chém" (`MASTER_TIMELINE.md:74`) | MINOR | Logic / chronology | **OPTIONAL MICRO-FIX**. Cần tác giả xác nhận một câu: thứ tự cái chết nào là canon. Không tự sửa. N1A D-01, N2A 2.3 |
| R-02 | `ep5.txt:365/751/857` ("Còn hơn mười ngày / Còn mười ngày / mười ngày nữa ông ấy chết") ↔ `:941` (23/7 là ngày chết, kiếp trước 3/8) và `:1047` ("Sai lệch, mười một ngày"). Số học ngày không khớp tuyệt đối với từng cảnh trước | MINOR | Chronology | **N3 ONLY**: kiểm số học theo ngày tháng từng cảnh; chỉ nêu, không sửa nếu tác giả không xác nhận. Nguồn đã có, N1B review: PRESERVED |
| R-03 | `ep9.txt:749` ("Cuối tháng Tám… Tạm đình chức sáu tháng") ↔ `:877` sổ "Hai mươi tháng Chín, cha bị đình chức. Điều này lại xảy ra, nhưng vì lý do khác" | MINOR (thấp) | Chronology | **SAFE TO LEAVE**. Đọc được như "nhận quyết định cuối tháng Tám, hiệu lực 20/9". Nếu N3 nghe thấy vướng thì ghi lại, không sửa |
| R-04 | Kênh thông tin: Chiêu Ninh tới nhà an toàn của Trần Quảng (`ep6` sc.34); "nhẫn" kể cho Tĩnh An (`ep7` sc.29); kẻ bắt Lục Trầm biết có phong thư ở Thẩm gia (`ep5` sc.34/40) — C-04, C-05, C-07 | MINOR | Knowledge boundary | **SAFE TO LEAVE**. N1B review xếp PRESERVED; N2B không chạm các cảnh này. Lượt này không tìm thấy bằng chứng mới cho vi phạm. N3 chỉ cần nghe lại một lần |
| R-05 | Quá tải mã/tên "bốn/tứ/4" và mã (K7, D2, N4, N-4, BT-3, PM-6, HX-4, H4, Nam 4, Nam tứ, Ninh Tứ, Kho Bốn, Hạng bốn, Tôn Tứ, Tứ gia); nhiều tên mới ở EP8 (AU-01, AU-02) | MINOR (rủi ro nghe) | Audio | **N3 ONLY**: nghe thành tiếng kiểm các cụm đã nêu. Không đổi tên, không thêm giải thích. Văn bản đã tự phân biệt HX-4/H4 ("Không phải HX-4. Chỉ H4.") và "chữ giống không có nghĩa cùng thứ" |
| R-06 | Chuỗi hỏi–đáp ngắn dài 16–19 lượt trong EP8 (Bùi Tấn liệt kê tên, Tề Phương, Hoài Xuyên–Chiêu Ninh về Cố, Phùng Mậu về nhẫn) (AU-03) | MINOR | Audio | **OPTIONAL MICRO-FIX** / **N3 ONLY**: chỉ gắn thẻ người nói ở điểm nghe thấy rối. Phần lớn hỏi–đáp luân phiên hai người nên theo dõi được |
| R-07 | Mốc nhảy ngày không neo ("Hai ngày sau", "Hôm sau") ở EP8–EP9 (AU-06, N-01) | MINOR (thấp) | Audio / chronology | **SAFE TO LEAVE**. Các điểm kiểm trong EP8 đều có nơi và người hành động ngay trong câu mở cảnh (ví dụ cảnh Hứa Nghiêm, cảnh Hoài Xuyên đi Nam lộ có "Nàng ở lại kinh") |
| R-08 | Mật độ công thức "không nói gì", "Ừ.", câu cụt (AU-08, 09, 10) | LOW | Audio / style | **SAFE TO LEAVE**. Là giọng của tập, không phải lỗi. N2B đã giảm các thẻ vô chức năng trong EP8 |
| R-09 | Tài liệu cũ chưa đồng bộ: `MASTER_TIMELINE.md` (bản sớ, đơn nặc danh — dòng ~67/147; "ba ngày sau anh bị chém" dòng 74), `KNOWLEDGE_MAP.md`, `AUTHOR_DECISIONS.md` (Từ Kính "siết tay" ~335; liệt kê AD-01..04 như câu hỏi mở; số dòng `ep8` cũ), `PASS_N1B_REPORT.md` H-12 (không có căn cứ), con dấu mẻ, ba dấu hiệu HX-4, v.v. (C-09, C-10) | MINOR | Documentation | **N3 ONLY** (đồng bộ tài liệu, không đụng bản thảo) |
| R-10 | Các mạch mở nằm ngoài danh sách AD và N2B: Thẩm phu nhân "Năm đó ông giấu ta. Giờ lại giấu con." (`EP4.txt:1607`; hôn sự ở EP9 chỉ chạm nhẹ), hook EP1 ("Phía trên đã có lệnh", "Bắc môn có động!"), chủ kho số ba/Vạn Hưng, bốn hiệu bạc (chỉ ba tên), dấu Ty Thông hành "nét khuyết", vết thương trán Lục Trầm (N2A E3–E7, E10) | LOW | Mystery | **SAFE TO LEAVE**. Việc chốt hay để mở là quyết định tác giả; không phải việc của N2C |
| R-11 | Điểm N2A mức MEDIUM/LOW chưa đụng: tóm tắt lặp EP9 (S-06), EP6 kể lại ba lần (S-07), EP7 trùng ý (S-08), EP9 hậu quả dài (S-09), vòng cảnh cha–con (S-10), gag cầu nối (S-14), v.v. | LOW | Pacing | **SAFE TO LEAVE**. "Có thể mượt hơn" không phải lỗi cấu trúc. Mỗi cảnh còn mang chi tiết thật hoặc nhịp thở theo Bible §7 |

Không có mục nào gắn MUST FIX BEFORE N3.

Mục đã khóa, không đưa vào bảng: AD-N2-04 (Mã Tam, giữ), AD-N2-06 (em gái Hàn Dực, giữ), AD-N2-10 (Bùi Tấn và Nhị hoàng tử xuất hiện muộn, giữ như hiện tại; kiểm tra: hai tên xuất hiện từ EP8, EP1–EP7 không có).

---

## 3. Assessment of the 8 N2B MINORs

| N2B MINOR | Nội dung | Phân loại mới | Lý do |
|---|---|---|---|
| MINOR-1 | Mất nhịp "Đúng." khi bỏ C41 | **SAFE TO LEAVE** | Thông tin, nhân quả và kết luận còn đủ ở cảnh liền trước và liền sau; tinh thần "không ép Cố" nằm trong hành động ở cảnh bẫy Hạng bốn |
| MINOR-2 | Ba lần im lặng của Cố gộp thành một | **SAFE TO LEAVE** | Giảm thẻ lặp có chủ đích; nhịp "không đáp" và "nhìn hắn" còn |
| MINOR-3 | "Tôn Tứ khai vận chuyển" khớp yếu (có từ bản gốc) | **SAFE TO LEAVE** | Câu nói về vai trò, được hỗ trợ bởi lời Tôn Tứ ("Ta giữ hắn", "Phiếu", "Bốn") và bảng cuối. Không vi phạm ranh giới tri thức. Không do N2B tạo ra |
| MINOR-4 | "trên bảng" (`ep8.txt:1501`) | **SAFE TO LEAVE** (tùy chọn gói vào N3) | Làm rõ cục bộ, không thêm sự kiện. Lệch nhẹ "giấy chia bốn phần" → "bảng" không gây hiểu sai |
| MINOR-5 | Cảnh nhẫn: mất lượt dè dặt của Tĩnh An; mất liệt kê bốn vai | **SAFE TO LEAVE** | Hai lần dè dặt còn trong cảnh "Nhẫn ngọc đen" và với Hoài Xuyên; Bùi Tấn tự xác nhận về sau. "hợp thức hóa" còn nguyên |
| MINOR-6 | Mất mốc "đêm"/"cùng lúc" ở `ep8.txt:2113` và `ep5.txt:1381` | **SAFE TO LEAVE** (N3 nghe lại) | Cảnh liền trước đã nêu "Đêm đó" (ep8) và cảnh đêm của Chiêu Ninh (ep5); chuỗi vẫn hiểu được |
| MINOR-7 | "Chiêu Ninh cầm đũa lên." (`ep8.txt:1217`) | **SAFE TO LEAVE** | Hành động nhỏ khớp "Ăn cơm trước"; không đổi thông tin hay quan hệ |
| MINOR-8 | Kết ep8 "Chưa." có thể nghe là "chưa đến lúc chạy" | **SAFE TO LEAVE** | Khớp trạng thái ở `ep9.txt` mở tập (Chiêu Ninh vẫn canh cổng, "Không ai tới."); không tạo cliffhanger giả hay bí ẩn mới |

Kết quả: cả 8 mục đều **SAFE TO LEAVE**. Nếu tác giả muốn dọn trong N3, thứ tự ưu tiên thấp là MINOR-6 rồi MINOR-4; cả hai chỉ đổi cách diễn đạt.

---

## 4. Assessment of the 3 deferred threads

Không giải, không thêm giải thích.

| Thread | Phân loại | Lý do |
|---|---|---|
| K7/D2/N4 (ba nghĩa: điểm rút, "nhóm phí", "nhóm quân/nguồn Doanh hai") | **SAFE TO LEAVE** | Văn bản tự đóng khung: "chữ giống không có nghĩa cùng thứ"; Hoài Xuyên "không cố ép nghĩa mã nữa". Ba nghĩa không mâu thuẫn trực tiếp. Mạch chính (ai chọn Thẩm gia; Bùi Tấn nối các phần) không phụ thuộc vào việc chốt mã. Chốt thêm sẽ là canon mới |
| "Hộp trong Binh bộ" đưa số cho Hứa Nghiêm | **SAFE TO LEAVE** | Hứa Nghiêm "Không biết"; khớp AD-N2-02b (không gán danh tính cho nhóm chưa rõ mặt). Không có điểm nào buộc người nghe hỏi lại |
| Tam hoàng tử "Ta sẽ tra" | **SAFE TO LEAVE** | Lời hứa điều tra nhỏ ở cảnh phụ, không kéo theo bí ẩn hay payoff. Mạch Bùi Tấn đóng ở lời nhận và ở việc hồ sơ bị niêm; ở EP9 không cần kết quả của lời hứa đó |

Không mục nào cần N2C.

---

## 5. Story-level QA summary

| Tiêu chí | Kết luận | Ghi chú |
|---|---|---|
| Logic / nhân quả | **PASS** | Chuỗi điều tra EP8 (lộ dẫn → Lý Khâm → ba mã → Ninh Tứ/Tôn Tứ → Nam tứ → Cố Văn Lâm → Hạng bốn → Bùi Tấn → niêm hồ sơ) liền mạch sau N2B; cảnh bị bỏ (C41) không phải mắt xích. Chỉ còn mục R-01 ở EP1 là điểm có thể bị nghe là lệch |
| Động cơ nhân vật | **PASS** | Cố Văn Lâm ("tin mình đúng"), Hứa Nghiêm (từng bước), Trần Quảng (dừng lại), Bùi Tấn ("cần ông ấy rời Binh bộ") nguyên vẹn |
| Ranh giới tri thức | **PASS** (kèm kiểm lại ở N3) | EP7 Hoài Xuyên không nhớ; Bùi Tấn không có khung kiếp trước ("Cô nói như đã thấy"); Cố không bị gán là biết mạng. Các kênh tri thức R-04 chưa có bằng chứng vi phạm |
| Quan hệ / cảm xúc | **PASS** | Các nhịp chính Chiêu Ninh–Hoài Xuyên, cha–con, A Lục–Tử Khiêm không bị chạm |
| Setup / payoff | **PASS** | Nét móc, "hợp thức hóa", "cửa", "chạy", nhẫn ngọc đen, chữ ký, Lạc Thủy đều còn; các mạch mở còn lại đã được AD khóa hoặc nằm ở danh sách giữ nguyên (mục 7) |
| Bí ẩn | **PASS** | Ranh giới giữ: không gán danh tính nhóm vô danh, không giải mã K7/D2/N4, không giải thích nguồn hộp, không gán Tây Uyển cho ai |
| Audio | **PASS với giám sát** | Rủi ro còn lại là tải mã/tên ở EP8 và vài chuỗi hỏi–đáp dài; chỉ nghe thành tiếng mới kết luận được (N3) |
| Chronology | **PASS với ba điểm MINOR** | R-01, R-02, R-03 (đều có sẵn từ nguồn) |

Kiểm tra kỹ thuật còn cần ở N3 cuối: ngoặc “ ” cân (đã cân ở ep5/6/8/9 sau N2B), CRLF nguyên, không còn nhãn kịch bản hay tiêu đề cảnh, chính tả tên nhất quán.

---

## 6. Recommended N3 scope

N3 = QA cuối **giới hạn**. Không nén, không dọn cấu trúc, không audio polish tổng quát, không canon mới.

1. **Kiểm số học thời gian** (chỉ báo cáo): R-01, R-02, R-03. Chỉ sửa khi tác giả xác nhận một dòng "canon là gì" (đặc biệt R-01).
2. **Nghe thành tiếng, chỉ ở điểm nóng:** cụm mã/số/tên ở EP7–EP8 (K7/D2/N4, N-4, HX-4/H4, Nam 4/Nam tứ/Ninh Tứ, Hạng bốn, Tôn Tứ/Tứ gia); các chuỗi hỏi–đáp dài của EP8 (Bùi Tấn liệt kê tên, Tề Phương, bàn về Cố, Phùng Mậu về nhẫn); hai chỗ mất mốc thời gian (`ep8.txt:2113`, `ep5.txt:1381`). Chỉ gắn thẻ người nói hoặc neo thời gian nếu nghe thấy rối.
3. **Kiểm toàn vẹn kỹ thuật toàn bộ EP1–EP9:** ngoặc kép, CRLF, thứ tự thoại so với nguồn (đã có script), không sót nhãn kịch bản, chính tả tên.
4. **Đồng bộ tài liệu** (không đụng bản thảo): `MASTER_TIMELINE.md`, `KNOWLEDGE_MAP.md`, `AUTHOR_DECISIONS.md` (đưa các khóa B1 và AD-N2 vào; bỏ chi tiết đã cắt: bản sớ, đơn nặc danh, đứa trẻ đưa thư, Từ Kính "siết tay", con dấu mẻ), ghi chú H-12 của `PASS_N1B_REPORT.md`.
5. **Gói MINOR tùy chọn** (nếu tác giả muốn): MINOR-4 ("bảng"), MINOR-6 (hai mốc thời gian), R-01 (một câu EP1 nếu tác giả xác nhận).

Không đưa vào N3: nén thêm; sửa các mạch mở ở mục 7; chốt K7/D2/N4; gắn "kết quả" cho Tam hoàng tử; thêm dấu hiệu sớm cho Bùi Tấn.

---

## 7. DO-NOT-TOUCH list (mạch mở có chủ ý hoặc đã khóa)

- Tây Uyển: không gán cho ai (AD-N2-01 b, AD-04); câu "Cùng một cách, chưa chắc cùng một người." giữ nguyên.
- Nhóm chưa rõ mặt (người áo nâu, giọng kinh thành, kẻ trói Hàn Dực, kẻ đốt xe): chỉ "có thể thuộc nhóm giữ người ấy" (AD-N2-02 b).
- Từ Kính (AD-N2-03 b), Mã Tam (04 a), chủ Tấn Ký (05 b), em gái Hàn Dực (06 a), nguyên nhân chết của Trịnh Hành để mở (07 b), HX-4 / "Ba chuyện, cùng một cửa" / "Chưa biết." (08 b), con dấu mẻ (09 a), Bùi Tấn và Nhị hoàng tử xuất hiện muộn (10 a), hai điểm neo luận đề ở `ep6` sc.49 và `ep9` sc.6 (11 b).
- K7/D2/N4 với ba nghĩa; "chữ giống không có nghĩa cùng thứ".
- H4 không bị đồng nhất với HX-4.
- Hộp trong Binh bộ: "Không biết."
- Người mua sổ bù "người của phủ"; "Người khởi đầu? Có thể đã chết."; Nhị hoàng tử "không chắc".
- Nhẫn ngọc đen: một dấu hiệu có thể trùng nhiều người.
- Tam hoàng tử "Ta sẽ tra."
- Thẩm phu nhân "Năm đó ông giấu ta. Giờ lại giấu con."
- Hook EP1: "Phía trên đã có lệnh", "Bắc môn có động!"; chủ kho số ba; bốn hiệu bạc; dấu Ty Thông hành; vết thương trán Lục Trầm.
- Kết ep8 "Chưa."; cuối ep5, ep6, ep7, ep9 như hiện tại.
- Lạc Thủy: "Đê không vỡ."
- EP7: Hoài Xuyên không nhớ kiếp trước; EP8–EP9: chặn hồ sơ Hạng bốn, không tái thẩm; mốc 17/10 LK23 là ngày Thẩm phủ bị phong ở kiếp trước.

---

## 8. Final recommendation

N2B is approved. No structural N2C pass is required. Proceed to N3 final QA with the limited scope listed above.

- Bắt đầu N3 theo mục 6, theo thứ tự: (1) kiểm số học thời gian, (2) nghe điểm nóng, (3) kiểm kỹ thuật, (4) đồng bộ tài liệu.
- Điểm duy nhất cần ý kiến tác giả trước N3: thứ tự cái chết của Tĩnh An và Tử Khiêm (R-01); và nếu muốn, R-02 (số ngày "còn mười ngày").
- Tất cả MINOR còn lại có thể bỏ qua mà không ảnh hưởng chất lượng truyện.

STOP: không sửa bản thảo, không chạy N2C, không chạy N3.
