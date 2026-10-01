# PASS N1A REPORT — TÀN CỤC (EP1–EP4: KỊCH BẢN → VĂN XUÔI TỰ SỰ)

**Phạm vi:** chỉ `EP1.txt`, `EP2.txt`, `EP3.txt`, `EP4.txt`. Không sửa EP5–EP9, Handbook, Bible, Protocol, báo cáo B1 hay tài liệu Pass A.

**Nguồn:** bản thảo hiện tại sau B1.5 (commit `ba4cc5a`). Mỗi tập được chuyển riêng, đối chiếu với bản kịch bản gốc giữ nguyên bên cạnh trong suốt quá trình.

**Quy trình mỗi tập:** đọc nguồn → chuyển → đọc lại như văn nghe → đối chiếu từng câu thoại với nguồn bằng script (mọi câu thoại trong ngoặc kép của nguồn phải xuất hiện trong bản chuyển) → kiểm mốc ngày → kiểm POV và người nói.

---

## 1. Conversion Decisions

| Thành phần kịch bản | Cách chuyển |
|---|---|
| Tiêu đề cảnh (`## CẢNH N — NỘI./NGOẠI. ĐỊA ĐIỂM — THỜI GIAN`) | Bỏ. Thông tin địa điểm/thời gian cần cho người nghe được đưa vào câu mở đầu đoạn (vd. "Ngày mười ba tháng Sáu, Chiêu Ninh ngồi trong xe ngựa đi qua phố Đông kinh thành."). Khi tiêu đề không mang thông tin mới, không thêm câu chuyển. |
| Cảnh `TIẾP` (liên tục cùng chỗ) | Nối liền trong cùng một mạch văn, không thêm dấu ngắt. Không có nội dung nào bị gộp hay lược. |
| Ngắt cảnh khi đổi thời gian/không gian/POV | Dùng `* * *` (dấu ngắt đoạn của văn xuôi, không đọc thành tiếng), kèm câu mở đầu có tín hiệu thời gian/nơi chốn. Số ngắt: EP1 15, EP2 16, EP3 19, EP4 14. |
| Nhãn người nói (`Chiêu Ninh:` / `Tạ Hoài Xuyên:`) | Bỏ. Thay bằng tag thoại tự nhiên ("Tử Khiêm nói", "hắn đáp") hoặc nhịp hành động, chỉ khi cần để người nghe biết ai nói. Trao đổi hai người qua lại nhanh giữ dạng câu ngắn không tag, như nguồn. |
| Dòng thoại im lặng `“…”` | Chuyển thành tường thuật hành vi tương đương: "không đáp", "cứng họng", "không nói nên lời", "chờ ông nói tiếp", "im lặng nhìn". Không thêm nội dung suy nghĩ. (EP1: 10, EP2: 7, EP3: 7, EP4: 12 chỗ.) |
| Nhiều dòng thoại liên tiếp của cùng một người | Gộp vào một đoạn thoại. Câu chữ giữ nguyên. |
| Dòng ghi chép/sổ tay in đậm (`**…**`) | Bỏ markdown in đậm. Giữ nguyên văn câu ghi, dẫn bằng tường thuật ("Nàng viết:", "Dưới đó:"). Các mục danh sách ngắn được nối thành một đoạn khi đọc to tự nhiên hơn. |
| Ký hiệu khó đọc thành tiếng | "chuyến 17" → "chuyến mười bảy"; "L17" → "L mười bảy"; "→" → dấu phẩy hoặc câu; "Hệ quả chưa biết: ?" → "Hệ quả chưa biết. Bên cạnh chỉ có một dấu hỏi."; ba cột "SỰ KIỆN CŨ / HIỆN TẠI / SAI LỆCH" → "Nàng kẻ ba cột trên giấy: sự kiện cũ, sự kiện hiện tại, sai lệch." |
| Khối metadata đầu tập (Thể loại / Tông / Mốc thời gian) | Bỏ (ghi chú sản xuất). Mốc thời gian được giữ trong văn bản: EP1 đã có sẵn ở sc.2; EP2–EP3 có ngày trong từng cảnh; EP4 chuyển "mùng chín tháng Bảy" từ metadata vào câu mở đầu. |
| `# TÀN CỤC` / `## TẬP N — TÊN TẬP` | Giữ làm tiêu đề tệp và tên tập. |
| `# HẾT TẬP N`, `---` | Bỏ. |
| Markdown bị escape ở EP2 (`\#`, `\*\*`, `\---`) | Bỏ toàn bộ. |
| Câu cụt nối nhau | Câu cụt mang nhịp căng, giọng nhân vật hoặc nhấn mạnh thì giữ (vd. "Không có ám sát. Không có tên bắn. Không có tiếng hét."). Các mảnh chỉ do định dạng kịch bản (mỗi dòng một mệnh đề) được nối thành câu/đoạn. |
| Mã hóa | UTF-8, CRLF như trước. |

