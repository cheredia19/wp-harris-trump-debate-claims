---
title: Welcome to your template dataset page!
description: 
---

<FlatUiTable
  data={{
    url: 'all_claims.csv'
  }}
 />

<PlotlyBarChart
  data={{
    url: 'topics.csv'
  }}
  title="Analyzed candidate phrases by topic"
  xAxis="topic"
  yAxis="times"
/>
