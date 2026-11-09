# Báo cáo cá nhân — 2A202603615_TranDucManh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Đức Mạnh
- MSSV: 2A202603615
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: ABC404
- Link repo nhóm:https://github.com/dongtranquoc951/K5-L3A-Day02-Nhomabc404-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi kiểm soát xe ra vào bãi gửi xe giờ cao điểm, tôi muốn tự động đối soát biển số xe với thẻ từ thay vì nhìn mắt thường và nhập tay, để tránh ùn tắc và giảm rủi ro mất xe. | Nhân viên bảo vệ, sinh viên/người gửi xe tại trường học và khu chung cư. | Xảy ra 2 khung giờ cao điểm/ngày (7h30-8h30 và 17h00-18h30); bãi xe 300-500 lượt/giờ; thẻ mờ hoặc camera quét lỗi gây tắc nghẽn 10-15 phút tại cửa soát vé. |
| 2 | Tốn thời gian | Khi tiếp nhận tin nhắn đặt lịch của khách hàng trên Fanpage/Zalo, tôi muốn tự động phân loại nhu cầu và gợi ý giờ trống, để không phải liên tục tra cứu sổ lịch và nhắn tin thủ công. | Lễ tân phòng khám nha khoa/spa, khách hàng đặt dịch vụ. | 30-50 cuộc trò chuyện/ngày; mất trung bình 5-7 phút cho 1 lượt tư vấn giờ khám; tỉ lệ khách quên/hủy lịch sát giờ lên tới 20% do thiếu hệ thống nhắc lịch tự động. |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi làm đồ án tốt nghiệp và nghiên cứu, tôi muốn tóm tắt nhanh phương pháp, dataset và kết quả từ hàng chục file PDF bài báo khoa học, để so sánh và chọn hướng đi mà không mất công đọc từng trang. | Sinh viên năm cuối, giảng viên hướng dẫn nghiên cứu. | Cần đọc 20-30 papers/đồ án (10-15 trang/paper); mất 3-4 ngày chỉ để đọc lướt và lọc bài liên quan; dễ ghi chú sót các thông số kỹ thuật cốt lõi. |
| 4 | Pain từ người khác | Khi mạch nhúng/thiết bị IoT gặp sự cố không chạy, tôi muốn nhanh chóng chẩn đoán xem lỗi do đấu sai chân phần cứng hay do logic code, để tránh mất hàng giờ đo mạch thủ công. | Sinh viên thực hành môn vi điều khiển/nhúng, kỹ sư phần cứng mới đi làm. | Gặp trong các buổi thực hành lab (1-2 lần/tuần); mất 1-2 tiếng đo từng chân nguồn/dây lỏng; log lỗi Serial chung chung (như timeout, core panic) rất khó khoanh vùng. |
| 5 | Lặp lại | Khi kiểm duyệt tin nhắn trong hòm thư hỗ trợ và bình luận nhóm, tôi muốn tự động phát hiện và chặn các nội dung spam quảng cáo/lừa đảo, để giữ luồng trao đổi trong sạch và kịp thời hỗ trợ khách hàng thật. | Quản trị viên nhóm/Fanpage, nhân viên trực chat CSKH. | Nhận 50-100 bình luận spam link rác/ngày; mất 30-45 phút/ngày duyệt và bấm xóa tay; người dùng có nguy cơ click nhầm link lừa đảo. |
| 6 | Cần đọc, tổng hợp nhiều thông tin | Khi đọc tài liệu báo cáo kỹ thuật dài hoặc tài liệu hướng dẫn hệ điều hành (Linux/RTOS), tôi muốn tra cứu và giải thích nhanh ngữ cảnh các hàm API/System Call trực tiếp trên file PDF, để không phải liên tục chuyển tab tìm kiếm tài liệu gốc. | Sinh viên ngành CNTT, kỹ sư phần mềm hệ thống/nhúng. | Tài liệu đặc tả dài 200-400 trang; mỗi buổi đọc phải tra cứu 15-20 hàm hệ thống; mất 2-3 phút mỗi lần tìm qua Google/man page khiến đứt gãy mạch đọc logic. |
| 7 | Tốn thời gian | Khi chấm bài tập lập trình hoặc kiểm tra format mã nguồn của sinh viên, tôi muốn tự động chạy lint và chấm điểm sơ bộ các tiêu chí cơ bản, để tập trung phản biện tư duy thuật toán thay vì ngồi soi lỗi cú pháp. | Giảng viên, trợ giảng (TA) phụ trách môn lập trình. | 60-80 bài nộp/lần bài tập; mất 5-10 phút để tải file, kiểm tra chạy thử và soi format từng bài; tốn 6-8 tiếng cho mỗi đợt chấm bài tập định kỳ. |
| 8 | Pain từ người khác | Khi đi làm việc hoặc trao đổi tài liệu nhóm trong môi trường mạng công cộng (quán cà phê, thư viện), tôi muốn mã hóa nhanh và gửi file an toàn, để người không phận sự không đọc trộm dữ liệu nhạy cảm nếu vô tình bắt được gói tin. | Sinh viên làm việc nhóm ở nơi công cộng, nhân viên làm việc từ xa (remote). | Làm việc ngoài văn phòng 3-4 buổi/tuần; chia sẻ các tài liệu điểm danh, hợp đồng nháp qua Wi-Fi công cộng không có mật khẩu; lo ngại rò rỉ dữ liệu cá nhân. |

