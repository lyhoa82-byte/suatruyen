# PASS N2B — BÁO CÁO RÀ SOÁT (REVIEW ONLY)

Phạm vi: rà soát các thay đổi N2B (commit `4d1749c` so với `7ff49e1`) trên bản thảo hiện tại. Không sửa bản thảo, không sửa chữa, không mở lại AD-N2-01..11, không thêm canon.
Neo dòng: số dòng **hiện tại** trong tệp (sau N2B). `PASS_N2B_REPORT.md` dùng số dòng **trước** khi sửa nên lệch với báo cáo này.
Nhãn: **PASS** · **MINOR** · **MEDIUM** · **HIGH**.

Tài liệu đã đọc: `PASS_N2B_REPORT.md`, diff thực tế (chỉ `ep5`, `ep6`, `ep8`, `ep9` + báo cáo; `EP1`–`EP4` và `ep7` không bị chạm), `ep8.txt` toàn bộ, phần đầu/cuối `ep9`, `PASS_N2A_AUDIT.md`, `PASS_N2A_AUTHOR_DECISION_PREP.md`, `N2B_DECISION_EXECUTION_REPORT.md`, `N2B_POST_EXECUTION_MICRO_REPAIR_REPORT.md`.

---

## 1. Executive verdict

**N2B is structurally approved pending only optional micro-fixes, if any.**

- Không có HIGH. Không có MEDIUM.
- 8 phát hiện MINOR, đều tùy chọn. Không cái nào làm đổi ai biết gì, khi nào biết, sự kiện, chứng cứ, động cơ hay quan hệ.
- Cảnh C41 bị bỏ: **SAFE**.
- Ba mục DEFERRED: cả ba **SAFE TO LEAVE OPEN**.
- Một ghi chú minh bạch (không phải lỗi): câu sổ "Tàn cục không có một người đánh" (ep8:3205 hiện còn dòng thay thế) bị bỏ **không nằm** trong danh sách 13 câu luận đề của N2A (F2) hay danh sách AD-N2-11 đã thực thi. Việc bỏ nằm trong quyền hạn N2B ("bỏ các câu luận đề thừa còn lại"), và không mâu thuẫn với lựa chọn "một câu kết" ở ep9 sc.6. Xem mục 4.

---

## 2. Structural integrity

### 2.1 EP8 C41 — cảnh tóm tắt "ba người đã nhận phần" — **SAFE**

Nội dung cảnh bị bỏ (theo diff): Chiêu Ninh liệt kê Hứa Nghiêm / Phùng Mậu / Tôn Tứ; "Cố Văn Lâm? Chưa. Nhưng hồ sơ qua tay hắn. Có thể biết / có thể không"; "Không cần ép hắn thành nút thứ tư nếu chưa đủ." — "Đúng."

| Kiểm tra | Kết quả |
|---|---|
| Thông tin riêng | Không có. Ba vai trò đã nằm ở ep8:1501 và bảng cuối (ep8:2599). "Tôn Tứ … giữ người" còn ở lời Tôn Tứ (ep8:2279 "Ta giữ hắn") và bảng cuối. |
| Chuyển tiếp nhân quả | Cảnh liền trước (Tề Phương, ep8:~1917) kết bằng câu người kể: "Không đủ bắt Cố Văn Lâm vì mạng lưới. Nhưng đủ chứng minh hồ sơ có bất thường…" — đã mang đúng kết luận. Cảnh liền sau (ep8:1959) mở bằng "Ba nút đã lộ… Còn hồ sơ… Chưa chắc." — tự nhắc lại. Không có chỗ nhảy. |
| Phản ứng nhân vật | Không có phản ứng riêng. |
| Nhịp cảm xúc | Chỉ còn một nhịp rất nhỏ "Đúng." (Hoài Xuyên đồng ý với Chiêu Ninh). Không phải nhịp quan hệ chính. |
| Thay đổi tri thức | Không. "Cố chưa đủ" vẫn được thể hiện ở ep8:~2540–2580 (Hoài Xuyên "Cần chứng", bẫy Hạng bốn, "không phải người của mạng"). |
| Phụ thuộc xuôi dòng | "bảng" (xem 3.3) và "nút chứng cứ" (ep8:2589) còn nguyên. Không còn tham chiếu nào tới "ba người đã nhận phần" hoặc "nút thứ tư" trong ep7–ep9 (đã grep). |

