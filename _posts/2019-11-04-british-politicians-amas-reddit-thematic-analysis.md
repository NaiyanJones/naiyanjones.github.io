---
title: What type of questions do people ask British politicians in online Q&As? A
  thematic analysis of MP’s “Ask Me Anything” sessions on Reddit
date: 2019-11-04 00:00:00 +00:00
categories:
- Politics
tags:
- British politics
- Politicians
- Social media
excerpt_separator: "<!--more-->"
analytics:
  provider: google-gtag
  google:
    tracking_id: UA-168799890-2
    anonymize_ip: false
toc: true
toc_label: Table of Contents
---

_This blogpost is the first in a two-part series which outlines the result of a study on MP’s social media Q&As sessions. This first post details the themes of questions asked,_ [_the second on the extent to which MPs evaded answering questions_](https://naiyanjones.github.io/politics/british-politicians-amas-reddit-equivocative-analysis/)_. The dissertation received a Distinction from the University of Birmingham, 2019._

![](/assets/images/0__zUrDMfVTl65kXEA8.jpg)

# Introduction

It’s rare for people to directly interact with elected politicians in the UK. It’s even rarer to ask questions and get a direct personal response, instead of a standard reply made by an intern, researcher or assistant.

But that’s exactly what happened on [Reddit](https://www.reddit.com/).

Reddit is a social media platform which is mainly anonymous (or pseudo-anonymous). It boasts 330 million active subscribers, and over 1.2 million communities known as “subreddits”, ranging from as little as several users to 18 million. And a website with a sizeable British userbase and number of subreddits.

Several British MPs have conducted Q&A sessions with users of the site to date. These sessions are referred to as ‘Ask Me Anything’ (AMAs) on the website.

{% include figure image_path="/assets/images/1__SMjJVFVifViBI0657bC3IA.jpeg" caption="[President Obama’s AMA](https://redd.it/z1c9z) from 2012 is the most popular to date" %}

These AMAs can give several insights. Firstly it shows the things people think are important and willing to ask politicians. Secondly it can show the priorities of certain sections of society since the userbase skews male and young ([Pew Research Centre, 2016](https://www.journalism.org/2016/02/25/reddit-news-users-more-likely-to-be-male-young-and-digital-in-their-news-preferences/)). Lastly it can show that communications between people and politicians can be less [toxic and abusive](https://www.sheffield.ac.uk/news/nr/twitter-abuse-politics-1.800975) on social media.

In addition this work fills a gap in the political science social media literature, which has mainly focused on Twitter, and to a less extent Facebook, using what is called digital trace data, like @-messages, retweets, likes or #hastags ([Jungherr, 2016](https://www.tandfonline.com/doi/abs/10.1080/19331681.2015.1132401)). It also fills a gap in the wider “Reddit literature” I identified in my [other work](https://towardsdatascience.com/a-systematized-literature-review-of-reddit-dd2acbe6ebc4).

# Demographics

Large scientific surveys of Reddit have primarily focused on American samples.

> According to Pew Research Centre ([2016](https://www.journalism.org/2016/02/25/reddit-news-users-more-likely-to-be-male-young-and-digital-in-their-news-preferences/)) the average user is American, young, male and likely to be college educated.

These demographics are very similar to Twitter and the platforms average user ([Vaccari, et al., 2013](https://nyuscholars.nyu.edu/en/publications/social-media-and-political-communication-a-survey-of-twitter-user)).

## British Reddit users

There has been no rigorous large scientific surveys of British users to date. Instead we can use other sources to given an indication, while keeping in mind their limitations.

[Alexa Ranking](https://www.alexa.com/siteinfo/reddit.com) which records desktop web traffic notes 8% of Reddit traffic is from the UK. This does not track the [40% of users who use the official mobile app.](https://www.reddit.com/r/announcements/comments/5q4qmg/out_with_2016_in_with_2017/?st=iydbz2gd&sh=ecdd146b)

Users of certain British subreddits have conducted their own user surveys. These surveys can be used to given an indication of demographics but must be approached with caution given their lack of scientific rigor. The British political subreddit /r/ukpolitics [ran a survey](https://www.reddit.com/r/ukpolitics/comments/8dve8g/april_rukpolitics_opinion_poll_results/) which had approximately 900 respondents. This survey reported:

*   71% of users were between the ages of 18 to 29
*   95% identified as male
*   46% identified as middle class, followed by 27% upper middle, and 22% working class.

The results also showed users to be more left or centre-left. With voting intentions skewed to Labour, the Liberal Democrats and the Conservatives in order of popularity.

{% include figure image_path="/assets/images/1__Wss__lUMef9DHQrGzrOfzMw.png" caption="Adapted from /u/FormerlyPallas’ [April /r/UKPolitics Opinion Pol](https://www.reddit.com/r/ukpolitics/comments/8dve8g/april_rukpolitics_opinion_poll_results/)l (2018)" %}


This skew towards the political left is also mirrored by Claive and Moradpoor’s ([2018](https://www.napier.ac.uk/~/media/worktribe/output-1167476/two-communities-one-topic-exploring-the-british-reddit-community-split-based-on-1.pdf)) findings. They compared the types of news sources posted on the two largest British subreddit communities, /r/unitedkingdom and /r/ukpolitics. They found both had an overall bias towards left wing sources, but /r/ukpolitics had a more diverse political mix of sources.

These above findings and general age demographics of the website strongly suggest a left wing bias. Which strongly corresponds with the trend for age becoming the new dividing line in British politics for voting intention (see: [IpsosMORI, 1997](https://www.ipsos.com/ipsos-mori/en-uk/how-britain-voted-1997?language_content_entity=en-uk); [YouGov, 2017](https://yougov.co.uk/topics/politics/articles-reports/2017/06/13/how-britain-voted-2017-general-election)).

![](/assets/images/1__UqoMXn8X__mcDQTB5elpPJA.jpeg)

# Research design, methods and methodology

This study can be categorised as a qualitative descriptive study.

It is a study which focuses on the “what” rather than “how” and “why” of explanatory or causal studies.

## **Sampling**

These was no prior work on this topic. I created a sampling frame myself using [redditsearch.io](https://redditsearch.io/) by searching for relevant keywords in several subreddits in June 2019.

I identified 40 AMAs from a range of political actors including: party campaigners, journalists, parliamentary researchers, party members, parliamentary candidates, party leaders, peers and politicians from the devolved governments.

Out of these 40 there were 13 MPs. I excluded two AMAs on grounds of them being non-comparable. One involved answering questions via Youtube and the other one selectively answered questions 8 days after the AMA had taken place.

![image-center](/assets/images/1__Dy2XEFkzms33IlfXuxdDYQ.png){: .align-center}

In total 11 AMAs were selected, comprising of 2,301 comments for analysis.

## **Thematic analysis**

All comments were uploaded to [Nvivo 12](https://en.wikipedia.org/wiki/NVivo) for analysis. Top level and follow-up comments were selected. Each comment was read closely in recognition that users could ask multiple questions in a single comment. I then conducted a thematic analysis on the dataset.

Thematic analysis is a method for identifying and analysing patterns within qualitative data. To analyse the questions I followed Braun and Clarke’s ([2006: 15–13](https://www.tandfonline.com/doi/abs/10.1191/1478088706qp063oa)) popular six step process which involved:

1.  Familiarising myself with the dataset
2.  Generating initial codes systematically across the entire dataset
3.  Collecting selected codes into potential themes
4.  Reviewing themes by checking the validity of each constructed theme in relation to each other
5.  Defining names and themes
6.  Producing the report

## **Limitations**

A major limitation of this study is the lack of a second researcher to review codes and themes indepently.

Thematic and content analysis are inherently biased because of researcher self report and unintended influence of their viewpoints. In contrast, published thematic and content analysis studies of Reddit have involved multiple researchers ([Pilkington and Rominov, 2017](https://www.ncbi.nlm.nih.gov/pubmed/30804656); [O’Neill, 2018](https://www.crimejusticejournal.com/article/view/893); [Sharma, et al., 2017](https://www.ncbi.nlm.nih.gov/pubmed/28025516); [Sowles, et al., 2018](https://www.sciencedirect.com/science/article/abs/pii/S1740144517302528)). This allows for independent coding and comparison of codes, themes and results to test for reliability (see: [intercoder reliability](https://methods.sagepub.com/reference/encyclopedia-of-survey-research-methods/n228.xml)).

Furthermore, there are ethical implications for conducting social media research. Reddit specifically is envisioned as a public place, but many users of the site may view it as public-private and dislike researcher intrusion and use of past comments ([Association of Internet Researchers, 2012](https://aoir.org/reports/ethics2.pdf)).

And on a broader level the British public’s concerns about online data and privacy issues must be acknowledged ([Ofcom & ICO, 2019](https://ico.org.uk/media/about-the-ico/documents/2615000/online-harms-chart-pack.pdf)).

# **Results**

After analysis 14 major and 34 minor themes were identified from 713 individual questions asked.

![](/assets/images/1__eat4CSQt6dL__x85omxWUkQ.png)

Major themes were identified post-analysis. They were defined by a gap in popularity by the number of questions asked. With the next theme being half as popular by questions asked as the preceding theme.

![](/assets/images/1__OafX__qZEpgu3OrvhhRNgdQ.png)

As seen above, most questions were on the EU and Brexit, elections and campaigning, party political issues, and non-political and humour. Housing (notably being the first non-EU related policy issue), the lives of MPs, economic, democratic deficit, drugs, immigration, digital, constituency, welfare, and electoral themed questions in order of popularity.

## The EU and Brexit

MPs were asked about their views on the EU and Britain’s withdrawal. The majority of questions centred around their voting intentions in the lead up to the 2016 EU Referendum, and the potential impact of proposed scenarios. MPs were asked if the campaign claims by both Leave and Remain were “actually true or… made up” and several mentioned Michael Gove’s comments on the British people “having enough of experts”. Both campaigns were accused of producing propaganda which made people “frustrated” because they felt that they had to sift through the “rubbish both sides are throwing out”.

## Elections and campaigns

Elections and campaigns were heavily discussed, with questions centring around party manifestos, performance and campaign strategies. Party performances and potential electoral threat included the Greens to the Liberal Democrat vote, the perceived inactivity of the Remain campaign, and the discussion of low polling numbers. The 2014 Scottish Independence Referendum and 2015 General Election were also prominent.

## Party political issues

This theme covered political parties themselves, including internal conflict between factions, the record of parties in government, and perceptions of political parties by the wider public. Internal conflict was mainly centred around Jeremy Corbyn and challenges and resignations by Labour MPs. While the Liberal Democrat were challenged on their record in government as junior coalition partners during the Conservative-Liberal Coalition Government. Lastly questions revolved around perceived negative perceptions of political parties by the wider public, with Liberal Democrats worried about being “taken seriously”, Labour being out of touch, and the Conservatives as being “inherently evil, the spawn of Satan”.

## Non-political humour

Non-political and humorous questions were popular reflecting the ethos of Reddit’s Ask Me Anything format, with the emphasis on _Anything._ Questions ranged from the choice between “hash browns or black puddings?”, “is Jaffa Cake a biscuit or cake?” to “What would you rather fight, one David Cameron sized duck, or 100 duck sized David Camerons?’. A reference to a [popular Reddit meme](https://knowyourmeme.com/memes/horse-sized-duck) often asked in AMAs.

## The lives of MPs

People showed an interest in the lives of MPs themselves as individuals. Users asked about their careers, lives and what it meant to be an MP. Common questions asked when they first realised they wanted to become involved in politics and stand for office, the transition from other career paths, and potential future career plans. Moreover they were asked what a normal working day entails, what support they received to carry out their duties, and the “difference that seperate a good parliamentarian from a bad one?”

## Housing

Housing was a frequent policy issue and mentioned in all AMAs. People were concerned about about the affordability, supply and demand. Supply questions included the design of new builds, building restrictions on greenbelt land, restrictions on local government, and the potential for investment by central government. Demand issues were mainly concerned with migration from the 1997–2010 Labour administrations.

## The economy

Economic questions ranged from open ended, such as “what economic policies would you implement if the Labour Party was in power today?”, to much more specific policy and proposals. These included taxation on alcohol, capital gains, financial transactions (the “Robin Hood tax”), land value, and tax avoidance. MPs were also asked about the impact of the 2010 coalition government’s austerity policies on the economy.

## Democratic deficit

This theme encompasses questions about the existence and reasons for a disconnect between politicians and the public. It includes a perceived negative political atmosphere due to lack of engagement, apathy, and the state of discourse. Partisan “bickering” in Prime Minister’s Questions was especially singled out. A subset of users also proposed solutions to this deficit such as reforming the House of Commons, electoral reform, and a stronger evidence-led policy making process.

## Drug reform

MPs were solicited for their views and perceived barriers to drug reform, including lack of evidence-led policy. They were asked if anything was “happening about drug legislation… within the next four years”, their “views on the current state of the drug policy in the UK”, and if drugs were a “major policy issue come the next election”. At the same time users recognised that drug reform was a relatively niche compared to other “serious issues” and one user prefaced their question with “I know drug reform is pretty much impossible in this country, but…”.

## Immigration

Immigration was a recurring theme which appeared in every AMA minus one. Immigration was heavily correlated with other policy issues. It was discussed in terms of the Leave and Remain campaigns and rhetoric, its impact on housing, and the present and past policies of political parties. The Labour Party and the Remain campaign were singled out for having a ‘blind spot’ towards immigration which has negatively affected the employment opportunities of the working class.

## Digital issues

Digital issues comprised of questions about general internet censorship, to specific legislation, and campaigns against said legislation. For example, pornographic filters during David Cameron’s administration, mass surveillance and civil liberties encroachment from the Investigatory Powers Act 2016 (dubbed the “Snooper’s charter”). Overall accessing content on the internet and filters were discussed in terms of an “open internet” being encroached by “disproportionate and unsafe” policy proposals.

## Constituency issues

The majority of AMAs each contained a question about the MP’s constituency with users disclosing or indicating they were constituents interested in local issues. This ranged from broad questions on how MPs had represented their constituency “in the House of Commons on local issues”, the future of a local hospital, transport infrastructure, the effects of an RAF base closure, and what could be done about “decent telecoms infrastructure”.

## Welfare

Welfare questions were diverse, with people concerned about with current welfare provisions. These included accusations of the British media demonising the less fortunate in society, the “bedroom tax” for under occupancy of social housing from the 2012 Welfare Act, and the rise in homelessness. Furthermore, MPs were asked for their views on a higher national minimum wage and living wage and the scrapping of the bedroom tax.

## Electoral reform

Electoral reform encompassed explicit alternative voting system to first past the post (FPTP), to lowering the voting age to 16, and reforming the House of Commons and House of Lords. MPs were solicited for their views, support and also their party’s support of these reforms.

# Discussion

## Results of the thematic analysis

Firstly, given the younger demographics of Reddit it is not unsurprising that some themes and policy issues were popular. However, the importance of these policy issues seem to differ from those reported by younger people in scientific surveys ([Sloam and Henn, 2019](https://www.palgrave.com/gp/book/9783319974682); [Ashcroft, 2017](https://lordashcroftpolls.com/2017/06/result-happen-post-vote-survey/)). The popular issues identified here were EU-Brexit, party politics, elections, housing and the economy. This contrasts to those identified by Ashcroft which were the NHS/Hospitals, Brexit, austerity, cuts and inequalities, education, economic/jobs, and the environment ([Ashcroft, 2017](https://lordashcroftpolls.com/2017/06/result-happen-post-vote-survey/)).

Secondly, the themes indicate a politically engaged userbase with interest beyond single issue policy issues. This is shown by interest in party politics (including internal elections), interest in the lives of MPs, and concerns of a wider democratic deficit.

Lastly, this study identified proactive moderation by the volunteer moderators of several subreddits who removed comments in the AMAs under study. Of the 2,301 comments analysed, 92 were removed.

## Placing in the wider literature

Firstly the use of Reddit by mainstream political parties reflects findings on Twitter with Labour and Liberal Democrats accounting for the majority of AMAs ([Ahmed and Skoric, 2014](https://ieeexplore.ieee.org/document/6758880); [Ahmed et al., 2016](https://dl.acm.org/citation.cfm?id=2937355)).

![](/assets/images/1__Diocd5H3kkDvpa__UjdG45g.png)

Secondly, the timing of the AMAs strongly correspond to election periods ([Evans et al., 2014](https://www.cambridge.org/core/journals/ps-political-science-and-politics/article/twitter-style-an-analysis-of-how-house-candidates-used-twitter-in-their-2012-campaigns/2975E5DB5DC41AE4F4977264DDDFE649#); [Vergeer and Hermans, 2013](https://onlinelibrary.wiley.com/doi/full/10.1111/jcc4.12023)). Particularly the 2015 General Election, and also internal party elections, such as the 2016 Labour Party leadership election. Given elections correspond to AMAs it is not surprising that MPs’ use of Reddit aligned with Jackson and Lilleker’s ([2011](https://www.tandfonline.com/doi/abs/10.1080/13572334.2011.545181)) finding of MPs using social media mainly for impression management and self-promotion.

Thirdly, like Twitter political discourse were mainly centred on campaigns and elections ([Small, 2010](http://revparl.ca/33/3/33n3_10e_Small.pdf); [Bruns and Burgess, 2011](https://eprints.qut.edu.au/46515/%29)), however the results of this study indicates that policy issues are slightly more popular topic on Reddit. At least in political Q&As.

Lastly, the theme of non-political and humorous questions bares striking similarity to the identification of humour, satire and irony in political tweets ([Bode and Dalrymple, 2016](https://www.tandfonline.com/doi/abs/10.1080/15377857.2014.959686); [Trilling, 2015](https://journals.sagepub.com/doi/abs/10.1177/0894439314537886?journalCode=ssce); [Merjova et al., 2013](https://dl.acm.org/citation.cfm?id=2433463)) and Mumsnet comments ([Campbell and Childs, 2010](https://academic.oup.com/pa/article-abstract/63/4/760/1585321)).

_This ends the first in a two part series. This post covered the themes of questions asked, the second will cover the extent to which MPs answered questions_

Note: This blogpost was originally posted on [Medium in November 2019](https://medium.com/what-type-of-questions-do-people-ask-british-politicians-in-online-q-as-e8aaa2f6315f).
{: .notice--primary}
