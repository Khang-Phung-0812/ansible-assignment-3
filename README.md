
---

# ✅ **README.md — Assignment 3**

```markdown
# Assignment 3 – Configure NTP, Logging, Timezone & Role-Based Banners
**Student:** Tran Minh Khang Phung  
**Course:** CNIT381 – Network Automation

## 📘 Description
This playbook configures NTP servers, logging settings, and timezone across all routers.  
It applies different login banners based on router roles defined in inventory groups (core vs distribution).  
The playbook verifies banner and NTP configuration using IOS show commands.

## ▶️ How to Run
```bash
ansible-playbook -i inventory.ini assignment3.yaml
