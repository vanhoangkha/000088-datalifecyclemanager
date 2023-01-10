---
title : "Introduction"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---

#### Introduction

In this workshop, we will showcase two examples of how you can automate snapshot archival and management with Data Lifecycle Manager, followed by guidance on how you can use the EC2 Console to view the snapshots managed and archived by Data Lifecycle Manager. In the first example, we will create an age-based policy to automate snapshot creation and archival with a single policy schedule. In the second example, we will create a policy to automate snapshot creation and archival using multiple policy schedules. One schedule will keep daily/weekly snapshots in the Amazon EBS Snapshot Standard tier (standard tier), while the other moves snapshots created on a monthly cadence to the EBS Snapshots Archive tier.

![Amazon Data Lifecycle Manager](/images/1/00010.png?featherlight=false&width=90pc)

