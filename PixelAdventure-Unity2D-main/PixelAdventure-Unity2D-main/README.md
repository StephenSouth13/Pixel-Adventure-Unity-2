# 🎮 Pixel Adventure - Unity 2D Platformer

![Unity](https://img.shields.io/badge/Engine-Unity-blue?logo=unity)
![C#](https://img.shields.io/badge/Language-C%23-green?logo=csharp)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 🌌 Giới thiệu
**Mario Mini** là một game **Platformer 2D** được xây dựng bằng Unity.  
Người chơi sẽ điều khiển nhân vật chính vượt qua những thử thách, nhảy qua các platform, thu thập coin và tránh kẻ thù.  
Dự án mang phong cách **pixel art** cổ điển, đem lại trải nghiệm hoài niệm như các tựa game Mario, Celeste hay Hollow Knight.  

---

## ✨ Tính năng nổi bật
- 🕹️ **Gameplay platformer cổ điển**: di chuyển, nhảy, thu thập coin, tiêu diệt enemy.
- 🎨 **Đồ họa Pixel Art**: gọn nhẹ, đẹp mắt, dễ mở rộng.
- 🔊 **Âm thanh & hiệu ứng** sống động.
- 🧩 **Prefab & Scene tổ chức rõ ràng**, thuận tiện cho việc phát triển.
- ⚡ **Tối ưu hiệu suất** để chạy mượt mà trên Unity.

---

## 🛠️ Công nghệ sử dụng
- **Game Engine**: Unity 6000.0.55f1 hoặc mới hơn
- **Ngôn ngữ lập trình**: C#
- **IDE**: Visual Studio / Rider
- **Hệ điều hành hỗ trợ**: Windows, macOS

---

## 🚀 Cách cài đặt & chạy game
1. Clone repository:
   ```bash
   git clone https://github.com/StephenSouth13/MarioMiniLab

## 📚 Thông tin Bài Lab 14

### 🎯 Mục tiêu
Học viên hoàn thành được **prototype game platformer cơ bản** với gameplay giống Mario mini:
- Sử dụng **Tilemap** để tạo map  
- Điều khiển nhân vật **di chuyển & nhảy**  
- Thu thập **coin**  
- Di chuyển qua **platform bay**  
- Tiêu diệt **enemy**  
- Có hệ thống **tính điểm**  

### 📝 1.Thông tin
- **Tên**: Bài Lab 14 – Game 2D Platformer Mario Mini  
- **Thời lượng**: 6 giờ  
- **Mức độ**: Cơ bản – dành cho học viên đã biết Scene, Sprite, Rigidbody2D, Collider  
- **Phần mềm**: Unity 6.1.1f1 hoặc mới hơn  
- **Output mong muốn**: Game platformer có đầy đủ gameplay: di chuyển, nhảy, coin, platform bay, enemy, camera follow, tính điểm.  
- Tạo scene mới: **Level1**  

### 2. Thiết lập GameObject (45’)
- **Map**: sử dụng Tilemap, vẽ bản đồ dài 5 màn hình, có vực sâu + khu vực cao.  
- **Player**: thêm `Rigidbody2D`, `BoxCollider2D`, script `PlayerMovement.cs`.  
- **Coin**: trigger collider, script `Coin.cs` (+10 điểm khi ăn).  
- **Platform bay**: script `MovingPlatform.cs` di chuyển qua lại.  
- **Enemy**: di chuyển qua lại, bị tiêu diệt khi player nhảy lên đầu.  
- **Camera**: Cinemachine Virtual Camera follow player.  

### 3. Gameplay & Score (45’)
- Enemy va chạm → mất mạng hoặc tiêu diệt.  
- Thu thập coin → cập nhật `ScoreManager.cs`.  
- Platform bay → giúp player vượt vực sâu.  

### 4. UI hiển thị điểm (15’)
- Canvas với **TextMeshPro**: `"Score: X"`.  

### 5. Quy tắc Gameplay
- Player di chuyển, nhảy qua vực sâu, đứng trên platform bay.  
- Nhảy lên đầu enemy để tiêu diệt.  
- Ăn coin: **+10 điểm**.  
- Camera luôn follow theo trục X.  

### 6. Yêu cầu Animation
- **Player**: idle, run.  
- **Coin**: animation quay vòng.  
- **Enemy**: animation di chuyển.  
- **Platform**: di chuyển mượt.  

### 7. Nộp bài & Đánh giá
- Nộp qua Google Drive hoặc push lên GitHub/GitLab.  
- Asset tham khảo: [Pixel Frog - Pixel Adventure](https://pixelfrog-assets.itch.io/pixel-adventure-1).  

---

## 🧑‍💻 Thông tin sinh viên thực hiện
- **Họ tên**: Quách Thành Long  
- **Email**: longqt.124010124034@vtc.edu.vn  
- **Lớp học phần**: K24GD-03-2D Game Engine  
- **Giờ học**: 8h30 – 11h30  
- **Giảng viên hướng dẫn**: Thầy Nguyễn Trung Hiếu  

---

## 📸 Hình ảnh minh họa
![alt text](image.png)
