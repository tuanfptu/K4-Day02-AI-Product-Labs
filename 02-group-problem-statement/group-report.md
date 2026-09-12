# 02 — Group Problem Statement (Bản nộp nhóm)

> Trạng thái: **bản chuẩn bị từ nội dung cá nhân, chưa phải artifact nhóm đã xác nhận**. Các phần convergence, quote phỏng vấn, danh sách thành viên và contribution phải được cập nhật sau buổi làm nhóm. Nội dung dưới đây không tự nhận hoạt động nhóm chưa diễn ra.

## Thành viên nhóm

| STT | Họ và tên | Mã học viên | Vai trò trong nhóm |
|---:|---|---|---|
| 1 | Hà Mạnh Tuân | 2A202602982 | Leader |
| 2 | Nguyễn Hải Long | 2A202602471 | Member |
| 3 | Nguyễn Nguyên Phong | 2A202602691 | Member |
| 4 | Đào Ngọc Quỳnh Thiên | 2A202602814 | Member |
| 5 |  Đỗ Thái Sơn | 2A202603021 | Member |
| 6 | Nguyễn Vũ Huy | 2A202602662 | Member |

**Candidate problem đề xuất để nhóm xem xét:** Sinh viên học nhiều môn phải tự hợp nhất deadline và yêu cầu từ LMS, email, chat và file nên dễ bỏ sót hoặc nhập sai lịch.

---

## Phase 3 — Group Convergence

### 3.1. Candidate đầu vào hiện có

| # | Người đưa ra | Candidate problem | Người gặp vấn đề | Điểm nghẽn | Cảm nhận nhanh của nhóm |
|---:|---|---|---|---|---|
| 1 | _Cá nhân_ | Gom deadline và yêu cầu đa nguồn | Sinh viên học 5–7 môn/kỳ | Lọc và diễn giải văn bản tự do | Chờ nhóm đánh giá |
| 2 | _Cá nhân_ | Literature review và tìm research gap khả thi | Sinh viên/researcher làm đề tài kỹ thuật | Xác minh gap có thật và phù hợp data/compute/time/skill | Self-report: hơn 3 ngày cho 1 case nhận diện va chạm ô tô trong tuần 05–11/09/2026 |
| 3 | _Cá nhân_ | Reconcile action item sau họp | Nhóm đồ án 3–6 người | Chuyển hội thoại thành commitment rõ | Chờ nhóm đánh giá |

> Nhóm cần bổ sung top 3 của các thành viên khác để đạt 9–12 candidates.

### 3.2. Cluster dự kiến

| Cluster | Candidates included | Pattern chung | Ghi chú |
|---|---|---|---|
| A. Quản lý công việc học tập | Deadline đa nguồn; action item sau họp | Thông tin phân mảnh phải chuyển thành task | Có workflow và metric rõ |
| B. Literature review có kiểm chứng | Literature Review & Research Gap Navigator | Tìm paper uy tín, evidence map và gap khả thi | Có case nhận diện va chạm ô tô |
| C. Khác | _Bổ sung từ nhóm_ | _Bổ sung_ | Chờ convergence thật |

### 3.3. Shortlist cá nhân để nhóm phản biện

| Candidate | Vì sao vào shortlist | Rủi ro / điều chưa rõ |
|---|---|---|
| Assignment Control Tower | Pain lặp lại, workflow rõ, outcome đo được | Primary evidence, quyền dữ liệu, willingness-to-pay |
| Literature Review & Research Gap Navigator | Có pain thật: hơn 3 ngày cho 1 case; đầu ra hỗ trợ chọn hướng nghiên cứu phù hợp nguồn lực | Self-report mới từ 1 người; full-text/licensing; AI có thể bịa gap |
| Group Action-item Reconciler | MVP nhỏ, task thiếu owner/deadline đo được | Tool hiện hữu và willingness-to-pay thấp |

### 3.4. Score chuẩn bị

| Candidate | Actor rõ | Workflow rõ | Pain có evidence | Impact đo được | Làm trong lab | So sánh R/W/A được | Hiểu domain | Tổng /35 |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Assignment Control Tower | 5 | 5 | 4 | 5 | 4 | 5 | 4 | **32** |
| Literature Review & Research Gap Navigator | 5 | 5 | 4 | 5 | 4 | 4 | 5 | **32** |
| Group Action-item Reconciler | 4 | 4 | 3 | 5 | 5 | 4 | 3 | **28** |

