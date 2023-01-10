---
title : "Automatically archive Amazon EBS Snapshots with Amazon Data Lifecycle Manager"
date : "`r Sys.Date()`"
weight : 1
chapter : false
---

# Automatically archive Amazon EBS Snapshots with Amazon Data Lifecycle Manager

Customers use snapshots to capture a point-in-time copy of their data, which can be used to enable disaster recovery, migrate data across regions and accounts, and improve backup compliance. For enterprises using snapshots, it is a common requirement to keep snapshots (which are seldom accessed) for more than 90 days, for compliance purposes. However, the cost of storing these full snapshots for extended periods presents a challenge to IT budget and customers risk non-compliance by deleting snapshots due to budget pressures.

![Amazon Data Lifecycle Manager](/images/1/DLM.svg?featherlight=false&width=10pc)

On November 29 2021, Amazon Elastic Block Store (EBS) announced the availability of Amazon EBS Snapshots Archive, a new storage tier for the long-term retention of Amazon Elastic Block Store (EBS) snapshots of EBS volumes. Today, we are excited to announce that customers can now leverage Amazon Data Lifecycle Manager – a policy-based lifecycle management solution for EBS Snapshots and EBS-backed Amazon Machines Images (AMIs) available at no additional cost – to create custom policies that automate the archival and retention of EBS Snapshots.

In this workshop, we dive deeper into using Data Lifecycle Manager to automate the creation, archival, and deletion of Amazon EBS Snapshots. Customers that need to keep full, point-in-time snapshots for backup and compliance can now do so by creating ‘set-and-forget’ policies instead of having to manage and maintain complex custom scripts that may lead to data loss because of human errors.

![Launch EC2](/images/1/00010.png?featherlight=false&width=90pc)