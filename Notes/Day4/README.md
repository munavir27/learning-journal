# 🔥 Day 4 – Processes and Monitoring

**Focus:** Learning how to manage processes in Linux, monitor system activity, and simulate real-world incident response.  

---

## What I Learned
- A **process** is a running program, each with a unique PID (Process ID).  
- **Foreground process** = runs in front of you.  
- **Background process** = runs silently while you continue working.  
- Key commands:  
  - `ps aux | less` → snapshot of running processes.  
  - `top` → live activity monitoring.  
  - `htop` → advanced, colorful process monitor.  
  - `ping <target>` → start a foreground process.  
  - `ping <target> &` → run in background.  
  - `kill <PID>` → stop a process.  
  - `kill -9 <PID>` → force kill.  
- Attackers may hide malicious processes, so defenders must spot and eliminate them.  

---

## Deliverables
- [Lab Report](lab-report.md)  
- [CLI_1 Screenshot](images/CLI_1.png)  
- [CLI_2 Screenshot](images/CLI_2.png)  

---
