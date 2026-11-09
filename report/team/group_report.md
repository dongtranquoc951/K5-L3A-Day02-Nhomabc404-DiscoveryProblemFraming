# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: Nhomabc404
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Người được hỏi phải giải thích lại cùng một câu hỏi cho đồng nghiệp, bạn học, khoảng 2 lần/tuần và khoảng 15–30 phút mỗi lần (survey 10 người, ước lượng từ khoảng giá trị).
- Quyết định cuối: **Go, phạm vi nhỏ** (pilot FAQ, mức No AI).

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Nguyễn Quang Đạo | Kiểm tra các điều khoản bất lợi trong hợp đồng dịch vụ so với quy định chuẩn của công ty | Nhân viên pháp chế, Trưởng phòng kinh doanh | Đọc dò từng dòng trong 30–40 trang và chép lại các điểm bất lợi (240–300 phút/hợp đồng) | Nhóm không có hợp đồng thật dài 30–40 trang và không có luật sư nội bộ để kiểm chứng ngay trong buổi lab thì đo baseline thế nào? (Trần Quốc Đông) |
| 2 | Nguyễn Quang Đạo | Đọc hiểu và phân loại tin nhắn/email phàn nàn của khách hàng để chuyển đúng người | Nhân viên trực hỗ trợ, Trưởng nhóm CSKH | Đọc hiểu tin nhắn ngắn/cụt ngủn và đoán bộ phận xử lý (10–15 phút/tin, ~20% chuyển nhầm) | Nếu khách nhắn quá ngắn hoặc không dấu thì bộ lọc từ khóa (Rule) có giải quyết được 70–80% trước khi dùng AI không? (Nguyễn Văn Ngọc Sơn) |
| 3 | Nguyễn Quang Đạo | Kiểm tra định dạng và hạn nộp bài tập của sinh viên trước khi khóa cổng nộp bài | Trợ giảng (TA), Giảng viên | Tải và mở từng file của 60–80 sinh viên để kiểm tra tên file và lỗi hỏng trang (135–150 phút/lớp) | Cụm "kiểm tra định dạng" có thể giải quyết hoàn toàn bằng script đối chiếu tên file trên Google Drive (Rule) mà không cần AI phải không? (Hồ Sỹ Tùng) |
| 4 | Đỗ Cao Cường | Chọn món và đặt cơm trưa trên Grab trong giờ nghỉ ngắn: khi xong việc lúc 12h mà giờ nghỉ chỉ có ít phút, muốn có cơm đúng lúc để kịp ăn và quay lại làm việc | Nhân viên văn phòng có giờ nghỉ trưa ngắn | Đặt sau 12h vì trong giờ làm không để ý tới việc đặt, nên 30–45 phút chọn và chờ giao rơi vào giờ nghỉ (ước lượng) | Trong 30–45 phút đó phần chờ giao chiếm 15–30 phút, vậy chỉ cần đặt báo thức lúc 11h20 để đặt sớm (No AI) là giải quyết triệt để đúng không? (Trần Đức Mạnh) |
| 5 | Đỗ Cao Cường | Giải thích lại cùng một câu hỏi cho đồng nghiệp, bạn học: muốn có sẵn chỗ để họ tự tra, không phải giải thích lại từ đầu | Người được hỏi (kỹ sư, trưởng nhóm, sinh viên), đồng nghiệp và bạn học | Giải thích lại từ đầu, khoảng 30 phút–1 giờ/lần, 1–2 lần/tuần (ước lượng ban đầu; sau survey hiệu chỉnh về phổ biến 15–30 phút/lần) | Phần tốn 30–60 phút là do phải tìm lại câu trả lời cũ hay do phải ngồi giải thích lại từ đầu, và các câu hỏi có đủ giống nhau để viết sẵn 1 chỗ (FAQ) không? (Nguyễn Quang Đạo, Trần Đức Mạnh) |
| 6 | Đỗ Cao Cường | Sắp xếp ưu tiên công việc mỗi sáng: muốn biết ngay việc nào làm trước, không mất thời gian sắp xếp lại | Người đi làm tự sắp xếp công việc | Khoảng 15 phút mỗi sáng, 4–5 ngày/tuần để gom việc và cân nhắc thứ tự ưu tiên (ước lượng) | Nếu chốt sẵn 3 việc quan trọng nhất từ cuối chiều hôm trước vào 1 to-do list duy nhất thì buổi sáng có còn mất 15 phút nữa không? (Hồ Sỹ Tùng) |
| 7 | Hồ Sỹ Tùng | Tìm kiếm ảnh chụp màn hình theo nội dung trong điện thoại | Học sinh, sinh viên, nhân viên văn phòng hay lưu screenshot | Lướt tìm thủ công qua hàng trăm ảnh và mở từng ảnh kiểm tra (8–10 phút/lần) | "Tìm kiếm theo nội dung" là tên tính năng (solution); hơn nữa iOS và Google Photos đã có sẵn OCR tìm chữ trong ảnh thì còn khoảng trống nào chưa giải? (Nguyễn Quang Đạo) |
| 8 | Hồ Sỹ Tùng | Tổng hợp công việc và deadline từ nhiều ứng dụng khác nhau | Sinh viên, nhân viên làm việc trên nhiều ứng dụng (Gmail, Slack, Discord) | Mở từng ứng dụng kiểm tra và chép tay các task/deadline vào chung một danh sách (20–25 phút/ngày) | Công việc và deadline đang nằm ở những ứng dụng nào, mỗi lần gom mất bao nhiêu phút, và vì sao đây khác với sắp xếp ưu tiên mỗi sáng (#6)? (Đỗ Cao Cường, Trần Quốc Đông) |
| 9 | Hồ Sỹ Tùng | Tổng hợp ưu và nhược điểm sản phẩm từ nhiều đánh giá online | Người thường xuyên mua sắm trực tuyến | Đọc hàng chục bình luận trên nhiều nền tảng và tự so sánh ưu/nhược điểm (30–35 phút/sản phẩm) | Các sàn TMĐT lớn hiện đã có mục tóm tắt đánh giá tự động và bộ lọc theo số sao/hình ảnh, người mua có thực sự cần thêm công cụ riêng không? (Trần Quốc Đông) |
| 10 | Trần Quốc Đông | Khiếu nại sản phẩm không đúng mô tả được xử lý chậm | Người mua hàng trực tuyến, Nhân viên CSKH | Nhân viên đọc nội dung, đối chiếu hình ảnh với mô tả sản phẩm và phân loại thủ công (~10 phút/khiếu nại) | Nguyên nhân chính khiến khiếu nại xử lý chậm nằm ở bước nhân viên phân loại thủ công hay do phải chờ phía người bán xác minh và phê duyệt hoàn tiền? (Đỗ Cao Cường) |
| 11 | Trần Quốc Đông | Người mua khó nhận biết đánh giá giả | Người mua hàng trực tuyến, người bán uy tín | Đọc và đối chiếu nhiều bình luận, hình ảnh, video để tự phán đoán độ tin cậy (15–20 phút/sản phẩm) | Người mua bên ngoài sàn không có dữ liệu log tài khoản hay lịch sử giao dịch thật thì lấy dữ liệu đầu vào ở đâu để xác minh đánh giá giả? (Nguyễn Văn Ngọc Sơn) |
| 12 | Trần Quốc Đông | Người mua mất nhiều thời gian so sánh sản phẩm | Người mua hàng trực tuyến | Mở nhiều trang web để đọc thông số, giá cả, bảo hành và đối chiếu thủ công (30–60 phút/lần chọn mua) | Với các sản phẩm tiêu dùng phổ thông, bảng so sánh thông số và bộ lọc giá có sẵn trên web đã đủ giải quyết chưa? (Hồ Sỹ Tùng) |
| 13 | Trần Đức Mạnh | Quản lý và đối soát xe ra vào bãi xe giờ cao điểm | Nhân viên bảo vệ trực chốt soát vé, người gửi xe | Bảo vệ nhìn mắt thường đối chiếu biển số và gõ tay lại khi thẻ từ bị mờ/lỗi (30–60 giây/xe, gây ùn ứ 10–15 phút giờ cao điểm) | Có thực sự cần đưa Computer Vision vào nhận diện biển số không, hay chỉ cần thay thẻ mờ và phân làn xe hợp lý (No AI / Rule) là hết ùn tắc? (Trần Quốc Đông) |
| 14 | Trần Đức Mạnh | Tự động hóa tiếp nhận và điều phối lịch hẹn phòng khám | Nhân viên lễ tân phòng khám/spa, khách hàng đặt lịch | Lễ tân tra cứu sổ lịch thủ công, nhắn qua lại (5–10 phút/khách) và gọi điện nhắc lịch cuối ngày (1–2 giờ/ngày) | Nếu gửi link đặt lịch cố định (như Calendly/Google Calendar) kèm tin nhắn nhắc tự động theo giờ thì đã giải quyết được bao nhiêu phần trăm? (Đỗ Cao Cường) |
| 15 | Trần Đức Mạnh | Tóm tắt và trích xuất phương pháp/dataset từ paper PDF | Sinh viên năm cuối làm đồ án, học viên cao học | Cuộn tìm phần Experiment/Method trong 20–30 paper và gõ tay phương pháp, dataset, metric vào bảng Excel (45–60 phút/paper) | Rủi ro mô hình trích xuất sai số liệu từ bảng biểu phức tạp rất cao, làm sao sinh viên tin tưởng mà không phải đọc lại toàn bộ bài báo? (Nguyễn Quang Đạo, Nguyễn Văn Ngọc Sơn) |
| 16 | Nguyễn Văn Ngọc Sơn | Khi chỉnh sửa prompt của tính năng sinh câu trả lời tự động, muốn nhận ra những câu hỏi trước đây trả lời đúng nhưng bản mới lại trả lời sai, để tránh đưa lỗi vào phiên bản tiếp theo | AI Engineer, QA, nhóm sản phẩm | Đọc và chấm thủ công 20 output sau mỗi lần sửa prompt (27/62 phút mỗi lần, 2 lần/tuần) | Kiểm thử hồi quy prompt đã có các công cụ eval sẵn (như promptfoo, LangSmith); nếu viết rõ rubric pass/fail và dùng công cụ đó thì phần việc còn lại có còn đủ đau không? (Nguyễn Quang Đạo) |
| 17 | Nguyễn Văn Ngọc Sơn | Khi job huấn luyện hoặc tinh chỉnh mô hình thất bại, muốn xác định bước lỗi và nguyên nhân cụ thể, để hạn chế các lần chạy lại không cần thiết | AI Engineer theo dõi fine-tuning, kỹ sư hạ tầng | Mở log dài để dò tìm dòng/bước gây lỗi và đối chiếu cấu hình (21/60 phút mỗi sự cố, 2 sự cố/tháng) | Tần suất chỉ 2 sự cố/tháng (120 phút/tháng) thì impact thời gian có quá nhỏ để ưu tiên so với việc chuẩn hóa structured logging và dry-run trước khi chạy không? (Trần Đức Mạnh) |
| 18 | Nguyễn Văn Ngọc Sơn | Khi PM/BA hỏi hệ thống đang sai ở những tình huống nào, muốn cung cấp các nhóm lỗi, ví dụ và tần suất có thể đối chiếu, để nhóm chọn đúng việc cần sửa trước | AI Engineer, PM/BA | Đọc và phân nhóm lỗi bằng tay cho ~18 case mỗi yêu cầu (26/66 phút/yêu cầu, 3 yêu cầu/tuần) | Nếu chốt sẵn bộ 6 nhóm lỗi cố định (taxonomy) và bắt buộc người báo lỗi chọn loại lỗi ngay trên biểu mẫu (Rule tại nguồn) thì bước phân loại tay có biến mất không? (Hồ Sỹ Tùng) |

*Ghi chú: Toàn bộ 18 candidate đã được 6 thành viên trình bày và đặt câu hỏi phản biện chéo trực tiếp tại phiên Pitch CP3 (không dùng AI).*

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A · Gom và đọc thông tin rải ở nhiều nguồn | #7, #8, #9, #12, #15 | Người dùng phải đi qua nhiều nơi (ứng dụng, đánh giá, tài liệu dài) để rút ra một kết luận, và việc này tốn thời gian |
| B · Câu hỏi, khiếu nại, yêu cầu lặp lại xử lý bằng tay | #2, #5, #10, #14 | Cùng một loại yêu cầu quay lại nhiều lần, mỗi lần một người phải đọc, trả lời hoặc điều phối thủ công và chậm |
| C · Kiểm tra, phát hiện lỗi hoặc sai lệch | #1, #3, #11, #13, #16, #17, #18 | Lỗi, điều khoản bất lợi hoặc sai lệch bị phát hiện muộn hoặc sót vì kiểm tra thủ công, không có chỗ đối chiếu rõ ràng |
| D · Việc nhỏ hằng ngày thiếu tín hiệu nhắc đúng lúc | #4, #6 | Việc lặp lại mỗi ngày bị dồn lại hoặc làm muộn vì không có điểm nhắc cố định |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm số giờ mỗi tuần mà một người phải bỏ ra cho việc lặp lại, đọc, tìm và kiểm tra thủ công
├── Opportunity A: Mất nhiều thời gian gom và đọc thông tin rải ở nhiều nguồn mới ra được kết luận
├── Opportunity B: Cùng một câu hỏi, khiếu nại hoặc yêu cầu phải xử lý lặp lại bằng tay và chậm
├── Opportunity C: Lỗi, điều khoản bất lợi hoặc sai lệch bị phát hiện muộn hoặc bị sót
└── Opportunity D: Việc nhỏ hằng ngày bị dồn hoặc làm muộn vì không có điểm nhắc đúng lúc
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- #3 "Tự động kiểm tra định dạng và hạn nộp": "tự động kiểm tra" là cách giải. Viết lại thành pain: sinh viên nộp sai định dạng hoặc quá hạn mà chỉ biết sau khi cổng đã khóa.
- #14 "Tự động hóa tiếp nhận và điều phối lịch hẹn": "tự động hóa" là cách giải. Pain thật: trùng lịch và bệnh nhân quên hoặc hủy sát giờ.
- #7 "Tìm kiếm ảnh chụp màn hình theo nội dung": đây là tính năng. Pain thật: không tìm lại được ảnh chụp màn hình cần dùng.
- #15 "Tóm tắt và trích xuất từ paper PDF": "tóm tắt, trích xuất" là cách giải. Pain thật: đọc tài liệu kỹ thuật dài tốn hàng chục giờ.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #5 Giải thích lại cùng một câu hỏi | 5 | 4 | 3 | 4 | 5 | 5 | 4 | **30** |
| #8 Tổng hợp công việc và deadline từ nhiều ứng dụng | 2 | 2 | 2 | 3 | 3 | 4 | 3 | **19** |
| #15 Đọc paper PDF dài để lấy phương pháp và dataset | 4 | 3 | 3 | 4 | 3 | 4 | 3 | **24** |

*Điểm do nhóm chấm (thang 1–5). Tổng đã kiểm tra lại: #5 = 30, #8 = 19, #15 = 24. #5 dẫn đầu, #8 thấp nhất vì thiếu thông tin về actor, quy trình và bằng chứng.*

**Tóm tắt phiếu nhận định của các thành viên trong nhóm:**

- **Đỗ Cao Cường:** Chọn nhất **#5** vì có số đo, actor rõ và dễ thử cách đơn giản (FAQ) rồi đo lại; muốn loại nhất **#8** vì chưa rõ actor, nguồn việc và dễ trùng với #6.
- **Nguyễn Quang Đạo:** Ban đầu pitch **#1** (kiểm tra hợp đồng), nhưng sau phản biện đã đồng ý rút #1 vì không có hợp đồng thật 30–40 trang và luật sư nội bộ trong buổi lab; chuyển sang chọn **#5** vì có sẵn đối tượng để khảo sát ngay và dễ đối chiếu từ mức No AI.
- **Trần Đức Mạnh:** Đưa **#15** vào shortlist nhưng đồng thuận chọn **#5** làm bài toán chính vì #15 có rủi ro trích sai số liệu từ bảng biểu cao; chất vấn thêm #5 về rào cản hành vi liệu người hỏi có chịu tự tra tài liệu hay không.
- **Hồ Sỹ Tùng, Trần Quốc Đông, Nguyễn Văn Ngọc Sơn:** Thống nhất chọn **#5** (30/35 điểm) vì đạt điểm cao nhất trên cả 7 tiêu chí, quy trình rõ ràng và kiểm chứng được ngay bằng survey trong buổi học.

**Candidate được chọn:** #5 · Khi đồng nghiệp hoặc bạn học hỏi lại một câu đã được trả lời, người được hỏi phải giải thích lại từ đầu, khoảng 2 lần/tuần và khoảng 15–30 phút mỗi lần (survey 10 người, ước lượng).

**Vì sao chọn:**

- Là candidate duy nhất đã có dữ liệu từ người ngoài nhóm: survey 10 người cho thấy 10/10 từng bị hỏi lại, 7/10 từ 3 lần trở lên trong 2 tuần, 7/10 mất từ 15 phút mỗi lần (xem mục 3.2).
- Actor rõ (người được hỏi, đồng nghiệp, bạn học) và nhóm đã khảo sát được những người bị ảnh hưởng ở CP4.
- Điểm nhóm cao nhất trong shortlist: 30, so với 24 (#15) và 19 (#8).
- Vừa sức lab, và có thể so sánh rõ các mức: một trang FAQ đã có thể đủ (No AI), nên nhóm kiểm chứng được việc có cần AI hay không.

**Vì sao loại các candidate còn lại:**

- **#8 Tổng hợp công việc và deadline từ nhiều ứng dụng:** chưa rõ actor, nguồn việc và số phút. Dễ trùng với việc sắp xếp ưu tiên mỗi sáng (#6). Có thể quay lại nếu người đưa ra bổ sung số liệu.
- **#15 Đọc paper PDF dài để lấy phương pháp và dataset:** pain thật, nhưng rủi ro trích sai số liệu từ bảng biểu cao, khó đưa ra tiêu chí đạt trong khuôn khổ lab. Chưa có số đo thời gian đọc cho từng người.
- **Các candidate ngoài shortlist (#1–#4, #6, #7, #9–#14, #16–#18):** đã được rà soát tại phiên Pitch; các bài toán chuyên sâu (#1 hợp đồng pháp lý, #13 bãi xe, #16–#18 kiểm thử/huấn luyện mô hình) khó tiếp cận mẫu khảo sát ngoài nhóm ngay trong phạm vi buổi lab hoặc giải quyết tốt hơn bằng Rule/công cụ có sẵn.

**Xử lý bất đồng (nếu có):** Ở đầu phiên thảo luận CP3, một số thành viên quan tâm tới các bài toán thiên về kỹ thuật AI (#1 rà soát hợp đồng, #15 đọc paper PDF, #16 kiểm thử hồi quy prompt). Sau khi phản biện về tính khả thi khi kiểm chứng (CP4) và rủi ro ảo giác số liệu, cả 6 thành viên đạt đồng thuận 100% chọn candidate #5 và giữ các bài toán còn lại cho các vòng nghiên cứu sau.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Người khác (đồng nghiệp, bạn học) thật sự hỏi lại cùng một câu khoảng 1–2 lần/tuần | Value | 5 | 4 (survey 10 người: 10/10 từng gặp, 7/10 từ 3 lần trong 2 tuần) | Đã kiểm chứng bằng survey |
| 2 | Mỗi lần giải thích lại mất 30 phút–1 giờ, không chỉ vài phút | Value | 5 | 3 (7/10 mất từ 15 phút, chỉ 3/10 mất 30–60 phút: bị phản bác một phần) | Đã kiểm chứng, cần sửa baseline |
| 3 | Người hỏi chịu tự tra một chỗ có sẵn (FAQ, tin ghim) thay vì hỏi trực tiếp | Usability | 5 | 2 (7/10 nói sẵn sàng, 3/10 có thể: mới là ý định nói ra) | Cần pilot để xem hành vi thật |
| 4 | Các câu hỏi lặp lại đủ giống nhau để gom thành một bộ trả lời sẵn, không phải mỗi lần một khác | Feasibility | 4 | 3 (6/10 hầu hết giống, 4/10 giống một phần) | Đã kiểm chứng một phần |
| 5 | Phần tốn thời gian là giải thích lại, không phải tìm lại câu trả lời cũ | Value | 3 | 2 | Sau |
| 6 | Có người chịu cập nhật FAQ để nó không lỗi thời | Viability | 3 | 1 | Sau |

Giả định nhóm kiểm chứng trong buổi này: #1, #2, #3, #4, qua survey 10 người (xem 3.2). #3 vẫn cần pilot.

### 3.2. Kiểm chứng

Cách đã dùng: **Survey** (10 người). Không thực hiện phỏng vấn, nên không có interview snapshot.

**Thiết kế survey:** 10 người trả lời, ẩn danh theo vai trò. Thu thập 4 chỉ số: số lần bị hỏi lại trong 2 tuần gần đây, thời gian mỗi lần, mức độ giống nhau của các câu hỏi, và mức sẵn sàng dùng FAQ. Dữ liệu thô nằm ở bảng dưới (chép nguyên từ file kết quả survey của nhóm).

| Mã | Vai trò | Số lần bị hỏi lại (2 tuần) | Thời gian mỗi lần | Mức giống nhau của câu hỏi | Sẵn sàng dùng FAQ |
|---|---|---|---|---|---|
| R1 | Kỹ sư phần mềm | 3–5 | 15–30 phút | Hầu hết giống nhau | Có |
| R2 | Sinh viên | 1–2 | 5–15 phút | Giống một phần | Có thể |
| R3 | Trưởng nhóm | 6–10 | 30–60 phút | Hầu hết giống nhau | Có |
| R4 | Kỹ sư phần mềm | 3–5 | 15–30 phút | Hầu hết giống nhau | Có |
| R5 | Sinh viên | 3–5 | 15–30 phút | Giống một phần | Có |
| R6 | Nhân viên văn phòng | 1–2 | 5–15 phút | Giống một phần | Có thể |
| R7 | Kỹ sư phần mềm | 6–10 | 30–60 phút | Hầu hết giống nhau | Có |
| R8 | Sinh viên | 1–2 | Dưới 5 phút | Hầu hết giống nhau | Có |
| R9 | Trưởng nhóm | 3–5 | 30–60 phút | Hầu hết giống nhau | Có |
| R10 | Nhân viên văn phòng | 3–5 | 15–30 phút | Giống một phần | Có thể |

Tổng hợp:

| Chỉ số | Kết quả | Giả định liên quan | Tín hiệu |
|---|---:|---|---|
| Từng bị hỏi lại câu cũ | 10/10 (100%) | #1 | Xác nhận |
| Bị hỏi lại từ 3 lần trở lên trong 2 tuần | 7/10 (70%) | #1 | Xác nhận |
| Mất từ 15 phút trở lên mỗi lần | 7/10 (70%) | #2 | Xác nhận một phần |
| Mất 30–60 phút mỗi lần | 3/10 (30%) | #2 | **Phản bác một phần**: giả định ban đầu là 30 phút–1 giờ, nhưng chỉ 3/10 ở mức này |
| Câu hỏi hầu hết giống nhau | **6/10 (60%)**, 4/10 giống một phần | #4 | Xác nhận một phần |
| Sẵn sàng dùng FAQ | 7/10 (70%) Có, 3/10 (30%) Có thể, 0/10 Không | #3 | Xác nhận yếu: đây là ý định nói ra, chưa phải hành vi đã xảy ra |

Ước tính từ khoảng giá trị giữa của từng mức (ước lượng, không phải số đo): trung bình khoảng 4 lần/người trong 2 tuần (khoảng 2 lần/tuần), khoảng 25 phút/lần, tức khoảng 65 phút/tuần/người, thấp hơn mức 30 phút–1 giờ/lần ở giả định ban đầu nhưng khớp với khoảng 0,5–2 giờ/tuần của ước lượng ban đầu.

**Hạn chế của survey:**

- Mẫu nhỏ (10 người). Cả 10 người đều từng bị hỏi lại ít nhất 1–2 lần, nên có thể mẫu chưa gồm người ít bị hỏi lại (thiên lệch chọn mẫu).
- Không có câu trả lời mở ("lần gần nhất là chuyện gì"), nên chưa có một câu nói nguyên văn hay chuyện cụ thể nào.
- "Sẵn sàng dùng FAQ" là câu hỏi giả định về tương lai. Theo The Mom Test, đây là bằng chứng yếu. Cần pilot để xem hành vi thật.

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

- Giữ nguyên problem: việc bị hỏi lại câu cũ có thật và đủ thường xuyên (10/10 từng gặp, 7/10 từ 3 lần/2 tuần).
- **Sửa baseline:** từ "30 phút–1 giờ mỗi lần" xuống "khoảng 15–30 phút mỗi lần là phổ biến nhất (4/10 ở mức 15–30 phút, 3/10 ở mức 30–60 phút)". Mức 30–60 phút chỉ nên coi là trường hợp nặng (trưởng nhóm và kỹ sư có nhiều lần hỏi lại).
- **Sửa quyết định** từ Not Yet sang Go phạm vi nhỏ (pilot FAQ, No AI), vì hai giả định quan trọng nhất (#1, #4) có bằng chứng và không có ai trả lời "Không" với FAQ. Giả định #3 vẫn cần kiểm chứng bằng pilot.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Slack Workflow Builder, trả lời FAQ bằng emoji | [slack.com](https://slack.com/resources/using-slack/4-simple-ways-to-save-time-with-workflow-builder) | Bước "giải thích lại": khi ai đó hỏi câu cũ, một emoji kích hoạt tin nhắn trả lời sẵn dẫn tới tài liệu FAQ | Trang mô tả cách làm ngay: chỉ cần có sẵn một tài liệu FAQ, gắn emoji, workflow gửi trả lời trong thread | Cần người viết và duy trì tài liệu FAQ trước. Trang không nói về chi phí hay gói áp dụng. Chỉ chạy được nếu nhóm dùng Slack | Giải pháp đơn giản, không cần AI, đúng hướng No AI. Điều kiện then chốt là có FAQ tốt |
| Notion, hỏi đáp trên nội dung workspace | [notion.com](https://www.notion.com/help/guides/get-answers-about-content-faster-with-q-and-a) | Bước "tìm lại câu trả lời": người hỏi tự đặt câu hỏi cho tài liệu của nhóm thay vì nhắn cho đồng nghiệp | Trang nói thẳng vấn đề "người giữ kiến thức bị hỏi liên tục những câu thường lệ" | Chỉ trả lời được từ nội dung đã có trong workspace và người dùng có quyền truy cập. Hiệu quả phụ thuộc workspace đầy đủ và cập nhật | Dù có công cụ hỏi đáp, bước đầu vẫn là có nội dung tốt. Mức "có AI" chỉ có ích khi tài liệu nguồn đã tồn tại |
| Slack AI, tìm kiếm có trả lời | [slack.com](https://slack.com/intl/en-au/features/ai) | Bước "tìm lại câu trả lời cũ" trong các cuộc trò chuyện đã có | Tìm trong tin nhắn, tệp và ứng dụng đã tích hợp vào Slack | Trang nói tính năng AI có trên các gói trả phí và có chú thích thông tin có thể thay đổi. Con số tiết kiệm thời gian của trang dựa trên phân tích nội bộ của chính Slack, không độc lập | Cần thận trọng với số liệu của nhà cung cấp. Không phải giải pháp cho nhóm không dùng Slack hoặc không dùng gói trả phí |

*Cả 3 link đã được mở và đối chiếu nội dung trang. Trang Notion có tiêu đề hiển thị là "Get answers about work content faster with Notion Agent". Link của Slack có bản ngôn ngữ khác, nội dung có thể khác nhau chút.*

**Bằng chứng kiểm chứng Research trong `report/assets/`:**
- Ghi chú trích dẫn và phân tích chi tiết: [cp4-research-notes.md](../assets/cp4-research-notes.md)
- Ảnh chụp màn hình đối chiếu: [Slack Workflow Builder](../assets/cp4-research-slack-workflow.png) · [Notion Q&A / Notion Agent](../assets/cp4-research-notion-qa.png) · [Slack AI](../assets/cp4-research-slack-ai.png)

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ quy trình hiện tại (đã đối chiếu với kết quả survey 10 người ở mục 3.2):

```text
HIỆN TẠI — phổ biến 15–30 phút/lần (nặng nhất 30–60 phút), trung bình ~2 lần/tuần (~65 phút/tuần/người)

[1. Người hỏi nhắn/hỏi lại câu cũ: ~2'] → [2. Người được hỏi nhớ hoặc tìm lại câu trả lời cũ: ~3–5']
→ [3. Người được hỏi giải thích lại từ đầu: 15–30' (nặng nhất 30–60')] ← BOTTLENECK
→ [4. Người hỏi làm thử và hỏi xác nhận lại nếu chưa rõ: ~5']
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Đồng nghiệp, bạn học (người hỏi) | Vướng mắc trùng với câu hỏi đã từng được trả lời trước đó | Tin nhắn trên kênh chat nhóm (Zalo/Discord/Slack) hoặc câu hỏi trực tiếp | ~2 phút/lần; trung bình ~2 lần/tuần | Người hỏi thường nhắn hỏi ngay vì không có chỗ tra cứu tập trung |
| 2 | Người được hỏi (kỹ sư, trưởng nhóm, sinh viên) | Câu hỏi của đồng nghiệp / bạn học | Nhớ lại hoặc cuộn tìm lại câu trả lời/lệnh hướng dẫn trong lịch sử chat cũ | ~3–5 phút/lần | Lịch sử chat bị trôi nên khó tìm lại nhanh đoạn giải thích cũ |
| 3 | Người được hỏi | Nội dung câu trả lời / quy trình xử lý | Gõ tin nhắn dài hoặc ngồi giải thích lại từ đầu từng bước | **Phổ biến 15–30 phút/lần** (30–60 phút ở 3/10 người trong survey) | **Bước nghẽn chính (Bottleneck)** — làm ngắt quãng công việc đang làm |
| 4 | Người hỏi | Lời giải thích của người được hỏi | Thao tác làm thử, gửi ảnh màn hình hỏi tiếp nếu vướng bước phụ | ~5 phút/lần | Kéo dài hơn nếu lời giải thích miệng thiếu bước hoặc thiếu câu lệnh mẫu |

**Bottleneck chính:** Bước 3 — giải thích lại từ đầu. Dữ liệu survey 10 người (mục 3.2) cho thấy mức phổ biến nhất là **15–30 phút/lần** (4/10 người), mức **30–60 phút/lần** (3/10 người, rơi vào Trưởng nhóm và Kỹ sư phần mềm), tần suất trung bình khoảng **2 lần/tuần** (~4 lần/2 tuần), tương đương **~65 phút/tuần/người**.

### 4.2. Quy trình tương lai

Mức chọn: **No AI**. Toàn bộ các bước đều do con người thực hiện thông qua một **trang FAQ dùng chung** (hoặc tin nhắn ghim ở đầu kênh chung) gồm các câu hỏi thường gặp nhất. Chưa cần bước xử lý tự động bằng Rule hay AI.

```text
TƯƠNG LAI — No AI (Trang FAQ dùng chung + Tin ghim)

[1. Người hỏi gặp vướng mắc] → [2. Tự tra trong FAQ / tin ghim: ≤ 2']  (CON NGƯỜI)
     ├── Tìm thấy câu trả lời → [3a. Làm theo hướng dẫn trong FAQ: ~3'] → Xong (người được hỏi tốn 0' hoặc chỉ ≤ 1' gửi link)
     └── Không thấy (câu hỏi mới) → [3b. Nhắn hỏi người được hỏi] (CON NGƯỜI)
                                        → [4. Người được hỏi giải thích trực tiếp: 15–30'] (CON NGƯỜI)
                                        → [5. Người phụ trách cập nhật câu hỏi lặp lại ≥ 2 lần vào FAQ: ~5'/tuần] (CON NGƯỜI — HITL)

BOUNDARY: Chưa dùng AI. Nếu về sau thêm AI hỗ trợ tra cứu thì AI chỉ được trích xuất từ các mục FAQ đã được con người duyệt, tuyệt đối không tự suy diễn câu trả lời ngoài FAQ.
PHƯƠNG ÁN QUAY VỀ: Nếu người hỏi không tìm thấy trong FAQ hoặc tài liệu FAQ chưa bao phủ tình huống đặc thù, quay về hỏi và giải thích trực tiếp giữa người với người như quy trình hiện tại.
NGƯỜI KIỂM TRA (HITL): Người phụ trách duy trì FAQ của nhóm (Nhóm trưởng phối hợp cùng người được hỏi nhiều nhất) rà soát và cập nhật nội dung vào cuối mỗi tuần.
```

### 4.3. Before / after

| Chỉ số | Trước (As-Is) | Sau (To-Be kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 4 bước mỗi lần hỏi | 2 bước khi câu hỏi đã có trong FAQ (4–5 bước khi gặp câu hỏi mới cần bổ sung vào FAQ) | Giảm tải trực tiếp cho người được hỏi |
| Tổng thời gian của người được hỏi | Phổ biến **15–30 phút/lần** (30–60 phút ở bản nháp ban đầu và ở nhóm Trưởng nhóm/Kỹ sư); trung bình **~65 phút/tuần/người** | **≤ 5 phút/lần** khi câu hỏi đã có trong FAQ (chỉ gửi link hoặc nhắc xem tin ghim) | Đo thực tế trong 2 tuần pilot |
| Số bước thủ công của người được hỏi | 2 bước chính mỗi lần bị hỏi (tìm lại + giải thích lại từ đầu) | 0–1 bước khi đã có trong FAQ (chỉ gửi link); 1 lần rà soát cập nhật FAQ hằng tuần (~5–10 phút) | Chuyển từ giải thích lặp lại sang chuẩn hóa 1 lần |
| Bottleneck chính | Bước 3: Giải thích lại từ đầu mỗi khi có người hỏi | Viết rõ 5 mục FAQ ban đầu và duy trì cập nhật khi có câu hỏi mới lặp lại ≥ 2 lần | Điểm nghẽn mới nhẹ hơn và kiểm soát được theo lịch cố định |
| Rủi ro mới phát sinh | — | FAQ lỗi thời nếu thiếu người duy trì; người hỏi vẫn quen nhắn hỏi trực tiếp mà không mở FAQ đọc trước | Kiểm soát qua pilot 2 tuần và ngưỡng dừng ở mục 8.2 |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Người được hỏi lại (thành viên trong nhóm học và làm việc), cùng đồng nghiệp và bạn học là người hỏi. |
| **Quy trình** | Người hỏi nhắn hoặc hỏi lại câu cũ, người được hỏi nhớ hoặc tìm lại câu trả lời rồi giải thích lại từ đầu, người hỏi làm thử và hỏi tiếp. |
| **Bottleneck** | Bước giải thích lại từ đầu, khoảng 30 phút–1 giờ mỗi lần (ước lượng ban đầu trước khi đối chiếu toàn bộ survey). |
| **Impact** | Khoảng 0,5–2 giờ/tuần cho người được hỏi (ước lượng, từ 1–2 lần/tuần). Làm gián đoạn việc đang làm. Người hỏi phải chờ người được hỏi rảnh. |
| **Success Metric** (baseline → target, cách đo) | Thời gian người được hỏi bỏ ra cho một lần bị hỏi lại câu đã có: từ 30 phút–1 giờ xuống ≤ 5 phút (mục tiêu đề xuất). Cách đo: ghi số phút mỗi lần bị hỏi lại trong 2 tuần, trước và sau khi có FAQ. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Chưa dùng AI. Người được hỏi vẫn trả lời các câu mới chưa có trong FAQ. |

**Phản biện nhận được cho Problem Statement v0 (từ AI và các thành viên trong nhóm) và cách nhóm xử lý:**

- **AI và bạn Đỗ Cao Cường, Hồ Sỹ Tùng chỉ ra:** Ở quy mô nhóm hiện tại, chỉ cần viết một trang FAQ chuẩn và ghim link là đủ (mức No AI), chưa cần nhảy sang xây công cụ AI. → **Nhóm đồng ý:** Giữ mức can thiệp là **No AI**.
- **Bạn Trần Đức Mạnh và Trần Quốc Đông phản biện từ dữ liệu Survey CP4:** Baseline `30 phút–1 giờ/lần` ở v0 đang bị cao hơn thực tế khảo sát (chỉ 3/10 người mất 30–60 phút, còn phổ biến nhất là `15–30 phút/lần`). Ngoài ra, câu hỏi "Sẵn sàng dùng FAQ" (7/10 Có) mới chỉ là ý định nói ra theo *The Mom Test*. → **Nhóm đồng ý:** Sửa lại baseline ở Problem Statement v1 về `15–30 phút/lần` (~65 phút/tuần/người) và thiết kế đợt pilot 2 tuần để đo hành vi thật.
- **Bạn Nguyễn Quang Đạo và Nguyễn Văn Ngọc Sơn phản biện về Metric & Boundary:** Nếu Success Metric ở v0 chỉ đo "số phút mỗi lần trả lời" thì chưa biết người hỏi có thực sự tự tra FAQ để giảm số lần hỏi lặp lại hay không; đồng thời cần ghi rõ ai là người kiểm tra/duy trì FAQ hàng tuần và ranh giới cấm AI bịa câu trả lời ngoài FAQ nếu về sau nâng cấp. → **Nhóm đồng ý:** Bổ sung chỉ số thứ hai (số lần bị hỏi lại giảm từ `1–2 lần/tuần` xuống `≤ 1 lần/2 tuần`) và làm rõ điều kiện Boundary + người kiểm tra ở bản **Problem Statement v1** (Mục 7).

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **mơ hồ thấp, vận hành đơn giản** ("rule hoặc script — vùng ngọt" trong ma trận của khóa).

Vì sao: Cùng một câu hỏi lặp lại, nên câu trả lời đã biết và ổn định, không mơ hồ. Việc vận hành chỉ là tìm một câu trả lời có sẵn và gửi cho người hỏi, không cần gọi công cụ hay gây tác động ra ngoài. *(Nhận định này dựa trên giả định #4 "câu hỏi đủ giống nhau", đã được xác nhận một phần qua survey với 6/10 "hầu hết giống nhau" và 4/10 "giống một phần".)*

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | Viết một trang FAQ dùng chung hoặc ghim tin nhắn trả lời, gửi link khi bị hỏi lại | Khi câu hỏi đủ giống nhau và người hỏi chịu tự tra | FAQ lỗi thời, không ai duy trì | **Chọn** |
| **Rule** | Gắn từ khóa để tự gửi đúng mục FAQ (ví dụ phản ứng emoji kích hoạt tin nhắn trả lời sẵn, như Slack Workflow Builder) | Khi có nhiều câu hỏi và người hỏi ngại tự tìm | Cần cấu hình công cụ, chỉ chạy được trên nền tảng hỗ trợ | Chưa |
| **Workflow** | Các bước cố định: nhận câu hỏi, tìm trong FAQ, trả lời, ghi lại câu mới | Khi số câu hỏi lớn và cần ghi nhận để cập nhật FAQ | Đắt hơn, khó test hơn, cần người vận hành | Chưa |
| **Agent** | Mô hình tự chọn bước và công cụ để trả lời | Gần như không có tình huống phù hợp ở quy mô này | Khó kiểm soát, có thể trả lời sai với giọng chắc chắn | Không |

**Mức chọn:** No AI.

**Vì sao không chọn mức đơn giản hơn:** Không có mức nào đơn giản hơn No AI. Quan trọng hơn, phần tiếp theo là vì sao **không lên mức cao hơn**: chưa có bằng chứng đo được rằng FAQ viết tay không đủ. Theo quy tắc của khóa, chỉ lên mức cao hơn khi có thứ gì đó đo được tốt lên để đáng đổi lấy chi phí.

### 6.3. AI Canvas rút gọn

*Bài toán hiện chọn No AI, nên canvas dưới đây chỉ áp dụng nếu CP4 cho thấy FAQ không đủ và nhóm cân nhắc thêm một bước AI.*

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | (Giả định) Tìm mục FAQ phù hợp nhất với câu hỏi của người hỏi. Không tự viết câu trả lời mới ngoài FAQ. |
| **Judgment** — con người cân nhắc, quyết định gì? | Người được hỏi duyệt nội dung FAQ và quyết định có thêm câu mới vào FAQ hay không. |
| **Action** — hành động cuối cùng là gì, ai làm? | Người hỏi đọc mục FAQ được gợi ý. Nếu không giải quyết được thì hỏi người được hỏi. |
| **Outcome** — đo kết quả bằng gì? | Số lần bị hỏi lại câu đã có trong FAQ, và thời gian người được hỏi bỏ ra mỗi lần. |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Câu hỏi của người hỏi và nội dung FAQ. FAQ chưa có, cần viết trước. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | Câu hỏi nào vẫn bị hỏi lại, người hỏi có thấy câu trả lời hữu ích không. |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: survey 10 người cho thấy 7/10 sẵn sàng dùng FAQ và 3/10 "có thể", không ai từ chối, nghĩa là người dùng chấp nhận được hỗ trợ (augment) hơn là giao hẳn việc. Đây vẫn là ý định nói ra, cần pilot để xem hành vi thật.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Nếu có AI, kiểu sai tệ hơn là **trả lời sai với giọng chắc chắn** (báo nhầm), vì người hỏi có thể làm theo câu trả lời sai mà không hỏi lại. Thiết kế nghiêng về tránh kiểu này: khi không chắc thì chuyển cho người, không tự trả lời ngoài FAQ. Với phương án No AI hiện tại, kiểu sai tương ứng là FAQ lỗi thời, xử lý bằng cách có người rà hằng tuần.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | Người được hỏi lại (thành viên trong nhóm học và làm việc), cùng đồng nghiệp và bạn học là người hỏi. |
| **Quy trình** | Người hỏi tự tìm trong FAQ hoặc tin ghim. Nếu không thấy thì hỏi người được hỏi, người này trả lời và thêm câu mới vào FAQ. |
| **Bottleneck** | Giải thích lại từ đầu những câu đã từng trả lời, phổ biến khoảng 15–30 phút mỗi lần, nặng nhất 30–60 phút (survey 10 người). |
| **Impact** | Trung bình khoảng 65 phút/tuần/người, từ khoảng 4 lần mỗi 2 tuần × khoảng 25 phút/lần (ước lượng từ khoảng giá trị giữa của survey). Trưởng nhóm và kỹ sư phần mềm ở mức cao nhất. |
| **Success Metric** (baseline → target, cách đo) | Thời gian người được hỏi bỏ ra mỗi lần bị hỏi lại câu đã có trong FAQ: từ khoảng 15–30 phút xuống ≤ 5 phút. Số lần bị hỏi lại câu đã có: từ khoảng 1–2 lần/tuần xuống ≤ 1 lần/2 tuần (mục tiêu đề xuất). Cách đo: ghi nhận trong 2 tuần trước và 2 tuần sau khi có FAQ. |
| **Boundary** | Chưa dùng AI. Nếu sau này thêm AI, chỉ được tìm trong FAQ đã được người duyệt, không tự trả lời ngoài FAQ, câu không có trong FAQ chuyển cho người. Người duy trì FAQ rà nội dung hằng tuần. |
| **AI intervention point** | **Không có** (vì bài toán nằm ở vùng mơ hồ thấp × vận hành đơn giản, số lượng câu hỏi lặp lại ít và ổn định nên một trang FAQ viết tay đã đủ giải quyết mà chưa cần AI dự đoán hay sinh nội dung; điểm duy nhất chỉ cân nhắc về sau là bước "tìm mục FAQ phù hợp" nếu FAQ quá lớn và người hỏi khó tìm). |
| **Mức chọn** | No AI |
| **Rủi ro & người kiểm tra** | FAQ lỗi thời hoặc sai: người phụ trách duy trì FAQ (Nhóm trưởng phối hợp cùng người được hỏi nhiều nhất) rà soát vào cuối mỗi tuần. Người hỏi không chịu tự tra: người được hỏi theo dõi số lần bị hỏi lại trong đợt pilot. Số liệu thời gian ở survey là ước lượng theo khoảng: cần bấm giờ đo thật trong 2 tuần pilot. |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| Quy trình | Mô tả quy trình hiện tại | Mô tả quy trình tương lai có FAQ | Cần chỉ ra chỗ nào thay đổi |
| Success Metric | Baseline 30 phút–1 giờ/lần, chỉ đo thời gian mỗi lần | Baseline sửa theo survey còn 15–30 phút/lần, thêm số lần bị hỏi lại câu đã có | Survey cho thấy 30–60 phút chỉ ở 3/10 người. Chỉ đo thời gian không cho biết FAQ có được dùng không |
| Bottleneck, Impact | 30 phút–1 giờ/lần, 0,5–2 giờ/tuần (ước lượng một người) | 15–30 phút/lần, khoảng 65 phút/tuần/người (survey 10 người) | Có dữ liệu từ người ngoài nhóm |
| Boundary | "Chưa dùng AI" | Thêm điều kiện nếu sau này thêm AI và người rà FAQ | Cần rõ AI được và không được làm gì, và ai kiểm tra |
| AI intervention point, Mức chọn, Rủi ro & người kiểm tra | (chưa có) | Thêm mới | Yêu cầu của v1 ở CP6 |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):** *Bài toán chọn No AI, nên các tiêu chí dưới đây áp dụng cho đầu ra của FAQ, và áp dụng nguyên cho AI nếu sau này thêm bước AI.*

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | Đúng nội dung | Câu trả lời trong FAQ khớp với điều người được hỏi sẽ giải thích | Câu trả lời sai hoặc lỗi thời |
| 2 | Tìm thấy nhanh | Người hỏi tìm được mục đúng trong ≤ 2 phút | Người hỏi không tìm được hoặc mất hơn 2 phút |
| 3 | Không bịa | Mọi câu trả lời đều có trong FAQ đã duyệt | Có câu trả lời không nằm trong FAQ |
| 4 | Chuyển người khi không chắc | Câu không có trong FAQ được chuyển cho người | Tự trả lời câu không có trong FAQ |
| 5 | Cập nhật | Câu hỏi bị hỏi lại ≥ 2 lần được thêm vào FAQ trong vòng 1 tuần | Câu hỏi lặp lại nhưng không được thêm vào |

*Ngưỡng 2 phút, 2 lần và 1 tuần là mục tiêu đề xuất, nhóm chỉnh sau khi có số đo thật.*

**Bộ 10 cặp Eval mẫu (Input / Đầu ra mong đợi — Bonus B3):** Xem chi tiết tại [report/assets/cp6-eval-samples.md](../assets/cp6-eval-samples.md).

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | Thấp | Survey 10 người: 10/10 từng bị hỏi lại, 7/10 từ 3 lần trong 2 tuần, 7/10 mất từ 15 phút mỗi lần. Mẫu nhỏ và có thể thiên lệch chọn mẫu. |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Trung bình | 7/10 sẵn sàng dùng FAQ, 3/10 "có thể", 0/10 từ chối. Nhưng đây là ý định nói ra, chưa phải hành vi, nên cần pilot (giả định #3). Với No AI thì không có đầu ra AI để sửa. |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | Thấp | FAQ viết tay hoặc ghim tin, không cần công nghệ đặc biệt. Cần gom các câu hỏi hay lặp lại (giả định #4 đã kiểm chứng một phần: 6/10 cho rằng câu hỏi hầu hết giống nhau). |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | Trung bình | Chi phí gần như bằng 0, nhưng chưa có người duy trì FAQ (giả định #6). Không có vấn đề pháp lý hiển nhiên ở phương án No AI. |

### 8.2. Kết luận

**Quyết định:** **Go, phạm vi nhỏ** (pilot FAQ, mức No AI).

**Lý do:** Survey 10 người xác nhận pain có thật (10/10 từng gặp, 7/10 từ 3 lần trong 2 tuần), 7/10 mất từ 15 phút mỗi lần, 6/10 cho rằng câu hỏi hầu hết giống nhau và 0/10 từ chối dùng FAQ. Giải pháp FAQ gần như không tốn chi phí và chưa có bằng chứng cần AI. Rủi ro còn lại: mẫu nhỏ, thiên lệch chọn mẫu, và ý định dùng FAQ chưa phải hành vi. Vì vậy chỉ đi phạm vi nhỏ.

**Nếu Go — pilot nhỏ nhất:** Trong 2 tuần, viết một trang FAQ cho 5 câu hỏi hay bị hỏi lại nhất (kèm câu lệnh/hướng dẫn chuẩn), ghim ở đầu kênh chung và gửi link mỗi khi bị hỏi. Ghi số phút mỗi lần bị hỏi lại và số lần câu đã có trong FAQ vẫn bị hỏi, trước và sau pilot.

**Nếu Not Yet — cần kiểm chứng gì trước:** Pilot 2 tuần để xem người hỏi có thật sự tự tra FAQ không (giả định #3), và liệt kê cụ thể các câu hay bị hỏi lại để gom thành FAQ (giả định #4).

**Nếu No-Go — nên làm gì thay AI:** Nếu pilot cho thấy mỗi lần chỉ mất dưới 15 phút hoặc ít người hỏi lại, dừng việc này và quay lại shortlist (#8 hoặc #15) hoặc candidate khác.

**Ngưỡng dừng** (mục tiêu đề xuất): nếu sau 2 tuần có FAQ mà số lần bị hỏi lại câu đã có trong FAQ vẫn ≥ 1 lần/tuần, thì xem lại cách trình bày và chỗ đặt FAQ. Nếu sau 4 tuần vẫn không giảm, dừng phương án FAQ và cân nhắc mức Rule hoặc đổi problem. Nếu đo trong pilot cho thấy pain trung bình < 15 phút/lần, dừng và chọn candidate khác.

---

## 9. Hạn chế và hướng tiếp theo

- **Hạn chế về mẫu khảo sát:** Survey hiện mới thực hiện trên 10 người, cả 10 đều từng bị hỏi lại (có thể thiên lệch chọn mẫu), sử dụng câu hỏi đóng nên chưa có câu trích dẫn nguyên văn từ câu hỏi mở, và chỉ số "7/10 sẵn sàng dùng FAQ" mới phản ánh ý định tương lai chứ chưa phải hành vi thực tế theo *The Mom Test*. Các số trung bình (~4 lần/2 tuần, ~25 phút/lần, ~65 phút/tuần/người) được tính từ điểm giữa của khoảng giá trị khảo sát.
- **Hạn chế về đo đếm quy trình:** Thời gian từng bước trong quy trình hiện tại và các ngưỡng mục tiêu ở mục 7, 8 (`≤ 5 phút/lần`, tìm thấy trong `≤ 2 phút`, cập nhật trong `1 tuần`) là ước lượng và mục tiêu đề xuất cho đợt pilot, cần bấm giờ thực nghiệm để hiệu chỉnh.
- **Hướng tiếp theo ngay sau buổi lab:**
  1. Chỉ định người phụ trách duy trì FAQ hằng tuần (Nhóm trưởng phối hợp cùng thành viên kỹ thuật trong nhóm).
  2. Đưa 5 mục FAQ đầu tiên (đã phác thảo tại [`report/assets/cp6-eval-samples.md`](../assets/cp6-eval-samples.md)) lên kênh làm việc chung của nhóm và ghim cố định.
  3. Chạy pilot trong 2 tuần, ghi nhật ký số lần bị hỏi lại và số phút xử lý thực tế để đánh giá theo đúng ngưỡng dừng tại mục 8.2.

## 10. Tài liệu tham khảo

- Slack, "4 simple ways to save time with Workflow Builder": https://slack.com/resources/using-slack/4-simple-ways-to-save-time-with-workflow-builder
- Notion, "Get answers about work content faster with Q&A" (trang hiển thị tiêu đề "…with Notion Agent"): https://www.notion.com/help/guides/get-answers-about-content-faster-with-q-and-a
- Slack, "Slack AI features & AI assistants": https://slack.com/intl/en-au/features/ai
- Rob Fitzpatrick, *The Mom Test* (3 luật phỏng vấn, theo hướng dẫn trong `docs/01-worksheet.md`).
- Google PAIR, *People + AI Guidebook* (hai câu hỏi augment/automate và báo nhầm/bỏ sót, theo hướng dẫn trong `docs/01-worksheet.md`).
