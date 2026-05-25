# Mobile App User Acquisition & Fraud Analysis

This is a personal project I built using Power BI to practice data analysis skills. The main goal is to evaluate the performance of a User Acquisition (UA) campaign for a mobile app and identify potential bot traffic to support budget optimization.

## Business Objectives
- Track basic performance metrics such as ROAS, CVR, Cost, and Revenue.
- Identify which marketing channels are performing well and which are underperforming.
- Look for unusual click patterns to detect potential ad fraud.

## Tech Stack
- Tool: Power BI
- Skills applied: Data Cleaning, basic DAX, Data Modeling, and Data Visualization.

## Key Findings

### 1. Performance Insights
- The overall Return on Ad Spend (ROAS) is currently at 0.06.
- Channel 280 brings in the most revenue with a reasonable cost.
- Channels like 245 and 107 consume a large portion of the budget but generate $0 in revenue. It might be a good idea to pause these channels and reallocate the budget.

### 2. Fraud Detection
- Found suspicious traffic from IPs 73487, 73516, and 5345. They generated hundreds of clicks but zero installs, which affected the overall CVR.
- Click volumes show unusual spikes during Hour 4 and Hour 23 without a matching increase in installs. Suggesting these IPs could be added to a tracking blacklist to save ad spend.

## Dashboard Snapshots
<img width="996" height="619" alt="Screenshot 2026-05-25 220319" src="https://github.com/user-attachments/assets/9dc8e331-0f29-47ea-bc7b-2e06879963b5" />
<img width="1003" height="617" alt="Screenshot 2026-05-25 220307" src="https://github.com/user-attachments/assets/1a23bfcb-d27e-444a-8feb-e3a97786871d" />

