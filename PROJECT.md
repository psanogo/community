# 🚀 Project: Secure Microservices with Calico

## 🎯 Objective

Build a Kubernetes system where:
- Services communicate selectively
- Security is enforced using Calico

---

## 🧱 Architecture

Services:
- Frontend
- Backend
- Database

---

## 🔄 Communication Rules

| Source     | Destination | Allowed |
|------------|------------|--------|
| Frontend   | Backend     | ✅ Yes |
| Backend    | Database    | ✅ Yes |
| Frontend   | Database    | ❌ No  |

---

## 🔐 Security Implementation

Used Calico Network Policies to:
- Allow trusted communication
- Block direct access to database

---

## 🧪 Testing

- Verified pods connectivity
- Confirmed blocked traffic

---

## 💡 What I Learned

- Network policies are powerful security tools
- Default allow can be dangerous
- Isolation improves system safety

---

## 🔥 Key Takeaway

> "Security is not just authentication—it's controlling communication."

---

## 🧭 Future Improvements

- Add logging and monitoring
- Test with real applications
- Explore advanced Calico features