**Nguyên tắc giữ thông tin:** không thêm suy nghĩ riêng, động cơ, foreshadowing hay chi tiết bối cảnh mới. Chi tiết không gian chỉ lấy từ nguồn. Mọi câu thoại được giữ nguyên chữ. Khác biệt duy nhất là dấu câu: dấu chấm cuối câu thành dấu phẩy khi có tag phía sau, như "“Có,” hắn nói.".

**Các chỉnh câu chữ cụ thể có ảnh hưởng tới cách hiểu (đều đã kiểm):**
- EP1 sc.1: "Chuyện giữa hai người này hắn không muốn nghe" (bước vào đầu viên lại mục) → "trông ông ta chẳng muốn nghe chút nào" (quan sát từ ngoài, giữ POV Chiêu Ninh).
- EP1 sc.11: "Trẻ hơn người nàng nhớ hơn một năm" (gượng, đã ghi trong B1 mục D) → "So với người trong trí nhớ của nàng, hắn bây giờ trẻ hơn một năm có lẻ." Giữ nghĩa "hơn một năm".
- EP4 sc.31: dòng in đậm "**Quân nhu Bắc lộ.**" ngay sau "Tạ Hoài Xuyên nhìn nàng." (trả lời câu "Gì?") được chuyển thành lời Hoài Xuyên nói ra. Nội dung không đổi; chỉ chọn dạng nói thay vì dạng hiển thị.
- EP4 sc.18: câu "Tam giác không phải ký hiệu riêng." và câu hỏi "Là dấu kiểm chuyến?" được gộp thành một lượt nói của Hoài Xuyên. Nguồn không ghi người nói câu thứ hai; ngữ cảnh (sai dịch đáp "Dạ.") cho thấy là Hoài Xuyên hỏi.

---

## 2. POV Approach

**Mặc định:** ngôi ba hạn tri, bám sát Chiêu Ninh ở mọi cảnh có nàng. Nội tâm chỉ dùng ở những chỗ kịch bản đã viết rõ suy nghĩ/ký ức của nàng (danh sách kiếp trước, các dòng "Kiếp trước…", "Nàng biết mình hỏi quá nhanh."). Không thêm dòng nội tâm mới nào.

**Các cảnh giữ POV trung tính/bên ngoài** (chỉ hành động, quan sát, lời nói; không vào đầu nhân vật):