Phát hiện phụ (MINOR-1, xem mục 10): mất một lần Chiêu Ninh–Hoài Xuyên cùng nói rõ "không ép Cố thành nút thứ tư". Tinh thần này vẫn nằm trong hành động ở cảnh bẫy. Không cần sửa.

### 2.2 Ba lời khai về Cố Văn Lâm gộp thành một lượt — **PASS** (kèm MINOR-2)

Hiện tại (ep8:2581): “Phùng Mậu khai mạng tiền. Hứa Nghiêm khai quân báo. Tôn Tứ khai vận chuyển. Không ai nhắc tên ngài. Ngài không phải người của mạng.”

| Tiêu chí | Kết quả |
|---|---|
| Thông tin riêng từng lời khai | Giữ: ba người, ba lĩnh vực (tiền / quân báo / vận chuyển), cùng kết quả "không nhắc tên Cố". Bản gốc cũng không có thông tin khác giữa ba câu. |
| Khác biệt có nghĩa | Chỉ một: với Phùng Mậu bản gốc nói "Ngài không nằm trong đó", với hai người kia nói "Không có tên ngài". Hai nghĩa gần nhau; nghĩa mạnh hơn được câu "Ngài không phải người của mạng" bao lại. Không mất nghĩa. |
| Tri thức người nói | Hoài Xuyên nêu các lời khai đã có trước cảnh: Phùng Mậu (ep8:~2340–2400), Hứa Nghiêm (ep8:~1740–1800), Tôn Tứ (ep8:~2220–2300). Đúng trình tự thời gian. |
| Tiến trình chứng cứ | Mạch giữ nguyên: Hàn Dực (lời khai ép) → Tấn Ký (bị mua), phản ứng đổi sắc của Cố → "không đáp" → loại trừ Cố khỏi mạng → định nghĩa "người tin chứng cứ do mạng tạo ra". |
| Nhịp | Bản gốc có ba lần "Cố Văn Lâm không nói gì" như ba nhịp suy sụp. Giờ còn một nhịp "không đáp" (ep8:2579) trước lượt dài, rồi "Cố Văn Lâm nhìn hắn". Mất độ lặp có chủ ý, nhưng đây chính là kiểu thẻ lặp cơ học mà pass nhắm tới. MINOR-2 (tùy chọn, về nhịp cảm xúc). |
| Vấn đề có sẵn, không do N2B | "Tôn Tứ khai vận chuyển": Tôn Tứ ở kho cá chỉ khai rời rạc (phiếu, bốn hiệu, "ta giữ hắn") và đòi thương lượng; không có cảnh nào ghi lời khai về vận chuyển. Bản gốc cũng viết như vậy; N2B giữ nguyên. Không phải lỗi N2B. Ghi để tham khảo (MINOR-3). |

### 2.3 Các cắt khác (S3, S4, S6, S7) — **PASS**

| Cắt | Kiểm tra |
|---|---|
| S3 "Ngài nhìn thấy?/Ừ." (ep8:1671) | Lặp đoạn người kể ngay trước (Hoài Xuyên thấy nét móc). Dòng còn lại “Cùng nét?” / “Có thể.” / “Trên hồ sơ hiện tại?” / “Ừ.” vẫn nối trôi chảy. |
| S4 "PM-6 là hắn thật/Ừ." (ep8:2101) | Liên hệ PM-6 = Phùng Mậu đã được lập ở cảnh Giang Châu (quản sự: người mở tài khoản là Phùng Mậu) và bằng câu “Phùng Mậu.” của Hoài Xuyên ngay trước. Thẻ người nói “Chiêu Ninh nói:” gắn trực tiếp vào lượt còn lại; người nói rõ. |
| S6 "Nhưng rất nhiều người đeo/Con biết" (ep8:2865) | Lần thứ ba cùng kết luận; phần hai lần trước nằm trong cảnh "Nhẫn ngọc đen" (nhân vật tự dừng, “Không chạy theo nhẫn”). Xem MINOR-5. |
| S7 "Lần này, một chữ ký chặn…" (ep8:3229) | Đối lập "kiếp trước đưa lên / lần này chặn" đã trọn ở ep8:~3170 (góc nhìn Chiêu Ninh). Phần còn lại là nội tâm Hoài Xuyên (ba năm trước để nó nằm im, "không coi đó là chuộc tội"), tự đứng được. |

