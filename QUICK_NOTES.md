# ⚡ UFM Quick Notes (Certification Cheat Sheet)

---

## 📦 UFM Components

### UFM Telemetry
- Real-time monitoring
- Switch, adapter, cable telemetry
- CLI-based
- Streams to external tools

### UFM Enterprise
- Network management
- Orchestration
- Monitoring tools
- Flexible deployment

### UFM Cyber-AI
- Detects performance degradation
- Detects user anomalies
- Smart alerts
- Recommended actions

---

## 🧠 Key Concepts

- **SM (Subnet Manager)** → Controls routing
- **SA (Subnet Administrator)** → Handles queries
- **LID** → Local ID in fabric
- **GUID** → Unique device ID
- **PKey** → Partition (like VLAN)
- **Trap 128** → Fabric event (often issue indicator)

---

## ⚡ Exam Tips

- Know differences between Telemetry / Enterprise / Cyber-AI
- Understand SM vs SA roles
- Focus on troubleshooting flow
- Understand purpose of commands (not deep syntax)

---

## 🧪 Quick Checks

- Is SM running?
- Any trap floods?
- Ports stable?
- Errors increasing?
- Links up?
- UFM active?

---

## 📝 Notes

- UFM restart ≠ always enough → use stop/start if needed
- Not all errors = cable issue
- High discards often = host/NIC issue
