---
title: "Sử dụng nhiều policy schedule"
date: "`r Sys.Date()`"
weight: 4
chapter: false
pre: "<b> 4. </b>"
---

#### Sử dụng nhiều policy schedule

1. Tương tự như trước, nhưng lần này chúng ta sẽ tạo nhiều policy schedule với một policy lifecycle.

   - Truy cập vào giao diện **Data Lifecycle Manager**.
   - Chọn **Create lifecycle policy**.

![Sử dụng nhiều policy schedule](/images/3/0001.png?featherlight=false&width=90pc)

2. Chọn **EBS snapshot policy**.

   - Nhấn **Next**.

![Sử dụng nhiều policy schedule](/images/3/0002.png?featherlight=false&width=90pc)

3. Tại mục **Target resource**, chọn **Volume**.

   - Chọn theo tag: **FCJ-Volume**.
   - Đặt mô tả: **FCJ-DLM-Week policy**.

![Sử dụng nhiều policy schedule](/images/3/0003.png?featherlight=false&width=90pc)

4. Sử dụng **IAM Role** mặc định.

   - Nhấn **Next**.

![Sử dụng nhiều policy schedule](/images/3/0004.png?featherlight=false&width=90pc)

5. Tiếp tục đến bước cấu hình **Schedule**.

   - Tại **Schedule name**, nhập tên tùy chọn.
   - Chọn **Frequency** là **Weekly**.
   - Chọn các ngày bạn muốn.
   - Đặt thời gian bắt đầu vào lúc **09:00**.
   - Tại **Retention type**, chọn **Age** và thiết lập **180 days**.

![Sử dụng nhiều policy schedule](/images/3/0005.png?featherlight=false&width=90pc)

6. Chọn **Add another schedule**.

![Sử dụng nhiều policy schedule](/images/3/0006.png?featherlight=false&width=90pc)

7. Cấu hình **Schedule** thứ hai.

   - Tại **Schedule name**, nhập tên tùy chọn.
   - Chọn **Frequency** là **Monthly**.
   - Chọn **Day** và **Last**.
   - Đặt thời gian bắt đầu vào lúc **09:00**.
   - Tại **Retention type**, chọn **Age** và thiết lập **1 day**.

![Sử dụng nhiều policy schedule](/images/3/0007.png?featherlight=false&width=90pc)

8. Chọn **Advanced settings**.

![Sử dụng nhiều policy schedule](/images/3/0008.png?featherlight=false&width=90pc)

9. Tại **Snapshot archiving**.

   - Chọn **Archive snapshots created by this schedule**.
   - Lưu trữ snapshots trong **90 days**.
   - Nhấn **Review policy**.

![Sử dụng nhiều policy schedule](/images/3/0009.png?featherlight=false&width=90pc)

10. Kiểm tra lại thông tin và chọn **Create policy**.

![Sử dụng nhiều policy schedule](/images/3/00010.png?featherlight=false&width=90pc)

11. Hoàn thành việc tạo **lifecycle policy**.

![Sử dụng nhiều policy schedule](/images/3/00011.png?featherlight=false&width=90pc)
