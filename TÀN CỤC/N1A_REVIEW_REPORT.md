# N1A REVIEW REPORT — TÀN CỤC

**Phạm vi:** chỉ duyệt lại. Không sửa episode nào, chưa bắt đầu N1B.

**Nguồn đối chiếu:**
- Kịch bản gốc: commit `ba4cc5a`, bản sau B1.5 và trước N1A.
- Bản chuyển: commit `8d6f603`. Working tree sạch khi duyệt.

**Tiêu chí duy nhất:** bản chuyển có giữ đúng chất liệu nguồn không. Không đánh giá văn chương, không đề xuất câu hay hơn.

---

## 1. EP3 Review

**Chuyển đổi:** tiêu đề cảnh `## CẢNH 19 — NGOẠI. KHO CŨ PHÍA NAM THÀNH — TỐI` thành câu mở đoạn "Đến tối, Tử Khiêm đã tìm được Mã Tam ở một kho cũ phía Nam thành." (`EP3.txt:1003` bản chuyển).

**Vấn đề cần kiểm:** "Đến tối", đặt sau chuỗi cảnh buổi chiều, đọc thành *tối cùng ngày*. Tiêu đề nguồn chỉ ghi "TỐI". Câu hỏi là kịch bản có xác lập được đó là cùng ngày không.

**Bằng chứng trong kịch bản nguồn:**

1. **Chuỗi tiêu đề cảnh liên tục, không có mốc ngang ngày nào chen vào.**

   | Cảnh | Tiêu đề | Ngày |
   |---|---|---|
   | sc.10 | SÁNG HÔM SAU | D2 = 4/7 (sau ngày 3/7 ở sc.1–9) |
   | sc.12–15 | TRƯA / TIẾP | D2. sc.14: "Vì **hôm qua** cô nghe Từ Kính sống" xác nhận D2. |
   | sc.16 | CHIỀU | D2 |
   | sc.17 | SAU ĐÓ | D2 |
   | sc.18 | **CÙNG CHIỀU** | D2 |
   | sc.19 | **TỐI** | ? |
   | sc.20–21 | TIẾP | |
   | sc.22 | ĐÊM | |
   | sc.23–24 | TIẾP | |
   | sc.25 | NỬA ĐÊM | |
   | sc.28 | GẦN SÁNG | |
   | sc.29 | CÙNG LÚC | |
   | sc.30 | SÁNG | |

2. **Quy ước của chính bản thảo.** Khi sang ngày mới, kịch bản ghi rõ: EP3 sc.10 "SÁNG HÔM SAU"; EP4 sc.30 "SÁNG HÔM SAU". Ở EP3 sc.19 không có mốc như vậy. Một tiêu đề trần "TỐI" ngay sau "CÙNG CHIỀU" theo quy ước này là tối cùng ngày.

3. **Ràng buộc từ sc.30.**
   - Trần Quảng hỏi: "Tập quân báo **hôm qua** đâu?"
   - Câu trả lời: Chu Tử Dung lấy "**Tối qua**."
   - Tập ấy chính là tập Trần Quảng xem ở sc.18 (CÙNG CHIỀU, D2), khi Chu Tử Dung ghé phòng.
   - Từ sc.18 tới sc.30 chỉ có một đêm: ĐÊM → NỬA ĐÊM → GẦN SÁNG → SÁNG. Mọi cảnh sc.19–28 nằm trong khoảng tối D2 tới gần sáng D3.

4. **Ràng buộc từ sc.23.** Tin "Hàn Dực mất tích… Sau giờ Dậu" tới ngay trong đêm Chiêu Ninh mang thông tin về Mã Tam đến Đại Lý Tự (sc.22). Cuộc gặp Mã Tam (sc.19–21) phải diễn ra trước đó, trong cùng buổi tối.

5. **Lời Tử Khiêm ở sc.17** ("Nếu hắn chưa chạy khỏi kinh, một ngày.") là giới hạn trên. Tìm được trong buổi tối cùng ngày không mâu thuẫn với câu này.

**Kết luận: SUPPORTED.**

