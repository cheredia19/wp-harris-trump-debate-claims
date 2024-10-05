---
title: Creation of a database from an article in The Washington Post on verifications of 55 phrases said by Kamala Harris and Donald Trump in the last presidential debate
description: 
---

In the information age, where news spreads fast, people often use opinions, falsehoods, and out-of-context claims to create erroneous opinion matrices that usually overshadow facts. So, fact-checking has never been more critical.

An article from The Washington Post scrutinized 55 sentences made by U.S. presidential candidates Kamala Harris and Donald Trump at the last (and only) presidential debate, held on September 10, highlighting the importance of holding the Democratic and Republican nominees accountable for their statements. 

Building on this, the Datahub team developed a comprehensive database to conduct a data-driven analysis of these claims, offering insights into the accuracy of their assertions. 

This analysis underscores the essential role of fact-checking in promoting transparency, allowing the public to make informed decisions in an era where [misinformation and disinformation](https://www.dictionary.com/e/misinformation-vs-disinformation-get-informed-on-the-difference/) can easily cloud judgment.

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

## The Washington Post's assessments of Harris and Trump's claims

<FlatUiTable
  data={{
    url: 'twp_assessments.csv'
  }}
 />

## The Washington Post's assessments of Donald Trump's claims

<FlatUiTable
  data={{
    url: 'twp_dtrump_assessments.csv'
  }}
 />

 ## The Washington Post's assessments of Kamala Harris' claims

 <FlatUiTable
  data={{
    url: 'twp_kharris_assessments.csv'
  }}
 />

 Source: [The Washington Post](https://www.washingtonpost.com/politics/2024/09/11/fact-check-presidential-debate-harris-trump/)
 
