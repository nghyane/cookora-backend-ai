# Cookora App – Product Specification (v1)

**Mục tiêu:**  
Ứng dụng giúp người dùng nấu ăn thông minh hơn thông qua việc gợi ý món ăn từ nguyên liệu sẵn có, tích hợp cộng đồng yêu bếp, cá nhân hóa dinh dưỡng và hệ thống phần thưởng.

**Ngày cập nhật:** 2025-06-19  
**Tác giả:** Nghia Hoang

---

## 📚 Mục lục

1. [Giới thiệu & Tầm nhìn](#1-giới-thiệu--tầm-nhìn)
2. [Tính năng chính của App](#2-tính-năng-chính-của-app)
3. [Hành trình người dùng (User Flows)](#3-hành-trình-người-dùng-user-flows)
4. [Tính năng Website](#4-tính-năng-website)
5. [Quản trị & Nội dung](#5-quản-trị--nội-dung)
6. [Lộ trình phát triển (Roadmap)](#6-lộ-trình-phát-triển-roadmap)
7. [Phân loại tính năng theo giai đoạn](#7-phân-loại-tính-năng-theo-giai-đoạn)
8. [Thuật ngữ (Glossary)](#8-thuật-ngữ-glossary)
9. [Phụ lục](#9-phụ-lục)

---

## 1. Giới thiệu & Tầm nhìn

Cookora là nền tảng nấu ăn giúp người dùng dễ dàng sử dụng các nguyên liệu sẵn có để tạo nên những bữa ăn ngon, khoa học và cá nhân hoá.

### USP (Unique Selling Point):

- Scan ảnh nguyên liệu → gợi ý món ăn tức thì
- Công thức được kiểm chứng, chuyên sâu
- Hệ thống cộng đồng + gamification tích điểm 💎

### Persona:

- Sinh viên / người đi làm bận rộn
- Người theo chế độ Eat Clean, dị ứng
- Mẹ bỉm sữa hoặc người nội trợ sáng tạo

---

## 2. Tính năng chính của App

Ứng dụng được chia thành 5 tab chức năng chính:

### 2.1 Trang chủ (Home)
- Gợi ý món ăn hôm nay
- Banner sự kiện, công thức trending
- Bộ sưu tập theo mùa/lễ

### 2.2 Tìm kiếm (Search)
- Tìm món ăn theo từ khóa, nguyên liệu
- Bộ lọc cơ bản (mặn/ngọt, thời gian nấu)
- Bộ lọc nâng cao (Pro): calories, chế độ ăn

### 2.3 Scan nguyên liệu
- Mở camera → chụp ảnh
- GPT-4o nhận diện nguyên liệu chính (trứng, thịt, rau…)
- Trả về danh sách món có thể nấu

### 2.4 Cộng đồng (Community)
- Đăng bài, hình ảnh, caption
- Tương tác: like, bình luận
- Gamification: tích điểm 💎

### 2.5 Cá nhân (Profile)
- Quản lý công thức yêu thích
- Thực đơn cá nhân (Pro)
- Quản lý điểm 💎, nâng cấp gói

---

## 3. Hành trình người dùng (User Flows)

Chi tiết các hành vi chính từ lúc người dùng mở app đến lúc tương tác nâng cao.

### 3.1 Guest Mode
- Trải nghiệm thử Scan và Tìm kiếm
- Xem công thức bị làm mờ phần nguyên liệu / cách nấu
- CTA mời đăng ký để mở khoá

### 3.2 Member Free
- Truy cập toàn bộ công thức cơ bản
- Lưu công thức, tạo bài viết, tích điểm
- Gặp tường phí khi lọc nâng cao → CTA nâng cấp

### 3.3 Member Premium (Plus / Pro)
- Plus: mở tất cả bộ lọc, không quảng cáo, cảnh báo dị ứng
- Pro: tạo thực đơn AI + danh sách đi chợ + nội dung độc quyền

---

## 4. Tính năng Website

Website đóng vai trò SEO, giới thiệu App, cộng đồng mở rộng.

- Người dùng Google search → vào bài công thức
- CTA Tải App nằm xen kẽ nội dung
- Người dùng có thể đăng ký, lưu món, tham gia cộng đồng

---

## 5. Quản trị & Nội dung

### 5.1 Admin
- Duyệt công thức người dùng gửi lên
- Từ chối có lý do rõ ràng
- Theo dõi chỉ số hệ thống

### 5.2 Chuyên gia (Content Editor)
- Viết bài Blog, mẹo nấu ăn
- Đăng bài xu hướng: “Eat Clean mùa hè”, “Low Carb tối giản”

---

## 6. Lộ trình phát triển (Roadmap)

| Giai đoạn | Mục tiêu                    | Tính năng tiêu biểu                       |
|-----------|-----------------------------|-------------------------------------------|
| MVP       | Scan → Gợi ý món → Xem món | Đăng nhập, Scan, xem chi tiết, lưu món    |
| Giai đoạn 2 | Tăng tương tác             | Cộng đồng, điểm thưởng, bình luận         |
| Giai đoạn 3 | Cá nhân hóa dinh dưỡng     | Kế hoạch ăn uống AI, cảnh báo dị ứng      |

---

## 7. Phân loại tính năng theo giai đoạn

| Tính năng                        | Ưu tiên | Nền tảng | Giai đoạn     |
|----------------------------------|---------|----------|----------------|
| Scan ảnh                        | 🔥      | App      | MVP            |
| Gợi ý món ăn từ nguyên liệu     | 🔥      | App      | MVP            |
| Lưu công thức yêu thích         | ✅      | App      | MVP            |
| Cộng đồng (post, comment)       | ⚠       | App/Web  | Giai đoạn 2    |
| Điểm thưởng 💎                  | ⚠       | App/Web  | Giai đoạn 2    |
| Gợi ý AI theo thể trạng         | ❌      | App      | Giai đoạn 3    |

---

## 8. Thuật ngữ (Glossary)

| Thuật ngữ      | Giải thích |
|----------------|------------|
| USP            | Unique Selling Point – Điểm độc đáo cạnh tranh |
| Guest Mode     | Người dùng chưa đăng nhập |
| CTA            | Call to Action – Nút kêu gọi hành động |
| 💎 Point       | Hệ thống điểm thưởng trong ứng dụng |

---

## 9. Phụ lục

- Sitemap App: Home → Search → Scan → Community → Profile
- Prompt GPT-4o cho tính năng Scan ảnh nguyên liệu
- Mẫu UI/UX gợi ý nếu có
