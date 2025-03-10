<div align="center">

# LAPORAN RESMI SISTEM OPERASI
### Minggu ke-3

---

![Image](https://github.com/user-attachments/assets/3ad88b6e-7159-44a2-a004-c909b974a88c)

#### Dosen Pengampu :
**Dr. Ferry Astika Saputra ST, M.Sc.**

#### Disusun Oleh : 
**Bagus Insan Pradana** D3 IT A **(3214521007)**

> PROGRAM STUDI D3 TEKNIK INFORMATIKA PSDKU LAMONGAN
> DEPARTEMEN TEKNIK INFORMATIKA DAN KOMPUTER 
> POLITEKNIK ELEKTRONIKA NEGERI SURABAYA 
> 2025

---

</div>

---

# 📌How Operating Systems Works?

**📖Tujuan :** 
Mahasiswa diharapkan dapat memahami lebih tentang bagaimana cara sebuah OS berjalan dalam sebuah "Operating Systems". Terutama pada OS yang berbasis **open-source**, seperti: **Linux**.

---

# 🖊Penugasan:

1. Membuat repository di GitHub untuk media pengumpulan tugas.
2. Membuat flowchart untuk proses dari komputer dinyalakan, bootstrap, dst hingga komputer bisa digunakan.

---

# 🤔Overview 
When a computer is powered on, it undergoes several steps to initialize hardware, load the operating system, and become ready for use. Below is a breakdown of the boot process.

---

## ⭐Flowchart :

<div align="center">
  
![Image](https://github.com/user-attachments/assets/47c3f6c5-730b-42f9-a035-bcdf9446fc5b)

</div>

---

## 🤓Explanation :

#### OS Boot Process Steps

| 🪜Step | 💬Description | ☁️Next Step |
|------|------------|-----------|
| **🏃‍♂️Start** | The computer is off. | Turning ON a computer |
| **🖥️Turning ON a computer** | User presses the power button. | Computer ON? |
| **💻Computer ON?** | If NO: Troubleshoot and try again. | If YES: PSU turns ON |
| **⚡PSU turns ON** | Power is supplied to all components. | Processor starts BIOS/EFI |
| **🔥Processor starts BIOS/EFI** | BIOS/UEFI initializes hardware and runs POST. | Loading MBR to RAM |
| **🫙Loading MBR to RAM** | The Master Boot Record (MBR) is loaded into RAM. | Running the Bootloader |
| **🚗Running the Bootloader** | Bootloader finds and loads the OS kernel. | Load OS Kernel |
| **🔃Load OS Kernel** | The OS kernel is loaded into memory. | Initialize Kernel data structures & hardware |
| **🌎Initialize Kernel data structures & hardware** | The kernel sets up memory, CPU, and system processes. | Load Driver Hardware |
| **🔃Load Driver Hardware** | The OS loads drivers for system components. | Starts the OS |
| **🔥Starts the OS** | Core OS services and processes begin. | Load User Data (GUI/TERMINAL) |
| **🔃Load User Data (GUI/TERMINAL)** | The user interface is prepared. | Shows User Interface |
| **✨Shows User Interface** | The system is ready for use. | STOP |

---

## 📖Refrences
- Unix and Linux system administration handbook by Evi Nemeth Garth Snyder Trent R. Hein Ben Whaley Dan Mackin
- https://www.baeldung.com/cs/computer-boot-process
- https://automateinfra.com/2021/11/09/windows-boot-process-step-by-step/
- https://youtu.be/7D4qiFIosWk

---

## 🔍Conclusion
This table represents the computer boot process flowchart in a structured manner. Understanding these steps helps in troubleshooting boot issues and optimizing system performance.
