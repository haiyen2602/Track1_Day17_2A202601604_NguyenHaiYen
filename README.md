# Track 1 — Day 17: Finding and Validating Pain Points
## Case C — AI Support Radar

> **Đổi tên repo trước khi nộp:** `Track1_Day17_MHV_HoVaTen`

Repo cá nhân này dùng để lưu toàn bộ kết quả bài lab theo 4 chặng:
1. Problem Hypothesis
2. Conversation Guide
3. Interview Practice
4. Reflection & Revision

**Lưu ý quan trọng:** Chặng 3 yêu cầu evidence từ cuộc phỏng vấn thật. Không tự tạo quote, transcript, recording hoặc kết luận “validated”.

---

# 1. Thông tin cá nhân và nhóm

- **Mã học viên (MHV):** `<điền MHV>`
- **Họ và tên:** `<điền họ tên>`
- **Tên nhóm:** `<điền tên nhóm>`
- **Thành viên nhóm:** `<điền thành viên>`
- **Case đã chọn:** **Case C — AI Support Radar**

---

# 2. Problem Hypothesis — kết quả Chặng 1

## Solution capability trung tính

> Tổng hợp các dấu hiệu học tập rời rạc sau một phiên học để giúp con người nhận biết và ưu tiên các nhu cầu hỗ trợ có thể đang bị bỏ sót.

## Problem Hypothesis chính

> Khi learner đang học một phiên online/self-paced và gặp một phần chưa hiểu nhưng vẫn cần tiếp tục, họ có thể không yêu cầu hỗ trợ ngay mà thử tự xử lý bằng cách xem lại, chuyển qua lại, sửa đáp án, ghi chú, hỏi AI hoặc bỏ qua tạm thời. Nếu phần vướng không được giải quyết, learner mất thời gian và có thể mang lỗ hổng sang bước tiếp theo; trong khi instructor thường chỉ biết khi learner chủ động hỏi hoặc khi đã xuất hiện kết quả muộn.

## Competing Hypothesis

> Pain chính có thể nằm ở instructor: sau một phiên học có nhiều learner, instructor thiếu visibility để biết ai đang gặp khó khăn nhưng chưa chủ động hỏi và họ đang vướng ở phần nào, dẫn đến triage thủ công, bỏ sót hoặc hỗ trợ muộn.

Chi tiết: [`docs/01_problem_hypothesis.md`](docs/01_problem_hypothesis.md)

---

# 3. Conversation Guide — phiên bản cuối

- Bản chuẩn bị cho Chặng 2: [`docs/02_conversation_guide.md`](docs/02_conversation_guide.md)
- Sau Chặng 3, phải cập nhật file trên thành **phiên bản đã chỉnh sau luyện phỏng vấn**.
- Không pitch hoặc cho interviewee xem solution directive.
- Tập trung vào hành vi đã xảy ra trong quá khứ.

---

# 4. Practice Reflection — Chặng 4

Sau vòng luyện, điền vào [`docs/04_practice_reflection.md`](docs/04_practice_reflection.md).

Ba câu bắt buộc:

1. Câu hỏi nào đã giúp user kể một tình huống cụ thể?
2. Chỗ nào mình cần làm tốt hơn ở lần phỏng vấn thật?
3. Sau khi luyện, mình đã sửa Conversation Guide ở đâu và vì sao?

---

# 5. AI Support Log

| Hạng mục | AI đã hỗ trợ gì? | Điểm AI có thể sai / hời hợt | Tôi đã kiểm tra / chỉnh gì? |
|---|---|---|---|
| Problem framing | Hỗ trợ reverse-engineer Solution → Change → Actor → Situation/Job → Pain → Evidence | AI chỉ có thể tạo hypothesis, không có evidence thực tế | Nhóm phải dùng interview để kiểm chứng |
| Conversation Guide | Hỗ trợ chuyển Evidence Map thành câu hỏi quá khứ, tránh hypothetical | Một số câu hỏi có thể vẫn dẫn dắt hoặc chứa giả định | Rà soát bằng checklist Chặng 2 và sửa sau practice |
| Interview Practice | Hỗ trợ tạo template notes và probe bank | AI không được bịa quote, transcript hoặc phản ứng interviewee | Chỉ ghi dữ liệu thật từ buổi phỏng vấn |
| Reflection | Hỗ trợ tạo cấu trúc reflection | AI không thể thay trải nghiệm của interviewer | Reflection phải dựa trên recording/notes thật |

---

# Repo structure

```text
Track1_Day17_MHV_HoVaTen/
├── README.md
├── .gitignore
├── docs/
│   ├── 01_problem_hypothesis.md
│   ├── 02_conversation_guide.md
│   ├── 03_interview_runbook.md
│   ├── 04_practice_reflection.md
│   └── 05_submission_checklist.md
├── interview/
│   ├── notes.md
│   ├── recording_link.md
│   └── README.md
└── evidence/
    └── README.md
```

## Recording

Nếu có file ghi âm cục bộ, đặt một trong các file sau vào `interview/`:

```text
recording.m4a
recording.mp3
recording.mp4
```

Nếu file nằm trên Drive/nền tảng nội bộ, điền link vào:

[`interview/recording_link.md`](interview/recording_link.md)

Link phải mở được với giảng viên/TA theo yêu cầu của lớp và không cần để công khai toàn Internet.

---

# Trạng thái

- [x] Chặng 1 — Problem Hypothesis
- [x] Chặng 2 — Conversation Guide bản chuẩn bị
- [ ] Chặng 3 — Interview Practice thực tế
- [ ] Chặng 4 — Reflection & Revision
- [ ] Thay placeholder MHV / Họ tên / Nhóm
- [ ] Thêm recording hoặc recording link
- [ ] Chỉnh Conversation Guide sau practice
- [ ] Kiểm tra checklist trước khi nộp
