# Project Three: Insider Threat Technical Brief
**CYB-200 | Cybersecurity Foundations | Grade: A**

## Scenario Summary
A government agency employee working on classified U.S. Army contracts observes a trusted colleague (Jan) using a personal Android tablet to photograph classified project schematics. Jan's recent unexplained change in financial status (expensive clothes and jewelry despite known financial struggles) raises suspicion. Investigation confirms the photos were uploaded to personal cloud storage.

---

## I. Introduction — Threat Actor Characterization

| Attribute | Detail |
|---|---|
| **Threat Actor Type** | Malicious Insider |
| **Access Level** | Legitimate — cleared employee with authorized access |
| **Motivation** | Financial gain (evidenced by sudden change in lifestyle) |
| **Method** | Unauthorized personal device use to exfiltrate classified imagery |
| **Exfiltration Channel** | Personal cloud storage |

Insider threats are uniquely dangerous because the actor has pre-established trust and legitimate access. Detection relies heavily on behavioral signals rather than perimeter defenses.

---

## II. Analysis

### A. Detection Methods

**User and Entity Behavior Analytics (UEBA):**
UEBA systems establish behavioral baselines and flag anomalies — such as unusual file access patterns, off-hours activity, or unauthorized device connections. Jan's behavior (accessing materials outside her scope, using a personal device) should have triggered automated alerts.

**Physical and Policy Controls:**
Visible posted policies (no personal devices, no IoT) existed but lacked technical enforcement. Detection gap: no mechanism prevented device use — only signage.

**Behavioral Indicators:**
- Sudden unexplained lifestyle changes (financial motivation indicator)
- Accessing information outside normal work scope
- Defensiveness when questioned about device usage

### B. Response Actions Taken
1. Employee confrontation and report to supervisor
2. Formal investigation initiated
3. Digital forensic review of cloud storage activity
4. Discovery and documentation of exfiltrated imagery

### C. Prevention Recommendations
- **Technical:** Deploy device management controls that block unauthorized personal device connectivity; use DLP (Data Loss Prevention) tools to monitor and block unauthorized data transfers
- **Physical:** Access-controlled zones with device check-in/check-out at entry
- **Policy:** Regular insider threat awareness training and anonymous reporting channels
- **Cultural:** Foster a security-aware workplace where reporting concerns is normalized and protected

---

## III. Key Takeaways
This scenario illustrates that technical controls alone are not sufficient — human observation, behavioral awareness training, and a culture that encourages reporting are equally critical layers of defense against insider threats.

---

## Skills Demonstrated
`Insider Threat Analysis` `Threat Actor Characterization` `UEBA` `Digital Forensics Concepts` `Data Loss Prevention (DLP)` `Incident Response` `Behavioral Security Analysis` `Government/Classified Environment Security`
