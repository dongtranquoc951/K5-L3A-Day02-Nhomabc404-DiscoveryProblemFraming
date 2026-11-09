# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Trần Quốc Đông
- MSSV: 2A202603643
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: abc404
- Link repo nhóm: https://github.com/dongtranquoc951/K5-L3A-Day02-Nhomabc404-DiscoveryProblemFraming.git

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Pain từ người khác | Khi nhận sản phẩm không đúng mô tả, tôi muốn khiếu nại được phân loại và xử lý nhanh để không phải chờ đợi lâu.|Người mua, nhân viên CSKH |Số khiếu nại sai mô tả mỗi ngày, thời gian xử lý trung bình, tỷ lệ phải liên hệ nhiều lần. |
| 2 | Cần đọc, tổng hợp nhiều thông tin |Khi mua sản phẩm có nhiều người bán, tôi muốn so sánh giá, chất lượng và đánh giá để chọn sản phẩm phù hợp. |Người mua hàng |Thời gian so sánh sản phẩm, số trang phải xem, số người gặp khó khăn khi lựa chọn. |
| 3 | Lặp lại |Khi khách liên tục hỏi về chính sách đổi trả, tôi muốn trả lời nhanh các câu hỏi phổ biến để giảm thời gian xử lý thủ công. |Nhân viên CSKH, người mua |Số câu hỏi đổi trả/ngày, thời gian phản hồi, tỷ lệ câu hỏi trùng lặp. |
| 4 | Pain từ người khác |Khi mua hàng qua mạng, tôi muốn nhận biết đánh giá giả hoặc đánh giá không đáng tin để tránh mua phải sản phẩm kém chất lượng. |Người mua, người bán uy tín |Số đánh giá đáng ngờ, số khiếu nại sau mua, kết quả kiểm tra mẫu đánh giá. |
| 5 | Cần tổng hợp nhiều thông tin|Khi mua sản phẩm điện tử, tôi muốn tổng hợp ưu nhược điểm từ nhiều đánh giá để biết sản phẩm có phù hợp với nhu cầu không. |Người mua hàng |Số đánh giá cần đọc, thời gian tìm hiểu, mức độ hữu ích của bản tổng hợp. |
| 6 | Lặp lại | Khi cửa hàng nhận nhiều tin nhắn hỏi về sản phẩm, tôi muốn phân loại câu hỏi và gợi ý câu trả lời để phản hồi khách nhanh hơn. | Người bán, nhân viên tư vấn | Số tin nhắn/ngày, thời gian phản hồi, tỷ lệ câu hỏi lặp lại. |
| 7 | Tốn thời gian | Khi muốn đổi trả sản phẩm bị lỗi, tôi muốn được hướng dẫn và kiểm tra thông tin yêu cầu nhanh chóng để không phải thực hiện nhiều bước. | Người mua, nhân viên xử lý đổi trả | Thời gian tạo yêu cầu đổi trả, số bước thực hiện, tỷ lệ hồ sơ thiếu thông tin. |
| 8 | Pain từ người khác | Khi mua hàng trực tuyến, tôi muốn được cảnh báo sản phẩm có dấu hiệu hàng giả để tránh mất tiền và gặp rủi ro khi sử dụng. | Người mua, nền tảng thương mại điện tử | Số báo cáo hàng giả, tỷ lệ xác minh đúng, thiệt hại từ các trường hợp đã xác nhận. |

Nếu có dùng AI để gợi ý thêm:

