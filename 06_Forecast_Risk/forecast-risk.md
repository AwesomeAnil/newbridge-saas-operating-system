# ⚠️ Forecast Risk
## 📘 Exposure Severity & Recovery Requirement Analysis

[⬅ Pipeline Governance](../05_Pipeline_Governance/README.md)
|
[⬅ Forecast Confidence](../05_Pipeline_Governance/forecast-confidence.md)
|
[⬅ Forecast Exposure](../05_Pipeline_Governance/forecast-exposure.md)
|
[➡ Central Risk Reserve](../08_Central_Risk_Reserve/README.md)
|
[➡ Recovery Optimization](../09_Recovery_Optimization/README.md)

---

<p align="center">

![Forecast Risk](https://img.shields.io/badge/Forecast-Risk-critical)
![Exposure Analysis](https://img.shields.io/badge/Exposure-Severity-darkred)
![Commercial Risk](https://img.shields.io/badge/Commercial-Risk-orange)
![Enterprise Governance](https://img.shields.io/badge/Enterprise-Governance-black)
![Revenue Operations](https://img.shields.io/badge/Revenue-Operations-blue)
![Executive Analytics](https://img.shields.io/badge/Executive-Decision%20Support-purple)
![Risk Intelligence](https://img.shields.io/badge/Risk-Intelligence-darkblue)
![Recovery Planning](https://img.shields.io/badge/Recovery-Planning-success)

</p>

---

## 📌 Executive Overview

Forecast Confidence established whether the forecast could be trusted.

Forecast Risk evaluates the consequences of that forecast.

The objective is no longer to determine confidence.

The objective is to quantify:

- exposure magnitude
- exposure severity
- concentration risk
- recovery requirements

This transforms forecasting from a confidence discussion into a risk governance discipline.

---

## 🧠 Core Governance Principle

The most important principle in Forecast Risk is:

> Forecast confidence identifies potential failure.
>
> Forecast risk quantifies the consequences of failure.

Confidence explains whether a forecast is believable.

Risk explains what happens when the forecast misses its target.

---

## 🗓️ Operating Context

This analysis is performed at the conclusion of Q3.

At this point:

- Q1–Q3 actual performance is known.
- Q4 execution remains uncertain.
- Forecast confidence calibration has already been completed.

The organization now understands that the confidence-adjusted forecast differs materially from the fiscal target.

The next question becomes:

> How severe is the remaining exposure?

---

## 📉 Forecast Risk Evolution

```mermaid
flowchart TD
    A["<table width='220'><tr><td><b>FY26 Budget</b><br>$160M</td></tr></table>"]
    B["<table width='220'><tr><td><b>High Confidence Forecast</b><br>$125M</td></tr></table>"]
    C["<table width='220'><tr><td><b>Forecast Exposure</b><br>$35M</td></tr></table>"]
    D["<table width='220'><tr><td><b>Risk Assessment</b><br> </td></tr></table>"]
    E["<table width='220'><tr><td><b>Recovery Requirement</b><br> </td></tr></table>"]

    A --> B
    B --> C
    C --> D
    D --> E

    %% Color Styling %%
    classDef budget fill:#2E7D32,stroke:#1B5E20,stroke-width:2px,color:#FFFFFF;
    classDef forecast fill:#1565C0,stroke:#0D47A1,stroke-width:2px,color:#FFFFFF;
    classDef exposure fill:#E65100,stroke:#BF360C,stroke-width:2px,color:#FFFFFF;
    classDef risk fill:#C62828,stroke:#5D4037,stroke-width:2px,color:#FFFFFF;
    classDef recovery fill:#AD1457,stroke:#4A148C,stroke-width:2px,color:#FFFFFF;

    %% Applying styles to nodes %%
    class A budget;
    class B forecast;
    class C exposure;
    class D risk;
    class E recovery;
```

Forecast Risk begins when confidence-adjusted forecasting reveals a gap between expected performance and fiscal commitments.

---

## 📊 Exposure Calculation

Using the confidence-adjusted forecast:

| Metric | Value |
|----------|----------:|
| FY26 Budget | $160M |
| High Confidence Forecast | $125M |
| Forecast Exposure | $35M |

---

## Exposure Formula

```text
Forecast Exposure
=
Budget
-
High Confidence Forecast
```

```text
Forecast Exposure
=
160M
-
125M
```

```text
Forecast Exposure
=
35M
```

The enterprise is therefore exposed to a potential year-end shortfall of $35M.

---

## 📉 Exposure Escalation

Forecast Confidence established how forecast survivability deteriorated under increasingly strict confidence assumptions.

Forecast Risk translates that deterioration into measurable exposure.

| Scenario | Forecast | Exposure |
|----------|----------:|----------:|
| Full Pipeline | $168M | $0M |
| Qualified Pipeline | $148M | $12M |
| High Confidence | $125M | $35M |

---

### Executive Insight

Confidence calibration transformed what initially appeared to be a forecast surplus into a critical exposure position.

```text
Full Pipeline
VTB = +$8M
```

became:

```text
High Confidence
VTB = -$35M
```

This transition marks the point at which confidence concerns become enterprise risk concerns.

---

## ⚠️ Exposure Severity

Exposure magnitude alone does not fully describe risk.

Risk must be evaluated relative to enterprise commitments.

---

### Exposure Severity Scale

| Exposure % | Classification |
|----------:|----------|
| 0–5% | Low |
| 5–10% | Moderate |
| 10–20% | High |
| >20% | Critical |

---

### Enterprise Exposure Profile

| Metric | Value |
|----------|----------:|
| FY26 Budget | $160M |
| High Confidence Forecast | $125M |
| Exposure | $35M |
| Exposure Severity | 21.9% |
| Classification | Critical |

---

### Executive Interpretation

More than one-fifth of planned fiscal attainment is unsupported under high-confidence assumptions.

This places the enterprise within a critical exposure zone requiring executive attention.

---

## 📈 Risk Escalation Curve

```mermaid
flowchart TD
    A["<table width='180'><tr><td><b>Low</b><br>0-5%</td></tr></table>"]
    B["<table width='180'><tr><td><b>Moderate</b><br>5-10%</td></tr></table>"]
    C["<table width='180'><tr><td><b>High</b><br>10-20%</td></tr></table>"]
    D["<table width='180'><tr><td><b>Critical</b><br>20%+</td></tr></table>"]

    A --> B
    B --> C
    C --> D

    %% Color Styling %%
    classDef low fill:#2E7D32,stroke:#1B5E20,stroke-width:2px,color:#FFFFFF;
    classDef moderate fill:#F9A825,stroke:#F57F17,stroke-width:2px,color:#FFFFFF;
    classDef high fill:#E65100,stroke:#BF360C,stroke-width:2px,color:#FFFFFF;
    classDef critical fill:#C62828,stroke:#5D4037,stroke-width:2px,color:#FFFFFF;

    %% Applying styles to nodes %%
    class A low;
    class B moderate;
    class C high;
    class D critical;
```

As exposure increases, recovery flexibility declines and intervention requirements become more severe.

---

## 🌍 Exposure Concentration Analysis

Forecast risk is rarely distributed evenly across the enterprise.

Instead, exposure typically concentrates within a small number of high-revenue operating regions.

![Forecast Coverage](assets/images/forecast-coverage.png)

---

## 📊 Geographic Exposure Concentration

Forecast confidence calibration revealed that enterprise exposure was concentrated within a small number of major revenue-producing geographies.

| Region | Full Pipeline | Qualified Pipeline | High Confidence |
|----------|----------:|----------:|----------:|
| NA West | 105.2% | 87.2% | 66.8% |
| NA East | 109.8% | 90.6% | 68.1% |
| DACH | 101.6% | 95.0% | 87.6% |
| UKI | 102.6% | 96.5% | 90.7% |

The largest forecast deterioration occurred within:

```text
NA East
NA West
```

where attainment declined materially under high-confidence assumptions.

Because these regions represent a significant proportion of enterprise revenue, their deterioration contributes disproportionately to overall forecast risk.

---

## ⚠️ Concentration Risk

This reveals a second governance reality:

> Not all forecast variance is created equally.

A modest deterioration within a low-revenue geography may have limited fiscal impact.

The same deterioration within a major revenue-producing geography can materially alter enterprise outcomes.

Enterprise risk therefore depends on:

- confidence deterioration
- revenue concentration
- exposure magnitude

rather than forecast variance alone.

---

## 🧭 Regional Risk Assessment

### Resilient Regions

```text
UKI
DACH
```

These regions maintained comparatively strong attainment levels under confidence calibration.

---

### Vulnerable Regions

```text
India
ANZ
Middle East
```

These regions demonstrated moderate deterioration under increasingly strict confidence assumptions.

---

### Critical Regions

```text
NA East
NA West
```

These regions combine:

- significant revenue concentration
- material confidence deterioration
- elevated exposure contribution

making them the largest contributors to enterprise risk.

---

## ⏳ Recovery Window Compression

Exposure severity is amplified by limited recovery time.

At the conclusion of Q3:

```text
Actual Performance = Known

Remaining Fiscal Time = One Quarter

Forecast Exposure = $35M
```

The enterprise must therefore offset a $35M exposure using only the remaining Q4 execution window.

---

### Recovery Compression Evolution

```mermaid
flowchart TD
    A["<table width='240'><tr><td><b>Forecast Exposure</b></td></tr></table>"]
    B["<table width='240'><tr><td><b>Recovery<br> Requirement</b></td></tr></table>"]
    C["<table width='240'><tr><td><b>Reduced Time <br> Available</b></td></tr></table>"]
    D["<table width='240'><tr><td><b>Compressed<br> Execution Window</b></td></tr></table>"]
    E["<table width='240'><tr><td><b>Higher Recovery Risk</b></td></tr></table>"]

    A --> B
    B --> C
    C --> D
    D --> E

    %% Color Styling %%
    classDef exposure fill:#E65100,stroke:#BF360C,stroke-width:2px,color:#FFFFFF;
    classDef recovery fill:#AD1457,stroke:#4A148C,stroke-width:2px,color:#FFFFFF;
    classDef time fill:#880E4F,stroke:#4A0033,stroke-width:2px,color:#FFFFFF;
    classDef window fill:#701212,stroke:#3E0000,stroke-width:2px,color:#FFFFFF;
    classDef risk fill:#B71C1C,stroke:#4A0000,stroke-width:2px,color:#FFFFFF;

    %% Applying styles to nodes %%
    class A exposure;
    class B recovery;
    class C time;
    class D window;
    class E risk;
```

Risk severity increases not only because exposure exists, but because recovery time continuously declines.

---

## 📊 Recovery Burden Assessment

The forecast exposure creates a measurable recovery requirement.

| Metric | Value |
|----------|----------:|
| Forecast Exposure | $35M |
| Remaining Quarter | Q4 |
| Monthly Recovery Requirement | ~$11.7M |

---

## Executive Interpretation

Maintaining fiscal commitments would require the organization to generate approximately:

```text
$11.7M
```

of incremental attainment per remaining month.

This illustrates the scale of intervention required to preserve year-end commitments.

---

## 🧠 Executive Risk Profile

Forecast risk is determined by the interaction of multiple factors.

| Risk Driver | Observation |
|-------------|-------------|
| Magnitude | $35M exposure |
| Concentration | Exposure concentrated in NA East and NA West |
| Timing | Single quarter remaining |
| Confidence | High-confidence forecast at 78% attainment |

---

### Executive Insight

Individually these factors may be manageable.

Combined they create a critical enterprise risk profile requiring structured intervention.

Forecast risk is therefore created by the combination of:

- exposure magnitude
- concentration
- timing constraints
- recovery feasibility

rather than missed targets alone.

---

## 🔗 Transition To Central Risk Reserve

Forecast Confidence established whether the forecast could be trusted.

Forecast Risk quantified the consequences of forecast failure.

The next challenge becomes:

> How should the organization respond?

This introduces:

### 🛡️ Central Risk Reserve (CRR)

which provides the institutional recovery mechanism used to mitigate forecast exposure and preserve fiscal commitments.

---

## 🎯 Strategic Conclusion

Forecast confidence reveals forecast survivability.

Forecast risk reveals exposure severity.

Together they provide leadership with a structured understanding of enterprise vulnerability.

By quantifying:

- exposure magnitude
- concentration risk
- timing pressure
- recovery requirements

organizations can transition from reactive forecasting toward proactive risk governance.

Forecast Risk therefore serves as the bridge between forecast governance and enterprise recovery planning within the New Bridge operating model.

---

### 👤 Author

**Anil Jacob**  
Enterprise BI • Revenue Operations • Executive Analytics • Forecast Governance

---

### 📜 Repository Context

All forecasts, exposure assessments, risk classifications, recovery scenarios, and governance environments contained within this repository are simulated for portfolio and strategic demonstration purposes.