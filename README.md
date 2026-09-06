# HealthConnect Clinic - Data Analytics Project

## Project Overview
Analyzing appointment no-show patterns to help HealthConnect Clinic reduce missed appointments and improve patient engagement. This project aims to identify key drivers of no-show behavior and provide actionable insights to the clinic for targeted interventions.

## Project Status
- ✅ Week 4: Project Kickoff & Problem Understanding
- ✅ Week 5: Data Preparation & Exploratory Analysis
- 🔄 Week 6: Analysis & Solution Design
- ⏳ Week 7: Testing & Refinement
- ⏳ Week 8: Final Presentation

## Dataset
- **Source**: HealthConnect_Appointment_Data.csv
- **Records**: 5,000 appointments
- **Variables**: 18 fields including patient demographics, appointment details, and outcomes

## Key Business Questions
1. What demographic factors are most strongly associated with higher no-show rates?
2. Are there specific days of the week, times, or appointment types with higher no-show rates?
3. How does patient history affect their likelihood of missing a future appointment?
4. Which months have high bookings but low turn-up?
5. How does reminder and logistic information affect no-show rates?

## Key Findings
1. 48.46% of appointments result in no-shows
2. SMS is the most effective reminder channel with 48.0%
3. Patients 30-40km away with reminders have 77% no-show rate
4. Females 45-54 and Males 18-24 have highest no-show rates
5. Sundays and Fridays, Evening appointments have higher no-show rates
6. Patients with history of no-shows are significantly more likely to no-show again

## Business Recommendations
1. Shift communication budget from email to SMS reminders, especially for high-risk patient segments.  
2. Offer virtual follow-ups to reduce attendance barriers
3. Secondary SMS or call for Sunday/Friday and evening appointments
4. Flag high-risk patients (history of no-shows, 30-40km distance) for morning-of check-ins
5. Prioritize SMS reminders as the primary intervention channel to reduce this rate because it has proven to be the most effective channel
   
## Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn
- **Power BI**: Interactive Executive Dashboard
  
## Proposed KPIs
Total Bookings | Count of all appointments | 5,000
Total show | Count of all appointment attended | 2,314
Total no show | Count of all missed appointments | 2,423
No-Show Rate | (No-Shows / Total Bookings) × 100 | 48.46%
Show Rate | (Attended / Total Bookings) × 100 | 46.28%
Previous No-Show | Count of patients with a history of previous no-shows | 1,232

## Cross Track Collaboration
**Data Science**
1. Shared EDA findings and KPIs
2. Cross validated core numbers(5000, 2314,2423)
3. Aligned on feature definitions including previous_noshow_rate, reminder_and_channel, and interaction features (distance × reminder, age/gender patterns)

**Project Management**
1. Provided insights on 30-40km group analysis, booking lead time patterns
2. KPI recommendations for post-intervention tracking
3. Shared project progress

## Author
**Poloko Dignity Ranna**
LinkedIn: www.linkedin.com/in/poloko-dignity-ranna
Email: rannadignity@gmail.com
