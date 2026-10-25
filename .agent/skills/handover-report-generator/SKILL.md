---
name: handover-report-generator
description: Synthesize and summarize the full chat thread context, critical issues, key decisions, and core information into an executive handover report. Use when the user asks to summarize the conversation, create a handoff report, compile session context, or prepare a handover summary.
---
# Handover Report Generator
Tổng hợp toàn bộ lịch sử phiên làm việc thành Báo cáo bàn giao (Handover Report) chuyên nghiệp.
## Workflow
Trích xuất ngữ cảnh và trình bày báo cáo theo đúng 5 mục sau:
1. **Executive Summary**: Mục tiêu chính của phiên làm việc và trạng thái tổng quan hiện tại (Completed / In Progress / Blocked).
2. **Thông tin cốt lõi & Quyết định quan trọng (Core Decisions)**: Danh sách các quyết định về nghiệp vụ, kiến trúc hoặc thiết kế đã chốt kèm lý do.
3. **Vấn đề đã xử lý & Khó khăn tồn đọng (Key Issues & Blockers)**: Các điểm nghẽn đã giải quyết và các rủi ro/câu hỏi mở `[Cần xác nhận thêm]`.
4. **Danh sách tài nguyên & Deliverables**: Các file spec, tài liệu, API schema hoặc code đã tạo/chỉnh sửa trong phiên.
5. **Kế hoạch bàn giao & Hành động tiếp theo (Next Actions)**: Các đầu việc cụ thể cần người/agent tiếp theo xử lý theo thứ tự ưu tiên.
