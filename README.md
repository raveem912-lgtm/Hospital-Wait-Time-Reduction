# 📘 Lean Six Sigma Green Belt Project  
## Hospital Wait Time Reduction – ABC Hospital

## 1. Overview
This project applies Lean Six Sigma Green Belt methodology to reduce excessive patient wait times at ABC Hospital in California. The hospital’s appointment scheduling process resulted in an average wait time above the industry benchmark of 30 minutes, causing patient dissatisfaction, resource inefficiency, and financial loss.  
This repository documents the complete DMAIC cycle, statistical analysis, process capability, and improvement results.

---

## 2. Project Charter

### Problem Statement
ABC Hospital is experiencing high patient wait times due to inefficiencies in the appointment scheduling process. Current wait times exceed 30 minutes, leading to dissatisfaction, operational delays, and financial loss.

### Objective
To analyze and optimize the scheduling workflow using Lean Six Sigma tools to:
- Reduce wait times
- Improve resource utilization
- Increase satisfaction
- Reduce cancellations and no-shows
- Improve financial outcomes

### Business Case
Achieving the 30-minute benchmark will improve patient experience, optimize staffing and room utilization, and increase revenue by reducing no-shows and bottlenecks.

### Scope  
**In Scope:** Appointment scheduling, front desk operations, physician availability, exam room allocation, patient flow.  
**Out of Scope:** Emergency services, surgical procedures, inpatient admissions.

### Team  
- Sponsor: Hospital Director  
- Project Leader (Green Belt): Scheduling Manager  
- Team Members: Front desk staff, IT administrator, nursing supervisor, physicians  

### Timeline  
4 Months

---

## 3. Voice of Business (VOB) vs Voice of Customer (VOC)

| Voice of Business (VOB) | Voice of Customer (VOC) |
|-------------------------|-------------------------|
| Optimize scheduling efficiency | Reduce wait time |
| Reduce cancellations | Easy and reliable booking |
| Maximize resource use | On-time consultations |
| Improve financial performance | Better patient experience |

---

## 4. SIPOC Diagram

**Suppliers:** Patients, Front Desk Staff, Doctors, IT System, Insurance Providers  
**Inputs:** Appointment requests, doctor availability, patient data, scheduling software, exam rooms  

**Process Steps:**
1. Patient requests appointment  
2. Appointment scheduled  
3. Confirmation sent  
4. Patient checks in  
5. Consultation begins  

**Outputs:** Scheduled appointments, wait time, consultation start time  
**Customers:** Patients, Doctors, Hospital Administration

---

## 5. RACI Matrix

| Task | Front Desk | Scheduling Manager | Doctors | IT Admin | Director |
|------|------------|--------------------|---------|----------|----------|
| Collect appointment requests | R | A | C | I | I |
| Manage scheduling system | R | A | C | R | I |
| Confirm appointments | R | A | I | I | I |
| Optimize resource allocation | C | A | C | C | I |
| Project oversight | I | R | I | I | A |

---

## 6. Communication Plan

| Audience | Frequency | Method | Content |
|----------|-----------|--------|---------|
| Project Team | Weekly | Meetings/Email | Progress updates, issues |
| Sponsor | Bi-weekly | Reports/Meetings | Milestones, risks |
| Hospital Staff | Monthly | Newsletter | Process changes |
| Patients | As needed | SMS/Email | Appointment updates |

---

## 7. Data Analysis

### Summary Statistics

| Phase | Count | Mean | Median | Mode | Std Dev | Range | Max |
|-------|-------|-------|--------|------|---------|--------|------|
| Before | 25 | 43.40 | 45 | 45 | 10.07 | 30 | 60 |
| After | 27 | 30.59 | 30 | 30 | 2.52 | 9 | 35 |

**Key Findings:**
- Average wait time improved from 43.4 to 30.6 minutes.
- Variation decreased significantly (Std Dev from 10.07 to 2.52).
- Worst-case wait times improved.

---

## 8. Defects per Million Opportunities (DPMO)

- Before: 720,000 DPMO (18 defects out of 25)
- After: 481,481 DPMO (13 defects out of 27)

While improved, nearly half of patients still exceeded the 30-minute benchmark.

---

## 9. Process Capability Analysis

### Before Intervention
- Cp = 0.50 (high variation)
- Cpk = -0.44 (mean above USL)

### After Intervention
- Cp = 1.99 (process capable)
- Cpk = -0.08 (mean slightly above USL)

Variation is under control; centering still needs improvement.

---

## 10. Root Cause Analysis

Common contributing factors included:
- Outdated scheduling software
- Inaccurate doctor availability updates
- Overbooking of slots
- Late patient arrivals
- Room underutilization
- Inefficient coordination
- Lack of standardized policies
- Limited automation

Root cause categories: People, Process, Technology, Environment, Policies, Patients

---

## 11. Hypothesis Testing

**H0:** No improvement in wait times  
**H1:** Significant improvement in wait times  

T-test results:  
- t = 6.18  
- p = 0.000002  

Since p < 0.05, we reject the null hypothesis.  
The improvement is statistically significant.

---

## 12. Improvement Solutions

- Upgrade scheduling system with predictive analytics  
- Implement SMS/email reminders  
- Adjust staffing for peak times  
- Standardize consultation durations  
- Provide real-time doctor availability to front desk  

---

## 13. Pilot Run Results

| Metric | Before | After Pilot |
|--------|---------|-------------|
| Average Wait Time | 43.4 mins | 30.59 mins |
| Satisfaction | Baseline | +15% improvement |

---

## 14. Control Plan

- Weekly monitoring of wait-time metrics  
- Automated reminders and scheduling rules  
- Quarterly audits  
- Updated standard operating procedures  
- Ongoing staff training  

---

## 15. Conclusion

The Lean Six Sigma project at ABC Hospital significantly reduced average wait times from 43.4 minutes to 30.6 minutes. The intervention improved process stability, patient satisfaction, and operational efficiency.  
While the process now approaches the 30-minute benchmark, additional centering improvements are recommended to fully meet the target and sustain long-term performance.

---
