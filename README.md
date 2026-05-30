# 🐧 Linux User Management

> A Linux administration project demonstrating user account management, group management, permission control, and shell scripting automation.

*Collaborative project with [AtchayaDurga](https://github.com/AtchayaDurga)*

---

## 📌 Overview

This project covers core Linux system administration tasks — managing users, groups, and file permissions through shell scripts. Built to demonstrate hands-on Linux skills relevant to DevOps, cybersecurity, and system administration roles.

---

## ⚙️ Features

- 👤 **User Account Management** — Create, modify, and delete user accounts using shell commands
- 👥 **Group Management** — Assign users to groups, manage group permissions
- 🔐 **Permission Control** — Set and manage file/directory permissions using `chmod`, `chown`, `chgrp`
- 🤖 **Shell Script Automation** — Automate repetitive admin tasks with Bash scripts
- 📋 **Audit & Logging** — Track user activity and system changes

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Bash / Shell | Scripting and automation |
| Linux (Ubuntu) | Operating system |
| `useradd` / `usermod` / `userdel` | User management commands |
| `chmod` / `chown` / `chgrp` | Permission management |
| `groupadd` / `gpasswd` | Group management |

---

## 📂 Project Structure

```
Linux-user-management/
└── Linux user management/
    ├── user_management.sh       # User create/modify/delete scripts
    ├── group_management.sh      # Group assignment scripts
    ├── permission_control.sh    # Permission management scripts
    └── automation/              # Automated admin task scripts
```

---

## 🚀 Getting Started

### Prerequisites
- Linux system (Ubuntu/Debian recommended)
- Root or sudo access

### Run the scripts

```bash
# Clone the repository
git clone https://github.com/harinym112/Linux-user-management.git
cd Linux-user-management

# Give execute permission
chmod +x *.sh

# Run user management script
sudo ./user_management.sh
```

---

## 📚 Concepts Covered

- Linux user and group hierarchy
- File permission model (read/write/execute)
- `sudoers` configuration
- Shell scripting best practices
- System administration automation

---

## 🤝 Collaborators

| Name | GitHub |
|------|--------|
| Hariny M | [@harinym112](https://github.com/harinym112) |
| Atchaya Durga | [@AtchayaDurga](https://github.com/AtchayaDurga) |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