**Nếu có dùng AI để gợi ý thêm:** 
- *Ý giữ lại:* Giữ lại 8 bài toán xuất phát từ các khâu thao tác thực tế (đọc tài liệu kỹ thuật, chấm bài tập, soát vé bãi xe, đặt lịch phòng khám, chẩn đoán mạch), các đối tượng (Actor) đều rõ ràng và có dữ liệu đo lường cụ thể về tần suất, thời gian lãng phí.
- *Ý bỏ qua:* Bỏ qua gợi ý về "Ứng dụng gợi ý thực đơn ăn kiêng tự động" và "Lên kế hoạch du lịch cá nhân" vì đây là các bài toán phụ thuộc nhiều vào cảm xúc/sở thích chủ quan, không có quy trình As-is định lượng và rào cản hành vi (behavior barrier) quá lớn.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3
| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Quản lý và đối soát xe ra vào bãi xe giờ cao điểm (Lặp lại) | Tần suất diễn ra hàng ngày, ùn ứ thấy rõ, dễ đo lường thời gian trễ và rủi ro nhầm lẫn vé xe. | Độ chính xác của camera nhận diện biển số khi gặp trời mưa, chói đèn hoặc biển số cong vênh/bám bẩn. |
| 2 | Tự động hóa tiếp nhận và điều phối lịch hẹn phòng khám (Tốn thời gian) | Giải quyết triệt để tình trạng trùng lịch và giảm mạnh tỷ lệ bệnh nhân quên/hủy lịch sát giờ (no-show). | Khách hàng lớn tuổi có quen tương tác xác nhận qua link/hệ thống tự động hay vẫn muốn gọi điện thoại trực tiếp. |
| 3 | Tóm tắt và trích xuất phương pháp/dataset từ paper PDF (Cần đọc, tổng hợp) | Nhu cầu cấp thiết của sinh viên làm đồ án; tiết kiệm hàng chục giờ đọc lướt tài liệu kỹ thuật dài. | Khả năng đọc hiểu bảng biểu và trích xuất số liệu thực nghiệm có bị ảo giác (hallucination) hay không. |

### Problem Card #1
| Trường | Nội dung |
|---|---|
| Job Story | Khi kiểm soát phương tiện tại cổng bãi xe giờ cao điểm, tôi muốn tự động đối soát biển số xe vào/ra với mã thẻ từ, để giải tỏa ùn tắc nhanh chóng và ngăn chặn hoàn toàn rủi ro tráo/mất xe. |
| Actor | Nhân viên bảo vệ trực chốt soát vé; người gửi xe (sinh viên, cư dân, nhân viên văn phòng). |
| Thời điểm / bối cảnh | Khung giờ cao điểm buổi sáng (7h30–8h30) và tan tầm (17h00–18h30) tại cổng bãi xe trường học, tòa nhà. |
| Quy trình hiện tại (3–7 bước) | 1. Xe dừng trước barie -> 2. Khách đưa thẻ gửi xe -> 3. Bảo vệ quẹt thẻ lên đầu đọc -> 4. Bảo vệ nhìn mắt thường đối chiếu biển số trên màn hình camera với xe thực tế -> 5. Nếu thẻ mờ/không khớp, bảo vệ cúi xuống xem biển và gõ lại biển số vào phần mềm -> 6. Xác nhận hợp lệ và bấm nút mở barie. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 4 và 5: Khi thẻ lỗi hoặc mắt thường nhìn nhầm, bảo vệ mất 30–60 giây/xe để kiểm tra và gõ tay lại; giờ cao điểm dồn ứ cả hàng dài xe phía sau. |
| Impact (nếu không giải thì sao) | Gây ùn tắc kéo dài 10–15 phút tại cổng; trễ giờ học/giờ làm của người gửi; rủi ro bảo vệ cho qua nhầm xe khi mệt mỏi, dẫn đến mất cắp phương tiện. |
| Success metric (baseline → target) | Thời gian xử lý đối soát trung bình giảm từ 8s/xe xuống dưới 2s/xe; tỷ lệ thao tác nhập tay thủ công giảm từ 15% xuống dưới 1%. |
| Phương án không dùng AI | Dùng thẻ chip RFID tầm xa gắn cố định trên xe kết hợp barrier tự động quét thẻ; hoặc phân chia thêm làn xe thủ công và tăng gấp đôi nhân sự trực giờ cao điểm. |
| Giả thuyết về AI (nếu có) | Sử dụng Computer Vision / OCR (nhận diện biển số tự động) nhận diện trực tiếp biển số xe khi vừa tiến vào vùng quét camera, tự so khớp với cơ sở dữ liệu thẻ vào mà không cần bảo vệ soi màn hình. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[Xe dừng trước barie] 
       │
       ▼