---

## 3. Character / relationship integrity

- **Chiêu Ninh–Hoài Xuyên:** các nhịp quan hệ chính (Chiêu Ninh tự chọn ở lại; "Lần này ta đi"–"Ừ"; "Ngài ra lệnh?–Ta không nghe"; ký tờ niêm phong; "Cô thất vọng?–Chưa xong") không bị chạm. PASS.
- **Chiêu Ninh–Thẩm Tĩnh An:** cảnh nhẫn ngọc đen mất lượt “Nhưng rất nhiều người đeo.” / “Con biết.” Đây là nhịp cha cẩn trọng + con đã học cách cẩn trọng. Nhịp con đã học vẫn hiện ở “Không chạy theo nhẫn” (ep8:~2795). Phần cha chỉ còn xác nhận “Có đeo nhẫn.” Xem MINOR-5. Không đổi quan hệ.
- **Cố Văn Lâm:** động cơ ("tin mình đúng", tin chứng cứ do mạng tạo) và tri thức (biết trang bị thay, không nhận tiền, không bị gán là biết mạng) nguyên vẹn.
- **Tôn Tứ, Phùng Mậu, Hứa Nghiêm, Tề Phương, Trần Quảng, Chu Tử Dung, Mạnh Thành:** lời thoại và hành động không bị đổi trong các cắt N2B. PASS.
- **Thẻ "không nói gì":** ba thẻ bị đổi/bỏ đều thuộc phản ứng phụ; các thẻ mang hài hoặc cảm xúc (ep8:479, 699, 861, 951, 1517 …) được giữ. PASS.

---

## 4. Setup / payoff integrity

### 4.1 "trên bảng" (ep8:1501) — **MINOR-4** (hợp lệ, không phải chi tiết bịa)

- Câu sửa: “Chiêu Ninh nhìn ba nút rõ hơn **trên bảng**.”
- Trước N2B, "bảng" xuất hiện đúng hai lần: lượt C41 (đã bỏ) và “bảng cuối cùng ghi” (ep8:2599). Sau khi bỏ C41, ep8:2599 sẽ mất tiền đề, nên N2B thêm "trên bảng" ở ep8:1501.
- Đây là làm rõ liên tục **cục bộ**: không thêm sự kiện, không thêm thông tin, chỉ gọi tên vật đã có (tờ chia bốn phần ở ep8:137; sổ bốn ô ở ep7:1963). Không bịa canon.
- Hạn chế nhỏ: "bảng" lần đầu xuất hiện ở ep8:1501 như một vật mới, không gọi lại đúng "giấy chia bốn phần" ở ep8:137; có thể lệch từ ngữ (giấy → bảng). Không có hậu quả logic. Tùy chọn: để nguyên.

### 4.2 Các setup/payoff khác — **PASS**