**Candidate đề xuất:** Assignment Control Tower.

**Vì sao chọn:** Bài toán lặp lại thường xuyên, có actor và workflow cụ thể. Bottleneck nằm ở bước chuyển thông tin đa nguồn thành task đúng. Có thể đo thời gian, missed-task rate, precision và edit rate. Khoảng trống giả định nằm ở provenance và conflict detection, không phải thêm một app nhắc việc chung chung.

**Lưu ý trước khi nhóm chốt:** Literature Review & Research Gap Navigator hiện có điểm ngang Assignment Control Tower vì đã có trải nghiệm thật trong tuần qua. Nhóm nên dùng validation và mức độ phù hợp với năng lực lab để chọn giữa hai bài. Action-item reconciler dễ thử nhưng nhiều công cụ cộng tác đã hỗ trợ summary và task extraction, còn willingness-to-pay của nhóm sinh viên có thể thấp.

**Disagreement:** Chưa có dữ liệu thảo luận nhóm. Cần ghi ai phản đối điểm nào và cách chốt sau buổi convergence.

---

## Phase 4 — Quick Validation + Research

### 4.1. Quick validation

| Nguồn | Số người / mẫu | Tín hiệu xác nhận | Tín hiệu phản bác | Nhóm sửa problem thế nào |
|---|---:|---|---|---|
| Interview | Chưa thực hiện | Không có quote thật | Chưa biết pain đa nguồn có đủ lớn | Phỏng vấn 2–3 người trước khi chốt PS v1 |
| Survey / poll | Chưa thực hiện | Không có dữ liệu thật | Chưa biết baseline missed assignment | Poll 5–10 người, hỏi theo hành vi gần nhất |
| Diary/log | Đề xuất 10–15 người trong 2 tuần | Ghi nơi assignment xuất hiện và thời gian nhập lịch | Có thể cho thấy LMS hiện tại đã đủ | Thu time-log và lỗi thực tế thay vì hỏi chung chung |

**Insight hiện tại:** Desk research xác nhận reminder đúng lúc có thể tác động đến submission, nhưng chưa xác nhận pain phân mảnh tại nhóm người dùng mục tiêu. Vì vậy candidate vẫn ở trạng thái hypothesis.

### 4.2. Research giải pháp đã có

