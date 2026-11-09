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
| Pitch Problem Card | Trình bày 3 candidate (#13 bãi xe, #14 đặt lịch phòng khám, #15 tóm tắt paper PDF); trong đó candidate #15 được nhóm đưa vào shortlist top 3. | Đóng góp bài toán #15 vào vòng chấm điểm shortlist, đạt 24/35 điểm (xếp thứ 2 sau bài #5). |
| Phản biện bài của bạn khác | Đặt câu hỏi chất vấn candidate #5 của Cường và #8 của Tùng: *"Người hỏi có thực sự chịu tự tra cứu tài liệu không hay tiện tay là nhắn hỏi miệng, và gom deadline có trùng với việc sắp xếp ưu tiên sáng không?"* | Giúp nhóm nhận diện rào cản hành vi (Usability), thống nhất đưa giả định "người hỏi chịu tự tra" vào Assumption Map để kiểm chứng. |
| Nhận phản biện | Nhận phản biện về candidate #15: nguy cơ AI trích xuất sai số liệu từ bảng biểu trong paper rất cao và sinh viên chưa chắc có tần suất đọc paper hàng ngày. | Thống nhất loại bài #15 vì rủi ro hallucination cao và khó kiểm soát trong khuôn khổ lab, đồng thuận dồn lực cho bài #5. |
| Gom cluster / cây OST | Cùng bạn Tùng phân loại 18 candidate vào 4 cluster (A, B, C, D); tham gia gạch bỏ các ý "solution đội lốt opportunity" (như #3, #7, #14, #15). | Định hình Outcome chung và chọn nhánh Opportunity B (câu hỏi, yêu cầu lặp lại) làm hướng đi chính của nhóm. |
| Chọn candidate problem | Cùng nhóm chấm điểm shortlist trên 7 tiêu chí; bỏ phiếu chọn candidate #5 (30/35 điểm) làm bài toán chính thức. | Nhóm đạt đồng thuận 100%, ghi nhận quyết định hội tụ vào mục 1 và 2.4 của group_report.md. |
| Kiểm chứng (Phụ trách chính) | Xây dựng Assumption Map gồm 6 giả định; thiết kế và thu thập dữ liệu thô từ Survey 10 người (R1–R10: Kỹ sư phần mềm, Trưởng nhóm, Nhân viên, Sinh viên) theo The Mom Test. | Thu được dữ liệu thật: 10/10 từng bị hỏi lại, 7/10 mất từ 15 phút trở lên, phát hiện giả định 30–60 phút bị phản bác một phần (chỉ 3/10 người gặp). |
| Quy trình nhóm (Hỗ trợ) | Phối hợp với bạn Cường cung cấp dữ liệu survey để vẽ sơ đồ As-is (nút thắt bước 3) và thiết kế luồng To-be dựa trên trang FAQ dùng chung. | Giúp hoàn thiện bảng Before/After với số liệu baseline thực tế ~65 phút/tuần/người và mục tiêu giảm xuống ≤ 5 phút/lần. |
| Problem Statement | Tham gia hoàn thiện Problem Statement v0 và v1: đưa số liệu survey vào điều chỉnh baseline thời gian từ 30–60 phút về mức phổ biến 15–30 phút/lần. | Giúp nhóm có phát biểu bài toán trung thực, không bị phóng đại nỗi đau, xác định rõ ranh giới No AI. |
| Mức can thiệp AI | Phân tích ma trận độ mơ hồ × độ phức tạp; thống nhất chọn mức **No AI** (viết trang FAQ/tin ghim) vì bài toán nằm ở vùng mơ hồ thấp × vận hành đơn giản. | Giúp nhóm tránh lỗi lạm dụng AI, bám sát nguyên tắc của khóa: chỉ dùng AI khi có bằng chứng đo lường được giá trị vượt trội chi phí. |
| Quyết định | Phối hợp đánh giá 4 rủi ro sản phẩm (Value, Usability, Feasibility, Viability); biểu quyết đưa ra kết luận: **Go, phạm vi nhỏ (pilot FAQ 2 tuần)** kèm ngưỡng dừng định lượng. | Hoàn thiện mục 8 của group_report.md, thống nhất kế hoạch thử nghiệm 5 câu hỏi hay gặp nhất và đo lường trước khi quyết định bước tiếp. |
---

## 5. Dùng AI

| Ở bước nào? | AI giúp gì? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|
| CP1: Scan problem | Gợi ý mở rộng các góc nhìn về các vấn đề tốn thời gian trong học tập và làm việc kỹ thuật. | Đưa ra các ý tưởng chung chung, thiên về giải pháp công nghệ (như "làm app quản lý", "dùng AI tự động"). | Lọc lại và viết lại thành 8 bài toán xuất phát từ nỗi đau thật của người dùng, gắn với các bottleneck cụ thể. |
| CP2: Problem Card & Quy trình | Hỗ trợ cấu trúc Job Story và gợi ý các bước trong sơ đồ As-is cho 3 bài toán cá nhân. | Ước lượng thời gian và tần suất theo cảm tính, không có căn cứ đo lường thực tế. | Tự bổ sung các số liệu baseline ước lượng thận trọng và đánh dấu rõ các điểm cần ra thực địa khảo sát. |
| CP6: Mức can thiệp AI & Rủi ro | Đề xuất giải pháp xây dựng Chatbot RAG hoặc AI Agent tự động đọc tin nhắn và trả lời thay con người. | Bỏ qua rủi ro chi phí bản quyền, ảo giác số liệu (hallucination) và bỏ qua việc tài liệu gốc chưa được chuẩn hóa. | Cùng nhóm kiên quyết chọn mức **No AI** (trang FAQ dùng chung), chỉ ra rằng cần chuẩn hóa quy trình con người trước khi nghĩ đến công nghệ. |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Khi lắng nghe top 3 bài toán từ các bạn trong nhóm ở CP3 (gồm bài #5 giải thích câu hỏi lặp lại của Cường, bài #8 tổng hợp deadline của Tùng và bài #15 đọc paper PDF của tôi), tôi nhận ra sự khác biệt sâu sắc giữa một "ý tưởng nghe có vẻ hấp dẫn về mặt công nghệ" và một "nỗi đau công việc thực tế có thể đo lường được". Ban đầu, tôi khá tâm đắc với đề tài trích xuất thông tin từ paper PDF vì nó mang tính học thuật cao và ứng dụng trực tiếp mô hình ngôn ngữ lớn kết hợp RAG. Tuy nhiên, khi nhóm đặt lên bàn cân chấm điểm shortlist dựa trên 7 tiêu chí rõ ràng, bài #5 của bạn Cường đạt tới 30 điểm nhờ Actor rõ ràng và quy trình As-is dễ bóc tách, trong khi bài của tôi chỉ đạt 24 điểm do rủi ro ảo giác số liệu từ bảng biểu quá lớn. Lắng nghe các bạn giúp tôi hiểu rằng một bài toán sản phẩm tốt không nhất thiết phải dùng công nghệ phức tạp, mà quan trọng nhất là phải có một đối tượng chịu nỗi đau lặp đi lặp lại hàng ngày và có thể kiểm chứng tại hiện trường. Điều này giúp tôi học được cách gạt bỏ cái tôi cá nhân, nhìn nhận khách quan dựa trên dữ liệu để cùng nhóm chọn ra bài toán có tính khả thi và vừa sức nhất.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có, nhóm tôi đã rơi vào cái bẫy "solution-first" rất rõ ràng ngay sau khi vừa thống nhất chọn candidate #5 ở CP3. Phản xạ tự nhiên đầu tiên của các thành viên là lập tức đề xuất xây dựng một "Chatbot AI tích hợp RAG trên Slack hoặc Discord" hoặc "AI Agent tự động đọc tin nhắn trong kênh chat để sinh câu trả lời thay con người". Nhóm chỉ giật mình nhận ra mình đang bị cuốn theo giải pháp công nghệ khi bắt tay vào xây dựng bảng Assumption Map ở CP4 và đối mặt với câu hỏi cốt lõi: "Nếu nhóm chưa có sẵn tài liệu câu trả lời chuẩn xác thì mô hình AI sẽ lấy dữ liệu ở đâu để trả lời?". Lúc đó, chúng tôi nhận thấy nút thắt cổ chai thực sự không phải là thiếu công nghệ trả lời tự động, mà là thông tin đang nằm phân tán trong đầu từng người và chưa bao giờ được văn bản hóa. Nhóm đã chủ động phanh lại, gác toàn bộ các ý tưởng về chatbot hay AI Agent sang một bên để tập trung kiểm chứng xem người dùng thực sự bị hỏi những nội dung gì và một giải pháp phi công nghệ như trang FAQ dùng chung có giải quyết được vấn đề hay không.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Tôi đã đổi ý hoàn toàn về mức độ nghiêm trọng của bài toán sau khi thực hiện và phân tích kết quả khảo sát 10 người ở CP4. Ban đầu, khi bạn Cường trình bày Problem Card, bạn ấy ước lượng rằng mỗi lần phải giải thích lại một câu hỏi mất tới 30 đến 60 phút, và tôi cũng tin vào con số đó. Nhưng khi tôi trực tiếp phụ trách tổng hợp dữ liệu survey từ 10 người (bao gồm cả kỹ sư phần mềm, trưởng nhóm, nhân viên văn phòng và sinh viên), dữ liệu thực tế đã phản bác con số này: chỉ có đúng 3/10 người (chủ yếu là cấp trưởng nhóm) rơi vào khung 30–60 phút, trong khi phần lớn (4/10 người) chỉ mất khoảng 15–30 phút cho mỗi lần giải thích. Khi bạn Đông phản biện rằng con số 30–60 phút là bị phóng đại và yêu cầu tôi xem lại dữ liệu, tôi đã chấp nhận sự thật từ survey và đồng ý điều chỉnh lại toàn bộ baseline của nhóm về mức 15–30 phút/lần. Sự thay đổi này giúp nhóm nhìn nhận bài toán một cách trung thực, tránh được cái bẫy "thổi phồng nỗi đau" để cố tình biện minh cho việc áp dụng công nghệ đắt đỏ.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Điều làm tôi bất ngờ nhất khi kiểm chứng 10 đối tượng là sự mâu thuẫn giữa "thái độ ủng hộ" và "hành vi thực tế" theo đúng cảnh báo của cuốn sách The Mom Test. Khi được hỏi trong khảo sát, có tới 7/10 người trả lời "Có" và 3/10 người trả lời "Có thể" sẵn sàng dùng trang FAQ nếu nhóm tổng hợp sẵn, không có bất kỳ ai từ chối. Tuy nhiên, khi nhóm nghiên cứu các case study thực tế như Slack Workflow Builder và Notion Q&A ở mục 3.3, bài học rút ra là rào cản lớn nhất không nằm ở công cụ, mà nằm ở việc con người có chịu đọc tài liệu hay không: đa số người hỏi vẫn có thói quen tiện tay nhắn tin hỏi trực tiếp cho nhanh thay vì tự mở trang tài liệu ra đọc. Điều này làm tôi nhận ra một rủi ro cực lớn về mặt Usability: ý định nói ra trong khảo sát chỉ là bằng chứng yếu. Phát hiện này đã làm thay đổi hoàn toàn hướng tiếp cận của nhóm, từ việc định xây dựng một hệ thống phức tạp sang việc chỉ làm một bản pilot FAQ rất nhỏ trong 2 tuần cho 5 câu hỏi hay gặp nhất để đo lường hành vi tra cứu thật sự.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Điều khó khăn nhất khi hoàn thiện Problem Statement v0 và v1 là việc chuẩn hóa các chỉ số thành công (Success Metric) và khoanh vùng ranh giới (Boundary) sao cho có thể đo đếm được một cách sòng phẳng. Rất dễ để cả nhóm viết một câu tuyên ngôn chung chung như "giúp tiết kiệm thời gian hỏi đáp cho nhóm" hoặc "tăng hiệu suất làm việc của thành viên". Nhóm đã phải tranh luận rất nhiều từ số liệu survey để ép chỉ số về dạng định lượng rõ ràng: thời gian người được hỏi bỏ ra mỗi lần phải giảm từ 15–30 phút xuống còn ≤ 5 phút, và số lần bị hỏi lại câu đã có giảm từ 1–2 lần/tuần xuống còn ≤ 1 lần/2 tuần. Đồng thời, việc xác định Boundary cũng là một thách thức: nhóm phải quy định rõ ràng rằng giải pháp hiện tại chưa dùng AI; nếu sau này có áp dụng thì AI chỉ được phép tìm trong các mục FAQ đã được con người duyệt, tuyệt đối không được tự ý sinh câu trả lời mới ngoài tài liệu để tránh rủi ro trả lời sai với giọng chắc chắn (báo nhầm). Việc vạch rõ ranh giới trách nhiệm giữa con người và công nghệ chính là phần đòi hỏi sự cẩn trọng cao nhất.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Nếu có cơ hội làm lại bài lab này từ đầu, điều đầu tiên tôi muốn thay đổi là thúc đẩy cả nhóm thực hiện phỏng vấn sâu trực tiếp 3–5 người thay vì chỉ phát form khảo sát trắc nghiệm nhanh 10 người. Việc phỏng vấn trực tiếp theo phương pháp The Mom Test sẽ giúp chúng tôi lắng nghe được những câu chuyện cụ thể về lần gần nhất họ bị hỏi lại, từ đó trích dẫn được các câu nói nguyên văn làm bằng chứng thuyết phục hơn. Bên cạnh đó, tôi sẽ đóng vai trò phản biện quyết liệt hơn ngay từ đầu ở bước đề xuất giải pháp có AI. Khi nghiên cứu tính năng Notion Agent và Slack AI, tôi nhận thấy chi phí bản quyền và rủi ro hallucination là rất lớn nếu tài liệu nguồn chưa hoàn thiện. Tôi sẽ chất vấn mạnh mẽ hơn để nhóm kiên quyết giữ vững mức độ can thiệp là No AI ngay từ đầu, tập trung 100% nguồn lực vào việc xây dựng quy trình gom và duy trì 5 câu hỏi thường gặp nhất thay vì mất thời gian thảo luận về các kiến trúc chatbot phức tạp.

**6.7. Hiểu bài:**

Chuỗi logic của bài toán nhóm được triển khai chặt chẽ qua 6 bước:
1. **Problem:** Người được hỏi (kỹ sư, nhân viên, sinh viên) thường xuyên phải ngắt quãng công việc để giải thích lại cùng một câu hỏi lặp lại cho đồng nghiệp/bạn học khoảng 2 lần/tuần, gây lãng phí trung bình ~65 phút/tuần/người.
2. **Quy trình:** Bóc tách quy trình As-is (người hỏi gặp vướng -> nhắn tin hỏi trực tiếp -> người được hỏi dừng việc giải thích từ đầu mất 15–30 phút) và quy trình To-be (người hỏi tự tra cứu trang FAQ/tin ghim trước -> chỉ hỏi trực tiếp khi chưa có trong tài liệu -> người được hỏi trả lời và bổ sung câu mới vào FAQ).
3. **Metric:** Đo lường bằng việc giảm thời gian mỗi lần bị hỏi lại từ khoảng 15–30 phút xuống ≤ 5 phút, và tần suất bị hỏi lại câu đã có giảm từ 1–2 lần/tuần xuống ≤ 1 lần/2 tuần.
4. **Boundary:** Ranh giới an toàn xác định chưa dùng AI; nếu sau này thêm AI thì chỉ được tìm trong các mục FAQ đã duyệt, câu không có trong FAQ phải chuyển cho con người xử lý chứ không tự trả lời ngoài tài liệu.
5. **Mức can thiệp AI:** Chọn mức **No AI** (viết trang FAQ dùng chung hoặc ghim tin nhắn) vì bài toán nằm ở vùng mơ hồ thấp × vận hành đơn giản, chưa có bằng chứng cho thấy cần tới AI.
6. **Quyết định:** Thống nhất quyết định **Go, phạm vi nhỏ (pilot FAQ trong 2 tuần)** cho 5 câu hỏi phổ biến nhất, kèm ngưỡng dừng: nếu sau 2 tuần số lần bị hỏi lại câu đã có vẫn ≥ 1 lần/tuần thì xem lại cách trình bày; nếu sau 4 tuần không giảm thì dừng phương án FAQ.
---

## 7. Tài liệu tham khảo

- Slack, "4 simple ways to save time with Workflow Builder": [https://slack.com/resources/using-slack/4-simple-ways-to-save-time-with-workflow-builder](https://slack.com/resources/using-slack/4-simple-ways-to-save-time-with-workflow-builder) (tham khảo case study giải pháp No AI dùng emoji kích hoạt tin nhắn dẫn tới FAQ).
- Notion, "Get answers about work content faster with Q&A / Notion Agent": [https://www.notion.com/help/guides/get-answers-about-content-faster-with-q-and-a](https://www.notion.com/help/guides/get-answers-about-content-faster-with-q-and-a) (tham khảo bài học: công cụ hỏi đáp AI chỉ có ích khi tài liệu nguồn đã được chuẩn hóa).
- Slack, "Slack AI features & AI assistants": [https://slack.com/intl/en-au/features/ai](https://slack.com/intl/en-au/features/ai) (phân tích hạn chế về chi phí bản quyền và tính độc lập của số liệu nhà cung cấp).
- Rob Fitzpatrick, *The Mom Test* (áp dụng 3 nguyên tắc phỏng vấn kiểm chứng hành vi quá khứ thay vì hỏi ý kiến tương lai; phát hiện mâu thuẫn giữa ý định và hành vi tra FAQ).
- Google PAIR, *People + AI Guidebook* (áp dụng 2 câu hỏi thiết kế: Augment vs. Automate và phân tích mức độ nghiêm trọng giữa Báo nhầm vs. Bỏ sót đối với câu trả lời sai lệch).
