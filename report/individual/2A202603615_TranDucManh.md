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
| Pitch Problem Card | Trình bày Problem Card #1 (Bãi giữ xe) và phân tích các bài toán cá nhân đã chuẩn bị ở CP2. | Đóng góp thêm góc nhìn thực tế về quy trình có yếu tố lặp lại cao vào danh sách thảo luận của nhóm. |
| Phản biện bài của bạn khác | Đặt câu hỏi phản biện: "Liệu bài toán này dùng phương án phân nhánh thủ công (Rule-based) đã giải quyết được chưa mà phải cần đến AI?" | Giúp nhóm nhận diện rõ ranh giới giữa tự động hóa thông thường và bài toán cần can thiệp thông minh. |
| Nhận phản biện | Tiếp nhận câu hỏi về tính khả thi của dữ liệu đầu vào và các trường hợp ngoại lệ (Edge cases). | Đề xuất giải pháp dự phòng (fallback) để quy trình không bị gián đoạn khi hệ thống gặp lỗi. |
| Gom cluster / cây OST | Cùng nhóm phân loại các ý kiến khảo sát thành 2 nhánh chính: Tốc độ xử lý quy trình và Trải nghiệm của người dùng trực tiếp. | Giúp định hình cấu trúc sơ đồ cây cơ hội (Opportunity Solution Tree) của nhóm. |
| Chọn candidate problem | Thảo luận, bỏ phiếu cùng nhóm và đồng thuận chốt bài toán được chọn ghi trong group_report.md. | Nhóm thống nhất 100% hướng đi để tiến hành khảo sát thực tế ở CP4. |
| Kiểm chứng / research | Tham gia xây dựng câu hỏi phỏng vấn thực tế và khảo sát đối tượng chịu ảnh hưởng trực tiếp (Actor). | Thu thập bằng chứng thực tế (survey/interview evidence) đưa vào thư mục assets của nhóm. |
| Quy trình nhóm | Đóng góp hoàn thiện các bước trong luồng As-is (hiện tại) và phác thảo các điểm nghẽn (bottlenecks). | Giúp vẽ sơ đồ quy trình To-be rõ ràng, làm rõ bước nào người làm và bước nào máy hỗ trợ. |
| Problem Statement | Cùng nhóm rà soát câu Problem Statement v0: kiểm tra Actor, Metric đo lường và ranh giới (Boundary). | Đảm bảo các chỉ số đo lường (Success metrics) có baseline và target định lượng rõ ràng. |
| Mức can thiệp AI | Phân tích 4 mức (No AI, Rule, Workflow, Agent) và đánh giá 4 rủi ro sản phẩm (Value, Usability, Feasibility, Viability). | Thống nhất mức can thiệp phù hợp nhất, tránh đưa AI vào những khâu không cần thiết. |
| Quyết định | Tham gia thảo luận và chốt quyết định cuối cùng của nhóm (ghi tại group_report.md và TEAM.md). | Báo cáo nhóm có lập luận chặt chẽ, đầy đủ căn cứ thực nghiệm. |
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
Tôi nhận ra sự khác biệt rất lớn giữa một "ý tưởng nghe có vẻ hay" và một "vấn đề thực tế có điểm nghẽn đo lường được". Khi các bạn chia sẻ về bài toán tóm tắt paper hay gợi ý lịch trình, tôi thấy hầu hết mọi người đều xuất phát từ mong muốn cá nhân chứ chưa chỉ ra được bước nào trong quy trình hiện tại đang gây tốn thời gian nhất. Lắng nghe các góc nhìn đa dạng giúp tôi học được cách bóc tách từng bước thao tác thực tế thay vì chỉ nhìn vào bức tranh chung chung.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Có, ngay ở giai đoạn đầu cả nhóm đã lập tức nghĩ đến việc "xây dựng mô hình AI nhận diện biển số xe máy" hoặc "làm app đặt lịch tự động". Nhóm chỉ nhận ra mình bị solution-first khi bắt tay vào vẽ quy trình As-is và đối mặt với câu hỏi: "Nếu không có AI thì người ta đang giải quyết bằng cách nào?". Nhóm đã phải phanh lại, quay về phân tích kỹ bước quẹt thẻ và đối chiếu mắt thường của chú bảo vệ để tìm ra điểm nghẽn thực sự trước khi bàn đến công nghệ.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi đã đổi ý về giả định giải pháp tuyệt đối. Ban đầu khi pitch bài bãi xe, tôi nghĩ chỉ cần lắp camera AI nhận diện tự động là barie có thể mở ngay mà không cần thẻ từ. Nhưng khi nhóm phản biện về trường hợp trời mưa bão, biển số bẩn, hoặc người lạ vào gửi xe, tôi nhận ra AI không thể thay thế 100%. Tôi đã đổi ý và bổ sung cơ chế fallback: chỉ áp dụng AI hỗ trợ trích xuất nhanh, nếu độ tin cậy dưới 90% thì hệ thống lập tức quay về quy trình quẹt thẻ thủ công.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Điều làm tôi bất ngờ nhất là thời gian trễ thực tế không nằm ở khâu quẹt thẻ (chỉ mất 1–2 giây), mà nằm ở khâu mắt thường của bảo vệ phải ngước lên nhìn màn hình rồi nhìn xuống xe để kiểm tra biển số, đặc biệt khi thẻ mờ thì phải gõ tay mất 30–60 giây. Trước đó, tôi cứ tưởng chỉ cần đầu đọc thẻ xịn hơn là giải quyết được, nhưng kiểm chứng cho thấy thao tác đối chiếu của con người mới là nút thắt cổ chai.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất là xác định ranh giới (Boundary) và chỉ số thành công (Success Metric) có thể đo lường được. Rất dễ rơi vào cái bẫy viết mục tiêu chung chung như "giúp bãi xe thông minh hơn" hoặc "giảm ùn tắc". Nhóm đã phải tranh luận rất nhiều để ép con số về dạng định lượng rõ ràng: giảm thời gian xử lý từ 8s xuống < 2s/xe và khoanh vùng boundary là AI chỉ gợi ý số đọc được chứ không được tự ý quyết định mở barie nếu dữ liệu không khớp.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, tôi sẽ yêu cầu nhóm đi khảo sát thực địa sớm hơn ngay từ CP1 thay vì ngồi suy đoán trên bàn giấy. Đồng thời, tôi sẽ phản biện nhóm quyết liệt hơn ở các phương án không dùng AI (No-AI baseline), ví dụ như việc chỉ cần kẻ lại vạch phân làn xe ra/vào hợp lý hay thay đầu đọc thẻ tầm xa có thể đã giải quyết được 70% vấn đề mà chi phí rẻ hơn rất nhiều so với việc dựng một hệ thống camera thông minh.