Ý bỏ qua: Bỏ qua gợi ý về "cảnh báo sản phẩm có dấu hiệu hàng giả" vì đây là việc ảnh hưởng trực tiếp đến lợi nhuận của người bán hàng và sàn thương mại điện tử cần có người rà soát trực tiếp AI ở đây chỉ được xem như công cụ hỗ trợ cho người phân loại không được phép đưa ra quyết định trực tiếp. Việc này có thể được làm từ khâu lọc sản phẩm có dấu hiệu hàng giả từ phía sàn tmdt

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 |Khiếu nại sản phẩm không đúng mô tả được xử lý chậm |Người mua phải chờ lâu; nhân viên mất thời gian đọc nội dung, kiểm tra hình ảnh và phân loại khiếu nại. AI có thể hỗ trợ. |Chưa rõ số lượng khiếu nại, thời gian xử lý trung bình và nguyên nhân gây chậm. |
| 2 |Người mua khó nhận biết đánh giá giả |Đánh giá giả có thể khiến khách mua nhầm sản phẩm kém chất lượng. AI có thể phân tích nội dung và hành vi bất thường. |Chưa rõ tỷ lệ đánh giá giả và có đủ dữ liệu để nhận diện chính xác không. |
| 3 |Người mua mất nhiều thời gian so sánh sản phẩm |Phải đọc nhiều mô tả, thông số và đánh giá từ nhiều người bán. AI có thể tổng hợp và so sánh thông tin. |Chưa rõ người mua mất bao lâu và công cụ lọc, so sánh hiện tại đã đáp ứng đủ chưa. |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhận sản phẩm không đúng mô tả, tôi muốn yêu cầu khiếu nại được tiếp nhận, phân loại và xử lý nhanh chóng để được đổi trả hoặc hoàn tiền mà không phải chờ đợi lâu. |
| Actor |Người mua hàng trực tuyến; nhân viên CSKH là người trực tiếp xử lý yêu cầu. |
| Thời điểm / bối cảnh |Sau khi khách nhận hàng và phát hiện sản phẩm sai mẫu mã, màu sắc, thông số hoặc không đúng quảng cáo. |
| Quy trình hiện tại (3–7 bước) |1. Khách nhận hàng và phát hiện sai mô tả. 2. Khách gửi khiếu nại kèm hình ảnh. 3. Nhân viên đọc nội dung, kiểm tra đơn hàng. 4. Đối chiếu hình ảnh và mô tả sản phẩm. 5. Phân loại và chuyển bộ phận phụ trách. 6. Xác minh và quyết định đổi trả/hoàn tiền. 7. Thông báo kết quả cho khách. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Giả định bước 3–5 mất khoảng 10 phút/khiếu nại do nhân viên phải kiểm tra và phân loại thủ công. Cần đo thực tế. |
| Impact (nếu không giải thì sao) |Khách chờ lâu, giảm mức độ hài lòng; nhân viên mất thời gian, khiếu nại tồn đọng và có nguy cơ mất khách hàng. |
| Success metric (baseline → target) |Giả định giảm thời gian kiểm tra và phân loại trung bình từ 10 phút xuống 3 phút/khiếu nại sau 2 tháng thử nghiệm; không tăng tỷ lệ phân loại sai. |
| Phương án không dùng AI |Tạo biểu mẫu khiếu nại có danh mục lỗi, bắt buộc cung cấp mã đơn và hình ảnh; tự động chuyển yêu cầu theo quy tắc. |
| Giả thuyết về AI (nếu có) |AI phân tích nội dung khiếu nại và hình ảnh, đối chiếu mô tả sản phẩm, gợi ý loại lỗi và mức độ ưu tiên để nhân viên kiểm tra. |
| Cảm nhận nhanh | Workflow trước; cân nhắc AI Agent hỗ trợ nếu quy trình dựa trên quy tắc không đủ hiệu quả. |

Quy trình nháp hiện tại:

```text
Khách phát hiện sản phẩm sai mô tả.

Gửi khiếu nại kèm hình ảnh.

Nhân viên tiếp nhận và kiểm tra đơn hàng.

Đối chiếu thông tin sản phẩm.

Phân loại và chuyển bộ phận xử lý.

Xác minh, quyết định đổi trả/hoàn tiền.

Thông báo kết quả.

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi xem đánh giá sản phẩm trên sàn thương mại điện tử, tôi muốn nhận biết những đánh giá giả hoặc không đáng tin cậy để tránh mua phải sản phẩm kém chất lượng. |
| Actor |Người mua hàng trực tuyến. |
| Thời điểm / bối cảnh |Khi người mua đang xem đánh giá và cân nhắc đặt mua một sản phẩm có nhiều lượt đánh giá. |
| Quy trình hiện tại (3–7 bước) |1. Người mua tìm kiếm sản phẩm. 2. Xem số sao và lượt đánh giá. 3. Đọc bình luận của người mua trước. 4. Kiểm tra hình ảnh, video và nội dung đánh giá. 5. So sánh đánh giá tích cực và tiêu cực. 6. Quyết định có mua sản phẩm hay không. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 3–5: Người mua phải đọc và đánh giá nhiều bình luận, giả định mất 15–20 phút/sản phẩm nhưng vẫn khó xác định đánh giá giả. |
| Impact (nếu không giải thì sao) |Người mua có thể bị đánh giá giả dẫn dắt, mua hàng kém chất lượng, mất tiền và thời gian đổi trả. Người bán uy tín cũng bị ảnh hưởng bởi cạnh tranh không lành mạnh. |
| Success metric (baseline → target) |Giả định giảm thời gian xem xét đánh giá từ 20 phút xuống 5 phút/sản phẩm trong 2 tháng; đồng thời hệ thống đạt Precision ≥ 90% khi cảnh báo đánh giá giả trên tập dữ liệu đã được xác minh. |
| Phương án không dùng AI |Lọc đánh giá từ người đã mua hàng, ưu tiên đánh giá có hình ảnh thực tế, cho phép báo cáo đánh giá đáng ngờ và áp dụng quy tắc phát hiện spam. |
| Giả thuyết về AI (nếu có) |AI phân tích nội dung, sự trùng lặp, thời gian đăng và hành vi tài khoản để nhận diện các đánh giá có dấu hiệu bất thường, sau đó cảnh báo người mua. |
| Cảm nhận nhanh |AI/ML hỗ trợ phát hiện bất thường, kết hợp Rule và người kiểm duyệt. Chưa nên dùng Agent tự quyết định xóa đánh giá.  |

Quy trình nháp hiện tại:

```text
Tìm kiếm sản phẩm.

Xem số sao và lượt đánh giá.

Đọc bình luận của người mua trước.

Kiểm tra ảnh, video và nội dung đánh giá.

So sánh đánh giá tích cực, tiêu cực.

Quyết định mua hàng.
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi muốn mua một sản phẩm có nhiều lựa chọn, tôi muốn so sánh giá cả, thông số, chất lượng và đánh giá từ nhiều người bán để lựa chọn sản phẩm phù hợp với nhu cầu và ngân sách. |
| Actor |Người mua hàng trực tuyến. |
| Thời điểm / bối cảnh |Khi người mua đang cân nhắc giữa nhiều sản phẩm tương tự, ví dụ laptop, điện thoại, tai nghe hoặc thiết bị gia dụng. |
| Quy trình hiện tại (3–7 bước) |1. Xác định nhu cầu và ngân sách. 2. Tìm sản phẩm trên các website. 3. Mở nhiều trang để xem thông tin. 4. Đọc thông số và đánh giá. 5. So sánh giá, tính năng, bảo hành. 6. Lựa chọn và đặt mua. |
| Bottleneck (bước nào, mất bao nhiêu phút) |Bước 3–5: Người mua phải tổng hợp nhiều thông tin từ các website, giả định mất 30–60 phút/lần lựa chọn. |
| Impact (nếu không giải thì sao) |Tốn thời gian tìm kiếm, dễ bỏ sót thông tin quan trọng, có thể mua sản phẩm không phù hợp hoặc giá cao hơn lựa chọn tương đương. |
| Success metric (baseline → target) |Giả định giảm thời gian so sánh trung bình từ 45 phút xuống 15 phút trong 2 tháng; đồng thời ≥ 95% thông số được hiển thị phải khớp với nguồn đã xác minh. |
| Phương án không dùng AI |Xây dựng bảng so sánh sản phẩm, bộ lọc theo giá và thông số, sắp xếp theo tiêu chí, cho phép chọn nhiều sản phẩm để đối chiếu. |
| Giả thuyết về AI (nếu có) |AI đọc và tổng hợp thông số, đánh giá, ưu nhược điểm từ nhiều nguồn, sau đó giải thích sản phẩm nào phù hợp với nhu cầu người mua. |
| Cảm nhận nhanh | Workflow + AI hỗ trợ tổng hợp, chưa cần Agent tự động mua hàng. |

Quy trình nháp hiện tại:

```text
Xác định nhu cầu và ngân sách.

Tìm kiếm sản phẩm trên các website.

Mở nhiều trang để xem thông tin.

Đọc thông số, đánh giá và bảo hành.

So sánh giá, tính năng, ưu nhược điểm.

Chọn sản phẩm và đặt mua.
```

### Card muốn pitch nhất

