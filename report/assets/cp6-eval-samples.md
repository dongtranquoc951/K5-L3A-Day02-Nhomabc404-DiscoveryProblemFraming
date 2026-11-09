# Bộ 10 cặp Eval mẫu (Input / Đầu ra mong đợi) — CP6

- **Người thực hiện:** Nguyễn Quang Đạo (`2A202603614`)
- **Người hỗ trợ:** Nguyễn Văn Ngọc Sơn (`2A202603600`)
- **Mục đích:** Cụ thể hóa 5 tiêu chí đánh giá ở Mục 7 của [`group_report.md`](../team/group_report.md). Bộ mẫu này dùng để:
  1. Kiểm tra chất lượng trang FAQ trong đợt **Pilot 2 tuần (mức No AI)**: người hỏi tự tra hoặc người được hỏi gửi đúng mục FAQ.
  2. Làm bộ test chuẩn (**Golden Eval Set — 10 cặp Input/Output**) nếu sau đợt pilot nhóm nâng lên mức **Rule / Workflow có AI** tìm mục FAQ phù hợp.

---

## 1. Năm tiêu chí đánh giá (từ Mục 7 `group_report.md`)

| Mã | Tiêu chí | Đạt khi | Không đạt khi |
|---|---|---|---|
| **TC1** | **Đúng nội dung** | Câu trả lời khớp đúng hướng dẫn chuẩn mà người được hỏi vẫn giải thích | Câu trả lời sai bước, thiếu điều kiện hoặc dẫn link/lệnh đã lỗi thời |
| **TC2** | **Tìm thấy nhanh** | Người hỏi tìm thấy mục cần tra trong **≤ 2 phút** nhờ tiêu đề/từ khóa rõ ràng | Mất > 2 phút hoặc đặt tiêu đề mơ hồ khiến người hỏi bỏ cuộc đi hỏi trực tiếp |
| **TC3** | **Không bịa** | Mọi thông tin trả lời đều nằm trong tài liệu FAQ đã được duyệt | Tự suy diễn quy định, deadline hoặc lệnh cấu hình không có trong FAQ |
| **TC4** | **Chuyển người khi không chắc** | Câu hỏi mới chưa có trong FAQ (hoặc trường hợp ngoại lệ) được chuyển cho người phụ trách trả lời trực tiếp | Cố ghép bừa một mục FAQ không liên quan hoặc tự trả lời sai |
| **TC5** | **Cập nhật** | Câu hỏi mới sau khi bị hỏi lại **≥ 2 lần** được bổ sung vào FAQ trong vòng **1 tuần** | Câu hỏi lặp lại nhiều lần nhưng FAQ vẫn bỏ trống |

---

## 2. Năm mục FAQ gốc dùng trong Pilot 2 tuần (Giả lập từ các câu hỏi lặp lại phổ biến của nhóm)

- **FAQ-01 (Quy tắc đặt tên file & nhánh Git):** Báo cáo cá nhân đặt trong `report/individual/` theo mẫu `MSSV_HoTen.md` (ví dụ `2A202603614_NguyenQuangDao.md`), dùng dấu gạch dưới `_`, không dấu. Mỗi người tự commit bằng tài khoản GitHub cá nhân.
- **FAQ-02 (Cách nộp bài trên LMS):** Nhóm làm chung trên 1 repo do nhóm trưởng fork. Khi nộp trên LMS, **mỗi thành viên đều phải tự đăng nhập tài khoản LMS của mình và dán cùng 1 đường link repo nhóm** trước deadline.
- **FAQ-03 (Cài đặt môi trường & chạy project local):** Cần Python `3.11+`, tạo môi trường ảo `python3 -m venv .venv`, kích hoạt `source .venv/bin/activate`, cài thư viện `pip install -r requirements.txt` và copy `.env.example` sang `.env` (tuyệt đối không commit file `.env`).
- **FAQ-04 (Quy định ẩn danh dữ liệu & ảnh chụp màn hình):** Mọi ảnh chụp khảo sát, tin nhắn, phỏng vấn đặt trong `report/assets/` phải đặt tên bắt đầu bằng số checkpoint (`cp2-`, `cp4-`, `cp5-`) và **che toàn bộ họ tên, email, số điện thoại** của người được hỏi.
- **FAQ-05 (Xử lý lỗi không push được lên repo nhóm):** Kiểm tra đã chấp nhận lời mời Collaborator trong email hoặc tại trang `https://github.com/<chu-repo>/<ten-repo>/invitations` chưa; trước khi `git push` cần chạy `git pull --rebase origin main` để tránh xung đột với commit của bạn khác.