[Khách quẹt thẻ từ lên đầu đọc]
       │
       ▼
[Bảo vệ nhìn màn hình camera đối chiếu biển số]
       │
       ├─► (Thẻ mờ / Số không khớp) ──► [Bảo vệ cúi nhìn biển & gõ tay biển số]
       │                                                    │
       ▼                                                    ▼
[Bảo vệ bấm nút mở barie cho xe qua] ◄──────────────────────┘
```

### Problem Card #2
| Trường | Nội dung |
|---|---|
| Job Story | Khi tiếp nhận tin nhắn đặt hẹn từ khách hàng trên Fanpage/Zalo, tôi muốn tự động hóa việc sàng lọc nhu cầu dịch vụ và gợi ý khung giờ còn trống, để chốt lịch nhanh chóng và giảm thiểu tình trạng trùng/hủy hẹn. |
| Actor | Nhân viên lễ tân phòng khám nha khoa/spa; khách hàng có nhu cầu khám. |
| Thời điểm / bối cảnh | Suốt thời gian làm việc trong ngày khi khách hàng nhắn tin hỏi tư vấn và xếp lịch hẹn. |
| Quy trình hiện tại (3–7 bước) | 1. Khách nhắn tin miêu tả tình trạng/nhu cầu -> 2. Lễ tân đọc tin nhắn và phản hồi hỏi thêm thông tin -> 3. Lễ tân mở file sổ lịch trên máy tra cứu giờ trống của bác sĩ -> 4. Nhắn lại 2–3 khung giờ cho khách chọn -> 5. Khách xác nhận -> 6. Lễ tân nhập tay lịch vào sổ -> 7. Trước ngày khám gọi điện thủ công nhắc khách. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2, 3 và 7: Tra cứu qua lại mất 5–10 phút/khách; nếu có 3–4 khách nhắn cùng lúc rất dễ bị xếp trùng ghế/bác sĩ; gọi điện nhắc lịch thủ công tốn 1–2 tiếng mỗi cuối ngày. |
| Impact (nếu không giải thì sao) | Khách chờ phản hồi lâu dễ bỏ sang cơ sở khác; tỷ lệ no-show (quên lịch/bỏ hẹn) sát giờ lên tới 15–20% gây lãng phí giờ làm của bác sĩ. |
| Success metric (baseline → target) | Thời gian hoàn tất 1 lượt đặt lịch giảm từ 7 phút xuống dưới 1 phút; tỷ lệ bỏ hẹn không báo trước (no-show) giảm từ 20% xuống dưới 5%. |
| Phương án không dùng AI | Sử dụng trang đặt lịch cố định (như Calendly/Google Calendar link) gửi cho khách tự bấm chọn giờ trống; thiết lập kịch bản chatbot bấm nút (rule-based) theo cây quyết định. |
| Giả thuyết về AI (nếu có) | Tích hợp LLM chatbot hiểu ngôn ngữ tự nhiên để trích xuất ý định (intent) và thời gian khách muốn khám, tự động kết nối API kiểm tra lịch trống và gửi thông báo nhắc lịch tự động qua Zalo OA. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[Khách nhắn tin qua Fanpage/Zalo mô tả nhu cầu khám]
       │
       ▼
[Lễ tân đọc tin nhắn và phản hồi hỏi thêm triệu chứng]
       │
       ▼
[Lễ tân mở file Excel/sổ lịch tra cứu khung giờ trống của bác sĩ]
       │
       ▼
[Lễ tân nhắn lại 2-3 khung giờ cho khách lựa chọn]
       │
       ▼
[Khách phản hồi chốt giờ] ──► [Lễ tân nhập tay thông tin vào sổ khám]
                                        │
                                        ▼
                   [Trước ngày khám: Lễ tân gọi điện thoại nhắc lịch]
```

