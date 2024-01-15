---
post: true
title: "Autoscaling GitHub Actions Runners Using Hetzner Cloud"
description: FIXME
date: 2024-01-10
author: Vitaliy Zakaznikov
image: FIXME
icon: fas fa-glasses pt-5 pb-5
---

Discover how you can Autoscaling GitHub Actions Runners Using Hetzner Cloud,using github-hetzner-runners service,a practical tool designed to enhance the efficiency of GitHub Actions workflows. This service automatically starts servers in Hetzner Cloud when new GitHub Actions jobs are queued, providing dedicated and ephemeral runners for each task. Once a job is completed, the service takes care of shutting down and deleting the server, ensuring a cost-effective and streamlined process. This article will cover how github-hetzner-runners supports both x64 and arm64 runners, its straightforward setup, and how it manages costs effectively, making it a smart choice for any GitHub repository.

# ?
This service offers an innovative solution for GitHub Actions workflows by providing cost-efficient, on-demand runners utilizing Hetzner Cloud. It stands out for its simple configuration process, eliminating the need for complex setups like Webhooks, AWS Lambdas, or additional GitHub applications. Users benefit from the ability to customize runner server types, images, and locations using job labels, making it highly adaptable to specific project needs. The service is a self-contained program, allowing for easy deployment, redeployment, and management directly on a cloud instance. It supports a wide range of runner types, including both x64 (x86) and ARM64 (arm) architectures, and is compatible with any Hetzner Cloud server types and standard images or applications, even those with pre-installed Docker. Efficiency is further enhanced with features like auto-replenishable standby runner pools for immediate job uptake and the ability to limit the number of runners per workflow, ensuring resources are used judiciously. Additionally, it optimizes GitHub API interactions through HTTP caching and conditional requests, presenting itself as a simpler, more efficient alternative to other autoscaling solutions recommended by GitHub.
