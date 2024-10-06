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

Some initial insights:

- TWP assessed 21 former president's claims as false. Apart from False, the media outlet used verdicts such as *flat wrong*, *repeatedly debunked*, *absurd*, *poppyrock*, and *channeling right-wing social media sensations*.
- None of Harris' claims were assessed false by TWP. Two were *true* and *correct*, one was *partly false*, and another was *out of date*.
- Based on TWP analysis, we labeled 3/4 of Trump's phrases as False. Even though we assessed one of Harris' claims as False, 53.3% (8/15) of them need context, according to our scrutiny.
- The economy, immigration, and abortion were the most analyzed Trump's topics. 
- TWP focused on Harris' POV about the economy and external issues but did not take into account her immigration or abortion claims.

Speaking on topics, the article reviewed ten economy, eight external issues, and six immigration (all Trump's, all fake) phrases from both candidates. Other subjects, such as [Project 2025](https://static.project2025.org/2025_MandateForLeadership_FULL.pdf) and [The Central Park Five](https://www.bbc.com/news/newsbeat-48609693) were considered by TWP.

<PlotlyBarChart
  data={{
    url: 'topics.csv'
  }}
  title="Analyzed claims by topic"
  xAxis="topic"
  yAxis="times"
/>

We assessed 31 of the 55 claims as *false* (56.36%) and 14 (25.45%) as *needs context*. Two were, *exaggerated*, *partially true*, *mostly true*, or *true*. One was *underestimated*, another was *unverifiable*.

<PlotlyBarChart
  data={{
    url: 'assessments.csv'
  }}
  title="Assessments of the claims made by each candidate"
  xAxis="assessment"
  yAxis="times"
/>

As said above, out of the 40 Donald Trump sentences assessed by TWP, **75% were false** (TWP used other adjectives that implied misrepresentation). **Only one was true**, according to the renowned media outlet. More precisely, TWP said Trump "got this right" when he claimed Harris has never supported defunding the police.

<PlotlyBarChart
  data={{
    url: 'trump_assessments.csv'
  }}
  title="Assessments of the 40 claims made by Donald Trump"
  xAxis="assessment"
  yAxis="times"
/>

One of the 15 Kamala Harris' phrases was labeled true by our team (The former president has said that climate change is a hoax), and another was false (Trump took out a full-page ad in the New York Times calling for the execution of five young Black and Latino boys who were innocent, referring to *The Central Park Five*). **Over half of the claims need additional context**, and two looked exaggerated.

<PlotlyBarChart
  data={{
    url: 'harris_assessments.csv'
  }}
  title="Assessments of the 15 claims made by Kamala Harris"
  xAxis="assessment"
  yAxis="times"
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
 
