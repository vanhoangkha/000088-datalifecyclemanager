---
title: "Introduction"
date: "`r Sys.Date()`"
weight: 1
chapter: false
pre: "<b> 1. </b>"
---

#### Introduction

In this workshop, we'll demonstrate two methods of automating snapshot archival and management using Data Lifecycle Manager. Additionally, we'll provide instructions on utilizing the EC2 Console to observe the snapshots managed and archived by Data Lifecycle Manager. The first method involves establishing an age-based policy for automating the creation and archival of snapshots through a singular policy schedule. The second method introduces a strategy to automate snapshot creation and archival across multiple policy schedules. One schedule is designed to maintain daily/weekly snapshots within the Amazon EBS Snapshot Standard tier, whereas another schedule is tasked with transferring snapshots generated on a monthly basis to the EBS Snapshots Archive tier.

![Amazon Data Lifecycle Manager](/images/1/00010.png?featherlight=false&width=90pc)