**6.7. Hiểu bài:** 
Chuỗi logic của bài toán nhóm được triển khai chặt chẽ qua 6 bước:
1. **Problem:** Giờ cao điểm bãi xe bị ùn tắc cục bộ do bảo vệ mất nhiều thời gian quan sát đối chiếu biển số bằng mắt và gõ tay lại khi thẻ bị trầy xước.
2. **Quy trình:** Tách rõ luồng As-is (khách quẹt thẻ $\to$ bảo vệ nhìn màn hình đối chiếu $\to$ gõ tay nếu lỗi $\to$ bấm mở) và To-be (xe vào $\to$ camera quét OCR biển số tự khớp với thẻ $\to$ bảo vệ chỉ xác nhận ngoại lệ).
3. **Metric:** Đo lường trực tiếp bằng thời gian xử lý qua cổng giảm từ 8s xuống dưới 2s/xe, và tỷ lệ bảo vệ phải can thiệp gõ tay giảm từ 15% xuống dưới 1%.
4. **Boundary:** Ranh giới an toàn quy định AI chỉ thực hiện nhận diện và so khớp ký tự; AI không được phép tự động kích hoạt mở barie khi độ tin cậy dưới ngưỡng quy định.
5. **Mức can thiệp AI:** Chọn mức **Workflow** (quy trình cố định có AI hỗ trợ một mắt xích nhận diện hình ảnh), không dùng Agent vì bài toán mang tính lặp lại cố định, không cần ra quyết định tự chủ đa bước.
6. **Quyết định:** Kết luận **Not Yet** (hoặc **Go** có điều kiện), vì cần thêm thời gian thử nghiệm thực tế độ chính xác của camera trong điều kiện ban đêm và thời tiết xấu trước khi đầu tư lắp đặt đồng loạt.
---

## 7. Tài liệu tham khảo

- Rob Fitzpatrick, *The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you* (áp dụng 3 nguyên tắc phỏng vấn kiểm chứng hành vi quá khứ thay vì hỏi ý kiến tương lai).
- Google PAIR, *People + AI Guidebook* (áp dụng 2 câu hỏi thiết kế: Augment vs. Automate và phân tích mức độ nghiêm trọng giữa Báo nhầm vs. Bỏ sót).
- Slack, "4 simple ways to save time with Workflow Builder": https://slack.com/resources/using-slack/4-simple-ways-to-save-time-with-workflow-builder (tham khảo case study về tự động hóa quy trình trả lời câu hỏi lặp lại).
- Notion, "Get answers about work content faster with Q&A / Notion Agent": https://www.notion.com/help/guides/get-answers-about-content-faster-with-q-and-a (tham khảo giải pháp trích xuất tri thức từ tài liệu sẵn có).
- Teresa Torres, *Continuous Discovery Habits* (tham khảo mô hình Opportunity Solution Tree - OST để liên kết Outcome với các Pain Point thực tế).
