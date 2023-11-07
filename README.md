![Welcome!](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGNuamZlbGg2ZHVqdnMweGl0cHdmOWU1Y3Y1cXIwdnF0anptdTh6NyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/aWYNvKMvwPVADwIM4i/giphy.gif "Introduction animation for streamViz gauge indicator visualization for Streamlit")


# streamviz

[![PyPI version](https://badge.fury.io/py/streamviz.svg)](https://badge.fury.io/py/streamviz)

<p>
    Custom Plotly visualizations for Streamlit
</p>

## Installation
Open a terminal and run:

```bash
$ pip install streamviz
```

## Demonstration App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://stream-gauge.streamlit.app/)

## Dependencies

| Library   | Language | Link                                                               |
| --------- | -------- | ------------------------------------------------------------------ |
| Streamlit | Python   | https://github.com/streamlit/streamlit                             |
| Plotly    | Python   | https://github.com/plotly/plotly.py                                |

## Function Parameters

| Name                             | Data Type        | Short Desc                           | Options                       |
| -------------------------------- | ---------------- | ------------------------------------ | ----------------------------- |
| gVal                             | "integer, float" | gauge Value (required)               |                               |
| gTitle                           | string           | gauge Title (default '')             |                               |
| gMode                            | string           | gauge Mode (default gauge+number)    | "gauge+number, gauge, number" |
| gSize                            | String           | gauge Size (default FULL)            | "SML, MED, LRG, FULL, CUST"   |
| grLow                            | "integer, float" | Low gauge Range (default 0.30)       |                               |
| grMid                            | "integer, float" | Middle gauge Range (default 0.70)    |                               |
| gcLow                            | string           | Low gauge Color (default #FF1708)    |                               |
| gcMid                            | string           | Middle gauge Color (default #FF9400) |                               |
| gcHigh                           | string           | High gauge Color (default #1B8720)   |                               |
| sFix                             | string           | gauge Value Suffix (default 0.0)     | %                             |
| gTheme                           | string           | Gauge theme color (default Black)    |                               |