| Chuỗi | Trạng thái |
|---|---|
| Nét móc: ep8:1–93 → Hình bộ → mẫu so sánh → Tề Phương | Nguyên vẹn. Cảnh "Hoặc thư lại dưới hắn" (ep8:~1675) vẫn dẫn tới Tề Phương. |
| "hợp thức hóa" | ep8:1739 giữ chữ; sổ "Hợp thức hóa, không phải toàn bộ là đồng phạm" giữ (ep8:~3203). Mất phần liệt kê bốn vai ngay trước (xem 5, mục 4 luận đề). |
| "Nhưng hắn là cửa" ↔ ep7 "cùng một cửa" (AD-N2-08b) | Nguyên văn. |
| Nhẫn ngọc đen (Phùng Mậu → Hàn Dực → Tĩnh An → Bùi Tấn) | Nguyên vẹn. |
| "chạy": ep6 "Mai có chạy không?" → ep8 "Có phải chạy chưa?" | Giữ. Câu giải thích cuối bị bỏ, xem 7. |
| Chữ ký: kiếp trước (đưa chứng cứ lên) / lần này (chặn) / ba năm trước (để nằm im) | Ba lớp còn đủ; lớp "lần này" nằm ở phía Chiêu Ninh. |
| Lạc Thủy: bản đối chiếu, "Lạc Thủy qua mùa nước tháng Tám. Đê không vỡ." (ep9:859) | Không chạm. |

---

## 5. Mystery / knowledge integrity

- Không câu nào thêm danh tính, động cơ, chứng cứ hay sự kiện (đã đối chiếu từng mẩu diff).
- Ranh giới bí ẩn giữ nguyên: người trói Hàn Dực, áo nâu, người đốt xe, hộp trong Binh bộ, "người của phủ", "người khởi đầu có thể đã chết" — không bị gán danh tính hay giải thích mới. Bảng cuối với Tôn Tứ (AD-N2-02b) nguyên văn.
- Nhẫn ngọc đen sau khi bỏ lượt “Nhưng rất nhiều người đeo” (MINOR-5): giữa ep8:2865 và cảnh bắt Bùi Tấn không còn lời "dè dặt" nào của nhân vật. Hai lần dè dặt còn lại (ep8:~2790–2795) đủ để người nghe không đọc nhẫn là chứng cứ chắc. Không đổi ranh giới bí ẩn.
- Tri thức nhân vật: Chiêu Ninh "Ta chết" / "Cô nói như đã thấy" (Bùi Tấn) nguyên vẹn; Hoài Xuyên không nhớ kiếp trước (ep7 không chạm); Cố Văn Lâm không biết mạng.

---

## 6. Audio review

| # | Thay đổi | Kết quả | Ghi chú |
|---|---|---|---|
| 1 | ep8:869 "Cùng tối ấy, ở Binh bộ…" → "Ở Binh bộ, … ngay trong đêm." | **PASS** | Thời gian rõ nhờ "ngay trong đêm". Hơi nặng ("nhận … ngay trong đêm") nhưng không cơ học. |
| 2 | ep8:1747 "Cùng đêm ấy, trên sông Nam…" → "Trên sông Nam, … trong đêm." | **PASS** | Cảnh liền trước là đêm ở Thẩm phủ; tiếp nối rõ. |
| 3 | ep8:2113 "Cùng đêm ấy, trên Nam lộ, Phùng Mậu trên thuyền…" → "Trên Nam lộ, Phùng Mậu nhận được tin…" | **MINOR-6** | Mất cả mốc "đêm" lẫn "trên thuyền". Cảnh liền trước kết bằng "Đêm đó, hắn gửi một phiếu khẩn", nên liên tục vẫn đọc được; người chèo ở dòng sau xác nhận thuyền. Nghe mơ hồ nhẹ về thời điểm. |
| 4 | ep5:1381 "Ở Binh bộ, Trần Quảng ngồi một mình." | **MINOR-6** | Liền sau cảnh đêm của Chiêu Ninh; mất "cùng lúc" nên giao nhau thời gian giảm. Không có hậu quả thông tin. |
| 5 | ep6:1873 "Ở Binh bộ, Chu Tử Dung ngồi một mình." | **PASS** | Liền ngay sau "Cùng đêm ấy" ở ep6:1847; bỏ lần lặp là đúng mục đích. |
| 6 | ep9:325 "Trong phủ Nhị hoàng tử, Nhị hoàng tử nhận tin Bùi Tấn khai." | **PASS** | "nhận tin Bùi Tấn khai" tự mang mốc thời gian. Hơi lặp "Nhị hoàng tử … Nhị hoàng tử", đã có từ bản gốc. |
| 7 | ep8:1091 "Hắn bị thương" → "Tôn Tứ bị thương." | **PASS** | Gỡ đại từ mơ hồ (hai người nam trong đoạn). |
| 8 | ep8:1217 "Chiêu Ninh không nói gì." → "Chiêu Ninh cầm đũa lên." | **MINOR-7** | Thêm một hành động sân khấu nhỏ. Hợp với "Ăn cơm trước" nhưng cảnh được mở bằng "Đêm ở Thẩm phủ, Chiêu Ninh kể cha" chưa nói rõ đang ăn. Không thêm thông tin. |
| 9 | ep8:2001 bỏ thẻ sau “Ta đứng về phía kế hoạch đỡ ngu.” | **PASS** | Cảnh kết ở câu của cha, tự nhiên, không mơ hồ người nói. |
| 10 | ep8:3183 bỏ thẻ sau “Vậy ăn thêm một bát cơm.” | **PASS** | Tử Khiêm có thẻ người nói riêng ở lượt kế. |

