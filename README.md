# Bypass_WindowsDefender
Một bản thử nghiệm nghiên cứu kỹ thuật vượt qua Windows Defender AMSI bằng cách vá bộ nhớ và trích xuất dữ liệu qua API Telegram

                                         BẢN THÂN NHIỆM VỤ CHÍNH PHÁT TRIỂN MÔ HÌNH 
                                         
Một bản thử nghiệm nghiên cứu (Proof of Concept) về kỹ thuật vượt qua Windows Defender AMSI bằng cách vá bộ nhớ (Memory Patching) và trích xuất dữ liệu qua API Telegram.

## 🚀 Tính năng chính
- **AMSI Patching:** Vô hiệu hóa Windows Antimalware Scan Interface thông qua .NET Reflection.
- **Obfuscation:** Kỹ thuật làm mờ mã nguồn bằng cách cộng chuỗi để vượt qua bộ quét tĩnh.
- **Fileless Exfiltration:** Tự động thu thập tệp `.txt` và gửi về Telegram Bot qua HTTPS (Port 443).

## 🛠️ Kỹ thuật sử dụng
- **Ngôn ngữ:** PowerShell, Batch Script.
- **Cơ chế:** Memory Patching (`amsiInitFailed` bypass).
- **C2 Communication:** Telegram Bot API.

## 📸 Demo thực tế
https://www.youtube.com/watch?v=ZfakxBd45D8

## ⚠️ Disclaimer
Dự án này chỉ phục vụ mục đích học tập và nghiên cứu an toàn thông tin tại HUIT. Tác giả không chịu trách nhiệm cho bất kỳ hành vi sử dụng trái phép nào.
