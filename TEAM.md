# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: NHOMSH
- Candidate problem nhóm chọn (1 câu): Khi họp nhóm xong, tôi muốn có ngay danh sách chia việc (To-do list), để không ai quên việc hoặc cãi nhau.
- Quyết định cuối (Go / Not Yet / No-Go):

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Nguyễn Lương Phúc | 2A202603889 | | phucluo |
| 2 | Nguyễn Tiến Đạt |2A202603922 | Nhóm trưởng, Phụ trách CP3, CP4  |duhocsinh4to10 |
| 3 | Trần Xuân Lộc | 2A202603951| | Kaylez-TXL |
| 4 | Nguyễn Quang Tiệp | 2A202603946 | | nguyenquangtiep |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | | | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | | | Assumption map, snapshot hoặc survey |
| CP4 — Research | | | Bảng research có link |
| CP5 — Quy trình trước/sau | | | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | | | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | | | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | | | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### NguyenLuongPhuc-2A202603889

**Phần việc phụ trách:**

- Chuẩn bị và pitch 3 Problem Card cá nhân; phản biện candidate của các thành viên khác.
- Tham gia gom cluster, xây Opportunity Solution Tree và chấm điểm shortlist để chọn candidate nhóm.
- Hỗ trợ research giải pháp có sẵn, vẽ quy trình trước/sau, hoàn thiện Problem Statement v0/v1, lựa chọn mức can thiệp AI và đánh giá quyết định cuối.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Đưa ra 3 candidate: cập nhật tiến độ nhóm, xác định yêu cầu bài lab và tìm lại quyết định cũ; mỗi candidate có actor, bottleneck và số liệu thời gian.
- Đặt câu hỏi phản biện về khả năng truy cập API Zalo, nguy cơ AI tóm tắt slide làm mất kiến thức quan trọng và khả năng phân biệt hổng kiến thức với lỗi đọc nhầm đề.
- Tham gia phân loại 12 candidate, tách opportunity khỏi solution và so sánh ba candidate trong shortlist. Tôi đồng ý không chọn candidate cá nhân và ủng hộ “Tạo To-do list sau họp” vì bottleneck rõ, đo được và vừa sức lab.
- Tham gia thu hẹp giải pháp từ AI tự ghi âm cuộc họp sang Workflow nhận ghi chú text thô, tạo bản nháp To-do list và bắt buộc con người duyệt.
- Góp phần bổ sung metric chất lượng, boundary, HITL, fallback, 5 tiêu chí eval, ma trận 4 rủi ro và ngưỡng dừng; thống nhất quyết định **Not Yet** vì kiểm chứng Value hiện còn chủ yếu từ nội bộ nhóm.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md` mục 2.1: ba candidate của Nguyễn Lương Phúc ở dòng #1–#3; các câu hỏi Phúc đặt cho candidate #4, #8 và #11.
- `report/team/group_report.md` mục 2.2–2.4: cluster, cây OST, bảng chấm điểm và lý do chọn candidate #7.
- `report/team/group_report.md` mục 3.1–3.3: assumption map và research Otter.ai/Fireflies.ai, Zoom AI Companion, pattern dùng prompt xử lý ghi chú text.
- `report/team/group_report.md` mục 4–8: quy trình trước/sau, Problem Statement v0/v1, Workflow, AI Canvas, eval, bốn rủi ro và quyết định Not Yet.
- `report/individual/2A202603889_NGUYENLUONGPHUC.md`: CP1, CP2, nhật ký tham gia nhóm và nhật ký dùng AI của cá nhân.
- `report/assets/`: hiện chưa có file riêng do tôi tạo được ghi nhận.
- Commit cá nhân: hiện chưa có commit đứng tên/tài khoản GitHub của tôi; cần `git add`, commit và push phần đóng góp bằng tài khoản của mình trước deadline.

**Điều mình học được từ phần nhóm:**

- Tôi học được rằng phải bắt đầu từ actor, quy trình, bottleneck và bằng chứng thay vì bắt đầu từ một tính năng AI. Một phương án No AI hoặc Rule vẫn cần được thử trước khi nâng lên Workflow; Agent chỉ phù hợp khi thật sự cần AI tự quyết bước tiếp theo. Tôi cũng hiểu metric không chỉ đo tốc độ mà phải đo độ đầy đủ, nội dung bịa và lỗi gán người/deadline. Boundary, bước con người kiểm tra và fallback là bắt buộc khi đầu vào có ghi chú mơ hồ. Cuối cùng, quyết định **Not Yet** là hợp lý khi giải pháp có vẻ khả thi nhưng bằng chứng Value chưa đủ mạnh.


### HoVaTen-MSSV

**Phần việc phụ trách:**

-

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

-

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

-

**Điều mình học được từ phần nhóm:**

-

### Nguyễn Tiến Đạt-2A202603922

**Phần việc phụ trách:**

- Nhóm trưởng, phụ trách chính CP3 (Hội tụ nhóm) và CP4 (Kiểm chứng & Research).

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Điều phối buổi hội tụ, gom nhóm ý tưởng (cluster), vẽ Opportunity Solution Tree (OST) và lập bảng chấm điểm candidate. Đảm bảo quyết định chọn To-do list dựa trên bằng chứng đo lường được (15-20 phút rà soát).

- Lập Assumption Map, thiết kế câu hỏi phỏng vấn, lên danh sách công cụ cần đối chiếu (Otter, Fireflies). Đưa ra bằng chứng phỏng vấn (user mất 20p dọn dẹp nháp), quyết định không dùng AI nghe trực tiếp do rủi ro tiếng ồn, chuyển sang giải pháp xử lý text (Workflow).

**Bằng chứng** :

- Các bảng cluster, OST, chấm điểm ở mục 2 `group_report.md`.
- Assumption map, interview snapshot, bảng research ở mục 3 `group_report.md`.
- File cá nhân `202603922_NguyenTienDat.md`.

**Điều mình học được từ phần nhóm:**

- Nhận ra sự khác biệt giữa "nỗi đau cá nhân" và "nỗi đau hệ thống". Việc tôi bị trôi tin nhắn là vấn đề của một người, nhưng việc cả nhóm cãi nhau vì chia việc không rõ ràng sau họp là nỗi đau ảnh hưởng đến tiến độ của tập thể.
- Học cách lùi lại khi bị "solution-first". Thay vì cố ép công nghệ thu âm (Whisper/API) vào quán cafe ồn ào, nhóm đã chọn giải pháp an toàn hơn: AI xử lý phần ghi chú thô của con người.

### HoVaTen-MSSV

**Phần việc phụ trách:**

-

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

-

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

-

**Điều mình học được từ phần nhóm:**

-
### HoVaTen-MSSV

**Phần việc phụ trách:**

-

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

-

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

-

**Điều mình học được từ phần nhóm:**

-
