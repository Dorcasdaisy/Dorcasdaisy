# 🔍 Splunk Log Analysis

## 📌 Objective
To detect suspicious login activity using Splunk.

---

## 🛠 Tools Used
- Splunk

---

## 🧪 Scenario
A system showed multiple failed login attempts within a short time period. This could indicate a brute-force attack.

---

## 🔎 Steps Taken
1. Imported log data into Splunk
2. Searched for failed login attempts:
   index=main "failed password"
3. Identified multiple attempts from a single IP
4. Analyzed timestamps and patterns

---

## 🚨 Findings
- Repeated failed login attempts detected
- Single IP address involved
- Pattern suggests brute-force attack

---

## ✅ Conclusion
This activity indicates a possible unauthorized access attempt. Recommended blocking the IP and enabling account lockout policies.

---

## 📸 Screenshots
