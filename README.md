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

<PlotlyBarChart
  data={[
    {
      temperature: -0.41765878,
      year: '1850'
    },
    {
      temperature: -0.2333498,
      year: '1851'
    },
    {
      temperature: -0.22939907,
      year: '1852'
    },
    {
      temperature: -0.27035445,
      year: '1853'
    },
    {
      temperature: -0.29163003,
      year: '1854'
    }
  ]}
  xAxis="year"
  yAxis="temperature"
/>

The data files will be automatically displayed here.


