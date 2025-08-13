# 🚀 Deploying Jenkins & Ansible Inside a Kubernetes Cluster (Manual kubeadm Setup)

---

## 📌 Introduction

In this guide, we’ll walk through **deploying Jenkins and Ansible inside a Kubernetes cluster**, fully manually set up using **kubeadm**.
The goal is to create a flexible automation environment where **Jenkins can trigger Ansible playbooks** to manage and deploy applications directly inside Kubernetes pods.

**Key Features:**

* Fully manual **kubeadm** Kubernetes setup
* **Dockerized Jenkins** and **Dockerized Ansible** pods
* Jenkins triggers Ansible using `kubectl exec`
* No external SSH or inventory required – runs directly on localhost inside the pods

---

## 📂 Project Workflow Overview

✅ **Step 1:** Kubernetes Cluster Setup using kubeadm
✅ **Step 2:** Deploy Dockerized Jenkins Pod
✅ **Step 3:** Deploy Dockerized Ansible Pod
✅ **Step 4:** Jenkins triggers Ansible Playbooks inside Kubernetes

---


## ✅ Final Thoughts

We have successfully:

* Built a **manual kubeadm Kubernetes cluster**
* Deployed **Dockerized Jenkins** and **Dockerized Ansible** pods
* Created a **local automation pipeline** without SSH or external inventory
* Used `kubectl exec` for seamless communication between Jenkins and Ansible

This setup is perfect for **learning**, **experimentation**, and **local development environments**.

---
