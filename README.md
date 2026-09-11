# System Software Integrity Auditor

A standalone Windows desktop utility developed by **BIM Sphere Consulting** to inspect system registry hives, verify installed application metadata, flag unverified software, and export structured compliance audit reports.

---

### Features

* **Registry-Based Detection:** Scans both `HKLM` and `HKCU` uninstall paths for installed 32-bit and 64-bit software.
* **Integrity Auditing:** Highlights unverified or suspicious software entries lacking official publisher verification.
* **Multi-Format Export:** Generates standardized audit logs in CSV, HTML, JSON, XML, and TSV formats.
* **Zero Installation Required:** Distributed as a self-contained, standalone Windows executable.

---

### System Requirements

* **OS:** Windows 10 / Windows 11 (64-bit)
* **Architecture:** x86_64
* **Dependencies:** None (all runtimes bundled)

---

### Download & Installation

1. Navigate to the [Releases](https://github.com/BIM-Sphere-Consulting/software-integrity-auditor/releases) tab on the right side of this page.
2. Download the latest `SoftwareAuditor_Protected.exe`.
3. Run the executable directly. No administrative installer or external runtime is required.
> **Note on Windows SmartScreen:**  
> Because this is a newly released binary, Microsoft SmartScreen or Edge may show an *"Unknown app"* or *"Isn't commonly downloaded"* prompt.  
> * In Edge: Click **`...` > Keep > Show More > Keep anyway**.  
> * In Windows: Click **More info > Run anyway**.  
> The executable has been submitted to Microsoft Security Intelligence for false-positive validation and contains no malicious code.

---

### Security & Whitelisting

This binary is compiled to native machine code and validated with Microsoft Security Intelligence developer pipelines to ensure safe operation across enterprise workstations.

---

### Contact & Support

* **Publisher:** BIM Sphere Consulting
* **Lead Developer:** Shanmuganand
* **Email:** bimsphereconsulting@outlook.com
