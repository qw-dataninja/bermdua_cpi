---
datapackage:
  title: Consumer Price Index (CPI)
  <PlotlyLineChart
  url = "./cpi_inflation.csv"
  xAxis="Date"
  yAxis="CPI"
  title="test"
/>
  resources:
  - path: cpi_inflation.csv
    title: CPI (12-Month Change (%))
    name: cpi-inflation
    format: csv
    schema:
      fields:
      - name: Year
        type: date
      - name: Month
        type: string
      - name: Date
        type: date
      - name: CPI
        type: number
---

Here's some text.

You can add as much text as you like.



The data files will be automatically displayed here.


