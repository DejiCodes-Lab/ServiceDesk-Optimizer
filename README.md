# ServiceDesk 360: IT Support Performance Analysis

## 📊 Project Overview
This project provides a data-driven analysis of IT Support operations using a dataset of **9,500+ support tickets** from 2020. The primary objective was to visualize the ticket lifecycle and provide actionable insights for IT leadership to reduce backlog and improve the user experience.

### The Problem
The support team faced challenges in tracking ticket aging and severity-based prioritization. Initial analysis revealed that over **70% of tickets remained in an "Open" status**, and a significant portion of tickets were missing severity assignments (Unassigned), leading to triage delays.

## 🚀 Key Insights
* **Ticket Backlog:** Identified a high volume of open tickets (6,838) vs. resolved tickets (1,283), indicating a need for increased staffing or automated triage.
* **Resolution Efficiency:** The average ticket remains open for **18.9 days**, regardless of priority.
* **Satisfaction Metrics:** The average satisfaction score is **2.17/3.0**, showing a strong baseline but highlighting room for improvement in "Unsatisfied" categories.
* **Demand Distribution:** Hardware and Architecture groups received the highest ticket volume, accounting for nearly 40% of all requests.

## 🛠️ Tech Stack
* **Analysis:** Excel, Power Query
* **Visualization:** Power BI
* **Dataset:** 9,542 records covering hardware, software, and networking issues.

## 📈 Dashboard Features
* **KPI Overview:** Real-time tracking of Total Tickets, Average Resolution Time (ART), and CSAT.
* **Severity Matrix:** Breakdown of tickets by High, Medium, and Low severity to prioritize high-impact issues.
* **Team Performance:** Analysis of ticket distribution across Owner Groups (Networking, Software, Hardware, etc.).
* **Trend Analysis:** Monthly volume tracking to identify peak support periods.

## 📂 Data Dictionary
| Column | Description |
| :--- | :--- |
| `ticket_number` | Unique identifier for each request. |
| `owner_group` | The IT department responsible (e.g., Hardware, Software). |
| `severity` | Impact level (0-Unassigned to 3-High). |
| `days_open` | Total duration the ticket has been active. |
| `satisfaction_score` | User-reported satisfaction (1-3). |

## 💡 Recommendation
Based on the analysis, the IT department should:
1. **Automate Triage:** Standardize severity assignment for the 3,000+ "Unassigned" tickets.
2. **Focus on Hardware:** Allocate more resources to the Hardware group as they handle the highest volume.
3. **SLA Review:** Address the 19-day average open time for "High" severity issues.