Không có chỗ nào trở nên cơ học hơn. Hai chỗ đáng cân nhắc nhất là mục 3 và 4 (MINOR-6).

---

## 7. Ending review

### 7.1 ep8 kết ở “Chưa.” — **PASS** (kèm MINOR-8)

Nội dung kết hiện tại: dậy sớm, sổ cũ, "Ngày hôm nay đã đi qua. Không có lính. Không có lệnh bắt. Không có cửa bị phá. Nàng không gạch dòng cũ. Chỉ khép lại." — A Lục mơ màng “Có phải chạy chưa?” — “Chưa.”

| Câu hỏi | Kết quả |
|---|---|
| Có động cơ tự nhiên từ cảnh trước? | Có. Ba câu "Không có lính / lệnh bắt / cửa bị phá" đã nêu lý do để "chưa phải chạy". |
| Giữ chức năng cảm xúc? | Có. Chuyển từ nhịp chạy (ep6 "Mai có chạy không?" → "Chưa biết") sang nhịp sống qua được ngày, bằng hình ảnh sổ khép lại. Điểm cảm xúc "không còn biết trước" vẫn được ep9 mang tiếp ("Lần này nàng không cần biết"). |
| Có tạo cliffhanger giả? | Không. Các mạch lớn đều đã đóng ở ep8 (Bùi Tấn bị bắt, hồ sơ bị niêm). "Chưa xong" ở ep8:3209 (Hoài Xuyên) vẫn là dư vị có chủ ý. |
| Có tạo bí ẩn mới? | Không. Không câu nào gợi nguy hiểm cụ thể. |
| Có đột ngột? | Không. Kết bằng lời thoại ngắn khác hẳn nhịp "kết bằng người kể" ở ep5/6/7/9. Không thấy cụt. |

Ghi nhận thêm: câu cũ "chưa có gì để chạy" (khẳng định không sợ) thực ra **lệch** với ep9, nơi Chiêu Ninh sáng hôm sau vẫn nhìn cổng và canh ngày ("Hôm nay vẫn nằm trong chuỗi ngày…", ep9:~23). Ending mới khớp ep9 hơn.

**MINOR-8:** "Chưa." có thể nghe là "chưa đến lúc chạy" (còn hàm ý nguy hiểm sau) thay vì "không có gì để chạy". Độ mơ hồ này nhỏ và đúng với trạng thái ở ep9. Không cần sửa; ghi để tác giả cân.

### 7.2 Lặp mô-típ chữ ký và "viết khẩu hiệu → gạch" — **PASS**

