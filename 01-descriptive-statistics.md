# 📊 Chapter 1: Descriptive Statistics

## The Complete Guide — From First Principles to Publication-Ready Analysis

---

[![Open Access](https://img.shields.io/badge/Open%20Access-Free-success?style=for-the-badge)]()
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?style=for-the-badge)]()
[![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-blue?style=for-the-badge)]()
[![Sections](https://img.shields.io/badge/Sections-100%2B-orange?style=for-the-badge)]()
[![Software](https://img.shields.io/badge/Software-R%20%7C%20Python%20%7C%20SPSS%20%7C%20STATA%20%7C%20SAS%20%7C%20Excel-brightgreen?style=for-the-badge)]()
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026--07--05-yellow?style=for-the-badge)]()
[![Lines of Code](https://img.shields.io/badge/Lines-3%2C000%2B-red?style=for-the-badge)]()

---

> *"The goal is to turn data into information, and information into insight."* — **Carly Fiorina**

---

## 🌟 Interactive Visualization Gallery

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    DESCRIPTIVE STATISTICS AT A GLANCE                       ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  📊 DATA TYPES HIERARCHY                    🔄 ANIMATED FLOW       │    ║
║   │                                                                      │    ║
║   │   DATA ────┬──────────┬───────────┐        ╔══════╗  ╔══════╗       │    ║
║   │            │          │           │        ║ DATA ║─▶║ CLEAN║       │    ║
║   │      QUANTITATIVE  CATEGORICAL  OTHER      ╚══════╝  ╚══════╝       │    ║
║   │            │          │                    ╔══════╗  ╔══════╗       │    ║
║   │   ┌────────┼────────┐ │                    ║ EDA  ║─▶║ VIZ  ║       │    ║
║   │   │        │        │ │                    ╚══════╝  ╚══════╝       │    ║
║   │ DISCRETE CONTINUOUS ORDINAL NOMINAL        ╔══════╗  ╔══════╗       │    ║
║   │                                                                      │    ║
║   │ 📈 DISTRIBUTION SHAPES                    📉 MEASUREMENT SCALES      │    ║
║   │                                                                      │    ║
║   │ NORMAL    SKEWED    BIMODAL    UNIFORM    NOMINAL → ORDINAL →       │    ║
║   │  ██        ██        ██        ██        INTERVAL → RATIO          │    ║
║   │ ████      ████      ████      ████      (Increasing Information)   │    ║
║   │██████    ██████    ██████    ██████                                 │    ║
║   │██████    ██████    ██████    ██████                                 │    ║
║   │ ████      ████      ████      ████                                 │    ║
║   │  ██        ██        ██        ██                                  │    ║
║   │                                                                      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

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
- [4.11 Heatmap](#411-heatmap)
- [4.12 Violin Plot](#412-violin-plot)

### 5. Exploratory Data Analysis
- [5.1 Exploratory Data Analysis (EDA)](#51-exploratory-data-analysis-eda)
- [5.2 Data Cleaning](#52-data-cleaning)
- [5.3 Missing Data](#53-missing-data)
- [5.4 Outlier Detection](#54-outlier-detection)
- [5.5 Five Number Summary](#55-five-number-summary)
- [5.6 Quartiles](#56-quartiles)
- [5.7 Percentiles](#57-percentiles)
- [5.8 Correlation Analysis](#58-correlation-analysis)

### 6. Distribution Shape
- [6.1 Distribution Shape](#61-distribution-shape)
- [6.2 Symmetry](#62-symmetry)
- [6.3 Left Skewness](#63-left-skewness)
- [6.4 Right Skewness](#64-right-skewness)
- [6.5 Kurtosis](#65-kurtosis)
- [6.6 Empirical Rule](#66-empirical-rule)
- [6.7 Chebyshev's Theorem](#67-chebyshevs-theorem)
- [6.8 Normality Testing](#68-normality-testing)

### 7. Data Presentation & Reporting
- [7.1 Data Summarization](#71-data-summarization)
- [7.2 Tabular Presentation](#72-tabular-presentation)
- [7.3 Reporting Mean ± SD](#73-reporting-mean--sd)
- [7.4 Reporting Median (IQR)](#74-reporting-median-iqr)
- [7.5 Journal Reporting Standards](#75-journal-reporting-standards)
- [7.6 Publication Guidelines](#76-publication-guidelines)

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

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    DESCRIPTIVE STATISTICS CORE CONCEPTS                     ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │                    DATA → INFORMATION → INSIGHT                     │    ║
║   │                    🔄═══▶ ═══▶ ═══▶                                │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║                    THREE PILLARS OF DESCRIPTIVE STATISTICS           ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌───────────────┐    ┌───────────────┐    ┌───────────────┐               ║
║   │  📊 SUMMARIZE  │    │  📁 ORGANIZE   │    │  📈 VISUALIZE │               ║
║   ├───────────────┤    ├───────────────┤    ├───────────────┤               ║
║   │ • Mean        │    │ • Frequency   │    │ • Histograms  │               ║
║   │ • Median      │    │ • Tables      │    │ • Box plots   │               ║
║   │ • Mode        │    │ • Groups      │    │ • Scatter     │               ║
║   │ • SD          │    │ • Classes     │    │ • Pie charts  │               ║
║   │ • Variance    │    │ • Bins        │    │ • Bar charts  │               ║
║   │ • Range       │    │ • Categories  │    │ • Heatmaps    │               ║
║   │ • IQR         │    │ • Intervals   │    │ • Violin      │               ║
║   └───────────────┘    └───────────────┘    └───────────────┘               ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │                    DISCOVER PATTERNS IN DATA                        │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │  🔍 TRENDS    📌 OUTLIERS    🔗 RELATIONSHIPS    🕳️ GAPS         │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 1.2 Historical Background

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    HISTORICAL DEVELOPMENT TIMELINE                          ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   🌅 ANCIENT (3000 BCE - 500 CE)                                            ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Egypt: First census (3000 BCE)  │  Babylon: Population records    │    ║
║   │  Rome: Census for taxation      │  China: Population surveys       │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                              ▼                                               ║
║   🏰 RENAISSANCE (1500s - 1700s)                                            ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  John Graunt: Life tables (1662)  │  William Petty: Political      │    ║
║   │  Edmond Halley: Mortality tables  │  arithmetic (1676)             │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                              ▼                                               ║
║   💡 ENLIGHTENMENT (1700s - 1800s)                                          ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Gauss: Normal distribution    │  Laplace: Central limit theorem   │    ║
║   │  de Moivre: Normal curve       │  Legendre: Least squares          │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                              ▼                                               ║
║   🏭 MODERN (1880s - 1900s)                                                 ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Galton: Regression/Correlation │  Pearson: Chi-square             │    ║
║   │  Fisher: ANOVA/Design           │  Tukey: EDA                      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                              ▼                                               ║
║   💻 DIGITAL AGE (1900s - Present)                                          ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Computational statistics    │  Machine learning                   │    ║
║   │  Big data analytics          │  AI-driven analysis                 │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 1.3 Evolution of Descriptive Statistics

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    EVOLUTION OF DESCRIPTIVE STATISTICS                      ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   Period          │ Key Developments              │ Major Contributors      ║
║  ─────────────────┼───────────────────────────────┼──────────────────────── ║
║   🌅 Ancient      │ Census data, population       │ Babylonians, Egyptians  ║
║    (3000 BCE -    │ records, basic enumeration    │ Romans, Chinese         ║
║    500 CE)        │                               │                         ║
║  ─────────────────┼───────────────────────────────┼──────────────────────── ║
║   🏰 Renaissance  │ Political arithmetic, life    │ John Graunt,            ║
║    (1500s-1700s)  │ tables, mortality statistics  │ William Petty,          ║
║                   │                               │ Edmond Halley           ║
║  ─────────────────┼───────────────────────────────┼──────────────────────── ║
║   💡 Enlightenment│ Normal distribution, least    │ Carl Gauss,             ║
║    (1700s-1800s)  │ squares, probability theory   │ Pierre Laplace,         ║
║                   │                               │ Abraham de Moivre       ║
║  ─────────────────┼───────────────────────────────┼──────────────────────── ║
║   🏭 Modern       │ Correlation, regression, EDA  │ Francis Galton,         ║
║    (1880s-1900s)  │ Chi-square, ANOVA             │ Karl Pearson,           ║
║                   │                               │ Ronald Fisher,          ║
║                   │                               │ John Tukey              ║
║  ─────────────────┼───────────────────────────────┼──────────────────────── ║
║   💻 Digital Age  │ Computational statistics,     │ Modern statisticians,   ║
║    (1900s-Present)│ Big data analytics,           │ Data scientists,        ║
║                   │ Machine learning, AI          │ ML engineers            ║
║  ─────────────────┼───────────────────────────────┼──────────────────────── ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 1.4 Importance in Science

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    IMPORTANCE IN SCIENTIFIC FIELDS                          ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  🔬 BIOLOGY                                                         │    ║
║   │  • Summarizing measurements of organisms                            │    ║
║   │  • Characterizing populations and species                           │    ║
║   │  • Describing genetic variations                                    │    ║
║   │  • Analyzing experimental results                                   │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  ⚛️ PHYSICS                                                         │    ║
║   │  • Describing measurement distributions                             │    ║
║   │  • Error analysis and uncertainty quantification                    │    ║
║   │  • Characterizing experimental precision                            │    ║
║   │  • Quality control in measurements                                  │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  🧪 CHEMISTRY                                                       │    ║
║   │  • Characterizing samples and compounds                             │    ║
║   │  • Quality control in manufacturing                                 │    ║
║   │  • Describing reaction yields                                       │    ║
║   │  • Analyzing spectroscopic data                                     │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  🌍 ENVIRONMENTAL SCIENCE                                           │    ║
║   │  • Summarizing pollution levels                                     │    ║
║   │  • Climate data analysis                                            │    ║
║   │  • Monitoring environmental changes                                 │    ║
║   │  • Characterizing ecosystems                                        │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  👥 SOCIAL SCIENCES                                                 │    ║
║   │  • Describing survey responses                                      │    ║
║   │  • Demographic data analysis                                        │    ║
║   │  • Characterizing populations                                       │    ║
║   │  • Policy evaluation                                                │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  🌌 ASTRONOMY                                                       │    ║
║   │  • Summarizing observations                                         │    ║
║   │  • Characterizing celestial objects                                 │    ║
║   │  • Analyzing light curves                                           │    ║
║   │  • Processing astronomical data                                     │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 1.5 Importance in Medical Research

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    IMPORTANCE IN MEDICAL RESEARCH                           ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   Application           │ Example                                            ║
║  ───────────────────────┼─────────────────────────────────────────────────── ║
║   🏥 Clinical Trials    │ Baseline characteristics, treatment effects       ║
║                         │ Adverse event frequencies, efficacy measures      ║
║  ───────────────────────┼─────────────────────────────────────────────────── ║
║   📋 Observational      │ Patient demographics, risk factor distributions   ║
║   Studies               │ Disease prevalence, outcome frequencies           ║
║  ───────────────────────┼─────────────────────────────────────────────────── ║
║   🔬 Diagnostic Testing │ Reference ranges, test characteristics            ║
║                         │ Sensitivity, specificity, predictive values       ║
║  ───────────────────────┼─────────────────────────────────────────────────── ║
║   💊 Drug Development   │ Safety profiles, dose-response patterns           ║
║                         │ Efficacy measures, adverse event monitoring       ║
║  ───────────────────────┼─────────────────────────────────────────────────── ║
║   🦠 Epidemiology       │ Disease incidence and prevalence                  ║
║                         │ Risk factor distributions, outbreak patterns      ║
║  ───────────────────────┼─────────────────────────────────────────────────── ║
║   📊 Survival Analysis  │ Median survival times, event frequencies          ║
║                         │ Survival distributions, hazard rates              ║
║  ───────────────────────┼─────────────────────────────────────────────────── ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  📈 KEY MEDICAL STATISTICS VISUALIZED                                ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Blood Pressure Distribution    │  BMI Distribution                       ║
║        ██                        │       ██                                ║
║       ████                       │      ████                               ║
║      ██████                      │     ██████                              ║
║     ████████                     │    ████████                             ║
║    ██████████                    │   ██████████                            ║
║   ████████████                   │  ████████████                           ║
║  ██████████████                  │ ██████████████                          ║
║ ████████████████                 │████████████████                         ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 1.6 Importance in Public Health

> [!TIP]
> *Descriptive statistics is the cornerstone of public health surveillance, monitoring, and response.*

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    IMPORTANCE IN PUBLIC HEALTH                              ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  🚨 DISEASE SURVEILLANCE                                            │    ║
║   │  • Tracking incidence and prevalence                                │    ║
║   │  • Monitoring disease outbreaks                                     │    ║
║   │  • Characterizing disease patterns                                  │    ║
║   │  • Early warning systems                                            │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  📊 HEALTH INDICATORS                                               │    ║
║   │  • Monitoring population health status                              │    ║
║   │  • Tracking key health metrics                                      │    ║
║   │  • Evaluating health programs                                       │    ║
║   │  • International comparisons                                        │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  ⚖️ HEALTH DISPARITIES                                              │    ║
║   │  • Identifying vulnerable populations                               │    ║
║   │  • Characterizing health inequalities                               │    ║
║   │  • Monitoring progress in health equity                             │    ║
║   │  • Policy development                                               │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  💰 RESOURCE ALLOCATION                                             │    ║
║   │  • Informing public health decisions                                │    ║
║   │  • Prioritizing interventions                                       │    ║
║   │  • Budget allocation                                                │    ║
║   │  • Health system planning                                           │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  🌍 GLOBAL HEALTH                                                   │    ║
║   │  • DHS surveys and national indicators                              │    ║
║   │  • International health monitoring                                  │    ║
║   │  • Comparative health systems                                       │    ║
║   │  • Global health goals monitoring                                   │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 1.7 Importance in Machine Learning

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    IMPORTANCE IN MACHINE LEARNING                           ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ML Task              │ Role of Descriptive Statistics                     ║
║  ──────────────────────┼─────────────────────────────────────────────────── ║
║   🧹 Data              │ Understanding distributions                        ║
║   Preprocessing        │ Handling missing values                            ║
║                        │ Detecting and handling outliers                    ║
║                        │ Data normalization/standardization                 ║
║  ──────────────────────┼─────────────────────────────────────────────────── ║
║   ⚙️ Feature           │ Feature scaling and normalization                  ║
║   Engineering          │ Creating derived features                          ║
║                        │ Identifying important features                     ║
║                        │ Transformations and interactions                   ║
║  ──────────────────────┼─────────────────────────────────────────────────── ║
║   🎯 Model Selection   │ Understanding data characteristics                 ║
║                        │ Choosing appropriate models                        ║
║                        │ Matching data to assumptions                      ║
║                        │ Algorithm selection                                ║
║  ──────────────────────┼─────────────────────────────────────────────────── ║
║   📊 Evaluation        │ Performance metrics interpretation                 ║
║                        │ Understanding model behavior                       ║
║                        │ Error analysis                                     ║
║                        │ Model comparison                                   ║
║  ──────────────────────┼─────────────────────────────────────────────────── ║
║   🔍 Feature           │ Understanding variable relationships               ║
║   Importance           │ Identifying key predictors                        ║
║                        │ Correlation analysis                               ║
║                        │ Feature selection                                  ║
║  ──────────────────────┼─────────────────────────────────────────────────── ║
║   📈 EDA               │ Discovering patterns in data                       ║
║                        │ Identifying data quality issues                    ║
║                        │ Understanding data structure                       ║
║                        │ Hypothesis generation                              ║
║  ──────────────────────┼─────────────────────────────────────────────────── ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  🤖 ML PIPELINE WITH DESCRIPTIVE STATISTICS                          ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Raw Data → 📊 EDA → 🧹 Cleaning → ⚙️ Features → 🎯 Model → 📈 Results    ║
║        │        │           │           │           │          │            ║
║        │   ┌────┴────┐ ┌────┴────┐ ┌────┴────┐ ┌────┴────┐ ┌────┴────┐     ║
║        │   │Summary  │ │ Missing │ │Scaling  │ │Model    │ │Metrics  │     ║
║        │   │Tables   │ │Handling │ │Stats    │ │Selection│ │Reporting│     ║
║        └───┴─────────┘ └─────────┘ └─────────┘ └─────────┘ └─────────┘     ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 1.8 Importance in AI

> 🤖 *"Descriptive statistics provides the foundation for AI systems to understand the data they are learning from."*

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    IMPORTANCE IN ARTIFICIAL INTELLIGENCE                    ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  🧠 DATA UNDERSTANDING                                              │    ║
║   │  • Characterizing training data distributions                       │    ║
║   │  • Understanding data quality and completeness                      │    ║
║   │  • Identifying data limitations                                     │    ║
║   │  • Ensuring representative samples                                  │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  ⚠️ BIAS DETECTION                                                  │    ║
║   │  • Identifying biases in datasets                                   │    ║
║   │  • Monitoring fairness metrics                                      │    ║
║   │  • Ensuring equitable AI                                            │    ║
║   │  • Bias mitigation strategies                                       │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  ✅ MODEL VALIDATION                                               │    ║
║   │  • Ensuring data quality                                            │    ║
║   │  • Model performance monitoring                                     │    ║
║   │  • Data drift detection                                             │    ║
║   │  • Model robustness assessment                                      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  🔍 EXPLAINABLE AI                                                 │    ║
║   │  • Understanding data distributions                                 │    ║
║   │  • Feature importance interpretation                                │    ║
║   │  • Model behavior explanation                                       │    ║
║   │  • Transparent AI systems                                           │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  🤖 AUTOMATED ML                                                   │    ║
║   │  • Feature selection and preprocessing                              │    ║
║   │  • Model and hyperparameter selection                               │    ║
║   │  • Automated data quality checks                                    │    ║
║   │  • Pipeline optimization                                            │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  📈 EVALUATION                                                     │    ║
║   │  • Understanding model performance                                  │    ║
║   │  • Error analysis and reporting                                     │    ║
║   │  • Model improvement identification                                 │    ║
║   │  • Performance comparisons                                          │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 1.9 Types of Descriptive Statistics

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    TYPES OF DESCRIPTIVE STATISTICS                          ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  1. 📊 CENTRAL TENDENCY                                             ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Mean      → Average of all values                                  │    ║
║   │  Median    → Middle value when data sorted                          │    ║
║   │  Mode      → Most frequently occurring value                        │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  2. 📈 DISPERSION (SPREAD)                                          ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Range     → Maximum - Minimum                                      │    ║
║   │  IQR       → Q3 - Q1 (interquartile range)                         │    ║
║   │  Variance  → Average of squared deviations                          │    ║
║   │  SD        → Square root of variance                                │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  3. 📉 DISTRIBUTION SHAPE                                           ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Symmetry  → Balanced distribution                                  │    ║
║   │  Skewness  → Direction of tails (left/right)                       │    ║
║   │  Kurtosis  → Peakedness of distribution                             │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  4. 🔗 RELATIONSHIP                                                 ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Correlation → Strength and direction of association                │    ║
║   │  Covariance  → How two variables vary together                     │    ║
║   │  Contingency → Categorical variable relationships                   │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  5. 📍 POSITION MEASURES                                            ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Percentiles → Positions dividing data into 100 parts               │    ║
║   │  Quartiles   → Positions dividing data into 4 parts                 │    ║
║   │  Z-scores    → Standardized positions                               │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## 2. Data Fundamentals

### 2.1 Population vs Sample Summary

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    POPULATION VS SAMPLE                                     ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║                      ╔═══════════════════════════════════════════════════╗   ║
║                      ║              POPULATION                           ║   ║
║                      ║   ┌─────────────────────────────────────────┐    ║   ║
║                      ║   │         All Subjects of Interest        │    ║   ║
║                      ║   │                                         │    ║   ║
║                      ║   │   • N = 10,000                         │    ║   ║
║                      ║   │   • Parameter: μ, σ, ρ                 │    ║   ║
║                      ║   │   • Greek Notation                     │    ║   ║
║                      ║   │   • Usually unknown                    │    ║   ║
║                      ║   └─────────────────────────────────────────┘    ║   ║
║                      ║                    │                            ║   ║
║                      ║                    │ SAMPLE                     ║   ║
║                      ║                    ▼                            ║   ║
║                      ║   ┌─────────────────────────────────────────┐    ║   ║
║                      ║   │         Subset of Population           │    ║   ║
║                      ║   │                                         │    ║   ║
║                      ║   │   • n = 100                            │    ║   ║
║                      ║   │   • Statistic: x̄, s, r               │    ║   ║
║                      ║   │   • Roman Notation                    │    ║   ║
║                      ║   │   • Known and manageable              │    ║   ║
║                      ║   └─────────────────────────────────────────┘    ║   ║
║                      ╚═══════════════════════════════════════════════════╝   ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  COMPARISON TABLE                                                    ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Aspect              │ Population                      │ Sample             ║
║  ─────────────────────┼─────────────────────────────────┼─────────────────── ║
║   Definition          │ Entire group of interest        │ Subset of pop      ║
║   Size                │ N                               │ n                  ║
║   Parameter           │ μ, σ, ρ                         │ x̄, s, r           ║
║   Notation            │ Greek                           │ Roman              ║
║   Access              │ Often unknown                   │ Known              ║
║   Cost                │ Expensive                       │ Feasible           ║
║   Time                │ Time-consuming                  │ Faster             ║
║   Practicality        │ Often impossible                │ Always possible    ║
║   Precision           │ Exact (if known)                │ Estimated          ║
║   Purpose             │ Complete description            │ Inference          ║
║  ─────────────────────┼─────────────────────────────────┼─────────────────── ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 2.2 Data Types

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                         DATA TYPES HIERARCHY                                ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║                              ╔═══════╗                                      ║
║                              ║ DATA  ║                                      ║
║                              ╚═══┬═══╝                                      ║
║                                  │                                           ║
║              ┌───────────────────┼───────────────────┐                      ║
║              │                   │                   │                      ║
║              ▼                   ▼                   ▼                      ║
║        ╔═══════════╗      ╔═══════════╗      ╔═══════════╗                  ║
║        ║QUANTITATVE║      ║CATEGORICAL║      ║  OTHER    ║                  ║
║        ║(Numerical)║      ║ (Groups)  ║      ║           ║                  ║
║        ╚═════┬═════╝      ╚═════┬═════╝      ╚═══════════╝                  ║
║              │                   │                                           ║
║     ┌────────┼────────┐        ┌─┼────────┐                                ║
║     │        │        │        │ │        │                                ║
║     ▼        ▼        ▼        ▼ ▼        ▼                                ║
║   ╔═══╗    ╔═══╗    ╔═══╗    ╔═══╗    ╔═══╗                               ║
║   ║DIS║    ║CON║    ║ORD║    ║NOM║    ║BIN║                               ║
║   ║CRE║    ║TIN║    ║INAL║    ║INAL║    ║ARY║                               ║
║   ║TE ║    ║UOUS║   ║    ║    ║    ║    ║   ║                               ║
║   ╚═══╝    ╚═══╝    ╚═══╝    ╚═══╝    ╚═══╝                               ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  EXAMPLES                                                             ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ████ DISCRETE (Counts)    ████ CONTINUOUS (Measured)                     ║
║   • Number of children     • Height                                       ║
║   • Number of patients     • Weight                                       ║
║   • Hospital visits        • Blood pressure                              ║
║   • Adverse events         • Temperature                                  ║
║                                                                              ║
║   ████ ORDINAL (Ranked)     ████ NOMINAL (Unordered)                      ║
║   • Disease severity       • Gender                                       ║
║   • Education level        • Blood group                                  ║
║   • Cancer stage           • Religion                                     ║
║   • Pain scale             • Race/ethnicity                              ║
║                                                                              ║
║   ████ BINARY (Two categories)                                              ║
║   • Alive/Dead                                                             ║
║   • Male/Female                                                            ║
║   • Yes/No                                                                 ║
║   • Present/Absent                                                         ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 2.3 Variables

> 📖 **Definition**: A **variable** is any characteristic, attribute, or measurable property that can take different values across individuals, objects, places, or observations. Variables form the foundation of statistical analysis because every statistical method is ultimately designed to summarize, compare, or model variables.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                         VARIABLE CLASSIFICATION                            ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │                     ╔═══════════════════════════╗                    │    ║
║   │                     ║       VARIABLE           ║                    │    ║
║   │                     ╚═════════════┬═════════════╝                    │    ║
║   │                                   │                                  │    ║
║   │          ┌────────────────────────┼────────────────────────┐         │    ║
║   │          │                        │                        │         │    ║
║   │          ▼                        ▼                        ▼         │    ║
║   │   ╔───────────────╗        ╔───────────────╗        ╔───────────────╗│    ║
║   │   ║  QUANTITATIVE ║        ║  CATEGORICAL  ║        ║  OTHER TYPES  ║│    ║
║   │   ║   Variables   ║        ║   Variables   ║        ║               ║│    ║
║   │   ╠═══════════════╣        ╠═══════════════╣        ╠═══════════════╣│    ║
║   │   ║ • Height      ║        ║ • Gender      ║        ║ • Confounder  ║│    ║
║   │   ║ • Weight      ║        ║ • Blood Group ║        ║ • Mediator    ║│    ║
║   │   ║ • Age         ║        ║ • Religion    ║        ║ • Moderator   ║│    ║
║   │   ║ • Income      ║        ║ • Education   ║        ║ • Control     ║│    ║
║   │   ║ • BP          ║        ║ • Occupation  ║        ║ • Covariate   ║│    ║
║   │   ║ • BMI         ║        ║ • Marital     ║        ║ • Independent ║│    ║
║   │   ║ • Cholesterol ║        ║   Status      ║        ║ • Dependent   ║│    ║
║   │   ╚═══════════════╝        ╚═══════════════╝        ╚═══════════════╝│    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  REAL RESEARCH EXAMPLE                                              ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Research Question: Does physical activity reduce blood pressure?           ║
║                                                                              ║
║   ┌─────────────────┬────────────────────┬─────────────────┐                 ║
║   │   Variable      │        Type        │      Role       │                 ║
║   ├─────────────────┼────────────────────┼─────────────────┤                 ║
║   │ Physical Activity│ Quantitative       │ Independent    │                 ║
║   │ Blood Pressure  │ Quantitative       │ Dependent      │                 ║
║   │ Age             │ Quantitative       │ Confounder     │                 ║
║   │ Sex             │ Categorical        │ Control        │                 ║
║   │ BMI             │ Quantitative       │ Covariate      │                 ║
║   │ Smoking Status  │ Categorical        │ Moderator      │                 ║
║   └─────────────────┴────────────────────┴─────────────────┘                 ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 2.4 Measurement Scales

> 📖 **Definition**: A **measurement scale** defines the way a variable is observed, categorized, or quantified. It determines the mathematical operations that can be performed on the data and guides the selection of appropriate statistical methods.

**The Four Levels of Measurement:**

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    HIERARCHY OF MEASUREMENT SCALES                          ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║                    ═══════════════════════════════════════════════════════    ║
║                            Increasing Information                           ║
║                        ─────────────────────────▶                          ║
║                    ═══════════════════════════════════════════════════════    ║
║                                                                              ║
║   ┌─────────────┐    ┌─────────────┐    ┌─────────────┐    ┌─────────────┐  ║
║   │   NOMINAL   │    │   ORDINAL   │    │  INTERVAL   │    │    RATIO    │  ║
║   │   Scale     │    │   Scale     │    │   Scale     │    │   Scale     │  ║
║   ├─────────────┤    ├─────────────┤    ├─────────────┤    ├─────────────┤  ║
║   │ Categories  │    │ Categories  │    │ Equal       │    │ Equal       │  ║
║   │ No Order    │    │ With Order  │    │ Intervals   │    │ Intervals   │  ║
║   │ Labels Only │    │ Rankings    │    │ No True Zero│    │ True Zero   │  ║
║   │ =, ≠        │    │ <, >        │    │ +, −        │    │ ×, ÷        │  ║
║   ├─────────────┤    ├─────────────┤    ├─────────────┤    ├─────────────┤  ║
║   │ Blood Group │    │ Pain Score  │    │ Temperature │    │ Height      │  ║
║   │ Gender      │    │ Cancer Stage│    │ IQ Score    │    │ Weight      │  ║
║   │ Religion    │    │ Education   │    │ Calendar    │    │ Age         │  ║
║   │ Race        │    │ Severity    │    │ Years       │    │ Income      │  ║
║   └─────────────┘    └─────────────┘    └─────────────┘    └─────────────┘  ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  DETAILED COMPARISON                                                 ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Scale     │ Definition              │ Operations │ Examples               ║
║  ───────────┼─────────────────────────┼────────────┼─────────────────────── ║
║   Nominal   │ Categories without      │ =, ≠       │ Blood group, Gender    ║
║             │ order/ranking           │            │ Religion, Race         ║
║  ───────────┼─────────────────────────┼────────────┼─────────────────────── ║
║   Ordinal   │ Categories with         │ =, ≠, <, > │ Pain severity,         ║
║             │ meaningful order        │            │ Education, Stage       ║
║  ───────────┼─────────────────────────┼────────────┼─────────────────────── ║
║   Interval  │ Equal intervals,        │ +, −       │ Temperature (°C),      ║
║             │ no true zero            │            │ IQ score, Calendar     ║
║  ───────────┼─────────────────────────┼────────────┼─────────────────────── ║
║   Ratio     │ Equal intervals,        │ +, −, ×, ÷ │ Height, Weight,        ║
║             │ true zero               │            │ Age, Income            ║
║  ───────────┼─────────────────────────┼────────────┼─────────────────────── ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 2.5 Raw Data

> 📖 **Definition**: Raw data are unprocessed, original observations collected from a study or experiment.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                         RAW DATA                                            ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  CHARACTERISTICS                                                    │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │  • Unprocessed and in original form                                 │    ║
║   │  • Contains all observations                                        │    ║
║   │  • May include errors                                               │    ║
║   │  • Requires cleaning                                                │    ║
║   │  • No aggregation                                                   │    ║
║   │  • No summarization                                                 │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  EXAMPLE: Blood Pressure Readings                                   ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Raw Data: 78, 92, 85, 67, 89, 73, 94, 81, 76, 88                         ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  VISUAL REPRESENTATION                                               │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  100 ●                                                              │    ║
║   │   90 │  ●    ●  ●                                                  │    ║
║   │   80 │    ●      ●    ●    ●                                      │    ║
║   │   70 │      ●          ●                                          │    ║
║   │   60 │                                                            │    ║
║   │   50 │                                                            │    ║
║   │      └──────────────────────────────────────────────────────────────│    ║
║   │        1    2    3    4    5    6    7    8    9   10             │    ║
║   │                        Observations                                │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 2.6 Ordered Data

> 📖 **Definition**: Ordered data are observations arranged in ascending order.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                         ORDERED DATA                                        ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  EXAMPLE: Sorting Blood Pressure Readings                           │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Raw Data:   78, 92, 85, 67, 89, 73, 94, 81, 76, 88                │    ║
║   │                                                                      │    ║
║   │  Ordered:    67, 73, 76, 78, 81, 85, 88, 89, 92, 94                │    ║
║   │                                                                      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  BENEFITS OF ORDERING                                                ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  ✅ Easy to find minimum and maximum                                 │    ║
║   │  ✅ Facilitates median calculation                                   │    ║
║   │  ✅ Enables percentile computation                                   │    ║
║   │  ✅ Provides distribution insight                                    │    ║
║   │  ✅ Helps identify outliers                                          │    ║
║   │  ✅ Reveals gaps and patterns                                        │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  DOT PLOT OF ORDERED DATA                                            ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   67  70  73  76  79  82  85  88  91  94                                   ║
║   │   │   │   │   │   │   │   │   │   │                                   ║
║   ●       ●   ●   ●   ●       ●   ●       ●   ●                          ║
║                         Median = 83                                        ║
║                         Q1 = 76, Q3 = 89                                  ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## 3. Frequency Distributions

### 3.1 Frequency Distribution

> 📖 **Definition**: A **frequency distribution** is a systematic arrangement of data that displays the number of observations (frequencies) corresponding to each value or class interval.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    FREQUENCY DISTRIBUTION STRUCTURE                         ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │                    FREQUENCY DISTRIBUTION TABLE                     │    ║
║   ├───────────────┬───────────────┬───────────────┬────────────────────┤    ║
║   │   Value/Class │   Frequency   │   Relative    │    Cumulative       │    ║
║   │               │               │   Frequency   │    Frequency        │    ║
║   ├───────────────┼───────────────┼───────────────┼────────────────────┤    ║
║   │   Category A  │      15       │     0.30      │       15           │    ║
║   │   Category B  │      22       │     0.44      │       37           │    ║
║   │   Category C  │      18       │     0.36      │       55           │    ║
║   │   Category D  │      10       │     0.20      │       65           │    ║
║   ├───────────────┼───────────────┼───────────────┼────────────────────┤    ║
║   │   Total       │      65       │     1.30*     │       65           │    ║
║   └───────────────┴───────────────┴───────────────┴────────────────────┘    ║
║   *Sum may exceed 1 due to rounding                                         ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  VISUAL REPRESENTATION                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   25 │              ████                                                    ║
║   20 │    ████      ████                                                    ║
║   15 │    ████      ████      ████                                          ║
║   10 │    ████      ████      ████      ████                                ║
║    5 │    ████      ████      ████      ████                                ║
║    0 └────────────────────────────────────────────────────────────────────   ║
║         A          B          C          D                                  ║
║                         Categories                                          ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 3.2 Relative Frequency

> 📖 **Definition**: Relative frequency represents the proportion of observations belonging to each category relative to the total sample size.

**Formula:**
$$ \text{Relative Frequency} = \frac{\text{Frequency}}{\text{Total Number of Observations}} $$

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    RELATIVE FREQUENCY                                       ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  EXAMPLE: Blood Type Distribution                                   │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  If 15 out of 65 people have blood type O+:                         │    ║
║   │                                                                      │    ║
║   │  Relative Frequency = 15/65 = 0.231 = 23.1%                         │    ║
║   │                                                                      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  RELATIVE FREQUENCY TABLE                                            ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Blood Type │ Frequency │ Relative Frequency │ Percentage                  ║
║  ────────────┼───────────┼────────────────────┼─────────────               ║
║   O+         │    25     │      0.385         │   38.5%                    ║
║   A+         │    20     │      0.308         │   30.8%                    ║
║   B+         │    10     │      0.154         │   15.4%                    ║
║   AB+        │     5     │      0.077         │    7.7%                    ║
║   Other      │     5     │      0.077         │    7.7%                    ║
║  ────────────┼───────────┼────────────────────┼─────────────               ║
║   Total      │    65     │      1.000         │  100.0%                    ║
║  ────────────┼───────────┼────────────────────┼─────────────               ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 3.3 Cumulative Frequency

> 📖 **Definition**: Cumulative frequency represents the running total of frequencies as observations accumulate from one class to the next.

**Formula:**
$$ \text{Cumulative Frequency} = \sum_{i=1}^{k} f_i $$

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    CUMULATIVE FREQUENCY                                     ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  EXAMPLE: Test Score Distribution (n=60)                           │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Score Range │ Frequency │ Cumulative Frequency │  Percentage       │    ║
║   ├──────────────┼───────────┼────────────────────┼─────────────┤      │    ║
║   │  0-59        │     5     │         5          │    8.3%     │      │    ║
║   │  60-69       │     8     │        13          │   21.7%     │      │    ║
║   │  70-79       │    12     │        25          │   41.7%     │      │    ║
║   │  80-89       │    18     │        43          │   71.7%     │      │    ║
║   │  90-100      │    17     │        60          │  100.0%     │      │    ║
║   ├──────────────┼───────────┼────────────────────┼─────────────┤      │    ║
║   │  Total       │    60     │        60          │             │      │    ║
║   └──────────────┴───────────┴────────────────────┴─────────────┘      │    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  INTERPRETATION                                                      ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ 25 students (41.7%) scored below 80                                   ║
║   ✅ 43 students (71.7%) scored below 90                                   ║
║   ✅ All 60 students scored below 100                                      ║
║   ✅ Most students (43/60) scored below 90                                 ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  CUMULATIVE FREQUENCY CURVE (OGIVE)                                  ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   60 │                                  ●                                   ║
║   50 │                               ●                                      ║
║   40 │                            ●                                         ║
║   30 │                         ●                                            ║
║   20 │                      ●                                               ║
║   10 │                   ●                                                  ║
║    0 │●────────────────────────────────────────────────────────────────────  ║
║       0   20   40   60   80   100                                            ║
║                           Score                                              ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 3.4 Frequency Tables

**Complete Example: Blood Types (n=100)**

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    FREQUENCY TABLE: Blood Types                             ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────┬─────────────┬──────────────────┬───────────┬─────────────┐║
║   │ Blood Type  │  Frequency  │ Relative Freq.   │ Percentage│ Cum Freq.   │║
║   ├─────────────┼─────────────┼──────────────────┼───────────┼─────────────┤║
║   │    O+       │     35      │      0.35        │   35%     │     35      │║
║   │    A+       │     28      │      0.28        │   28%     │     63      │║
║   │    B+       │     18      │      0.18        │   18%     │     81      │║
║   │    AB+      │     12      │      0.12        │   12%     │     93      │║
║   │    O-       │      4      │      0.04        │    4%     │     97      │║
║   │    A-       │      2      │      0.02        │    2%     │     99      │║
║   │    B-       │      1      │      0.01        │    1%     │    100      │║
║   ├─────────────┼─────────────┼──────────────────┼───────────┼─────────────┤║
║   │   Total     │    100      │      1.00        │  100%     │             │║
║   └─────────────┴─────────────┴──────────────────┴───────────┴─────────────┘║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  KEY INSIGHTS                                                        ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   🔍 O+ is the most common blood group (35%)                                ║
║   🔍 63% of participants are either O+ or A+                                ║
║   🔍 Only 7% have Rh-negative blood                                         ║
║   🔍 AB+ is relatively rare (12%)                                           ║
║   🔍 Distribution follows known population patterns                         ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  PIE CHART VISUALIZATION                                              ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║               ╔═══════════════════════════════════════╗                     ║
║              ╔╝                                   ╚╗                    ║
║              ║          O+ (35%)                    ║                    ║
║              ║    █████████████████████████████     ║                    ║
║              ║                                     ║                    ║
║          B-  ║  A+ (28%)      ████████████████     ║                    ║
║         1%   ║                                     ║                    ║
║               ║                                     ║                    ║
║          A-   ║                                     ║   O- 4%            ║
║         2%    ║                                     ║                    ║
║               ║                                     ║                    ║
║               ║  B+ (18%)      ███████████          ║                    ║
║               ║                                     ║                    ║
║               ╚╗                                   ╔╝                    ║
║                ╚═══════════════════════════════════════╝                     ║
║                    AB+ (12%)                                                 ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 3.5 Grouped Data

> 📖 **Definition**: **Grouped data** are observations organized into class intervals rather than reported individually.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    GROUPED FREQUENCY TABLE                                  ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  EXAMPLE: Age Distribution (n=200)                                 │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Age Group   │ Frequency │ Percentage │ Cumulative                   │    ║
║   │  (Years)     │           │            │                             │    ║
║   ├──────────────┼───────────┼────────────┼───────────                  │    ║
║   │  20-29       │    18     │   15.0%    │    18                      │    ║
║   │  30-39       │    42     │   35.0%    │    60                      │    ║
║   │  40-49       │    56     │   46.7%    │   116                      │    ║
║   │  50-59       │    48     │   40.0%    │   164                      │    ║
║   │  60-69       │    36     │   30.0%    │   200                      │    ║
║   ├──────────────┼───────────┼────────────┼───────────                  │    ║
║   │  Total       │   200     │  100.0%    │                            │    ║
║   └──────────────┴───────────┴────────────┴───────────                  │    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  HISTOGRAM OF AGE DISTRIBUTION                                      ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   60 │          ████                                                        ║
║   50 │          ████      ████                                              ║
║   40 │    ████  ████      ████      ████                                    ║
║   30 │    ████  ████      ████      ████      ████                         ║
║   20 │    ████  ████      ████      ████      ████                         ║
║   10 │    ████  ████      ████      ████      ████                         ║
║    0 └────────────────────────────────────────────────────────────────────   ║
║       20-29  30-39  40-49  50-59  60-69                                    ║
║                          Age Groups                                         ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 3.6 Ungrouped Data

> 📖 **Definition**: **Ungrouped data** consist of individual observations presented in their original form without classification into intervals.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    UNGROUPED DATA EXAMPLE                                   ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Number of Siblings (n=30)                                         │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Siblings │ Frequency │ Relative │ Cumulative                       │    ║
║   ├───────────┼───────────┼──────────┼───────────                        │    ║
║   │     0     │     8     │   0.27   │     8                           │    ║
║   │     1     │    12     │   0.40   │    20                           │    ║
║   │     2     │     6     │   0.20   │    26                           │    ║
║   │     3     │     3     │   0.10   │    29                           │    ║
║   │     4     │     1     │   0.03   │    30                           │    ║
║   ├───────────┼───────────┼──────────┼───────────                        │    ║
║   │  Total    │    30     │   1.00   │                                 │    ║
║   └───────────┴───────────┴──────────┴───────────                        │    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  DOT PLOT                                                           ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Number of Siblings                                                        ║
║                                                                              ║
║   0: ●●●●●●●●                                                               ║
║   1: ●●●●●●●●●●●●                                                          ║
║   2: ●●●●●●                                                                 ║
║   3: ●●●                                                                     ║
║   4: ●                                                                       ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  BAR CHART                                                           ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   12 │          ████                                                        ║
║   10 │          ████                                                        ║
║    8 │   ████   ████                                                        ║
║    6 │   ████   ████   ████                                                ║
║    4 │   ████   ████   ████                                                ║
║    2 │   ████   ████   ████   ████   ████                                  ║
║    0 └────────────────────────────────────────────────────────────────────   ║
║         0       1       2       3       4                                   ║
║                     Number of Siblings                                      ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 3.7 Class Intervals

> 📖 **Definition**: A **class interval** is the range of values used to group continuous observations into meaningful categories.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    CLASS INTERVAL SELECTION                                 ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  STEP-BY-STEP PROCESS                                               │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Step 1: Find Range                                                  │    ║
║   │  Range = Maximum - Minimum                                           │    ║
║   │  Example: 98 - 45 = 53                                               │    ║
║   │                                                                      │    ║
║   │  Step 2: Choose Number of Classes                                    │    ║
║   │  Sturges' Rule: k = 1 + 3.322 × log₁₀(n)                           │    ║
║   │  For n = 30: k = 1 + 3.322 × 1.477 = 5.91 ≈ 6                      │    ║
║   │                                                                      │    ║
║   │  Step 3: Calculate Class Width                                       │    ║
║   │  Class Width = Range / Number of Classes                            │    ║
║   │  53 / 6 = 8.83 ≈ 9                                                  │    ║
║   │                                                                      │    ║
║   │  Step 4: Create Intervals                                            │    ║
║   │  40-48, 49-57, 58-66, 67-75, 76-84, 85-93, 94-102                  │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  ALTERNATIVE METHODS FOR CLASS NUMBER                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Method              │ Formula                │ Example (n=30)      │    ║
║   ├──────────────────────┼────────────────────────┼─────────────────────┤    ║
║   │  Sturges' Rule       │ k = 1 + 3.322 log₁₀(n)│ 6                   │    ║
║   │  Square Root         │ k = √n                 │ 5.5 ≈ 6             │    ║
║   │  Rice Rule           │ k = 2 × ³√n            │ 6.2 ≈ 6             │    ║
║   │  Scott's Rule        │ h = 3.49σ × n⁻¹/³     │ Data-dependent      │    ║
║   │  Freedman-Diaconis  │ h = 2×IQR × n⁻¹/³     │ Data-dependent      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 3.8 Class Boundaries

> 📖 **Definition**: **Class boundaries** represent the true limits separating adjacent class intervals by eliminating any gaps between them.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    CLASS BOUNDARIES                                         ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  EXAMPLE: Age Groups                                                │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Class Interval  │ Lower Boundary │ Upper Boundary │ Class Width    │    ║
║   ├──────────────────┼────────────────┼────────────────┼───────────────┤    ║
║   │  20-29           │     19.5       │     29.5       │      10        │    ║
║   │  30-39           │     29.5       │     39.5       │      10        │    ║
║   │  40-49           │     39.5       │     49.5       │      10        │    ║
║   │  50-59           │     49.5       │     59.5       │      10        │    ║
║   │  60-69           │     59.5       │     69.5       │      10        │    ║
║   └──────────────────┴────────────────┴────────────────┴───────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  FORMULAS                                                            ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Lower Boundary = Lower Limit - 0.5                                        ║
║   Upper Boundary = Upper Limit + 0.5                                        ║
║   Class Width = Upper Boundary - Lower Boundary                            ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  VISUAL REPRESENTATION                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌──────┐  ┌──────┐  ┌──────┐  ┌──────┐  ┌──────┐                       ║
║   │19.5-29.5││29.5-39.5││39.5-49.5││49.5-59.5││59.5-69.5│                 ║
║   └──────┘  └──────┘  └──────┘  └──────┘  └──────┘                       ║
║      ↑         ↑         ↑         ↑         ↑                            ║
║   Boundaries  Boundaries  Boundaries  Boundaries  Boundaries               ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 3.9 Class Midpoints

> 📖 **Definition**: The class midpoint represents the center of each class interval.

**Formula:**
$$ \text{Class Midpoint} = \frac{\text{Lower Class Limit} + \text{Upper Class Limit}}{2} $$

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    CLASS MIDPOINTS                                          ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  EXAMPLE: Age Groups                                                │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Class Interval │ Lower Limit │ Upper Limit │ Midpoint Calculation │   ║
║   ├──────────────────┼─────────────┼─────────────┼─────────────────────┤   ║
║   │  20-29           │     20      │     29      │  (20+29)/2 = 24.5   │   ║
║   │  30-39           │     30      │     39      │  (30+39)/2 = 34.5   │   ║
║   │  40-49           │     40      │     49      │  (40+49)/2 = 44.5   │   ║
║   │  50-59           │     50      │     59      │  (50+59)/2 = 54.5   │   ║
║   │  60-69           │     60      │     69      │  (60+69)/2 = 64.5   │   ║
║   └──────────────────┴─────────────┴─────────────┴─────────────────────┘   ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  APPLICATION IN FREQUENCY POLYGON                                    ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Frequency                                                                ║
║   12 │                           ●                                         ║
║   10 │                        ●                                            ║
║    8 │                     ●                                               ║
║    6 │                  ●                                                  ║
║    4 │               ●                                                     ║
║    2 │            ●                                                        ║
║    0 └────────────────────────────────────────────────────────────────────   ║
║       24.5  34.5  44.5  54.5  64.5                                          ║
║                       Class Midpoints                                       ║
║                                                                              ║
║   Key Points:                                                               ║
║   • Midpoints represent the "typical" value in each class                   ║
║   • Used in calculating grouped mean                                        ║
║   • Essential for frequency polygon construction                            ║
║   • Important for grouped data analysis                                    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## 4. Data Visualization

### 4.1 Histograms

> 📖 **Definition**: A **histogram** is a graphical display of the frequency distribution of a continuous numerical variable. Unlike a bar chart, histogram bars are **adjacent**, indicating continuous data.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    HISTOGRAM SHAPES                                         ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  SYMMETRIC (Normal Distribution)                                    ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║           █                                                                  ║
║         █████                                                                ║
║       █████████                                                              ║
║     █████████████                                                            ║
║   █████████████████                                                          ║
║     █████████████                                                            ║
║       █████████                                                              ║
║         █████                                                                ║
║           █                                                                  ║
║   Mean = Median = Mode                                                       ║
║   Skewness = 0                                                               ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  RIGHT-SKEWED (Positive Skew)                                        ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║             █                                                                ║
║           ████                                                               ║
║         ███████                                                              ║
║       ██████████                                                             ║
║     █████████████                                                            ║
║   ████████████████                                                           ║
║   Mean > Median > Mode                                                       ║
║   Long right tail                                                            ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  LEFT-SKEWED (Negative Skew)                                         ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║           █                                                                  ║
║         █████                                                                ║
║       █████████                                                              ║
║     █████████████                                                            ║
║   █████████████████                                                          ║
║     █████████████                                                            ║
║       █████████                                                              ║
║         █████                                                                ║
║           █                                                                  ║
║   Mean < Median < Mode                                                       ║
║   Long left tail                                                             ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  BIMODAL DISTRIBUTION                                                ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║         ████                    ████                                         ║
║       ████████                ████████                                       ║
║     ████████████            ████████████                                     ║
║   ████████████████        ████████████████                                   ║
║   Two peaks, two modes                                                       ║
║   May indicate mixed populations                                             ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  UNIFORM DISTRIBUTION                                                ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ██████████████████████████████████████████████████████████████████████   ║
║   ██████████████████████████████████████████████████████████████████████   ║
║   ██████████████████████████████████████████████████████████████████████   ║
║   ██████████████████████████████████████████████████████████████████████   ║
║   Equal frequencies across all values                                        ║
║   No mode, flat distribution                                                 ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.2 Frequency Polygon

> 📖 **Definition**: A **frequency polygon** is a line graph constructed by plotting the **class midpoints** on the x-axis against their corresponding **frequencies** on the y-axis and connecting the points with straight lines.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    FREQUENCY POLYGON                                        ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  FREQUENCY POLYGON OF AGE DISTRIBUTION                              │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Frequency                                                           │    ║
║   │   20 │                                ●                              │    ║
║   │   18 │                             ●    ●                           │    ║
║   │   16 │                          ●          ●                        │    ║
║   │   14 │                       ●                ●                     │    ║
║   │   12 │                    ●                      ●                  │    ║
║   │   10 │                 ●                            ●               │    ║
║   │    8 │              ●                                  ●            │    ║
║   │    6 │           ●                                        ●         │    ║
║   │    4 │        ●                                              ●      │    ║
║   │    2 │     ●                                                    ●   │    ║
║   │    0 │●──────────────────────────────────────────────────────────●   │    ║
║   │       14.5  24.5  34.5  44.5  54.5  64.5  74.5  84.5  94.5        │    ║
║   │                         Class Midpoints                            │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  KEY FEATURES                                                        ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Points at class midpoints                                               ║
║   ✅ Lines connect the points                                                ║
║   ✅ Starts and ends at baseline (zero frequency)                           ║
║   ✅ Shows overall distribution trend                                        ║
║   ✅ Easier to compare multiple distributions                               ║
║   ✅ Smoother appearance than histogram                                     ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  COMPARISON WITH HISTOGRAM                                           ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Histogram                  │ Frequency Polygon                            ║
║   ───────────────────────────┼───────────────────────────────────────────── ║
║   Bars represent frequencies │ Points connected by lines                   ║
║   Best for showing shape    │ Best for showing trends                      ║
║   Single distribution        │ Multiple distributions overlaid              ║
║   Absolute frequencies       │ Can show relative frequencies                ║
║   More detailed              │ Smoother appearance                          ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.3 Ogive (Cumulative Frequency Curve)

> 📖 **Definition**: An **ogive**, also known as a **cumulative frequency curve**, is a line graph that displays the cumulative frequency of a dataset across class intervals.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    OGIVE (Cumulative Frequency Curve)                       ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  OGIVE OF TEST SCORES                                               │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Cumulative Frequency                                                │    ║
║   │   60 │                                         ●                     │    ║
║   │   50 │                                      ●                       │    ║
║   │   40 │                                   ●                          │    ║
║   │   30 │                                ●                             │    ║
║   │   20 │                             ●                                │    ║
║   │   10 │                          ●                                   │    ║
║   │    0 │●────────────────────────────────────────────────────────────   │    ║
║   │       20   30   40   50   60   70   80   90   100                   │    ║
║   │                        Upper Class Boundaries                        │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  KEY FEATURES                                                        ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Uses upper class boundaries                                             ║
║   ✅ Always increases (non-decreasing)                                      ║
║   ✅ Starts at 0                                                             ║
║   ✅ Ends at total frequency (n)                                             ║
║   ✅ Used for finding percentiles                                           ║
║   ✅ Shows "at most" cumulative frequencies                                 ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  FINDING PERCENTILES WITH OGIVE                                      ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   To find the 75th percentile:                                               ║
║   1. Draw horizontal line at 75% of n                                        ║
║   2. Find intersection with ogive                                            ║
║   3. Read value on x-axis                                                    ║
║   4. This gives the 75th percentile                                         ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.4 Bar Chart

> 📖 **Definition**: A **bar chart** (or **bar graph**) is a graphical representation of **categorical data** using rectangular bars of equal width. Unlike histograms, **bars are separated by gaps**.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    BAR CHART                                                ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  BAR CHART: Blood Type Distribution                                │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Frequency                                                           │    ║
║   │   35 │         ████                                                  │    ║
║   │   30 │         ████           ████                                   │    ║
║   │   25 │         ████           ████                                   │    ║
║   │   20 │         ████           ████           ████                    │    ║
║   │   15 │         ████           ████           ████                    │    ║
║   │   10 │         ████           ████           ████     ████          │    ║
║   │    5 │         ████           ████           ████     ████   ████   │    ║
║   │    0 └──────────────────────────────────────────────────────────────│    ║
║   │           O+            A+            B+           AB+     O- A-   │    ║
║   │                          Blood Type                                 │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  KEY FEATURES                                                        ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Equal width bars                                                        ║
║   ✅ Gaps between bars                                                       ║
║   ✅ Used for categorical data                                               ║
║   ✅ Easy to compare categories                                              ║
║   ✅ Can be vertical or horizontal                                           ║
║   ✅ Can show absolute or relative frequencies                               ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  BAR CHART VS HISTOGRAM                                              ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Feature          │ Bar Chart              │ Histogram                      ║
║  ──────────────────┼────────────────────────┼─────────────────────────────── ║
║   Data Type        │ Categorical            │ Quantitative/Continuous        ║
║   Bar Spacing      │ Gaps between bars      │ No gaps between bars           ║
║   Bar Width        │ Fixed (arbitrary)      │ Represents class width         ║
║   Order of Bars    │ Can be reordered       │ Fixed by class intervals       ║
║   Purpose          │ Compare categories     │ Show distribution shape        ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.5 Pie Chart

> 📖 **Definition**: A pie chart is a circular graph showing proportions of a whole.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    PIE CHART                                                ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  PIE CHART: Blood Type Distribution                                │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │                                                                      │    ║
║   │                   ╔═══════════════════════════════════╗              │    ║
║   │                  ╔╝                                   ╚╗             │    ║
║   │                  ║    O+ (35%)    ████████████████████  ║             │    ║
║   │                  ║                                     ║             │    ║
║   │              B-   ║  A+ (28%)      ████████████████    ║             │    ║
║   │             1%    ║                                     ║             │    ║
║   │                   ║                                     ║             │    ║
║   │              A-   ║                                     ║   O- 4%    │    ║
║   │             2%    ║                                     ║             │    ║
║   │                   ║                                     ║             │    ║
║   │                   ║  B+ (18%)    ███████████            ║             │    ║
║   │                   ║                                     ║             │    ║
║   │                   ╚╗                                   ╔╝             │    ║
║   │                    ╚═══════════════════════════════════╝              │    ║
║   │                         AB+ (12%)                                      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  KEY FEATURES                                                        ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Shows proportions of a whole                                            ║
║   ✅ Each slice represents a category                                       ║
║   ✅ Best for few categories (≤ 6)                                          ║
║   ✅ Easy to see relative sizes                                              ║
║   ✅ Use percentages for labels                                              ║
║   ✅ Color coding enhances readability                                      ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  BEST PRACTICES                                                      ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Start at 12 o'clock                                                     ║
║   ✅ Order slices by size                                                    ║
║   ✅ Use contrasting colors                                                  ║
║   ✅ Include percentages                                                     ║
║   ✅ Don't use 3D effects                                                    ║
║   ✅ Limit to 6-8 categories                                                 ║
║   ✅ Consider using bar chart for many categories                            ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.6 Line Graph

> 📖 **Definition**: A line graph displays data points connected by straight lines.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    LINE GRAPH                                               ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  LINE GRAPH: Blood Pressure Over Time                              │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Blood Pressure (mmHg)                                               │    ║
║   │  150 │         ●                                                    │    ║
║   │  140 │      ●    ●                                                 │    ║
║   │  130 │   ●          ●                                              │    ║
║   │  120 │●               ●                                            │    ║
║   │  110 │                  ●                                          │    ║
║   │  100 │                     ●                                       │    ║
║   │   90 │                        ●                                    │    ║
║   │   80 │                           ●                                 │    ║
║   │      └──────────────────────────────────────────────────────────────│    ║
║   │        0    1    2    3    4    5    6    7    8                    │    ║
║   │                           Time (hours)                              │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  USES                                                                ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Time series data                                                        ║
║   ✅ Trends over time                                                       ║
║   ✅ Comparing changes across groups                                        ║
║   ✅ Showing continuous data                                                ║
║   ✅ Multiple series on same graph                                          ║
║   ✅ Identifying patterns and cycles                                        ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  MULTIPLE LINE GRAPHS                                                ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Value                                                                     ║
║   15 │                    ● ─ ─ ─ ─ ─ ─ ─ ─ ─ ●                           ║
║   10 │         ● ─ ─ ─ ─ ─ ─ ─ ─ ●                                         ║
║    5 │● ─ ─ ─ ─ ─ ─ ●                                                      ║
║    0 └────────────────────────────────────────────────────────────────────   ║
║       1    2    3    4    5    6    7    8    9   10                      ║
║                           Time                                               ║
║   ─── Group A    ─── Group B    ─── Group C                                 ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.7 Stem-and-Leaf Plot

> 📖 **Definition**: A stem-and-leaf plot retains original data values while showing distribution.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    STEM-AND-LEAF PLOT                                       ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  STEM-AND-LEAF PLOT: Test Scores (n=30)                            │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Stem │ Leaf                          │ Frequency                   │    ║
║   ├───────┼───────────────────────────────┼─────────────                │    ║
║   │   4   │ 5                             │     1                       │    ║
║   │   5   │ 2 8                           │     2                       │    ║
║   │   6   │ 1 3 7 8                       │     4                       │    ║
║   │   7   │ 0 2 3 4 5 6 7 8 9           │     9                       │    ║
║   │   8   │ 0 1 2 3 4 5 6 7 8 9         │    10                       │    ║
║   │   9   │ 0 2 4 8                      │     4                       │    ║
║   └───────┴───────────────────────────────┴─────────────                │    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  DATA RECONSTRUCTION                                                 ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Data: 45, 52, 58, 61, 63, 67, 68, 70, 72, 73, 74, 75, 76, 77, 78, 79,   ║
║          80, 81, 82, 83, 84, 85, 86, 87, 88, 89, 90, 92, 94, 98            ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  ADVANTAGES                                                          ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Retains all original data values                                       ║
║   ✅ Shows distribution shape                                               ║
║   ✅ Identifies gaps and clusters                                          ║
║   ✅ Easy to construct by hand                                              ║
║   ✅ Useful for small to moderate datasets                                  ║
║   ✅ Helps identify outliers                                                ║
║   ✅ Can be split for more detail (split stems)                            ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.8 Dot Plot

> 📖 **Definition**: A dot plot uses dots on a simple scale to show data distribution.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    DOT PLOT                                                 ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  DOT PLOT: Blood Pressure Readings (n=20)                          │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  110  115  120  125  130  135  140  145  150  155  160              │    ║
║   │   │    │    │    │    │    │    │    │    │    │    │              │    ║
║   │                   ●    ●                                           │    ║
║   │              ●    ●    ●    ●                                      │    ║
║   │         ●    ●    ●    ●    ●    ●                                 │    ║
║   │    ●    ●    ●    ●    ●    ●    ●    ●    ●                       │    ║
║   │ ●  ●    ●    ●    ●    ●    ●    ●    ●    ●    ●                  │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  CHARACTERISTICS                                                    ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ One dot per observation                                                 ║
║   ✅ Stacked dots for repeated values                                        ║
║   ✅ Good for small datasets (n < 50)                                        ║
║   ✅ Shows exact values                                                     ║
║   ✅ Easy to see distribution                                               ║
║   ✅ Quick to construct                                                     ║
║   ✅ Useful for comparing distributions                                      ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  COMPARATIVE DOT PLOTS                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Group A:  ●●●●   ●●●●●   ●●                                              ║
║   Group B:    ●●   ●●●●●●●  ●●●                                            ║
║   Group C:      ●   ●●●   ●●●●●●                                           ║
║              ───────────────────────────                                   ║
║              10  15  20  25  30  35  40                                   ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.9 Box Plot

> 📖 **Definition**: A box plot displays the five-number summary of data.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    BOX PLOT                                                 ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  BOX PLOT: Blood Pressure by Treatment Group                       │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │         Outlier                                                      │    ║
║   │            ●                                                         │    ║
║   │         ──────                                                       │    ║
║   │         │     │                                                      │    ║
║   │         │     │                                                      │    ║
║   │         │     │                                                      │    ║
║   │         │     │ ← Upper Fence (Q3 + 1.5×IQR)                        │    ║
║   │         ──────                                                       │    ║
║   │         │ ███ │                                                      │    ║
║   │         │ ███ │ ← Q3 (75th percentile)                               │    ║
║   │         │ ███ │                                                      │    ║
║   │         │█████│                                                      │    ║
║   │         │█████│ ← Median (50th percentile)                           │    ║
║   │         │ ███ │                                                      │    ║
║   │         │ ███ │                                                      │    ║
║   │         │ ███ │                                                      │    ║
║   │         ──────                                                       │    ║
║   │         │     │                                                      │    ║
║   │         │     │ ← Q1 (25th percentile)                               │    ║
║   │         │     │                                                      │    ║
║   │         ──────                                                       │    ║
║   │         │     │ ← Lower Fence (Q1 - 1.5×IQR)                        │    ║
║   │            ●                                                         │    ║
║   │         Outlier                                                      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  COMPONENTS                                                          ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Box: IQR (Q3 - Q1)                                                    ║
║   ✅ Line: Median                                                           ║
║   ✅ Whiskers: 1.5 × IQR from Q1 and Q3                                    ║
║   ✅ Points: Outliers (beyond whiskers)                                    ║
║   ✅ Shows skewness                                                         ║
║   ✅ Good for comparing groups                                              ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  INTERPRETATION GUIDE                                                ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Symmetric:  Median centered in box, whiskers equal length          │    ║
║   │  Right-skew: Median closer to Q1, longer upper whisker              │    ║
║   │  Left-skew:  Median closer to Q3, longer lower whisker              │    ║
║   │  Outliers:   Points beyond 1.5×IQR                                  │    ║
║   │  Spread:     Wider box = more variable                              │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.10 Scatter Plot

> 📖 **Definition**: A scatter plot shows the relationship between two quantitative variables.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    SCATTER PLOT                                             ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  SCATTER PLOT: Blood Pressure vs Age                                │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Blood Pressure (mmHg)                                               │    ║
║   │  180 │                 ●                                            │    ║
║   │  160 │          ●  ●  ●    ●                                       │    ║
║   │  140 │      ●  ●  ●  ●  ●  ●  ●                                    │    ║
║   │  120 │   ●  ●  ●  ●  ●  ●  ●  ●    ●                              │    ║
║   │  100 │●  ●  ●  ●  ●  ●  ●  ●  ●  ●  ●                              │    ║
║   │   80 │●  ●  ●  ●  ●  ●  ●  ●  ●  ●  ●                              │    ║
║   │   60 │ ●  ●  ●  ●  ●  ●  ●  ●  ●  ●                               │    ║
║   │   40 │    ●  ●  ●  ●  ●  ●  ●                                      │    ║
║   │      └──────────────────────────────────────────────────────────────│    ║
║   │       20   30   40   50   60   70   80                              │    ║
║   │                           Age (years)                                │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  CORRELATION PATTERNS                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Positive Correlation           Negative Correlation                       ║
║      ●                             ●                                        ║
║     ● ●                         ● ●                                         ║
║    ●   ●                       ●   ●                                        ║
║   ●     ●                     ●     ●                                       ║
║  ●       ●                   ●       ●                                      ║
║ ●         ●                 ●         ●                                     ║
║                                                                              ║
║   No Correlation                Strong Correlation                           ║
║    ●   ●                         ●●●●                                      ║
║   ● ● ● ●                     ●●●●●●                                       ║
║  ● ● ● ● ●                  ●●●●●●●●                                        ║
║   ● ● ● ●                   ●●●●●●●                                         ║
║    ●   ●                      ●●●●                                          ║
║   ● ● ● ●                     ●●●●                                          ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.11 Heatmap

> 📖 **Definition**: A heatmap uses colors to represent data values in a matrix format.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    HEATMAP                                                   ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  CORRELATION HEATMAP                                                │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │              Age    BP    BMI   Chol  Glu                           │    ║
║   │          ┌──────────────────────────────────────┐                   │    ║
║   │   Age    │ 1.00  0.65  0.45  0.30  0.20       │                   │    ║
║   │   BP     │ 0.65  1.00  0.55  0.40  0.25       │                   │    ║
║   │   BMI    │ 0.45  0.55  1.00  0.35  0.15       │  Color Scale       │    ║
║   │   Chol   │ 0.30  0.40  0.35  1.00  0.10       │  ──────────────    │    ║
║   │   Glu    │ 0.20  0.25  0.15  0.10  1.00       │  ████  1.0         │    ║
║   │          └──────────────────────────────────────┘  ████  0.8         │    ║
║   │                                                   ████  0.6         │    ║
║   │                                                   ████  0.4         │    ║
║   │                                                   ████  0.2         │    ║
║   │                                                   ████  0.0         │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  APPLICATIONS                                                        ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Correlation matrices                                                     ║
║   ✅ Gene expression data                                                     ║
║   ✅ Spatial data                                                             ║
║   ✅ Time-series patterns                                                     ║
║   ✅ Confusion matrices                                                       ║
║   ✅ Missing data visualization                                               ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 4.12 Violin Plot

> 📖 **Definition**: A violin plot combines box plot features with kernel density estimation to show distribution shape.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    VIOLIN PLOT                                              ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  VIOLIN PLOT: Age Distribution by Treatment Group                  │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  80 │                          ████████████████                    │    ║
║   │  70 │                        ███████████████████                   │    ║
║   │  60 │                       ████████████████████                   │    ║
║   │  50 │                      █████████████████████                   │    ║
║   │  40 │              ███████████████████████████████                 │    ║
║   │  30 │            ██████████████████████████████████                │    ║
║   │  20 │           ████████████████████████████████████               │    ║
║   │     └─────────────────────────────────────────────────────────────   │    ║
║   │         Placebo    Low Dose    High Dose                            │    ║
║   │                          Treatment Group                            │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  FEATURES                                                            ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Shows full distribution shape                                          ║
║   ✅ Includes box plot inside                                               ║
║   ✅ Better than box plot for multimodal data                              ║
║   ✅ Good for comparing groups                                              ║
║   ✅ Shows density of data                                                  ║
║   ✅ Wider sections indicate more data points                               ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  VIOLIN VS BOX PLOT                                                  ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Feature          │ Box Plot              │ Violin Plot                    ║
║  ──────────────────┼────────────────────────┼─────────────────────────────── ║
║   Distribution     │ Only summary          │ Full shape                     ║
║   Multimodality    │ Not shown             │ Clearly visible                ║
║   Outliers         │ Explicit              │ Sometimes shown                ║
║   Sample size      │ N/A                   │ Width indicates density        ║
║   Complexity       │ Simple                │ More complex                   ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## 5. Exploratory Data Analysis

### 5.1 Exploratory Data Analysis (EDA)

> 📖 **Definition**: EDA is an approach to analyzing datasets to summarize their main characteristics, often with visual methods.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                         EDA WORKFLOW                                        ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │                    COMPLETE EDA WORKFLOW                            │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │   1. Data Collection                                                  │    ║
║   │      └───▶ Raw data gathering                                        │    ║
║   │                                                                      │    ║
║   │   2. Data Cleaning                                                   │    ║
║   │      └───▶ Missing values, duplicates, errors                        │    ║
║   │                                                                      │    ║
║   │   3. Univariate Analysis                                              │    ║
║   │      └───▶ Single variable distributions                              │    ║
║   │                                                                      │    ║
║   │   4. Bivariate Analysis                                               │    ║
║   │      └───▶ Relationships between pairs of variables                  │    ║
║   │                                                                      │    ║
║   │   5. Multivariate Analysis                                            │    ║
║   │      └───▶ Interactions between multiple variables                   │    ║
║   │                                                                      │    ║
║   │   6. Pattern Discovery                                                │    ║
║   │      └───▶ Identifying interesting patterns                         │    ║
║   │                                                                      │    ║
║   │   7. Hypothesis Generation                                            │    ║
║   │      └───▶ Formulating research questions                            │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  EDA CHECKLIST                                                      ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Understand data structure and types                                   ║
║   ✅ Identify data quality issues                                          ║
║   ✅ Explore distributions                                                ║
║   ✅ Detect outliers                                                      ║
║   ✅ Understand relationships                                              ║
║   ✅ Formulate hypotheses                                                 ║
║   ✅ Guide modeling approach                                               ║
║   ✅ Communicate findings                                                ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 5.2 Data Cleaning

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                         DATA CLEANING CHECKLIST                            ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  DATA QUALITY ISSUES AND SOLUTIONS                                 │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  ❌ Missing Values          → Impute or remove                      │    ║
║   │     • MCAR (Completely Random)                                      │    ║
║   │     • MAR (Random with covariates)                                  │    ║
║   │     • MNAR (Systematic missingness)                                 │    ║
║   │                                                                      │    ║
║   │  ❌ Duplicate Records       → Remove duplicates                     │    ║
║   │     • Exact duplicates                                               │    ║
║   │     • Near duplicates                                               │    ║
║   │                                                                      │    ║
║   │  ❌ Inconsistent Formats    → Standardize formats                   │    ║
║   │     • Date formats                                                  │    ║
║   │     • Text case                                                    │    ║
║   │     • Units                                                         │    ║
║   │                                                                      │    ║
║   │  ❌ Outliers                → Investigate and handle                │    ║
║   │     • Univariate outliers                                            │    ║
║   │     • Multivariate outliers                                         │    ║
║   │                                                                      │    ║
║   │  ❌ Data Entry Errors       → Correct or remove                     │    ║
║   │     • Typographical errors                                           │    ║
║   │     • Coding errors                                                 │    ║
║   │     • Logical inconsistencies                                       │    ║
║   │                                                                      │    ║
║   │  ❌ Incorrect Coding        → Recode correctly                      │    ║
║   │     • Wrong data type                                               │    ║
║   │     • Wrong scale                                                   │    ║
║   │     • Wrong categories                                              │    ║
║   │                                                                      │    ║
║   │  ❌ Impossible Values       → Investigate                           │    ║
║   │     • Age = 200                                                    │    ║
║   │     • Weight = 0                                                   │    ║
║   │     • Height = -5                                                  │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 5.3 Missing Data

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    MISSING DATA HANDLING                                    ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  TYPES OF MISSING DATA                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  MCAR (Missing Completely at Random)                                │    ║
║   │  • Missingness unrelated to any variable                            │    ║
║   │  • Data are missing randomly                                        │    ║
║   │  • Least problematic                                                │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  MAR (Missing at Random)                                            │    ║
║   │  • Missingness related to observed variables                        │    ║
║   │  • Can be handled with proper methods                               │    ║
║   │  • Most common in real data                                         │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  MNAR (Missing Not at Random)                                       │    ║
║   │  • Missingness related to unobserved values                         │    ║
║   │  • Most problematic                                                 │    ║
║   │  • Requires sensitivity analysis                                    │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  HANDLING METHODS                                                    ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   1. LISTWISE DELETION                                                       ║
║      • Remove all cases with missing values                                 ║
║      • Simple but reduces sample size                                       ║
║      • Only valid if MCAR                                                  ║
║                                                                              ║
║   2. MEAN/MEDIAN IMPUTATION                                                  ║
║      • Replace missing with mean or median                                  ║
║      • Simple but reduces variance                                          ║
║      • Can bias results                                                     ║
║                                                                              ║
║   3. REGRESSION IMPUTATION                                                    ║
║      • Predict missing values using other variables                         ║
║      • More sophisticated                                                   ║
║      • Assumes relationships                                                ║
║                                                                              ║
║   4. MULTIPLE IMPUTATION                                                     ║
║      • Create multiple imputed datasets                                     ║
║      • Combine results                                                      ║
║      • Most sophisticated                                                   ║
║      • Preferred method                                                     ║
║                                                                              ║
║   5. INDICATOR VARIABLES                                                    ║
║      • Create missing indicator column                                      ║
║      • Include in analysis                                                  ║
║      • Useful for MNAR                                                     ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 5.4 Outlier Detection

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    OUTLIER DETECTION METHODS                                ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  1. Z-SCORE METHOD                                                   ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   • Z = (x - μ) / σ                                                        ║
║   • |Z| > 3 → Outlier                                                      ║
║   • Assumes normality                                                      ║
║   • For symmetric data                                                    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  2. IQR METHOD                                                        ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   • Q1 - 1.5×IQR (Lower fence)                                             ║
║   • Q3 + 1.5×IQR (Upper fence)                                             ║
║   • Any value outside fences → Outlier                                      ║
║   • Robust method                                                          ║
║   • No distribution assumption                                             ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  3. VISUALIZATION                                                     ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   • Boxplots show outliers                                                 ║
║   • Scatter plots show unusual points                                      ║
║   • Histograms show extreme values                                        ║
║   • QQ plots show distribution deviations                                 ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  4. MULTIVARIATE METHODS                                             ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   • Mahalanobis distance                                                   ║
║   • Cook's distance                                                         ║
║   • Leverage values                                                        ║
║   • Clustering methods                                                     ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  OUTLIER HANDLING                                                     ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Investigate cause                                                      ║
║   ✅ Verify data entry                                                      ║
║   ✅ Consider transformation                                               ║
║   ✅ Robust methods                                                        ║
║   ✅ Winsorization                                                         ║
║   ✅ Remove only if justified                                             ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 5.5 Five Number Summary

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    FIVE NUMBER SUMMARY                                      ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  EXAMPLE: Blood Pressure Data (n=20)                               │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Component    │ Value   │ Interpretation                             │    ║
║   ├───────────────┼─────────┼───────────────────────────────────────────┤    ║
║   │  Minimum      │  118    │ Lowest blood pressure                     │    ║
║   │  Q1           │  121.5  │ 25% of data below this                    │    ║
║   │  Median       │  126.5  │ 50th percentile, middle value             │    ║
║   │  Q3           │  139.5  │ 75% of data below this                    │    ║
║   │  Maximum      │  150    │ Highest blood pressure                    │    ║
║   ├───────────────┼─────────┼───────────────────────────────────────────┤    ║
║   │  IQR          │   18    │ Q3 - Q1 = 139.5 - 121.5                   │    ║
║   │  Range        │   32    │ 150 - 118                                  │    ║
║   └───────────────┴─────────┴───────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  BOX PLOT REPRESENTATION                                             ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   150 │                               ●                                    ║
║   145 │                         ────────                                   ║
║   140 │                         │       │                                   ║
║   135 │                         │  ███  │                                   ║
║   130 │                         │███████│                                   ║
║   125 │                         │  ███  │                                   ║
║   120 │                         ────────                                   ║
║   115 │                         │       │                                   ║
║       └──────────────────────────────────────────────────────────────       ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 5.6 Quartiles

> 📖 **Definition**: Quartiles divide data into four equal parts.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                         QUARTILE DIVISION                                  ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  EXAMPLE: Test Scores (n=12)                                       │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Data: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12                       │    ║
║   │                                                                      │    ║
║   │  Q1 = 3.5 (25th percentile)                                          │    ║
║   │  Q2 = 6.5 (50th percentile = Median)                                 │    ║
║   │  Q3 = 9.5 (75th percentile)                                          │    ║
║   │                                                                      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  VISUAL REPRESENTATION                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ──────────────────────────────────────────────────────────────────────      ║
║   25%    │    25%    │    25%    │    25%                                   ║
║   Q1     │    Q2     │    Q3     │                                          ║
║   3.5    │    6.5    │    9.5    │                                          ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  QUARTILE CALCULATION METHODS                                        ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Method 1: (n+1)×p/100                                             │    ║
║   │  Q1 position = (12+1)×25/100 = 3.25 → 3.5                          │    ║
║   │  Q3 position = (12+1)×75/100 = 9.75 → 9.5                          │    ║
║   │                                                                      │    ║
║   │  Method 2: n×p/100 + 0.5                                            │    ║
║   │  Q1 position = 12×0.25 + 0.5 = 3.5 → 3.5                           │    ║
║   │  Q3 position = 12×0.75 + 0.5 = 9.5 → 9.5                           │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 5.7 Percentiles

> 📖 **Definition**: Percentiles divide data into 100 equal parts.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    PERCENTILES                                              ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  KEY PERCENTILES                                                    │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  1st percentile  → Very low values                                  │    ║
║   │  5th percentile  → Low values                                       │    ║
║   │ 25th percentile  → Q1 (Lower quartile)                              │    ║
║   │ 50th percentile  → Median                                           │    ║
║   │ 75th percentile  → Q3 (Upper quartile)                              │    ║
║   │ 95th percentile  → High values                                      │    ║
║   │ 99th percentile  → Very high values                                 │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  EXAMPLE: Interpreting Percentiles                                  ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   If a test score is at the 80th percentile:                                 ║
║   • 80% of students scored lower                                            ║
║   • 20% scored higher                                                       ║
║   • The score is above average                                              ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  APPLICATIONS                                                         ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Clinical reference ranges                                              ║
║   ✅ Growth charts                                                          ║
║   ✅ Test scoring (SAT, IQ)                                                ║
║   ✅ Health indicators                                                      ║
║   ✅ Risk assessment                                                       ║
║   ✅ Quality control                                                       ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 5.8 Correlation Analysis

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    CORRELATION ANALYSIS                                     ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  PEARSON CORRELATION (r)                                            ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   • Measures linear relationship                                            ║
║   • Range: -1 to +1                                                         ║
║   • Sensitive to outliers                                                   ║
║   • Assumes normality                                                       ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  INTERPRETATION OF r                                                 ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   │r│   Interpretation                                                       ║
║  ────────┼───────────────────────────────────────────────────────────────    ║
║   0.00   │ No correlation                                                    ║
║   0.00-0.19 │ Very weak                                                     ║
║   0.20-0.39 │ Weak                                                           ║
║   0.40-0.59 │ Moderate                                                       ║
║   0.60-0.79 │ Strong                                                         ║
║   0.80-0.99 │ Very strong                                                    ║
║   1.00   │ Perfect                                                           ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  ALTERNATIVE CORRELATION METHODS                                    ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Spearman's ρ: Rank-based, non-parametric                          │    ║
║   │  Kendall's τ: Concordance-based, non-parametric                    │    ║
║   │  Point-biserial: Continuous vs binary                              │    ║
║   │  Phi coefficient: Binary vs binary                                 │    ║
║   │  Cramér's V: Categorical vs categorical                            │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## 6. Distribution Shape

### 6.1 Distribution Shape

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    DISTRIBUTION SHAPES                                      ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  NORMAL (SYMMETRIC)                                                 ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║           █                                                                ║
║         █████                                                              ║
║       █████████                                                            ║
║     █████████████                                                          ║
║   █████████████████                                                        ║
║     █████████████                                                          ║
║       █████████                                                            ║
║         █████                                                              ║
║           █                                                                ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  RIGHT-SKEWED (POSITIVE SKEW)                                       ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║             █                                                              ║
║           ████                                                             ║
║         ███████                                                            ║
║       ██████████                                                           ║
║     █████████████                                                          ║
║   ████████████████                                                         ║
║   Mean > Median > Mode                                                     ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  LEFT-SKEWED (NEGATIVE SKEW)                                        ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   █                                                                        ║
║   ████                                                                     ║
║   ███████                                                                  ║
║   ██████████                                                               ║
║   █████████████                                                            ║
║   ████████████████                                                         ║
║   Mean < Median < Mode                                                     ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  BIMODAL                                                             ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║       ████                    ████                                          ║
║     ████████                ████████                                        ║
║   ████████████            ████████████                                      ║
║   ████████████████      ████████████████                                    ║
║   Two peaks, two modes                                                     ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  UNIFORM                                                             ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ██████████████████████████████████████████████████████████████████████   ║
║   Equal frequencies across all values                                        ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 6.2 Symmetry

> 📖 **Definition**: A distribution is symmetric if it is identical on both sides of its center.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    SYMMETRY PROPERTIES                                      ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  PROPERTIES OF SYMMETRIC DISTRIBUTIONS                              │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  ✅ Mean = Median = Mode                                             │    ║
║   │  ✅ Skewness = 0                                                     │    ║
║   │  ✅ Bell curve shape                                                 │    ║
║   │  ✅ Symmetric around center                                          │    ║
║   │  ✅ Equal tails                                                      │    ║
║   │  ✅ Examples: Normal, Uniform, T-distribution                       │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  VISUAL CHECK FOR SYMMETRY                                           ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ╔═══════════════════════════════════════════╗                             ║
║   ║              │             │              ║                             ║
║   ║              │    ████     │              ║                             ║
║   ║              │  ████████   │              ║                             ║
║   ║              │█████████████│              ║                             ║
║   ║              │█████████████│              ║                             ║
║   ║              │  ████████   │              ║                             ║
║   ║              │    ████     │              ║                             ║
║   ║              │             │              ║                             ║
║   ╚═══════════════════════════════════════════╝                             ║
║              ← Symmetric →                                                  ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 6.3 Left Skewness

> 📖 **Definition**: Left skewness occurs when the left tail is longer than the right tail.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    LEFT SKEWNESS PROPERTIES                                 ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  PROPERTIES OF LEFT-SKEWED DISTRIBUTIONS                            │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  ✅ Mean < Median < Mode                                             │    ║
║   │  ✅ Long left tail                                                    │    ║
║   │  ✅ Negative skewness                                                │    ║
║   │  ✅ Most values concentrated on right                                │    ║
║   │  ✅ Few low values (outliers)                                       │    ║
║   │  ✅ Examples: Age at death, Test scores (with low outliers)          │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  VISUAL REPRESENTATION                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║         █                                                                  ║
║       █████                                                                ║
║     █████████                                                              ║
║   █████████████                                                            ║
║   ████████████████                                                         ║
║   █████████████████                                                        ║
║   █████████████████                                                        ║
║   █████████████████                                                        ║
║   ←──Long left tail───┘                                                    ║
║                                                                              ║
║   Mode > Median > Mean                                                     ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 6.4 Right Skewness

> 📖 **Definition**: Right skewness occurs when the right tail is longer than the left tail.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    RIGHT SKEWNESS PROPERTIES                                ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  PROPERTIES OF RIGHT-SKEWED DISTRIBUTIONS                           │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  ✅ Mean > Median > Mode                                             │    ║
║   │  ✅ Long right tail                                                   │    ║
║   │  ✅ Positive skewness                                                │    ║
║   │  ✅ Most values concentrated on left                                 │    ║
║   │  ✅ Few high values (outliers)                                      │    ║
║   │  ✅ Examples: Income, Blood pressure, Hospital stay                  │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  VISUAL REPRESENTATION                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   █                                                                        ║
║   ████                                                                     ║
║   ███████                                                                  ║
║   ██████████                                                               ║
║   █████████████                                                            ║
║   ████████████████                                                         ║
║     ████████████████                                                       ║
║       ████████████████                                                     ║
║         ──Long right tail──▶                                               ║
║                                                                              ║
║   Mean > Median > Mode                                                     ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 6.5 Kurtosis

> 📖 **Definition**: Kurtosis measures the "tailedness" of a probability distribution.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                         KURTOSIS TYPES                                      ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  LEPTOKURTIC (Heavy Tails)                                          ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║       ██                                                                  ║
║     ██████                                                                ║
║   ██████████                                                              ║
║   ████████████                                                            ║
║   ████████████                                                            ║
║   ██████████                                                              ║
║     ██████                                                                ║
║       ██                                                                  ║
║   Kurtosis > 3                                                            ║
║   Heavy tails, peaked center                                               ║
║   More extreme outliers                                                    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  MESOKURTIC (Normal)                                                ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║         ██                                                                ║
║       ██████                                                              ║
║     ██████████                                                            ║
║   ██████████████                                                          ║
║   ██████████████                                                          ║
║     ██████████                                                            ║
║       ██████                                                              ║
║         ██                                                                ║
║   Kurtosis = 3                                                            ║
║   Normal tails, moderate peak                                              ║
║   Standard distribution                                                    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  PLATYKURTIC (Light Tails)                                          ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║         ██                                                                ║
║       ██████                                                              ║
║     ██████████                                                            ║
║   ██████████████                                                          ║
║   ██████████████                                                          ║
║     ██████████                                                            ║
║       ██████                                                              ║
║         ██                                                                ║
║   Kurtosis < 3                                                            ║
║   Light tails, flatter peak                                                ║
║   Fewer extreme outliers                                                   ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  EXCESS KURTOSIS                                                    ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Excess Kurtosis = Kurtosis - 3                                            ║
║   Positive: Leptokurtic (heavy tails)                                       ║
║   Zero: Mesokurtic (normal)                                                 ║
║   Negative: Platykurtic (light tails)                                       ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 6.6 Empirical Rule (68-95-99.7 Rule)

> 📖 **Definition**: For a normal distribution, approximately 68-95-99.7% of data fall within 1-2-3 standard deviations.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                          EMPIRICAL RULE                                     ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  NORMAL DISTRIBUTION WITH EMPIRICAL RULE                           │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │                        ████████████████████████                     │    ║
║   │                     ████████████████████████████████                │    ║
║   │                  ██████████████████████████████████████             │    ║
║   │                ████████████████████████████████████████████         │    ║
║   │              ██████████████████████████████████████████████████     │    ║
║   │            ████████████████████████████████████████████████████████ │    ║
║   │                                                                      │    ║
║   │   ──────┼───────┼───────┼───────┼───────┼───────┼───────┼───────   │    ║
║   │        μ-3σ    μ-2σ    μ-1σ      μ     μ+1σ    μ+2σ    μ+3σ       │    ║
║   │                                                                      │    ║
║   │       68% within μ ± 1σ                                              │    ║
║   │       95% within μ ± 2σ                                              │    ║
║   │     99.7% within μ ± 3σ                                             │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  PRACTICAL APPLICATIONS                                              ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Range        │ Percentage  │ Interpretation                               ║
║  ──────────────┼─────────────┼───────────────────────────────────────────── ║
║   μ ± 1σ       │   68.27%    │ Most data (roughly 2/3)                     ║
║   μ ± 2σ       │   95.45%    │ Almost all data (common range)              ║
║   μ ± 3σ       │   99.73%    │ Nearly all data (outlier detection)         ║
║   μ ± 4σ       │   99.99%    │ Virtually all data                          ║
║  ──────────────┼─────────────┼───────────────────────────────────────────── ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  EXAMPLE: Blood Pressure (μ=130, σ=10)                              ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   68% of people: 120 to 140 mmHg                                            ║
║   95% of people: 110 to 150 mmHg                                            ║
║   99.7% of people: 100 to 160 mmHg                                          ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 6.7 Chebyshev's Theorem

> 📖 **Definition**: For any distribution, at least 1 - 1/k² of data fall within k standard deviations of the mean.

$$ P(|X - \mu| < k\sigma) \geq 1 - \frac{1}{k^2} $$

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    CHEBYSHEV'S THEOREM                                      ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  KEY PROPERTIES                                                     │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  ✅ Applies to ANY distribution                                      │    ║
║   │  ✅ No normality assumption                                          │    ║
║   │  ✅ Conservative estimates                                           │    ║
║   │  ✅ Lower bound of data within kσ                                   │    ║
║   │  ✅ Works for all k > 1                                             │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  MINIMUM PERCENTAGES FOR DIFFERENT k                                ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   k      │ Minimum % within kσ  │ Formula                                   ║
║  ────────┼──────────────────────┼─────────────────────────────────────────  ║
║   1.5    │       55.6%          │ 1 - 1/(1.5²) = 1 - 0.444 = 0.556         ║
║   2.0    │       75.0%          │ 1 - 1/(2²) = 1 - 0.25 = 0.75             ║
║   2.5    │       84.0%          │ 1 - 1/(2.5²) = 1 - 0.16 = 0.84           ║
║   3.0    │       88.9%          │ 1 - 1/(3²) = 1 - 0.111 = 0.889           ║
║   4.0    │       93.75%         │ 1 - 1/(4²) = 1 - 0.0625 = 0.9375         ║
║   5.0    │       96.0%          │ 1 - 1/(5²) = 1 - 0.04 = 0.96             ║
║  ────────┼──────────────────────┼─────────────────────────────────────────  ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  COMPARISON WITH EMPIRICAL RULE                                     ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   k      │ Chebyshev (Any Dist.)  │ Empirical Rule (Normal)                 ║
║  ────────┼─────────────────────────┼───────────────────────────────────────  ║
║   2      │ At least 75%            │ Approximately 95%                     ║
║   3      │ At least 88.9%          │ Approximately 99.7%                   ║
║   4      │ At least 93.75%         │ Approximately 99.99%                  ║
║  ────────┼─────────────────────────┼───────────────────────────────────────  ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  PRACTICAL APPLICATION                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Given: Mean = 100, SD = 15                                                ║
║   Find: Range that contains at least 75% of data                          ║
║                                                                              ║
║   k = 2 (since 1 - 1/2² = 0.75)                                            ║
║   Range = μ ± 2σ = 100 ± 30 = [70, 130]                                   ║
║                                                                              ║
║   Interpretation: At least 75% of data lie between 70 and 130              ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 6.8 Normality Testing

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    NORMALITY TESTING                                        ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  VISUAL METHODS                                                      ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   1. Q-Q PLOT                                                               ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  3 │                         ●                                      │    ║
║   │  2 │                    ●                                           │    ║
║   │  1 │               ●                                                │    ║
║   │  0 │          ●                                                     │    ║
║   │ -1 │     ●                                                          │    ║
║   │ -2 │●                                                               │    ║
║   │    └──────────────────────────────────────────────────────────────│    ║
║   │      -3   -2   -1    0    1    2    3                              │    ║
║   │                     Theoretical Quantiles                           │    ║
║   │  Straight line = Normal distribution                                │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   2. HISTOGRAM WITH NORMAL CURVE                                            ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │        ████                                                         │    ║
║   │      ████████                                                       │    ║
║   │    ████████████                                                     │    ║
║   │  ████████████████                                                   │    ║
║   │  ████████████████  ─── Normal Curve                                 │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  STATISTICAL TESTS                                                  ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  Shapiro-Wilk: Best for small samples (n < 50)                     │    ║
║   │  Kolmogorov-Smirnov: Good for large samples                        │    ║
║   │  Anderson-Darling: Sensitive to tails                              │    ║
║   │  Jarque-Bera: Based on skewness and kurtosis                      │    ║
║   │  D'Agostino-Pearson: Combined skewness/kurtosis                   │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  INTERPRETATION                                                     ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   p-value > 0.05 → Fail to reject normality (not enough evidence)            ║
║   p-value ≤ 0.05 → Reject normality (evidence against normality)            ║
║   ⚠️ Caution: Large samples can reject normality for minor deviations       ║
║   ⚠️ Small samples may lack power to detect non-normality                  ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## 7. Data Presentation & Reporting

### 7.1 Data Summarization

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    DATA SUMMARIZATION                                       ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  PURPOSES OF DATA SUMMARIZATION                                     │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  📢 COMMUNICATION                                                    │    ║
║   │  • Presenting findings to audiences                                 │    ║
║   │  • Making results accessible                                        │    ║
║   │  • Storytelling with data                                           │    ║
║   │                                                                      │    ║
║   │  🎯 DECISION MAKING                                                  │    ║
║   │  • Supporting evidence-based decisions                              │    ║
║   │  • Informing policy and practice                                    │    ║
║   │  • Guiding resource allocation                                      │    ║
║   │                                                                      │    ║
║   │  🔍 PATTERN DISCOVERY                                               │    ║
║   │  • Identifying trends and patterns                                  │    ║
║   │  • Detecting anomalies                                              │    ║
║   │  • Generating hypotheses                                            │    ║
║   │                                                                      │    ║
║   │  ✅ QUALITY ASSESSMENT                                               │    ║
║   │  • Checking data quality                                            │    ║
║   │  • Verifying assumptions                                            │    ║
║   │  • Monitoring data collection                                       │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 7.2 Tabular Presentation

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    TABULAR PRESENTATION TYPES                               ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  1. FREQUENCY TABLES                                                 ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌─────────────┬─────────────┬──────────────────┬───────────┐              ║
║   │ Category    │ Frequency   │ Relative Freq.   │ Percentage│              ║
║   ├─────────────┼─────────────┼──────────────────┼───────────┤              ║
║   │ A           │    25       │      0.25        │   25%     │              ║
║   │ B           │    35       │      0.35        │   35%     │              ║
║   │ C           │    20       │      0.20        │   20%     │              ║
║   │ D           │    20       │      0.20        │   20%     │              ║
║   └─────────────┴─────────────┴──────────────────┴───────────┘              ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  2. CONTINGENCY TABLES                                              ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌───────────────────────────────┬───────────────┬───────────────┐        ║
║   │                               │   Treatment   │   Control     │        ║
║   ├───────────────────────────────┼───────────────┼───────────────┤        ║
║   │   Improved                    │     45        │     30        │        ║
║   │   Not Improved                │     15        │     30        │        ║
║   └───────────────────────────────┴───────────────┴───────────────┘        ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  3. SUMMARY TABLES                                                  ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌─────────────────┬───────────┬───────────┬───────────┬───────────┐      ║
║   │    Variable     │   Mean    │    SD     │   Median  │   Range   │      ║
║   ├─────────────────┼───────────┼───────────┼───────────┼───────────┤      ║
║   │   Age (years)   │   54.3    │   12.1    │   55.0    │   22-85   │      ║
║   │   BMI (kg/m²)   │   27.8    │    4.2    │   27.5    │   18-38   │      ║
║   │   SBP (mmHg)    │  134.5    │   14.6    │  132.0    │  110-160  │      ║
║   └─────────────────┴───────────┴───────────┴───────────┴───────────┘      ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 7.3 Reporting Mean ± SD

> 📖 **Definition**: Reporting mean with standard deviation is the standard format for normally distributed continuous data.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    REPORTING MEAN ± SD                                      ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  FORMAT                                                             │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Mean ± SD (n=XX)                                                    │    ║
║   │                                                                      │    ║
║   │  Example: Age: 54.3 ± 12.1 years (n=120)                            │    ║
║   │                                                                      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  GUIDELINES                                                          ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Use appropriate precision (1 decimal for continuous)                   ║
║   ✅ Always include sample size                                            ║
║   ✅ Check for normality before using                                      ║
║   ✅ Report with measure of dispersion                                     ║
║   ✅ Use consistent decimal places                                         ║
║   ✅ Consider reporting range as well                                      ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  WHEN TO USE                                                         ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Symmetric distributions                                                ║
║   ✅ Approximately normal data                                              ║
║   ✅ Continuous variables                                                   ║
║   ✅ When comparing group means                                            ║
║   ✅ In inferential statistics (t-tests, ANOVA)                            ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  EXAMPLE IN REPORT                                                   ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   "The mean age of participants was 54.3 years (SD = 12.1; n = 120),        ║
║   ranging from 22 to 85 years."                                             ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 7.4 Reporting Median (IQR)

> 📖 **Definition**: Reporting median with interquartile range is the standard format for skewed continuous data.

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    REPORTING MEDIAN (IQR)                                   ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  FORMAT                                                             │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  Median (IQR) [Min, Max]                                             │    ║
║   │                                                                      │    ║
║   │  Example: Length of stay: 5 (3-8) days [1-45]                       │    ║
║   │                                                                      │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  GUIDELINES                                                          ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Use for skewed data                                                    ║
║   ✅ Include Q1 and Q3 in parentheses                                       ║
║   ✅ May include full range                                                ║
║   ✅ Better than mean for skewed data                                      ║
║   ✅ Robust to outliers                                                    ║
║   ✅ Include sample size                                                   ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  WHEN TO USE                                                         ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Skewed distributions                                                   ║
║   ✅ Ordinal data                                                           ║
║   ✅ Non-normal continuous data                                            ║
║   ✅ When outliers present                                                 ║
║   ✅ In non-parametric tests                                               ║
║   ✅ For cost/hospital stay data                                           ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  EXAMPLE IN REPORT                                                   ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   "The median length of hospital stay was 5 days (IQR: 3-8; n=200),         ║
║   with a range of 1 to 45 days."                                            ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 7.5 Journal Reporting Standards

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    JOURNAL REPORTING STANDARDS                              ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  MAJOR GUIDELINES                                                   │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  📋 CONSORT                                                          │    ║
║   │  • Consolidated Standards of Reporting Trials                       │    ║
║   │  • For randomized controlled trials                                 │    ║
║   │  • 25-item checklist                                                 │    ║
║   │  • Flow diagram required                                             │    ║
║   │                                                                      │    ║
║   │  📋 STROBE                                                           │    ║
║   │  • Strengthening Reporting of Observational Studies                 │    ║
║   │  • For cohort, case-control, cross-sectional studies                │    ║
║   │  • 22-item checklist                                                 │    ║
║   │  • Study design specific                                             │    ║
║   │                                                                      │    ║
║   │  📋 PRISMA                                                           │    ║
║   │  • Preferred Reporting Items for Systematic Reviews                 │    ║
║   │  • For systematic reviews and meta-analyses                         │    ║
║   │  • 27-item checklist                                                 │    ║
║   │  • Flow diagram required                                             │    ║
║   │                                                                      │    ║
║   │  📋 STARD                                                            │    ║
║   │  • Standards for Reporting Diagnostic Accuracy Studies              │    ║
║   │  • For diagnostic test studies                                       │    ║
║   │  • 30-item checklist                                                 │    ║
║   │  • 2×2 tables required                                               │    ║
║   │                                                                      │    ║
║   │  📋 MOOSE                                                            │    ║
║   │  • Meta-analysis of Observational Studies in Epidemiology           │    ║
║   │  • For meta-analyses of observational studies                       │    ║
║   │  • 35-item checklist                                                 │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  GENERAL REQUIREMENTS                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ✅ Sample size for each analysis                                          ║
║   ✅ Appropriate precision                                                 ║
║   ✅ Complete reporting                                                    ║
║   ✅ Reproducibility                                                       ║
║   ✅ Transparency                                                          ║
║   ✅ Ethical considerations                                                ║
║   ✅ Funding disclosure                                                    ║
║   ✅ Conflict of interest                                                  ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 7.6 Publication Guidelines

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    PUBLICATION GUIDELINES                                   ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ┌─────────────────────────────────────────────────────────────────────┐    ║
║   │  MANUSCRIPT STRUCTURE                                               │    ║
║   ├─────────────────────────────────────────────────────────────────────┤    ║
║   │                                                                      │    ║
║   │  1. TITLE                                                           │    ║
║   │     • Concise and informative                                       │    ║
║   │     • Study design included                                         │    ║
║   │                                                                      │    ║
║   │  2. ABSTRACT                                                        │    ║
║   │     • Structured (Background, Methods, Results, Conclusion)         │    ║
║   │     • Key findings with numbers                                     │    ║
║   │     • Within word limit                                             │    ║
║   │                                                                      │    ║
║   │  3. INTRODUCTION                                                    │    ║
║   │     • Background and rationale                                      │    ║
║   │     • Literature review                                             │    ║
║   │     • Study objectives and hypotheses                               │    ║
║   │                                                                      │    ║
║   │  4. METHODS                                                         │    ║
║   │     • Study design and setting                                      │    ║
║   │     • Participants and sampling                                     │    ║
║   │     • Variables and measurements                                    │    ║
║   │     • Statistical analysis (descriptive)                            │    ║
║   │     • Software and version                                          │    ║
║   │                                                                      │    ║
║   │  5. RESULTS                                                         │    ║
║   │     • Participant flow and characteristics                          │    ║
║   │     • Descriptive statistics                                        │    ║
║   │     • Tables and figures                                            │    ║
║   │     • Key findings                                                  │    ║
║   │                                                                      │    ║
║   │  6. DISCUSSION                                                      │    ║
║   │     • Summary of findings                                           │    ║
║   │     • Comparison with literature                                    │    ║
║   │     • Strengths and limitations                                     │    ║
║   │     • Implications                                                  │    ║
║   │                                                                      │    ║
║   │  7. CONCLUSION                                                      │    ║
║   │     • Main conclusion                                               │    ║
║   │     • Future directions                                             │    ║
║   │                                                                      │    ║
║   │  8. REFERENCES                                                      │    ║
║   │     • Complete and accurate                                         │    ║
║   │     • Journal-specific format                                       │    ║
║   └─────────────────────────────────────────────────────────────────────┘    ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## 8. Software Implementation

### 8.1 R Implementation

```r
# ==============================================================================
# COMPREHENSIVE DESCRIPTIVE STATISTICS IN R
# ==============================================================================

# Load necessary libraries
library(dplyr)
library(ggplot2)
library(tidyr)
library(e1071)
library(psych)
library(rstatix)

# ==============================================================================
# 1. CORE DESCRIPTIVE STATISTICS FUNCTION
# ==============================================================================

descriptive_stats <- function(data, variable, group = NULL) {
  
  # Overall statistics
  if (is.null(group)) {
    result <- data %>%
      summarise(
        n = n(),
        mean = mean({{ variable }}, na.rm = TRUE),
        median = median({{ variable }}, na.rm = TRUE),
        sd = sd({{ variable }}, na.rm = TRUE),
        se = sd / sqrt(n),
        min = min({{ variable }}, na.rm = TRUE),
        max = max({{ variable }}, na.rm = TRUE),
        range = max - min,
        q1 = quantile({{ variable }}, 0.25, na.rm = TRUE),
        q3 = quantile({{ variable }}, 0.75, na.rm = TRUE),
        iqr = IQR({{ variable }}, na.rm = TRUE),
        skew = skewness({{ variable }}, na.rm = TRUE),
        kurt = kurtosis({{ variable }}, na.rm = TRUE),
        cv = (sd / mean) * 100,
        missing = sum(is.na({{ variable }})),
        n_valid = n - missing
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
        se = sd / sqrt(n),
        min = min({{ variable }}, na.rm = TRUE),
        max = max({{ variable }}, na.rm = TRUE),
        range = max - min,
        q1 = quantile({{ variable }}, 0.25, na.rm = TRUE),
        q3 = quantile({{ variable }}, 0.75, na.rm = TRUE),
        iqr = IQR({{ variable }}, na.rm = TRUE),
        skew = skewness({{ variable }}, na.rm = TRUE),
        kurt = kurtosis({{ variable }}, na.rm = TRUE),
        cv = (sd / mean) * 100,
        missing = sum(is.na({{ variable }})),
        n_valid = n - missing
      )
  }
  
  # Add confidence intervals
  result <- result %>%
    mutate(
      ci_lower = mean - 1.96 * se,
      ci_upper = mean + 1.96 * se
    )
  
  return(result)
}

# ==============================================================================
# 2. FREQUENCY TABLE FUNCTION
# ==============================================================================

freq_table <- function(data, variable) {
  data %>%
    count({{ variable }}) %>%
    mutate(
      percent = n / sum(n) * 100,
      cum_n = cumsum(n),
      cum_percent = cumsum(percent)
    )
}

# ==============================================================================
# 3. FULL EDA REPORT FUNCTION
# ==============================================================================

eda_report <- function(data, variables, group = NULL) {
  # Initialize list to store results
  results <- list()
  
  # Loop through variables
  for (var in variables) {
    cat("\n", "=", rep("-", 60), "\n", sep = "")
    cat("Variable:", var, "\n")
    cat("=", rep("-", 60), "\n\n")
    
    # Check variable type
    var_type <- class(data[[var]])
    
    if (var_type %in% c("numeric", "integer")) {
      # Continuous variable
      print(descriptive_stats(data, !!sym(var), {{ group }}))
      
      # Normality test
      if (nrow(data) >= 3) {
        shapiro <- shapiro.test(data[[var]])
        cat("\nShapiro-Wilk Normality Test:\n")
        print(shapiro)
      }
      
    } else {
      # Categorical variable
      print(freq_table(data, !!sym(var)))
    }
    
    cat("\n")
  }
  
  return(results)
}

# ==============================================================================
# 4. VISUALIZATION FUNCTIONS
# ==============================================================================

create_histogram <- function(data, variable, group = NULL, bins = 30) {
  p <- ggplot(data, aes(x = {{ variable }}))
  
  if (is.null(group)) {
    p <- p +
      geom_histogram(aes(y = ..density..), bins = bins, 
                     fill = "#3498db", alpha = 0.7) +
      geom_density(color = "#e74c3c", size = 1.2)
  } else {
    p <- p +
      geom_histogram(aes(y = ..density.., fill = {{ group }}), 
                     bins = bins, alpha = 0.5, position = "identity") +
      geom_density(aes(color = {{ group }}), size = 1)
  }
  
  p <- p +
    labs(title = "Distribution Plot",
         x = deparse(substitute(variable)),
         y = "Density") +
    theme_minimal() +
    theme(legend.position = "bottom")
  
  return(p)
}

create_boxplot <- function(data, variable, group) {
  p <- ggplot(data, aes(x = {{ group }}, y = {{ variable }}, fill = {{ group }})) +
    geom_boxplot(alpha = 0.7, outlier.color = "#e74c3c", outlier.size = 3) +
    geom_jitter(width = 0.2, alpha = 0.3) +
    labs(title = "Boxplot by Group",
         x = deparse(substitute(group)),
         y = deparse(substitute(variable))) +
    theme_minimal() +
    theme(legend.position = "none")
  
  return(p)
}

# ==============================================================================
# 5. EXAMPLE USAGE WITH IRIS DATA
# ==============================================================================

data(iris)

# Descriptive statistics
stats <- descriptive_stats(iris, Sepal.Length, Species)
print(stats)

# Frequency table
freq <- freq_table(iris, Species)
print(freq)

# Create visualizations
hist <- create_histogram(iris, Sepal.Length, Species)
print(hist)

box <- create_boxplot(iris, Sepal.Length, Species)
print(box)

# EDA report
eda_report(iris, c("Sepal.Length", "Sepal.Width", "Petal.Length"), Species)

# ==============================================================================
# 6. ADVANCED ANALYSES
# ==============================================================================

# Correlation matrix with significance
cor_test <- iris %>%
  select(-Species) %>%
  cor_test(method = "pearson")
print(cor_test)

# Correlation matrix visualization
cor_plot <- iris %>%
  select(-Species) %>%
  cor() %>%
  corrplot::corrplot(method = "color", 
                     type = "upper",
                     order = "hclust",
                     addCoef.col = "black",
                     tl.col = "black",
                     tl.srt = 45)

# ==============================================================================
# 7. EXPORT RESULTS
# ==============================================================================

# Export to CSV
write.csv(stats, "descriptive_stats.csv", row.names = FALSE)

# Export to Excel (requires openxlsx)
# library(openxlsx)
# write.xlsx(stats, "descriptive_stats.xlsx")
```

### 8.2 Python Implementation

```python
# ==============================================================================
# COMPREHENSIVE DESCRIPTIVE STATISTICS IN PYTHON
# ==============================================================================

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from scipy import stats
from scipy.stats import shapiro, skew, kurtosis
import warnings
warnings.filterwarnings('ignore')

# ==============================================================================
# 1. CORE DESCRIPTIVE STATISTICS FUNCTION
# ==============================================================================

def descriptive_stats(data, variable, group=None):
    """
    Calculate comprehensive descriptive statistics
    
    Parameters:
    -----------
    data : pandas DataFrame
        Input dataset
    variable : str
        Name of variable to analyze
    group : str, optional
        Grouping variable for stratified analysis
    
    Returns:
    --------
    pandas DataFrame with descriptive statistics
    """
    
    if group is None:
        # Overall statistics
        stats_df = pd.DataFrame({
            'n': [len(data)],
            'mean': [data[variable].mean()],
            'median': [data[variable].median()],
            'std': [data[variable].std()],
            'se': [data[variable].std() / np.sqrt(len(data))],
            'min': [data[variable].min()],
            'max': [data[variable].max()],
            'range': [data[variable].max() - data[variable].min()],
            'q1': [data[variable].quantile(0.25)],
            'q3': [data[variable].quantile(0.75)],
            'iqr': [data[variable].quantile(0.75) - data[variable].quantile(0.25)],
            'skew': [skew(data[variable].dropna())],
            'kurt': [kurtosis(data[variable].dropna())],
            'cv': [(data[variable].std() / data[variable].mean()) * 100],
            'missing': [data[variable].isna().sum()],
            'n_valid': [data[variable].notna().sum()]
        })
        
        # Add confidence intervals
        se = data[variable].std() / np.sqrt(len(data))
        stats_df['ci_lower'] = data[variable].mean() - 1.96 * se
        stats_df['ci_upper'] = data[variable].mean() + 1.96 * se
        
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
            ('skew', lambda x: skew(x.dropna())),
            ('kurt', lambda x: kurtosis(x.dropna())),
            ('missing', lambda x: x.isna().sum()),
            ('n_valid', lambda x: x.notna().sum())
        ])
        
        # Add standard error and confidence intervals
        stats_df['se'] = stats_df['std'] / np.sqrt(stats_df['n'])
        stats_df['ci_lower'] = stats_df['mean'] - 1.96 * stats_df['se']
        stats_df['ci_upper'] = stats_df['mean'] + 1.96 * stats_df['se']
        stats_df['cv'] = (stats_df['std'] / stats_df['mean']) * 100
    
    return stats_df

# ==============================================================================
# 2. FREQUENCY TABLE FUNCTION
# ==============================================================================

def freq_table(data, variable):
    """
    Create frequency table for categorical variable
    
    Parameters:
    -----------
    data : pandas DataFrame
    variable : str
        Name of categorical variable
    
    Returns:
    --------
    pandas DataFrame with frequencies
    """
    
    freq = data[variable].value_counts().reset_index()
    freq.columns = [variable, 'n']
    
    total = len(data)
    freq['percent'] = (freq['n'] / total) * 100
    freq['cum_n'] = freq['n'].cumsum()
    freq['cum_percent'] = freq['percent'].cumsum()
    
    return freq

# ==============================================================================
# 3. EDA REPORT FUNCTION
# ==============================================================================

def eda_report(data, variables, group=None):
    """
    Generate comprehensive EDA report
    
    Parameters:
    -----------
    data : pandas DataFrame
    variables : list
        List of variable names to analyze
    group : str, optional
        Grouping variable
    """
    
    for var in variables:
        print(f"\n{'='*60}")
        print(f"Variable: {var}")
        print(f"{'='*60}\n")
        
        # Check variable type
        if pd.api.types.is_numeric_dtype(data[var]):
            # Continuous variable
            print(descriptive_stats(data, var, group))
            
            # Normality test
            if len(data) >= 3:
                shapiro_stat, p_value = shapiro(data[var].dropna())
                print(f"\nShapiro-Wilk Test: W={shapiro_stat:.4f}, p={p_value:.4f}")
                
        else:
            # Categorical variable
            print(freq_table(data, var))
        
        print("\n")

# ==============================================================================
# 4. VISUALIZATION FUNCTIONS
# ==============================================================================

def create_histogram(data, variable, group=None, bins=30):
    """
    Create histogram with optional grouping
    """
    plt.figure(figsize=(10, 6))
    
    if group is None:
        sns.histplot(data=data, x=variable, bins=bins, 
                    kde=True, color='#3498db', alpha=0.7)
    else:
        sns.histplot(data=data, x=variable, hue=group, 
                    bins=bins, kde=True, alpha=0.5)
    
    plt.title(f'Distribution of {variable}')
    plt.xlabel(variable)
    plt.ylabel('Frequency')
    plt.show()

def create_boxplot(data, variable, group):
    """
    Create boxplot by group
    """
    plt.figure(figsize=(10, 6))
    
    sns.boxplot(data=data, x=group, y=variable, palette='Set2')
    sns.stripplot(data=data, x=group, y=variable, 
                 alpha=0.3, color='black')
    
    plt.title(f'{variable} by {group}')
    plt.xlabel(group)
    plt.ylabel(variable)
    plt.show()

def create_scatterplot(data, x_var, y_var, group=None):
    """
    Create scatter plot with optional grouping
    """
    plt.figure(figsize=(10, 6))
    
    if group is None:
        sns.scatterplot(data=data, x=x_var, y=y_var,
                       color='#3498db', alpha=0.7)
    else:
        sns.scatterplot(data=data, x=x_var, y=y_var, 
                       hue=group, alpha=0.7)
    
    plt.title(f'{y_var} vs {x_var}')
    plt.xlabel(x_var)
    plt.ylabel(y_var)
    plt.show()

# ==============================================================================
# 5. EXAMPLE USAGE WITH IRIS DATA
# ==============================================================================

from sklearn.datasets import load_iris

# Load data
iris = load_iris()
df = pd.DataFrame(iris.data, columns=iris.feature_names)
df['species'] = iris.target_names[iris.target]

# Descriptive statistics
stats = descriptive_stats(df, 'sepal length (cm)', 'species')
print(stats)

# Frequency table
freq = freq_table(df, 'species')
print(freq)

# Create visualizations
create_histogram(df, 'sepal length (cm)', 'species')
create_boxplot(df, 'sepal length (cm)', 'species')
create_scatterplot(df, 'sepal length (cm)', 'sepal width (cm)', 'species')

# EDA report
eda_report(df, ['sepal length (cm)', 'sepal width (cm)'], 'species')

# ==============================================================================
# 6. ADVANCED ANALYSES
# ==============================================================================

# Correlation matrix
corr_matrix = df.drop('species', axis=1).corr()
print(corr_matrix)

# Correlation heatmap
plt.figure(figsize=(8, 6))
sns.heatmap(corr_matrix, annot=True, cmap='coolwarm', 
            center=0, square=True, fmt='.2f')
plt.title('Correlation Matrix')
plt.show()

# Pairplot
sns.pairplot(df, hue='species', diag_kind='kde')
plt.show()

# ==============================================================================
# 7. EXPORT RESULTS
# ==============================================================================

# Export to CSV
stats.to_csv('descriptive_stats.csv')

# Export to Excel
stats.to_excel('descriptive_stats.xlsx', index=False)
```

### 8.3 SPSS Implementation

```spss
* ============================================================================ *
* DESCRIPTIVE STATISTICS IN SPSS                                               *
* ============================================================================ *

* 1. BASIC DESCRIPTIVE STATISTICS.
DESCRIPTIVES VARIABLES=SepalLength SepalWidth PetalLength PetalWidth
  /STATISTICS=MEAN STDDEV MIN MAX SEMEAN SKEWNESS KURTOSIS
  /SAVE.

* 2. FREQUENCY TABLES.
FREQUENCIES VARIABLES=Species
  /STATISTICS=MEAN MEDIAN MODE STDDEV VARIANCE MIN MAX RANGE
  /HISTOGRAM
  /BAR.

* 3. GROUPED STATISTICS.
MEANS TABLES=SepalLength SepalWidth PetalLength PetalWidth BY Species
  /CELLS MEAN COUNT STDDEV MIN MAX MEDIAN
  /STATISTICS ANOVA.

* 4. EXPLORE DETAILED ANALYSIS.
EXAMINE VARIABLES=SepalLength BY Species
  /PLOT BOXPLOT HISTOGRAM
  /STATISTICS DESCRIPTIVES EXTREME
  /MISSING LISTWISE
  /NOTOTAL.

* 5. CROSSTABS.
CROSSTABS
  /TABLES=Species BY Species
  /FORMAT=AVALUE TABLES
  /STATISTICS=CHISQ
  /CELLS=COUNT EXPECTED ROW COLUMN.

* 6. CORRELATION.
CORRELATIONS
  /VARIABLES=SepalLength SepalWidth PetalLength PetalWidth
  /PRINT=TWOTAIL NOSIG
  /MISSING=PAIRWISE.

* 7. DATASET PREPARATION.
DATASET DECLARE iris.
DATASET ACTIVATE iris.

* 8. SELECT CASES.
USE ALL.
COMPUTE filter_$=(Species='setosa').
VARIABLE LABELS filter_$ 'Species=setosa (FILTER)'.
FILTER BY filter_$.
EXECUTE.

* 9. SPLIT FILE ANALYSIS.
SORT CASES BY Species.
SPLIT FILE LAYERED BY Species.
FREQUENCIES VARIABLES=SepalLength
  /STATISTICS=MEAN MEDIAN MODE STDDEV.
SPLIT FILE OFF.

* 10. SAVE OUTPUT.
OUTPUT SAVE
  /OUTFILE='output.spv'
  /VERSION=3.
```

### 8.4 STATA Implementation

```stata
* ============================================================================ *
* DESCRIPTIVE STATISTICS IN STATA                                              *
* ============================================================================ *

* 1. LOAD DATA.
use iris.dta, clear

* 2. BASIC DESCRIPTIVE STATISTICS.
summarize SepalLength SepalWidth PetalLength PetalWidth, detail

* 3. BY-GROUP SUMMARY.
bysort Species: summarize SepalLength, detail

* 4. FREQUENCY TABLES.
tabulate SepalLength
tabulate Species, summarize(SepalLength)

* 5. DESCRIBE COMMAND.
describe, full

* 6. TABSTAT (Two-way tables).
tabstat SepalLength, by(Species) stats(n mean sd median min max)

* 7. TABLE COMMAND.
table Species, contents(n SepalLength mean SepalLength sd SepalLength)

* 8. CENTERED STATISTICS (mean, median, etc.).
summarize SepalLength, meanonly

* 9. PERCENTILES.
centile SepalLength, centile(25 50 75)

* 10. CORRELATION.
correlate SepalLength SepalWidth PetalLength PetalWidth

* 11. VISUALIZATIONS.
histogram SepalLength, by(Species) normal

graph box SepalLength, over(Species)

scatter SepalLength SepalWidth, by(Species)

* 12. EXPORT RESULTS.
estpost summarize SepalLength, detail
esttab using summary.tex, replace cells("mean(fmt(2)) p50(fmt(2)) sd(fmt(2)) min(fmt(2)) max(fmt(2))")

* 13. SAVE DATASET.
save iris_analysis.dta, replace

* 14. LOG FILE.
log using analysis.log, replace
summarize SepalLength, detail
log close
```

### 8.5 SAS Implementation

```sas
* ============================================================================ *
* DESCRIPTIVE STATISTICS IN SAS                                                *
* ============================================================================ *

* 1. BASIC DESCRIPTIVE STATISTICS.
PROC MEANS DATA=iris N MEAN STD MEDIAN MIN MAX Q1 Q3 RANGE SKEWNESS KURTOSIS;
    VAR SepalLength SepalWidth PetalLength PetalWidth;
RUN;

* 2. GROUPED STATISTICS.
PROC MEANS DATA=iris N MEAN STD MEDIAN MIN MAX;
    CLASS Species;
    VAR SepalLength SepalWidth PetalLength PetalWidth;
RUN;

* 3. DETAILED SUMMARY.
PROC UNIVARIATE DATA=iris;
    VAR SepalLength;
    CLASS Species;
    HISTOGRAM / NORMAL;
    QQPLOT / NORMAL;
RUN;

* 4. FREQUENCY TABLES.
PROC FREQ DATA=iris;
    TABLES Species / OUT=freq_table;
    TABLES Species * Species / CHISQ;
RUN;

* 5. CORRELATION.
PROC CORR DATA=iris;
    VAR SepalLength SepalWidth PetalLength PetalWidth;
    RUN;

* 6. BY-GROUP ANALYSIS.
PROC SORT DATA=iris;
    BY Species;
RUN;

PROC MEANS DATA=iris;
    BY Species;
    VAR SepalLength;
RUN;

* 7. REPORTING TABLE.
PROC REPORT DATA=iris;
    COLUMN Species SepalLength SepalWidth;
    DEFINE Species / GROUP;
    DEFINE SepalLength / ANALYSIS MEAN STD MIN MAX;
    DEFINE SepalWidth / ANALYSIS MEAN STD MIN MAX;
RUN;

* 8. EXPORT TO EXCEL.
PROC EXPORT DATA=iris
    OUTFILE='iris_analysis.xlsx'
    DBMS=EXCEL REPLACE;
RUN;

* 9. CREATE PLOTS.
PROC SGPLOT DATA=iris;
    VBOX SepalLength / GROUP=Species;
    TITLE 'Boxplot of Sepal Length by Species';
RUN;

PROC SGPLOT DATA=iris;
    HISTOGRAM SepalLength / GROUP=Species;
    DENSITY SepalLength / GROUP=Species;
    TITLE 'Histogram of Sepal Length by Species';
RUN;

PROC SGPLOT DATA=iris;
    SCATTER X=SepalLength Y=SepalWidth / GROUP=Species;
    TITLE 'Scatter Plot of Sepal Length vs Width';
RUN;

* 10. ODS OUTPUT FOR REPORTS.
ODS OUTPUT Summary=summary_data;
PROC MEANS DATA=iris;
    VAR SepalLength;
RUN;
ODS OUTPUT CLOSE;

* 11. MULTIPLE ANALYSES.
PROC TABULATE DATA=iris;
    CLASS Species;
    VAR SepalLength SepalWidth;
    TABLE Species,
          (SepalLength SepalWidth)*(N MEAN STD MIN MAX);
RUN;
```

### 8.6 Excel Implementation

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    EXCEL IMPLEMENTATION                                     ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  KEY FUNCTIONS FOR DESCRIPTIVE STATISTICS                           ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   ┌────────────────────────┬────────────────────┬─────────────────────────┐ ║
║   │       Function         │      Purpose       │       Example          │ ║
║   ├────────────────────────┼────────────────────┼─────────────────────────┤ ║
║   │  =AVERAGE(range)       │      Mean          │  =AVERAGE(A1:A100)     │ ║
║   │  =MEDIAN(range)        │      Median        │  =MEDIAN(A1:A100)      │ ║
║   │  =MODE.SNGL(range)     │      Mode          │  =MODE.SNGL(A1:A100)   │ ║
║   │  =STDEV.S(range)       │      Sample SD     │  =STDEV.S(A1:A100)     │ ║
║   │  =STDEV.P(range)       │      Population SD │  =STDEV.P(A1:A100)     │ ║
║   │  =VAR.S(range)         │      Sample Var    │  =VAR.S(A1:A100)       │ ║
║   │  =VAR.P(range)         │      Pop Var       │  =VAR.P(A1:A100)       │ ║
║   │  =MIN(range)           │      Minimum       │  =MIN(A1:A100)         │ ║
║   │  =MAX(range)           │      Maximum       │  =MAX(A1:A100)         │ ║
║   │  =MAX(range)-MIN(range)│      Range         │  =MAX(A1:A100)-MIN(A1) │ ║
║   │  =QUARTILE.EXC(range,1)│      Q1            │  =QUARTILE.EXC(A1,1)   │ ║
║   │  =QUARTILE.EXC(range,3)│      Q3            │  =QUARTILE.EXC(A1,3)   │ ║
║   │  =SKEW(range)          │      Skewness      │  =SKEW(A1:A100)        │ ║
║   │  =KURT(range)          │      Kurtosis      │  =KURT(A1:A100)        │ ║
║   │  =COUNT(range)         │      Count         │  =COUNT(A1:A100)       │ ║
║   │  =COUNTIF(range,criteria)│   Count with      │  =COUNTIF(A1:A100,">0")│ ║
║   └────────────────────────┴────────────────────┴─────────────────────────┘ ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  FREQUENCY TABLE (Pivot Table)                                       ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Steps:                                                                     ║
║   1. Select data range                                                       ║
║   2. Insert → PivotTable                                                     ║
║   3. Drag variable to Rows                                                   ║
║   4. Drag same variable to Values (Count)                                    ║
║   5. Add Show Values As → % of Total                                         ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  DATA ANALYSIS TOOLPAK (Add-in)                                      ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   To enable: File → Options → Add-ins → Analysis ToolPak → Go                ║
║                                                                              ║
║   Available analyses:                                                       ║
║   • Descriptive Statistics                                                  ║
║   • Histogram                                                                ║
║   • Regression                                                               ║
║   • Correlation                                                              ║
║   • t-test                                                                   ║
║   • ANOVA                                                                   ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  CHARTS AND GRAPHS                                                   ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Chart Type          │ How to Create                                       ║
║  ─────────────────────┼───────────────────────────────────────────────────── ║
║   Histogram           │ Select data → Insert → Histogram                   ║
║   Box Plot            │ Need add-in or manual calculation                 ║
║   Pie Chart           │ Select data → Insert → Pie                         ║
║   Bar Chart           │ Select data → Insert → Bar                         ║
║   Scatter Plot        │ Select data → Insert → Scatter                     ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  CONDITIONAL FORMATTING                                              ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   • Color scales for data values                                             ║
║   • Data bars for comparisons                                                ║
║   • Icon sets for categorization                                             ║
║   • Highlight outliers with rules                                           ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

## 9. Assessment & Summary

### 9.1 Worked Example

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    WORKED EXAMPLE                                           ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   Dataset: Blood pressure (mmHg) from 10 patients                           ║
║                                                                              ║
║   118, 122, 130, 145, 119, 125, 138, 128, 121, 150                         ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  STEP 1: SORT DATA                                                   ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   118, 119, 121, 122, 125, 128, 130, 138, 145, 150                         ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  STEP 2: CALCULATE MEASURES                                          ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Mean    = 129.6 mmHg                                                       ║
║   Median  = 126.5 mmHg                                                       ║
║   Mode    = No mode (all unique)                                            ║
║   SD      = 11.4 mmHg                                                       ║
║   Range   = 32 mmHg                                                         ║
║   IQR     = 18 mmHg                                                         ║
║   CV      = 8.8%                                                            ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  STEP 3: FIVE-NUMBER SUMMARY                                         ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Min     = 118                                                              ║
║   Q1      = 121.5                                                            ║
║   Median  = 126.5                                                            ║
║   Q3      = 139.5                                                            ║
║   Max     = 150                                                              ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  STEP 4: INTERPRETATION                                              ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   • The typical blood pressure is approximately 130 mmHg                    ║
║   • Most values lie between 121.5 and 139.5 mmHg                            ║
║   • The distribution is slightly right-skewed (mean > median)               ║
║   • One high value (150 mmHg) pulls the mean up                             ║
║   • No extreme outliers (within 1.5×IQR)                                   ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  STEP 5: REPORTING                                                   ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   "The mean blood pressure was 129.6 mmHg (SD = 11.4; n=10), with            ║
║   a median of 126.5 mmHg (IQR: 121.5-139.5). The values ranged               ║
║   from 118 to 150 mmHg. The distribution showed slight right                 ║
║   skewness (skewness = 0.42)."                                               ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
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

6. Give an example of when to report median (IQR) instead of mean (SD).

7. What is the difference between a histogram and a bar chart?

8. What does skewness measure?

9. How do you interpret a positive skew?

10. What is the purpose of exploratory data analysis?

**Long Questions:**

1. You have collected blood pressure data from 200 patients. Describe how you would:
   - Clean the data
   - Create frequency tables
   - Choose appropriate measures of central tendency and dispersion
   - Create visualizations
   - Write a results section

2. Compare and contrast the following visualizations:
   - Histogram vs Box plot
   - Scatter plot vs Heatmap
   - Bar chart vs Pie chart
   - Line graph vs Frequency polygon

3. Explain how descriptive statistics are used in:
   - Clinical trials
   - Machine learning
   - Public health surveillance
   - Quality control

</details>

### 9.3 MCQs

<details>
<summary>📝 Click to reveal 50 MCQs</summary>

**Section 1: Fundamentals (Questions 1-10)**

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

**Section 2: Data Types (Questions 11-20)**

11. Blood type is an example of:
    - A) Nominal ✓
    - B) Ordinal
    - C) Interval
    - D) Ratio

12. Pain severity (mild, moderate, severe) is:
    - A) Nominal
    - B) Ordinal ✓
    - C) Interval
    - D) Ratio

13. Temperature in Celsius is:
    - A) Nominal
    - B) Ordinal
    - C) Interval ✓
    - D) Ratio

14. Height is:
    - A) Nominal
    - B) Ordinal
    - C) Interval
    - D) Ratio ✓

15. The number of hospital visits is:
    - A) Discrete ✓
    - B) Continuous
    - C) Ordinal
    - D) Nominal

16. Weight is:
    - A) Discrete
    - B) Continuous ✓
    - C) Ordinal
    - D) Nominal

17. Education level (elementary, high school, college) is:
    - A) Nominal
    - B) Ordinal ✓
    - C) Interval
    - D) Ratio

