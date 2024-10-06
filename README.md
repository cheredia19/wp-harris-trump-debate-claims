---
title: Creation of a database from an article in The Washington Post on verifications of 55 phrases said by Kamala Harris and Donald Trump in the last presidential debate
description: 
---

In the information age, where news spreads fast, people often use opinions, falsehoods, and out-of-context claims to create erroneous opinion matrices that usually overshadow facts.

The issue worsens when politicians lie or manipulate the truth to their benefit. When this happens, fact-checking becomes critical.

An **article from The Washington Post** (TWP) scrutinized 55 sentences made by U.S. presidential candidates **Kamala Harris** and **Donald Trump** at their only presidential debate, [held on September 10 and hosted by ABC](https://abcnews.go.com/Politics/harris-trump-presidential-debate-transcript/story?id=113560542).

Building on this, the Datahub team developed a comprehensive database to conduct a data-driven analysis of these claims, offering insights into the accuracy of their assertions. 

TWP's article underscores the essential role of fact-checking in promoting transparency  and holding the Democratic and Republican nominees accountable for their statements, allowing the public to make informed decisions in an era where [misinformation and disinformation](https://www.dictionary.com/e/misinformation-vs-disinformation-get-informed-on-the-difference/) can easily cloud judgment.

The table below summarizes all the 55 claims (40 from Trump, 15 from Harris) made at the debate, the ten identified topics, and the verdicts from TWP (and our own). The sentences in the table can be filtered by any of the fields.

<FlatUiTable
  data={{
    url: 'all_claims.csv'
  }}
 />

Some insights:



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
 