| Tập | Cảnh nguồn | Nhân vật trong cảnh | Ghi chú |
|---|---|---|---|
| EP1 | sc.1 (phần viên lại mục) | Viên lại mục | Câu nội tâm của viên lại mục chuyển thành quan sát từ phía Chiêu Ninh ("Có lẽ…", "trông ông ta…"). |
| EP2 | sc.12 | Trần Quảng | Hoàn toàn bên ngoài. |
| EP2 | sc.20 | Lục Trầm | Bên ngoài. "Một chút bất lực" → "Giọng có chút bất lực" (thuộc tính giọng nói, không phải nội tâm). |
| EP2 | sc.21 | Tạ Hoài Xuyên | Bên ngoài. |
| EP3 | sc.3 | Tạ Hoài Xuyên | Bên ngoài. |
| EP3 | sc.10–11 | Tạ Hoài Xuyên, Từ Kính | Bên ngoài. Cử chỉ "Từ Kính khẽ siết tay" giữ nguyên, không giải thích. |
| EP3 | sc.18, sc.30 | Trần Quảng, Chu Tử Dung | Bên ngoài. |
| EP3 | sc.29 | Tạ Hoài Xuyên | Chỉ thể hiện qua ghi chép và gạch xóa, không có nội tâm. |
| EP4 | sc.16–17, sc.37–38 | Trần Quảng, Chu Tử Dung | Bên ngoài. Phát hiện "cùng một kiểu sửa" giữ ở mức quan sát như nguồn. |
| EP4 | sc.21–22 | Tạ Hoài Xuyên (trong kho, Chiêu Ninh ở ngoài) | Bên ngoài. Có tín hiệu "Cùng lúc ấy, bên trong kho…" để người nghe biết đã đổi chỗ. |
| EP4 | sc.40 | Thẩm Tĩnh An, Thẩm phu nhân | Bên ngoài. Câu "chưa từng đưa Chiêu Ninh xem" là thông tin có sẵn trong nguồn, giữ nguyên. |

Không có cảnh nào đổi POV giữa chừng trong một mạch liên tục.

---

## 3. Major Screenplay Elements Removed

Chỉ là thành phần định dạng và sản xuất. Không có nội dung truyện nào bị lược.