18. Gender is:
    - A) Nominal ✓
    - B) Ordinal
    - C) Interval
    - D) Ratio

19. IQ score is:
    - A) Nominal
    - B) Ordinal
    - C) Interval ✓
    - D) Ratio

20. Age is:
    - A) Nominal
    - B) Ordinal
    - C) Interval
    - D) Ratio ✓

**Section 3: Visualization (Questions 21-30)**

21. Histogram bars are:
    - A) Separated by gaps
    - B) Adjacent (no gaps) ✓
    - C) Variable width
    - D) Circular

22. A box plot displays the:
    - A) Frequency distribution
    - B) Five-number summary ✓
    - C) Correlation
    - D) Time trend

23. A scatter plot is used to:
    - A) Show distribution of single variable
    - B) Show relationship between two variables ✓
    - C) Show proportions
    - D) Show time trends

24. A pie chart should be used when:
    - A) Showing many categories
    - B) Showing proportions of a whole ✓
    - C) Showing relationships
    - D) Showing distributions

25. The 68-95-99.7 rule applies to:
    - A) Any distribution
    - B) Normal distribution ✓
    - C) Skewed distribution
    - D) Bimodal distribution

26. A violin plot combines:
    - A) Box plot and histogram ✓
    - B) Scatter plot and line graph
    - C) Pie chart and bar chart
    - D) Histogram and pie chart

