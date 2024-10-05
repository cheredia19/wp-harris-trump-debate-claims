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
  title="Frases analizadas de los candidatos por tópico"
  xAxis="topics"
  yAxis="times"
/>
