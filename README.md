# 🏏 Asia Cup Cricket Analysis (1984–2022)

An exploratory data analysis of Asia Cup cricket matches spanning nearly four decades, examining how the game has evolved across formats, eras, and key performance metrics.

---

## 📁 Project Structure

```
├── data/
│   ├── asiacup.csv
│   ├── batsman data odi.csv
│   ├── batsman data t20i.csv
│   ├── bowler data odi.csv
│   ├── bowler data t20i.csv
│   ├── wicketkeeper data odi.csv
│   ├── wicketkeeper data t20i.csv
│   └── champion.csv
├── notebooks/
│   └── NotebookDataPreparationAndMatchAnalysis.ipynb
├── images/
│   ├── graph_01.png
│   ├── graph_02.png
│   ├── graph_03.png
│   ├── graph_04.png
│   └── graph_05.png
└── README.md
```

---

## 📊 Analysis Overview

### Format Distribution
![Asia Cup Matches by Format](images/graph_01.png)
ODI has dominated the Asia Cup with **206 matches** compared to **48 T20I matches**, reflecting the tournament's historical roots in the 50-over format.

---

### ODI Matches by Year
![ODI Matches by Year](images/graph_02.png)
Match counts grew significantly from the mid-2000s onward, with 2004, 2008, and 2018 each reaching a peak of **26 matches** — driven by expanded team participation and round-robin formats.

---

### ODI Matches by Era
![ODI Matches by Era](images/graph_03.png)
The analysis splits matches into three eras: **Early (1984–1995)**, **Middle (1996–2008)**, and **Modern (2009–2018)**. The Middle and Modern eras saw significantly more matches, with 78 and 76 respectively vs just 50 in the Early era.

---

### Performance Distributions by Era (KDE)
![KDE Performance by Era](images/graph_04.png)
Kernel density plots reveal how runs scored, strike rate, and boundary percentage have shifted across eras. The Modern Era shows a tighter, higher distribution — indicating more consistent and aggressive batting.

---

### Batting Metrics by Era (Box Plots)
![Boxplot Batting by Era](images/graph_05.png)
Box plots confirm the trend: the **Modern Era** has the highest median runs (246) with a tighter IQR (64), while the **Middle Era** shows the most volatility. Sixes have increased steadily across all three eras.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas** — data wrangling
- **Matplotlib** — visualisation
- **Seaborn** — statistical plots
- **Jupyter Notebook**

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
   ```

2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook notebooks/NotebookDataPreparationAndMatchAnalysis.ipynb
   ```

---

## 📌 Key Findings

- ODI remains the dominant Asia Cup format with 4x more matches than T20I
- Match frequency grew significantly post-2000 due to tournament expansion
- The Modern Era (2009–2018) shows higher, more consistent scoring with greater boundary hitting
- The Middle Era was the most volatile period for batting performance
- Sixes have increased steadily across all eras, reflecting the evolution of aggressive batting