27. A stem-and-leaf plot retains:
    - A) Only summary statistics
    - B) All original data values ✓
    - C) Only categorical data
    - D) Only frequency counts

28. An ogive displays:
    - A) Frequency distribution
    - B) Cumulative frequency ✓
    - C) Relative frequency
    - D) Percentage

29. A heatmap is best for:
    - A) Time series data
    - B) Correlation matrices ✓
    - C) Single distributions
    - D) Proportions

30. The most appropriate graph for categorical data is:
    - A) Histogram
    - B) Bar chart ✓
    - C) Scatter plot
    - D) Line graph

**Section 4: Analysis (Questions 31-40)**

31. The empirical rule states:
    - A) 68% within 1 SD ✓
    - B) 95% within 1 SD
    - C) 99.7% within 2 SD
    - D) All data within 3 SD

32. The five-number summary includes:
    - A) Mean, SD, n, min, max
    - B) Min, Q1, Median, Q3, Max ✓
    - C) Mean, Median, Mode, Range, IQR
    - D) Count, Sum, Mean, Variance, SD

33. Skewness measures:
    - A) Spread of distribution
    - B) Asymmetry of distribution ✓
    - C) Peakedness of distribution
    - D) Center of distribution

34. Kurtosis measures:
    - A) Spread of distribution
    - B) Asymmetry of distribution
    - C) Tailedness of distribution ✓
    - D) Center of distribution

