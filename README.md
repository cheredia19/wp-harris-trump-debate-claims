---
title: Welcome to your template dataset page!
description: 
---

<FlatUiTable
  data={{
    url: 'claims.csv'
  }}
 />

<PlotlyBarChart
  data={{
    url: 'claims.csv'
  }}
  title="Analyzed candidate phrases by topic"
  xAxis="topics"
  yAxis="times"
/>
