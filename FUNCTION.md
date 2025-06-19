
> Tài liệu đặc tả chức năng tổng quan cho backend/frontend/product.  
> Mục tiêu: ưu tiên triển khai theo hành vi người dùng, module chức năng rõ ràng, dễ mở rộng.

---

## 🔰 1. Phân tầng người dùng & quyền hạn (User Tier & Access Control)

| Cấp người dùng      | Mô tả                           | Quyền hạn chính                                                |
|---------------------|----------------------------------|----------------------------------------------------------------|
| Guest               | Người mới, chưa đăng nhập        | Dùng thử scan & tìm kiếm, không xem chi tiết công thức         |
| Free Member         | Đã đăng ký tài khoản             | Xem công thức đầy đủ, đăng bài, lưu món, tích điểm             |
| Premium Plus        | Trả phí gói cá nhân              | Bộ lọc nâng cao, không quảng cáo, cảnh báo dị ứng              |
| Premium Pro         | Trả phí gói chuyên gia           | Thực đơn AI, danh sách đi chợ, nội dung độc quyền              |
| Admin / Editor      | Kiểm duyệt & quản lý nội dung    | Duyệt công thức, viết blog, quản lý user                       |

---

## 📲 2. Module tính năng theo mức độ ưu tiên

### 2.1. Tài khoản & Phân quyền
- Đăng ký / đăng nhập (email, Google, Facebook)
- Cập nhật hồ sơ
- Phân quyền theo RBAC

### 2.2. Công thức & Tìm kiếm
- CRUD công thức
- Tìm kiếm theo tên món / nguyên liệu
- Bộ lọc cơ bản (Free), nâng cao (Premium)
- Giao diện kết quả dạng card

### 2.3. Quét nguyên liệu (Scan AI)
- Mở camera → nhận diện AI
- Trả danh sách nguyên liệu
- Gợi ý món phù hợp

### 2.4. Hệ thống Điểm thưởng (💎 Rewards)
- Cộng/trừ điểm theo hành vi
- Lịch sử giao dịch
- Đổi điểm lấy tính năng / quà

### 2.5. Cộng đồng
- Feed bài đăng (ảnh + caption)
- Like / Comment / Lưu
- Đăng công thức chi tiết (duyệt)

### 2.6. Trang cá nhân
- Thông tin cơ bản, ảnh đại diện
- Công thức đã lưu, bài viết, thực đơn
- Điểm thưởng & hoạt động

### 2.7. Kế hoạch ăn uống AI (Pro)
- Khai báo mục tiêu cá nhân
- AI tạo thực đơn tuần/tháng
- Tự động tạo danh sách đi chợ

---

## 🌐 3. Website (SEO + Cộng đồng)

### 3.1. SEO Recipe Page
- Index công thức, tối ưu đọc
- CTA tải app hoặc đăng ký

### 3.2. Feed cộng đồng
- Đăng nhập để tương tác
- Giao diện bài viết giống social

### 3.3. Admin Panel
- Duyệt công thức
- Viết blog chuyên sâu

---

## 🛠️ 4. Gợi ý kỹ thuật Backend

| Module         | Gợi ý công nghệ               | Ghi chú                                 |
|----------------|-------------------------------|------------------------------------------|
| Auth           | JWT / OAuth2                  | Middleware phân quyền                    |
| Recipe Search  | PostgreSQL + fulltext / Typesense | Ưu tiên Typesense cho UX tốt          |
| Rewards        | rewards + reward_logs         | Cộng/trừ điểm theo hành vi              |
| Scan           | AI backend riêng (Flask/FastAPI) | Dùng REST API hoặc WebSocket           |
| Community      | posts, comments, likes        | Cần kiểm duyệt nội dung                 |
| Premium        | subscriptions + webhook       | Tích hợp Stripe / App Store / GPlay     |

---

## 🚦 5. Lộ trình MVP

| Giai đoạn     | Mục tiêu                       | Thành phần chính                       |
|---------------|-------------------------------|----------------------------------------|
| Giai đoạn 1   | MVP core                      | Auth, Công thức, Tìm kiếm, Trang chủ   |
| Giai đoạn 2   | Tăng tương tác                | Scan, Rewards, Cộng đồng               |
| Giai đoạn 3   | Monetize                      | Premium, AI plan, thanh toán           |
| Giai đoạn 4   | SEO & Web cộng đồng           | Website recipe, blog, admin panel      |

---

## 📌 Kết luận

- Nên tổ chức code backend theo module: `recipes`, `users`, `rewards`, `posts`, `premium`, `ai_scan`
- Ưu tiên bảo trì dễ dàng, API rõ ràng, hỗ trợ tăng trưởng và phân quyền theo vai trò người dùng.