"Đến tối" chỉ nói ra điều mà chuỗi tiêu đề, quy ước ghi mốc ngày của bản thảo và ràng buộc "hôm qua / tối qua" ở sc.30 đã xác lập. Không có cách đọc nào của nguồn đặt sc.19 sang ngày khác mà không phá các ràng buộc trên. Không thêm thông tin mới, không đổi trình tự sự kiện hay luồng thông tin.

---

## 2. EP4 Review

**Chuyển đổi:**
- Nguồn EP4 sc.31, cuối cảnh: dòng `**Quân nhu Bắc lộ.**` đứng riêng, in đậm, không có ngoặc kép, ngay sau "Tạ Hoài Xuyên nhìn nàng."
- Bản chuyển (`EP4.txt:1353`): "Tạ Hoài Xuyên nhìn nàng. “Quân nhu Bắc lộ.”". Dòng này giờ là lời Hoài Xuyên nói ra.

**Bằng chứng trong kịch bản nguồn:**

1. **Bản thảo dùng hai định dạng tách bạch.** Đã quét mọi dòng in đậm trong EP1–EP4 nguồn, khoảng 110 dòng, không tính metadata. Không dòng nào là lời thoại. Thoại luôn nằm trong ngoặc kép. Dòng in đậm có hai cách dùng:
   - **Chữ viết trên giấy hoặc vật:** sổ tay, thư, công văn, nhãn hộp, dấu trên gỗ. Ví dụ: EP1 sc.5 "**Lạc Thủy.**" trên hộp; EP4 sc.9 lá thư; EP4 sc.17 "**Bắc Lộ — doanh Trấn Viễn.**"; EP4 sc.22 "**L17.**"; EP4 sc.26 danh sách bốn mục.
   - **Từ khóa được nhấn trong khoảnh khắc nhận ra:** EP3 sc.9 "Tên— Nàng nhắm mắt cố nhớ. **Từ Kính.**" và "Nàng nhớ tên. **Hàn Dực.**".

   Không có tiền lệ nào dùng in đậm cho lời nói.

2. **Kịch bản để ngỏ cách thông tin được truyền đạt.** Trong cảnh, cả hai cách đọc đều có chỗ dựa:
   - **Đọc là văn bản:** ngay trước đó, "Tạ Hoài Xuyên kéo một hồ sơ ra." Bản năm mục vẫn nằm trong hộp của Đại Lý Tự (sc.34; EP7 "Để bản năm mục nằm trong hộp").
   - **Đọc là lời nói:** mấy dòng trước, Hoài Xuyên vừa từ chối "Cho ta xem." / "Không." (về sổ ghi nhận đơn nặc danh). Đoạn "Bốn con số / Bản sau có năm / Có thêm một mục" đều là lời nói.

   Nguồn không chọn một trong hai. Nó dùng định dạng *không phải thoại*.

3. **Điều không thay đổi:** nội dung Chiêu Ninh biết (mục thứ năm là "Quân nhu Bắc lộ"), nguồn tin (Hoài Xuyên, tại thời điểm này) và hệ quả ở sc.32 trở đi đều giống nhau ở cả hai cách đọc. Các tập sau (EP7 `ep7.txt:281, 325, 359, 3713`) không phụ thuộc vào việc dòng này được nói hay được cho xem.

**Kết luận: UNSUPPORTED.**

Đây không phải chuyển đổi định dạng trung thành. Nguồn cố ý không đặt dòng này trong ngoặc kép, và trong toàn bộ EP1–EP4 định dạng in đậm không bao giờ là lời nói. Đổi thành thoại của Hoài Xuyên là chọn một cách đọc mà nguồn để ngỏ. Điều này trái với nguyên tắc của N1A: "nếu kịch bản để điều gì không chắc, văn xuôi cũng để không chắc" và "chọn cách thể hiện đưa vào ít thông tin mới nhất".

**Mức độ:** THẤP. Luồng thông tin, canon (AD-01..04) và kết quả không đổi. Chỉ cách truyền đạt bị cam kết thay cho nguồn.

