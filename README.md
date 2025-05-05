# Insider Data Breach: A Multi-Layered Forensic Investigation

## 🔍 Overview
This project investigates an insider attack at HaajiZ Corp involving data exfiltration through PowerShell scripting, fileless malware, and keylogger deployment. The investigation spans storage, memory, and network forensics, and concludes with an in-depth forensic report and security recommendations.

---

## 🎯 Objectives
- **Collect & Secure Evidence**: Acquire disk images, RAM dumps, and network logs.
- **Perform Forensic Analysis**:
  - **Memory Forensics**: Detect malware, injected code, and stolen credentials.
  - **Storage Forensics**: Identify deleted files, malware traces, and USB activities.
  - **Network Forensics**: Trace data exfiltration paths and C2 activity.
- **Keylogger Analysis**: Determine if and how credentials were stolen.
- **Reporting**: Reconstruct attack timeline and deliver actionable security recommendations.

---

## 🧰 Tools & Technologies

| Category              | Tools Used                    |
|-----------------------|-------------------------------|
| Disk Forensics        | Autopsy, Sleuth Kit           |
| Memory Forensics      | Volatility Framework          |
| Network Forensics     | Wireshark, Zeek               |
| Evidence Imaging      | FTK Imager, dd                |
| Keylogger Detection   | Manual analysis + Volatility  |

---

## 🧪 Methodology

### Phase 1: Evidence Collection
- Clone hard drives, extract memory dumps, and collect PCAP network logs.

### Phase 2: Deep Analysis
- **Autopsy/Sleuth Kit**: Recover deleted files, analyze USB usage.
- **Volatility**: Identify injected processes, credential harvesting, keylogger traces.
- **Wireshark/Zeek**: Analyze data exfiltration (e.g., DNS tunneling, cloud uploads).

### Phase 3: Reporting & Recommendations
- Document evidence and timeline.
- Recommend controls (USB restrictions, PowerShell monitoring, IDS, etc.).
- Deliver final forensic report and presentation.

---

## ✅ Expected Outcomes
- Proven insider threat activity through digital artifacts.
- Evidence of malware and keylogger deployment.
- Traced exfiltration vectors (DNS tunneling, cloud services).
- A comprehensive report with Indicators of Compromise (IOCs) and recommendations.

---

