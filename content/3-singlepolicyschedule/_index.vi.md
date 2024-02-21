---
title: "Sử dụng một policy schedule"
date: "`r Sys.Date()`"
weight: 3
chapter: false
pre: "<b> 3. </b>"
---

#### Sử dụng một policy schedule

1. Truy cập vào giao diện **EC2**
   - Chọn **Lifecycle Manager**
   - Chọn **Next step**

![Sử dụng một lịch trình policy duy nhất](/images/2/0001.png?featherlight=false&width=90pc)

2. Trong bước **setting**, thực hiện chọn **Target resources**
   - **Target resource type** chọn **Volume**
   - Chọn theo tags là **FCJ-Volume**

![Sử dụng một lịch trình policy duy nhất](/images/2/0002.png?featherlight=false&width=90pc)

3. Sử dụng IAM role mặc định.

![Sử dụng một lịch trình policy duy nhất](/images/2/0003.png?featherlight=false&width=90pc)

4. Sau đó, chọn **Next**

![Sử dụng một lịch trình policy duy nhất](/images/2/0004.png?featherlight=false&width=90pc)

5. Đối với cấu hình **Schedule**:
   - Ở mục này, chúng ta sẽ cấu hình một schedule và một policy.
   - Phần **Schedule name**, đặt tên tùy ý.
   - Phần **Frequency**, chọn **Daily**.
   - **Every**, chọn **1 hour**.
   - **Starting at** lúc **14:00**, bạn có thể tùy chỉnh.
   - Đối với **Retention type**, chọn **30 days**.

![Sử dụng một lịch trình policy duy nhất](/images/2/0005.png?featherlight=false&width=90pc)

6. Chọn **Review policy**

![Sử dụng một lịch trình policy duy nhất](/images/2/0006.png?featherlight=false&width=90pc)

7. Chọn **Create policy**

![Sử dụng một lịch trình policy duy nhất](/images/2/0007.png?featherlight=false&width=90pc)

8. Tạo **lifecycle policy** thành công.

![Sử dụng một lịch trình policy duy nhất](/images/2/0008.png?featherlight=false&width=90pc)
