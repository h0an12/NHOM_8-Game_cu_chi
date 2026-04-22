<h2 align="center">
    <a href="https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin">
    🎓 Faculty of Information Technology (DaiNam University)
    </a>
</h2>
<h1 align="center">
    🌌 SPACE MONSTER - QUÁI VẬT KHÔNG GIAN 🌌
</h1>
<div align="center">
    <p align="center">
        <img src="docs/logo/aiotlab_logo.png" alt="AIoTLab Logo" width="170"/>
        <img src="docs/logo/fitdnu_logo.png" alt="FIT DNU Logo" width="180"/>
        <img src="docs/logo/dnu_logo.png" alt="DaiNam University Logo" width="200"/>
    </p>

[![AIoTLab](https://img.shields.io/badge/AIoTLab-green?style=for-the-badge)](https://www.facebook.com/DNUAIoTLab)
[![Faculty of Information Technology](https://img.shields.io/badge/Faculty%20of%20Information%20Technology-blue?style=for-the-badge)](https://dainam.edu.vn/vi/khoa-cong-nghe-thong-tin)
[![DaiNam University](https://img.shields.io/badge/DaiNam%20University-orange?style=for-the-badge)](https://dainam.edu.vn)

<hr>
<!-- Badges Công Nghệ -->
<img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Pygame-2.5.2-green?logo=pygame&logoColor=white" alt="Pygame">
<img src="https://img.shields.io/badge/MediaPipe-0.10.9-orange?logo=google&logoColor=white" alt="MediaPipe">
<img src="https://img.shields.io/badge/OpenCV-4.9.0-red?logo=opencv&logoColor=white" alt="OpenCV">
<img src="https://img.shields.io/badge/License-MIT-yellow" alt="License">
<hr>
</div>

## 📖 Giới Thiệu Dự Án

**Space Monster** là một dự án game hành động platformer được phát triển bởi sinh viên **Khoa Công Nghệ Thông Tin - Đại Học Đại Nam**, dưới sự hướng dẫn của Thầy **ThS. Lê Trung Hiếu**.

Trò chơi kết hợp giữa đồ họa 2D cổ điển và công nghệ **Trí Tuệ Nhân Tạo (AI)** hiện đại, cho phép người chơi điều khiển nhân vật hoàn toàn bằng **cử chỉ bàn tay** qua Webcam. Bạn sẽ vào vai **Galactic Guardian**, chiến đấu vượt qua 5 hành tinh đầy rẫy quái vật không gian và những tên Boss hùng mạnh để giải cứu vũ trụ.

## 📜 Cốt Truyện

> Năm 2157, Trái Đất nhận được tín hiệu cầu cứu yếu ớt từ rìa Ngân Hà. Một thế lực bóng tối cổ đại, **Void Emperor**, đã thức tỉnh và đang thôn tính các hành tinh. Những **Quái Vật Không Gian** tràn lan khắp nơi. Bạn là **Galactic Guardian** - chiến binh ánh sáng cuối cùng. Hãy du hành qua 5 kỳ quan vũ trụ, sử dụng sức mạnh công nghệ và ý chí để đánh bại cái ác!

## ✨ Các Tính Năng Chính

| Tính Năng | Mô Tả |
|-----------|-------|
| **🖐️ Điều Khiển Bằng Cử Chỉ AI** | Sử dụng camera và MediaPipe. *Đấm, Bắn, Nhảy* không cần chạm bàn phím. |
| **📷 Chế Độ Theo Dõi Thông Minh** | Nhân vật di chuyển mượt mà theo vị trí tay bạn trước camera (Follow Mode). |
| **👑 Hệ Thống 5 Boss Đa Dạng** | Mỗi boss có cốt truyện, hội thoại riêng và 3 cấp độ tiến hóa (Phase). |
| **⚔️ Cơ Chế Chiến Đấu Phong Phú** | Combo cận chiến (kiếm năng lượng), súng laser tầm xa, kỹ năng Né Tránh và Chiêu Cuối (Ultimate). |
| **💬 Đối Thoại Tương Tác** | Trước trận đánh Boss, người chơi có thể lựa chọn đầu hàng hoặc chiến đấu bằng cử chỉ tay. |
| **🎁 Vật Phẩm Hỗ Trợ** | Kẻ địch rớt Máu (HP), Khiên (Shield) và đặc biệt là **Đạn Vĩnh Viễn** (Infinite Ammo). |

## 🗺️ Hành Trình Qua Các Màn Chơi

| Màn | Tên Vùng Đất | Boss (Quái Vật Không Gian) | Màu Đại Diện |
|-----|--------------|------------------------------|--------------|
| **1** | Vành Đai Sao Chổi | **Comet Warden** - Người Gác Sao Chổi | `CYAN` |
| **2** | Hành Tinh Lửa Ignis | **Inferno Dragon** - Rồng Lửa | `ORANGE` |
| **3** | Tinh Vân Băng Giá Glacia | **Frost Queen** - Nữ Hoàng Băng Giá | `BLUE` |
| **4** | Lõi Thiên Hà Điện Từ | **Nebula Specter** - Bóng Ma Tinh Vân | `PURPLE` |
| **5** | Kỳ Quan Bóng Tối | **Void Emperor** - Hoàng Đế Hư Không | `RED` |

## 🕹️ Hướng Dẫn Điều Khiển (Gesture Guide)

### 🖐️ Chế Độ Camera AI (Mặc định)
*Lưu ý: Giơ tay trước camera để hệ thống nhận diện.*

| Hành Động | Cử Chỉ Tay | Mô Tả Chi Tiết |
|-----------|------------|----------------|
| **Di Chuyển** | ✊ Nắm đấm + Vuốt ngang | Giữ nắm đấm và di chuyển tay sang trái/phải. |
| **Nhảy** | ☝️ 1 ngón + Kéo lên | Giơ 1 ngón trỏ và kéo nhanh lên trên. |
| **Đấm Cận Chiến** | ✊ Nắm đấm | Nắm chặt tay lại. |
| **Bắn Súng** | ✌️ 2 ngón (Hình chữ V) | Giơ ngón trỏ và ngón giữa. |
| **Hồi Máu** | 🤟 3 ngón (ILoveYou) | Giơ ngón cái, trỏ và út. |
| **Chiêu Cuối** | 👍 Ngón cái (Like) | Giơ ngón cái lên. |
| **Quay Lại Menu** | 🤟 3 ngón (Trong menu) | Dùng để thoát khỏi menu phụ. |

> **Follow Mode (Phím `H`):** Thay vì vuốt tay, bạn chỉ cần đưa tay di chuyển tự do trong khung hình, nhân vật sẽ tự động chạy theo tay bạn.

### ⌨️ Chế Độ Bàn Phím (Dự Phòng)
| Phím | Chức Năng | Phím | Chức Năng |
|------|-----------|------|-----------|
| `←` `→` | Di chuyển trái/phải | `J` | Nhảy |
| `SPACE` | Đánh cận chiến | `F` | Bắn súng |
| `B` | Bật/Tắt **God Mode** | `N` | Hồi máu (Thoát God) |
| `C` | Bật/Tắt Camera Preview | `H` | Bật/Tắt Follow Mode |
| `P` | Tạm dừng trò chơi | `M` | Về Menu chính |

## 📦 Hướng Dẫn Cài Đặt & Chạy Dự Án

### 1. Yêu cầu hệ thống
- Python 3.8 trở lên.
- Webcam (bắt buộc nếu muốn trải nghiệm điều khiển bằng tay).
- Hệ điều hành: Windows 10/11, macOS, Linux.

### 2. Cài đặt Thư viện
Mở Terminal tại thư mục dự án và chạy lệnh:
```bash
pip install -r requirements.txt