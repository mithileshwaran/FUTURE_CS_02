# 🛡️ SOC Task 2 – Security Alert Monitoring & Incident Response

**Intern Name:** Mithileshwaran  
**Internship Domain:** Cyber Security  
**Task Title:** Security Alert Monitoring & Incident Response  
**Tool Used:** Splunk Cloud Free Trial  
**Date:** July 2025  

---

## 📄 Objective

To simulate real-world Security Operations Center (SOC) activities by:
- Monitoring and analyzing system logs using a SIEM (Splunk)
- Identifying potential threats such as malware, brute-force login attempts, and network scans
- Executing SPL queries to investigate incidents
- Preparing an incident response report with severity-based classification

---

## 🧰 Tools Used

- 🔍 **Splunk Cloud Free Trial** – SIEM platform for log analysis  
- 📄 **Sample Log File** – Contains system and network events  
- 📝 **Google Docs / Word** – For incident documentation  

---

## 🧪 Analysis Performed

The following SPL (Search Processing Language) commands were used to perform log analysis:

- `index=main`  
  → Showed all logs ingested into Splunk

- `index=main malware OR trojan`  
  → Detected malware-related events

- `index=main "Failed password"`  
  → Investigated brute-force login attempts

- `index=main host="si-i-04b7fc88c35bfb928.prd-p-lb42n.splunkcloud.com"`  
  → Analyzed activity of a specific host with high log volume

- `index=main port OR scan OR connection`  
  → Identified port scanning or suspicious network connections

Each query was used to isolate and identify abnormal or suspicious behavior from the provided simulated logs.

---

## 🧠 Key Learnings

- Used a **SIEM tool (Splunk)** for monitoring and alert detection  
- Wrote **basic SPL queries** to filter and investigate log data  
- Detected **malware**, **brute-force attacks**, and **port scans**  
- Created a **structured incident response report**  

This task reflects the foundational work of real-world SOC teams in monitoring and responding to live security incidents.

---

## 📁 Files Included

- `Incident_Report.pdf` – Final incident response documentation  
- `Malware_Troject_alert.png` – Malware detection log  
- `Failed_Login_Attempts_Splunk.png` – Brute-force login screenshot  
- `High_Host_Activity_Splunk.png` – Host activity spike  
- `Port_Scan_Activity_Splunk.png` – Detected port scan activity  

---

Thanks to **Future Interns** for the opportunity to learn and apply hands-on SOC skills.
