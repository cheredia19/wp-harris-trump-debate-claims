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
  title="Analyzed claims by topic"
  xAxis="topic"
  yAxis="times"
/>

<PlotlyBarChart
  data={{
    url: 'assessments.csv'
  }}
  title="Assessments of the claims made by each candidate"
  xAxis="assessment"
  yAxis="times"
/>

<PlotlyBarChart
  data={{
    url: 'trump_assessments.csv'
  }}
  title="Assessments of the 40 claims made by Donald Trump"
  xAxis="assessment"
  yAxis="times"
/>

<PlotlyBarChart
  data={{
    url: 'harris_assessments.csv'
  }}
  title="Assessments of the 15 claims made by Kamala Harris"
  xAxis="assessment"
  yAxis="times"
/>

<PlotlyBarChart
  data={{
    url: 'twp_assessments.csv'
  }}
  title="The Washington Post's assessment of each candidate's claims"
  xAxis="twp_assessment"
  yAxis="times"
/>
