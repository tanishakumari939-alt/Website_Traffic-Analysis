# Website_Traffic-Analysis

## 📖 About the Project

**Website Traffic Analysis** is a Python-based Exploratory Data Analysis (EDA) project focused on understanding website traffic and user engagement.

The project analyzes website performance across different **channel groups** and **hours of the day**.

The analysis includes:

- 👥 Users
- 🧭 Sessions
- 💬 Engaged Sessions
- ⏱️ Average Engagement Time
- 🔄 Engaged Sessions per User
- 📌 Events per Session
- 📈 Engagement Rate
- ⚡ Event Count

The dataset contains **3,182 records** and the analysis was performed using Python and Jupyter Notebook.

---

## 🎯 Objectives

The main objectives of this project are:

- 👥 Analyze website users and sessions
- 📣 Compare traffic across different channels
- ⏱️ Analyze average engagement time
- 📊 Study engagement rates
- 🔄 Compare engaged and non-engaged sessions
- 🕐 Analyze traffic according to the hour of the day
- 📈 Identify useful website traffic patterns
- 💡 Generate data-driven insights

---

## 🗂️ Dataset

The dataset contains website traffic information with the following columns:

| Column | Description |
|---|---|
| `channel group` | Website traffic/acquisition channel |
| `Datehour` | Date and hour of the traffic |
| `Users` | Number of users |
| `Sessions` | Number of sessions |
| `Engaged sessions` | Number of engaged sessions |
| `Average engagement time per session` | Average engagement time |
| `Engaged sessions per user` | Engaged sessions relative to users |
| `Events per session` | Average events per session |
| `Engagement rate` | Website engagement rate |
| `Event count` | Total number of events |
| `Hour` | Hour extracted from Datehour |

---


## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| 🐍 Python | Data analysis |
| 🐼 Pandas | Data cleaning & manipulation |
| 🔢 NumPy | Numerical operations |
| 📊 Matplotlib | Data visualization |
| 🎨 Seaborn | Statistical visualization |
| 📓 Jupyter Notebook | Interactive analysis |
| 💻 GitHub | Project documentation |

---

## 🔄 Analysis Workflow

```text
📥 Import Dataset
        ↓
🧹 Data Cleaning
        ↓
🗓️ Date & Time Conversion
        ↓
🔢 Convert Data Types
        ↓
🕐 Extract Hour
        ↓
🔎 Exploratory Data Analysis
        ↓
📊 Data Visualization
        ↓
💡 Insights & Findings

```

## 📈 Visualizations

The project contains multiple visualizations:

#	Visualization	Chart


| No. | Analysis | Visualization |
|:---:|---|---|
| 01 | Users & Sessions Over Time | 📈 Line Chart |
| 02 | Total Users by Channel | 📊 Bar Chart |
| 03 | Average Engagement Time by Channel | 📊 Bar Chart |
| 04 | Engagement Rate Distribution | 📦 Box Plot |
| 05 | Engaged vs Non-Engaged Sessions | 📊 Bar Chart |
| 06 | Traffic by Hour & Channel | 🔥 Heatmap |
| 07 | Engagement Rate vs Sessions | 📈 Line Chart |


## 🖼️ Project Visualizations

### 📈 Users & Sessions Over Time
<img width="857" height="509" alt="image" src="https://github.com/user-attachments/assets/7f055bfa-d3e7-4d7d-a16c-b9e83b0c5f72" />


### 📊 Users by Channel
<img width="717" height="536" alt="image" src="https://github.com/user-attachments/assets/2c7838c8-a013-4335-959d-0947d92b872c" />



### ⏱️ Average Engagement Time
<img width="706" height="542" alt="image" src="https://github.com/user-attachments/assets/408b61f2-35ad-4d5a-93aa-ef6f0eda4e96" />



### 📦 Engagement Rate Distribution
<img width="695" height="535" alt="image" src="https://github.com/user-attachments/assets/818392ed-69b8-42a5-bf55-441649429e74" />



### 🔄 Engaged vs Non-Engaged Sessions
<img width="710" height="541" alt="image" src="https://github.com/user-attachments/assets/7afde78d-923c-4a86-9a1f-bd9026c4eb27" />



### 🔥 Traffic Heatmap


---


## 💡 Key Metrics

### Metric	Average

| Metric | Average |
|---|---:|
| 👥 Users | 41.94 |
| 🧭 Sessions | 51.19 |
| 💬 Engaged Sessions | 28.33 |
| ⏱️ Avg. Engagement Time | 66.64 sec |
| 🔄 Engaged Sessions / User | 0.606 |
| 📌 Events / Session | 4.68 |
| 📈 Engagement Rate | 50.34% |
| ⚡ Event Count | 242.27 |
---

The analysis helps answer important website-performance questions:

👥 User Behaviour
How many users visit the website?
How does traffic change over time?
📣 Channel Performance
Which channels generate more users?
Which channels show stronger engagement?
⏱️ Engagement
Which channels have higher engagement time?
How does engagement rate vary?
🕐 Time Analysis
Which hours have higher traffic?
Are there noticeable hourly traffic patterns?
📊 Session Quality
What proportion of sessions are engaged?
How does engaged traffic vary between channels?
📁 Project Structure
Website-Traffic-Analysis/
│
├── 📂 Dataset/
│   └── data-export (1).csv
│
├── 📂 Notebook/
│   └── Wesite_Traffic Analysis.ipynb
│
├── 📂 Screenshots/
│   ├── sessions_users_over_time.png
│   ├── users_by_channel.png
│   ├── engagement_time_by_channel.png
│   ├── engagement_rate_distribution.png
│   ├── engaged_vs_non_engaged.png
│   └── traffic_by_hour_channel.png
│
└── 📄 README.md


