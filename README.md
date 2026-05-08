# Insanely Small Linux (ISL)

**"A Linux distribution so small, it shouldn't exist."**

`Insanely Small Linux (ISL)` is a minimalist, kernel-focused operating system designed to push the absolute limits of the x86_64 architecture. Developed by Naoto, this project focuses on extreme optimization, achieving a functional OS in just **5.4 MB**.

---

## 🚀 Key Achievements

* **The 15MB Milestone:** Slashed over 80% of the size from standard minimal builds by ditching GRUB in favor of a precision-tuned `ISOLINUX` bootloader.
* **Pure Kernel Hacking:** A custom-compiled Linux Kernel 7.0.x, stripped of every non-essential driver and debug symbol.
* **Bespoke UI/UX:** Features a custom-coded login manager and shell interface, built entirely in POSIX-compliant shell script.
* **Instant Execution:** Boots directly into the user interface in milliseconds, bypassing traditional systemd/init overhead.

## 🛠 Specifications

- **OS Name:** Insanely Small Linux (ISL)
- **Kernel:** 7.0.3 (Custom Minimalist Build)
- **Bootloader:** ISOLINUX (El Torito No-Emulation Mode)
- **Userland:** BusyBox (Statically Linked)


---

## 👨‍💻 The Developer's Mission

The goal was simple but insane: How much can we remove before a Linux system stops being a Linux system? 

ISL is the result of that obsession. From the "17.9MB barrier" to the current "5.4MB breakthrough," every byte has been audited, every kernel flag has been questioned, and every unnecessary driver has been "hacked" away.

MIT License. Open for forks, hacks, and further minimization.
