---
datapackage:
  title: Consumer Price Index (CPI)
  description: A template for a dataset to publish on DataHub. Uses the Data Package metadata.
  licenses:
  - path: http://opendatacommons.org/licenses/pddl/
    title: Open Data Commons Public Domain Dedication and License v1.0
  resources:
  - path: cpi_inflation.csv
    title: CPI (12-Month Change (%))
    name: cpi-inflation-bermuda
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

<LineChart
  data="./cpi_inflation.csv"
  title="CPI (12-month change %)"
  xAxis="Food"
  xAxisType="quantitative"
  xAxisTimeUnit = "date"
  yAxis="CPI"
  yAxisType="quantitative"
/>

The data files will be automatically displayed here.