- **Khẩu hiệu → gạch:** ở ep6 vẫn còn nguyên (ep6:~1905: “Nàng thấy dòng ấy cũng hơi giống khẩu hiệu. Nàng gạch.”). Bản ep8 chỉ lặp cùng thiết bị, không có tiến triển mới (cùng người, cùng ý, cùng hành động). Việc bỏ không mất thành phần cảm xúc riêng. N2A F3 ghi "khẩu hiệu bị gạch" là chi tiết riêng của một lần kết, thuộc nhóm "OPEN, biên tập nhịp" chứ không phải AD đã khóa. Phần thay thế “Việc còn lại, tách từng phần, xử từng người.” giữ nguyên chức năng hành động. Mất duy nhất tín hiệu "Chiêu Ninh vẫn giữ thói quen tự sửa kết luận quá sớm" lần thứ hai; thói quen ấy đã được lập ở ep6 và ep7 (“Nàng dừng. Không gạch.”).
- **Chữ ký:** xem 2.3 (S7). Lớp cảm xúc khác nhau (Chiêu Ninh nhìn kiếp trước / Hoài Xuyên tự trách) đều còn.

---

## 8. Deferred-item assessment

Không giải, không thêm giải thích.

| ID | Mục | Phân loại | Lý do |
|---|---|---|---|
| DF-1 | K7/D2/N4 có ba nghĩa (điểm rút, "nhóm phí", "nhóm quân/nguồn Doanh hai") | **SAFE TO LEAVE OPEN** | Văn bản tự đóng khung: “Để nhớ rằng chữ giống không có nghĩa cùng thứ” (ep8:~607) và “Tạ Hoài Xuyên không cố ép nghĩa mã nữa” (ep8:~1371). Ba nghĩa không mâu thuẫn trực tiếp (điểm rút có thể đồng thời là nhóm phí). Mạch chính (chọn Thẩm gia; Bùi Tấn nối các phần) không phụ thuộc vào việc chốt mã. Không nên giải thích thêm vì sẽ là canon mới. |
| DF-2 | Nguồn "hộp trong Binh bộ" đưa số cho Hứa Nghiêm | **SAFE TO LEAVE OPEN** | Hứa Nghiêm khai "Không biết", khớp AD-N2-02b (không gán danh tính cho nhân vật chưa rõ). Mạnh Thành khai cùng mảng nhưng không nối vào hộp. Không có điểm nào buộc người nghe hỏi lại. |
| DF-3 | Tam hoàng tử nói “Ta sẽ tra” Bùi Tấn có tìm người của ngài không; không có kết quả | **SAFE TO LEAVE OPEN** | Một lời hứa điều tra nhỏ trong cảnh chính trị phụ; không tạo bí ẩn. Mạch Bùi Tấn khép ở Bùi Tấn thừa nhận (ep8:~3000) và hồ sơ bị niêm. Ở ep9 Tam hoàng tử và Nhị hoàng tử xuất hiện lại nhưng không cần kết quả của "Ta sẽ tra". Nếu tác giả muốn khép, đó là lựa chọn tùy ý, không phải sửa chữa cần thiết. |

Không mục nào cần N2C.

---

## 9. Canon verification

| Khóa | Kết quả |
|---|---|
| AD-01 (vụ Thẩm chưa từng xảy ra trong dòng hiện tại) | PASS. Không câu nào quay lại xét lại/minh oan; ep8:3205–3229 (sổ, ký chặn) giữ cấu trúc phòng ngừa. |
| AD-02 (chỉ Chiêu Ninh nhớ kiếp trước) | PASS. “Ta chết”/“Cô nói như đã thấy” nguyên; Hoài Xuyên không nhớ. |
| AD-03 (Lạc Thủy không vỡ) | PASS. ep9:859 không chạm. |
| AD-04 (không Final Boss) | PASS. Bùi Tấn vẫn "mưu sĩ nối các phần"; Nhị hoàng tử "không chắc" nguyên. |
| AD-N2-01..11 | PASS. AD-N2-02b (bảng Tôn Tứ, ep8:2599) nguyên văn; AD-N2-08b ("cùng một cửa" ↔ "hắn là cửa") nguyên; AD-N2-11: hai điểm neo ep6 sc.49 và ep9 sc.6 nguyên, không câu giữa nào được khôi phục. Các câu N2B bỏ thêm đều là câu luận đề hoặc lặp, nằm trong "bỏ luận đề thừa" (xem mục 4 của `PASS_N2B_REPORT.md`). |
| EP7 Hoài Xuyên lock | PASS. `ep7.txt` không bị chạm. |
| EP8–EP9 cấu trúc phòng ngừa | PASS. Chặn hồ sơ Hạng bốn trước khi thành án; Hoàng thượng chuẩn tra làm giả quân báo. |
| Vụ Thẩm không xảy ra trong dòng hiện tại | PASS. |
| Lạc Thủy (hiệu ứng cánh bướm) | PASS (không chạm). |
| Ranh giới tri thức nhân vật | PASS (xem mục 5). |

