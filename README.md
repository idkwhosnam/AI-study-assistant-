# AI-study-assistant-
Hệ thống hỗ trợ học tập thông minh tích hợp AI &amp; Quản lý thời gian Pomodoro
Đây là bản dự thảo nội dung **README.md** chuyên nghiệp, đầy đủ và được cấu trúc chặt chẽ để bạn đưa lên GitHub.

Nội dung này tổng hợp toàn bộ các điểm sáng về nghiệp vụ, kỹ thuật, và mô hình kinh doanh mà chúng ta đã thảo luận, được trình bày dưới ngôn ngữ của chuyên ngành **Hệ thống Thông tin Quản lý (MIS)**.

-----

### Cách sử dụng:

1.  Tạo file tên là `README.md` trong thư mục dự án.
2.  Copy toàn bộ nội dung bên dưới vào.
3.  Commit lên GitHub và gửi link cho team.

-----

# AI Study Assistant Platform (Dự án Tốt nghiệp MIS)

> **Hệ thống hỗ trợ học tập thông minh tích hợp AI & Quản lý thời gian Pomodoro**

  

## 1. Tổng quan Dự án (Executive Summary)

Dự án xây dựng một nền tảng **EdTech (Công nghệ giáo dục)** giải quyết vấn đề "quá tải thông tin" của sinh viên. Hệ thống kết hợp phương pháp quản lý thời gian **Pomodoro** với sức mạnh của **Generative AI** để biến các tài liệu giáo trình dày cộm thành các đơn vị kiến thức dễ học (Sơ đồ tư duy & Flashcard) chỉ trong vài giây.

### Mục tiêu cốt lõi:

  * **Tối ưu thời gian:** Giảm 80% thời gian đọc hiểu tài liệu và soạn đề cương.
  * **Cá nhân hóa:** Học theo nhu cầu (On-demand), học chương nào xử lý chương đó.
  * **Hiệu quả chi phí:** Mô hình kinh doanh bền vững, tối ưu chi phí vận hành AI.

-----

## 2. Giải pháp & Tính năng Chính

### A. Quy trình Nghiệp vụ Thông minh (Smart Workflow)

Khác với các công cụ tóm tắt truyền thống, hệ thống áp dụng quy trình **"Chia để trị" (Chunking Strategy)**:

1.  **Structure Scanning:** Hệ thống quét mục lục file (PDF/DOCX) ngay khi upload mà chưa xử lý nội dung -\> **Tiết kiệm chi phí.**
2.  **User Selection:** Người dùng chọn đúng chương cần học (Ví dụ: Chỉ học Chương 1).
3.  **AI Processing:** Hệ thống chỉ gửi dữ liệu chương đó lên API để tạo bài học.
4.  **Learning:** Hiển thị kết quả dưới dạng Mindmap (Tổng quan) và Flashcard (Chi tiết).

### B. Tính năng nổi bật

  * **Integrated Pomodoro:** Đồng hồ tập trung tích hợp, chặn xao nhãng.
  * **Auto-Mindmap:** Tự động vẽ cây kiến thức từ văn bản (có thể chỉnh sửa).
  * card **Smart Flashcards:** Tạo câu hỏi ôn tập kèm đáp án, hỗ trợ chế độ Spaced Repetition (Lặp lại ngắt quãng).
  * **Wallet & Pay-as-you-go:** Ví điện tử, trừ tiền theo từng chương tài liệu được xử lý (1.500đ/chương).

-----

## 🛠 3. Kiến trúc Hệ thống & Công nghệ (Tech Stack)

Dự án áp dụng mô hình phát triển **AI-Assisted Development** (Sử dụng AI để hỗ trợ code cho team Non-tech).

| Thành phần | Công nghệ lựa chọn | Lý do (MIS Perspective) |
| :--- | :--- | :--- |
| **Frontend** | **Next.js (React)** | Tối ưu SEO, render nhanh, dễ tích hợp UI đẹp (V0.dev). |
| **Backend & DB** | **Supabase** | Backend-as-a-Service. Có sẵn Auth, Database PostgreSQL, API (Không cần code nhiều). |
| **AI Processing** | **Python / LangChain** | Thư viện mạnh nhất để xử lý văn bản và kết nối LLM. |
| **AI Model** | **GPT-4o-mini** | Chi phí cực rẻ ($0.15/1M tokens), tốc độ nhanh, phù hợp bài toán tóm tắt. |
| **Development** | **Cursor IDE** | Công cụ code tích hợp AI giúp team fix bug và generate code. |

-----

## 🗄 4. Thiết kế Cơ sở Dữ liệu (Database Schema)

Hệ thống tuân thủ chuẩn hóa **3NF**, tập trung vào việc quản lý phân mảnh tài liệu.

### ERD Sơ bộ:

  * **Users:**
  * **Documents:** 
  * **DocumentSections (Core):** 
  * **Flashcards:**
  * **MindmapNodes:**
  * **Transactions:** 

-----

## 5. Mô hình Kinh doanh & Tài chính (Business Model)

Dự án áp dụng mô hình lai (Hybrid) để tối đa hóa doanh thu và giảm rủi ro.

### Các nguồn thu (Revenue Streams):

1.  **Pay-as-you-go (B2C):** Thu phí lẻ **1.500 VNĐ / chương**.
      * *Biên lợi nhuận gộp:* \>95% (Chi phí API gốc chỉ \~50 VNĐ/chương).
2.  **Subscription (B2C):** Gói tháng **49.000 VNĐ** (Không giới hạn).
3.  **Partnership (B2B):** Bán gói tài khoản sỉ cho các CLB, Lớp học, Trung tâm luyện thi.
4.  **Affiliate:** Hoa hồng từ việc giới thiệu sách/khóa học liên quan.

### Chỉ số tài chính dự kiến (Tháng thứ 6):

  * **Điểm hòa vốn (Break-even):** Chỉ cần \~10 khách hàng trả phí tháng để nuôi Server.
  * **Rủi ro tài chính:** Thấp. Vốn khởi điểm \~3.000.000 VNĐ.

-----

## 6. Phân chia Nhân sự (Team Roles)

Mô hình làm việc Agile cho team 5 người (Non-tech Founder):

1.  **Product Manager (PM):** Chốt tính năng, quản lý tiến độ, quyết định Roadmap.
2.  **Business Analyst & DB Architect:** Thiết kế luồng đi dữ liệu, quản lý cấu trúc Supabase.
3.  **AI Operator 1 (Backend Logic):** Sử dụng Cursor để viết logic xử lý file và gọi API.
4.  **AI Operator 2 (Frontend UI):** Sử dụng V0.dev/Cursor để dựng giao diện.
5.  **Tester & Prompt Engineer:** Tối ưu câu lệnh cho AI (Prompting), kiểm thử lỗi, và triển khai (Deploy).

-----

## 7. Lộ trình Triển khai (Roadmap)

  * **Tuần 1-2:** Thiết lập Database trên Supabase, Dựng khung Web cơ bản (Upload file).
  * **Tuần 3:** Xây dựng logic tách file (Chunking) và hiển thị mục lục.
  * **Tuần 4:** Tích hợp ví tiền ảo và thanh toán giả lập.
  * **Tuần 5:** Kết nối API OpenAI (Tạo Flashcard/Mindmap).
  * **Tuần 6:** Testing, Fix bug và Deploy bản MVP.

-----

> **Note for Team:** Đây là dự án thiên về **Tư duy quản trị hệ thống và Tối ưu quy trình**. Cần hiểu luồng đi của dữ liệu và dùng AI để thực thi nó.

-----
