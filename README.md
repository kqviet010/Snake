# 🐍 Snake Game (C++)

Chào mừng đến với dự án **Snake Game**. Đây là một phiên bản tái hiện trò chơi "Rắn Săn Mồi" cổ điển, được viết hoàn toàn bằng ngôn ngữ lập trình C++. Dự án này được thực hiện nhằm mục đích học tập và rèn luyện tư duy thuật toán cũng như kỹ năng lập trình hướng đối tượng.

## 📖 Mô tả dự án (Description)

Trò chơi Rắn Săn Mồi là một video game kinh điển ra đời từ những năm 1970. Trong phiên bản này, người chơi sẽ điều khiển một con rắn di chuyển trên bản đồ giới hạn.

**Mục tiêu của trò chơi:**
* Điều khiển rắn ăn các vật phẩm (mồi) xuất hiện ngẫu nhiên trên màn hình.
* Mỗi lần ăn, rắn sẽ dài ra và điểm số sẽ tăng lên.
* Trò chơi kết thúc nếu rắn đâm vào tường hoặc tự cắn vào thân mình.

Dự án tập trung vào việc tối ưu hóa mã nguồn, xử lý input từ bàn phím mượt mà và hiển thị đồ họa đơn giản trên giao diện Console.

## ✨ Tính năng chính
* [x] Giao diện Console cổ điển, nhẹ nhàng.
* [x] Cơ chế di chuyển mượt mà, không bị giật (lag).
* [x] Hệ thống tính điểm thời gian thực.
* [x] Tự động tăng độ khó (tốc độ) khi đạt điểm cao.

## 🎮 Hướng dẫn điều khiển
Sử dụng các phím sau để điều khiển rắn:

* **W** hoặc **Mũi tên lên**: Di chuyển lên trên.
* **S** hoặc **Mũi tên xuống**: Di chuyển xuống dưới.
* **A** hoặc **Mũi tên trái**: Di chuyển sang trái.
* **D** hoặc **Mũi tên phải**: Di chuyển sang phải.
* **X**: Thoát game.

## 👥 Thành viên nhóm thực hiện

Dưới đây là danh sách các thành viên đã đóng góp vào dự án này:

| STT | Họ và Tên | Mã Sinh Viên | Vai trò (Role) |
|:---:|:---|:---:|:---|
| 1 | **Kiều Quang Việt** (Nhóm trưởng) | 25730093 | Lập trình chính (Core Logic) |
| 2 | **Phạm Thị Thanh Tuyền** | 25730091 | Thiết kế giao diện & Xử lý input |
| 3 | **Nguyễn Thị Thu Uyên** | 25730092 | Kiểm thử (Tester) & Viết tài liệu |

## 🛠️ Cách cài đặt và chạy
1. Clone repository này về máy:
   ```bash
   git clone https://github.com/kqviet010/Snake.git
   ```
2. Build và chạy game (Linux)
   ```bash
   g++ snake.cpp -o snake
   ./snake
   ```