Kiểm tra kỹ thuật: ngoặc “ ” cân (ep5 623/623, ep6 807/807, ep8 1350/1350, ep9 663/663); CRLF nguyên (LF=CR). Số ký tự khớp báo cáo N2B.

---

## 10. Findings by severity

**HIGH:** không có.
**MEDIUM:** không có.

**MINOR** (tất cả tùy chọn, không cần thiết cho phê duyệt):

| ID | Vị trí | Vấn đề | Ghi chú |
|---|---|---|---|
| MINOR-1 | ep8 (C41 bỏ) | Mất một nhịp nhỏ "Đúng." cùng đồng thuận "không ép Cố thành nút thứ tư". | Tinh thần còn trong hành động ở cảnh bẫy. |
| MINOR-2 | ep8:2581 | Gộp ba lượt thành một làm mất nhịp suy sụp ba lần của Cố. | Có chủ ý để giảm thẻ lặp; nhịp còn một "không đáp". |
| MINOR-3 | ep8:2581 (có sẵn) | "Tôn Tứ khai vận chuyển" khớp yếu với những gì Tôn Tứ thực sự khai. | **Không do N2B gây ra**; bản gốc đã vậy. |
| MINOR-4 | ep8:1501 | "trên bảng" lần đầu gọi vật "bảng" mới, lệch nhẹ so với "giấy chia bốn phần". | Làm rõ cục bộ hợp lệ, không bịa. |
| MINOR-5 | ep8:2865 | Cảnh cha–con về nhẫn mất lượt dè dặt của cha. | Hai lần dè dặt còn lại đủ giữ ranh giới. Mất phần liệt kê bốn vai ("người biến hồ sơ thành án") ở cảnh Cố liền trước; "hợp thức hóa" vẫn còn. |
| MINOR-6 | ep8:2113, ep5:1381 | Mất mốc "đêm"/"cùng lúc" nên giao nhau thời gian giảm. | Không đổi thông tin. |
| MINOR-7 | ep8:1217 | "cầm đũa lên" thêm hành động sân khấu nhỏ. | Hợp với "Ăn cơm trước". |
| MINOR-8 | ep8 kết | "Chưa." có thể nghe là "chưa đến lúc chạy". | Hợp trạng thái ở ep9. |

Phụ: câu "Chỉ là một người nhận tiền…" (ep8:1847) mất đối trọng "Không có đại âm mưu. Không lời thề." nên "Chỉ là" hơi thiếu vế đối. Vẫn đọc trôi, không đáng coi là phát hiện riêng.

Mọi phát hiện đều chưa sửa.

---

## 11. Recommended next step

- **N2B được duyệt:** N2B is structurally approved pending only optional micro-fixes, if any.
- Việc tiếp theo tùy tác giả. Có thể (a) bỏ qua toàn bộ MINOR, hoặc (b) gom vài micro-fix nhẹ nếu muốn: MINOR-6 (hai mốc thời gian), MINOR-4 (từ "bảng"). Cả hai đều chỉ đổi cách diễn đạt, không đổi thông tin.
- Ba mục DEFERRED nên **để mở**; không cần N2C cho chúng.
- Không cần mở lại AD-N2-01..11.

STOP: không sửa bản thảo, không N2C, không N3.
