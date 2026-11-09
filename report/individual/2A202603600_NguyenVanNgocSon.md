# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Văn Ngọc Sơn
- MSSV:2A202603600
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: abc404
- Link repo nhóm: https://github.com/dongtranquoc951/K5-L3-Day02-Nhomabc404-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi chỉnh sửa prompt của tính năng sinh câu trả lời tự động, tôi muốn nhận ra những câu hỏi trước đây trả lời đúng nhưng bản mới lại trả lời sai, để tránh đưa lỗi vào phiên bản tiếp theo. | AI Engineer, QA, nhóm sản phẩm | 2 lần sửa/tuần, 20 test case/lần, 62 phút/lần → 124 phút/tuần |
| 2 | Tốn thời gian | Khi job huấn luyện hoặc tinh chỉnh mô hình thất bại, tôi muốn xác định bước lỗi và nguyên nhân cụ thể, để hạn chế các lần chạy lại không cần thiết. | AI Engineer, kỹ sư hạ tầng | 2 sự cố/tháng, 60 phút/sự cố để phân tích và xử lý → 120 phút/tháng |
| 3 | Lặp lại | Khi hoàn thành một lần thử nghiệm mô hình, tôi muốn đối chiếu metric và cấu hình với các lần chạy trước, để nhận biết thay đổi nào thực sự cải thiện kết quả. | AI Engineer, Tech Lead | 3 thí nghiệm/tuần, 18 phút/lần đối chiếu notebook, metric và cấu hình → 54 phút/tuần |
| 4 | Pain từ người khác | Khi PM/BA hỏi hệ thống đang sai ở những tình huống nào, tôi muốn cung cấp các nhóm lỗi, ví dụ và tần suất có thể đối chiếu, để nhóm chọn đúng việc cần sửa trước. | PM/BA, AI Engineer | 3 yêu cầu/tuần, 66 phút/yêu cầu để xuất case, phân nhóm và báo cáo → 198 phút/tuần |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi đánh giá kỹ thuật mới từ tài liệu nghiên cứu và kết quả thử nghiệm, tôi muốn hiểu điều kiện áp dụng và giới hạn của kỹ thuật đó, để tránh chọn hướng không phù hợp với dữ liệu đang có. | AI Engineer, Tech Lead | 2 tài liệu chuyên sâu/tháng, 95 phút/tài liệu để đọc và đối chiếu điều kiện áp dụng → 190 phút/tháng |
| 6 | Lặp lại | Khi nhận một lô dữ liệu đã gán nhãn, tôi muốn xác định những nhãn thiếu nhất quán trước khi dùng để huấn luyện hoặc kiểm thử, để giảm rủi ro đánh giá sai chất lượng mô hình. | AI Engineer, người gán nhãn | 1 batch/2 tuần gồm 250 mẫu; rà soát 50 mẫu trong 45 phút, phát hiện 6 nhãn cần kiểm tra lại |
| 7 | Pain từ người khác | Khi đồng nghiệp mới thiết lập môi trường chạy dự án, tôi muốn họ hiểu lỗi cấu hình hoặc phân quyền đang gặp, để không phải hỏi lặp lại và có thể bắt đầu công việc. | Thành viên mới, AI Engineer hỗ trợ | 2 người mới/quý, 60 phút hỗ trợ/người, trung bình 4 câu hỏi lặp/người |
| 8 | Tốn thời gian | Khi review thay đổi của pipeline xử lý dữ liệu, tôi muốn phát hiện biến đổi ngoài dự kiến ở trường dữ liệu và phân phối mẫu, để tránh đưa sai lệch vào kết quả mô hình. | AI Engineer reviewer, nhóm dữ liệu | 2 pull request/tuần, 35 phút/PR để kiểm tra schema, thống kê và kết quả → 70 phút/tuần |
| 9 | Lặp lại | Khi chuẩn bị cuộc họp cập nhật tiến độ thử nghiệm, tôi muốn tập hợp kết quả, cấu hình và vấn đề còn tồn tại ở một chỗ, để người phụ trách kỹ thuật quyết định bước tiếp theo. | AI Engineer, Tech Lead | 1 báo cáo/tuần, 42 phút/báo cáo, đối chiếu 3 nguồn kết quả |
| 10 | Pain từ người khác | Khi bộ phận vận hành báo hệ thống trả lời khách hàng cung cấp thông tin sai, tôi muốn nhận đủ câu hỏi gốc, ngữ cảnh và kết quả để tái hiện lỗi, để không phải trao đổi bổ sung nhiều lượt. | Bộ phận vận hành, AI Engineer | 5 báo lỗi/tuần, 3 báo lỗi thiếu ngữ cảnh, 12 phút bổ sung thông tin/báo lỗi thiếu → 36 phút/tuần |

