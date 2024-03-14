---
title: Quick Hit - Update kubeconfig for EKS
date: 2024-03-09
tags: kubernetes, eks, aws, kubeconfig
summary: This is part of a series of posts that I am going to create as time goes on. The point is for a short quick post that demonstrates how to complete a simple task. In this post, I will demonstrate how to update your KUBECONFIG to work with an EKS cluster.
slug: update-kubeconfig-eks
---

# Quick Hit - Updating Kubeconfig for EKS

This is part of a series of posts that I am going to create as time goes on. The point is for a short quick post that demonstrates how to complete a simple task.

In this post, I will demonstrate how to update your KUBECONFIG to work with an EKS cluster.

First, we need to create a new kubeconfig file. This is done via the command line. You will need to have AWS CLI installed and configured first.

```sh
aws eks update-kubeconfig --region <region> --name <cluster-name> --kubeconfig <path-to-file-to-create>
```

After that is done, we need to update the KUBECONFIG environment variable to include the path to the newly created file. If you want to make this persist across sessions, you will need to add this to your shell profile.

```sh
export KUBECONFIG="${KUBECONFIG}:<path-to-file-created-above>"
```

