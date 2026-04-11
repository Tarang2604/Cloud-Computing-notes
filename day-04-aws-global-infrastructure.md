# 📅 Day 4 - AWS Global Infrastructure 🌍

## ☁️ Introduction

:contentReference[oaicite:0]{index=0} (AWS) provides a global cloud infrastructure to deliver services worldwide.

---

## 🌍 AWS Global Infrastructure Components

### 🗺 Region
A region is a **geographical area** where AWS has data centers.

👉 Example:
India Region (Mumbai)

---

### 🏢 Availability Zone (AZ)
- Each region contains multiple AZs  
- AZs are isolated data centers  
- Connected with high-speed networks  

👉 Example:
India Region:
- AZ-1  
- AZ-2  
- AZ-3  

👉 Each AZ may contain **50k–80k servers**

---

### 🌐 Edge Locations

Edge locations are used for **content delivery** and low latency.

👉 Services:
- Route 53 (DNS)
- CloudFront (CDN)
- Lambda@Edge
- AWS WAF / Shield (Security)

---

## 🔁 How It Works Together

User → Internet → AWS Region → Availability Zones → Servers  

👉 Data is distributed across AZs for:
- High availability  
- Fault tolerance  
- Better performance  

---

## 🌎 AWS Global Network

AWS has a **global fiber network** connecting:
- Regions  
- AZs  
- Edge locations  

👉 Ensures:
- Fast data transfer  
- Low latency  
- High reliability  

---

## 🖥 Data Centers

- Physical server rooms  
- Store and process data  
- Highly secure and scalable  

---

## 📚 What I Learned Today

- AWS global infrastructure structure  
- Difference between Region, AZ, and Edge Location  
- How AWS ensures high availability and performance  
