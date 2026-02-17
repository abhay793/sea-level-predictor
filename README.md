# 🌊 Sea Level Predictor

## Overview

This project analyzes historical global average sea level data from 1880 onward and uses linear regression to project sea level rise through the year 2050.

The objective is to examine long-term trends and compare them with more recent acceleration patterns using statistical modeling and visualization techniques.

---

## Dataset

Global Average Absolute Sea Level Change (1880–2014)

Source:
US Environmental Protection Agency (EPA)  
Data from CSIRO (2015) and NOAA (2015)

---

## Project Tasks

1. Import sea level data using Pandas.
2. Create a scatter plot of Year vs. CSIRO Adjusted Sea Level.
3. Compute a line of best fit using all available data.
4. Extend the regression line to predict sea level in 2050.
5. Compute a second regression line using data from 2000 onward.
6. Extend the second regression line to 2050.
7. Label axes and title appropriately.

---

## Visualization

The final output includes:

- Historical sea level scatter plot
- Long-term regression trend line (1880–2050)
- Recent trend regression line (2000–2050)

The comparison highlights acceleration in sea level rise in recent decades.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- SciPy (linregress)

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/sea-level-predictor.git
cd sea-level-predictor