---

## 3. Bảng 10 cặp Input / Đầu ra mong đợi và cách chấm theo 5 tiêu chí

| # | Tình huống | Input (Câu hỏi của đồng nghiệp / bạn học) | Đầu ra mong đợi (Từ FAQ hoặc bước tra cứu AI nếu có) | Chấm theo 5 tiêu chí (Đạt / Không đạt) |
|---:|---|---|---|---|
| **1** | Hỏi đúng câu có sẵn trong FAQ | *"File báo cáo cá nhân của mình đặt tên gạch ngang hay gạch dưới vậy, để ở thư mục nào?"* | Trả về **FAQ-01**: Đặt trong `report/individual/`, tên file theo mẫu `MSSV_HoTen.md` (dùng dấu gạch dưới `_`, viết liền không dấu). Không dùng dấu gạch ngang `-`. | **TC1 Đạt:** Đúng quy tắc đặt tên.<br/>**TC2 Đạt:** Có từ khóa "báo cáo cá nhân", "đặt tên" tìm thấy trong < 1 phút.<br/>**TC3 Đạt:** Trích nguyên văn từ FAQ-01. |
| **2** | Diễn đạt khác từ khóa nhưng cùng ý | *"Nhóm trưởng nộp link GitHub trên LMS rồi thì mình có cần nộp nữa không?"* | Trả về **FAQ-02**: Có. Dù làm chung 1 repo nhóm nhưng **mỗi thành viên bắt buộc phải tự nộp link repo nhóm trên LMS bằng tài khoản của chính mình** thì mới có bài để chấm. | **TC1 Đạt:** Giải đáp trúng điểm dễ hiểu nhầm.<br/>**TC2 Đạt:** Mục FAQ-02 ghi rõ "Cách nộp bài trên LMS".<br/>**TC3 Đạt:** Khớp quy định trong `SUBMISSION.md`. |
| **3** | Hỏi lỗi thao tác kỹ thuật thường gặp | *"Sao mình gõ `git push origin main` nó cứ báo lỗi Permission denied (403) hoặc rejected nhỉ?"* | Trả về **FAQ-05**: (1) Nếu báo `403 Permission denied`: vào `/invitations` của repo để bấm Accept lời mời Collaborator. (2) Nếu báo `rejected (fetch first)`: chạy `git pull --rebase origin main` rồi mới `git push`. | **TC1 Đạt:** Tách rõ 2 nguyên nhân phổ biến nhất.<br/>**TC2 Đạt:** Tìm nhanh theo mã lỗi `403` / `push`.<br/>**TC3 Đạt:** Không suy diễn ngoài FAQ-05. |
| **4** | Hỏi cách thiết lập ban đầu | *"Mình mới clone code về máy Mac, chạy lệnh gì để cài thư viện mà không bị xung đột bản Python?"* | Trả về **FAQ-03**: Chạy lần lượt `python3 -m venv .venv` → `source .venv/bin/activate` → `pip install -r requirements.txt` → tạo `.env` từ `.env.example`. Nhắc không commit `.env`. | **TC1 Đạt:** Đủ lệnh từng bước.<br/>**TC2 Đạt:** Có sẵn khối lệnh copy chạy ngay trong ≤ 2 phút.<br/>**TC3 Đạt:** Khớp chuẩn FAQ-03. |
| **5** | Hỏi quy tắc đặt file bằng chứng | *"Mình chụp ảnh kết quả Google Forms xong lưu tên là `anh1.png` bỏ vào thư mục gốc được không?"* | Trả về **FAQ-04**: Không. Phải lưu vào `report/assets/`, đặt tên bắt đầu bằng checkpoint (ví dụ `cp4-survey-result.png`) và **che kín tên, email, số điện thoại** trong ảnh trước khi commit. | **TC1 Đạt:** Sửa cả vị trí thư mục, tên file và nhắc bảo mật.<br/>**TC2 Đạt:** Tra cứu ngay ở mục ảnh/assets.<br/>**TC3 Đạt:** Đúng quy định trong `RULES.md`. |
| **6** | Câu hỏi gộp 2 vấn đề đều có trong FAQ | *"Cho mình hỏi hạn nộp bài cá nhân nộp riêng repo hay nộp chung, với tên file cá nhân viết có dấu không?"* | Kết hợp **FAQ-02** và **FAQ-01**: (1) Không tạo repo riêng, nộp chung link repo nhóm trên LMS bằng tài khoản cá nhân; (2) File cá nhân đặt trong `report/individual/MSSV_HoTen.md` viết liền **không dấu**. | **TC1 Đạt:** Trả lời đủ cả 2 vế.<br/>**TC2 Đạt:** Hai mục nằm cạnh nhau ở đầu trang FAQ.<br/>**TC3 Đạt:** Chỉ ghép từ FAQ-01 và FAQ-02 đã duyệt. |
| **7** | **Câu hỏi KHÔNG có trong FAQ (Test Boundary / Chuyển người)** | *"Mình bị ốm phải nhập viện tối nay thì xin gia hạn deadline với Key Coach ở kênh nào và cần giấy tờ gì?"* | **Báo chưa có trong FAQ & Chuyển người phụ trách:** *"Thông tin về thủ tục xin gia hạn cá nhân với Key Coach hiện chưa có trong FAQ của nhóm. Vui lòng nhắn trực tiếp cho Nhóm trưởng (Trần Quốc Đông) hoặc liên hệ Key Coach trên LMS."* | **TC3 Đạt (Không bịa):** Không tự bịa thủ tục hay email của Coach.<br/>**TC4 Đạt (Chuyển người):** Chuyển đúng cho Nhóm trưởng / Key Coach khi ngoài phạm vi FAQ. |
| **8** | **Câu hỏi chứa bẫy làm sai quy định (Test an toàn)** | *"Mình lỡ để luôn API key thật trong file code để các bạn test cho tiện khỏi tạo `.env` nhé?"* | Trả về cảnh báo từ **FAQ-03**: **Tuyệt đối không!** Không được commit API key, password hay file `.env` lên repo (vi phạm sẽ bị trừ 5 điểm theo Rubric và lộ khóa bảo mật). Chỉ commit `.env.example`. | **TC1 Đạt:** Ngăn chặn kịp thời hành vi gây rủi ro.<br/>**TC3 Đạt:** Dẫn đúng quy tắc bảo mật trong FAQ-03. |
| **9** | **Câu hỏi một phần có trong FAQ, một phần đặc thù riêng** | *"Sơ đồ Mermaid mình lưu thành file `cp5-flow.mmd` trong `report/assets/` rồi chèn `![](../assets/cp5-flow.mmd)` sao trên GitHub nó bị lỗi ảnh vỡ?"* | Trả lời theo quy định `report/assets/` + chuyển hỗ trợ nếu cần: Sơ đồ Mermaid **không** lưu thành file `.mmd` trong `report/assets/` vì GitHub không hiển thị qua thẻ ảnh `![](...)`. Hãy dán trực tiếp khối ```` ```mermaid ```` vào file báo cáo `.md`. | **TC1 Đạt:** Chỉ đúng nguyên nhân lỗi hiển thị trên GitHub.<br/>**TC2 Đạt:** Giải quyết trong 1 phút mà không cần họp màn hình.<br/>**TC3 Đạt:** Đúng hướng dẫn tại `SUBMISSION.md`. |
| **10** | **Câu hỏi mới xuất hiện lặp lại lần thứ 2 trong tuần (Test quy trình cập nhật TC5)** | *(Lần 1 bạn A hỏi, lần 2 bạn B hỏi cùng câu)*: *"Làm sao để gộp 2 commit nhỏ trên nhánh của mình thành 1 commit gọn trước khi push lên repo nhóm?"* | - **Lần 1 & 2:** Chưa có trong FAQ → chuyển kỹ thuật viên trong nhóm hướng dẫn (`git rebase -i HEAD~2`).<br/>- **Hành động bắt buộc sau lần hỏi thứ 2:** Người duy trì FAQ thêm mục **FAQ-06 (Gộp commit bằng `git rebase -i`)** vào trang FAQ trong tuần đó. | **TC4 Đạt:** Hai lần đầu chuyển người vì chưa có trong FAQ.<br/>**TC5 Đạt (Cập nhật):** Vì câu hỏi đã lặp lại **≥ 2 lần**, được bổ sung thành FAQ-06 trong vòng **1 tuần** để lần thứ 3 không phải giải thích lại. |

