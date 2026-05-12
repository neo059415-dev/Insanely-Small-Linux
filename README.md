# Insanely Small Linux (ISL)

`Insanely Small Linux (ISL)` is a minimalist, kernel-focused operating system designed to push the absolute limits of the x86_64 architecture. Developed by Neo. this project focuses on extreme optimization, achieving a functional OS in just **5MB**.

- *Current latest version: 1.3*

---

## Key Achievements

* **The 5MB Milestone:** Slashed over 80% of the size from standard minimal builds by ditching GRUB in favor of a precision-tuned `ISOLINUX` bootloader.
* **Pure Kernel Hacking:** A custom-compiled Linux Kernel 7.0.3, stripped of every non-essential driver and debug symbol.
* **Bespoke UI/UX:** Features a custom-coded login manager and shell interface, built entirely in POSIX-compliant shell script.
* **Instant Execution:** It boots directly into the shell for maximum speed.

## Specifications

- **OS Name:** Insanely Small Linux (ISL)
- **Kernel:** 7.0.3 (Custom Minimalist Build)
- **Bootloader:** ISOLINUX (El Torito No-Emulation Mode)
- **Userland:** BusyBox (Statically Linked)

MIT License. Open for forks, hacks, and further minimization.

## Screenshots

![alt](https://a.fsdn.com/con/app/proj/insanely-small-linux/screenshots/Screenshot%20From%202026-05-13%2000-09-22-9dc9acd2.png/max/max/1)

## Open Source Compliance

This project utilizes open-source software. In compliance with the **GPL v2**, the following resources are provided:

- **Kernel & BusyBox Config:** Found in the `/LEGAL` directory. These files contain the exact configuration used to achieve the 5.4MB size.
- **Upstream Sources:**
  - Linux Kernel: [kernel.org](https://www.kernel.org)
  - BusyBox: [busybox.net](https://www.busybox.net)
- **Modifications:** All custom scripts (`/init`, `/bin/MyShell`) are original works by the developer and are provided under the MIT License.

## Sourceforge URL

Older versions can be downloaded from here.

- https://sourceforge.net/projects/insanely-small-linux/

## Contact

Questions, bug reports or suggestions:

- neo059415@gmail.com