- Card số: Xử lý khiếu nại sản phẩm không đúng mô tả.
- Vì sao: Đây là vấn đề ảnh hưởng trực tiếp đến người mua hàng và nhân viên chăm sóc khách hàng. Nhân viên phải đọc nội dung khiếu nại, kiểm tra đơn hàng, đối chiếu hình ảnh và phân loại thủ công, dẫn đến thời gian xử lý kéo dài. Vấn đề có quy trình rõ ràng, có thể đo thời gian và thử nghiệm cải tiến.
- Câu hỏi muốn nhóm phản biện: Nguyên nhân chính khiến khiếu nại xử lý chậm có thực sự nằm ở bước kiểm tra và phân loại thủ công, hay do quy trình xác minh và phê duyệt đổi trả/hoàn tiền?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
|1. Chưa có bằng chứng thực tế: Thời gian xử lý 10 phút/khiếu nại chỉ là giả định.|Có |Ghi rõ đây là giả định và đề xuất đo thời gian xử lý thực tế của 20–30 khiếu nại. |
|2. Chưa xác định đúng bottleneck: Khiếu nại chậm có thể do chờ người bán xác minh, không phải do nhân viên phân loại. |Có |Tách thời gian tiếp nhận, phân loại, xác minh và phê duyệt để tìm bước gây chậm nhất. |
|3. Chưa chứng minh cần AI: Biểu mẫu chuẩn hóa và phân loại theo quy tắc có thể đã giải quyết được vấn đề. |Có |Đề xuất thử workflow không AI trước, sau đó mới đánh giá AI có giúp cải thiện thêm không. |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card |Đưa ra 3 candidate #10 (khiếu nại sai mô tả), #11 (khó nhận biết đánh giá giả), #12 (mất thời gian so sánh sản phẩm). Pitch ưu tiên candidate #10 và nêu câu hỏi về nguyên nhân chậm: phân loại hay xác minh/phê duyệt. |Ba candidate được ghi tại mục 2.1 báo cáo nhóm; #10 thuộc Cluster B, #11 thuộc Cluster C, #12 thuộc Cluster A. |
| Phản biện bài của bạn khác | “Với candidate #8, deadline nằm ở ứng dụng nào, mỗi lần tổng hợp mất bao nhiêu phút và khác gì việc ưu tiên công việc hằng sáng?” |Giúp chỉ ra dữ kiện còn thiếu ở #8; báo cáo nhóm ghi #8 chỉ đạt 19/35 điểm. |
| Nhận phản biện | Với card #10, AI nêu 3 điểm yếu: thiếu bằng chứng cho 10 phút/khiếu nại, chưa chắc bottleneck nằm ở phân loại, và chưa chứng minh cần AI. | đánh dấu thời gian là giả định; đề xuất đo từng bước; ưu tiên thử biểu mẫu/workflow theo quy tắc trước. |
| Gom cluster / cây OST |Hỗ trợ Hồ Sỹ Tùng ở CP3, đối chiếu các candidate #10–#12 với nhóm vấn đề tương ứng và rà soát cách viết pain thay vì viết sẵn giải pháp. |Báo cáo nhóm có 4 cluster A–D và OST với 1 outcome, 4 opportunity (mục 2.2–2.3). |
| Chọn candidate problem |Hỗ trợ điều phối việc so sánh shortlist #5, #8, #15 theo 7 tiêu chí; ưu tiên chọn vấn đề có actor, pain, bằng chứng và khả năng thử giải pháp đơn giản. |Candidate #5 “giải thích lại cùng một câu hỏi” đứng đầu 30/35 điểm, so với #15 là 24 và #8 là 19. |
| Kiểm chứng / research |Rà soát tính thuyết phục của survey |Nhóm giữ rõ hạn chế mẫu 10 người, thiếu câu hỏi mở và chưa có quan sát hành vi |
| Quy trình nhóm |đối chiếu quy trình As-Is và To-Be của candidate #5 với bottleneck |Quy trình 4 bước hiện tại và FAQ No AI tương lai được trình bày ở mục 4 |
| Problem Statement |Hỗ trợ rà soát PS v0 ở CP5: cần rõ actor, bottleneck, baseline, cách đo và boundary; theo dõi thay đổi v0 → v1 sau survey. |Baseline từ giả định 30–60 phút/lần được điều chỉnh về mức phổ biến 15–30 phút/lần |
| Mức can thiệp AI |đối chiếu phương án No AI, Rule, Workflow, Agent với độ mơ hồ và độ phức tạp. |Nhóm chọn No AI (FAQ/tin ghim), chỉ cân nhắc mức cao hơn nếu pilot cho thấy FAQ không đủ. |
| Quyết định |Hỗ trợ Nguyễn Văn Ngọc Sơn rà soát 4 rủi ro Value, Usability, Feasibility, Viability |Quyết định nhóm hiện là Go phạm vi nhỏ, pilot FAQ 5 câu hỏi phổ biến trong 2 tuần, theo dõi và đánh giá tiếp sau 4 tuần |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan |Gợi ý loại bỏ vấn đề thứ 8 |Hỗ trợ diễn đạt pain, actor và dấu hiệu cần thu thập theo cấu trúc CP1. |Dễ đưa ra con số giả định như thể là dữ liệu thật; một số gợi ý nghiêng về tính năng AI thay vì vấn đề. |Chỉ giữ số liệu ở dạng chỉ số cần kiểm chứng, không tuyên bố đã khảo sát; bỏ qua hướng tự động kết luận hàng giả do rủi ro cho người bán. |
| CP2 Problem Card |k |k |k |k |
| CP4 Research |dùng AI để gợi ý câu hỏi kiểm tra độ mạnh/yếu của bằng chứng survey. |Nhắc phân biệt câu trả lời về ý định tương lai với hành vi thực tế. |AI có thể kết luận “7/10 sẽ dùng FAQ” từ câu “sẵn sàng dùng”, dù chưa có pilot. |Trong phần phản biện, chỉ coi 7/10 là ý định được báo cáo |
| CP5 Quy trình |dùng AI rà soát logic giữa quy trình trước/sau và bottleneck. |Dễ phát hiện bước không có actor, input/output hoặc thiếu nhánh |AI có thể coi mục tiêu ≤ 5 phút là kết quả đã đạt, hoặc lẫn baseline 30–60 phút với số liệu sau survey. |Giữ phân biệt rõ baseline khảo sát, mục tiêu đề xuất và thời gian chưa đo |
| CP5–6 Problem Statement |dùng AI kiểm tra đủ các trường PS và so sánh v0/v1. |Hữu ích khi rà soát actor, bottleneck, impact, metric, boundary. |Có thể phóng đại 10 người thành đại diện cho mọi người dùng |Giới hạn kết luận trong mẫu 10 người |
| CP6 Mức can thiệp / quyết định | |Làm rõ tại sao No AI có thể phù hợp hơn Agent ở quy mô nhỏ. |AI dễ ưu tiên Agent chỉ vì bài học liên quan AI, hoặc coi ngưỡng pilot là bằng chứng hiệu quả. |Giữ quyết định Go phạm vi nhỏ |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Nhận ra được 1 số thiếu sót về cost của dự án hiện tại, có thêm góc nhìn mới về các dự án mà các nhóm đưa ra

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
k

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
k

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
k

