# 🔥 Day 3 – Users and Groups

**Focus:** Learning how Linux manages users and groups, and how permissions change with administrative powers.  

---

## What I Learned
- A **user** is like a citizen of the kingdom, each with a name, home, and powers.  
- A **group** is like a guild, multiple users can share permissions.  
- The **king (root)** is the superuser who can do anything.  
- Learned key commands:  
  - `whoami` → check current user.  
  - `groups` → see group memberships.  
  - `id` → check UID and GID.  
  - `sudo adduser <name>` → create a new user.  
  - `su <name>` → switch to another user.  
  - `sudo usermod -aG sudo <name>` → give a user sudo powers.  
- New users cannot run admin commands until added to the `sudo` group.  

---

## Deliverables
- [Lab Report](lab-report.md)  
- [CLI Screenshot](images/CLI.png)  
- [GUI Screenshot](images/GUI.png)  
