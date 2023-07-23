FBChat-Remake: Open Source
=======================================

Xin chào, tôi là **MinhHuyDev**. Lời nói đầu, đây là lần đầu tiên mà mình làm lại một source lớn như vậy nên sẽ không tránh được những *sai sót* trong quá trình code, rất mong sẽ được người dùng báo cáo lại **Lỗi** tại issues của GitHub này nhé:3

.. image:: https://i.ibb.co/tbDvDvR/Picsart-23-07-20-08-26-28-991.jpg

**📢Dành cho người mới**: *Lướt xuống cuối trang bạn sẽ thấy* **TUTORIAL (Hướng dẫn)** *nhận tin nhắn và gửi tin nhắn nhé!*

=======================================
Thông tin cơ bản về FBChat Remake
=======================================

- **Được làm lại từ:** *fbchat (Python)* 
- **Người đóng góp**: *hakuOwO*
- **Ngôn ngữ lập trình:** *Python*
- **Phát triển bởi:** *Nguyễn Minh Huy*
- **Phiên bản hiện tại:** *1.0.2*
- **Cập nhật lần cuối:** *08:30 20/07/2023*

=======================================
Tutorial (Hướng dẫn)
=======================================

**Đầu tiên**: Người dùng cần phải cài đặt *tất cả* các gói tài nguyên cần thiết để có thể sử dụng. Nếu bạn chưa cài đặt, hãy dùng lệnh sau:

.. code-block:: bash

  git clone https://github.com/MinhHuyDev/fbchat-v2

**Tiếp theo**: Hãy tạo thư mục trong chính folder mà mình vừa tải về từ *GitHub* về bằng cách sau:

*Đối với* **Windows (Command Prompt/PowerShell):**

.. code-block:: bash
  
  cd fbchat-v2/src && type nul > mainBot.py

*Đối với* **Mac/Linux:**

.. code-block:: bash
  
  cd fbchat-v2/src && touch mainBot.py
**Sau đó**: Tiếp tục vào file **mainBot.py**, Viết những dòng code cài đặt module như sau:

.. code-block:: python

  import __facebookToolsV2 # BẮT BUỘC
  import __messageListen # BẮT BUỘC
  import __sendMessage # BẮT BUỘC
  import __uploadImages # KHÔNG BẮT BUỘC (Tùy thuộc vào b có muốn dùng ảnh hay không)
  import json, requests, datetime, time, os

  # Đợi thêm nhé, lười viết nữa òi ^^

=======================================
Thông tin liên hệ
=======================================

- **FB:** *https://m.me/Booking.MinhHuyDev*
- **Telegram:** *https://t.me/MinhHuyDev*
- **Website**: *https://mhuyz.dev*