**6.5. Điều khó nhất khi viết Problem Statement là gì?** 
k

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
k

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.
Problem: Nhóm xác định vấn đề là người được hỏi phải giải thích lại cùng một câu hỏi cho đồng nghiệp hoặc bạn học nhiều lần, gây lãng phí thời gian.

Quy trình: Hiện tại, người hỏi đặt câu hỏi, người được hỏi tìm lại thông tin và giải thích từ đầu; nhóm đề xuất xây dựng trang FAQ để người hỏi có thể tự tra cứu trước.

Metric: Theo khảo sát 10 người, thời gian giải thích phổ biến là 15–30 phút/lần, với tần suất ước lượng khoảng 2 lần/tuần; nhóm đặt mục tiêu giảm thời gian tìm câu trả lời và số lần phải giải thích lại.

Boundary: Hệ thống chỉ cung cấp những câu trả lời đã được xác minh trong FAQ; các câu hỏi chưa có thông tin hoặc trường hợp phức tạp vẫn cần con người xử lý.

Mức can thiệp AI: Nhóm lựa chọn No AI vì vấn đề có thể giải quyết trước bằng trang FAQ đơn giản, chưa cần sử dụng chatbot hay AI Agent.

Quyết định: Nhóm chọn Go với phạm vi nhỏ, thử nghiệm FAQ trong 2 tuần với 5 câu hỏi phổ biến nhất, sau đó đánh giá hiệu quả thực tế trước khi mở rộng hoặc cân nhắc ứng dụng AI.

---

## 7. Tài liệu tham khảo

-