**Sửa nhỏ nhất (chỉ nêu yêu cầu, không đề xuất câu chữ mới):** tại `EP4.txt:1353`, bỏ ngoặc kép để "Quân nhu Bắc lộ." trở lại dạng một dòng đứng riêng sau "Tạ Hoài Xuyên nhìn nàng.". Không gắn động từ nói hay hành động đưa giấy. Như vậy văn bản giữ đúng mức để ngỏ của nguồn. N1A đã bỏ toàn bộ in đậm, nên dòng không ngoặc kép, đứng riêng là cách tương đương gần nhất.

---

## 3. EP1 Review

**Chuyển đổi:**
- Nguồn EP1 sc.11: "Trẻ hơn người nàng nhớ hơn một năm." (nguồn dòng 1358, ngay sau "Tạ Hoài Xuyên tới.").
- Bản chuyển (`EP1.txt:783`): "So với người trong trí nhớ của nàng, hắn bây giờ trẻ hơn một năm có lẻ."

**Kiểm từng thành phần nghĩa:**

| Thành phần | Nguồn | Bản chuyển | Đánh giá |
|---|---|---|---|
| Chủ thể | (ngầm) Tạ Hoài Xuyên | "hắn" | Giữ đúng. |
| Mốc so sánh | "người nàng nhớ" | "người trong trí nhớ của nàng" | Đồng nghĩa. |
| Thời điểm | (ngầm) lúc này | "bây giờ" | Chỉ làm rõ điều ngầm có trong ngữ cảnh. Không thêm thông tin. |
| Khoảng chênh | "hơn một năm" | "một năm có lẻ" | "Có lẻ" nghĩa là "hơn một chút so với số chẵn". "Một năm có lẻ" là hơn một năm. Nghĩa trùng. |

**Đối chiếu canon:**
- EP1 sc.2: "Một năm bốn tháng trước ngày nàng chết".
- Mốc khóa: Thẩm phủ bị niêm phong 17/10 LK23, Chiêu Ninh chết cuối thu LK24 (`PASS_B1_REPORT.md` A.1).
- Hình ảnh Hoài Xuyên "nàng nhớ" là lần gặp cuối ở phòng giam, cuối thu LK24 (EP1 sc.1).
- Khoảng cách tới 11/6 LK23 là khoảng một năm bốn tháng. Cả "hơn một năm" và "một năm có lẻ" đều đúng với khoảng này. Cách viết mới không thu hẹp hay mở rộng khoảng thời gian theo hướng mâu thuẫn canon.

Câu tiếp theo ("Không có quầng thâm dưới mắt. Không có vẻ mệt mỏi của người vừa đi qua một vụ án diệt môn.") giữ nguyên chữ.

**Kết luận: SUPPORTED.** Nghĩa và thông tin không đổi.

---

## 4. N1A Closure Recommendation

| Mục | Kết luận | Mức độ |
|---|---|---|
| A. EP3 "TỐI" → "Đến tối" | SUPPORTED | — |
| B. EP4 "Quân nhu Bắc lộ" → lời Hoài Xuyên nói | **UNSUPPORTED** | THẤP |
| C. EP1 "hơn một năm" → "một năm có lẻ" | SUPPORTED | — |

## N1A NEEDS REVISION

**Lý do:** mục B là một chuyển đổi không trung thành với định dạng nguồn. Tuy ảnh hưởng thấp, N1A là lượt chuyển đổi bảo thủ, nên một chỗ chọn cách đọc thay cho nguồn vẫn phải được trả về đúng mức để ngỏ ban đầu.

**Phạm vi sửa đề xuất (rất hẹp):**
- Một dòng duy nhất: `EP4.txt:1353`. Bỏ ngoặc kép, không thêm động từ nói hay hành động, như mô tả ở mục 2.
- Không đụng EP1, EP2, EP3. Không thay đổi phần nào khác của EP4.

**Sau khi sửa dòng này, N1A đủ điều kiện APPROVED.** Ngoài ra, nếu tác giả xác nhận rằng Hoài Xuyên *nói* ra mục này là đúng ý đồ, N1A có thể được duyệt ngay mà không cần sửa. Đó là quyết định của tác giả, không phải của lượt duyệt này.

**Xác nhận lượt duyệt:**
1. Không episode nào bị sửa.
2. Chưa bắt đầu N1B.
3. Không chỉnh audio, cấu trúc hay nén.
4. Chỉ tạo `N1A_REVIEW_REPORT.md`.
