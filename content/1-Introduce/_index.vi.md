---
title : "Giới thiệu"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---

####  Giới thiệu

Chúng tôi sẽ giới thiệu hai ví dụ về cách bạn có thể tự động hóa việc lưu trữ và quản lý snapshot với Data Lifecycle Manager, tiếp theo là hướng dẫn về cách bạn có thể sử dụng Bảng điều khiển EC2 để xem snapshot được quản lý và lưu trữ với Data Lifecycle Manager. Trong ví dụ đầu tiên, chúng tôi sẽ tạo chính sách dựa trên độ tuổi để tự động tạo và lưu trữ snapshot với một lịch trình chính sách duy nhất. Trong ví dụ thứ hai, chúng tôi sẽ tạo một chính sách để tự động tạo và lưu trữ snapshot bằng cách sử dụng nhiều lịch trình chính sách. Một lịch biểu sẽ giữ các snapshot hàng ngày / hàng tuần trong Amazon EBS Snapshot Standard tier (standard tier), trong khi lịch biểu còn lại chuyển snapshot được tạo theo chu kỳ hàng tháng sang EBS Snapshots Archive tier.

![Launch EC2](/images/1/00010.png?featherlight=false&width=90pc)