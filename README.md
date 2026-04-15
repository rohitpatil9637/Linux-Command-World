# 🐧 Linux Commands World — Complete Interview & Exam Reference

> Designed, single-file HTML reference guide for **200+ Linux commands** — organized by topic, tagged for interviews, and packed with real-world examples.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-Single_File-E34F26?logo=html5&logoColor=white)](linux-guide.html)
[![Commands](https://img.shields.io/badge/Commands-200%2B-blue)](linux-guide.html)
[![RHCSA](https://img.shields.io/badge/Exam-RHCSA%20%7C%20LFCS-purple)](linux-guide.html)

---

## 📚 Sections Covered

| # | Section | Commands | Topics |
|---|---------|----------|--------|
| 1 | 💻 **Essential Tools & Shell** | 17 | Shell basics, I/O redirection, grep, SSH, pipes, awk, sed, find |
| 2 | 📁 **File & Directory Management** | 14 | cp, mv, rm, tar, gzip, symlinks, diff, stat, du/df |
| 3 | 🔒 **Permissions, Links & ACLs** | 7 | chmod, chown, umask, SUID/SGID/Sticky, ACLs, chattr |
| 4 | 📦 **Package Management** | 9 | DNF/YUM, RPM queries, Flatpak, repo management |
| 5 | 📄 **Shell Scripting** | 11 | if/for/while/case, functions, variables, traps, strict mode |
| 6 | ⚙️ **Running Systems & Processes** | 14 | systemctl, ps, top, kill, nice, journalctl, rsync, scp |
| 7 | 💾 **Local Storage & LVM** | 9 | lsblk, fdisk/gdisk, PV/VG/LV, swap, LVM resize |
| 8 | 📊 **File Systems & Mounting** | 11 | mkfs, mount/fstab, UUID, NFS, autofs, fsck, xfs_growfs |
| 9 | 🕛 **System Maintenance & Boot** | 8 | cron/at, timedatectl, chrony, GRUB2, password reset |
| 10 | 🌐 **Network Configuration** | 9 | ip addr/route, nmcli, DNS, ss/netstat, nmap, firewall |
| 11 | 👤 **Users & Groups** | 9 | useradd/mod/del, passwd, chage, sudo, /etc/shadow |
| 12 | 🛡️ **Security: SELinux & Firewall** | 12 | SELinux contexts/booleans/ports, firewalld zones/rules |

---

## 🚀 Quick Start

### Option 1: Direct download
```bash
# Clone or download the file
git clone https://github.com/YOUR_USERNAME/linux-commands-reference.git

# Open in your browser
open linux-guide.html        # macOS
xdg-open linux-guide.html    # Linux
start linux-guide.html       # Windows
```

### Option 2: Just open it
Simply **double-click** `linux-guide.html` — it runs entirely in your browser with zero setup.




## 🗂️ Project Structure

```
.
├── linux-guide.html    # Complete application (single file)
└── README.md           # This file
```

---

## 📝 Contributing

Contributions are welcome! To add a new command:

1. Open `linux-guide.html`
2. Find the appropriate section in the `data` array (line ~607)
3. Add a new object to the `cmds` array:

```javascript
{
  cmd: "command --flags",           // Command syntax
  desc: "What it does",            // Description
  ex: "real-world example",        // Example (optional)
  tip: "Pro tip or interview note", // Tip (optional)
  interview: true,                  // Flag as exam topic (optional)
  tags: ["tag1", "tag2"]           // Searchable tags
}
```

4. Submit a pull request

---

## 📄 License

[MIT License](LICENSE).

---

## ⭐ Support

If you found this helpful, give it a **star** ⭐ and share it with fellow Linux learners!

---

<p align="center">
  <b>Author: ROHIT PATIL</b>
  <b>Made for the Linux community</b><br>
  <sub>200+ commands · 12 sections · Interview-ready · RHCSA/LFCS aligned</sub>
</p>

