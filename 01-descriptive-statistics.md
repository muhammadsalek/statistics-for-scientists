# 📊 Chapter 1: Descriptive Statistics

## The Complete Guide — From First Principles to Publication-Ready Analysis

---

[![Open Access](https://img.shields.io/badge/Open%20Access-Free-success?style=for-the-badge)]()
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?style=for-the-badge)]()
[![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-blue?style=for-the-badge)]()
[![Sections](https://img.shields.io/badge/Sections-100%2B-orange?style=for-the-badge)]()
[![Software](https://img.shields.io/badge/Software-R%20%7C%20Python%20%7C%20SPSS%20%7C%20STATA%20%7C%20SAS%20%7C%20Excel-brightgreen?style=for-the-badge)]()

---

> *"The goal is to turn data into information, and information into insight."* — **Carly Fiorina**

---

## 📋 Table of Contents

<details>
<summary><strong>📚 Click to expand full table of contents</strong></summary>

### 1. Fundamentals
- [1.1 What is Descriptive Statistics?](#11-what-is-descriptive-statistics)
- [1.2 Historical Background](#12-historical-background)
- [1.3 Evolution of Descriptive Statistics](#13-evolution-of-descriptive-statistics)
- [1.4 Importance in Science](#14-importance-in-science)
- [1.5 Importance in Medical Research](#15-importance-in-medical-research)
- [1.6 Importance in Public Health](#16-importance-in-public-health)
- [1.7 Importance in Machine Learning](#17-importance-in-machine-learning)
- [1.8 Importance in AI](#18-importance-in-ai)
- [1.9 Types of Descriptive Statistics](#19-types-of-descriptive-statistics)

### 2. Data Fundamentals
- [2.1 Population vs Sample Summary](#21-population-vs-sample-summary)
- [2.2 Data Types](#22-data-types)
- [2.3 Variables](#23-variables)
- [2.4 Measurement Scales](#24-measurement-scales)

### 3. Frequency Distributions
- [3.1 Frequency Distribution](#31-frequency-distribution)
- [3.2 Relative Frequency](#32-relative-frequency)
- [3.3 Cumulative Frequency](#33-cumulative-frequency)
- [3.4 Frequency Tables](#34-frequency-tables)
- [3.5 Grouped Data](#35-grouped-data)
- [3.6 Class Intervals](#36-class-intervals)
- [3.7 Class Boundaries](#37-class-boundaries)
- [3.8 Class Midpoints](#38-class-midpoints)

### 4. Data Visualization
- [4.1 Histograms](#41-histograms)
- [4.2 Frequency Polygon](#42-frequency-polygon)
- [4.3 Ogive](#43-ogive)
- [4.4 Bar Chart](#44-bar-chart)
- [4.5 Pie Chart](#45-pie-chart)
- [4.6 Box Plot](#46-box-plot)
- [4.7 Scatter Plot](#47-scatter-plot)

### 5. Exploratory Data Analysis
- [5.1 Exploratory Data Analysis (EDA)](#51-exploratory-data-analysis-eda)
- [5.2 Data Cleaning](#52-data-cleaning)
- [5.3 Missing Data](#53-missing-data)
- [5.4 Outlier Detection](#54-outlier-detection)
- [5.5 Five Number Summary](#55-five-number-summary)
- [5.6 Quartiles & Percentiles](#56-quartiles--percentiles)

### 6. Distribution Shape
- [6.1 Distribution Shape](#61-distribution-shape)
- [6.2 Symmetry & Skewness](#62-symmetry--skewness)
- [6.3 Kurtosis](#63-kurtosis)
- [6.4 Empirical Rule](#64-empirical-rule)
- [6.5 Chebyshev's Theorem](#65-chebyshevs-theorem)

### 7. Reporting & Software
- [7.1 Reporting Standards](#71-reporting-standards)
- [7.2 R Implementation](#72-r-implementation)
- [7.3 Python Implementation](#73-python-implementation)

### 8. Assessment
- [8.1 Worked Example](#81-worked-example)
- [8.2 Practice Questions](#82-practice-questions)
- [8.3 Chapter Summary](#83-chapter-summary)
- [8.4 Formula Sheet](#84-formula-sheet)

</details>

---

## 1. Fundamentals

### 1.1 What is Descriptive Statistics?

> 📖 **Definition**: Descriptive statistics is the branch of statistics that deals with summarizing, organizing, and presenting data in a meaningful way.

**The Foundation of All Statistical Analysis:**

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                        DESCRIPTIVE STATISTICS                            ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║  ┌─────────────┐    ┌─────────────┐    ┌─────────────┐                  ║
║  │  SUMMARIZE  │    │  ORGANIZE   │    │  VISUALIZE  │                  ║
║  ├─────────────┤    ├─────────────┤    ├─────────────┤                  ║
║  │ • Mean      │    │ • Frequency │    │ • Graphs    │                  ║
║  │ • Median    │    │ • Tables    │    │ • Charts    │                  ║
║  │ • Mode      │    │ • Groups    │    │ • Plots     │                  ║
║  │ • SD        │    │ • Classes   │    │ • Maps      │                  ║
║  │ • Range     │    │ • Bins      │    │ • Heatmaps  │                  ║
║  └─────────────┘    └─────────────┘    └─────────────┘                  ║
║                                                                           ║
║  ┌───────────────────────────────────────────────────────────────────┐   ║
║  │                      DISCOVER PATTERNS                            │   ║
║  ├───────────────────────────────────────────────────────────────────┤   ║
║  │  Trends  →  Outliers  →  Relationships  →  Gaps  →  Anomalies   │   ║
║  └───────────────────────────────────────────────────────────────────┘   ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

**The Data Journey:**

```
Raw Data → Organized Data → Summarized Data → Visualized Data → Insights
    │            │               │               │              │
    │            │               │               │              │
    ▼            ▼               ▼               ▼              ▼
  Numbers    Tables         Statistics       Graphs        Decisions
```

### 1.2 Historical Background

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    HISTORICAL DEVELOPMENT TIMELINE                        ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║  3000 BCE                       1600s CE                       1800s CE   ║
║      │                              │                             │       ║
║  ┌───▼───┐                    ┌───▼───┐                     ┌───▼───┐   ║
║  │Ancient│                    │Graunt │                     │ Gauss │   ║
║  │Census │                    │Petty  │                     │Laplace│   ║
║  └───────┘                    └───────┘                     └───────┘   ║
║      │                              │                             │       ║
║  • Population              • Bills of Mortality          • Normal Dist  ║
║  • Records                 • Political Arithmetic       • Least Squares ║
║                                                                           ║
║  1880s CE                       1900s CE                       2000s CE   ║
║      │                              │                             │       ║
║  ┌───▼───┐                    ┌───▼───┐                     ┌───▼───┐   ║
║  │Galton │                    │Fisher │                     │Big    │   ║
║  │Pearson│                    │Tukey  │                     │Data   │   ║
║  └───────┘                    └───────┘                     └───────┘   ║
║      │                              │                             │       ║
║  • Correlation             • Statistical Tests           • Machine      ║
║  • Regression              • ANOVA                       • Learning     ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

| Period | Key Developments | Major Contributors |
|--------|-----------------|-------------------|
| **Ancient** | Census data, population records | Babylonians, Egyptians, Romans |
| **Renaissance** | Political arithmetic, life tables | John Graunt, William Petty |
| **Enlightenment** | Normal distribution, least squares | Gauss, Laplace, de Moivre |
| **Modern** | Correlation, regression, EDA | Galton, Pearson, Fisher, Tukey |
| **Digital Age** | Computational statistics, ML | Modern statisticians |

### 1.3 Importance in Science

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                 IMPORTANCE ACROSS SCIENTIFIC FIELDS                       ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║  ┌─────────────────────────────────────────────────────────────────────┐  ║
║  │ BIOLOGY                                                             │  ║
║  │  → Summarizing measurements (height, weight, cell count)            │  ║
║  │  → Characterizing populations (species, genetic variants)           │  ║
║  └─────────────────────────────────────────────────────────────────────┘  ║
║                                                                           ║
║  ┌─────────────────────────────────────────────────────────────────────┐  ║
║  │ MEDICINE                                                            │  ║
║  │  → Clinical trials baseline characteristics                         │  ║
║  │  → Reference ranges (normal values)                                 │  ║
║  │  → Disease incidence and prevalence                                 │  ║
║  └─────────────────────────────────────────────────────────────────────┘  ║
║                                                                           ║
║  ┌─────────────────────────────────────────────────────────────────────┐  ║
║  │ PUBLIC HEALTH                                                       │  ║
║  │  → Health indicators monitoring                                     │  ║
║  │  → DHS surveys (demographic and health)                             │  ║
║  │  → Epidemic response characterization                               │  ║
║  └─────────────────────────────────────────────────────────────────────┘  ║
║                                                                           ║
║  ┌─────────────────────────────────────────────────────────────────────┐  ║
║  │ MACHINE LEARNING                                                    │  ║
║  │  → Data preprocessing and understanding                             │  ║
║  │  → Feature engineering and scaling                                  │  ║
║  │  → Model evaluation and interpretation                              │  ║
║  └─────────────────────────────────────────────────────────────────────┘  ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 1.4 Types of Descriptive Statistics

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    TYPES OF DESCRIPTIVE STATISTICS                        ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║  1. CENTRAL TENDENCY                                                      ║
║  ┌───────────────────────────────────────────────────────────────────┐   ║
║  │  Mean    →  Average value (balance point)                        │   ║
║  │  Median  →  Middle value (50th percentile)                       │   ║
║  │  Mode    →  Most frequent value                                  │   ║
║  └───────────────────────────────────────────────────────────────────┘   ║
║                                                                           ║
║  2. DISPERSION (SPREAD)                                                   ║
║  ┌───────────────────────────────────────────────────────────────────┐   ║
║  │  Range   →  Max - Min (full spread)                              │   ║
║  │  IQR     →  Q3 - Q1 (middle 50%)                                 │   ║
║  │  Variance →  Average squared deviation                           │   ║
║  │  SD      →  √Variance (original units)                           │   ║
║  └───────────────────────────────────────────────────────────────────┘   ║
║                                                                           ║
║  3. DISTRIBUTION SHAPE                                                    ║
║  ┌───────────────────────────────────────────────────────────────────┐   ║
║  │  Symmetry  →  Balanced on both sides                             │   ║
║  │  Skewness  →  Direction of tail                                  │   ║
║  │  Kurtosis  →  Peakedness of distribution                         │   ║
║  └───────────────────────────────────────────────────────────────────┘   ║
║                                                                           ║
║  4. RELATIONSHIP                                                          ║
║  ┌───────────────────────────────────────────────────────────────────┐   ║
║  │  Correlation →  Strength of linear relationship                  │   ║
║  │  Covariance  →  Direction of relationship                        │   ║
║  │  Contingency →  Association between categories                   │   ║
║  └───────────────────────────────────────────────────────────────────┘   ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

---

## 2. Data Fundamentals

### 2.1 Population vs Sample

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    POPULATION VS SAMPLE                                  ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║                         POPULATION                                        ║
║                    ┌───────────────────┐                                  ║
║                    │   All Subjects    │                                  ║
║                    │    of Interest    │                                  ║
║                    │                   │                                  ║
║                    │   N = 10,000      │                                  ║
║                    │   Parameter: μ    │                                  ║
║                    │   Greek Notation  │                                  ║
║                    └───────────────────┘                                  ║
║                             │                                             ║
║                             │ SAMPLE                                      ║
║                             ▼                                             ║
║                    ┌───────────────────┐                                  ║
║                    │   Subset of the   │                                  ║
║                    │    Population     │                                  ║
║                    │                   │                                  ║
║                    │   n = 100         │                                  ║
║                    │   Statistic: x̄    │                                  ║
║                    │   Roman Notation  │                                  ║
║                    └───────────────────┘                                  ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

| Aspect | Population | Sample |
|--------|-----------|--------|
| **Definition** | Entire group of interest | Subset of population |
| **Size** | N | n |
| **Parameter** | μ, σ, ρ | Statistic |
| **Notation** | Greek | Roman |
| **Access** | Often unknown | Known |
| **Cost** | Expensive | Feasible |

### 2.2 Data Types

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                         DATA TYPES HIERARCHY                              ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║                               DATA                                        ║
║                                 │                                         ║
║                ┌────────────────┼────────────────┐                       ║
║                │                │                │                       ║
║                ▼                ▼                ▼                       ║
║         QUANTITATIVE     CATEGORICAL       OTHER                         ║
║         (Numerical)      (Groups)                                        ║
║                │                │                                         ║
║     ┌──────────┼──────────┐     │                                        ║
║     │          │          │     │                                        ║
║     ▼          ▼          ▼     ▼                                        ║
║  DISCRETE  CONTINUOUS   ORDINAL  NOMINAL                                 ║
║  (Counts)   (Measured)  (Ranked) (Unordered)                            ║
║                                                                           ║
║  ┌───────────────────────────────────────────────────────────────────┐   ║
║  │ EXAMPLES                                                          │   ║
║  ├───────────────────────────────────────────────────────────────────┤   ║
║  │ Discrete    →  Children, Patients, Visits, Cases                 │   ║
║  │ Continuous  →  Height, Weight, BP, Temperature                   │   ║
║  │ Ordinal     →  Severity, Education, Stage, Rating                │   ║
║  │ Nominal     →  Gender, Blood Group, Religion, Race               │   ║
║  └───────────────────────────────────────────────────────────────────┘   ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 2.3 Variables

> 📖 **Definition**: A **variable** is any characteristic that can take different values across individuals.

**Variable Classification:**

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                         VARIABLE CLASSIFICATION                          ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║   ┌───────────────────────────────────────────────────────────────────┐  ║
║   │                         VARIABLE                                  │  ║
║   └───────────────────────────────────────────────────────────────────┘  ║
║                                    │                                     ║
║           ┌────────────────────────┼────────────────────────┐            ║
║           │                        │                        │            ║
║           ▼                        ▼                        ▼            ║
║   ┌───────────────┐        ┌───────────────┐        ┌───────────────┐   ║
║   │  QUANTITATIVE │        │  CATEGORICAL  │        │  OTHER TYPES  │   ║
║   │   Variables   │        │   Variables   │        │               │   ║
║   ├───────────────┤        ├───────────────┤        ├───────────────┤   ║
║   │ • Height      │        │ • Gender      │        │ • Confounder  │   ║
║   │ • Weight      │        │ • Blood Group │        │ • Mediator    │   ║
║   │ • Age         │        │ • Religion    │        │ • Moderator   │   ║
║   │ • Income      │        │ • Education   │        │ • Control     │   ║
║   └───────────────┘        └───────────────┘        └───────────────┘   ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

**Example: Research Question**
> "Does physical activity reduce blood pressure among adults?"

| Variable | Type | Role |
|----------|------|------|
| Physical Activity | Quantitative | Independent |
| Blood Pressure | Quantitative | Dependent |
| Age | Quantitative | Confounder |
| Sex | Categorical | Control |
| BMI | Quantitative | Covariate |

### 2.4 Measurement Scales

> 📖 **Definition**: A **measurement scale** defines how a variable is observed, categorized, or quantified.

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    HIERARCHY OF MEASUREMENT SCALES                        ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║                     Increasing Information                                ║
║                  ─────────────────────────▶                               ║
║                                                                           ║
║   ┌─────────────┐    ┌─────────────┐    ┌─────────────┐    ┌─────────────┐║
║   │   NOMINAL   │    │   ORDINAL   │    │  INTERVAL   │    │    RATIO    │║
║   │   Scale     │    │   Scale     │    │   Scale     │    │   Scale     │║
║   ├─────────────┤    ├─────────────┤    ├─────────────┤    ├─────────────┤║
║   │ Categories  │    │ Categories  │    │ Equal       │    │ Equal       │║
║   │ No Order    │    │ With Order  │    │ Intervals   │    │ Intervals   │║
║   │ Labels      │    │ Rankings    │    │ No True Zero│    │ True Zero   │║
║   │ =, ≠        │    │ <, >        │    │ +, −        │    │ ×, ÷        │║
║   ├─────────────┤    ├─────────────┤    ├─────────────┤    ├─────────────┤║
║   │ Blood Group │    │ Pain Score  │    │ Temperature │    │ Height      │║
║   │ Gender      │    │ Cancer Stage│    │ IQ Score    │    │ Weight      │║
║   │ Religion    │    │ Education   │    │ Calendar    │    │ Age         │║
║   └─────────────┘    └─────────────┘    └─────────────┘    └─────────────┘║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

**Choosing the Correct Scale:**

```
Start → Is it numeric?
           │
           ├── Yes → Is there a true zero?
           │           ├── Yes → RATIO SCALE
           │           └── No  → INTERVAL SCALE
           │
           └── No → Is there a natural order?
                     ├── Yes → ORDINAL SCALE
                     └── No  → NOMINAL SCALE
```

---

## 3. Frequency Distributions

### 3.1 Frequency Distribution

> 📖 **Definition**: A **frequency distribution** displays the number of observations corresponding to each value or class interval.

**General Structure:**

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    FREQUENCY DISTRIBUTION                                ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║   ┌───────────────┬───────────────┬───────────────┬─────────────────┐   ║
║   │  Value/Class  │   Frequency   │   Relative    │   Cumulative    │   ║
║   │               │               │   Frequency   │   Frequency     │   ║
║   ├───────────────┼───────────────┼───────────────┼─────────────────┤   ║
║   │  Category A   │      15       │     0.30      │       15        │   ║
║   │  Category B   │      22       │     0.44      │       37        │   ║
║   │  Category C   │      18       │     0.36      │       55        │   ║
║   │  Category D   │      10       │     0.20      │       65        │   ║
║   │               │               │               │                 │   ║
║   │  Total        │      65       │     1.00*     │       65        │   ║
║   └───────────────┴───────────────┴───────────────┴─────────────────┘   ║
║                                                                           ║
║   *Sum may not equal 1 due to rounding                                   ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 3.2 Relative Frequency

> 📖 **Definition**: The proportion of observations in each category.

**Formula:**
$$ \text{Relative Frequency} = \frac{\text{Frequency}}{\text{Total Observations}} $$

**Example:**
```
If 15 out of 65 people have blood type O+:
Relative Frequency = 15/65 = 0.231 = 23.1%
```

### 3.3 Cumulative Frequency

> 📖 **Definition**: The running total of frequencies.

**Formula:**
$$ \text{Cumulative Frequency} = \sum_{i=1}^{k} f_i $$

**Example:**
```
Score Range   Frequency   Cumulative
0-59             5            5
60-69            8           13
70-79           12           25
80-89           18           43
90-100          17           60
```

### 3.4 Frequency Tables

**Complete Example: Blood Types (n=100)**

| Blood Type | Frequency | Relative | Percentage | Cumulative |
|------------|----------:|---------:|-----------:|-----------:|
| O+ | 35 | 0.35 | 35% | 35 |
| A+ | 28 | 0.28 | 28% | 63 |
| B+ | 18 | 0.18 | 18% | 81 |
| AB+ | 12 | 0.12 | 12% | 93 |
| O- | 4 | 0.04 | 4% | 97 |
| A- | 2 | 0.02 | 2% | 99 |
| B- | 1 | 0.01 | 1% | 100 |
| **Total** | **100** | **1.00** | **100%** | |

**Interpretation:**
- O+ is most common (35%)
- 63% are O+ or A+
- Only 7% are Rh-negative

### 3.5 Grouped Data

> 📖 **Definition**: Observations organized into class intervals.

**Example: Age Distribution (n=200)**

```
┌─────────────────────────────────────────────────────────────────────────┐
│                    GROUPED FREQUENCY TABLE                              │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│   Age Group    │   Frequency   │   Percentage   │  Cumulative          │
│   (Years)      │               │                │                      │
│  ──────────────┼───────────────┼────────────────┼──────────────────────│
│   20-29        │      18       │     9.0%       │     18               │
│   30-39        │      42       │    21.0%       │     60               │
│   40-49        │      56       │    28.0%       │    116               │
│   50-59        │      48       │    24.0%       │    164               │
│   60-69        │      36       │    18.0%       │    200               │
│                │               │                │                      │
│   Total        │     200       │   100.0%       │                      │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

### 3.6 Class Intervals

> 📖 **Definition**: Ranges used to group continuous data.

**Choosing Class Intervals:**

```
Step 1: Find Range
Range = Maximum - Minimum
Example: 98 - 45 = 53

Step 2: Choose Number of Classes
Sturges' Rule: k = 1 + 3.322 × log₁₀(n)
For n = 30: k = 1 + 3.322 × 1.477 = 5.91 ≈ 6

Step 3: Calculate Class Width
Class Width = Range / Number of Classes
53 / 6 = 8.83 ≈ 9

Step 4: Create Intervals
40-48, 49-57, 58-66, 67-75, 76-84, 85-93, 94-102
```

### 3.7 Class Boundaries

> 📖 **Definition**: True limits eliminating gaps between classes.

**Example:**
```
Class Interval    Lower Boundary    Upper Boundary
20-29                19.5              29.5
30-39                29.5              39.5
40-49                39.5              49.5

Formula:
Lower Boundary = Lower Limit - 0.5
Upper Boundary = Upper Limit + 0.5
```

### 3.8 Class Midpoints

> 📖 **Definition**: Center value of a class interval.

**Formula:**
$$ \text{Class Midpoint} = \frac{\text{Lower Limit} + \text{Upper Limit}}{2} $$

**Example:**
```
Class Interval    Midpoint
20-29             24.5
30-39             34.5
40-49             44.5
50-59             54.5
```

---

## 4. Data Visualization

### 4.1 Histograms

> 📖 **Definition**: A graphical display of frequency distribution for continuous variables. Bars are **adjacent**.

**Histogram Shapes:**

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                         HISTOGRAM SHAPES                                  ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║  SYMMETRIC (Normal)              RIGHT-SKEWED                            ║
║      ╔═══╗                          ╔═══╗                               ║
║    ╔═══════╗                      ╔═══════╗                             ║
║  ╔═══════════╗                  ╔═══════════╗                           ║
║╔═══════════════╗              ╔═══════════════╗                         ║
║╔═══════════════╗            ╔═══════════════════╗                       ║
║  ╔═══════════╗              ╔═══════════╗                               ║
║    ╔═══════╗                  ╔═══════╗                                 ║
║      ╔═══╗                      ╔═══╗                                   ║
║                                                                           ║
║  LEFT-SKEWED                     BIMODAL                                 ║
║      ╔═══╗                      ╔═══╗  ╔═══╗                           ║
║    ╔═══════╗                  ╔═══════╗╔═══════╗                       ║
║  ╔═══════════╗              ╔═══════════╗╔═══════════╗                 ║
║╔═══════════════╗          ╔═══════════════╗╔═══════════╗               ║
║╔═══════════════╗          ╔═══════════════╗╔═══════════╗               ║
║  ╔═══════════╗              ╔═══════════╗╔═══════════╗                 ║
║    ╔═══════╗                  ╔═══════╗╔═══════╗                       ║
║      ╔═══╗                      ╔═══╗  ╔═══╗                           ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

**Key Features:**
- Bars touch each other
- X-axis: Class intervals
- Y-axis: Frequency or density
- Shows distribution shape
- Identifies outliers

### 4.2 Frequency Polygon

> 📖 **Definition**: A line graph connecting class midpoints and frequencies.

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    FREQUENCY POLYGON                                     ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║  Frequency                                                                ║
║     │                                                                     ║
║  12 │                         ●                                          ║
║     │                       /   \                                        ║
║  10 │                     ●       ●                                      ║
║     │                   /           \                                    ║
║   8 │                 ●               ●                                  ║
║     │               /                   \                                ║
║   6 │             ●                       ●                              ║
║     │           /                           \                            ║
║   4 │         ●                               ●                          ║
║     │       /                                   \                        ║
║   2 │     ●                                       ●                      ║
║     │   /                                           \                    ║
║   0 │●───────────────────────────────────────────────●                   ║
║     └─────────────────────────────────────────────────────────────        ║
║      10    20    30    40    50    60    70    80    90                  ║
║                              Class Midpoints                             ║
║                                                                           ║
║  Key Features:                                                            ║
║  • Points at class midpoints                                              ║
║  • Lines connect points                                                   ║
║  • Starts and ends at baseline                                            ║
║  • Shows distribution trend                                               ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 4.3 Ogive (Cumulative Frequency Curve)

> 📖 **Definition**: A line graph displaying cumulative frequencies.

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    OGIVE (Cumulative Frequency Curve)                     ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║  Cumulative Frequency                                                     ║
║     │                                                                     ║
║  50 │                                                          ●          ║
║     │                                                        /           ║
║  40 │                                                      ●             ║
║     │                                                    /               ║
║  30 │                                                  ●                 ║
║     │                                                /                   ║
║  20 │                                              ●                     ║
║     │                                            /                       ║
║  10 │                                          ●                         ║
║     │                                        /                           ║
║   0 │●─────────────────────────────────────●                             ║
║     └─────────────────────────────────────────────────────────────        ║
║      20    30    40    50    60    70    80    90                       ║
║                         Upper Class Boundaries                           ║
║                                                                           ║
║  Key Features:                                                            ║
║  • Uses upper class boundaries                                            ║
║  • Always increases                                                       ║
║  • Starts at 0                                                            ║
║  • Ends at total n                                                        ║
║  • Used for percentiles                                                   ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 4.4 Bar Chart

> 📖 **Definition**: A graphical representation of categorical data with separated bars.

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                         BAR CHART                                        ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║  Frequency                                                                ║
║     │                                                                     ║
║  10 │           ╔═══╗                                                    ║
║     │           ║   ║                                                    ║
║   8 │     ╔═══╗ ║   ║                                                    ║
║     │     ║   ║ ║   ║                                                    ║
║   6 │     ║   ║ ║   ║                                                    ║
║     │     ║   ║ ║   ║                                                    ║
║   4 │ ╔═══╗║   ║ ║   ║                                                    ║
║     │ ║   ║║   ║ ║   ║                                                    ║
║   2 │ ║   ║║   ║ ║   ║                                                    ║
║     │ ║   ║║   ║ ║   ║                                                    ║
║   0 └─────────────────────────────────────────────────────────────         ║
║        A     B     C     D     E                                         ║
║                            Categories                                    ║
║                                                                           ║
║  Key Features:                                                            ║
║  • Equal width bars                                                       ║
║  • Gaps between bars                                                      ║
║  • For categorical data                                                   ║
║  • Easy to compare categories                                             ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 4.5 Pie Chart

> 📖 **Definition**: A circular graph showing proportions of a whole.

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                         PIE CHART                                        ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║                     ╔══════════════════╗                                 ║
║                  ╔══╝                  ╚══╗                              ║
║                ╔╝                         ╚╗                            ║
║              ╔╝          35%               ╚╗                          ║
║             ╔╝          O+                  ╚╗                         ║
║            ╔╝                                ╚╗                        ║
║           ╔╝                                  ╚╗                       ║
║          ╔╝                                    ╚╗                      ║
║          ║   18%  ╔══════╗  28%                 ║                      ║
║          ║   B+   ║      ║  A+                  ║                      ║
║          ╚╗        ╚══════╝                  ╔╝                       ║
║           ╚╗         12%                    ╔╝                        ║
║            ╚╗        AB+                   ╔╝                         ║
║             ╚╗                            ╔╝                          ║
║              ╚╗                          ╔╝                           ║
║                ╚╗  7% Others           ╔╝                             ║
║                  ╚══╗                ╔══╝                              ║
║                     ╚══════════════════╝                               ║
║                                                                           ║
║  Key Features:                                                            ║
║  • Shows proportions                                                      ║
║  • Sum to 100%                                                            ║
║  • Best for few categories                                                ║
║  • Not for precise comparisons                                            ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 4.6 Box Plot

> 📖 **Definition**: A graphical display of the five-number summary.

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                         BOX PLOT                                         ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║     Outlier                                                               ║
║         ●                                                                ║
║      ──────────────────────────────────────────────────────────────────    ║
║      │                    │              │                    │           ║
║      │   ┌────────────────┼──────────────┼────────────────┐   │           ║
║      │   │                │              │                │   │           ║
║      │   │   ─────────────┼──────────────┼────────────    │   │           ║
║      │   │                │      ████    │                │   │           ║
║      │   │                │      ████    │                │   │           ║
║      │   │                │      ████    │                │   │           ║
║      │   │                │      ████    │                │   │           ║
║      │   │   ─────────────┼──────────────┼────────────    │   │           ║
║      │   │                │              │                │   │           ║
║      │   └────────────────┼──────────────┼────────────────┘   │           ║
║      │                    │              │                    │           ║
║      ──────────────────────────────────────────────────────────────────    ║
║                                                                           ║
║        Min               Q1           Median       Q3             Max     ║
║                                                                           ║
║  Components:                                                              ║
║  • Box: IQR (Q1 to Q3)                                                    ║
║  • Line: Median                                                           ║
║  • Whiskers: 1.5 × IQR                                                    ║
║  • Points: Outliers                                                       ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 4.7 Scatter Plot

> 📖 **Definition**: A plot showing the relationship between two quantitative variables.

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                         SCATTER PLOT                                     ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║  Y                                                                        ║
║  │                                                                        ║
║  │       ●                                                               ║
║  │     ●   ●                                                             ║
║  │   ●       ●                                                           ║
║  │ ●           ●                                                         ║
║  │●               ●                                                      ║
║  │                 ●                                                     ║
║  │                   ●                                                   ║
║  │                     ●                                                 ║
║  │                       ●                                               ║
║  │                         ●                                             ║
║  └────────────────────────────────────────────────────────────────────    ║
║                                                                   X      ║
║                                                                           ║
║  Correlation Patterns:                                                    ║
║  • Positive: Points go up-right                                           ║
║  • Negative: Points go down-right                                         ║
║  • No correlation: Random scatter                                         ║
║  • Strong: Points close to line                                           ║
║  • Weak: Points spread out                                                ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

---

## 5. Exploratory Data Analysis

### 5.1 Exploratory Data Analysis (EDA)

> 📖 **Definition**: EDA is an approach to analyzing datasets to summarize their main characteristics, often with visual methods.

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                         EDA WORKFLOW                                     ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║   ┌─────────────────┐                                                    ║
║   │   Data          │                                                    ║
║   │   Collection    │                                                    ║
║   └────────┬────────┘                                                    ║
║            │                                                              ║
║            ▼                                                              ║
║   ┌─────────────────┐                                                    ║
║   │    Data         │                                                    ║
║   │   Cleaning      │                                                    ║
║   └────────┬────────┘                                                    ║
║            │                                                              ║
║            ▼                                                              ║
║   ┌─────────────────┐                                                    ║
║   │  Univariate     │                                                    ║
║   │  Analysis       │                                                    ║
║   └────────┬────────┘                                                    ║
║            │                                                              ║
║            ▼                                                              ║
║   ┌─────────────────┐                                                    ║
║   │  Bivariate      │                                                    ║
║   │  Analysis       │                                                    ║
║   └────────┬────────┘                                                    ║
║            │                                                              ║
║            ▼                                                              ║
║   ┌─────────────────┐                                                    ║
║   │  Multivariate   │                                                    ║
║   │  Analysis       │                                                    ║
║   └────────┬────────┘                                                    ║
║            │                                                              ║
║            ▼                                                              ║
║   ┌─────────────────┐                                                    ║
║   │   Pattern       │                                                    ║
║   │  Discovery      │                                                    ║
║   └─────────────────┘                                                    ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 5.2 Data Cleaning

**Common Issues:**

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    DATA CLEANING CHECKLIST                               ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║   ❌ Missing Values          → Impute or remove                          ║
║   ❌ Duplicate Records       → Remove duplicates                         ║
║   ❌ Inconsistent Formats    → Standardize formats                      ║
║   ❌ Outliers                → Investigate and handle                   ║
║   ❌ Data Entry Errors       → Correct or remove                        ║
║   ❌ Incomplete Responses    → Review and handle                       ║
║   ❌ Incorrect Coding        → Recode correctly                        ║
║   ❌ Impossible Values       → Investigate (e.g., age = 200)           ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 5.3 Missing Data

**Types:**
- **MCAR**: Missing Completely at Random
- **MAR**: Missing at Random
- **MNAR**: Missing Not at Random

**Handling Methods:**

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    MISSING DATA HANDLING METHODS                         ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║   1. LISTWISE DELETION                                                    ║
║      • Remove all cases with missing values                              ║
║      • Simple but reduces sample size                                    ║
║      • Only valid if MCAR                                                ║
║                                                                           ║
║   2. MEAN/MEDIAN IMPUTATION                                               ║
║      • Replace missing with mean or median                               ║
║      • Simple but reduces variance                                       ║
║      • Can bias results                                                  ║
║                                                                           ║
║   3. MULTIPLE IMPUTATION                                                  ║
║      • Create multiple imputed datasets                                  ║
║      • Combine results                                                   ║
║      • Most sophisticated                                                ║
║      • Preferred method                                                  ║
║                                                                           ║
║   4. INDICATOR VARIABLES                                                  ║
║      • Create missing indicator column                                   ║
║      • Include in analysis                                               ║
║      • Useful for MNAR                                                   ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 5.4 Outlier Detection

**Methods:**

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    OUTLIER DETECTION METHODS                             ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║   1. Z-SCORE METHOD                                                       ║
║      • Z = (x - μ) / σ                                                   ║
║      • |Z| > 3 → Outlier                                                 ║
║      • Assumes normality                                                 ║
║      • For symmetric data                                                ║
║                                                                           ║
║   2. IQR METHOD                                                           ║
║      • Q1 - 1.5×IQR (Lower fence)                                        ║
║      • Q3 + 1.5×IQR (Upper fence)                                        ║
║      • Any value outside fences → Outlier                                ║
║      • Robust method                                                     ║
║      • No distribution assumption                                        ║
║                                                                           ║
║   3. VISUALIZATION                                                        ║
║      • Boxplots show outliers                                            ║
║      • Scatter plots show unusual points                                 ║
║      • Histograms show extreme values                                    ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 5.5 Five Number Summary

| Component | Description | Calculation |
|-----------|-------------|-------------|
| **Minimum** | Smallest value | x(1) |
| **Q1** | 25th percentile | (n+1)/4 |
| **Median** | 50th percentile | (n+1)/2 |
| **Q3** | 75th percentile | 3(n+1)/4 |
| **Maximum** | Largest value | x(n) |

**Example: Blood Pressure Data**
```
Min     = 118
Q1      = 121.5
Median  = 126.5
Q3      = 139.5
Max     = 150

IQR = Q3 - Q1 = 139.5 - 121.5 = 18
Range = Max - Min = 150 - 118 = 32
```

### 5.6 Quartiles & Percentiles

> 📖 **Definition**: Quartiles divide data into four equal parts; percentiles divide into 100 equal parts.

**Quartile Division:**
```
┌─────────────────────────────────────────────────────────────────────────┐
│                         QUARTILE DIVISION                              │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│   25%         25%         25%         25%                              │
│  ─────────────────────────────────────────────────────────────────      │
│  │     │     │     │     │     │     │     │     │     │     │         │
│  ─────────────────────────────────────────────────────────────────      │
│                                                                         │
│  Min    Q1         Q2           Q3         Max                         │
│        (25th)     (Median)     (75th)                                  │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 6. Distribution Shape

### 6.1 Distribution Shape

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                    DISTRIBUTION SHAPES                                   ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║   SYMMETRIC                    RIGHT-SKEWED                              ║
║      ┌───┐                        ┌───┐                                 ║
║    ┌───────┐                    ┌───────┐                               ║
║  ┌───────────┐                ┌───────────┐                             ║
║┌───────────────┐            ┌───────────────┐                           ║
║┌───────────────┐          ┌───────────────────┐                         ║
║  ┌───────────┐            ┌───────────────┐                             ║
║    ┌───────┐                ┌───────────┐                               ║
║      ┌───┐                    ┌───────┐                                 ║
║                                                                           ║
║   LEFT-SKEWED                  BIMODAL                                   ║
║      ┌───┐                    ┌───┐  ┌───┐                             ║
║    ┌───────┐                ┌───────┐┌───────┐                         ║
║  ┌───────────┐            ┌───────────┐┌───────────┐                   ║
║┌───────────────┐        ┌───────────────┐┌───────────────┐             ║
║┌───────────────┐        ┌───────────────┐┌───────────────┐             ║
║  ┌───────────┐            ┌───────────┐┌───────────┐                   ║
║    ┌───────┐                ┌───────┐┌───────┐                         ║
║      ┌───┐                    ┌───┐  ┌───┐                             ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 6.2 Symmetry & Skewness

**Symmetric Distribution:**
- Mean = Median = Mode
- Skewness = 0
- Bell curve shape

**Left-Skewed (Negative Skew):**
- Mean < Median < Mode
- Long left tail
- Negative skewness

**Right-Skewed (Positive Skew):**
- Mean > Median > Mode
- Long right tail
- Positive skewness

### 6.3 Kurtosis

> 📖 **Definition**: Kurtosis measures the "tailedness" of a distribution.

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                         KURTOSIS TYPES                                   ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║   LEPTOKURTIC (Heavy Tails)    MESOKURTIC (Normal)                       ║
║   ┌─────┐                      ┌─────┐                                   ║
║   │█████│                      │█████│                                   ║
║   │█████│                      │█████│                                   ║
║   │█████│                      │█████│                                   ║
║   │█████│                      │█████│                                   ║
║   │█████│                      │█████│                                   ║
║   │█████│                      │█████│                                   ║
║                                                                           ║
║   Kurtosis > 3                  Kurtosis = 3                             ║
║                                                                           ║
║   PLATYKURTIC (Light Tails)                                               ║
║   ┌─────┐                                                                ║
║   │█████│                                                                ║
║   │█████│                                                                ║
║   │█████│                                                                ║
║   │█████│                                                                ║
║   │█████│                                                                ║
║   │█████│                                                                ║
║                                                                           ║
║   Kurtosis < 3                                                            ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

### 6.4 Empirical Rule (68-95-99.7 Rule)

> 📖 **Definition**: For a normal distribution, approximately 68-95-99.7% of data fall within 1-2-3 standard deviations.

```
╔═══════════════════════════════════════════════════════════════════════════╗
║                          EMPIRICAL RULE                                  ║
╠═══════════════════════════════════════════════════════════════════════════╣
║                                                                           ║
║                        ┌──────────────────┐                              ║
║                     ┌────────────────────────┐                          ║
║                  ┌──────────────────────────────┐                       ║
║                ┌────────────────────────────────────┐                   ║
║              ┌────────────────────────────────────────┐                 ║
║            ┌────────────────────────────────────────────┐               ║
║                                                                           ║
║   ─────────┼─────────┼─────────┼─────────┼─────────┼─────────┼─────────   ║
║            μ-3σ     μ-2σ     μ-1σ       μ       μ+1σ     μ+2σ     μ+3σ    ║
║                                                                           ║
║       68% within μ ± 1σ                                                   ║
║       95% within μ ± 2σ                                                   ║
║     99.7% within μ ± 3σ                                                   ║
║                                                                           ║
╚═══════════════════════════════════════════════════════════════════════════╝
```

| Range | Percentage |
|-------|------------|
| μ ± 1σ | 68.27% |
| μ ± 2σ | 95.45% |
| μ ± 3σ | 99.73% |

### 6.5 Chebyshev's Theorem

> 📖 **Definition**: For any distribution, at least 1 - 1/k² of data fall within k standard deviations of the mean.

$$ P(|X - \mu| < k\sigma) \geq 1 - \frac{1}{k^2} $$

| k | Minimum % |
|---|-----------|
| 2 | 75% |
| 3 | 88.9% |
| 4 | 93.75% |
| 5 | 96% |

---

## 7. Reporting & Software

### 7.1 Reporting Standards

**Reporting Mean ± SD:**
```
Format: Mean ± SD (n=XX)
Example: Age: 54.3 ± 12.1 years
Guidelines:
• Use for symmetric data
• Include sample size
• Use appropriate precision
```

**Reporting Median (IQR):**
```
Format: Median (IQR)
Example: Length of stay: 5 (3-8) days
Guidelines:
• Use for skewed data
• Include Q1 and Q3
• May include range
```

**Journal Guidelines:**

| Guideline | Application |
|-----------|-------------|
| **CONSORT** | Clinical trials |
| **STROBE** | Observational studies |
| **PRISMA** | Systematic reviews |
| **STARD** | Diagnostic studies |

### 7.2 R Implementation

```r
# Comprehensive descriptive statistics
descriptive_stats <- function(data, variable, group = NULL) {
  
  if (is.null(group)) {
    result <- data %>%
      summarise(
        n = n(),
        mean = mean({{ variable }}, na.rm = TRUE),
        median = median({{ variable }}, na.rm = TRUE),
        sd = sd({{ variable }}, na.rm = TRUE),
        min = min({{ variable }}, na.rm = TRUE),
        max = max({{ variable }}, na.rm = TRUE),
        q1 = quantile({{ variable }}, 0.25, na.rm = TRUE),
        q3 = quantile({{ variable }}, 0.75, na.rm = TRUE),
        iqr = IQR({{ variable }}, na.rm = TRUE),
        skew = e1071::skewness({{ variable }}, na.rm = TRUE),
        kurt = e1071::kurtosis({{ variable }}, na.rm = TRUE)
      )
  } else {
    result <- data %>%
      group_by({{ group }}) %>%
      summarise(
        n = n(),
        mean = mean({{ variable }}, na.rm = TRUE),
        median = median({{ variable }}, na.rm = TRUE),
        sd = sd({{ variable }}, na.rm = TRUE),
        min = min({{ variable }}, na.rm = TRUE),
        max = max({{ variable }}, na.rm = TRUE),
        q1 = quantile({{ variable }}, 0.25, na.rm = TRUE),
        q3 = quantile({{ variable }}, 0.75, na.rm = TRUE),
        iqr = IQR({{ variable }}, na.rm = TRUE),
        skew = e1071::skewness({{ variable }}, na.rm = TRUE),
        kurt = e1071::kurtosis({{ variable }}, na.rm = TRUE)
      )
  }
  return(result)
}

# Example usage
data(iris)
descriptive_stats(iris, Sepal.Length, Species)

# Visualization
ggplot(iris, aes(x = Sepal.Length, fill = Species)) +
  geom_histogram(aes(y = ..density..), bins = 20, alpha = 0.6) +
  geom_density(alpha = 0.3) +
  facet_wrap(~Species) +
  labs(title = "Sepal Length Distribution", x = "Length (cm)") +
  theme_minimal()
```

### 7.3 Python Implementation

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats

def descriptive_stats(data, variable, group=None):
    """Calculate comprehensive descriptive statistics."""
    
    if group is None:
        stats_df = pd.DataFrame({
            'n': [len(data)],
            'mean': [data[variable].mean()],
            'median': [data[variable].median()],
            'std': [data[variable].std()],
            'min': [data[variable].min()],
            'max': [data[variable].max()],
            'q1': [data[variable].quantile(0.25)],
            'q3': [data[variable].quantile(0.75)],
            'iqr': [data[variable].quantile(0.75) - data[variable].quantile(0.25)],
            'skew': [stats.skew(data[variable].dropna())],
            'kurt': [stats.kurtosis(data[variable].dropna())]
        })
    else:
        stats_df = data.groupby(group)[variable].agg([
            ('n', 'count'),
            ('mean', 'mean'),
            ('median', 'median'),
            ('std', 'std'),
            ('min', 'min'),
            ('max', 'max'),
            ('q1', lambda x: x.quantile(0.25)),
            ('q3', lambda x: x.quantile(0.75)),
            ('iqr', lambda x: x.quantile(0.75) - x.quantile(0.25)),
            ('skew', lambda x: stats.skew(x.dropna())),
            ('kurt', lambda x: stats.kurtosis(x.dropna()))
        ])
    return stats_df

# Load data
iris = load_iris()
df = pd.DataFrame(iris.data, columns=iris.feature_names)
df['species'] = iris.target_names[iris.target]

# Calculate statistics
result = descriptive_stats(df, 'sepal length (cm)', 'species')
print(result)

# Visualization
fig, axes = plt.subplots(1, 2, figsize=(12, 5))
sns.boxplot(data=df, x='species', y='sepal length (cm)', ax=axes[0])
sns.violinplot(data=df, x='species', y='sepal length (cm)', ax=axes[1])
plt.tight_layout()
plt.show()
```

---

## 8. Assessment

### 8.1 Worked Example

**Dataset:** Blood pressure (mmHg) from 10 patients
```
118, 122, 130, 145, 119, 125, 138, 128, 121, 150
```

**Step 1: Sort Data**
```
118, 119, 121, 122, 125, 128, 130, 138, 145, 150
```

**Step 2: Calculate Measures**
```
Mean    = 129.6 mmHg
Median  = 126.5 mmHg
Mode    = No mode (all unique)
SD      = 11.4 mmHg
Range   = 32 mmHg
IQR     = 18 mmHg
```

**Step 3: Five-Number Summary**
```
Min     = 118
Q1      = 121.5
Median  = 126.5
Q3      = 139.5
Max     = 150
```

**Step 4: Interpret**
```
The typical blood pressure is approximately 130 mmHg,
with most values between 121.5 and 139.5 mmHg.
The distribution is slightly right-skewed.
```

### 8.2 Practice Questions

<details>
<summary>📝 Click to reveal practice questions</summary>

**MCQs:**

1. Which is NOT a measure of central tendency?
   - A) Mean
   - B) Median
   - C) Range ✓
   - D) Mode

2. The IQR is the difference between:
   - A) Mean and median
   - B) Q3 and Q1 ✓
   - C) Max and min
   - D) Q2 and Q1

3. For right-skewed data:
   - A) Mean < Median
   - B) Mean > Median ✓
   - C) Mean = Median
   - D) Mode > Mean

</details>

### 8.3 Chapter Summary

> 🎯 **Key Takeaways**

1. **Descriptive statistics** summarizes, organizes, and presents data
2. **Choose measures** based on data type and distribution
3. **Visualization** is essential for understanding data
4. **EDA** is critical before any statistical analysis
5. **Report** appropriate measures with proper formatting
6. **Follow** CONSORT/STROBE/PRISMA guidelines
7. **Interpret** descriptively, not causally

### 8.4 Formula Sheet

| Measure | Formula | Use |
|---------|---------|-----|
| **Mean** | $\bar{x} = \frac{\sum x}{n}$ | Symmetric data |
| **Variance** | $s^2 = \frac{\sum(x-\bar{x})^2}{n-1}$ | Data spread |
| **SD** | $s = \sqrt{s^2}$ | Data spread |
| **CV** | $CV = \frac{s}{\bar{x}} \times 100\%$ | Relative variation |
| **Skewness** | $g_1 = \frac{\sum(x-\bar{x})^3/n}{s^3}$ | Distribution shape |
| **Kurtosis** | $g_2 = \frac{\sum(x-\bar{x})^4/n}{s^4} - 3$ | Tail behavior |

---

**[⬅ Previous: Repository Home](../README.md) · [🏠 Back to Repository](../README.md) · [➡ Next: Chapter 2 - Measures of Central Tendency](./02-central-tendency.md)**