**Ghi chú CP1:** Tôi dùng AI để gợi ý danh sách candidate theo vai trò AI Engineer, sau đó tự chọn giữ những việc mình làm, tự điền số liệu, và sửa Job Story #10 (bỏ chữ "chatbot" để Job Story mô tả vấn đề, không gắn với công nghệ).## 2. Scan problem (CP1)

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi chỉnh sửa prompt của tính năng sinh câu trả lời tự động, tôi muốn nhận ra những câu hỏi trước đây trả lời đúng nhưng bản mới lại trả lời sai, để tránh đưa lỗi vào phiên bản tiếp theo. | AI Engineer, QA, nhóm sản phẩm | 2 lần sửa/tuần, 20 test case/lần, 62 phút/lần → 124 phút/tuần |
| 2 | Tốn thời gian | Khi job huấn luyện hoặc tinh chỉnh mô hình thất bại, tôi muốn xác định bước lỗi và nguyên nhân cụ thể, để hạn chế các lần chạy lại không cần thiết. | AI Engineer, kỹ sư hạ tầng | 2 sự cố/tháng, 60 phút/sự cố để phân tích và xử lý → 120 phút/tháng |
| 3 | Lặp lại | Khi hoàn thành một lần thử nghiệm mô hình, tôi muốn đối chiếu metric và cấu hình với các lần chạy trước, để nhận biết thay đổi nào thực sự cải thiện kết quả. | AI Engineer, Tech Lead | 3 thí nghiệm/tuần, 18 phút/lần đối chiếu notebook, metric và cấu hình → 54 phút/tuần |
| 4 | Pain từ người khác | Khi PM/BA hỏi hệ thống đang sai ở những tình huống nào, tôi muốn cung cấp các nhóm lỗi, ví dụ và tần suất có thể đối chiếu, để nhóm chọn đúng việc cần sửa trước. | PM/BA, AI Engineer | 3 yêu cầu/tuần, 66 phút/yêu cầu để xuất case, phân nhóm và báo cáo → 198 phút/tuần |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi đánh giá kỹ thuật mới từ tài liệu nghiên cứu và kết quả thử nghiệm, tôi muốn hiểu điều kiện áp dụng và giới hạn của kỹ thuật đó, để tránh chọn hướng không phù hợp với dữ liệu đang có. | AI Engineer, Tech Lead | 2 tài liệu chuyên sâu/tháng, 95 phút/tài liệu để đọc và đối chiếu điều kiện áp dụng → 190 phút/tháng |
| 6 | Lặp lại | Khi nhận một lô dữ liệu đã gán nhãn, tôi muốn xác định những nhãn thiếu nhất quán trước khi dùng để huấn luyện hoặc kiểm thử, để giảm rủi ro đánh giá sai chất lượng mô hình. | AI Engineer, người gán nhãn | 1 batch/2 tuần gồm 250 mẫu; rà soát 50 mẫu trong 45 phút, phát hiện 6 nhãn cần kiểm tra lại |
| 7 | Pain từ người khác | Khi đồng nghiệp mới thiết lập môi trường chạy dự án, tôi muốn họ hiểu lỗi cấu hình hoặc phân quyền đang gặp, để không phải hỏi lặp lại và có thể bắt đầu công việc. | Thành viên mới, AI Engineer hỗ trợ | 2 người mới/quý, 60 phút hỗ trợ/người, trung bình 4 câu hỏi lặp/người |
| 8 | Tốn thời gian | Khi review thay đổi của pipeline xử lý dữ liệu, tôi muốn phát hiện biến đổi ngoài dự kiến ở trường dữ liệu và phân phối mẫu, để tránh đưa sai lệch vào kết quả mô hình. | AI Engineer reviewer, nhóm dữ liệu | 2 pull request/tuần, 35 phút/PR để kiểm tra schema, thống kê và kết quả → 70 phút/tuần |
| 9 | Lặp lại | Khi chuẩn bị cuộc họp cập nhật tiến độ thử nghiệm, tôi muốn tập hợp kết quả, cấu hình và vấn đề còn tồn tại ở một chỗ, để người phụ trách kỹ thuật quyết định bước tiếp theo. | AI Engineer, Tech Lead | 1 báo cáo/tuần, 42 phút/báo cáo, đối chiếu 3 nguồn kết quả |
| 10 | Pain từ người khác | Khi bộ phận vận hành báo hệ thống trả lời khách hàng cung cấp thông tin sai, tôi muốn nhận đủ câu hỏi gốc, ngữ cảnh và kết quả để tái hiện lỗi, để không phải trao đổi bổ sung nhiều lượt. | Bộ phận vận hành, AI Engineer | 5 báo lỗi/tuần, 3 báo lỗi thiếu ngữ cảnh, 12 phút bổ sung thông tin/báo lỗi thiếu → 36 phút/tuần |

**Ghi chú CP1:** Tôi dùng AI để gợi ý danh sách candidate theo vai trò AI Engineer, sau đó tự chọn giữ những việc mình làm, tự điền số liệu, và sửa Job Story #10 (bỏ chữ "chatbot" để Job Story mô tả vấn đề, không gắn với công nghệ).

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi …, tôi muốn …, để … |
| Actor | |
| Thời điểm / bối cảnh | |
| Quy trình hiện tại (3–7 bước) | |
| Bottleneck (bước nào, mất bao nhiêu phút) | |
| Impact (nếu không giải thì sao) | |
| Success metric (baseline → target) | |
| Phương án không dùng AI | |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:

