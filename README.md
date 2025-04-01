# OpenOffice.org 2.4 README

For the latest updates to this README file, visit: [OpenOffice.org Readme](http://www.openoffice.org/welcome/readme.html)

---

## Welcome

Thank you for using OpenOffice.org 2.4! This document contains essential information about the software. Please read it carefully before starting.

The OpenOffice.org community, responsible for developing this product, invites you to become a member. As a new user, you can find valuable information here: [Introduction to OpenOffice.org](http://www.openoffice.org/about_us/introduction.html).

Additionally, you can learn how to contribute to the OpenOffice.org project below.

---

## Is OpenOffice.org Free for Everyone?

Yes! OpenOffice.org is completely free for all users, including government, businesses, educational institutions, and individuals. For full license details, visit: [OpenOffice.org License](http://www.openoffice.org/license.html).

---

## Installation Notes

### System Requirements:
- Microsoft Windows 98, ME, NT (Service Pack 6 or later), 2000, or XP
- Pentium-compatible PC
- 64 MB RAM
- 250 MB of free disk space (300 MB for CJK version)
- 500 MB of disk space required after installation if deleting temporary installer files
- Minimum screen resolution of 800x600 with at least 256 colors

### Installation Tips:
- Ensure sufficient free memory in your system’s temporary directory.
- Verify that you have read, write, and execute permissions.
- Close all other programs before starting the installation.
- Administrator rights are required for installation.
- **Windows 98 Users:** If you install Java during setup, the installer may request a reboot. You can ignore this or restart and rerun the OpenOffice.org installation.

---

## Troubleshooting Startup Issues

### Common Problems:
1. **Program Hangs or Display Issues**: Often caused by outdated graphics card drivers. Try updating the driver or using the default driver provided by your operating system.
2. **3D Display Issues**: Disable "Use OpenGL" under `Tools → Options → OpenOffice.org → View → 3D View`.
3. **Installing Alongside Older Versions**:
   - You can install OpenOffice.org 2.4 alongside older versions.
   - If you later remove an older version, run the new version’s installer and select 'Repair' to ensure proper system registration.
4. **Copy-Paste Compatibility**:
   - Copy-pasting between OpenOffice.org 1.x and 2.4 may not work properly.
   - Use `Edit → Paste Special` and select a different format, or open the document directly in OpenOffice.org 2.4.

---

## Known Issues

### ALPS/Synaptics Touchpad Scrolling
Due to a Windows driver issue, OpenOffice.org documents may not scroll when using an ALPS/Synaptics touchpad. To enable scrolling:
1. Open `C:\Program Files\Synaptics\SynTP\SynTPEnh.ini`
2. Add the following lines:
   ```ini
   [OpenOffice.org]
   FC = "SALFRAME"
   SF = 0x10000000
   SF |= 0x00004000
   ```
3. Restart your computer.

### Ai Squared ZoomText Compatibility
To use **Ai Squared ZoomText** with OpenOffice.org 2.4, you must have version **7.11 or later**. Only versions downloaded after **June 12, 2002**, provide full functionality.

### Keyboard Shortcuts
Some keyboard shortcuts may not work as expected due to conflicts with your operating system. If a shortcut does not function as described in the OpenOffice.org help, check if it is reserved by your OS. You can:
- Modify system-defined shortcuts
- Change OpenOffice.org keyboard shortcuts via `Tools → Customize`

### Emailing Documents from OpenOffice.org
When using `File → Send → Document as Email` or `Document as PDF Attachment`, OpenOffice.org may crash due to issues with Windows MAPI (Messaging Application Programming Interface). For solutions, visit: [Microsoft Knowledge Base](http://www.microsoft.com) and search for **"mapi dll"**.

---

## Registration & User Survey

### Product Registration
Registration is **optional but encouraged**. It helps the OpenOffice.org community improve the software. Your data is protected under strict privacy policies.

If you did not register during installation, you can do so anytime here: [OpenOffice.org Registration](http://www.openoffice.org/welcome/registration-site.html).

### User Survey
We also invite you to participate in our user survey. Your feedback helps shape the next generation of OpenOffice.org. Privacy is strictly maintained.

---

## User Support

For help with OpenOffice.org 2.4:
- Check the [mailing list archives](http://www.openoffice.org/mail_list.html) for previously answered questions.
- Post your questions to `users@openoffice.org` (subscription required).
- Visit the [FAQ section](http://user-faq.openoffice.org/) for answers to common questions.

---

## Reporting Bugs & Issues

Help improve OpenOffice.org by reporting bugs! We use **IssueZilla**, our issue tracking system, to report, track, and resolve bugs. 
- Report bugs here: [OpenOffice.org IssueZilla](http://www.openoffice.org/issuezilla)

---

## How to Contribute

Your participation is invaluable! Even if you are not a developer, you can contribute in many ways:
- **Join the Community**: [Get Involved](http://www.openoffice.org)
- **Subscribe to Mailing Lists**:
  - News: `announce@openoffice.org` (light traffic)  
  - User Discussions: `discuss@openoffice.org` (high traffic)  
  - Marketing: `dev@marketing.openoffice.org` (moderate traffic)  
  - Developer List: `dev@openoffice.org` (moderate-heavy traffic)  
  Subscribe here: [Mailing Lists](http://www.openoffice.org/mail_list.html)

- **Join a Project**:
  - OpenOffice.org has many projects, from **localization and porting** to **documentation and marketing**.
  - Find a project: [OpenOffice.org Projects](http://projects.openoffice.org/index.html)
  - Help promote OpenOffice.org: [Marketing & Communications](http://marketing.openoffice.org/contacts.html)

---

## License & Credits

Portions of this software are:
- **Copyright 1998, 1999 James Clark**
- **Copyright 1996, 1998 Netscape Communications Corporation**

For full licensing details, see: [OpenOffice.org License](http://www.openoffice.org/license.html)

---

We hope you enjoy working with OpenOffice.org 2.4!

🚀 **The OpenOffice.org Community** 🚀