### Problem Card #3
| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu nghiên cứu làm đồ án, tôi muốn trích xuất nhanh cấu trúc phương pháp, dataset và kết quả thực nghiệm từ các file PDF tài liệu, để phân loại và tổng hợp tài liệu tham khảo chính xác mà không phải đọc thủ công từng trang. |
| Actor | Sinh viên năm cuối làm đồ án, học viên cao học, trợ giảng/nghiên cứu viên. |
| Thời điểm / bối cảnh | Giai đoạn khảo sát tài liệu (Literature Review) trong 2–4 tuần đầu của kỳ làm đồ án tốt nghiệp. |
| Quy trình hiện tại (3–7 bước) | 1. Tải 20–30 bài báo PDF từ Google Scholar/arXiv về máy -> 2. Mở từng file, đọc lướt Abstract và Conclusion -> 3. Cuộn tìm phần Experiment/Method để xem thuật toán và số liệu -> 4. Ghi chú thủ công tên paper, dataset, kết quả vào bảng Excel/Notion -> 5. Đối chiếu chéo giữa các bài để chọn hướng nghiên cứu. |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3 và 4: Mất 45–60 phút cho mỗi bài báo kỹ thuật để tìm đúng tham số và trích xuất bảng biểu; đọc nhiều bài dẫn đến mệt mỏi và nhầm lẫn số liệu giữa các tác giả. |
| Impact (nếu không giải thì sao) | Mất 1–2 tuần chỉ để lập bảng tổng quan tài liệu; nguy cơ bỏ sót các nghiên cứu quan trọng hoặc trích dẫn sai số liệu gốc trong báo cáo. |
| Success metric (baseline → target) | Thời gian tổng hợp thông tin cốt lõi 1 bài báo giảm từ 45 phút xuống dưới 5 phút; độ chính xác trích xuất đúng tên dataset và kết quả metric đạt trên 90%. |
| Phương án không dùng AI | Dùng các phần mềm quản lý trích dẫn truyền thống (Mendeley, Zotero) để lưu trữ tag và đọc lướt mục lục; phân chia nhóm sinh viên đọc chéo và tóm tắt thủ công. |
| Giả thuyết về AI (nếu có) | Áp dụng LLM kết hợp RAG (Retrieval-Augmented Generation) để đọc hiểu định dạng PDF khoa học, tự động điền các trường thông tin (Method, Dataset, SOTA metric) vào bảng so sánh. |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
[Tải 20-30 file PDF bài báo khoa học về máy]
       │
       ▼
[Mở từng file đọc lướt phần Abstract & Conclusion]
       │
       ▼
[Cuộn tìm phần Experiment / Method để tra cứu thuật toán & dataset]
       │
       ▼
[Gõ tay tên paper, phương pháp, kết quả metric vào file Excel/Notion]
       │
       ▼
