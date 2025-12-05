# Panic Attacks – Power BI Report

## Dataset

The report uses a **panic attacks** dataset.  
Each row represents one patient and includes:

- Demographic data (age, gender, age group)  
- Trigger of panic attacks (e.g. caffeine, phobia, PTSD, social anxiety, unknown)  
- Panic attack details (frequency, duration, panic score, symptoms, heart rate)  
- Lifestyle factors (sleep hours, drinks per week, smoking, exercise, etc.)  
- Medical background (anxiety, PTSD, other conditions, therapy, medication)

## Page 1 – Overview & Key Indicators

![Image](https://github.com/user-attachments/assets/70948eef-ce23-4e4d-a8f0-44ed9207abd1)
This is the high-level summary page, designed to give a quick overview.

Top KPI cards:

- **% Patients with Dizziness** – around **51.7%**  
- **Most common symptom** – **Sweating**  
- **Most common pre-existing condition** – **Anxiety**  
- **Most affected age category** – **Adult**

Middle visuals:

- A bar chart showing **True vs False counts** for the selected symptom  
  (Chest Pain, Dizziness, Shortness of Breath, Sweating, Trembling).  
- A donut chart with the **top 3 most common triggers** (Unknown, PTSD, Phobia).

Bottom KPI cards:

- **Average alcoholic drinks per week** – about **4.55**  
- **Average panic attack duration** – about **24 minutes**  
- **Average panic attack frequency** – about **4.5** on the given scale
---

## Page 2 – Lifestyle & Intensity Distributions
![Image](https://github.com/user-attachments/assets/99e5b12b-6dce-4cf3-a983-6616cd58a557)
This page focuses on how values are distributed in the population.

Visuals:

- **Number of Patients by Sleep Hours**  
- **Number of Patients by Panic Attack Duration**  
- **Number of Patients by Drinks per Week (alcohol consumption)**  

Slicers:

- Panic Score (High / Medium / Low)  
- Gender  
- Trigger Reason  
- Medical History  

You can use the slicers to see how these distributions change for different subgroups  
(for example, only patients with high panic score, or only those with PTSD).

### Main conclusions

- Many patients cluster around a **typical sleep duration**  
  (roughly around 7–8 hours), with fewer people at the very low or very high ends.  
- **Panic attack duration** tends to cluster around a central value  
  (around **20–25 minutes**), with fewer attacks that are much shorter or much longer.  
- **Alcohol consumption** is spread out, but there is a noticeable group of patients  
  drinking **around 5–6 drinks per week**.  
- When filtering for high panic scores, you can check whether these groups tend to have  
  **shorter sleep**, **longer attacks**, or **higher alcohol intake**.

---
  
## Page 3  – Age Group & Trigger Analysis
![Image](https://github.com/user-attachments/assets/02f5f4ee-6ac8-4548-bcb0-26f5d9501bff
)

- Small multiples by **trigger reason** (Caffeine, Phobia, PTSD, Social Anxiety).  
- For each trigger, a bar chart comparing **Adults** and **Young Adults**.  
- A **Selector** slicer that lets you choose which metric to display:
  - Average Panic Score  
  - Average Panic Attack Frequency  
  - Average Sleep Hours  

When you change the selector, the same visual updates, so you can compare age groups and triggers across different metrics without changing pages.

### Main conclusions

- **Sleep hours** are quite similar across age groups and triggers.  
  Most averages are between **6.4 and 6.7 hours** of sleep.  
- For some triggers (e.g. caffeine, phobia), **young adults sleep slightly more** than adults.  
  For others (e.g. PTSD, social anxiety), adults sleep a bit more.  
  The gaps are small.  
- When switching the selector to panic score or panic frequency, differences between age groups are also **moderate rather than extreme**.  
- Overall, **trigger type** seems more important than age group; adults and young adults show similar patterns for each trigger.


---

### Final conclusions

- The dataset is dominated by **adult patients**.  
- **Sweating and dizziness** are very common symptoms during panic attacks.  
- **Anxiety** is the most frequent pre-existing condition, suggesting many patients  
  already have an anxiety-related background.  
- The top triggers are **Unknown, PTSD, and Phobia**, which together account for  
  about **one-third each** of the main triggers.  
- On average, patients experience **moderate panic frequency**,  
  **attacks lasting around 24 minutes**, and **moderate alcohol consumption**.
