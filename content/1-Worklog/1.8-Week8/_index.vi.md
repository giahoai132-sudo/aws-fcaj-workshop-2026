---
title: "Worklog tuần 8"
date: 2026-05-31
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:

* Tìm hiểu Amazon ECS.
* Tìm hiểu các thành phần của Amazon ECS.
* Thực hành triển khai ứng dụng trên Amazon ECS.
* Tìm hiểu các khái niệm về CI/CD.
* Tìm hiểu AWS CodePipeline.
* Tìm hiểu tích hợp GitHub với AWS.

### Công việc thực hiện trong tuần:

| Ngày | Công việc | Ngày bắt đầu | Ngày hoàn thành | Tài liệu tham khảo |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | ---------------- | ----------------------------------------- |
| 1   | - Tìm hiểu Amazon ECS nâng cao: <br>&emsp; + ECS Service Discovery <br>&emsp; + Task Placement Strategy <br>&emsp; + Capacity Provider Strategy <br>&emsp; + Rolling Update & Blue/Green Deployment <br> - Tìm hiểu Amazon ECS Exec để truy cập Container đang chạy | 31/05/2026 | 31/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 2   | - Tìm hiểu AWS CodePipeline: <br>&emsp; + Pipeline, Stage, Action <br>&emsp; + Source Stage (GitHub, CodeCommit, S3) <br>&emsp; + Build Stage (CodeBuild) <br>&emsp; + Deploy Stage (ECS, CloudFormation, Lambda) <br>&emsp; + Manual Approval | 01/06/2026 | 01/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 3   | - Tìm hiểu AWS CodeBuild: <br>&emsp; + Build Environment <br>&emsp; + Buildspec.yml <br>&emsp; + Environment Variables <br>&emsp; + Build Artifact <br>&emsp; + Logging với CloudWatch | 02/06/2026 | 02/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - **Thực hành:** Xây dựng CI/CD Pipeline: <br>&emsp; + Kết nối GitHub với CodePipeline <br>&emsp; + Build Docker Image bằng CodeBuild <br>&emsp; + Push Image lên Amazon ECR <br>&emsp; + Deploy ứng dụng lên Amazon ECS | 03/06/2026 | 03/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Tìm hiểu GitHub Actions: <br>&emsp; + Workflow, Job, Step <br>&emsp; + GitHub-hosted Runner <br>&emsp; + Secrets & Variables <br>&emsp; + Trigger: push, pull_request, workflow_dispatch <br>&emsp; + Cache Dependency | 04/06/2026 | 04/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - **Lab tổng hợp:** <br>&emsp; + Xây dựng CI/CD với GitHub Actions <br>&emsp; + Build & Push Docker Image lên Amazon ECR <br>&emsp; + Tự động Deploy lên Amazon ECS <br>&emsp; + Kiểm tra Pipeline và Rollback khi lỗi | 05/06/2026 | 05/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 7   | - Ôn tập nội dung tuần. <br>&emsp; + Tổng hợp kiến thức về Amazon ECS, CodePipeline, CodeBuild và GitHub Actions <br>&emsp; + Hoàn thiện Worklog và Workshop | 06/06/2026 | 06/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Kết quả đạt được trong tuần 8:

* Tìm hiểu Amazon ECS:
  * Hiểu mục đích của điều phối container.
  * Nắm được kiến trúc cơ bản của Amazon ECS.
  * Biết các trường hợp sử dụng phổ biến của ECS.

* Tìm hiểu các thành phần của Amazon ECS:
  * Cluster.
  * Service.
  * Task Definition.

* Thực hành Amazon ECS:
  * Làm quen với giao diện quản lý ECS.
  * Hiểu quy trình triển khai ứng dụng.
  * Nắm được các tài nguyên cơ bản của ECS.

* Tìm hiểu các khái niệm về CI/CD:
  * Hiểu Continuous Integration.
  * Hiểu Continuous Deployment.
  * Nắm được quy trình triển khai tự động.

* Tìm hiểu AWS CodePipeline:
  * Hiểu các giai đoạn Source, Build và Deploy.
  * Hiểu quy trình hoạt động của Pipeline.

* Tìm hiểu tích hợp GitHub:
  * Hiểu quản lý phiên bản bằng Git.
  * Hiểu cách GitHub tích hợp với AWS CodePipeline.

* Nâng cao kiến thức về Amazon ECS, CI/CD và quy trình triển khai ứng dụng.