# 🏔️ EDA: Himalayan Mountaineering (Nepal)

Exploratory Data Analysis in **R** on Himalayan expeditions in Nepal (1905–Spring 2019).  
Dataset includes expedition-level info + participant-level info (members).

---

## 🎯 Goal
I explored what factors are associated with **risk and outcomes** in Himalayan expeditions:
who dies more often, when, where, and under what conditions.

---

## ❓ Research questions (what I checked)
1. 🧗‍♀️ Which peaks are the most deadly? (counts vs % mortality)
2. 🗓️ Does death risk depend on the season? (association strength)
3. ⛰️ Is max achieved altitude different for survivors vs non-survivors?
4. 🧑‍🤝‍🧑 Does death risk differ by expedition role?
5. 🫁 Does bottled oxygen increase survival chances above 8000m (“death zone”)?
6. 🎂 Does age affect maximum achieved altitude? (Kruskal–Wallis + Dunn post-hoc)
7. ♀️♂️ Is participant sex associated with death risk?
8. 📈 Has Himalayan climbing become safer over time? (mortality trend)

---

## 🧪 Methods & tools
- R / tidyverse (data wrangling)
- ggplot2 (visualisation)
- Tests: Cramér’s V, proportions test, Kruskal–Wallis, Dunn post-hoc

---

## 📁 Repository contents
- `EDA - Zaclona.Rmd` — analysis notebook (source)
- `EDA---Zaclona.html` — rendered report (full results)
- `expeditions.csv`, `members.csv` — data files
- `link do danych.txt` — source link

---

## ▶️ How to run
1. Open `EDA - Zaclona.Rmd` in RStudio
2. Install packages used in the notebook
3. Knit to HTML ✅

---

## 👩‍💻 Author
Weronika Zacłona
