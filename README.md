# Data Skills Practice

My practice notebooks as I learn Python, SQL and data analysis, heading toward data engineering with an interest in finance. Every exercise uses data I made up myself, written in Google Colab.

## Progress

| # | Topic | What I built | Notebook |
|---|-------|--------------|----------|
| 01 | Matplotlib: line plots and scatter plots | Naira-to-dollar rate over 6 months, ad spend vs revenue, shop savings over time, price vs units sold | `01_matplotlib_line_scatter.ipynb` |

## What I learned

### 01 Matplotlib: line and scatter plots
- `plt.plot(x, y)` draws a line and `plt.scatter(x, y)` draws dots. The first list goes on the horizontal axis and the second on the vertical axis.
- Use a line plot for change over time, and a scatter plot for the relationship between two variables.
- Dots that rise left to right show a positive correlation, and dots that fall show a negative correlation.
- `plt.show()` displays the chart, and I call it after each chart so charts don't overlap.
- Titles should describe the chart, and axis labels should include units.

## Code template

    import matplotlib.pyplot as plt

    plt.plot(x, y)
    plt.title("What the chart shows")
    plt.xlabel("X name (unit)")
    plt.ylabel("Y name (unit)")
    plt.show()

## Tools
Python, Google Colab, matplotlib

*Updated after each new topic.*
