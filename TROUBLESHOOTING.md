# 🚨 UFM Troubleshooting Guide

> Quick reference for diagnosing and fixing common InfiniBand / UFM issues.

---

## ⚡ Quick Troubleshooting Flow

1. Check fabric status  
2. Check topology  
3. Check errors/counters  
4. Run diagnostics  
5. Verify SM  
6. Restart UFM if needed  

---

## 🚀 All Troubleshooting Commands

```bash
# ========================
# 📊 Check Fabric Status
# ========================
ibstat
ibv_devinfo

# ========================
# 🔎 Check Topology
# ========================
ibnetdiscover
ibhosts
ibswitches

# ========================
# 📈 Check Errors / Counters
# ========================
perfquery

# ========================
# 🧪 Full Diagnostics
# ========================
ibdiagnet

# ========================
# 🔄 UFM Recovery
# ========================
ufm status
ufm restart
ufm stop
ufm start