35. The mode is:
    - A) The average value
    - B) The middle value
    - C) The most frequent value ✓
    - D) The difference between max and min

36. Q1 represents:
    - A) 10th percentile
    - B) 25th percentile ✓
    - C) 50th percentile
    - D) 75th percentile

37. The interquartile range is:
    - A) Q2 - Q1
    - B) Q3 - Q1 ✓
    - C) Q3 - Q2
    - D) Max - Min

38. The coefficient of variation is useful for:
    - A) Comparing spread of different units ✓
    - B) Measuring central tendency
    - C) Detecting outliers
    - D) Testing normality

39. Outliers are defined as values:
    - A) More than 2 SD from mean
    - B) More than 3 SD from mean
    - C) Outside 1.5×IQR from Q1/Q3 ✓
    - D) Outside 2.5×IQR from Q1/Q3

40. The standard error is:
    - A) SD of the population
    - B) SD of the sample
    - C) SD divided by √n ✓
    - D) Variance divided by √n

**Section 5: Reporting (Questions 41-50)**

41. Mean ± SD should be reported for:
    - A) Skewed data
    - B) Normal data ✓
    - C) Ordinal data
    - D) Nominal data

42. Median (IQR) should be reported for:
    - A) Normal data
    - B) Skewed data ✓
    - C) Nominal data
    - D) Binary data

