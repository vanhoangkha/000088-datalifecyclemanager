---
title: "Tự động lưu trữ Amazon EBS Snapshot với Amazon Data Lifecycle Manager"
date: 2024-01-01
weight: 1
chapter: false
---

# Tự động lưu trữ Amazon EBS Snapshot với Amazon Data Lifecycle Manager

Khách hàng sử dụng snapshot để chụp một bản sao dữ liệu của họ theo thời gian. Bản sao này có thể được sử dụng để cho phép khôi phục sau thảm họa, di chuyển dữ liệu giữa các region và tài khoản cũng như cải thiện việc tuân thủ sao lưu. Đối với các doanh nghiệp sử dụng snapshot, yêu cầu phổ biến là giữ snapshot (hiếm khi được truy cập) trong hơn 90 ngày, vì mục đích tuân thủ. Tuy nhiên, chi phí lưu trữ toàn bộ các snapshot này trong thời gian dài gây ra thách thức đối với ngân sách CNTT và khách hàng có nguy cơ không tuân thủ bằng cách xóa snapshot do áp lực ngân sách.

![Amazon Data Lifecycle Manager](/images/1/DLM.svg?featherlight=false&width=10pc)

Vào ngày 29 tháng 11 năm 2021, Amazon Elastic Block Store (EBS) đã công bố tính khả dụng của Amazon EBS Snapshots Archive, một cấp lưu trữ mới để lưu giữ lâu dài snapshot của Amazon Elastic Block Store (EBS) đối với các EBS volume. Hôm nay, chúng tôi rất vui mừng thông báo rằng khách hàng hiện có thể tận dụng Amazon Data Lifecycle Manager - một giải pháp quản lý vòng đời dựa trên chính sách dành cho EBS snapshot và EBS-backed Amazon Machines Images (AMI) được hỗ trợ bởi EBS mà không phải trả thêm phí - để tạo các chính sách tùy chỉnh giúp tự động hóa lưu trữ và lưu giữ EBS snapshot.

Trong bài lab này, chúng tôi đi sâu hơn vào việc sử dụng Amazon Data Lifecycle Manager để tự động hóa việc tạo, lưu trữ và xóa Amazon EBS snapshot. Những khách hàng cần lưu giữ các snapshot đầy đủ, đúng thời điểm để sao lưu và tuân thủ hiện có thể làm như vậy bằng cách tạo các chính sách "thiết lập và quên" thay vì phải quản lý và duy trì các tập lệnh tùy chỉnh phức tạp có thể dẫn đến mất dữ liệu do con người lỗi.

![Amazon Data Lifecycle Manager](/images/1/00010.png?featherlight=false&width=90pc)

#### Nội dung

1. [Giới thiệu](1-introduce/)
2. [Các bước chuẩn bị](2-prerequiste/)
3. [Tạo một policy schedule](3-singlepolicyschedule/)
4. [Tạo nhiều policy schedule](4-mutilplolicyschedule/)
5. [Kiểm tra kết quả](5-monitoring/)
6. [Dọn dẹp tài nguyên](6-cleanup/)
