# NHẬP MÔN CÔNG NGHỆ PHẦN MỀM  
*(Introduction to Software Engineering – PTIT)*  

## Thông tin sinh viên  
| Họ tên | MSSV | Lớp | Vai trò |
|--------|------|------|----------|
| Trần Duy Vũ Anh | K23DTCN476 | D23TXCN06-K | Fullstack Developer |
| Lê Doãn Minh | K23DTCN475 | D23TXCN06-K | Fullstack Developer |
| Hồ Lâm Sơn | K23DTCN481 | D23TXCN06-K | Tester / QA |
| Nguyễn Xuân Nghĩa | K23DTCN4XX | D23TXCN06-K | UX/UI Design / DevOps |

**Github Repository:** [MiniApp-DatBanNhaHang](https://github.com/hanmn1k99/nmcnpm/)  

---

## Đề tài: MINI APP ĐẶT BÀN NHÀ HÀNG  

### 1. Giới thiệu đề tài  
Mini App Đặt Bàn Nhà Hàng là một ứng dụng web hỗ trợ **quản lý hoạt động đặt bàn** cho các nhà hàng, quán cafe.  
Hệ thống được phát triển theo mô hình **Agile–Scrum**, hướng tới việc số hóa quy trình quản lý bàn ăn, tối ưu trải nghiệm của khách hàng và nhân viên.  

---

### 2. Mục tiêu  
- Xây dựng ứng dụng web với **giao diện trực quan**, giúp nhân viên và quản lý dễ dàng thao tác.  
- Ứng dụng quy trình **phát triển phần mềm hiện đại (Agile-Scrum)**, kết hợp **CI/CD – DevOps** trong triển khai.  
- Thực hành kỹ năng **kiểm thử, đánh giá chất lượng phần mềm**, và **báo cáo phân tích cải tiến**.  

---

## 3. Yêu cầu chính của đề tài  

### a. Chức năng chính của phần mềm  
**Quản lý bàn**  
- Thêm, sửa, xóa, tìm kiếm, hiển thị danh sách bàn.  

**Quản lý đặt bàn**  
- Tạo đặt bàn, cập nhật, hủy đặt bàn, xử lý thanh toán.  

**Giao diện người dùng**  
- Thiết kế thân thiện, trực quan, bao gồm:  
  - Trang chủ  
  - Danh sách bàn  
  - Lịch đặt  
  - Thông báo trạng thái  

---

### b. Chức năng kiểm thử và đánh giá chất lượng  
- **Kiểm thử đơn vị (Unit Test):** bằng JUnit.  
- **Kiểm thử giao diện (UI Test):** bằng Selenium.  
- **Kiểm thử API:** bằng Postman hoặc MockMvc.  
- Báo cáo kết quả test: pass/fail, tỷ lệ bao phủ, lỗi phát hiện.  

---

### c. Báo cáo thống kê và cải tiến  
- Tổng hợp **test case**, **tỷ lệ pass/fail**, **coverage (%)**.  
- Đề xuất **cải tiến hệ thống** dựa trên kết quả test, ví dụ:  
  - Gợi ý bàn trống tự động.  
  - Cảnh báo trùng lịch đặt bàn.  

---

### d. Công cụ phát triển và kiểm thử  
| Hạng mục | Công cụ / Công nghệ |
|-----------|----------------------|
| Backend | Java Spring Boot |
| Cơ sở dữ liệu | H2 / MySQL |
| IDE | Visual Studio Code |
| Kiểm thử | JUnit, Selenium, Postman, Mockito |
| Quản lý mã nguồn | GitHub (Public Repository) |
| Quy trình phát triển | Agile – Scrum |
| CI/CD | Jenkins / GitHub Actions |

---

## 4. Quy trình và Phân công theo Agile – Scrum  

### Sprint Plan  
| Sprint | Nội dung chính | Deliverables |
|--------|----------------|--------------|
| Sprint 0 | Thiết lập môi trường, tạo repo GitHub, định nghĩa backlog | Project Definition + SRS |
| Sprint 1 | Thiết kế UI/UX, tạo model, database schema | Use Case, ERD, UI wireframe |
| Sprint 2 | Cài đặt module Đặt bàn và Quản lý bàn | API Backend + Frontend Form |
| Sprint 3 | Kiểm thử (JUnit, Selenium, Postman), CI/CD pipeline | Test Report + Deployment |

### Daily Scrum  
- Cập nhật tiến độ, blocker, kế hoạch trong nhóm.  

### Sprint Review & Retrospective  
- Đánh giá kết quả, điểm mạnh và cải tiến ở mỗi Sprint.  

---

## 5. Kết quả và Báo cáo  

### a. Báo cáo kỹ thuật  
- Tài liệu thiết kế: `Project_Definition_SRS.docx`  
- UML: Use Case, Activity, Sequence, ERD  
- Code và test scripts: `/src` và `/test`  

### b. Kiểm thử và Đánh giá  
- Unit Test: 20 test case JUnit  
- UI Test: Selenium chạy trên ChromeDriver  
- API Test: Postman collection + MockMvc  
- Báo cáo coverage & lỗi: `Test_Report.xlsx`  

### c. Triển khai  
- CI/CD với GitHub Actions  
- Deploy thử nghiệm trên Railway / Render  
- Hướng dẫn triển khai: `Deployment_Guide.docx`  
