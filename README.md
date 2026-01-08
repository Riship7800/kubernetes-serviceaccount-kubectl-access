# Kubernetes ServiceAccount Based kubectl Access

## 📌 Project Overview
This project demonstrates how to configure Kubernetes ServiceAccounts
to enable automated and secure kubectl access without using a human user.

## 🛠 Tools Used
- Kubernetes (Minikube)
- kubectl
- RBAC
- ServiceAccounts

## 🚀 What I Implemented
- Created Kubernetes ServiceAccount
- Applied RBAC using ClusterRoleBinding
- Generated ServiceAccount token (Kubernetes v1.24+)
- Built a custom kubeconfig for automated kubectl access
- Verified access using kubectl commands

## 📂 Use Case
- CI/CD pipelines
- Automation scripts
- Secure non-human Kubernetes access

## ⚠️ Security Note
Cluster-admin role is used only for learning purposes.
In production, least-privilege roles should be applied.
