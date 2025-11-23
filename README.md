Lean Six Sigma Green Belt Project Report                       Hospital Wait Time Reduction - ABC Hospital

1. Project Charter
Problem Statement:
ABC Hospital in California is facing excessive patient wait times due to inefficient scheduling of appointments. Current average wait times surpass the industry benchmark of 30 minutes, resulting in patient dissatisfaction, underutilization of resources, and financial losses.
Objective:
To systematically analyze and improve the appointment scheduling process using Lean Six Sigma methodology in order to reduce patient wait times, optimize resource utilization, and improve patient satisfaction and hospital revenue.
Business Case:
Reducing patient wait times to the industry benchmark of 30 minutes will enhance patient experience, improve resource utilization, and generate additional revenue by reducing appointment no-shows and cancellations.
Scope:
•	In-scope: Appointment scheduling process, front-desk operations, physician availability, examination room allocation, and patient flow management.
•	Out-of-scope: Emergency services, surgical procedures, inpatient admissions.
Team:
•	Project Sponsor: Hospital Director
•	Project Leader (Green Belt): Scheduling Manager
•	Team Members: Front desk staff, IT system administrator, nursing supervisor, physician representatives
Timeline: 4 months
________________________________________
2. Voice of Business (VOB) vs. Voice of Customer (VOC)
VOB (Business Needs)	VOC (Customer Needs)
Optimize scheduling to increase efficiency	Reduce waiting time
Reduce missed appointments and cancellations	Easy and reliable appointment booking
Maximize room and staff utilization	On-time consultation with doctors
Improve financial performance	Better hospital experience and trust
________________________________________
3. SIPOC Diagram
Suppliers → Inputs → Process → Outputs → Customers
•	Suppliers: Patients, Front desk staff, Doctors, IT system, Insurance providers
•	Inputs: Appointment requests, Doctor availability, Patient data, Scheduling software, Examination rooms
•	Process:
1.	Patient requests appointment
2.	Appointment scheduled in system
3.	Confirmation sent to patient
4.	Patient arrives and checks in
5.	Patient waits until consultation begins
•	Outputs: Scheduled appointments, Patient wait time, Consultation start time
•	Customers: Patients, Doctors, Hospital administration
________________________________________
4. RACI Matrix
Task	Front Desk Staff	Scheduling Manager	Doctors	IT Admin	Director
Collect appointment requests	R	A	C	I	I
Manage scheduling system	R	A	C	R	I
Confirm appointments	R	A	I	I	I
Optimize resource allocation	C	A	C	C	I
Project oversight	I	R	I	I	A
(R = Responsible, A = Accountable, C = Consulted, I = Informed)
________________________________________
5. Project Communication Plan
Audience	Frequency	Mode	Content
Project Team	Weekly	Meetings/Email	Progress updates, issues, next steps
Sponsor/Director	Bi-weekly	Reports/Meetings	Milestone updates, risks
Hospital Staff	Monthly	Newsletter	Process changes, improvements
Patients	As needed	SMS/Email	Appointment updates, new process details
________________________________________
6. Data Analysis 
Phase	Count	Mean	Median	Mode	Std Dev	Variance	Range	Max
Before	25	43.40	45.00	45.0	10.07	101.50	30.00	60.0
After	27	30.59	30.00	30	2.52	6.33	9.00	35

•	The hospital intervention clearly reduced average waiting time (from 43.4 → 30.6 minutes).
•	The distribution became tighter and more predictable (Std Dev dropped from 10.07 → 2.52).
•	Both the typical (median, mode) and worst-case (max) waiting times improved.________________________________________
7. DPMO (Defects per Million Opportunities)
    Before Project: 18 defects out of 25 (720000 DPMO)
    After Project: 13 defects out of 27 (481481 DPMO)
•	The project reduced DPMO from 720k → 481k, which means fewer patients are experiencing unacceptable wait times.
•	Still, nearly half of patients are above the 30-minute benchmark — so there’s improvement, but further work is needed.
________________________________________
8. Process Capability & Stability Check
Before Project: Cp = 0.50, Cpk = -0.44
•	Cp = 0.50 → process variation is too wide compared to spec limits.
•	Cpk = -0.44 → process mean is far above USL (process not centered).
 Highly incapable process, average well above USL.
After Project: Cp = 1.99, Cpk = -0.08
•	Cp: 1.99 → Process is potentially capable (tight variation).
•	Cpk: –0.08 → Mean is still slightly above USL (patients still exceeding 30 min, but much closer).
Variation is controlled and process is nearly capable, but the mean is still just beyond the USL.

•	Control charts  to check stability
 

 

•	Before project: wait times might have been unstable (wide variation).
•	After project: control chart shows wait times are within limits and more consistent (stable).
This helps prove that the intervention actually worked and improved process stability.________________________________________
9. Possible Causes of Delay
•	Poor scheduling software (system limitations)
•	Inaccurate doctor availability updates
•	Overbooking of slots
•	Late patient arrivals
•	Lack of coordination between departments
•	Examination room underutilization
________________________________________
10. Fishbone Diagram (Root Cause Analysis)
Categories: People, Process, Technology, Environment, Policies, Patients


- People: Staff not trained, doctors running late
- Process: Overbooking, poor scheduling practices
- Technology: Outdated scheduling system, no automation
- Environment: Limited rooms, peak-time congestion
- Policies: No-shows not penalized, lack of reminders
- Patients: Late arrivals, incomplete information.

 
The analysis shows that scheduling issues are caused by a mix of human, process, technological, environmental, policy, and patient-related factors. Addressing these root causes with targeted improvements (e.g., automation, staff training, stricter no-show policies) can reduce delays and make scheduling more efficient.
________________________________________
11. Hypothesis Testing 
Set hypotheses:
•	Null hypothesis (H₀): There is no improvement in wait times after the project.
•	Alternative hypothesis (H₁): There is a significant improvement in wait times.
Run T-test: Compare the means of wait times before vs. after intervention.
T-test statistic = 6.18, p-value = 0.000002

The T-test result (t = 6.18, p = 0.000002) shows that the difference in wait times before and after the project is highly significant. Since p < 0.05, we reject the null hypothesis and conclude that the intervention led to a real improvement in reducing wait times.


________________________________________


12. Brainstorm Solutions
•	Upgrade scheduling system with predictive analytics
•	Implement reminder systems (SMS, email)
•	Adjust staffing based on peak times
•	Standardize consultation durations
•	Provide real-time doctor availability to front desk
________________________________________

13. Pilot Run & Results Comparison
•	Before: Avg wait = 43.4 mins, 70% dissatisfaction rate
•	After pilot: Avg wait = 30.59 mins, 15% improvement in satisfaction


________________________________________

14. Control Plan
 

________________________________________
Conclusion
The Lean Six Sigma Green Belt project at ABC Hospital successfully demonstrated that systematic process improvement can significantly reduce patient wait times. By addressing inefficiencies in appointment scheduling, improving staff coordination, and piloting new solutions, the hospital reduced average wait times from 43.4 minutes to 30.6 minutes. This brought performance much closer to the industry benchmark of 30 minutes while also enhancing process stability and predictability. Although further refinement is needed to consistently meet or exceed the benchmark, the project has already improved patient satisfaction, optimized resource utilization, and reduced financial losses from cancellations and no-shows. The outcomes validate the importance of data-driven decision-making, continuous improvement, and cross-functional collaboration in healthcare operations.
