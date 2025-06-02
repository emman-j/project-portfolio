# project-portfolio
A collection of software projects I am actively developing and improving. These projects may be in various stages of completion and refinement.

---


# 📂 Project Directory

## 1. MMS (Meter Management System) (Private)  
**Description:**  
A Windows desktop application built with WinForms, designed for configuring and interacting with DLMS/COSEM-compliant smart meters via serial communication. 
Tailored for engineers and utility professionals in the energy metering sector.

**Highlights:**  
- **DLMS/COSEM protocol support** over raw serial communication  
- **Dynamic UI** leveraging inheritance and abstractions for flexible object handling, with UserControls enabling dynamic interface generation  
- **SQLite integration** for local user management and data logging  
- **Flexible data export**: Excel (via NPOI), CSV, and TXT  
- **JSON/XML-based configuration** with plugin-ready architecture for extensibility

**Features**
- **Device Management:** Discover, add, and configure DLMS/COSEM devices.
- **Object Browsing:** Visualize and edit DLMS objects such as Data, Register, Clock, Profile Generic, Security Setup, and more.
- **Data Reading/Writing:** Read and write values to device attributes with access control.
- **Action Scheduling:** Manage and execute scheduled actions on devices.
- **Security Management:** Configure security settings and certificates.
- **User Management:** Role-based access and account management.
- **Export/Import:** Export data and configurations for reporting or backup.
- **Extensible UI:** Modular user controls for each object type, supporting easy extension.



## 2. [Assembly Merger](https://github.com/emman-j/assembly-merger)  

![AssemblyMerger](https://raw.githubusercontent.com/emman-j/assembly-merger/refs/heads/main/Images/MainUI.png)

**Description:** 
A Windows desktop application built with WinForms in C#, designed to merge multiple .NET assemblies into a single executable.
Simplifies deployment by consolidating dependencies and resources. 

**Highlights:**  
- **Graphical User Interface**: Intuitive design for easy navigation and operation.
- **Customizable Output**: Specify output paths and filenames effortlessly.
- **Auto-Detection of ILMerge Executable**: Automatically resolves and uses ILMerge.exe from the local application directory.
- **Default Output Directory**: Automatically sets to `ExecutableBaseDirectory\output` for organized storage.
- **Real-time Logging**: Monitor merge operations through an integrated console.
- **Error Handling**: Provides feedback on merge success or failure.  


## 3. [SQLServer-Exporter](https://github.com/emman-j/SQLServer-Exporter)  

![main](https://raw.githubusercontent.com/emman-j/SQLServer-Exporter/refs/heads/main/Images/main.png)

**Description:**  
A Windows desktop application developed in C# using WinForms, designed to facilitate the extraction and export of data from Microsoft SQL Server databases. This tool aims to streamline the process of exporting SQL Server data into various formats for reporting, analysis, or backup purposes.

**Highlights:**  
- Connects to Microsoft SQL Server instances to retrieve data  
- Exports data into multiple formats (e.g., CSV, Excel)  
- User-friendly interface for selecting databases and tables  
- Built with C# and WinForms for a native Windows experience  


## 4. [Window Capture (Workspace Management)](https://github.com/emman-j/window-capture) [WIP]

**Description:**
A lightweight Windows application (WinForms & WPF) designed for capturing window screenshots and managing multiple workspace snapshots. Mainly made for testing win32 native interupt.

**Highlights:**  
- Dual implementation: WinForms(WIP) and WPF(WIP)  
- Simple and intuitive UI for capturing specific windows  
- Workspace-style design with potential for future automation features  
- Built with .NET 6  


---

## 🛠️ Technologies Explored

- **Languages:** C#, Python, SQL,
- **Databases:** SQL Server, InfluxDB, SQLite
- **Frameworks:** .NET (WinForms, WPF), Flask, LiveCharts, etc.
- **Tools:** Git, SQLite, Web APIs, etc.

---

## 🔖 Notes

- This repository contains no source code — only links and previews.
- All project source code is maintained in their individual repositories (some may be private).
- Preview images are embedded using raw GitHub links from the respective repos.

---

## 📌 Related

- [Practice Projects](https://github.com/emman-j/practice-projects-collection) – A collection of software projects made for practice.