```text

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi …, tôi muốn …, để … |
| Actor | |
| Thời điểm / bối cảnh | |
| Quy trình hiện tại (3–7 bước) | |
| Bottleneck (bước nào, mất bao nhiêu phút) | |
| Impact (nếu không giải thì sao) | |
| Success metric (baseline → target) | |
| Phương án không dùng AI | |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | No AI / Rule / Workflow / Agent / Chưa biết |

Quy trình nháp hiện tại:

```text

```

## 3. Top 3 Problem Cards (CP2)

| Rank | Problem | Vì sao chọn | Điều cần kiểm chứng |
|---:|---|---|---|
| 1 | #1 — Kiểm thử hồi quy sau khi sửa prompt | Lặp lại hằng tuần, quy trình rõ, đo được thời gian từng bước, so sánh được No AI / Rule / Workflow | Tiêu chí chấm đã được viết thành rubric chưa? Công cụ eval có sẵn đã giải được bước nào? Kỹ sư khác có cùng pain không? |
| 2 | #2 — Phân tích job training/fine-tuning thất bại | Có log để truy nguyên, đo riêng được công sức người và tài nguyên máy | Lỗi thường gặp do code/cấu hình hay do hạ tầng? Log đã có cấu trúc chưa? Công cụ theo dõi run đã giải được bước nào? |
| 3 | #4 — Phân loại lỗi để phản hồi PM/BA | Pain đến từ người khác, có yêu cầu lặp lại hằng tuần | PM thật sự dùng báo cáo để quyết định gì? Đã có taxonomy cố định chưa? Có thể gắn nhãn ngay lúc nhận báo lỗi không? Dữ liệu có thông tin cá nhân không? |

### Problem Card #1 — Kiểm thử hồi quy sau khi sửa prompt

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi chỉnh sửa prompt của tính năng sinh câu trả lời tự động, tôi muốn nhận ra những câu hỏi trước đây trả lời đúng nhưng bản mới lại trả lời sai, để tránh đưa lỗi vào phiên bản tiếp theo. |
| **Actor** | Tôi là AI Engineer phụ trách kiểm thử prompt cho tính năng sinh câu trả lời tự động từ tài liệu hỗ trợ nội bộ; QA hoặc người phụ trách sản phẩm nhận kết quả kiểm thử. |
| **Thời điểm / bối cảnh** | Trước khi đề xuất phát hành prompt mới, sau một bug report hoặc yêu cầu đổi hành vi trả lời. |
| **Input → Output** | Input: prompt trước và sau khi sửa, bộ 20 test case, tiêu chí pass/fail, kết quả baseline. Output: danh sách case pass/fail, các regression cần xem lại, đề xuất có/không chuyển bước phát hành. |
| **Quy trình hiện tại** | 1. Nhận yêu cầu, sửa prompt (10') → 2. Chọn/kiểm tra case (6') → 3. Chạy test (10') → **4. Đọc và chấm 20 output (27')** → 5. Ghi bảng (3') → 6. So với baseline (4') → 7. Kết luận (2') |
| **Bottleneck** | Bước 4, đọc và chấm output: **27/62 phút** (43,5% tổng thời gian). |
| **Impact** | **62 phút/lần × 2 lần/tuần = 124 phút/tuần**; 20 case/lần gồm cả câu trả lời xác định và câu trả lời mở. Rủi ro regression lọt tới người dùng là giả định, sẽ kiểm chứng ở CP4. |
| **Success metric** | Giảm thời gian một chu trình sửa và kiểm prompt (bước 1–7) từ **62 xuống ≤40 phút/lần**, đo trên 4 lần cập nhật prompt liên tiếp. **Guardrail:** không bỏ sót regression nào trong tập regression đã được QA/AI Engineer xác nhận (ghi rõ số case trong tập); mọi case bị đánh trượt đều được người kiểm lại. |
| **Phương án không dùng AI** | (1) Viết rubric pass/fail theo từng loại câu hỏi. (2) Script chạy batch, so khớp/regex cho câu trả lời có đáp án cố định. (3) Thử công cụ eval có sẵn (promptfoo, LangSmith) cho bước chạy test và so baseline. |
| **Hướng can thiệp AI cần kiểm chứng** | Chỉ chấm sơ bộ các case đầu ra mở, theo rubric đã viết. Người kiểm mọi case bị đánh trượt hoặc không chắc chắn. AI không quyết định phát hành. |
| **Cảm nhận nhanh** | **Rule → cân nhắc Workflow.** Rule cho đầu ra cố định; chỉ thử Workflow nếu sau khi có rubric vẫn còn nhiều case mở phải đọc tay. Không cần Agent. |

```text
QUY TRÌNH HIỆN TẠI #1 — TỔNG 62 PHÚT/LẦN