43. CONSORT guidelines apply to:
    - A) Observational studies
    - B) Randomized trials ✓
    - C) Systematic reviews
    - D) Case reports

44. STROBE guidelines apply to:
    - A) Randomized trials
    - B) Observational studies ✓
    - C) Systematic reviews
    - D) Diagnostic studies

45. PRISMA guidelines apply to:
    - A) Randomized trials
    - B) Observational studies
    - C) Systematic reviews ✓
    - D) Diagnostic studies

46. When reporting p-values:
    - A) Always report exact values ✓
    - B) Always use p<0.05
    - C) Only report significant values
    - D) Report to 1 decimal place

47. The most important descriptive statistic to report in medical research is:
    - A) Mean only
    - B) Median only
    - C) Both measure of center and spread ✓
    - D) Only p-values

48. For a skewed distribution, the best measure of center is:
    - A) Mean
    - B) Median ✓
    - C) Mode
    - D) Range

49. The best measure of spread for skewed data is:
    - A) SD
    - B) Variance
    - C) IQR ✓
    - D) Range

50. When writing a results section:
    - A) Only report p-values
    - B) Report descriptive statistics first ✓
    - C) Only report significant results
    - D) Skip descriptive statistics

</details>

### 9.4 Chapter Summary

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    CHAPTER SUMMARY                                          ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  🎯 KEY TAKEAWAYS                                                    ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   1. Descriptive statistics summarizes, organizes, and presents data        ║
║                                                                              ║
║   2. Choose measures based on data type and distribution:                   ║
║      • Normal data → Mean ± SD                                              ║
║      • Skewed data → Median (IQR)                                           ║
║      • Categorical → Frequency (%)                                         ║
║                                                                              ║
║   3. Visualization is essential for understanding data:                     ║
║      • Histograms for distributions                                         ║
║      • Box plots for comparing groups                                       ║
║      • Scatter plots for relationships                                      ║
║                                                                              ║
║   4. EDA is critical before any statistical analysis:                       ║
║      • Clean data first                                                     ║
║      • Check for outliers                                                   ║
║      • Examine distributions                                                ║
║      • Handle missing data                                                  ║
║                                                                              ║
║   5. Report appropriate measures with proper formatting:                   ║
║      • Include sample size                                                  ║
║      • Use correct precision                                                ║
║      • Follow journal guidelines                                            ║
║                                                                              ║
║   6. Follow CONSORT/STROBE/PRISMA guidelines:                               ║
║      • Complete reporting                                                   ║
║      • Transparent methods                                                  ║
║      • Reproducible results                                                 ║
║                                                                              ║
║   7. Interpret descriptively, not causally:                                 ║
║      • Describe what you see                                                ║
║      • Don't over-interpret                                                 ║
║      • Acknowledge limitations                                              ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  📚 RECOMMENDED RESOURCES                                            ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Books:                                                                    ║
║   • Altman DG. Practical Statistics for Medical Research                   ║
║   • Kirkwood BR, Sterne JAC. Essential Medical Statistics                  ║
║   • Tukey JW. Exploratory Data Analysis                                    ║
║                                                                              ║
║   Software:                                                                 ║
║   • R: ggplot2, dplyr, psych                                               ║
║   • Python: pandas, matplotlib, seaborn                                    ║
║   • SPSS: Explore, Frequencies, Descriptives                               ║
║                                                                              ║
║   Guidelines:                                                               ║
║   • CONSORT Statement (www.consort-statement.org)                          ║
║   • STROBE Statement (www.strobe-statement.org)                            ║
║   • PRISMA Statement (www.prisma-statement.org)                            ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 9.5 Formula Sheet

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                    FORMULA SHEET                                            ║
╠══════════════════════════════════════════════════════════════════════════════╣
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  MEASURES OF CENTRAL TENDENCY                                       ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Mean (x̄)                = Σx / n                                          ║
║   Median                  = Middle value when ordered                       ║
║   Mode                    = Most frequent value                             ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  MEASURES OF DISPERSION                                              ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Range                   = Max - Min                                       ║
║   IQR                     = Q3 - Q1                                         ║
║   Variance (s²)           = Σ(x - x̄)² / (n - 1)                           ║
║   Standard Deviation (s)  = √s²                                             ║
║   Standard Error (SE)     = s / √n                                          ║
║   CV                      = (s / x̄) × 100%                                 ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  POSITION MEASURES                                                   ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Percentile Position   = (n + 1) × p / 100                                ║
║   Q1 Position           = (n + 1) × 25 / 100                               ║
║   Q2 Position           = (n + 1) × 50 / 100                               ║
║   Q3 Position           = (n + 1) × 75 / 100                               ║
║   Z-score               = (x - μ) / σ                                      ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  DISTRIBUTION SHAPE                                                 ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Skewness (g₁)          = Σ(x - x̄)³ / (n × s³)                          ║
║   Kurtosis (g₂)          = Σ(x - x̄)⁴ / (n × s⁴) - 3                     ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  EMPIRICAL RULE (Normal Distribution)                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Within μ ± 1σ          = 68.27%                                           ║
║   Within μ ± 2σ          = 95.45%                                           ║
║   Within μ ± 3σ          = 99.73%                                           ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  CHEBYSHEV'S THEOREM (Any Distribution)                             ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   P(|X - μ| < kσ)        ≥ 1 - 1/k²                                        ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  CONFIDENCE INTERVALS                                                ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   95% CI for Mean       = x̄ ± 1.96 × (s/√n)                              ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  STANDARDIZED MEASURES                                              ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Z-score               = (x - μ) / σ                                      ║
║   T-score               = 50 + 10Z                                         ║
║   IQ score              = 100 + 15Z                                        ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  CORRELATION                                                         ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Pearson r            = Σ(x - x̄)(y - ȳ) / [(n-1)sx sy]                  ║
║   Spearman ρ           = Rank-based version of r                           ║
║   Coefficient of        = r²                                                ║
║   Determination                                                             ║
║                                                                              ║
║   ╔═══════════════════════════════════════════════════════════════════════╗  ║
║   ║  NOTATION CONVENTIONS                                               ║  ║
║   ╚═══════════════════════════════════════════════════════════════════════╝  ║
║                                                                              ║
║   Population Parameters:   μ (mean), σ (SD), ρ (correlation)               ║
║   Sample Statistics:       x̄ (mean), s (SD), r (correlation)              ║
║   Sample Size:             n (sample), N (population)                       ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

---

**[⬅ Previous: Repository Home](../README.md) · [🏠 Back to Repository](../README.md) · [➡ Next: Chapter 2 - Measures of Central Tendency](./02-central-tendency.md)**
