

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
- [2.5 Raw Data](#25-raw-data)
- [2.6 Ordered Data](#26-ordered-data)

### 3. Frequency Distributions
- [3.1 Frequency Distribution](#31-frequency-distribution)
- [3.2 Relative Frequency](#32-relative-frequency)
- [3.3 Cumulative Frequency](#33-cumulative-frequency)
- [3.4 Frequency Tables](#34-frequency-tables)
- [3.5 Grouped Data](#35-grouped-data)
- [3.6 Ungrouped Data](#36-ungrouped-data)
- [3.7 Class Intervals](#37-class-intervals)
- [3.8 Class Boundaries](#38-class-boundaries)
- [3.9 Class Midpoints](#39-class-midpoints)

### 4. Data Visualization
- [4.1 Histograms](#41-histograms)
- [4.2 Frequency Polygon](#42-frequency-polygon)
- [4.3 Ogive](#43-ogive)
- [4.4 Bar Chart](#44-bar-chart)
- [4.5 Pie Chart](#45-pie-chart)
- [4.6 Line Graph](#46-line-graph)
- [4.7 Stem-and-Leaf Plot](#47-stem-and-leaf-plot)
- [4.8 Dot Plot](#48-dot-plot)
- [4.9 Box Plot](#49-box-plot)
- [4.10 Scatter Plot](#410-scatter-plot)

### 5. Exploratory Data Analysis
- [5.1 Exploratory Data Analysis (EDA)](#51-exploratory-data-analysis-eda)
- [5.2 Data Cleaning](#52-data-cleaning)
- [5.3 Missing Data](#53-missing-data)
- [5.4 Outlier Detection](#54-outlier-detection)
- [5.5 Five Number Summary](#55-five-number-summary)
- [5.6 Quartiles](#56-quartiles)
- [5.7 Percentiles](#57-percentiles)

### 6. Distribution Shape
- [6.1 Distribution Shape](#61-distribution-shape)
- [6.2 Symmetry](#62-symmetry)
- [6.3 Left Skewness](#63-left-skewness)
- [6.4 Right Skewness](#64-right-skewness)
- [6.5 Kurtosis](#65-kurtosis)
- [6.6 Empirical Rule](#66-empirical-rule)
- [6.7 Chebyshev's Theorem](#67-chebyshevs-theorem)

### 7. Data Presentation & Reporting
- [7.1 Data Summarization](#71-data-summarization)
- [7.2 Tabular Presentation](#72-tabular-presentation)
- [7.3 Reporting Mean ± SD](#73-reporting-mean--sd)
- [7.4 Reporting Median (IQR)](#74-reporting-median-iqr)
- [7.5 Journal Reporting Standards](#75-journal-reporting-standards)

### 8. Software Implementation
- [8.1 R Implementation](#81-r-implementation)
- [8.2 Python Implementation](#82-python-implementation)
- [8.3 SPSS Implementation](#83-spss-implementation)
- [8.4 STATA Implementation](#84-stata-implementation)
- [8.5 SAS Implementation](#85-sas-implementation)
- [8.6 Excel Implementation](#86-excel-implementation)

### 9. Assessment & Summary
- [9.1 Worked Example](#91-worked-example)
- [9.2 Practice Questions](#92-practice-questions)
- [9.3 MCQs](#93-mcqs)
- [9.4 Chapter Summary](#94-chapter-summary)
- [9.5 Formula Sheet](#95-formula-sheet)

</details>

---

## 1. Fundamentals

### 1.1 What is Descriptive Statistics?

> 📖 **Definition**: Descriptive statistics is the branch of statistics that deals with summarizing, organizing, and presenting data in a meaningful way.

Descriptive statistics serves as the foundation of all statistical analysis. While inferential statistics draws conclusions about populations from samples, descriptive statistics simply describes the data at hand.

**Key Functions:**

```
┌─────────────────────────────────────────────────────────────────┐
│                    DESCRIPTIVE STATISTICS                       │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐             │
│  │  SUMMARIZE  │  │  ORGANIZE   │  │  VISUALIZE  │             │
│  ├─────────────┤  ├─────────────┤  ├─────────────┤             │
│  │ • Mean      │  │ • Frequency │  │ • Graphs    │             │
│  │ • Median    │  │ • Tables    │  │ • Charts    │             │
│  │ • Mode      │  │ • Groups    │  │ • Plots     │             │
│  │ • SD        │  │ • Classes   │  │ • Maps      │             │
│  │ • Range     │  │ • Bins      │  │ • Heatmaps  │             │
│  └─────────────┘  └─────────────┘  └─────────────┘             │
│                                                                 │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │                    DISCOVER PATTERNS                     │   │
│  ├─────────────────────────────────────────────────────────┤   │
│  │ • Trends    • Outliers    • Relationships    • Gaps     │   │
│  └─────────────────────────────────────────────────────────┘   │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### 1.2 Historical Background

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    HISTORICAL DEVELOPMENT TIMELINE                          │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│  3000 BCE                         1600s CE                   1800s CE       │
│      │                               │                         │            │
│  ┌───▼───┐                      ┌───▼───┐                 ┌───▼───┐        │
│  │Ancient│                      │Graunt│                 │Gauss │        │
│  │Census │                      │Petty │                 │Laplace│        │
│  └───────┘                      └───────┘                 └───────┘        │
│                                                                             │
│  1880s CE                          1900s CE                   2000s CE      │
│      │                               │                         │            │
│  ┌───▼───┐                      ┌───▼───┐                 ┌───▼───┐        │
│  │Galton │                      │Fisher │                 │Big    │        │
│  │Pearson│                      │Tukey  │                 │Data   │        │
│  └───────┘                      └───────┘                 └───────┘        │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 1.3 Evolution of Descriptive Statistics

| Period | Key Developments | Major Contributors |
|--------|-----------------|-------------------|
| **Ancient** (3000 BCE - 500 CE) | Census data, population records | Babylonians, Egyptians, Romans |
| **Renaissance** (1500s-1700s) | Political arithmetic, life tables | John Graunt, William Petty |
| **Enlightenment** (1700s-1800s) | Normal distribution, least squares | Gauss, Laplace, de Moivre |
| **Modern** (1800s-1900s) | Correlation, regression, EDA | Galton, Pearson, Fisher, Tukey |
| **Digital Age** (1900s-Present) | Computational statistics, ML | Modern statisticians |

### 1.4 Importance in Science

| Scientific Area | Role of Descriptive Statistics |
|----------------|-------------------------------|
| **Biology** | Summarizing measurements, characterizing populations |
| **Physics** | Describing measurement distributions, error analysis |
| **Chemistry** | Characterizing samples, quality control |
| **Environmental Science** | Summarizing pollution levels, climate data |
| **Social Sciences** | Describing survey responses, demographic data |
| **Astronomy** | Summarizing observations, characterizing celestial objects |

### 1.5 Importance in Medical Research

| Application | Example |
|------------|---------|
| **Clinical Trials** | Baseline characteristics, treatment effects |
| **Observational Studies** | Patient demographics, risk factor distributions |
| **Diagnostic Testing** | Reference ranges, test characteristics |
| **Drug Development** | Safety profiles, efficacy measures |
| **Epidemiology** | Disease incidence, prevalence rates |
| **Survival Analysis** | Median survival, event frequencies |

### 1.6 Importance in Public Health

> [!TIP]
> *Descriptive statistics is the cornerstone of public health surveillance, monitoring, and response.*

**Key Applications:**
- **Disease Surveillance**: Tracking incidence and prevalence
- **Health Indicators**: Monitoring population health
- **Health Disparities**: Identifying vulnerable populations
- **Resource Allocation**: Informing public health decisions
- **Epidemic Response**: Characterizing outbreak patterns
- **DHS Surveys**: National health indicators

### 1.7 Importance in Machine Learning

| ML Task | Role of Descriptive Statistics |
|---------|-------------------------------|
| **Data Preprocessing** | Understanding distributions, handling missing values |
| **Feature Engineering** | Scaling, normalization, transformations |
| **Model Selection** | Understanding data characteristics |
| **Evaluation** | Performance metrics interpretation |
| **Feature Importance** | Understanding variable relationships |
| **EDA** | Discovering patterns, outliers |

### 1.8 Importance in AI

> 🤖 *"Descriptive statistics provides the foundation for AI systems to understand the data they are learning from."*

**AI Applications:**
- **Data Understanding**: Characterizing training data
- **Bias Detection**: Identifying biases in datasets
- **Model Validation**: Ensuring data quality
- **Explainable AI**: Understanding data distributions
- **Automated ML**: Feature selection and preprocessing
- **Evaluation**: Understanding model performance

### 1.9 Types of Descriptive Statistics

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    TYPES OF DESCRIPTIVE STATISTICS                          │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│  1. CENTRAL TENDENCY          2. DISPERSION                                │
│  ┌────────────────────────┐   ┌────────────────────────┐                   │
│  │  Mean    Average value  │   │  Range   Max - Min     │                   │
│  │  Median  Middle value   │   │  IQR     Q3 - Q1       │                   │
│  │  Mode    Most frequent  │   │  Variance  Spread²     │                   │
│  │                          │   │  SD       √Variance    │                   │
│  └────────────────────────┘   └────────────────────────┘                   │
│                                                                             │
│  3. DISTRIBUTION SHAPE        4. RELATIONSHIP                              │
│  ┌────────────────────────┐   ┌────────────────────────┐                   │
│  │  Symmetry  Balanced     │   │  Correlation  Strength │                   │
│  │  Skewness  Tails        │   │  Covariance   Co-vary  │                   │
│  │  Kurtosis  Peakedness   │   │  Contingency  Tables  │                   │
│  └────────────────────────┘   └────────────────────────┘                   │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## 2. Data Fundamentals

### 2.1 Population vs Sample Summary

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    POPULATION VS SAMPLE                                     │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│                         POPULATION                                          │
│                    ┌───────────────────┐                                    │
│                    │   All Subjects    │                                    │
│                    │    of Interest    │                                    │
│                    │                   │                                    │
│                    │   N = 10,000      │                                    │
│                    │   Parameter: μ    │                                    │
│                    │   Greek Notation  │                                    │
│                    └───────────────────┘                                    │
│                             │                                               │
│                             │ SAMPLE                                        │
│                             ▼                                               │
│                    ┌───────────────────┐                                    │
│                    │   Subset of the   │                                    │
│                    │    Population     │                                    │
│                    │                   │                                    │
│                    │   n = 100         │                                    │
│                    │   Statistic: x̄    │                                    │
│                    │   Roman Notation  │                                    │
│                    └───────────────────┘                                    │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

| Aspect | Population | Sample |
|--------|-----------|--------|
| **Definition** | Entire group of interest | Subset of population |
| **Size** | N | n |
| **Parameter** | μ, σ, ρ | Statistic |
| **Notation** | Greek | Roman |
| **Access** | Often unknown | Known |
| **Cost** | Expensive | Feasible |
| **Time** | Time-consuming | Faster |

### 2.2 Data Types

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         DATA TYPES HIERARCHY                               │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│                               DATA                                          │
│                                 │                                           │
│                ┌────────────────┼────────────────┐                         │
│                │                │                │                         │
│                ▼                ▼                ▼                         │
│         QUANTITATIVE     CATEGORICAL       OTHER                           │
│         (Numerical)      (Groups)                                          │
│                │                │                                           │
│     ┌──────────┼──────────┐     │                                          │
│     │          │          │     │                                          │
│     ▼          ▼          ▼     ▼                                          │
│  DISCRETE  CONTINUOUS   ORDINAL  NOMINAL                                   │
│  (Counts)   (Measured)  (Ranked) (Unordered)                              │
│                                                                             │
│  Examples:   Examples:   Examples:  Examples:                              │
│  Children    Height      Severity   Gender                                 │
│  Patients    Weight      Education  Blood Group                            │
│  Visits      BP          Stage      Religion                               │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 2.3 Variables

> 📖 **Definition**: A **variable** is any characteristic, attribute, or measurable property that can take different values across individuals, objects, places, or observations. Variables form the foundation of statistical analysis because every statistical method is ultimately designed to summarize, compare, or model variables.

**Variable Classification:**

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         VARIABLE CLASSIFICATION                            │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   ┌─────────────────────────────────────────────────────────────────────┐   │
│   │                    VARIABLE                                         │   │
│   └─────────────────────────────────────────────────────────────────────┘   │
│                                    │                                       │
│           ┌────────────────────────┼────────────────────────┐              │
│           │                        │                        │              │
│           ▼                        ▼                        ▼              │
│   ┌───────────────┐        ┌───────────────┐        ┌───────────────┐     │
│   │  QUANTITATIVE │        │  CATEGORICAL  │        │  OTHER TYPES  │     │
│   │   Variables   │        │   Variables   │        │               │     │
│   ├───────────────┤        ├───────────────┤        ├───────────────┤     │
│   │ • Height      │        │ • Gender      │        │ • Confounder  │     │
│   │ • Weight      │        │ • Blood Group │        │ • Mediator    │     │
│   │ • Age         │        │ • Religion    │        │ • Moderator   │     │
│   │ • Income      │        │ • Education   │        │ • Control     │     │
│   └───────────────┘        └───────────────┘        └───────────────┘     │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

**Real Research Example:**

| Research Question | Variable | Type |
|-------------------|----------|------|
| Does physical activity reduce blood pressure? | Physical Activity | Independent |
| | Blood Pressure | Dependent |
| | Age | Confounder |
| | Sex | Control |
| | BMI | Covariate |

### 2.4 Measurement Scales

> 📖 **Definition**: A **measurement scale** defines the way a variable is observed, categorized, or quantified. It determines the mathematical operations that can be performed on the data and guides the selection of appropriate statistical methods.

**The Four Levels of Measurement:**

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    HIERARCHY OF MEASUREMENT SCALES                         │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│                     Increasing Information                                 │
│                  ─────────────────────────▶                                 │
│                                                                             │
│   ┌─────────────┐    ┌─────────────┐    ┌─────────────┐    ┌─────────────┐ │
│   │   NOMINAL   │    │   ORDINAL   │    │  INTERVAL   │    │    RATIO    │ │
│   │   Scale     │    │   Scale     │    │   Scale     │    │   Scale     │ │
│   ├─────────────┤    ├─────────────┤    ├─────────────┤    ├─────────────┤ │
│   │ Categories  │    │ Categories  │    │ Equal       │    │ Equal       │ │
│   │ No Order    │    │ With Order  │    │ Intervals   │    │ Intervals   │ │
│   │ Labels      │    │ Rankings    │    │ No True Zero│    │ True Zero   │ │
│   │ =, ≠        │    │ <, >        │    │ +, −        │    │ ×, ÷        │ │
│   ├─────────────┤    ├─────────────┤    ├─────────────┤    ├─────────────┤ │
│   │ Blood Group │    │ Pain Score  │    │ Temperature │    │ Height      │ │
│   │ Gender      │    │ Cancer Stage│    │ IQ Score    │    │ Weight      │ │
│   │ Religion    │    │ Education   │    │ Calendar    │    │ Age         │ │
│   └─────────────┘    └─────────────┘    └─────────────┘    └─────────────┘ │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

| Scale | Definition | Characteristics | Operations | Examples |
|-------|------------|-----------------|------------|----------|
| **Nominal** | Categories without order | Labels only | =, ≠ | Blood group, Gender |
| **Ordinal** | Categories with order | Rankings | =, ≠, <, > | Pain severity, Education |
| **Interval** | Equal intervals, no true zero | Equal distances | +, − | Temperature (°C), IQ |
| **Ratio** | Equal intervals, true zero | All operations | +, −, ×, ÷ | Height, Weight, Age |

### 2.5 Raw Data

> 📖 **Definition**: Raw data are unprocessed, original observations collected from a study or experiment.

**Characteristics:**
- Unprocessed
- Original form
- Contains all observations
- May include errors
- Requires cleaning

**Example:**
```
Raw Data: 78, 92, 85, 67, 89, 73, 94, 81, 76, 88
```

### 2.6 Ordered Data

> 📖 **Definition**: Ordered data are observations arranged in ascending order.

**Example:**
```
Raw Data: 78, 92, 85, 67, 89, 73, 94, 81, 76, 88
Ordered: 67, 73, 76, 78, 81, 85, 88, 89, 92, 94
```

**Benefits:**
- Easy to find minimum/maximum
- Facilitates median calculation
- Enables percentile computation
- Provides distribution insight

---

## 3. Frequency Distributions

### 3.1 Frequency Distribution

> 📖 **Definition**: A **frequency distribution** is a systematic arrangement of data that displays the number of observations (frequencies) corresponding to each value or class interval.

**General Structure:**

```
┌─────────────────────────────────────────────────────────────────┐
│                    FREQUENCY DISTRIBUTION                       │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   Value/Class    │    Frequency    │    Relative    │ Cumulative │
│                  │                 │    Frequency   │  Frequency │
│  ────────────────┼─────────────────┼────────────────┼────────────│
│   Category A     │        15       │      0.30      │     15     │
│   Category B     │        22       │      0.44      │     37     │
│   Category C     │        18       │      0.36      │     55     │
│   Category D     │        10       │      0.20      │     65     │
│                  │                 │                │            │
│   Total          │        65       │      1.30*     │     65     │
│                                                                 │
│   *Sum may exceed 1 due to rounding                            │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### 3.2 Relative Frequency

> 📖 **Definition**: Relative frequency represents the proportion of observations belonging to each category relative to the total sample size.

**Formula:**
$$ \text{Relative Frequency} = \frac{\text{Frequency}}{\text{Total Number of Observations}} $$

**Example:**
```
If 15 out of 65 people have blood type O+:
Relative Frequency = 15/65 = 0.231 = 23.1%
```

### 3.3 Cumulative Frequency

> 📖 **Definition**: Cumulative frequency represents the running total of frequencies as observations accumulate from one class to the next.

**Formula:**
$$ \text{Cumulative Frequency} = \sum_{i=1}^{k} f_i $$

**Example:**
```
┌─────────────────────────────────────────────────────────────────┐
│                    CUMULATIVE FREQUENCY                         │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   Score Range   │   Frequency   │   Cumulative   │    %        │
│                  │               │                │             │
│   0-59          │      5        │       5        │   8.3%      │
│   60-69         │      8        │      13        │  21.7%      │
│   70-79         │     12        │      25        │  41.7%      │
│   80-89         │     18        │      43        │  71.7%      │
│   90-100        │     17        │      60        │ 100.0%      │
│                  │               │                │             │
│   Total         │     60        │      60        │             │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

**Interpretation:**
- 25 students (41.7%) scored below 80
- 43 students (71.7%) scored below 90
- All 60 students scored below 100

### 3.4 Frequency Tables

**Complete Example: Blood Types (n=100)**

| Blood Type | Frequency | Relative Frequency | Percentage | Cumulative Frequency |
|------------|----------:|-------------------:|-----------:|---------------------:|
| O+ | 35 | 0.35 | 35% | 35 |
| A+ | 28 | 0.28 | 28% | 63 |
| B+ | 18 | 0.18 | 18% | 81 |
| AB+ | 12 | 0.12 | 12% | 93 |
| O- | 4 | 0.04 | 4% | 97 |
| A- | 2 | 0.02 | 2% | 99 |
| B- | 1 | 0.01 | 1% | 100 |
| **Total** | **100** | **1.00** | **100%** | |

**Interpretation:**
- O+ is the most common blood group (35%)
- 63% of participants are either O+ or A+
- Only 7% have Rh-negative blood

### 3.5 Grouped Data

> 📖 **Definition**: **Grouped data** are observations organized into class intervals rather than reported individually.

**Example: Age Distribution**

```
┌─────────────────────────────────────────────────────────────────┐
│                    GROUPED FREQUENCY TABLE                      │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   Age Group    │   Frequency   │   Percentage   │  Cumulative  │
│   (Years)      │               │                │              │
│  ──────────────┼───────────────┼────────────────┼──────────────│
│   20-29        │      18       │     15.0%      │     18       │
│   30-39        │      42       │     35.0%      │     60       │
│   40-49        │      56       │     46.7%      │    116       │
│   50-59        │      48       │     40.0%      │    164       │
│   60-69        │      36       │     30.0%      │    200       │
│                │               │                │              │
│   Total        │     200       │    100.0%      │             │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### 3.6 Ungrouped Data

> 📖 **Definition**: **Ungrouped data** consist of individual observations presented in their original form without classification into intervals.

**Example: Number of Siblings**

| Siblings | Frequency | Relative | Cumulative |
|----------|----------:|---------:|-----------:|
| 0 | 8 | 0.27 | 8 |
| 1 | 12 | 0.40 | 20 |
| 2 | 6 | 0.20 | 26 |
| 3 | 3 | 0.10 | 29 |
| 4 | 1 | 0.03 | 30 |
| **Total** | **30** | **1.00** | |

### 3.7 Class Intervals

> 📖 **Definition**: A **class interval** is the range of values used to group continuous observations into meaningful categories.

**Choosing Class Intervals:**

```
┌─────────────────────────────────────────────────────────────────┐
│                    CLASS INTERVAL GUIDELINES                    │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   Step 1: Find Range                                            │
│   Range = Maximum - Minimum                                     │
│   Example: 98 - 45 = 53                                         │
│                                                                 │
│   Step 2: Choose Number of Classes                              │
│   Sturges' Rule: k = 1 + 3.322 × log₁₀(n)                      │
│   For n = 30: k = 1 + 3.322 × 1.477 = 5.91 ≈ 6                │
│                                                                 │
│   Step 3: Calculate Class Width                                 │
│   Class Width = Range / Number of Classes                      │
│   53 / 6 = 8.83 ≈ 9                                            │
│                                                                 │
│   Step 4: Create Intervals                                      │
│   40-48, 49-57, 58-66, 67-75, 76-84, 85-93, 94-102            │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### 3.8 Class Boundaries

> 📖 **Definition**: **Class boundaries** represent the true limits separating adjacent class intervals by eliminating any gaps between them.

**Example:**

```
┌─────────────────────────────────────────────────────────────────┐
│                    CLASS BOUNDARIES                             │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   Class Interval    │   Lower Boundary   │   Upper Boundary    │
│  ──────────────────┼────────────────────┼─────────────────────│
│   20-29             │       19.5         │       29.5          │
│   30-39             │       29.5         │       39.5          │
│   40-49             │       39.5         │       49.5          │
│   50-59             │       49.5         │       59.5          │
│                                                                 │
│   Formula:                                                      │
│   Lower Boundary = Lower Limit - 0.5                           │
│   Upper Boundary = Upper Limit + 0.5                           │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

### 3.9 Class Midpoints

> 📖 **Definition**: The class midpoint represents the center of each class interval.

**Formula:**
$$ \text{Class Midpoint} = \frac{\text{Lower Class Limit} + \text{Upper Class Limit}}{2} $$

**Example:**

| Class Interval | Midpoint Calculation | Midpoint |
|---------------|---------------------|---------:|
| 20-29 | (20+29)/2 | 24.5 |
| 30-39 | (30+39)/2 | 34.5 |
| 40-49 | (40+49)/2 | 44.5 |
| 50-59 | (50+59)/2 | 54.5 |

---

## 4. Data Visualization

### 4.1 Histograms

> 📖 **Definition**: A **histogram** is a graphical display of the frequency distribution of a continuous numerical variable. Unlike a bar chart, histogram bars are **adjacent**, indicating continuous data.

**Histogram Shapes:**

```
SYMMETRIC (Normal)              RIGHT-SKEWED
        █                          ██████████
      █████                        ████████
    █████████                      ██████
  █████████████                   █████
█████████████████                 ████
  █████████████                   ███
    █████████                     ██
      █████                       █
        █


LEFT-SKEWED                     BIMODAL
        █                        ███
      █████                    ████████
    █████████                  ██████████
  █████████████                ████  ████
█████████████████              ██     ██
  █████████████               █       █
    █████████
      █████
        █


UNIFORM
████████████
████████████
████████████
████████████
████████████
```

### 4.2 Frequency Polygon

> 📖 **Definition**: A **frequency polygon** is a line graph constructed by plotting the **class midpoints** on the x-axis against their corresponding **frequencies** on the y-axis and connecting the points with straight lines.

```
FREQUENCY POLYGON
Frequency

12 |                 ●
11 |               /   \
10 |             ●       ●
 9 |            /         \
 8 |          ●             ●
 7 |         /               \
 6 |       ●                  ●
 5 |      /                    \
 4 |    ●                       ●
 3 |
 2 |
 1 |
    ----------------------------------------
      10   20   30   40   50   60   70
            Class Midpoints

Key Features:
• Points at class midpoints
• Lines connect points
• Starts and ends at baseline
• Shows distribution trend
```

### 4.3 Ogive (Cumulative Frequency Curve)

> 📖 **Definition**: An **ogive**, also known as a **cumulative frequency curve**, is a line graph that displays the cumulative frequency of a dataset across class intervals.

```
OGIVE (Cumulative Frequency Curve)
Cumulative Frequency

40 |                              ●
35 |                           ●
30 |                        ●
25 |                     ●
20 |                  ●
15 |               ●
10 |            ●
 5 |         ●
 0 |____●__________________________________
      20   30   40   50   60   70
        Upper Class Boundaries

Key Features:
• Uses upper class boundaries
• Always increases
• Starts at 0
• Ends at total n
• Used for percentiles
```

### 4.4 Bar Chart

> 📖 **Definition**: A **bar chart** (or **bar graph**) is a graphical representation of **categorical data** using rectangular bars of equal width. Unlike histograms, **bars are separated by gaps**.

```
BAR CHART
Frequency

10 |           ███
 9 |           ███
 8 |     ███   ███
 7 |     ███   ███
 6 |     ███   ███
 5 | ███ ███   ███
 4 | ███ ███   ███
 3 | ███ ███ ████
 2 | ███ ███ ████
 1 | ███ ███ ████
    -------------------------
      A    B    C    D
        Categories

Key Features:
• Equal width bars
• Gaps between bars
• Categorical data
• Easy to compare
```

### 4.5 Pie Chart

> 📖 **Definition**: A pie chart is a circular graph showing proportions of a whole.

```
PIE CHART

        ████████
      ██        ██
     █    O+    █
    █   35%     █
   █   ███████████
   █ ██         ███
   ███            █
   █ B+   ██████  █
   █ 18%  █    █ █
    █     █ AB+ █
     █    █12% █
      ██  ███ ██
        ██████
```

### 4.6 Line Graph

> 📖 **Definition**: A line graph displays data points connected by straight lines.

```
LINE GRAPH
Value

10 |     ●
 9 |    / \       ●
 8 |   /   \     / \
 7 |  /     \   /   \
 6 | /       \ /     \
 5 |●         ●       ●
 4 |
 3 |
 2 |
 1 |
    -------------------------
      1    2    3    4    5
            Time Points

Use Cases:
• Time series data
• Trends over time
• Comparing changes
```

### 4.7 Stem-and-Leaf Plot

> 📖 **Definition**: A stem-and-leaf plot retains original data values while showing distribution.

**Example: Test Scores**
```
Stem | Leaf
  4  | 5
  5  | 2 8
  6  | 1 3 7 8
  7  | 0 2 3 4 5 6 7 8 9
  8  | 0 1 2 3 4 5 6 7 8 9
  9  | 0 2 4 8

Data: 45, 52, 58, 61, 63, 67, 68, 70, 72, 73, 74, 75, 76, 77, 78, 79,
      80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 92, 94, 98
```

### 4.8 Dot Plot

> 📖 **Definition**: A dot plot uses dots on a simple scale to show data distribution.

```
DOT PLOT

Value: 1 2 3 4 5 6 7 8 9 10
          ●
          ●
          ● ●
        ● ● ● ●
      ● ● ● ● ●
    ● ● ● ● ● ● ●
  ● ● ● ● ● ● ● ● ●

Characteristics:
• One dot per observation
• Stacked dots for repeated values
• Good for small datasets
```

### 4.9 Box Plot

> 📖 **Definition**: A box plot displays the five-number summary of data.

```
BOX PLOT

     Outlier
         ●
      ──────
      │     │
      │     │
      │     │ ← Upper Fence
      ──────
      │ ███ │
      │ ███ │ ← Q3 (75%)
      │ ███ │
      │█████│
      │█████│ ← Median (50%)
      │ ███ │
      │ ███ │
      │ ███ │
      ──────
      │     │ ← Q1 (25%)
      │     │
      │     │
      ──────
      │     │ ← Lower Fence
         ●
         Outlier

Components:
• Box: IQR (Q1 to Q3)
• Line: Median
• Whiskers: 1.5 × IQR
• Points: Outliers
```

### 4.10 Scatter Plot

> 📖 **Definition**: A scatter plot shows the relationship between two quantitative variables.

```
SCATTER PLOT
Y
│
│     ●
│   ●   ●
│ ●     ●
│●       ●
│         ●
│           ●
│             ●
│               ●
│                 ●
└──────────────────── X
                     
Correlation Patterns:
• Positive: Points go up-right
• Negative: Points go down-right
• No correlation: Random scatter
• Strong: Points close to line
• Weak: Points spread out
```

---

## 5. Exploratory Data Analysis

### 5.1 Exploratory Data Analysis (EDA)

> 📖 **Definition**: EDA is an approach to analyzing datasets to summarize their main characteristics, often with visual methods.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         EDA WORKFLOW                                       │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   ┌─────────────┐                                                          │
│   │   Data      │                                                          │
│   │ Collection  │                                                          │
│   └──────┬──────┘                                                          │
│          │                                                                  │
│          ▼                                                                  │
│   ┌─────────────┐                                                          │
│   │    Data     │                                                          │
│   │   Cleaning  │                                                          │
│   └──────┬──────┘                                                          │
│          │                                                                  │
│          ▼                                                                  │
│   ┌─────────────┐                                                          │
│   │  Univariate │                                                          │
│   │  Analysis   │                                                          │
│   └──────┬──────┘                                                          │
│          │                                                                  │
│          ▼                                                                  │
│   ┌─────────────┐                                                          │
│   │  Bivariate  │                                                          │
│   │  Analysis   │                                                          │
│   └──────┬──────┘                                                          │
│          │                                                                  │
│          ▼                                                                  │
│   ┌─────────────┐                                                          │
│   │  Multivari- │                                                          │
│   │  ate        │                                                          │
│   └──────┬──────┘                                                          │
│          │                                                                  │
│          ▼                                                                  │
│   ┌─────────────┐                                                          │
│   │   Pattern   │                                                          │
│   │  Discovery  │                                                          │
│   └─────────────┘                                                          │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 5.2 Data Cleaning

**Common Issues:**

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         DATA CLEANING CHECKLIST                            │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   ❌ Missing Values          → Impute or remove                            │
│   ❌ Duplicate Records       → Remove duplicates                           │
│   ❌ Inconsistent Formats    → Standardize formats                        │
│   ❌ Outliers                → Investigate and handle                     │
│   ❌ Data Entry Errors       → Correct or remove                          │
│   ❌ Incomplete Responses    → Review and handle                         │
│   ❌ Incorrect Coding        → Recode correctly                          │
│   ❌ Impossible Values       → Investigate (e.g., age = 200)             │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 5.3 Missing Data

**Types:**
- **MCAR**: Missing Completely at Random
- **MAR**: Missing at Random
- **MNAR**: Missing Not at Random

**Handling Methods:**

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    MISSING DATA HANDLING METHODS                           │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   1. LISTWISE DELETION                                                      │
│      • Remove all cases with missing values                                │
│      • Simple but reduces sample size                                      │
│      • Only valid if MCAR                                                  │
│                                                                             │
│   2. MEAN/MEDIAN IMPUTATION                                                 │
│      • Replace missing with mean or median                                 │
│      • Simple but reduces variance                                         │
│      • Can bias results                                                    │
│                                                                             │
│   3. MULTIPLE IMPUTATION                                                    │
│      • Create multiple imputed datasets                                    │
│      • Combine results                                                     │
│      • Most sophisticated                                                 │
│      • Preferred method                                                    │
│                                                                             │
│   4. INDICATOR VARIABLES                                                    │
│      • Create missing indicator column                                     │
│      • Include in analysis                                                 │
│      • Useful for missing not at random                                   │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 5.4 Outlier Detection

**Methods:**

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    OUTLIER DETECTION METHODS                               │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   1. Z-SCORE METHOD                                                         │
│      • Z = (x - μ) / σ                                                     │
│      • |Z| > 3 → Outlier                                                   │
│      • Assumes normality                                                   │
│      • For symmetric data                                                  │
│                                                                             │
│   2. IQR METHOD                                                             │
│      • Q1 - 1.5×IQR (Lower fence)                                          │
│      • Q3 + 1.5×IQR (Upper fence)                                          │
│      • Any value outside fences → Outlier                                  │
│      • Robust method                                                       │
│      • No distribution assumption                                          │
│                                                                             │
│   3. VISUALIZATION                                                          │
│      • Boxplots show outliers                                              │
│      • Scatter plots show unusual points                                   │
│      • Histograms show extreme values                                      │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
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
Min = 118
Q1  = 121.5
Median = 126.5
Q3  = 139.5
Max = 150

IQR = Q3 - Q1 = 139.5 - 121.5 = 18
Range = Max - Min = 150 - 118 = 32
```

### 5.6 Quartiles

> 📖 **Definition**: Quartiles divide data into four equal parts.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         QUARTILE DIVISION                                  │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   Data: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12                            │
│                                                                             │
│   Q1 = 3.5 (25th percentile)                                               │
│   Q2 = 6.5 (50th percentile = Median)                                      │
│   Q3 = 9.5 (75th percentile)                                               │
│                                                                             │
│   ─────────────────────────────────────────────────────────────────         │
│   25%    │    25%    │    25%    │    25%                                  │
│   Q1     │    Q2     │    Q3     │                                         │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 5.7 Percentiles

> 📖 **Definition**: Percentiles divide data into 100 equal parts.

**Interpretation:**
- 50th percentile = Median
- 25th percentile = Q1
- 75th percentile = Q3

**Example:**
```
If a test score is at the 80th percentile:
- 80% of students scored lower
- 20% scored higher
- The score is above average
```

---

## 6. Distribution Shape

### 6.1 Distribution Shape

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                    DISTRIBUTION SHAPES                                     │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   SYMMETRIC                    RIGHT-SKEWED                                │
│        █                          █                                        │
│      █████                      ████                                       │
│    █████████                  ███████                                      │
│  █████████████              ██████████                                    │
│█████████████████          ██████████████                                  │
│  █████████████              ██████████                                    │
│    █████████                  ██████                                       │
│      █████                      ███                                        │
│        █                         █                                         │
│                                                                             │
│   LEFT-SKEWED                  BIMODAL                                     │
│        █                        ███                                        │
│      █████                    ███████                                      │
│    █████████                  █████████                                   │
│  █████████████                █████████                                   │
│█████████████████              █████████                                   │
│  █████████████                █████████                                   │
│    █████████                  █████████                                   │
│      █████                      ███                                        │
│        █                         █                                         │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 6.2 Symmetry

> 📖 **Definition**: A distribution is symmetric if it is identical on both sides of its center.

**Properties:**
- Mean = Median = Mode
- Skewness = 0
- Bell curve shape

### 6.3 Left Skewness

> 📖 **Definition**: Left skewness occurs when the left tail is longer than the right tail.

**Properties:**
- Mean < Median < Mode
- Long left tail
- Negative skewness

### 6.4 Right Skewness

> 📖 **Definition**: Right skewness occurs when the right tail is longer than the left tail.

**Properties:**
- Mean > Median > Mode
- Long right tail
- Positive skewness

### 6.5 Kurtosis

> 📖 **Definition**: Kurtosis measures the "tailedness" of a probability distribution.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                         KURTOSIS TYPES                                     │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│   LEPTOKURTIC (Heavy Tails)    MESOKURTIC (Normal)                         │
│   ██████                        █████                                       │
│   ██████                        █████                                       │
│   ██████                        █████                                       │
│   ██████                        █████                                       │
│   ██████                        █████                                       │
│   ██████                        █████                                       │
│                                                                             │
│   Kurtosis > 3                  Kurtosis = 3                               │
│                                                                             │
│   PLATYKURTIC (Light Tails)                                                │
│   ██████                                                                   │
│   ██████                                                                   │
│   ██████                                                                   │
│   ██████                                                                   │
│   ██████                                                                   │
│   ██████                                                                   │
│                                                                             │
│   Kurtosis < 3                                                             │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

### 6.6 Empirical Rule (68-95-99.7 Rule)

> 📖 **Definition**: For a normal distribution, approximately 68-95-99.7% of data fall within 1-2-3 standard deviations.

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                          EMPIRICAL RULE                                    │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                             │
│                        ████████████████████████                           │
│                     ████████████████████████████████                      │
│                  ██████████████████████████████████████                   │
│                ████████████████████████████████████████████               │
│              ██████████████████████████████████████████████████           │
│            ████████████████████████████████████████████████████████       │
│                                                                             │
│   ─────────┼─────────┼─────────┼─────────┼─────────┼─────────┼─────────   │
│            μ-3σ     μ-2σ     μ-1σ       μ       μ+1σ     μ+2σ     μ+3σ    │
│                                                                             │
│       68% within μ ± 1σ                                                    │
│       95% within μ ± 2σ                                                    │
│     99.7% within μ ± 3σ                                                    │
│                                                                             │
└─────────────────────────────────────────────────────────────────────────────┘
```

| Range | Percentage |
|-------|------------|
| μ ± 1σ | 68.27% |
| μ ± 2σ | 95.45% |
| μ ± 3σ | 99.73% |

### 6.7 Chebyshev's Theorem

> 📖 **Definition**: For any distribution, at least 1 - 1/k² of data fall within k standard deviations of the mean.

$$ P(|X - \mu| < k\sigma) \geq 1 - \frac{1}{k^2} $$

| k | Minimum % |
|---|-----------|
| 2 | 75% |
| 3 | 88.9% |
| 4 | 93.75% |
| 5 | 96% |

---

## 7. Data Presentation & Reporting

### 7.1 Data Summarization

**Purposes:**
- Communication
- Decision making
- Pattern discovery
- Quality assessment

### 7.2 Tabular Presentation

**Types:**
- Frequency tables
- Contingency tables
- Summary tables
- Demographic tables

### 7.3 Reporting Mean ± SD

**Format:** Mean ± SD (n=XX)

**Example:** Age: 54.3 ± 12.1 years

**Guidelines:**
- Use appropriate precision
- Include sample size
- Check distribution
- Report with measure of dispersion

### 7.4 Reporting Median (IQR)

**Format:** Median (IQR)

**Example:** Length of stay: 5 (3-8) days

**Guidelines:**
- Use for skewed data
- Include Q1 and Q3
- May include range

### 7.5 Journal Reporting Standards

| Guideline | Application |
|-----------|-------------|
| **CONSORT** | Clinical trials |
| **STROBE** | Observational studies |
| **PRISMA** | Systematic reviews |
| **STARD** | Diagnostic studies |
| **MOOSE** | Meta-analyses |

**General Requirements:**
- Sample size for each analysis
- Appropriate precision
- Complete reporting
- Reproducibility
- Transparency

---

## 8. Software Implementation

### 8.1 R Implementation

```r
# Load necessary libraries
library(dplyr)
library(ggplot2)
library(tidyr)

# Comprehensive descriptive statistics function
descriptive_stats <- function(data, variable, group = NULL) {
  
  if (is.null(group)) {
    # Overall statistics
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
    # Grouped statistics
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

# Example usage with iris data
data(iris)
descriptive_stats(iris, Sepal.Length, Species)

# Create visualizations
# Histogram with density
ggplot(iris, aes(x = Sepal.Length, fill = Species)) +
  geom_histogram(aes(y = ..density..), bins = 20, alpha = 0.6) +
  geom_density(alpha = 0.3) +
  facet_wrap(~Species) +
  labs(title = "Distribution of Sepal Length by Species",
       x = "Sepal Length (cm)", y = "Density") +
  theme_minimal()

# Boxplot with points
ggplot(iris, aes(x = Species, y = Sepal.Length, fill = Species)) +
  geom_boxplot(alpha = 0.7) +
  geom_jitter(width = 0.2, alpha = 0.3) +
  labs(title = "Sepal Length by Species",
       x = "Species", y = "Sepal Length (cm)") +
  theme_minimal()
```

### 8.2 Python Implementation

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats
from sklearn.datasets import load_iris

def descriptive_stats(data, variable, group=None):
    """Calculate comprehensive descriptive statistics"""
    
    if group is None:
        # Overall statistics
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
        # Grouped statistics
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
stats_result = descriptive_stats(df, 'sepal length (cm)', 'species')
print(stats_result)

# Visualizations
fig, axes = plt.subplots(2, 2, figsize=(15, 12))

# Histograms by species
for i, species in enumerate(df['species'].unique()):
    ax = axes[0, i]
    subset = df[df['species'] == species]
    ax.hist(subset['sepal length (cm)'], bins=15, alpha=0.7)
    ax.set_title(f'Sepal Length: {species}')
    ax.set_xlabel('Sepal Length (cm)')
    ax.set_ylabel('Frequency')

# Boxplot
sns.boxplot(data=df, x='species', y='sepal length (cm)', ax=axes[1, 0])
axes[1, 0].set_title('Boxplot by Species')

# Violin plot
sns.violinplot(data=df, x='species', y='sepal length (cm)', ax=axes[1, 1])
axes[1, 1].set_title('Violin Plot by Species')

plt.tight_layout()
plt.show()
```

### 8.3 SPSS Implementation

```spss
* Comprehensive descriptive analysis.
DESCRIPTIVES VARIABLES=SepalLength SepalWidth PetalLength PetalWidth
  /STATISTICS=MEAN STDDEV MIN MAX SKEWNESS KURTOSIS.

* Frequency tables.
FREQUENCIES VARIABLES=SepalLength SepalWidth PetalLength PetalWidth
  /STATISTICS=MEDIAN MODE
  /HISTOGRAM.

* Explore for detailed statistics.
EXAMINE VARIABLES=SepalLength BY Species
  /PLOT BOXPLOT HISTOGRAM
  /STATISTICS DESCRIPTIVES.

* Grouped statistics.
MEANS TABLES=SepalLength SepalWidth BY Species
  /CELLS MEAN COUNT STDDEV MIN MAX.
```

### 8.4 STATA Implementation

```stata
* Load dataset.
use iris.dta

* Descriptive statistics.
summarize SepalLength SepalWidth PetalLength PetalWidth, detail

* By group.
bysort Species: summarize SepalLength, detail

* Frequency tables.
tabulate SepalLength

* Visualizations.
histogram SepalLength, by(Species) normal
graph box SepalLength, over(Species)

* Export table.
estpost summarize SepalLength, detail
esttab using summary.tex, replace cells("mean(fmt(2)) p50(fmt(2)) sd(fmt(2)) min(fmt(2)) max(fmt(2))")
```

### 8.5 SAS Implementation

```sas
* Descriptive statistics.
PROC MEANS DATA=iris N MEAN STD MEDIAN Q1 Q3 MIN MAX SKEWNESS KURTOSIS;
    CLASS Species;
    VAR SepalLength SepalWidth PetalLength PetalWidth;
RUN;

* Frequency tables.
PROC FREQ DATA=iris;
    TABLES Species / OUT=freq_table;
RUN;

* Visualizations.
PROC SGPLOT DATA=iris;
    VBOX SepalLength / GROUP=Species;
    TITLE "Boxplot of Sepal Length by Species";
RUN;

* Histograms.
PROC SGPLOT DATA=iris;
    HISTOGRAM SepalLength / GROUP=Species;
    TITLE "Histogram of Sepal Length by Species";
RUN;
```

### 8.6 Excel Implementation

**Functions for Descriptive Statistics:**

| Function | Purpose | Example |
|----------|---------|---------|
| `=AVERAGE(range)` | Mean | `=AVERAGE(A1:A100)` |
| `=MEDIAN(range)` | Median | `=MEDIAN(A1:A100)` |
| `=MODE.SNGL(range)` | Mode | `=MODE.SNGL(A1:A100)` |
| `=STDEV.S(range)` | Sample SD | `=STDEV.S(A1:A100)` |
| `=VAR.S(range)` | Sample Variance | `=VAR.S(A1:A100)` |
| `=MIN(range)` | Minimum | `=MIN(A1:A100)` |
| `=MAX(range)` | Maximum | `=MAX(A1:A100)` |
| `=QUARTILE.EXC(range,1)` | Q1 | `=QUARTILE.EXC(A1:A100,1)` |
| `=QUARTILE.EXC(range,3)` | Q3 | `=QUARTILE.EXC(A1:A100,3)` |
| `=SKEW(range)` | Skewness | `=SKEW(A1:A100)` |
| `=KURT(range)` | Kurtosis | `=KURT(A1:A100)` |

---

## 9. Assessment & Summary

### 9.1 Worked Example

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

**Step 3: Create Five-Number Summary**
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

### 9.2 Practice Questions

<details>
<summary>📝 Click to reveal practice questions</summary>

**Short Questions:**

1. What is the difference between descriptive and inferential statistics?

2. When should you use the median instead of the mean?

3. What does the interquartile range measure?

4. How do you identify outliers using the IQR method?

5. What is the 68-95-99.7 rule?

</details>

### 9.3 MCQs

<details>
<summary>📝 Click to reveal 20 MCQs</summary>

1. Which of the following is NOT a measure of central tendency?
   - A) Mean
   - B) Median
   - C) Range ✓
   - D) Mode

2. The standard deviation is a measure of:
   - A) Central tendency
   - B) Dispersion ✓
   - C) Shape
   - D) Position

3. Which measure is most appropriate for nominal data?
   - A) Mean
   - B) Median
   - C) Mode ✓
   - D) Standard deviation

4. The IQR is the difference between:
   - A) Mean and median
   - B) Q3 and Q1 ✓
   - C) Max and min
   - D) Q2 and Q1

5. Which distribution has mean < median < mode?
   - A) Symmetric
   - B) Right-skewed
   - C) Left-skewed ✓
   - D) Bimodal

6. Chebyshev's theorem applies to:
   - A) Only normal distributions
   - B) Any distribution ✓
   - C) Only symmetric distributions
   - D) Only large samples

7. A boxplot displays the:
   - A) Mean and SD
   - B) Five-number summary ✓
   - C) Frequency distribution
   - D) Correlation

8. The coefficient of variation is:
   - A) SD/Mean × 100 ✓
   - B) Mean/SD × 100
   - C) Range/SD × 100
   - D) IQR/Mean × 100

9. Which measure is scale-independent?
   - A) Standard deviation
   - B) Variance
   - C) Coefficient of variation ✓
   - D) Range

10. For right-skewed data:
    - A) Mean < Median
    - B) Mean > Median ✓
    - C) Mean = Median
    - D) Mode > Mean

</details>

### 9.4 Chapter Summary

> 🎯 **Key Takeaways**

1. **Descriptive statistics** summarizes, organizes, and presents data
2. **Choose measures** based on data type and distribution
3. **Visualization** is essential for understanding data
4. **EDA** is critical before any statistical analysis
5. **Report** appropriate measures with proper formatting
6. **Follow** CONSORT/STROBE/PRISMA guidelines
7. **Interpret** descriptively, not causally

### 9.5 Formula Sheet

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
