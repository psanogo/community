# 📘 Calico Notes

## 🌐 What Calico Does

Calico provides:
- Networking between containers
- Security through network policies

It ensures:
- Pods can communicate efficiently
- Traffic is controlled and secure

---

## 🧠 Core Concepts

### 1. Pods
Smallest deployable unit in Kubernetes.

### 2. Networking
Each pod gets its own IP address.

### 3. Network Policy
Rules that control traffic flow between pods.

---

## 🔐 Why Calico Matters

By default:
- Kubernetes allows all traffic

With Calico:
- You control who talks to who
- You reduce security risks

---

## 🧩 Example

Without Calico:
- Any service can access any other

With Calico:
- Only allowed services can connect

---

## ⚙️ Key Features

- Layer 3 networking
- High performance
- Fine-grained security policies

---

## 💡 Insight

Calico is not just networking—it’s **security at the network level**.
