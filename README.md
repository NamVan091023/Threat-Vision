﻿# Threat-Vision
🚀 Network Intrusion Detection System (NIDS) using Machine Learning

📌 Mô tả dự án

Dự án này sử dụng Machine Learning (Random Forest) để phát hiện các cuộc tấn công mạng real-time bằng cách phân tích log từ Zeek (Bro IDS) hoặc các hệ thống giám sát mạng khác.

📊 Dữ liệu đầu vào: Log mạng từ Zeek (conn.log)
🔍 Mô hình sử dụng: Random Forest
🚨 Đầu ra: Cảnh báo tấn công, lưu kết quả dự đoán
🛠 Cài đặt

1️⃣ Yêu cầu hệ thống

Python 3.8+

pip (Python package manager)

Zeek hoặc Suricata để giám sát mạng

Telegram Bot API (nếu muốn nhận cảnh báo)

2️⃣ Cài đặt thư viện

Chạy lệnh sau để cài đặt các thư viện cần thiết:
pip install pandas scikit-learn pickle-mixin requests
