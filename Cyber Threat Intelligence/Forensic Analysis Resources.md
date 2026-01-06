## Incident Response Linux Cheatsheet

- https://www.hackingarticles.in/incident-response-linux-cheatsheet/

# Digital Forensics Tools

Tools used for **digital forensics investigations**, forensic challenges,
file analysis, memory analysis, network forensics, and data recovery.

---

## Wireless & Network Forensics

- **Aircrack-ng** – Crack 802.11 WEP and WPA-PSK keys.  
  ```bash
  apt-get install aircrack-ng

* **NetworkMiner** – Network forensic analysis tool for PCAP inspection.
* **Wireshark** – Analyze network traffic captured in PCAP or PCAPNG files.

---

## Audio, Image & Media Forensics

* **Audacity** – Analyze and inspect audio files (MP3, M4A, WAV, etc.).

  ```bash
  apt-get install audacity
  ```
* **ExifTool** – Read, write, and edit file metadata.
* **Pngcheck** – Verify PNG file integrity and display chunk-level information.

  ```bash
  apt-get install pngcheck
  ```

---

## File System & Data Recovery

* **Extundelete** – Recover lost data from mountable disk images.
* **Foremost** – Recover specific file types using file headers.

  ```bash
  apt-get install foremost
  ```
* **fsck.ext4** – Repair corrupted EXT4 file systems.

---

## Memory & System Forensics

* **Volatility** – Analyze and investigate memory dumps.
* **Bkhive & Samdump2** – Dump and extract credentials from Windows SYSTEM and SAM files.

  ```bash
  apt-get install samdump2 bkhive
  ```

---

## Malware & Executable Analysis

* **CFF Explorer** – Portable Executable (PE) editor.
* **Malzilla** – Malware hunting and analysis tool.
* **ResourcesExtract** – Extract embedded resources from executable files.

---

## Document & Steganography Analysis

* **PDF Streams Inflater** – Extract and analyze compressed ZLIB streams from PDF files.
* **Snow** – Whitespace steganography tool for hiding and extracting data.
