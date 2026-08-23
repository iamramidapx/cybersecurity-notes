# 06. Sound the Alarm: Detection and Response
> Course focus: Understand the incident response lifecycle and practice using tools to detect and respond to cybersecurity incidents.
Preparation: the planning and training process — the closest thing to hands-on SOC work in the Google Cybersecurity Certificate.

---

## 1. The 5 W's of Incident Investigation

Capture the 5 W's of an incident:

- **Who** caused the incident?
- **What** happened?
- **When** did the incident occur?
- **Where** did the incident happen?
- **Why** did the incident happen?

*("Which type" of incident is typically folded into "What.")*

---

## 4. CSIRT & SOC

Incident response is a team effort. Two structures organize that work:

- **CSIRT** (Computer Security Incident Response Team)
- **SOC** (Security Operations Center)

*(Follow-up reading covers the specific roles/responsibilities within each — worth a dedicated notes section once completed.)*

---

## 5. Incident Handler's Journal — Template

Reusable template for logging findings during labs/activities:

```
Date:
Entry #:

Description:
  Brief summary of the entry.

Tool(s) used:
  - 

5 W's:
  Who caused the incident?
  What happened?
  When did the incident occur?
  Where did the incident happen?
  Why did the incident happen?

Additional notes:
  
```

---

## 6. Knowledge Check — Answers & Rationale

| # | Question Topic | Correct Answer | Rationale |
|---|---|---|---|
| 1 | Phases *after* Preparation | Detection and Analysis / Containment, Eradication, and Recovery / Post-Incident Activity | The 4 NIST phases: Preparation → Detection & Analysis → Containment, Eradication & Recovery → Post-Incident Activity |
| 2 | Nature of the lifecycle | Cyclical | Response feeds lessons back into preparation for the next incident |
| 3 | Occurrence with no policy violation | Event | An incident is an event that crosses into policy violation / threat |
| 4 | Elements of the 5 W's tested | Who / When / Where the incident took place | "Which type" isn't a separate W — it's covered under "What" |

---

## Key Takeaway

This course is where the program gets closest to real SOC work — SIEM tooling, log/packet analysis, and a repeatable IR framework (NIST 800-61) that shows up in almost every real-world security job description. Worth the most detailed notes of the whole certificate.
