# FINAL_AUDIT — SONG ẢNH KINH THÀNH (Hồi I–VI)

Phạm vi: đọc lại CANON_DECISIONS.md, TIMELINE_LOCKED.md, EDIT_REPORT_H1 → H6, ep1.md → ep6.md (bản đã biên tập sang văn xuôi).
Quy tắc: không sửa truyện, không retcon, không tạo canon mới. File này chỉ liệt kê vấn đề và câu hỏi. Mọi mục "AUTHOR DECISION" là câu hỏi mở, không phải đề xuất nội dung.

## 0. Giới hạn của lượt audit này

- **Phương pháp:** đọc toàn văn sáu hồi và đối chiếu bằng tay, kèm `grep` để xác nhận một số điểm "chỉ xuất hiện một lần" (Sở Mậu, Tôn quản sự, chim sẻ, Mẫu Kính ở cuối truyện, Khâm Thiên Giám, Tạ gia). Không phải kiểm tra tự động toàn bộ. Có thể còn sót.
- **Nguồn ep6.md:** bản trong working tree là bản Hồi VI trên nhánh `claude/modest-tesla-3c3wg1` (PR #8, chưa merge vào `main` tại thời điểm audit). ep1–ep5 là bản đã merge.
- **Danh sách "nhóm A" gốc (#1 → #30) không có trong repo.** Chỉ biết các mã được nhắc trong CANON_DECISIONS và các báo cáo. Trạng thái các mã sau **không xác nhận được**: #3, #21, #22, #26, #27 (nhóm A), và #2, #18, #24, #30 (nhóm C). Các mã đã thấy được xử lý trong báo cáo: #4, #19 (H1), #11, #12, #13, #14, #15 (H1/H2), #9, #23 (H5), #29 (mọi hồi). #20 là nhóm C, giữ nguyên.
- **Ký hiệu mức độ:** Cao (có thể làm người nghe thấy lỗ hổng hoặc mâu thuẫn), Trung, Thấp.

---

## 1. Setup chưa payoff

Setup đã gieo trong truyện nhưng không có đoạn nào đóng lại. Không gồm các mục tác giả đã cố ý để mở (xem mục 3).

| ID | Setup | Gieo ở | Ghi chú | Mức |
|---|---|---|---|---|
| S-01 | Cuộn lụa trong hạt ngọc: "Tạ Vân Cơ đã chết trong Phượng Môn" | H2 cảnh khai A Yên | Câu này nói Tạ Vân Cơ đã chết từ 13 năm trước, trong khi canon (CANON_DECISIONS) xác định nàng chết đêm 13→14 trong lồng. Không hồi nào giải thích câu này nghĩa là gì hay ai viết. Xem AD-01 | Cao |
| S-02 | Giọng "Ta là…" giữa đám cháy | H1 cảnh 1 | CANON_DECISIONS B-04 nói có thể là người thật. Không hồi nào cho biết ai nói, nói gì | Trung |
| S-03 | Mắt thi thể "trắng đục như mặt gương", khói tím, đèn tắt, giọng "Lần này tới lượt tỷ mang tên ta" | H1 cảnh 6 | B-04 (a) đã khóa: giải thích bằng cơ quan, "cần một dòng xác nhận ở hồi sau". Hồi III chỉ có ống đồng ở tầng chín; không có câu nào nối lại với cảnh H1 hay nêu ai nói. Tô Mạn xác nhận Bế Tâm Sa (khói tím) và Hàn Thiền ở H2, nhưng lớp sáng ở mắt và giọng nói không được xác nhận | Cao |
| S-04 | Sở Mậu | H2 | Chỉ xuất hiện ở H2 (hai lần). Không bị truy ra, không bị loại trừ. Đã được tác giả đánh dấu mở (xem mục 3, O-01) | Trung |
| S-05 | Sáu thợ cơ quan mất tích; thư ghi "người đúc Phượng Môn bị cắt lưỡi" và "Tôn quản sự gãy một cánh tay" | H1, H2 | Chỉ Trương Đồng có kết cục (chết, H2). Năm người còn lại và Tôn quản sự không xuất hiện lại | Thấp–Trung |
| S-06 | Ba biểu tượng ở ngã ba đường hầm: đóa trà, con quạ, bàn tay sáu ngón; con quạ bị cắt một cánh ở cuối thư; đàn quạ ở H1 | H1, H2, H3 | Đóa trà (Thủy Nguyệt Các) và bàn tay sáu ngón (Vô Danh Môn) có nghĩa. Con quạ không có nghĩa nào được nêu | Thấp |
| S-07 | Bản đồ bảy cây kim đỏ: Thủy Nguyệt Các, La Sinh Đài, Đại Lý Tự, Tháp Quan Tinh, phủ Quốc sư, Tạ gia cũ, tẩm điện Hoàng đế | H3 cảnh 14 | Chỉ tháp, hoàng cung (và gián tiếp phủ Quốc sư qua Kỷ) liên quan về sau. Không nêu ai cắm kim và để làm gì | Trung |
| S-08 | Căn phòng thứ chín: bảy bộ tóc giả, giày, vòng tay, mặt nạ lụa | H3 cảnh 14 | Không nêu phòng thuộc ai (Tạ Vân Cơ hay Vô Danh Môn). B-06 (c) có quyết định về chân dung và tàn ảnh, nhưng không nói gì về căn phòng | Trung |
| S-09 | Hàng chục bóng người mang mặt Thanh La quanh bể nước ở chuông 5–7 | H1 cảnh 6 | Không có đoạn nào giải thích bằng cơ quan hay tàn ảnh. H2 chỉ giải thích tiếng chuông thứ tư và cơ chế kim | Trung |
| S-10 | Ổ khóa thứ tám không xoay được | H1 cảnh 6 | H2 chỉ nhắc Tiểu Sơn kiểm tra ổ thứ tám; không nêu vì sao nó kẹt | Thấp |
| S-11 | Sẹo bán nguyệt ở cổ tay phải thi thể; vết bỏng vai "của ai" | H2 cảnh 8 | Vân Cơ "không nhớ rõ vai của ai bị thương". Không hồi nào trả lời. Nhóm C #20: giữ nguyên trừ khi tác giả yêu cầu | Thấp |
| S-12 | Kẻ đeo mặt nạ đồng và bàn tay sáu ngón trong đêm cháy Vô Tướng Ban; Vân Cơ đâm cánh tay hắn và chém ngón thứ sáu; "Hắn không già đi" | H1, H2 | H6 cho biết ngón sáu là ngón gỗ gắn thêm (Kỷ, Mộc Dung). Không nêu ai là kẻ đeo mặt nạ trong đêm cháy 13 năm trước, và vết đâm ở cánh tay không bao giờ được dùng để nhận diện | Trung |
| S-13 | "Chiếc khóa thứ chín" nằm trong mộ sư phụ; Thanh La đào mộ, quan tài trống | H1 cảnh 5 | H2–H4 dùng chiếc chìa số chín, nhưng không nối với "khóa thứ chín trong mộ". "Quan tài trống" được đáp lại bằng việc Cố còn sống, nhưng không có câu nào nói vì sao có mộ | Trung |
| S-14 | Vết cắt tay, lời "không nhớ" và chiếc gương dính máu của "Phí Kinh Hồng" | H1, H3 | B-01 (b) khóa hướng chung, nhưng không nói vết cắt và mất ký ức là thật hay diễn, và hắn "nhìn thấy gì". Hồi IV vạch mặt hắn mà không trả lời câu này. Xem AD-03 | Trung |
| S-15 | Máu của Cố Bách Xảo dính vào Mẫu Kính trước khi lửa nổ; Cố biết trước có chuyện ("Lát nữa nếu có chuyện…", "bỏ màn ấy") | H1 cảnh 1 | Không giải thích Cố biết trước bằng cách nào, và máu dính vào gương có gây ra gì không | Trung |
| S-16 | Chim sẻ chết và dòng "Kẻ không có tên không xứng sống qua đêm nay" | H1, H2 | H2: A Yên đáp hộp đặt ở cửa sau, không thấy ai. Không bao giờ nói ai gửi (tác giả đã duyệt câu trả lời này, nhưng người gửi vẫn chưa rõ) | Thấp–Trung |
| S-17 | Số phận Mẫu Kính sau Hồi VI (nứt ở mép), bình máu Tạ Vân Cơ, nửa gương còn lại | H1 → H6 | Lần nhắc cuối cùng của Mẫu Kính là cảnh 36–37 (Hạ hỏi "Mẫu Kính lấy gì?"). Cảnh cuối chỉ có "chiếc gương đồng dùng trong màn diễn". Không có câu nào cho biết ai giữ, ai phá hay cất. Xem AD-06 | Cao |
| S-18 | Hoàng đế giả (người đóng giả) | H4–H6 | Bị lộ ở H6 cảnh 36 rồi không xuất hiện lại. Cùng nhóm: sáu người đeo mặt Phí chạy ra sáu hướng, "bốn người biến mất" ở H4, hơn hai mươi người Khâm Thiên Giám che mặt. Cảnh 38 chỉ nhắc "người giữ cửa, thợ làm mặt nạ" | Trung |
| S-19 | Khâm Thiên Giám (cơ quan do Kỷ điều khiển) | H2 → H5 | Không xuất hiện ở H6. Số phận cơ quan không được nêu | Trung |
| S-20 | Tạ gia bị kết tội mưu phản, người lớn chết trong ngục | H3 → H6 | H6 có miễn tội cho Cố vì lời khai bị ép, và tàn ảnh cho thấy Cố bị ép ký. Không có câu nào nói Tạ gia được minh oan hay không | Trung |
| S-21 | "Hữu danh vô thực" (bốn chữ trên mặt hồ) | H1 cảnh 2 | Không được nhắc lại. Có thể coi là chủ đề, không phải setup cần payoff; ghi lại để tác giả xác nhận | Thấp |

---

## 2. Payoff chưa đủ setup

Payoff có xuất hiện, nhưng nền gieo trước đó mỏng, mơ hồ hoặc lệch.

| ID | Payoff | Chỗ payoff | Vì sao chưa đủ | Mức |
|---|---|---|---|---|
| P-01 | "Mặt thì không. Nhưng tỷ nhận ra muội." | H6 cảnh 39 | Setup có đủ (H1: ngón út co, "Bằng gì?"). Nhưng H1 gán dấu ấy cho ngón út **tay trái** của Thanh La, trong khi người co ngón út tay trái (H1, H2, H5) là **chính Vân Cơ**; ngón co cố ý của Tạ Vân Cơ là **tay phải**. "Tỷ nhìn nhầm người rồi" (H1) không bao giờ được giải thích. Người nghe có thể hiểu payoff cảm xúc, nhưng chi tiết dấu hiệu nhận ra không khép lại. Xem AD-12 | Trung |
| P-02 | Người mặc áo trắng đeo vòng Thủy Nguyệt Các nói "Xin lỗi" là Tạ Vân Cơ | H2 cảnh 10 | B-06 (c) đã khóa điều này, nhưng không có câu nào nói thẳng trong truyện; Hồi II chủ ý không nói vì cảnh đứng trước đoạn lộ danh tính. Không hồi sau nhắc lại. Hai nửa còn lại của B-06 (chân dung là hồ sơ kẻ giả mạo của Vô Danh Môn; bảy tàn ảnh phần lớn là kẻ giả) cũng không được xác nhận trong truyện | Trung |
| P-03 | Bước ngoặt của Mộc Dung ("Làm phần nàng để lại") và hy sinh | H6 cảnh 35–37 | Quan hệ Mộc Dung – Tạ Vân Cơ chỉ được thấy lần đầu trong một tàn ảnh ở H6. Trước đó Mộc Dung chỉ là sát thủ giả mặt (H3–H5), với một dấu hiệu duy nhất ở H4 (ánh mắt nhìn lửa) | Trung |
| P-04 | Tàn ảnh ở H6 cho thấy Kỷ giết Phí thật và ép Cố ký lời khai 24 và 23 năm trước | H6 cảnh 36 | Setup là "tàn ảnh là việc đã xảy ra" (handbook). Không có nền nào cho việc Mẫu Kính đã ghi những cảnh đó (ai cho máu, khi nào) | Trung |
| P-05 | Người đóng giả mất gì khi cho máu (B-09 c) | H6 cảnh 33 | B-09 (c) khóa luật "máu người chết không ai trả giá; máu người sống mới tính" nhưng Hồi VI không có câu nào thể hiện hậu quả cho người giả (chỉ có sự lúng túng của hắn, vốn đã có sẵn). Luật chưa xuất hiện trong truyện | Thấp–Trung |
| P-06 | Chuông thứ tư ở La Sinh Đài làm "Phí Kinh Hồng" bất ngờ thật (B-01 b) | H1 → H2 | H2 xác nhận có cơ quan lắp dưới sân khấu. Không có đoạn nào nói ai lắp, vì sao chuông này làm Kỷ bất ngờ, hay ý nghĩa với kế hoạch | Trung |
| P-07 | Đứa trẻ sợ sấm là ai | H3 → H4 | H3 đặt nghi vấn "đứa trẻ trong ký ức đó là ai?". H4 Cố gõ ám hiệu "đứa trẻ sợ sấm" với Vân Cơ nhưng Vân Cơ không nhớ mặt đứa trẻ bên cạnh. Câu hỏi H3 được trả lời ngầm, không rõ | Thấp |
| P-08 | B-08 (c): Cố "chấp nhận" cái tên mới | H6 cảnh 38 | Thiết kế có chủ ý mỏng (không có cảnh mới). Material chỉ là một dòng ở H3 ("Lục Thanh La là tên ông đặt") và một cử chỉ ở H6. Handbook vẫn ghi payoff là "Trả lại tên thật cho họ"; tác giả đã nhận cập nhật handbook | Thấp |
| P-09 | Dòng Mộc Dung nói ở H3 ("Ngươi đã mang tên ta quá lâu") và khuôn mặt hiện ra khi kẻ tấn công bị giật mặt nạ | H3 cảnh 18 | Tàn ảnh cho thấy khi mặt nạ bị giật, bên dưới vẫn là khuôn mặt của Tạ Vân Cơ. Khuôn mặt thật của Mộc Dung (bỏng nặng, H4) không phải khuôn mặt đó. Câu nói cũng không khớp vai trò Mộc Dung ở H4–H6. Xem AD-13 | Trung |
| P-10 | "Lần này tới lượt tỷ mang tên ta" | H1 → H6 | Câu H1 không được nối với việc Vân La chọn tên mới ở H6 (chữ "Vân" của Tạ Vân Cơ, chữ "La" của Lục Thanh La). Có thể là chủ ý, nhưng hiện chưa có dấu hiệu xác nhận | Thấp |

---

## 3. Open setup (còn mở, đã được ghi nhận hoặc cố ý)

| ID | Mục | Nguồn xác nhận | Trạng thái |
|---|---|---|---|
| O-01 | **Sở Mậu** | EDIT_REPORT_H2 (tác giả duyệt, đánh dấu setup còn mở); nhắc lại ở H3, H4, H5, H6 | Chưa payoff. Không xuất hiện sau H2. Là setup duy nhất được tác giả đánh dấu mở |
| O-02 | Quan hệ Hạ Tử Khiêm ↔ Vân La | handbook mục 6 ("Mở. Có thể phát triển sequel"); H6 ("Phần còn lại ghi nợ") | Mở có chủ ý |
| O-03 | B-04: ai nói qua ống đồng ở tầng chín Tháp Quan Tinh | CANON_DECISIONS B-04; EDIT_REPORT_H3, H4, H5, H6 | Chưa chốt. Xem AD-02 |
| O-04 | TIMELINE X-1 → X-6 | TIMELINE_LOCKED mục 5 | Chờ tác giả xác nhận. Xem AD-14 |
| O-05 | Không còn Mẫu Kính trong cảnh cuối ("Không có Mẫu Kính. Không có máu.") | H6 cảnh 39 | Có thể cố ý, nhưng không nêu nó đi đâu. Gộp với S-17 |
| O-06 | Cố Bách Xảo mở lớp dạy bọn trẻ làm cơ quan sân khấu | H6 cảnh 38 | Không phải setup; ghi lại để tác giả xác nhận không cần payoff thêm |

---

## 4. Continuity risk

| ID | Rủi ro | Vị trí | Mức |
|---|---|---|---|
| C-01 | **Tên gọi gây nhầm khi nghe:** nhân vật chính là "Vân Cơ" (bản thảo) trong khi người chết trong lồng là "Tạ Vân Cơ". H4–H6 dùng cả hai ở cùng đoạn (đặc biệt tàn ảnh H5 cảnh 28 và H6 cảnh 35). Đã giảm bằng cụm "người chết trong lồng" ở nhiều chỗ nhưng vẫn còn đoạn chỉ gọi "Tạ Vân Cơ". Với bản nghe, người nghe có thể nhầm. Xem AD-11 | H4–H6 | Trung |
| C-02 | **Luật phản chiếu của Mẫu Kính:** "không phản chiếu người đã cho máu" (H1 sửa, H3 nêu). Vân Cơ, Hạ Tử Khiêm đều cho máu về sau (H2, H3, H5, H6), nhưng không có cảnh nào nhắc lại việc họ còn hay không còn phản chiếu. H6 Mộc Dung nhìn "mặt gương thứ mười hai" thấy khuôn mặt thật; đó là gương tháp, không phải Mẫu Kính, nhưng chưa phân biệt | H1, H3, H6 | Thấp–Trung |
| C-03 | **Thời lượng tàn ảnh theo B-03 (b):** B-03 viết máu tự nguyện giữ lâu (một canh giờ), máu ép chỉ bảy nhịp. Vân Cơ tự cắt tay (tự nguyện) nhưng tàn ảnh chỉ bảy nhịp (H2 cảnh 10, H6 cảnh 35). Cách đọc nhất quán nhất: "một canh giờ" cần máu Tạ gia tự nguyện. Canon chưa nêu thẳng. Xem AD-05 | H2, H5, H6 | Trung |
| C-04 | **Tám khóa, tám chìa và cửa sắt:** H1 Hạ nói tám khóa do Đại Lý Tự mang tới; H2 nói Trương Đồng đúc tám khóa cho Vô Tướng Ngục; H3 tám chìa Đại Lý Tự niêm phong vừa khít tám ổ của cửa sắt dưới đường nước. Hai nguồn "ai làm khóa" và việc chìa lồng mở được cửa đường hầm chưa được nối | H1, H2, H3 | Trung |
| C-05 | **Kiểm tra tóc và y phục trước buổi diễn:** H1 Hạ nói mọi thứ phải kiểm tra, nhưng độc Bế Tâm Sa trong tóc và cây kim giấu trong áo vẫn lọt. H3 cho thấy nạn nhân tự bôi độc trong phòng hóa trang; không có cảnh kiểm tra nào để đối chiếu | H1, H2, H3 | Thấp–Trung |
| C-06 | **Hai mươi bảy phụ nữ và 27 vụ giả chết:** H3: "những trang cũ hơn không phải nét chữ của chúng ta"; H6 Vân Cơ bị thẩm vấn về 27 vụ giả chết. Một phần trang cũ do người khác viết, nhưng toàn bộ 27 bị quy cho Vân Cơ | H3, H6 | Thấp |
| C-07 | **Hạ Tử Khiêm không bắt Kỷ Vô Nhai ở cổng:** H4 Hạ vạch mặt Kỷ; H6 hắn vẫn đứng đón và chỉ nói chuyện. Phù hợp mưu kế vạch mặt trước bá quan, nhưng chưa có câu nào cho biết kế hoạch này | H4, H6 | Trung |
| C-08 | **Trương Đồng chết trong trống Đăng Văn:** cách xác bị nhét trong trống và vào giữa sân Đại Lý Tự, trống tự nổ ba tiếng, không được giải thích | H2 cảnh 12 | Thấp–Trung |
| C-09 | **Khám người:** quan sai chỉ thu trâm và dao nhỏ của Vân Cơ (H2) nên nửa Mẫu Kính còn trong tay áo; Mộc Dung giấu mảnh kim loại sau khi bị trói (H4); tới H6 Mộc Dung lại dùng mảnh kim loại cắt dây. Cả hai lần đối phương đều không khám | H2, H4, H6 | Thấp–Trung |
| C-10 | **"Lục Thanh La" trước công chúng:** công chúng thấy Lục Thanh La chết trong lồng (H1) nhưng ở H6 lính gác Kỷ truy "Lục Thanh La" (cảnh 34). Cần xác nhận lính truy người đeo mặt nạ đỏ như một nhân vật bị truy nã, không phải người đã chết | H1, H6 | Thấp |
| C-11 | **Thời điểm Tạ Vân Cơ nắm sơ đồ Vạn Đăng Yến:** chỉ dụ ban ngày 12 (người giả ban chỉ); Tạ Vân Cơ chết đêm 13→14 nhưng khắc sơ đồ và cách đảo gương vào khoang cát của lồng đã đúc từ trước | H4, H5 | Thấp–Trung |
| C-12 | **Số lượng gương, trâm, mặt nạ, cây kim, hạt ngọc:** các chi tiết nhỏ đã được rà trong từng hồi (H2 cây trâm, H3 trâm trả lại, H4 số cây trâm) và không phát hiện mâu thuẫn mới. Ghi lại để tác giả biết đã rà | H2–H4 | Thấp |

---

## 5. Knowledge-state risk

Nhân vật biết điều gì tại thời điểm hành động, và nguồn tin chưa được nêu.

| ID | Nhân vật | Điều biết hoặc làm | Rủi ro | Mức |
|---|---|---|---|---|
| K-01 | Kỷ Vô Nhai | Đợi sẵn trong hầm băng đúng đêm 15→16 với hơn mười người, Mộc Dung và lọ Thanh Tâm Lộ (H5) | Không nêu cách hắn biết nhóm Hạ sẽ vào hầm băng, đúng đêm đó, bằng đường nào. Hợp B-01 (a) (dẫn dắt có chủ đích) nhưng thiếu nguồn tin | Trung |
| K-02 | Kỷ Vô Nhai | Tiếp tục buổi Vạn Đăng Yến dù Hoàng đế thật đã bị cứu khỏi hầm băng (H5) và Hạ đã vạch mặt hắn (H4) | Không nêu hắn tính gì. Hợp mục tiêu "tàn ảnh Hoàng đế trước bá quan", nhưng người nghe có thể thắc mắc | Trung |
| K-03 | Kỷ Vô Nhai | Kể trọn kế hoạch của Tạ Vân Cơ ("hai Lục Thanh La xuất hiện cùng lúc") ở H5 | B-01 (b): hắn chỉ cài Mộc Dung đổi thuốc. Nguồn tin có thể là Mộc Dung (ở bên Tạ Vân Cơ), nhưng chưa nêu | Thấp–Trung |
| K-04 | Kỷ Vô Nhai (khi mang mặt Phí) | Nói "Đã quá lâu. Có lẽ ta nhớ nhầm" về Vô Tướng Ngục, và để ý mặt thứ năm ngay từ H1 | Không nêu hắn từng thấy Vô Tướng Ngục khi nào (bị đuổi khỏi Vô Tướng Ban trước khi hai đứa trẻ về đoàn theo TIMELINE) | Thấp |
| K-05 | Cố Bách Xảo | Biết Hoàng đế "đã chết" và "người trong cung là giả", biết thuốc Hàn Thiền, Dưỡng Tâm Lộ, hạn mười ngày (H4, H5) | Bị xích 13 năm dưới tháp; chưa nêu nghe tin từ đâu | Trung |
| K-06 | Cố Bách Xảo | Biết trước đêm Vô Tướng Ban cháy (H1: dặn "đi thẳng ra cửa sau") | Chưa nêu biết bằng cách nào (xem S-15) | Trung |
| K-07 | Hạ Tử Khiêm | Mất ký ức (H3). Không nhớ Vân Cơ và Phí; vẫn biết Tiểu Sơn, Tô Mạn, lai lịch công khai của Quốc sư ("theo hồ sơ"), chìa số chín trong túi | Phạm vi và cách quay lại của ký ức không được canon xác định. H5 và H6 làm rõ là ký ức mới (15→18); không có câu nói rõ ranh giới giữa điều hắn nhớ và quên. Xem AD-10 | Trung |
| K-08 | Tô Mạn | Nhận ra tín hiệu ngón út tay trái của Vân Cơ ở hầm băng (H5) | Chưa có cảnh nào cho thấy Tô Mạn biết tín hiệu hoặc đã bàn trước | Thấp |
| K-09 | Tạ Vân Cơ (đã chết) | Biết kế hoạch Vạn Đăng Yến, cách đảo mười hai gương, và để lại thư cho Vân Cơ phòng khi không tỉnh | Nguồn kiến thức về kế hoạch của Kỷ trước khi chỉ dụ ban chưa rõ (xem C-11) | Thấp–Trung |
| K-10 | A Yên | Chuẩn bị tóc, nhận thuốc từ "sư phụ", khai "không biết có Bế Tâm Sa" (H2) | H3 cho thấy nạn nhân tự bôi Bế Tâm Sa, nên lời khai hợp lý, nhưng không có câu nào xác nhận A Yên vô tội. Nhân vật và người nghe có thể vẫn nghi | Thấp |
| K-11 | Vân Cơ | Tin mình là Lục Thanh La (H2) rồi bị đặt nghi vấn (H3, "Cô chưa từng là Lục Thanh La"); Cố gật xác nhận (H4); H6 khẳng định "Lục Thanh La từng là tên nàng" | Đã khép ở H6, nhưng người nghe cần nhớ H3 là lời dối của Mộc Dung. Không có câu nào gọi thẳng đó là lời dối | Thấp |
| K-12 | Hạ Tử Khiêm | Dùng "mật chỉ" niêm phong giả ở H6 | Là mưu kế, không phải thông tin sai; nhưng Hạ nói "Người dặn phải mở trước bá quan" mà không nói đã xác nhận với ai | Thấp |

---

## 6. Các mục cần AUTHOR DECISION

Mỗi mục là câu hỏi cần tác giả trả lời. Không có mục nào được tự trả lời trong audit này.

| ID | Câu hỏi | Liên quan | Ưu tiên |
|---|---|---|---|
| AD-01 | Cuộn lụa trong hạt ngọc ghi "Tạ Vân Cơ đã chết trong Phượng Môn": ai viết, câu này nói gì, và có mâu thuẫn với việc Tạ Vân Cơ chết trong lồng không? | S-01 | Cao |
| AD-02 | B-04: ai nói qua ống đồng ở Hồi III, và hồi nào xác nhận cơ chế mắt, khói, giọng nói ở Hồi I (đã khóa là cơ quan/vật lý)? Giọng "Ta là…" ở cảnh cháy có phải người thật không? | S-02, S-03, O-03 | Cao |
| AD-03 | Vết cắt tay, "mất ký ức" và chiếc gương dính máu của "Phí Kinh Hồng" ở Hồi I–III là thật hay diễn? Hắn thật sự nhìn thấy gì? | S-14 | Trung |
| AD-04 | Sở Mậu: payoff, vô hiệu hóa có lý do, hay bỏ? | S-04, O-01 | Trung |
| AD-05 | Luật thời lượng tàn ảnh theo máu (B-03 b): "một canh giờ" có phải chỉ áp dụng cho máu Tạ gia tự nguyện? Máu tự nguyện không phải họ Tạ thì giữ bao lâu? B-09 (c) có cần câu thể hiện trong truyện không? | C-03, P-05 | Trung |
| AD-06 | Số phận Mẫu Kính (nứt ở mép), bình máu và nửa gương còn lại sau Hồi VI. | S-17, O-05 | Cao |
| AD-07 | Số phận Hoàng đế giả, sáu người đeo mặt Phí, người Khâm Thiên Giám, và việc Tạ gia có được minh oan không. | S-18, S-19, S-20 | Trung |
| AD-08 | Ai gửi chim sẻ chết, và "Kẻ không có tên" nhắm tới ai? | S-16 | Thấp–Trung |
| AD-09 | Bảy chân dung, bảy tàn ảnh, căn phòng thứ chín, bảy kim đỏ và câu "Xin lỗi": có cần xác nhận trong truyện không (B-06 c chỉ khóa ý, chưa nói trong văn)? | S-07, S-08, P-02 | Trung |
| AD-10 | Phạm vi mất ký ức của Hạ Tử Khiêm (không nhớ gì, nhớ gì) và có cần xác nhận trong truyện không? | K-07 | Trung |
| AD-11 | Quy ước gọi tên: tiếp tục dùng "Vân Cơ" (nhân vật chính) và "Tạ Vân Cơ" (người chết) như hiện nay, hay cần cách phân biệt rõ hơn cho bản nghe? | C-01 | Trung |
| AD-12 | Dấu hiệu ngón út: tay trái hay tay phải thuộc về ai? "Tỷ nhìn nhầm người rồi" (H1) có cần giải thích? | P-01 | Trung |
| AD-13 | Tàn ảnh H3: khuôn mặt hiện ra khi giật mặt nạ kẻ tấn công và câu "Ngươi đã mang tên ta quá lâu" có khớp Mộc Dung (mặt bỏng) và vai trò của nàng ở H4–H6 không? | P-09 | Trung |
| AD-14 | TIMELINE X-1 → X-6: X-1 (hoàn cảnh Cố ký lời khai), X-2 (tuổi Hoàng đế 29), X-3 (tuổi và mốc của Kỷ), X-4 (tuổi Cố và Phí), X-5 (ngày giỗ ngày 14), X-6 (năm Kỷ thay Phí). Hiện Hồi IV và VI dùng "hai mươi bốn năm" theo hàng đã khóa. | O-04 | Trung |
| AD-15 | Nguồn tin của Kỷ (hầm băng, tiếp tục Vạn Đăng Yến, kế hoạch Tạ Vân Cơ) và kế hoạch vạch mặt của Hạ ở cổng. | K-01, K-02, K-03, C-07 | Trung |
| AD-16 | Nguồn tin của Cố Bách Xảo (tình trạng Hoàng đế, kế hoạch người giả) và việc ông biết trước đêm cháy 13 năm trước. | K-05, K-06, S-15 | Trung |
| AD-17 | Khóa, chìa và cửa sắt: tám khóa Đại Lý Tự mang tới có cùng loại với tám khóa Trương Đồng đúc không; vì sao ổ thứ tám kẹt; "chiếc khóa thứ chín" trong mộ là gì? | C-04, S-10, S-13 | Thấp–Trung |
| AD-18 | Thợ cơ quan mất tích còn lại, Tôn quản sự, người đúc Phượng Môn, con quạ bị cắt cánh: có cần payoff hay chấp nhận bỏ? | S-05, S-06 | Thấp |
| AD-19 | Hàng chục bóng người ở chuông 5–7 (H1) có cần giải thích không? | S-09 | Trung |
| AD-20 | Cập nhật handbook (editor không sửa): (1) B-08 (c) payoff Cố ↔ hai đồ đệ; (2) B-03 (b) và B-09 (c) luật máu tự nguyện/bị ép và máu người chết; (3) bỏ "nuốt âm thanh"; (4) timeline mốc −24, −23, −16 và bảng tuổi nếu X được xác nhận; (5) các chi tiết xác nhận qua sáu hồi. | O-04, các báo cáo H1–H6 | Cao |
| AD-21 | Danh sách nhóm A gốc không có trong repo: cần cung cấp để xác nhận trạng thái #3, #21, #22, #26, #27 và nhóm C #2, #18, #24, #30. | mục 0 | Cao |
| AD-22 | Các điểm khám người và thiếu kiểm tra (Vân Cơ H2, Mộc Dung H4/H6, tóc và y phục H1) có cần xử lý hay chấp nhận? | C-05, C-09 | Thấp |
| AD-23 | Lính truy "Lục Thanh La" ở Vạn Đăng Yến và 27 vụ giả chết quy cho Vân Cơ: giữ nguyên hay cần xác nhận? | C-06, C-10 | Thấp |
| AD-24 | Luật phản chiếu của Mẫu Kính (người đã cho máu không có bóng): có cần áp dụng lại cho Vân Cơ, Hạ Tử Khiêm sau khi họ cho máu không? | C-02 | Thấp |

---

## 7. Tổng kết ngắn

- **Không phát hiện** điểm nào trong ep1–ep6 đang vi phạm trực tiếp B-01 → B-10 hoặc các hàng đã khóa trong TIMELINE_LOCKED (các sửa đã ghi ở EDIT_REPORT_H2 → H6).
- **Nhóm rủi ro cao nhất cho người nghe:** S-01 (cuộn lụa "đã chết trong Phượng Môn"), S-03 (B-04 chưa có dòng xác nhận), S-17 (Mẫu Kính không có kết cục), C-01 (hai tên gần giống nhau trong bản nghe).
- **Setup còn treo được tác giả ghi nhận:** Sở Mậu (O-01) và quan hệ Hạ ↔ Vân La (O-02, cố ý).
- Phần lớn các mục còn lại là điểm chưa giải thích. Chúng chỉ là lỗi nếu tác giả coi chúng là setup cần payoff; nếu muốn để mơ hồ, chỉ cần ghi nhận trong handbook.
