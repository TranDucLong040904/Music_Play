# 🎶 Music Play - Trình Nghe Nhạc Web Đơn Giản

Music Play là một **mini project web** được xây dựng bằng **HTML, CSS và Vanilla JavaScript**, mô phỏng một giao diện nghe nhạc trực tuyến với thiết kế trực quan và các tính năng cơ bản. Điểm nhấn là hiệu ứng **đĩa nhạc xoay** độc đáo khi bài hát đang phát.



---

## ✨ Tính năng nổi bật

* **🎧 Điều khiển nhạc:** Phát (Play), Tạm dừng (Pause), Tua (Seek).
* **⏭️ Chuyển bài:** Bài hát tiếp theo và bài hát trước đó.
* **⏳ Hiển thị thời gian:** Cập nhật thời gian bài hát hiện tại và tổng thời lượng.
* **🖼️ Hiệu ứng trực quan:** **Đĩa nhạc xoay** khi nhạc đang phát.
* **📝 Thông tin:** Hiển thị tên bài hát và nghệ sĩ.
* **📱 Thiết kế Responsive:** Giao diện tối ưu cơ bản trên các kích thước màn hình.

---

## 🛠️ Công nghệ sử dụng

| Công nghệ | Mô tả |
| :--- | :--- |
| **HTML5** | Cấu trúc trang web. |
| **CSS3** | Thiết kế giao diện và hiệu ứng đĩa quay. |
| **JavaScript (Vanilla JS)** | Xử lý logic phát nhạc và tương tác người dùng. |
| **Font Awesome** | Cung cấp các biểu tượng điều khiển nhạc (icons). |

---

## 🚀 Hướng dẫn cài đặt & Chạy project

Thực hiện các bước sau để chạy project trên máy tính của bạn:

1.  **Clone** repository về máy:

    ```bash
    git clone https://github.com/TranDucLong040904/Music_Play.git
    ```

2.  Mở thư mục project vừa clone.

3.  Mở file **`index.html`** bằng bất kỳ trình duyệt hiện đại nào (Chrome, Edge, Firefox, v.v...).

**🎉 Enjoy!**

---

## 📂 Cấu trúc thư mục

Cấu trúc file được tổ chức rõ ràng như sau. Để trình bày đẹp hơn trên GitHub, tôi đã sử dụng khối code block cho cấu trúc cây thư mục.

```text
Music_Play/
├── index.html          # Cấu trúc trang web chính
├── Jscript.js          # Logic điều khiển trình phát nhạc
├── README.md           # File này
├── song.js             # Dữ liệu danh sách bài hát (array of objects)
├── style.css           # Định dạng và kiểu dáng (CSS)
|
├── images/             # Nơi lưu ảnh bìa bài hát và ảnh minh họa
│   ├── ... .png        # Ảnh bìa bài hát
│   └── demo.gif        # GIF minh họa hoạt động của trình phát
|
└── music/              # Nơi lưu trữ các file nhạc (.mp3)
    └── ... .mp3        # Các file nhạc
```
---

## 📝 Hướng dẫn thêm bài hát mới
Để thêm một bài hát mới vào danh sách phát, bạn cần chỉnh sửa file song.js theo các bước sau:

+ Thêm file nhạc .mp3 vào thư mục music/.

+ Thêm file ảnh bìa .png hoặc .jpg vào thư mục images/.

+ Mở file song.js và thêm một Object mới vào mảng songs (sử dụng cú pháp JSON/JavaScript):

```text
JavaScript

// File: song.js

// Thêm object mới vào mảng songs ở đây:
{
    name: "Tên bài hát",
    path: "music/tên_file_nhạc.mp3", 
    artist: "Tên nghệ sĩ",
    image: "images/tên_file_ảnh.png" 
},
```
Ví dụ thực tế:
```text
{
    name: "Blinding Lights",
    path: "music/Blinding Lights.mp3",
    artist: "The Weeknd",
    image: "images/blinding_lights.png"
}
```
+ Lưu file song.js và Refresh trình duyệt để thấy bài hát mới.

---
## ⚡ Demo giao diện
- We don't talk anymore (Charlie Puth)
<img width="587" height="836" alt="image" src="https://github.com/user-attachments/assets/b37edd7f-782c-4f13-a442-a7fa88715556" />  

- Fire (Alan Walker)
<img width="573" height="835" alt="image" src="https://github.com/user-attachments/assets/00d04dad-d329-4496-ac9c-ff14654c558d" />  

- Đừng làm trái tim anh đau (Sơn Tùng MTP)
<img width="573" height="839" alt="image" src="https://github.com/user-attachments/assets/2eb59b86-af5b-4356-87f4-0f2ef2b10ca1" />  

---
## 📜 Giấy phép (License)
Project này được cấp phép miễn phí sử dụng cho mục đích học tập và demo cá nhân. Vui lòng không sử dụng cho mục đích thương mại.
