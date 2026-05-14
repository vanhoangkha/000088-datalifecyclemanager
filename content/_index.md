---
title: "Automatically Archive Amazon EBS Snapshots with Amazon Data Lifecycle Manager"
date: 2024-01-01
weight: 1
chapter: false
---

# Automatically Archive Amazon EBS Snapshots with Amazon Data Lifecycle Manager

Customers utilize snapshots to capture a point-in-time copy of their data, enabling disaster recovery, migrating data across regions and accounts, and enhancing backup compliance. For enterprises that rely on snapshots, there is often a need to retain snapshots that are infrequently accessed for more than 90 days for compliance reasons. However, the cost associated with storing these full snapshots for prolonged periods poses a challenge to IT budgets, leading to potential non-compliance as customers may feel pressured to delete snapshots due to financial constraints.

![Amazon Data Lifecycle Manager](/images/1/DLM.svg?featherlight=false&width=10pc)

On November 29, 2021, Amazon Elastic Block Store (EBS) introduced the Amazon EBS Snapshots Archive, a new storage tier designed for the long-term retention of Amazon EBS snapshots of EBS volumes. We are thrilled to announce that customers can now utilize Amazon Data Lifecycle Manager – a policy-based lifecycle management solution for EBS Snapshots and EBS-backed Amazon Machine Images (AMIs) at no additional cost – to establish custom policies that automate the archival and retention of EBS Snapshots.

In this workshop, we explore how to use Data Lifecycle Manager to automate the creation, archival, and deletion of Amazon EBS Snapshots. Customers who need to maintain full, point-in-time snapshots for backup and compliance purposes can now achieve this through 'set-and-forget' policies, eliminating the need for complex custom scripts that could result in data loss due to human errors.

![Launch EC2](/images/1/00010.png?featherlight=false&width=90pc)