[Đối chiếu chéo bảng tổng hợp giữa các bài để chọn hướng làm đồ án]
```

### Card muốn pitch nhất
- Card số: Problem Card #1 (Quản lý và đối soát xe ra vào bãi xe giờ cao điểm - Lăng kính: Lặp lại).
- Vì sao: Vấn đề này có nỗi đau (pain point) rất trực quan, dễ quan sát thực tế tại cổng trường/tòa nhà; quy trình các bước As-is rất cụ thể và đo lường được ngay bằng thời gian xe dừng trước barie.
- Câu hỏi muốn nhóm phản biện: Có thực sự cần đưa AI/Computer Vision vào để nhận diện biển số không, hay chỉ cần dùng thẻ RFID tầm xa và phân làn xe hợp lý là đủ giải quyết bài toán?

### AI đã phản biện card thế nào
| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1 ban đầu chưa chỉ rõ nguyên nhân gây nghẽn là do bước đọc thẻ hay do bước bảo vệ nhìn đối chiếu bằng mắt. | Đồng ý | Đã tách rõ Bottleneck nằm ở bước 4 và 5: bảo vệ phải kiểm tra đối chiếu mắt thường và gõ tay lại khi thẻ bị lỗi. |
| Card #2 (Đặt lịch) chưa nêu rõ phương án thay thế thông thường mà đã vội giả định giải pháp AI. | Đồng ý | Đã bổ sung phương án không dùng AI (dùng link Calendly hoặc Chatbot rule-based theo nút bấm) vào bảng để nhóm cân nhắc mức can thiệp ở CP6. |
| Card #3 (Đọc paper) đặt phạm vi quá rộng là "đọc hiểu toàn bộ paper", điều này dễ khiến AI bị ảo giác (hallucination). | Đồng ý | Thu hẹp ranh giới (boundary) chỉ tập trung trích xuất 3 trường thông tin cụ thể: Tên phương pháp, Dataset thử nghiệm, và Kết quả thực nghiệm cốt lõi. |

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày Problem Card #1 về điểm nghẽn đối soát biển số xe tại chốt kiểm soát giờ cao điểm; phân tích As-is 6 bước và chỉ ra bước 4-5 bảo vệ đối chiếu mắt thường và nhập tay gây nghẽn 10-15 phút. | Đưa bài toán có dữ liệu đo lường cụ thể vào vòng bầu chọn; nhóm thống nhất lấy đây làm 1 trong các ứng viên tiềm năng nhất để phản biện. |
| Phản biện bài của bạn khác | Đặt câu hỏi chất vấn bài toán tóm tắt paper và đặt lịch phòng khám: *"Phương án Form/Calendly hoặc quy tắc phân nhánh thủ công (Rule-based) đã giải quyết được chưa mà phải cần tới AI?"* | Giúp nhóm nhận diện ranh giới giữa tự động hóa thông thường và bài toán cần AI; loại bỏ việc chọn các bài toán bị dư thừa công nghệ. |
| Nhận phản biện | Tiếp nhận phản biện từ nhóm về rủi ro thời tiết (mưa gió, chói sáng làm camera nhận diện sai). Tôi đề xuất cơ chế Fallback: nếu confidence score < 90% thì giữ nguyên quẹt thẻ thường để bảo vệ không bị động. | Hoàn thiện luồng To-be an toàn, đưa cơ chế xử lý ngoại lệ (Exception Handling) vào phần thiết kế hệ thống của nhóm. |
| Gom cluster / cây OST | Cùng nhóm gom các phản ánh từ khảo sát thành 2 nhánh cơ hội chính trên cây OST: (1) Rút ngắn thời gian xác thực phương tiện tại cổng và (2) Giảm thiểu rủi ro tráo thẻ/mất trộm xe. | Định hình cấu trúc cây Opportunity Solution Tree rõ ràng, giúp nhóm không bị lan man sang các tính năng phụ như tìm chỗ đỗ xe trống. |
| Chọn candidate problem | Cùng nhóm cân nhắc 4 tiêu chí (Tính khả thi, Khả năng kiểm chứng Mom Test, Giá trị thực tế, Rủi ro) và bỏ phiếu chọn bài toán bãi giữ xe làm Candidate Problem duy nhất. | Nhóm đạt đồng thuận 100%, ghi nhận quyết định hội tụ vào mục 1 của group_report.md để chuyển sang khảo sát thực địa. |
| Kiểm chứng / research | Trực tiếp tham gia khảo sát thực địa tại chốt cổng: bấm giờ 20 lượt xe giờ cao điểm và phỏng vấn chú bảo vệ theo 3 nguyên tắc The Mom Test (hỏi về sự cố quá khứ, không hỏi ý kiến tương lai). | Thu được dữ liệu thật: thời gian quẹt thẻ bình thường mất 2-3s, nhưng khi gặp thẻ mờ phải gõ tay mất 35-50s/xe; bổ sung bằng chứng vào thư mục report/assets. |
| Quy trình nhóm | Tham gia vẽ và bóc tách luồng As-is (6 bước thủ công) và xây dựng luồng To-be tích hợp OCR tự động so khớp biển số với thẻ từ. | Xác định chính xác vị trí can thiệp công nghệ, phân định rõ khâu nào máy tự động xử lý và khâu nào giữ lại con người giám sát. |
| Problem Statement | Rà soát và hoàn thiện câu Problem Statement v0 cùng nhóm: chuẩn hóa Actor (bảo vệ trực chốt), chỉ số thành công (giảm từ 8s xuống < 2s/xe, gõ tay < 1%), và ranh giới Boundary. | Chốt được phát biểu bài toán chặt chẽ, có baseline và target định lượng, giúp nhóm không bị lạc đề ở khâu giải pháp. |
| Mức can thiệp AI | Phân tích 4 mức (No AI, Rule, Workflow, Agent) và đối chiếu 4 rủi ro sản phẩm; bảo vệ quan điểm chọn mức **Workflow** thay vì Agent vì quy trình bãi xe là tuần tự, không cần ra quyết định tự chủ đa bước. | Nhóm thống nhất chọn mức Workflow trong báo cáo, tránh được lỗi lạm dụng thuật ngữ "AI Agent" khi quy trình nghiệp vụ chưa cần thiết. |
| Quyết định | Tham gia phân tích các rủi ro kỹ thuật (mưa, góc quay) và chi phí camera để cùng nhóm biểu quyết đưa ra quyết định cuối cùng (Go có điều kiện / Not Yet). | Đóng góp lập luận bảo vệ kết luận nhóm tại mục 9 của group_report.md, tạo tính thuyết phục cao khi bảo vệ trước giảng viên. |
---

## 5. Dùng AI
| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 | Gợi ý thêm các góc nhìn về lăng kính "Cần đọc, tổng hợp" và "Pain từ người khác". | Mở rộng nhanh các tình huống thực tế thường gặp. | Gợi ý một số bài toán quá chung chung (như tự động lập kế hoạch du lịch cá nhân). | Loại bỏ các ý chung chung, chỉ giữ lại các bài toán có thể đo lường thời gian và tần suất thật. |
| CP2 | Nhờ phản biện các giả định trong Problem Card và tìm điểm yếu của quy trình. | Chỉ ra các lỗ hổng như chưa tách rõ bước nghẽn thao tác và nguy cơ ảo giác số liệu. | Thường vội vàng đề xuất áp dụng ngay AI Agent phức tạp dù quy trình chưa cần thiết. | Bổ sung phương án không dùng AI (No-AI baseline) và thu hẹp ranh giới (boundary) bài toán. |
| CP6 | Đối chiếu 4 rủi ro sản phẩm (Value, Usability, Feasibility, Viability) theo framework. | Cung cấp cấu trúc checklist phân tích rủi ro đầy đủ, logic. | Đánh giá quá lạc quan về tính khả thi kỹ thuật (Feasibility) mà bỏ qua chi phí triển khai. | Đưa thêm yếu tố chi phí hạ tầng và độ trễ vào phần rủi ro thực tế của nhóm. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**
**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Tôi nhận ra sự khác biệt rất lớn giữa một "ý tưởng nghe có vẻ hay trên lý thuyết" và một "vấn đề thực tế có điểm nghẽn đo lường được". Khi các bạn trong nhóm chia sẻ về bài toán tóm tắt paper khoa học hay gợi ý lịch trình cá nhân, tôi thấy hầu hết mọi người đều xuất phát từ mong muốn chủ quan của bản thân chứ chưa xác định được quy trình thao tác As-is thực tế đang gặp nút thắt ở bước nào. Lắng nghe góc nhìn của các bạn giúp tôi hiểu rằng một bài toán đáng giải quyết phải có một Actor cụ thể chịu nỗi đau lặp đi lặp lại hàng ngày, có tần suất đo đếm được và có thể kiểm chứng tại hiện trường chứ không thể dựa vào cảm tính. Bên cạnh đó, việc nghe các bài toán đa dạng còn giúp tôi rèn luyện tư duy phản biện: khi nghe một đề tài mới, phản xạ đầu tiên không phải là khen hay chê giải pháp, mà là truy vấn xem người gặp vấn đề đã thử tự giải quyết bằng cách thủ công nào chưa, và tại sao cách làm hiện tại vẫn gây lãng phí thời gian. Điều này giúp tôi học được cách bóc tách từng bước thao tác thực tế thay vì chỉ nhìn vào bức tranh chung chung, từ đó biết cách chọn lọc bài toán vừa sức và có tính thực tế cao nhất cho cả nhóm.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, nhóm tôi đã rơi vào bẫy "solution-first" ngay từ những phút đầu tiên khi vừa bước vào thảo luận CP3. Khi tôi vừa nhắc đến bãi giữ xe bị ùn tắc, các thành viên đã lập tức hào hứng bàn về việc "phải huấn luyện mô hình YOLOv8 kết hợp OCR nhận diện biển số" hoặc "lập trình một ứng dụng di động để sinh viên tự quét mã QR mở barie tự động". Nhóm chỉ giật mình nhận ra mình đang bị cuốn theo giải pháp công nghệ khi bắt tay vào vẽ lưu đồ quy trình hiện tại (As-is) theo yêu cầu của bài tập và đối mặt với câu hỏi cốt lõi: "Nếu hoàn toàn không dùng AI, người ta đang giải quyết điểm nghẽn này bằng cách nào và tại sao lại thất bại?". Lúc đó, chúng tôi nhận thấy mình chưa hề hiểu rõ quy trình vận hành thực tế của một ca trực cổng. Nhóm đã chủ động phanh lại, gác toàn bộ các từ khóa về "AI", "mô hình", "Deep Learning" sang một bên để tập trung phân tích hành vi của chú bảo vệ: từ lúc nhận thẻ, quẹt thẻ lên đầu đọc, ngước mắt nhìn camera đối chiếu, cho đến khâu gõ tay khi thẻ mờ. Việc quay lại mổ xẻ từng giây thao tác của con người đã giúp nhóm thoát khỏi cái bẫy công nghệ để nhìn ra bản chất thực sự của điểm nghẽn.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi đã hoàn toàn đổi ý về tính khả thi tuyệt đối của giải pháp tự động hóa sau khi bị nhóm chất vấn gay gắt ở CP3. Ban đầu khi trình bày Problem Card #1, tôi rất tự tin cho rằng chỉ cần lắp một camera thông minh nhận diện biển số tự động là có thể loại bỏ hoàn toàn thẻ từ và cho phép mở barie tự động cho xe đi qua mà không cần bất kỳ sự can thiệp nào của bảo vệ. Tuy nhiên, một bạn trong nhóm đã đặt câu hỏi phản biện rất thực tế: "Nếu vào ngày trời mưa to nước ngập bắn bẩn biển số, hoặc xe chở hàng cồng kềnh che mất biển, camera nhận diện sai thì barie có tự mở không, và nếu barie không mở thì cả đoàn xe phía sau sẽ xử lý ra sao?". Câu hỏi này làm tôi nhận ra góc nhìn của mình trước đó quá màu hồng và thiếu an toàn cho vận hành thực tế. Tôi đã thừa nhận thiếu sót và đồng ý đổi ý, từ bỏ tham vọng "tự động hóa 100%" để chuyển sang mô hình "Workflow có con người giám sát (Human-in-the-loop)". Tôi đã trực tiếp bổ sung cơ chế dự phòng (Fallback Mechanism) vào luồng To-be: quy định rõ AI chỉ đóng vai trò trích xuất gợi ý; nếu điểm tin cậy (confidence score) của hình ảnh dưới 90%, hệ thống sẽ lập tức giữ nguyên trạng thái quẹt thẻ thủ công để bảo vệ chủ động xử lý, đảm bảo an ninh không bao giờ bị tê liệt.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Kết quả kiểm chứng thực tế tại cổng bãi xe đã mang lại cho tôi sự bất ngờ rất lớn và làm đảo lộn hoàn toàn giả định ban đầu của tôi. Trước khi đi khảo sát, tôi luôn đinh ninh rằng nguyên nhân chính gây tắc nghẽn giờ cao điểm là do thiết bị đầu đọc thẻ từ quá cũ, phản hồi chậm khiến sinh viên mất nhiều thời gian quẹt thẻ. Nhưng khi trực tiếp đứng bấm giờ quan sát 20 lượt xe và trò chuyện với chú bảo vệ theo nguyên tắc The Mom Test, số liệu thực tế đã chỉ ra một sự thật hoàn toàn khác: thao tác chạm thẻ vào đầu đọc thực chất chỉ tốn từ 1 đến 2 giây và diễn ra rất mượt mà. Điểm nghẽn gây trễ cục bộ thực sự nằm ở khâu nhận thức và đối chiếu thị giác của bảo vệ: mắt chú phải liên tục đảo giữa biển số xe thật bên ngoài và hình ảnh chụp lúc xe vào trên màn hình máy tính để xem có khớp hay không. Nghiêm trọng hơn, khi gặp thẻ bị xước mã vạch hoặc biển số dính bụi khiến hệ thống cũ không hiện số, chú bảo vệ phải cúi người xuống nhìn kỹ từng số rồi gõ tay lại vào bàn phím, làm thời gian xử lý vọt lên từ 35 đến 50 giây cho một chiếc xe. Sự thật này chứng minh rằng nút thắt cổ chai không nằm ở phần cứng quẹt thẻ, mà nằm ở thao tác xác thực thủ công của con người.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó khăn và gây tranh luận căng thẳng nhất trong nhóm khi chấp bút viết bản Problem Statement v0 chính là việc khoanh vùng ranh giới an toàn (Boundary) và xác lập các chỉ số thành công (Success Metrics) định lượng. Rất dễ để cả nhóm sa đà vào việc viết những câu tuyên ngôn chung chung, mang tính khẩu hiệu như "giúp bãi gửi xe vận hành thông minh hơn" hoặc "giảm thiểu tối đa tình trạng ùn tắc giao thông". Nhóm đã phải liên tục gọt giũa từng câu chữ để ép các mục tiêu này về những con số có thể đo lường và kiểm chứng được: thời gian xử lý trung bình phải giảm cụ thể từ baseline 8 giây/xe xuống target dưới 2 giây/xe, và tỷ lệ bảo vệ phải can thiệp gõ tay thủ công phải giảm từ 15% xuống dưới mức 1%. Bên cạnh đó, việc xác định Boundary cũng là một thách thức lớn: nhóm phải tranh luận để đặt ra giới hạn nghiêm ngặt rằng AI chỉ được phép dừng lại ở mức hỗ trợ nhận diện và điền sẵn ký tự biển số vào ô đối chiếu, tuyệt đối không được cấp quyền tự động kích hoạt rơ-le mở barie nếu dữ liệu không khớp hoàn toàn với cơ sở dữ liệu thẻ. Việc tách bạch rõ ràng giữa quyền hạn của máy móc và trách nhiệm của con người chính là phần đòi hỏi sự cẩn trọng cao nhất.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu có cơ hội thực hiện lại bài lab này từ đầu, điều đầu tiên tôi muốn thay đổi là thúc đẩy cả nhóm bước chân ra hiện trường khảo sát thực tế ngay từ CP1, thay vì dành quá nhiều thời gian ngồi trong phòng học để suy đoán các giả định chủ quan trên bàn giấy. Việc có dữ liệu thực tế sớm sẽ giúp nhóm tiết kiệm được ít nhất một nửa thời gian tranh luận lý thuyết suông ở các bước sau. Đồng thời, tôi sẽ đóng vai trò phản biện quyết liệt hơn đối với nhóm ở phương án cơ sở không dùng AI (No-AI baseline). Cụ thể, tôi sẽ chất vấn nhóm mạnh mẽ hơn về việc liệu chỉ cần tối ưu hóa hạ tầng vật lý—chẳng hạn như việc kẻ lại vạch sơn phân luồng xe vào/ra riêng biệt, lắp thêm gờ giảm tốc định vị bánh xe đúng góc quay camera, hoặc chuyển đổi sang dùng thẻ tầm xa RFID—thì đã có thể giải quyết được tới 70% vấn đề ùn tắc với chi phí rẻ hơn và độ ổn định cao hơn rất nhiều hay chưa. Việc đặt các phương án giải pháp truyền thống lên bàn cân so sánh một cách sòng phẳng ngay từ đầu sẽ giúp nhóm đánh giá chính xác hơn về giá trị gia tăng thực sự (ROI) của việc ứng dụng công nghệ mới.
---

## 7. Tài liệu tham khảo

- Rob Fitzpatrick, *The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you* (áp dụng 3 nguyên tắc phỏng vấn kiểm chứng hành vi quá khứ thay vì hỏi ý kiến tương lai).
- Google PAIR, *People + AI Guidebook* (áp dụng 2 câu hỏi thiết kế: Augment vs. Automate và phân tích mức độ nghiêm trọng giữa Báo nhầm vs. Bỏ sót).
- Slack, "4 simple ways to save time with Workflow Builder": https://slack.com/resources/using-slack/4-simple-ways-to-save-time-with-workflow-builder (tham khảo case study về tự động hóa quy trình trả lời câu hỏi lặp lại).
- Notion, "Get answers about work content faster with Q&A / Notion Agent": https://www.notion.com/help/guides/get-answers-about-content-faster-with-q-and-a (tham khảo giải pháp trích xuất tri thức từ tài liệu sẵn có).
- Teresa Torres, *Continuous Discovery Habits* (tham khảo mô hình Opportunity Solution Tree - OST để liên kết Outcome với các Pain Point thực tế).
