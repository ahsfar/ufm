# 🔧 UFM / InfiniBand Commands Cheat Sheet

> All essential commands in one place for quick copy/paste and real-world troubleshooting.

---

## 🚀 All Commands

```bash
# ========================
# 📊 Basic Fabric Info
# ========================
ibstat
ibv_devinfo

# ========================
# 🔎 Topology & Discovery
# ========================
ibnetdiscover
ibhosts
ibswitches

# ========================
# 📈 Performance & Errors
# ========================
perfquery

# ========================
# 🧪 Diagnostics
# ========================
ibdiagnet

# ========================
# 🔄 UFM Service Management
# ========================
ufm status
ufm restart
ufm stop
ufm start

# ========================
# 🔥 Firmware / Switch Ops
# ========================
# Query device
flint -d lid-XXXX q

# Reset switch
flint -d lid-XXXX swreset

# Burn firmware
flint -d lid-XXXX -i <fw.bin> burn

# ========================
# 🌐 Linux Network Basics
# ========================
ip a
ip link show
ip route