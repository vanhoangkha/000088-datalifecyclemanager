# Automatically Archive Amazon EBS Snapshots with Amazon Data Lifecycle Manager

> Automating EBS snapshots with Amazon Data Lifecycle Manager.

A hands-on workshop from the [AWS First Cloud Journey](https://github.com/vanhoangkha/aws-first-cloud-journey) series, available in English and Vietnamese.

**Read the workshop online:** https://vanhoangkha.github.io/000088-datalifecyclemanager/

## Overview

Customers utilize snapshots to capture a point-in-time copy of their data, enabling disaster recovery, migrating data across regions and accounts, and enhancing backup compliance. For enterprises that rely on snapshots, there is often a need to retain snapshots that are infrequently accessed for more than 90 days for compliance reasons. However, the cost associated with storing these full snapshots for prolonged periods poses a challenge to IT budgets, leading to potential non-compliance as customers may feel pressured to delete snapshots due to financial constraints.

On November 29, 2021, Amazon Elastic Block Store (EBS) introduced the Amazon EBS Snapshots Archive, a new storage tier designed for the long-term retention of Amazon EBS snapshots of EBS volumes. We are thrilled to announce that customers can now utilize Amazon Data Lifecycle Manager – a policy-based lifecycle management solution for EBS Snapshots and EBS-backed Amazon Machine Images (AMIs) at no additional cost – to establish custom policies that automate the archival and retention of EBS Snapshots.

## Workshop contents

1. Introduction
2. Preparation
   - Launch EC2 Instance
3. Using a Single Policy Schedule
4. Use multiple policy schedules
5. Review results
6. Clean up resources

## Prerequisites

- An AWS account with permissions to create the resources used in the labs
- Basic familiarity with the AWS Management Console
- [Hugo](https://gohugo.io/installation/) (extended edition) if you want to run the site locally

## Run locally

```bash
git clone --recurse-submodules https://github.com/vanhoangkha/000088-datalifecyclemanager.git
cd 000088-datalifecyclemanager
hugo server
```

Then open http://localhost:1313 in your browser.

## Repository structure

| Path | Purpose |
| --- | --- |
| `content/` | Workshop pages (`*.md` English, `*.vi.md` Vietnamese) |
| `static/` | Images and other static assets |
| `layouts/` | Hugo layout overrides |
| `themes/` | Hugo theme |
| `config.toml` | Site configuration |

## Cost and cleanup

The labs create AWS resources that may incur charges. Complete the **Clean up** chapter when you finish to remove them.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

To report a security issue, see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