[1 Sửa prompt: 10'] → [2 Chuẩn bị case: 6'] → [3 Chạy test: 10']
→ [4 Đọc và chấm output: 27'] ← BOTTLENECK
→ [5 Ghi kết quả: 3'] → [6 So baseline: 4'] → [7 Kết luận: 2']
```

**AI phản biện Card #1**

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Kiểm thử hồi quy prompt đã có nhiều công cụ eval giải sẵn (promptfoo, LangSmith, OpenAI Evals). Có thể problem thật chỉ là "team chưa áp dụng công cụ có sẵn" | Đồng ý | Thêm "thử công cụ eval có sẵn" vào phương án không dùng AI; đưa vào research CP4 |
| Chấm output lâu có thể chỉ là triệu chứng của việc tiêu chí đúng/sai chưa được viết ra. Tự động hóa việc chấm khi chưa có rubric chỉ là tự động hóa sự thiếu nhất quán | Đồng ý | Thêm bước "viết rubric pass/fail" vào phương án No AI, làm trước mọi bước dùng AI; thêm vào điều cần kiểm chứng |
| Impact chỉ tính thời gian (124 phút/tuần cho 1 người) là nhỏ. Giá trị lớn hơn là tránh regression lọt tới người dùng, nhưng chưa có bằng chứng lỗi đã lọt | Đồng ý một phần | Giữ thời gian làm chỉ số chính; ghi rủi ro chất lượng là giả định cần kiểm chứng ở CP4 |
| Actor chỉ có bản thân tôi; chưa biết AI engineer hay QA khác có cùng pain không | Đồng ý | Thêm giả định "kỹ sư khác cũng kiểm prompt thủ công" để phỏng vấn ở CP4 |
| Bộ 20 case quá nhỏ: chỉ tiêu "≥95% phát hiện regression" tính trên vài case thì chỉ cần sai 1 case là tụt dưới 95% | Đồng ý | Đổi guardrail thành "không bỏ sót regression nào trong tập đã xác nhận" và ghi rõ cỡ tập |
| Vì sao không để LLM chấm cả 20 output rồi tự cho phép hoặc chặn phát hành? | Không đồng ý | LLM chấm cũng có sai lệch riêng và cần hiệu chỉnh với người chấm; giữ boundary "người quyết định phát hành, AI chỉ chấm sơ bộ case mở" |
| Domain kỹ thuật, thành viên nhóm không làm AI có thể không hiểu "regression prompt" | Đồng ý một phần | Giữ card; chuẩn bị 1 ví dụ câu trả lời trước và sau khi sửa prompt để pitch dễ hiểu |

### Problem Card #2 — Phân tích nguyên nhân job training/fine-tuning thất bại

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi job huấn luyện hoặc tinh chỉnh mô hình thất bại, tôi muốn xác định bước lỗi và nguyên nhân cụ thể, để hạn chế các lần chạy lại không cần thiết. |
| **Actor** | Tôi là AI Engineer theo dõi các lần chạy fine-tuning trên máy chủ GPU của nhóm. Phạm vi card chỉ gồm lỗi do code, cấu hình và dữ liệu; lỗi hạ tầng (node, quota) chuyển kỹ sư hạ tầng. |
| **Thời điểm / bối cảnh** | Sau khi dashboard hoặc log báo job thất bại, trước khi quyết định chỉnh cấu hình và chạy lại. |
| **Input → Output** | Input: run ID, log, cấu hình, phiên bản dữ liệu. Output: vị trí lỗi, nguyên nhân có dẫn chứng, bản sửa và quyết định chạy lại. |
| **Quy trình hiện tại** | 1. Nhận cảnh báo (4') → 2. Mở run, tải log (7') → **3. Tìm dòng/bước lỗi (21')** → 4. Đối chiếu cấu hình, xác minh (13') → 5. Sửa lỗi (12') → 6. Kiểm tra, chuẩn bị chạy lại (3') |
| **Bottleneck** | Bước 3, tìm vùng log liên quan: **21/60 phút** (35% tổng thời gian). |
| **Impact** | **60 phút/sự cố × 2 sự cố/tháng = 120 phút/tháng**. Chi phí GPU-giờ chạy lại theo dõi riêng, không cộng vào thời gian của kỹ sư. |
| **Success metric** | (1) Thời gian từ khi nhận cảnh báo đến khi sẵn sàng chạy lại (bước 1–6) giảm từ **60 xuống ≤35 phút/sự cố**, đánh giá trên các sự cố cũ tái hiện được từ log đã lưu. (2) Số job hỏng do lỗi có thể chặn trước khi chạy giảm, đếm hằng tháng. **Guardrail:** mọi nguyên nhân được đề xuất phải trỏ đến đoạn log hoặc cấu hình kiểm tra được; kết luận cuối do kỹ sư xác nhận. |
| **Phương án không dùng AI** | (1) Structured logging, log level và mã lỗi. (2) Kiểm tra trước khi chạy: validate config, schema dữ liệu, dry-run vài bước. (3) Dùng tính năng so sánh config và lọc log của công cụ theo dõi run. (4) Checklist xử lý theo mã lỗi. |
| **Hướng can thiệp AI cần kiểm chứng** | Chỉ tóm tắt và chỉ ra đoạn log đáng chú ý, kèm dòng nguồn, cho các lỗi không khớp pattern nào của Rule. Không tự sửa cấu hình, không tự chạy lại job. |
| **Cảm nhận nhanh** | **Rule.** Phần lớn giá trị nằm ở log có cấu trúc và chặn lỗi trước khi chạy; chỉ cân nhắc Workflow cho lỗi lạ không khớp pattern. |

```text
QUY TRÌNH HIỆN TẠI #2 — TỔNG 60 PHÚT/SỰ CỐ

[1 Nhận cảnh báo: 4'] → [2 Mở run/log: 7']
→ [3 Tìm vùng log lỗi: 21'] ← BOTTLENECK
→ [4 Xác minh nguyên nhân: 13'] → [5 Sửa lỗi: 12']
→ [6 Kiểm tra/chạy lại: 3']
GPU-giờ chạy lại: theo dõi riêng theo lịch sử từng run.
```

**AI phản biện Card #2**

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chỉ 2 sự cố/tháng nên impact thời gian nhỏ nhất trong 3 card | Đồng ý một phần | Giữ card ở hạng 2, không chọn để pitch; tách chi phí GPU chạy lại thành chỉ số riêng |
| Công cụ theo dõi run (MLflow, W&B) đã lưu log theo run, có alert và so sánh config. Bước "tìm vùng log" có thể giải bằng tính năng có sẵn | Đồng ý | Thêm "dùng tính năng có sẵn của công cụ theo dõi run" vào phương án không dùng AI; đưa vào research CP4 |
| Tìm log lâu có thể chỉ là triệu chứng của việc log viết tự do, không có log level, không có mã lỗi | Đồng ý | Thêm structured logging và mã lỗi làm bước No AI đầu tiên |
| Nhiều lỗi có thể chặn trước khi chạy (sai config, sai schema, thiếu bộ nhớ). Outcome nên là giảm số job hỏng, không chỉ tìm lỗi nhanh hơn | Đồng ý | Thêm bước kiểm tra trước khi chạy và metric phụ "số job hỏng do lỗi chặn được trước" |
| Sự cố ít nên muốn đo trên vài sự cố mới cũng phải chờ nhiều tuần, không kịp kiểm chứng trong pilot ngắn | Đồng ý | Success metric đánh giá trên các sự cố cũ tái hiện được từ log đã lưu |
| Vì sao không để AI đọc log, tự sửa config rồi tự chạy lại job? | Không đồng ý | Chạy lại tốn GPU, sửa sai có thể làm hỏng thí nghiệm; giữ boundary "AI chỉ chỉ ra đoạn log, người sửa và quyết định chạy lại" |
| Nhiều lỗi do hạ tầng (node lỗi, hết quota) nằm ngoài quyền xử lý của AI Engineer | Đồng ý một phần | Thu hẹp phạm vi card về lỗi do code, cấu hình và dữ liệu |

### Problem Card #3 — Phân loại lỗi câu trả lời để phản hồi PM/BA

| Trường | Nội dung |
|---|---|
| **Job Story** | Khi PM/BA hỏi hệ thống đang sai ở những tình huống nào, tôi muốn cung cấp các nhóm lỗi, ví dụ và tần suất có thể đối chiếu, để nhóm chọn đúng việc cần sửa trước. |
| **Actor** | Tôi là AI Engineer xử lý các trường hợp trả lời không đạt; PM/BA dùng kết quả để sắp xếp backlog. |
| **Thời điểm / bối cảnh** | Sau buổi tổng hợp phản hồi chất lượng hoặc trước cuộc họp ưu tiên xử lý lỗi. |
| **Input → Output** | Input: ticket, câu hỏi đầu vào, câu trả lời của hệ thống, tiêu chí đúng/sai, dữ liệu được phép xem. Output: bảng 6 nhóm lỗi, số lượng, 1–2 ví dụ/nhóm có case ID, cỡ mẫu và giới hạn của phân tích. |
| **Quy trình hiện tại** | 1. Nhận yêu cầu (3') → 2. Truy xuất case (9') → 3. Lọc trùng (6') → **4. Phân loại 18 case (26')** → 5. Kiểm mẫu, đếm số (12') → 6. Viết tóm tắt (8') → 7. Phản hồi, làm rõ (2') |
| **Bottleneck** | Bước 4, phân nhóm lỗi bằng tay: **26/66 phút** (39% tổng thời gian). |
| **Impact** | **66 phút/yêu cầu × 3 yêu cầu/tuần = 198 phút/tuần**; mỗi yêu cầu khoảng 18 case. Rủi ro: phân loại không nhất quán giữa các tuần làm PM ưu tiên sai. |
| **Success metric** | Thời gian hoàn thành báo cáo giảm từ **66 xuống ≤35 phút/yêu cầu**, kiểm trên 4 yêu cầu tương đương. **Guardrail:** đồng thuận nhãn ≥90% so với người kiểm, tính trên taxonomy đã chốt; nhóm lỗi nghiêm trọng được soát 100%; mỗi báo cáo ghi rõ cỡ mẫu và case ID truy ngược được. |
| **Phương án không dùng AI** | (1) Chốt taxonomy 6 nhóm lỗi, có định nghĩa và ví dụ. (2) Gắn nhãn tại nguồn: người báo lỗi chọn loại lỗi trong form. (3) Query có bộ lọc và pivot để đếm. (4) Template báo cáo có sẵn mục cỡ mẫu và giới hạn. |
| **Hướng can thiệp AI cần kiểm chứng** | Chỉ đề xuất nhãn cho case mô tả tự do mà nhãn tại nguồn và Rule không xử lý được. Kỹ sư duyệt mọi nhãn trước khi gửi. Chỉ dùng dữ liệu đã ẩn danh, đúng chính sách dữ liệu. |
| **Cảm nhận nhanh** | **Rule** nếu gắn nhãn tại nguồn được; **Workflow** chỉ cho phần mô tả tự do còn lại. Chưa có căn cứ chọn Agent. |

```text
QUY TRÌNH HIỆN TẠI #3 — TỔNG 66 PHÚT/YÊU CẦU

[1 Nhận yêu cầu: 3'] → [2 Xuất case: 9'] → [3 Lọc trùng: 6']
→ [4 Phân nhóm 18 case: 26'] ← BOTTLENECK
→ [5 Kiểm mẫu + đếm: 12'] → [6 Soạn báo cáo: 8']
→ [7 Phản hồi: 2']
```

**AI phản biện Card #3**

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chưa biết PM thật sự cần gì: bảng phân loại đầy đủ, chỉ top 3 lỗi, hay dashboard tự xem. Đang đoán nhu cầu của người khác | Đồng ý | Thêm giả định kiểm chứng ở CP4: hỏi PM lần gần nhất dùng báo cáo để quyết định việc gì |
| Chưa có taxonomy cố định nên mỗi lần phân loại một kiểu, số liệu giữa các tuần không so sánh được, chỉ tiêu "đồng thuận nhãn ≥90%" không đo được | Đồng ý | Thêm bước No AI đầu tiên: chốt taxonomy 6 nhóm có định nghĩa và ví dụ |
| Nếu người báo lỗi chọn loại lỗi ngay trong form thì bước phân loại thủ công gần như biến mất, chỉ còn đếm bằng pivot | Đồng ý một phần | Thêm "gắn nhãn tại nguồn" vào phương án không dùng AI; ghi rủi ro tăng việc cho bộ phận vận hành, cần hỏi họ ở CP4 |
| 18 case/lần chia cho 6 nhóm lỗi là quá ít để kết luận nhóm nào nhiều nhất, PM có thể ưu tiên sai | Đồng ý | Báo cáo ghi rõ cỡ mẫu và khoảng thời gian; gộp nhiều tuần khi mẫu nhỏ |
| Bỏ sót nhóm lỗi nghiêm trọng (ví dụ trả lời sai thông tin chính sách) tệ hơn gán nhầm một lỗi nhẹ | Đồng ý | Thêm guardrail: nhóm lỗi nghiêm trọng luôn được người soát 100% |
| Case chứa câu hỏi thật của người dùng, có thể có thông tin cá nhân; đưa vào công cụ AI cần quyền và cần ẩn danh | Đồng ý | Thêm boundary: chỉ dùng dữ liệu đã ẩn danh, kiểm chính sách dữ liệu trước khi thử |
| Vì sao không để AI tự phân loại, tự viết báo cáo và gửi thẳng cho PM hằng tuần? | Không đồng ý | PM dùng báo cáo để ưu tiên backlog, phân loại sai khiến cả team sửa nhầm chỗ; giữ boundary "kỹ sư duyệt trước khi gửi" |

**Card muốn pitch:** #1.

**Câu hỏi muốn nhóm phản biện:** Nếu đã có rubric và công cụ eval có sẵn, phần việc còn lại có còn đủ đau để đáng giải không?
---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Trình bày 3 candidate problem: #1 Kiểm tra điều khoản hợp đồng, #2 Phân loại tin nhắn phàn nàn, #3 Kiểm tra quy cách nộp bài của sinh viên; pitch sâu Card #1. | Đóng góp 3 candidate vào bảng Pitch 18 ý của nhóm (mục 2.1 `group_report.md`). |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: Với candidate #5 (giải thích lại câu hỏi cũ), phần tốn 30–60 phút là do phải tìm lại câu trả lời cũ hay do phải giải thích lại từ đầu? Các câu hỏi có đủ giống nhau để viết sẵn vào một chỗ không? | Nhóm tách được 2 giả định quan trọng: #2 (thời gian giải thích lại) và #4 (mức độ giống nhau của câu hỏi), đưa vào Assumption Map và khảo sát ở CP4. |
| Nhận phản biện | Câu hỏi tôi nhận được: Với Card #1, nhóm không có hợp đồng thật dài 30–40 trang và không có luật sư nội bộ để kiểm chứng trong buổi lab thì đo baseline thế nào? | Tôi đã sửa gì: Đồng ý rút Card #1 khỏi shortlist vì không kiểm chứng được trong phạm vi một buổi lab; chuyển sang ủng hộ candidate #5 vì có sẵn người để khảo sát. |
| Gom cluster / cây OST | Cùng nhóm gom #1, #3 vào Cluster C (Kiểm tra, phát hiện lỗi/sai lệch) và #2 vào Cluster B (Yêu cầu lặp lại xử lý bằng tay); rà lại câu chữ của #3 để tách phần giải pháp ("tự động kiểm tra") ra khỏi pain thật. | Cây OST có 4 nhánh Opportunity (mục 2.2, 2.3), không lẫn tên công cụ hay tính năng. |
| Chọn candidate problem | Thảo luận và chấm điểm 7 tiêu chí cho 3 bài trong shortlist (#5, #8, #15). | Nhóm thống nhất chọn candidate #5: 30/35 điểm, cao nhất nhóm, dễ so sánh với mức No AI. |
| Kiểm chứng / research | Tham gia phỏng vấn/khảo sát người thật sự phải giải thích lại câu hỏi cũ, hỏi theo The Mom Test về lần gần nhất họ gặp chuyện này và mất bao lâu, để kiểm chứng giả định #2 và #4. | Kết quả phỏng vấn/khảo sát được ghi ở mục 3 `group_report.md`, làm căn cứ để nhóm sửa problem. |
| Quy trình nhóm | Góp ý khi nhóm vẽ quy trình hiện tại: đề nghị tách bước "tìm lại câu trả lời cũ" và bước "giải thích lại" để xác định đúng bước nghẽn. | Góp ý được nhóm cân nhắc khi chốt quy trình trước/sau và bottleneck (mục 4 `group_report.md`). |
| Problem Statement | Phản biện Problem Statement v0: kiểm tra Success Metric đã có đủ baseline, target, cách đo chưa và Boundary đã ghi rõ AI không được làm gì chưa. | Góp phần vào các chỉnh sửa từ v0 sang v1 (mục 5 và 7 `group_report.md`). |
| Mức can thiệp AI | Góp ý lập luận "vì sao không chọn mức đơn giản hơn": nếu các câu hỏi đủ giống nhau (giả định #4) thì FAQ hoặc template (No AI/Rule) có thể đã đủ. | Lập luận chọn mức can thiệp được ghi ở mục 6 `group_report.md`. |
| Quyết định | Đồng ý với quyết định của nhóm sau khi thảo luận 4 rủi ro Value / Usability / Feasibility / Viability. | Quyết định và ngưỡng dừng được ghi ở mục 8 `group_report.md`. |
---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Nhờ AI gợi ý danh sách candidate theo 4 lăng kính và gợi ý chỉ số đo | Phủ đủ 4 lăng kính, Job Story đúng mẫu "Khi… tôi muốn… để…" | Bản đầu có Job Story #10 chứa chữ "chatbot" (lẫn giải pháp vào problem); AI không biết công việc và số liệu thật của tôi | Sửa #10 thành "hệ thống trả lời khách hàng"; tự chọn giữ các dòng và tự điền số liệu |
| CP2 Problem Card | Nhờ AI đóng vai PM hoài nghi phản biện 3 card và kiểm phép tính | Chỉ ra nghẽn có thể do thiếu rubric/bộ test chứ không phải do bước chấm; đã có công cụ eval sẵn; guardrail 95% vô nghĩa trên mẫu nhỏ | Gợi ý để AI tự chặn phát hành và tự sửa config, chạy lại job; bản nháp đầu có tổng phút không khớp (74' và 60') | Không theo 2 gợi ý tự động hóa, giữ boundary người duyệt; cập nhật phương án không dùng AI và guardrail; thống nhất Card #1 thành 62' |
| CP4 Research | Không dùng AI ở bước này | — | — | — |
| CP5 Quy trình | Không dùng AI ở bước này | — | — | — |
| CP5–6 Problem Statement | Không dùng AI ở bước này | — | — | — |
| CP6 Mức can thiệp / quyết định | Không dùng AI ở bước này | — | — | — |

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**Qua phần trình bày của các thành viên, tôi nhận thấy cùng một vấn đề có thể được nhìn nhận theo nhiều góc độ khác nhau. Một vấn đề nghe có vẻ quan trọng chưa chắc đã phù hợp để lựa chọn nếu không có dữ liệu kiểm chứng hoặc không xác định được quy trình cụ thể. Tôi cũng nhận ra cần đánh giá vấn đề dựa trên mức độ ảnh hưởng, thời gian xử lý, khả năng đo lường và tính khả thi, thay vì chỉ dựa vào sự hấp dẫn của ý tưởng.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**Trong quá trình thảo luận, nhóm có những ý tưởng thiên về giải pháp trước khi phân tích đầy đủ vấn đề. Chẳng hạn, khi xem xét việc giải thích lại các câu hỏi cũ, chúng tôi dễ nghĩ ngay đến công cụ tự động trả lời. Tuy nhiên, nhóm đã đặt câu hỏi liệu nguyên nhân thực sự là khó tìm lại câu trả lời hay phải giải thích lại từ đầu. Từ đó, nhóm tập trung mô tả nhu cầu, xác định bước nghẽn và cân nhắc giải pháp đơn giản như FAQ hoặc mẫu câu trả lời trước khi đề xuất sử dụng AI.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**Ban đầu, tôi ưu tiên vấn đề kiểm tra điều khoản hợp đồng vì cho rằng công việc này đòi hỏi đọc nhiều thông tin và dễ xảy ra sai sót. Tuy nhiên, khi các thành viên phản biện về việc thiếu hợp đồng thực tế dài 30–40 trang và không có chuyên gia pháp lý để xác minh kết quả trong buổi lab, tôi nhận ra vấn đề khó kiểm chứng trong phạm vi thời gian cho phép. Vì vậy, tôi đồng ý rút vấn đề này khỏi danh sách ưu tiên và chuyển sang ủng hộ candidate #5 về việc giải thích lại câu hỏi cũ, vì có khả năng tiếp cận người gặp vấn đề để khảo sát trực tiếp.


**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**Điểm đáng chú ý khi thực hiện bước kiểm chứng là phải phân biệt giữa nhận định ban đầu với những hành vi đã thực sự xảy ra. Đối với vấn đề giải thích lại câu hỏi cũ, hai giả định quan trọng cần làm rõ là thời gian thực tế dành cho việc giải thích lại và mức độ tương đồng giữa các câu hỏi. Điều này khiến tôi thận trọng hơn với nhận định rằng tự động hóa chắc chắn sẽ mang lại hiệu quả. Nếu câu hỏi đủ giống nhau, việc xây dựng FAQ hoặc chuẩn hóa câu trả lời có thể giải quyết được phần lớn vấn đề mà chưa cần AI.


**6.5. Điều khó nhất khi viết Problem Statement là gì?**Theo tôi, khó nhất là xác định đúng bottleneck và xây dựng success metric có thể đo lường. Ban đầu, rất dễ mô tả chung rằng công việc mất nhiều thời gian, nhưng cách diễn đạt đó chưa chỉ ra bước nào gây chậm trễ. Khi xây dựng Problem Statement, cần phân tách rõ các bước tìm lại thông tin và giải thích lại, xác định thời gian hiện tại, mục tiêu cải thiện và cách kiểm tra kết quả. Ngoài ra, boundary phải nêu rõ phạm vi được hỗ trợ và những quyết định vẫn cần con người kiểm soát.


**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**Nếu thực hiện lại, tôi sẽ ưu tiên thu thập bằng chứng thực tế ngay từ bước lựa chọn vấn đề, thay vì dành nhiều thời gian cho những ý tưởng khó kiểm chứng. Tôi cũng sẽ chuẩn bị kỹ hơn các câu hỏi phản biện về tần suất xảy ra, tác động đo được và khả năng giải quyết bằng những công cụ sẵn có. Đặc biệt, tôi sẽ đề nghị nhóm kiểm tra các phương án No AI và Rule trước khi cân nhắc Workflow hoặc Agent. Điều này giúp tiết kiệm thời gian, hạn chế lựa chọn giải pháp quá phức tạp và làm cho quyết định cuối cùng có cơ sở hơn.


**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.Bài toán nhóm lựa chọn là việc người thực hiện phải giải thích lại những câu hỏi đã từng được trả lời, gây tốn thời gian và công sức. Quy trình cần phân biệt bước tiếp nhận câu hỏi, tìm lại câu trả lời cũ, giải thích lại và phản hồi cho người hỏi. Nhóm xác định bước gây tốn thời gian nhất làm bottleneck để ưu tiên cải thiện. Success metric cần so sánh thời gian xử lý trước và sau khi áp dụng giải pháp, đồng thời theo dõi chất lượng câu trả lời. Boundary yêu cầu không sử dụng nội dung thiếu kiểm chứng và không để hệ thống tự đưa ra kết luận ngoài phạm vi thông tin được xác nhận. Về mức can thiệp, cần ưu tiên FAQ hoặc Rule nếu các câu hỏi có tính lặp lại cao; chỉ cân nhắc Workflow khi các phương án đơn giản không đáp ứng được. Cuối cùng, quyết định Go / Not Yet / No-Go phải dựa trên kết quả kiểm chứng, tính khả thi, bốn nhóm rủi ro và ngưỡng dừng đo được.

---

## 7. Tài liệu tham khảo

-