| Nguồn / tool / case | Link | Họ giải quyết bước nào? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Google Classroom Calendar | [Google Support](https://support.google.com/edu/classroom/answer/6272985?hl=en-GB) | Đưa assignment có due date lên lịch | Tích hợp tốt trong Classroom | Không hợp nhất đầy đủ email/chat/file | Không build reminder app chung chung |
| Automated Educative Nudges | [IEEE DOI](https://doi.org/10.1109/TLT.2021.3064613) | Nhắc deadline chủ động | Có RCT và pilot | Không chứng minh pain tại Việt Nam | Cơ chế reminder đáng pilot |
| UNESCO GenAI guidance | [UNESCO](https://www.unesco.org/en/articles/guidance-generative-ai-education-research?hub=195885) | Định hướng kiểm soát AI trong giáo dục | Nhấn mạnh human-centred validation và privacy | Không phải bằng chứng sản phẩm | Boundary và consent phải có từ đầu |

**Research takeaway:** Nên thử workflow forward-only có dẫn nguồn và human confirmation. Không nên build Agent đọc toàn bộ inbox/chat hoặc tự thay đổi deadline trước khi có bằng chứng về pain, trust và quyền dữ liệu.

---

## Phase 5 — Workflow + Problem Statement

### 5.1. Current workflow bản chuẩn bị

```text
[Mở LMS/email/chat] → [Lọc thông báo] → [Đọc bài đăng/file] → [Diễn giải deadline và deliverable]
→ [Nhập Calendar/To-do] → [Chọn reminder] → [Mở lại nguồn trước khi nộp]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Sinh viên | Danh sách kênh | Nguồn cần kiểm tra | Hằng ngày | Handoff giữa nhiều hệ thống |
| 2 | Sinh viên | Thông báo mới | Item liên quan | Chưa đo | Có thể bỏ sót |
| 3 | Sinh viên | Bài đăng/file | Nội dung yêu cầu | Chưa đo | Văn bản tự do |
| 4 | Sinh viên | Nội dung yêu cầu | Deadline/deliverable/rubric | Chưa đo | **Bottleneck chính** |
| 5 | Sinh viên | Task đã diễn giải | Calendar/To-do item | Chưa đo | Lỗi nhập tay |
| 6 | Sinh viên | Task | Reminder | Mỗi task | Có nguy cơ notification fatigue |
| 7 | Sinh viên | Calendar item | Yêu cầu đã kiểm lại | Trước khi nộp | Rework để tạo trust |

**Bottleneck chính:** Sinh viên phải lọc và diễn giải thông tin không cấu trúc trước khi lịch trở nên hữu ích. Một cập nhật ở kênh khác có thể làm dữ liệu đã nhập lỗi thời.

### 5.2. Future workflow bản chuẩn bị

```text
[Sinh viên forward nguồn được phép] → [AI trích field + source snippet]
→ [Rule kiểm ngày, duplicate, conflict] → [Sinh viên xác nhận/sửa]
→ [Ghi Calendar/To-do] → [Rule gửi tối đa 2 reminder]

Fallback: confidence thấp hoặc nguồn mâu thuẫn thì không tạo deadline; hiển thị “cần kiểm tra”.
```

| Metric | Trước | Sau kỳ vọng | Cách đo |
|---|---:|---:|---|
| Tổng thời gian | Đo tuần 0 | Giảm ≥50% | Time diary, median phút/tuần |
| Số bước | 7 | 6 | Đếm bước workflow |
| Số bước thủ công | 7 | 2–3 | Audit theo item |
| Bottleneck chính | Lọc + diễn giải | Review case khó | Edit/abstain log |
| Risk mới | Không có AI extraction | AI trích sai deadline | Precision, edit rate, incident log |

### 5.3. Problem Statement v0

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên học 5–7 môn/kỳ và nhận thông tin qua ít nhất hai kênh. |
| **Workflow** | Theo dõi nguồn, lọc, đọc, diễn giải, nhập lịch, đặt nhắc và kiểm lại. |
| **Bottleneck** | Chuyển văn bản tự do và cập nhật đa nguồn thành task đúng. |
| **Impact** | Tốn thời gian hằng ngày, lỗi nhập lịch và nguy cơ bỏ sót bài. |
| **Success Metric** | Giảm thời gian ≥50%; deadline precision ≥95%; task bỏ sót giảm ≥30%; edit rate <15%. |
| **Boundary** | Chỉ đọc nội dung được forward/cấp quyền; không tự đổi deadline hoặc nộp bài; luôn giữ link nguồn. |

**AI phản biện v0:** Primary evidence và baseline nội địa còn thiếu. Nhóm cần thay số giả thuyết bằng time-log, interview và survey trước khi viết v1 chính thức.

---

## Phase 6 — Rule / Workflow / Agent + Decision

### 6.0. Ma trận độ phù hợp

- Độ mơ hồ: **Cao**, vì deadline và yêu cầu có thể nằm trong văn bản tự do hoặc mâu thuẫn.
- Độ phức tạp: **Cao**, vì có nhiều nguồn, nhiều bước validation và nhánh review.

**Bài toán nằm ở ô:** Workflow nhiều bước có AI hỗ trợ, chưa cần Agent tự lập kế hoạch.

### 6.1. So sánh Rule / Workflow / Agent

| Mức | Phương án | Khi nào đủ | Rủi ro | Chọn? |
|---|---|---|---|---|
| **Rule** | Sync due date có cấu trúc, dedupe, kiểm format và nhắc D-3/D-1 | Một LMS và input sạch | Không hiểu văn bản tự do | Dùng cho validation và reminder |
| **Workflow** | AI trích field, rule kiểm, người dùng xác nhận rồi ghi lịch | Input đa nguồn nhưng từng item review được | AI trích sai; người dùng bỏ qua review | **Chọn** |
| **Agent** | Tự đọc kênh, lập kế hoạch và thay đổi lịch | Chỉ khi trust và error cost đã được chứng minh | Quyền dữ liệu rộng, hành động sai khó phát hiện | Chưa chọn |

**5 câu hỏi chốt:**

1. Rule giải được phần structured nhưng không giải quyết đầy đủ văn bản tự do đa nguồn.
2. Workflow có nhánh conflict, confidence thấp và cập nhật deadline.
3. Chưa cần Agent tự lập kế hoạch hoặc gọi nhiều tool không giám sát.
4. Sinh viên phát hiện lỗi ở màn hình confirm hoặc khi mở source snippet; cần sửa trước khi ghi lịch.
5. Có thể hạ về rule-only nếu phần lớn input đã có due date có cấu trúc.

**Mức chọn:** Workflow.

**Vì sao chọn:** Bài toán cần hiểu văn bản nhưng hậu quả của deadline sai yêu cầu review. Workflow kết hợp AI, rule và human confirmation giới hạn quyền hạn, đồng thời tạo audit log để đo precision và edit rate.

**Vì sao không chọn mức đơn giản hơn:** Rule không đọc ổn định deadline và điều kiện nộp trong văn bản tự do. Tuy nhiên rule-only vẫn là baseline và phương án fallback nếu dữ liệu thực tế đã có cấu trúc.

### 6.2. Problem Statement v1 dự kiến sau validation

| Field | Nội dung |
|---|---|
| **Actor** | Sinh viên học 5–7 môn/kỳ, nhận yêu cầu qua ít nhất hai kênh và xác nhận pain qua validation nhóm. |
| **Workflow** | Forward nguồn → AI trích field có dẫn nguồn → rule kiểm → người dùng xác nhận → ghi lịch → nhắc giới hạn. |
| **Bottleneck** | Lọc và diễn giải thông tin đa nguồn, đặc biệt khi có update hoặc conflict. |
| **Impact** | Baseline cần thay bằng số đo nhóm; outcome chính là thời gian tổng hợp và task bỏ sót. |
| **Success Metric** | Deadline precision ≥95%; deliverable precision ≥90%; thời gian giảm ≥50%; missed task giảm ≥30%; edit rate <15%. |
| **Boundary** | Forward-only trong pilot; không đọc nguồn chưa cấp quyền; không tự đổi deadline hoặc nộp bài; abstain khi conflict. |
| **AI intervention point** | Sau khi người dùng forward nội dung và trước bước rule validation/human confirmation. |
| **Mức chọn** | Workflow vì cần hiểu văn bản nhưng mọi hành động lịch đều phải được duyệt. |
| **Rủi ro & người thật kiểm tra** | Rủi ro lớn nhất là deadline sai; chính sinh viên kiểm source snippet và xác nhận từng item. |

### 6.3. Final decision

| Câu hỏi | Yes / Not Yet / No | Ghi chú |
|---|---|---|
| Actor + workflow rõ chưa? | Yes | Actor và các bước đã cụ thể ở mức hypothesis. |
| Baseline + metric đo được chưa? | Not Yet | Có metric nhưng chưa có baseline thật. |
| Data/input đủ dùng chưa? | Not Yet | Cần tối thiểu 100 thông báo đã ẩn dữ liệu nhạy cảm. |
| AI sai, hậu quả chấp nhận được không? | Not Yet | Chỉ chấp nhận nếu human confirm và abstain hoạt động. |
| Có người review/owner không? | Yes | Sinh viên sở hữu task và duyệt trước khi ghi lịch. |
| Có cách non-AI đơn giản hơn không? | Yes | Form chuẩn, LMS sync và rule reminder là baseline. |

**Decision:** **Not Yet**.

**Lý do:** Cơ chế tác động và workflow hợp lý, nhưng chưa có primary evidence về fragmentation, baseline missed assignment, willingness-to-connect-data và willingness-to-pay. Nhóm nên validate pain và trust trước, sau đó pilot workflow nhỏ thay vì build Agent.

**Nếu Not Yet — cần validate gì trước:** Interview 10–15 sinh viên; diary study 2 tuần; 100 thông báo thật đã ẩn dữ liệu nhạy cảm; benchmark với form/rule-only; test forward-only và đo willingness-to-use.

**Exit / rollback:** Dừng AI hoặc quay về rule-only nếu phần lớn input đã có cấu trúc, người dùng không chấp nhận forward dữ liệu, edit rate vẫn >25% sau hai vòng cải tiến, hoặc xảy ra sự cố privacy nghiêm trọng.

---

### Self-check nộp phần 02

- [ ] Có nhật ký hội tụ 9–12 → 1 do nhóm xác nhận
- [ ] Có validation với quote thật + research
- [x] Có workflow trước/sau, bottleneck, boundary và fallback ở mức chuẩn bị
- [ ] Có PS v0 → v1 dựa trên baseline nhóm thật
- [x] Có so sánh Rule/Workflow/Agent + quyết định Not Yet có lý do