- Tiêu đề cảnh `## CẢNH N — …`: EP1 17, EP2 22, EP3 32, EP4 40.
- Nhãn `NỘI.` / `NGOẠI.`, `TIẾP`, `CÙNG LÚC`, `SAU ĐÓ` dạng nhãn (khi cần, được chuyển thành cụm từ trong câu).
- Nhãn `KIẾP TRƯỚC` trong tiêu đề EP1 sc.1. Người nghe nhận ra đó là kiếp trước qua nội dung cảnh và cảnh tỉnh dậy ngay sau, đúng như kịch bản vốn để lộ.
- Nhãn người nói đứng riêng dòng.
- Khối metadata đầu tập (Thể loại / Tông / Mốc thời gian).
- `# HẾT TẬP N`, dấu `---`.
- Markdown in đậm `**…**` và ký tự escape `\` ở EP2.

Kịch bản không có chỉ dẫn máy quay, góc máy hay SFX nào, nên không có gì để bỏ.

---

## 4. Canon Verification

Kiểm từng tập trước khi chuyển sang tập kế tiếp.

| Hạng mục | Kết quả | Cách kiểm |
|---|---|---|
| Thoại | Giữ đủ | Script đối chiếu toàn bộ câu thoại nguồn với bản chuyển: EP1 508, EP2 423, EP3 619, EP4 676 câu. Câu không khớp nguyên chữ chỉ do dấu phẩy thay dấu chấm trước tag, do gộp nhiều câu cùng người nói, hoặc do đổi "17" thành "mười bảy". Không có câu thoại nào mất. |
| Mốc ngày | Không đổi | Đối chiếu mọi biểu thức ngày tháng. Mọi ngày trong cảnh giữ nguyên: 11/6 LK23; 13, 15, 18, 19, 20, 23/6; kiếp trước 19/6 và 22/6; 27, 28/6; 1/7; 3/7. "Bốn tháng trước ngày Thẩm phủ bị niêm phong" và "Một năm bốn tháng trước ngày nàng chết" giữ nguyên (khớp mốc 17/10 LK23 đã khóa). Chỉ mất các khoảng thời gian trong metadata ("Mùng ba đến mùng tám tháng Bảy", "Mùng chín đến giữa tháng Bảy", "Cuối tháng Sáu đến đầu tháng Bảy"), là ghi chú sản xuất. EP4 "mùng chín" được chuyển vào văn bản. |
| Trình tự sự kiện | Không đổi | Thứ tự cảnh giữ nguyên ở cả bốn tập. Không gộp, xóa hay đảo cảnh. |
| Ai biết gì / biết bằng cách nào | Không đổi | Không thêm suy luận, nội tâm hay kênh tin. Các tín hiệu thời gian mới thêm đều chỉ dựa vào tiêu đề nguồn (xem mục 6, các điểm chuyển cảnh suy ra từ ngữ cảnh). |
| Phân biệt kiếp trước / kiếp này | Không đổi | Mọi dòng "Kiếp trước…" giữ nguyên ngữ cảnh ký ức của Chiêu Ninh. |
| Ký ức của Chiêu Ninh | Không đổi (AD-02) | Chỉ Chiêu Ninh mang ký ức kiếp trước. |
| Ký ức của Tạ Hoài Xuyên | Không đổi (AD-02, EP7 LOCK) | Hoài Xuyên không có ký ức nào. EP3 sc.23–24, sc.29 và EP4 sc.35 giữ đúng: hắn chỉ nghe chữ "kiếp trước", không hỏi, không kết luận ("Tin rằng mình biết trước" bị gạch; "Không biết chuyện cô nói"). |
| Án Thẩm gia ở kiếp này (AD-01) | Không đổi | EP1–EP4 không có án Thẩm gia nào hoàn tất ở kiếp này. Bản năm mục (EP4 sc.31–32) vẫn là tài liệu bị giữ, "không đủ để nộp". |
| Tây Uyển (AD-04) | Không đổi | Vụ Tây Uyển giữ nguyên: hai tầng, xe bị tráo, hung thủ chưa rõ, không quy về một chủ mưu. |
| Lạc Thủy (AD-03) | Không đổi | "Lạc Thủy vỡ đê" chỉ xuất hiện như ký ức kiếp trước (EP1 sc.6, sc.12). Câu R-02 đã sửa ở EP4 sc.10 ("sau này… có thể vỡ") giữ nguyên. |
| Cấu trúc án giả / chặn án EP8–EP9 | Không ảnh hưởng | EP1–EP4 chỉ gieo: bản đối chiếu bốn mục và năm mục, Trần Quảng ở Binh bộ, sửa số ở giữa dòng. Không thay đổi. |
| Quan hệ nhân vật | Không đổi | Không tăng hay giảm mức độ thân mật. Thoại Chiêu Ninh–Hoài Xuyên giữ nguyên câu. |
| Kết quả | Không đổi | Lục Trầm sống/mất tích; Trần Quảng sang Binh bộ; Tam hoàng tử bị thương, Từ Kính sống; Hàn Dực được tìm thấy; kho Tấn Ký bị niêm phong; Mã Tam biến mất; phong thư thứ ba "Lục Trầm". |
| Bí ẩn hoặc tuyến truyện mới | Không có | Không giải đáp bí ẩn nào: người gửi thư, người chết đưa sổ, người tráo xe, người lấy bản sao, nội dung phong thư thứ ba. |

**EP5–EP9:** không sửa (`git status` chỉ có `EP1.txt`–`EP4.txt` và báo cáo này).

---

## 5. Audio Readability Notes

Các điểm sau nên được xử lý ở lượt audio sau. N1A không xử lý vì cần đánh bóng nhịp sâu hơn mức chuyển đổi.

1. **Câu kể còn ngắn so với mức tham khảo.** Câu tường thuật trung bình (không tính thoại) khoảng 30 ký tự ở EP1, 26 ở EP2, 25 ở EP3, 24 ở EP4, thấp hơn mốc 50–60. Phần lớn do giọng gốc của truyện (câu cụt nhấn nhịp) và các mảnh căng thẳng đã được giữ có chủ đích. Kéo dài thêm sẽ phải viết lại câu, vượt phạm vi N1A.
2. **Chuỗi thoại hỏi–đáp dài không có tag.** Hai người qua lại bằng câu rất ngắn ("Ừ." / "Có." / "Chưa."). Người nghe có thể mất dấu ai đang nói nếu đoạn dài. Các chỗ nặng nhất:
   - EP2: Đại Lý Tự (Chiêu Ninh–Hoài Xuyên, sc.6–8).
   - EP3: sc.6–7 (sơ đồ ba điểm lạ); sc.20–21 (Mã Tam, ba người nói).
   - EP4: sc.6–10 (Tĩnh An kể chuyện Lạc Thủy); sc.24–28 (bốn sổ); sc.30–35 (Hoài Xuyên, bản năm mục).
3. **Danh sách sổ tay đọc to.** EP1 sc.6 (6 dòng ngày tháng), EP2 sc.11 (bảng ba cột), EP2 sc.22, EP3 sc.9, sc.28, EP4 sc.26, sc.39. Đã bỏ định dạng nhưng vẫn là liệt kê. Lượt audio có thể cần cách đọc riêng, như giọng khác hoặc khoảng ngừng.
4. **Câu thoại lặp có chủ đích** ("Khá tiện", "Có phải chạy không?", "Lại không biết", "Con cười? / Ra ngoài. / Cầm bát") được giữ nguyên vì là nhịp hài và tích lũy giọng nhân vật. Lượt audio nên kiểm tần suất khi nghe liền nhiều tập.
5. **Ký hiệu chữ–số:** "L mười bảy" (EP4) có thể cần cách đọc thống nhất với các tập sau.
6. **EP1 sc.1:** cảnh kiếp trước mở đầu không có nhãn "kiếp trước". Người nghe chỉ hiểu khi tới cảnh tỉnh dậy. Đây là cấu trúc gốc; lượt audio có thể cân nhắc tín hiệu âm thanh.

---

## 6. Deferred Issues

| # | Tập / cảnh | Vấn đề | Vì sao N1A không sửa | Lượt đề xuất |
|---|---|---|---|---|
| D-01 | EP1 sc.6 | "Kiếp trước Tử Khiêm chết đầu tiên", trong khi sc.1 nói cha chết trước anh một ngày (đã ghi trong B1 mục D/F). | Sửa sẽ đổi thông tin, không chỉ câu chữ. | B2 (canon/continuity) |
| D-02 | EP3 sc.19 | Tiêu đề nguồn chỉ ghi "TỐI". Bản chuyển dùng "Đến tối" (cùng ngày với sc.17–18). Suy ra từ sc.30 ("tập quân báo hôm qua", "tối qua") và lời Tử Khiêm "một ngày". | Cần một tín hiệu thời gian cho audio. Đã chọn cách diễn đạt ít cam kết nhất; nên được tác giả xác nhận. | Review N1A |
| D-03 | EP2 sc.20 | Cảnh Lục Trầm ở trạm nghỉ không ghi quan hệ thời gian với sc.19. Bản chuyển cố ý không dùng "cùng lúc ấy", chỉ ghi "đêm mưa nhỏ". Sc.21 giữ "Cũng đêm ấy" như nguồn ("CÙNG ĐÊM"). | Không suy diễn mốc thời gian. | Review N1A |
| D-04 | EP3 sc.20–21 | "Tử Khiêm hết cười" xuất hiện hai lần trong hai cảnh liền nhau. Lần hai chuyển thành "không cười nổi nữa", không đổi nghĩa. | Lặp gốc, giữ theo quy tắc lặp. | Nén (C) |
| D-05 | EP4 sc.24 | "Vì sao lúc chiều cha không nói?", trong khi cuộc nói chuyện ở thư phòng diễn ra buổi trưa (sc.3). | Mâu thuẫn nhỏ về thời điểm trong nguồn; sửa là đổi thông tin. | B2 |
| D-06 | EP4 sc.31–32 | Người nghe có thể thắc mắc bản năm mục có liên quan bản của Trịnh Hành không (đã ghi trong `B1_VERIFICATION_REPORT.md`). | Thuộc cấu trúc bí ẩn; không làm rõ trong N1A. | B2 |
| D-07 | EP3 sc.11 | Cử chỉ "Từ Kính khẽ siết tay" khi nghe tên Hàn Dực chưa được giải thích; Từ Kính vắng mặt sau EP3 (B1 mục C). | Setup/payoff, không thuộc chuyển đổi. | B2 |
| D-08 | EP3 sc.14 | Hoài Xuyên hỏi "Có tên Hàn Dực trong trí nhớ của cô không?". Chữ "trí nhớ" hơi sát với bí mật trọng sinh, dù hợp lý vì nàng đã nhiều lần nói "ta nhớ". | Giữ thoại gốc; không thay đổi luồng thông tin. | Review N1A / B2 |
| D-09 | EP3 sc.31 / EP4 sc.29 | Câu đùa "giết cả nhà ai" của Tử Khiêm được nhắc lại. Cố ý hay trùng? | Lặp có thể là tích lũy; giữ. | B2 |
| D-10 | EP4 sc.40 | Phong thư thứ ba "Lục Trầm" và câu "Năm đó ông giấu ta" của Thẩm phu nhân là setup mở. | Setup/payoff, không đụng. | B2 (theo dõi payoff) |
| D-11 | Toàn EP1–EP4 | Mật độ câu cụt và chuỗi thoại không tag (mục 5, điểm 1–2). | Cần đánh bóng audio sâu; ngoài phạm vi. | Audio pass |
| D-12 | Toàn EP1–EP4 | Các cơ hội nén đã ghi ở `PASS_B1_REPORT.md` mục E còn nguyên. | N1A không nén. | Nén (C) |

---

## 7. Length

Số liệu đo bằng script trên tệp thực tế.

| Tập | Ký tự thô trước | Ký tự thô sau | Nội dung không khoảng trắng trước* | Nội dung không khoảng trắng sau | Chênh lệch |
|---|---|---|---|---|---|
| EP1 | 34.410 | 33.176 | 25.107 | 25.567 | +460 (+1,8%) |
| EP2 | 23.565 | 20.300 | 15.001 | 15.557 | +556 (+3,7%) |
| EP3 | 28.573 | 27.087 | 20.158 | 20.814 | +656 (+3,3%) |
| EP4 | 28.279 | 26.415 | 19.693 | 20.273 | +580 (+2,9%) |
| **Tổng** | **114.827** | **106.978** | **79.959** | **82.211** | **+2.252 (+2,8%)** |

\* "Nội dung trước" đã loại tiêu đề, metadata, `---` và ký tự markdown, nhưng vẫn tính nhãn người nói (`Chiêu Ninh:`) vì đó là phần thân kịch bản.

- Ký tự thô giảm do bỏ xuống dòng, tiêu đề cảnh và nhãn.
- Nội dung chữ tăng nhẹ do thêm tag thoại và câu chuyển cảnh, thay cho nhãn người nói và tiêu đề đã bỏ.
- Không có cắt giảm hay mở rộng có chủ đích.

---

## Kiểm tra dừng N1A

1. EP1–EP4 đã là văn xuôi tự sự: không còn tiêu đề cảnh, nhãn `NỘI./NGOẠI.`, `TIẾP`, `HẾT TẬP`, nhãn người nói, markdown in đậm hay ký tự escape (đã quét bằng regex).
2. Không nén có chủ đích: số cảnh nguồn được giữ đủ trong mạch văn, mọi câu thoại còn nguyên, không lược beat.
3. Không tạo canon mới (mục 4).
4. EP5–EP9 không bị sửa.
5. Handbook, Bible, Protocol, `AUTHOR_DECISIONS.md`, các tài liệu Pass A và báo cáo B1 không bị sửa.
6. Dừng. Chưa chuyển sang N1B.
