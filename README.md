<h1 align="center">OpenOffice.org 2.4 README </h1>

<p align="center">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQB06vQWMpgy7Y6s5qRnCSl7sXqKgs2fvRCWw&s" alt="OpenOffice.org Logo">
</p>

---

## Welcome 🎉

Thank you for using **OpenOffice.org 2.4**! This document provides essential information to help you install and use the software effectively.

The **OpenOffice.org community** invites you to participate and contribute. Learn more here: [Introduction to OpenOffice.org](http://www.openoffice.org/about_us/introduction.html).

---

## Is OpenOffice.org Free? 🆓

Yes! OpenOffice.org is **completely free** for all users, including individuals, businesses, educational institutions, and governments. 

For full license details, visit: [OpenOffice.org License](http://www.openoffice.org/license.html).

---

## Installation Guide 🚀

### **System Requirements** 📌
- **Windows:** 98, ME, NT (SP6+), 2000, XP
- **Processor:** Pentium-compatible PC
- **Memory:** 64 MB RAM
- **Disk Space:** 250 MB (300 MB for CJK version); 500 MB required after installation
- **Display:** 800x600 resolution with 256+ colors

### **Installation Steps** ✅
1. **Close all running programs** before starting.
2. **Ensure sufficient disk space** for installation.
3. **Run the installer** and follow the on-screen instructions.
4. **For Windows 98 users:** If Java installation prompts a restart, ignore or restart and rerun the OpenOffice.org installation.

---

## Troubleshooting & Known Issues ⚠️

### **Startup Problems**
- **Graphics issues?** Update your graphics card drivers or use default OS drivers.
- **3D display issues?** Disable OpenGL under:
  - `Tools → Options → OpenOffice.org → View → 3D View`

### **Compatibility Issues**
- **Running older OpenOffice versions?** You can install OpenOffice.org 2.4 alongside them. If uninstalling an older version, rerun the OpenOffice.org installer and select 'Repair'.
- **Copy-paste issues?** Between OpenOffice.org 1.x and 2.4, use `Edit → Paste Special` and select a compatible format.

### **Touchpad Scrolling (ALPS/Synaptics)**
Fix for scrolling issues:
1. Open `C:\Program Files\Synaptics\SynTP\SynTPEnh.ini`
2. Add:
   ```ini
   [OpenOffice.org]
   FC = "SALFRAME"
   SF = 0x10000000
   SF |= 0x00004000
   ```
3. Restart your computer.

### **Email Integration Issues**
If OpenOffice crashes when sending documents via email, check for Windows MAPI issues. Visit the [Microsoft Knowledge Base](http://www.microsoft.com) and search for **"mapi dll"**.

---

## Getting Help & Support 💡

- **FAQs:** [user-faq.openoffice.org](http://user-faq.openoffice.org/)
- **Mailing Lists:** [OpenOffice.org Mailing Lists](http://www.openoffice.org/mail_list.html)
- **Bug Reports:** Report issues via [IssueZilla](https://www.openoffice.org/qa/issue_handling/project_issues.html)
- **Community Forum:** Engage with users and developers at [OpenOffice.org Community](http://www.openoffice.org)

---

## How to Contribute 🤝

Even if you're not a developer, you can help!

- **Join the Community:** [Get Involved](http://www.openoffice.org)
- **Subscribe to Mailing Lists:**
  - 📢 Announcements: `announce@openoffice.org`
  - 💬 Discussions: `discuss@openoffice.org`
  - 📈 Marketing: `dev@marketing.openoffice.org`
  - 🛠 Development: `dev@openoffice.org`
- **Find a Project:** [OpenOffice.org Projects](http://projects.openoffice.org/index.html)

---

## License & Credits 📜

Portions of this software are:
- **Copyright 1998-1999 James Clark**
- **Copyright 1996-1998 Netscape Communications Corporation**

For full licensing details, visit: [OpenOffice.org License](http://www.openoffice.org/license.html)

---

<p align="center">
    We hope you enjoy working with OpenOffice.org 2.4!
    <br>
    <b>🚀 The OpenOffice.org Community 🚀</b>
</p>
