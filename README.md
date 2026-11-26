# UI Tools Library

[![Downloads](https://img.shields.io/github/downloads/aimms/ui-tools-library/total?style=for-the-badge&logo=github&labelColor=000081&color=1847c9)](https://github.com/aimms/ui-tools-library/releases)
![AIMMS Version](https://img.shields.io/badge/AIMMS-26.8-white?style=for-the-badge&labelColor=009B00&color=00D400)
![WebUI Version](https://img.shields.io/badge/WebUI-26.10-white?style=for-the-badge&labelColor=009B00&color=00D400)

This repository contains an AIMMS toolkit: **UI Tools Library** (`libUITools`, prefix `uit`). It helps to convert WinUI applications to WebUI, with a progress procedure that works in both user interfaces and a notification manager.

## 🔧 What This Toolkit Solves

While you convert a WinUI application to WebUI, the WinUI version often has to keep working. `uit::pr_DialogProgress`
takes the same arguments as `DialogProgress`, and reports progress in WinUI or in the WebUI, depending on the flag
`uit::bp_useWebUI`. One call replaces the two versions you would otherwise maintain.

WinUI applications also often report findings with one message dialog per problem. `uit::pr_addNotification`
collects them in a list instead, and the library page **NotificationHandling** shows that list in the WebUI, where
the user can mark notifications as handled and open the related pages.

## 📖 How to Use This Toolkit

To get the most out of this toolkit, we highly recommend reading our detailed step-by-step
guide on the AIMMS How-To website:

👉 **[Read the Full Article: UI Tools Library](https://how-to.aimms.com/Articles/717/717-ui-tools-library.html)**

### Prerequisites
- **AIMMS**: You will need AIMMS installed to run the model. [Download the Free Academic Edition here](https://www.aimms.com/support/licensing/).
- **A project to add it to:** this toolkit is a library, meant to be imported into an application of your own.
- No cloud account or extra license is required.

## 🚀 Getting Started

1. **Download the Release:** Go to the [Releases](https://github.com/aimms/ui-tools-library/releases) page and download the `.zip` file from the latest version.
2. **Add the Library:** unpack the zip into your own project folder, and use **File > Library Manager > Add Library from Disk**.
3. **Use it:** replace `DialogProgress(` by `uit::pr_DialogProgress(`, and report findings with `uit::pr_addNotification`.

## 🤝 Support & Feedback

This toolkit is maintained by the **AIMMS User Support Team**.
- Found an issue? [Open an issue](https://github.com/aimms/ui-tools-library/issues).
- Questions? Reach out via the [AIMMS Community](https://community.aimms.com).

---
*Maintained by the AIMMS User Support Team. We optimize the way you build optimization.*
