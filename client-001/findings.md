# Web Recon Report – Client 001
**Target:** testphp.vulnweb.com  
**Date:** June 27, 2025  
**Tool:** Nmap 7.95

---

## 🌐 Host Info
- IP: 44.228.249.3
- Reverse DNS: ec2-44-228-249-3.us-west-2.compute.amazonaws.com
- Host is up (latency: 0.24s)

---

## 🔍 Open Port
- **Port 80/tcp** – HTTP  
  - Service: nginx 1.19.0  
  - HTTP Title: "Home of Acunetix Art"

---

## ⚠️ Observations
- All other 999 TCP ports are filtered
- OS detection failed (filtered ports)
- Default web page may indicate weak config

---

## ✅ Recommendations
- Update nginx version
- Customize default index page
- Proceed with Nikto scan
