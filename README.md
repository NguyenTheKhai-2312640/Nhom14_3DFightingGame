# Nhom14_3DFightingGame
# 🥊 3D Fighting Game (Game đấu kháng 3D)

> Một tựa game đối kháng 3D đơn giản.

---

## 📌 Giới thiệu dự án

Dự án **3D Fighting Game** là một game đối kháng góc nhìn ngang/3D cơ bản. Đề tài tập trung vào việc hiện thực hóa các cơ chế cốt lõi của dòng game đối kháng (di chuyển, tấn công, phòng thủ, va chạm và tính điểm).

### 🎯 Mục tiêu đề tài
- Xây dựng thành công vòng lặp chơi (Gameplay Loop) cơ bản cho game đối kháng.
- Áp dụng hiệu quả **Unity 6** và workflow lập trình C# trên **VS Code**.
- Quản lý phiên bản mã nguồn chuyên nghiệp bằng **Git/GitHub**.

---

## 👥 Thành viên thực hiện

| **STT** | **Mã số** | **Họ và tên** | **Vai trò chính** | **Lớp** | **Email** |
| :---: | :--- | :--- | :--- | :--- | :--- |
| **1** | 2312677 | Ngô Văn Trường Long | Nhóm trưởng | CTK47B | 2312677@dlu.edu.vn |
| **2** | 2312640 | Nguyễn Thế Khải | Thành viên | CTK47B | 2312640@dlu.edu.vn |

---

## 🛠 Công nghệ & Công cụ sử dụng

* **Game Engine:** Unity 6 (`6000.0.72f1`)
* **Ngôn ngữ lập trình:** C#
* **Trình soạn thảo code:** Visual Studio Code (VS Code)
* **Quản lý mã nguồn:** Git & GitHub

---

## ⚡ Tính năng cốt lõi (Scope tinh gọn)

Để đảm bảo tiến độ nhanh chóng, dự án tập trung vào các tính năng tối thiểu nhưng đủ tiêu chuẩn:

1. **Chế độ chơi (Game Mode):**
   * **2-Player (PVP):** 2 người chơi online (nếu có).
   * **Bot enemy (Offline):** Người chơi vs máy.
2. **Cơ chế chiến đấu (Combat Mechanics):**
   * Di chuyển: Tiến, lùi, nhảy, cúi.
   * Hành động: Tấn công nhẹ (Light Attack), Tấn công mạnh (Heavy Attack), Tự vệ (Block).
   * Hệ thống va chạm Hitbox đơn giản.
3. **Giao diện & Âm thanh (UI/UX):**
   * Màn hình Start / Menu cơ bản.
   * Thanh máu (HP Bar), đồng hồ đếm ngược (Round Timer).
   * Màn hình kết quả (Win/Lose).
   * Âm thanh đòn đánh và nhạc nền cơ bản.
4. **Tài nguyên (Assets):**
   * Sử dụng 2 nhân vật 3D sẵn có (kèm animation có sẵn).
   * 01 màn chơi đơn giản (sử dụng Primitives hoặc Asset Store miễn phí).

---

## 🚀 Hướng dẫn sử dụng Source Code
### Yêu cầu:
- Đã cài đặt **Unity Hub** và **Unity 6 (6000.0.72f1)**.
- Đã cài đặt **VS Code** kèm extension *C# Dev Kit* hoặc *OmniSharp*.
- Đã cài đặt **Git**.

### Các bước thực hiện

1. **Clone Repository:**
   ```bash
   git clone https://github.com/NguyenTheKhai-2312640/Nhom14_3DFightingGame.git
   ```

2. **Mở dự án trong Unity:**
   - Khởi động **Unity Hub**.
   - Chọn **Add** > **Add project from disk** và chọn thư mục vừa clone.
   - Mở dự án bằng phiên bản Unity `6000.0.72f1`.

---

## 🕹 Phím điều khiển mặc định (Local 2P)

| Hành động | Player 1 | Player 2 |
| :--- | :---: | :---: |
| **Di chuyển (Trái / Phải)** | `A` / `D` | `Left` / `Right` Arrow |
| **Nhảy / Cúi** | `W` / `S` | `Up` / `Down` Arrow |
| **Đánh nhẹ (Light Attack)** | `J` | `Numpad 1` |
| **Đánh mạnh (Heavy Attack)** | `K` | `Numpad 2` |
| **Đỡ (Block)** | `L` | `Numpad 3` |

---
