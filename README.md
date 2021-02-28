# Edd Webster Football Analytics
This repository is a public space for the football analytics projects by [Edd Webster](https://twitter.com/eddwebster).

<p align="center">
  <a href="https://www.twitter.com/eddwebster"><img src="img/fifa21eddwebsterbanner.png"></a>
</p>


I recently accidentally deleted what was quite a well written and cited README file for this repository, unfortunately without backup. Whilst this notice remains, I am currently rewriting it to include the full list with links of: data sources, libraries & webscrapers, and favourite papers and learning materials, all of which include links to credited sources. This is currently in progress but not yet finished - 28/02/2021.

## About this Repository and Author
Please note, all work produced in this repository is mine and/or credited to the publicly produced code and libraries used. and is in no way related to the work and analysis I produce for my employers.

For more information about this repository and the author, I'm available through all the following channels:
*    [eddwebster.com](https://www.eddwebster.com/);
*    edd.j.webster@gmail.com;
*    [@eddwebster](https://www.twitter.com/eddwebster);
*    [linkedin.com/in/eddwebster](https://www.linkedin.com/in/eddwebster/);
*    [github/eddwebster](https://github.com/eddwebster/);
*    [public.tableau.com/profile/edd.webster](https://public.tableau.com/profile/edd.webster);
*    [kaggle.com/eddwebster](https://www.kaggle.com/eddwebster); and
*    [hackerrank.com/eddwebster](https://www.hackerrank.com/eddwebster).

## Notebooks
For code, see the notebooks subfolder, in which the workflow is divided into the following:
1.    [Webscraping](https://github.com/eddwebster/football_analytics/tree/master/notebooks/1_data_scraping);
2.    [Data Parsing](https://github.com/eddwebster/football_analytics/tree/master/notebooks/2_data_parsing);
3.    [Data Engineering](https://github.com/eddwebster/football_analytics/tree/master/notebooks/3_data_engineering);
4.    [Machine Learning](https://github.com/eddwebster/football_analytics/tree/master/notebooks/4_machine_learning); and
5.    [Data Analysis](https://github.com/eddwebster/football_analytics/tree/master/notebooks/5_data_analysis_and_projects) - projects include working with [Tracking data](https://github.com/eddwebster/football_analytics/tree/master/notebooks/5_data_analysis_and_projects/tracking_data), constructing [VAEP models](https://github.com/eddwebster/football_analytics/tree/master/notebooks/5_data_analysis_and_projects/vaep) (as introduced by SciSports), building [xG models](https://github.com/eddwebster/football_analytics/tree/master/notebooks/5_data_analysis_and_projects/xg_modeling) using Logistic Regression, Decision Trees and XGBoost, and analysing [player similarity](https://github.com/eddwebster/football_analytics/tree/master/notebooks/5_data_analysis_and_projects/player_similarity) using PCA and Factor Analysis.

## Data Visualisation and Tableau 
For Tableau dashboards produced using the data engineered in the notebooks in this repository, please see my Tableau Public profile: [public.tableau.com/profile/edd.webster](https://public.tableau.com/profile/edd.webster). 
*    WSL dashboards and analysis [[link](https://public.tableau.com/views/EddWebsterFAWSLAnalysisandDashboard/WSLxGAnalysisDashboard?:language=es&:display_count=y&:origin=viz_share_link)];
*    ‘Big 5’ European leagues dashboards and analysis [[link](https://public.tableau.com/views/EddWebsterBig5EuropeanLeagueAnalysisandDashboards/Big5WaffleChart?:language=es&:display_count=y&:origin=viz_share_link)];
*    EFL dashboards and analysis [[link](https://public.tableau.com/views/EddWebsterEFLAnalysisandDashboards/EFLFullBackRadarDashboard?:language=es&:display_count=y&:origin=viz_share_link)];
*    StrataBet Chance dashboards and analysis [[link](https://public.tableau.com/views/EddWebsterStrataBetChanceAnalysisandDashboards/StrataBetChanceShotMapDashboard?:language=es&:display_count=y&:origin=viz_share_link)]; and
*    Opta [#mcfcanalytics](https://twitter.com/search?q=%23mcfcanalytics) dashboards and analysis [[link](https://public.tableau.com/views/EddWebsterOptaMCFCAnalyticsPL1112AnalysisandDashboards/OptaPlayerDemographicsDashboard?:language=es&:display_count=y&:origin=viz_share_link)].

## Data Sources
Due to the 100mb file size limitation in GitHub, all engineered datasets prepared in this repository have been exported and made publicly available to view and download in Google Drive. Please see the following [[link](https://drive.google.com/drive/folders/1r2Rf3CPsKnxyxtmDRIHQ2eoW5WwCzBa0?usp=sharing)]. However, all code in this repository should enable you to scrape, parse, and engineer the datasets used in the data analysis and visualisation.

Data sources featured in this repository include:
*    DAVIES estimated player evaluation data by Sam Goldberg for American Soccer Analysis;
*    ELO club rankings;
*    FIFA 15-21 player rating data;
*    [KPMG Football Benchmark](https://footballbenchmark.com/home) player valuation data;
*    [Last Row Tracking-like data](https://github.com/Friends-of-Tracking-Data-FoTD/Last-Row) by Ricardo Tavares;
*    [Metrica Sports Tracking data](https://github.com/metrica-sports/sample-data);
*    Opta Sports match-by-match aggregated player performance data for the 11/12 season and F24 Event data for a 11/12 match of Manchester City vs. Bolton Wanders as part of the [#mcfcanalytics](https://twitter.com/search?q=%23mcfcanalytics) initiative;
*    Signality Tracking data;
*    [SkillCorner broadcast Tracking data](https://github.com/SkillCorner/opendata);
*    [StatsBomb Open Event data](https://github.com/statsbomb/open-data);
*    StatsBomb season-on-season aggregated player performance data scraped from FBref using [Parth Athale](https://twitter.com/ParthAthale)'s [FBref webscraper](https://github.com/parth1902/Scrape-FBref-data), in turn ;
*    Stats Perform CPL Event data [[link](https://drive.google.com/drive/u/0/folders/1ktlkt6f6Ujami53YCS-Lbc9BGGL8BaYA)]
*    StrataBet Chance shooting data;
*    TransferMarket player bio and fiscal data scraped using the FCrStats webscraper (pull request submitted);
*    Understat shooting and meta data including player xG values; and
*    Wyscout Event data for the 17/18 season for the 'Big 5' European leagues, Euro 2016 Chanpionship, and 2018 World Cup made available by [Luca Pappalardo](https://twitter.com/lucpappalard?). See his paper [A public data set of spatio-temporal match events in soccer competitions](https://www.nature.com/articles/s41597-019-0247-7).
*    Reference data:
     -    League-wide xT values from the 2017-18 Premier League season (12x8 grid) by [Karun Singh](https://twitter.com/karun1710/) [[link](https://karun.in/blog/data/open_xt_12x8_v1.json)]
     -    Zones on a pitch for Tableau visualisation by [Rob Carroll](https://twitter.com/thevideoanalyst) [[link](https://drive.google.com/drive/folders/1Se0DFtsjQWmnt-G9Ihn_w8EQE4EZiblD)]

## Learning Resources
*    Friends of Tracking YouTube channel [[link](https://www.youtube.com/channel/UCUBFJYcag8j2rm_9HkrrA7w)] and Mathematical Modelling of Football course by Uppsala University [[link](https://uppsala.instructure.com/courses/28112)]. The GitHub repo with all code featured can be found at the following [[link](https://github.com/Friends-of-Tracking-Data-FoTD)];
*    [Soccer Analytics Handbook](https://github.com/devinpleuler/analytics-handbook) by [Devin Pleuler](https://twitter.com/devinpleuler)
*    Tableau Football User Group [[link](https://usergroups.tableau.com/footballtableauusergroup)]
*    Tableau for Sport by [Rob Carroll](https://twitter.com/thevideoanalyst) [[link](https://thevideoanalyst.com/tableau-sport/)] - completely free tutorials for using football data in Tableau;

## Libaries
*    [`kloppy`](https://github.com/PySport/kloppy) - a Python package providing (de)serializers for soccer tracking- and event data, standardized data models, filters, and transformers designed to make working with different tracking- and event data like a breeze.
*    [`socceraction`](https://github.com/ML-KULeuven/socceraction) - a Python library for valuing the individual actions performed by soccer players. Includes an Expected Threat (xT) implementation. From [Tom Decroos](https://twitter.com/TomDecroos) et. al.
*    [`statsbombpy`](https://github.com/statsbomb/statsbombpy) - a Python library written by Francisco Goitia to access StatsBomb data.
*    [`matplotsoccer`](https://github.com/TomDecroos/matplotsoccer) - a Python library for visualising soccer event data by [Tom Decroos](https://twitter.com/TomDecroos).
*    [`mplsoccer`](https://github.com/andrewRowlinson/mplsoccer) - a Python library for drawing soccer/football pitches in Matplotlib and loading StatsBomb open-data by [Andrew Rowlinson](https://twitter.com/numberstorm)
*    [`statsbomb-parser`](https://github.com/imrankhan17/statsbomb-parser) - Python library to convert StatsBomb's JSON data into easy-to-use CSV format.
*    [`Scrape-FBref-data`](https://github.com/parth1902/Scrape-FBref-data) - Python library to scrape StatsBomb data via FBref by [Parthe Athale](https://twitter.com/ParthAthale), which in turn was updated from [Christopher Martin](https://github.com/chmartin)'s [repository](https://github.com/chmartin/FBref_EPL)
*    [`Tyrone Mings`](https://github.com/FCrSTATS/tyrone_mings) - a Python TransferMarkt webscraper by [FCrSTATS](https://twitter.com/FC_rstats)
*    [`ggsoccer`](https://github.com/Torvaney/ggsoccer) - Soccer visualization library in R from [Ben Torvaney](https://twitter.com/Torvaney)

## GitHub repos
*    [Google Research Football](https://github.com/google-research/football)
*    [LaurieOnTracking](https://github.com/Friends-of-Tracking-Data-FoTD/LaurieOnTracking) by [Laurie Shaw](https://twitter.com/EightyFivePoint) - Python code for working with Metrica tracking data.
*    [occermatricsForPython](https://github.com/Friends-of-Tracking-Data-FoTD/SoccermaticsForPython) by [David Sumpter](https://twitter.com/Soccermatics): This repo is dedicated for people getting started with Python using the concepts derived from the book Soccermatics (Sumpter 2016)
*    [FoundationsInR](https://github.com/Friends-of-Tracking-Data-FoTD/FoundationsInR) by [Sudarshan Golaladesikan](https://twitter.com/suds_g) - getting started with R using the StatsBomb dataset.
*    [analytics-handbook](https://github.com/devinpleuler/analytics-handbook) by [Devin Pleuler](https://twitter.com/devinpleuler)
*    [football-crunching](https://github.com/rjtavares/football-crunching) by Ricardo Tavares (@rtavares). Accompanying Medium posts [[link](https://medium.com/football-crunching)]
*    [soccermatics](https://github.com/JoGall/soccermatics) by Joe Gallagher (R)

## Videos
For a YouTube playlist of over 800 Sports Analytics / Data Science video that I put together for my own viewing, see [[link](https://www.youtube.com/watch?v=lLcXH_4rwr4&list=PL38nJNjpNpH9OSeTgnnVeKkzHsQUJDb70&ab_channel=FourFourTwo)]. For a Tableau in football specific playlist, see [[link](https://www.youtube.com/watch?v=Rx7FWugmBC4&list=PL38nJNjpNpH__B0QzZ3BA0B3AxGzt0FAl&ab_channel=TableauSoftware)].

*    Laurie Shaw's Metrica Sports Tracking data series for #FoT - [Introduction](https://www.youtube.com/watch?v=8TrleFklEsE), [measuring physical performance](https://www.youtube.com/watch?v=VX3T-4lB2o0), [Pitch Control modelling](https://www.youtube.com/watch?v=5X1cSehLg6s), and [valuing actions](https://www.youtube.com/watch?v=KXSLKwADXKI);
*    StatsPerform AI in Sport series - [Overview](https://vimeo.com/473259469/3d56393c68), [AI in Basketball](), [AI In Soccer](https://vimeo.com/515977363/be3de09fc1), and [AI in Tennis]();
*    [Tom Goodall's Tactics, Training & Tableau: Football Tableau User Group](https://www.youtube.com/watch?v=Hy0tHU7yYHs&t=1702s). Check out his Football Tableau training courses [[link](https://www.touchlineanalytics.co.uk/)
*    What Football Analytics can Teach Successful Organisation by Rasmus Ankersen (@RasmusAnkersen)
*    Soccermatics: how maths explains football by David Sumpter (@Soccermatics)
*    Changing the soccer transfer market with big data by Giels Brouwer
*    How Stats Won Football: From Moneyball to FC Midtjylland – COPA90 Stories Documentary
*    The Numbers Game: How Data Is Changing Football - FourFourTwo Documentary
*    Christmas Lectures 2019: How to Get Lucky with Hannah Fry. Small segment with Tim Waskett (@StoneBakedGames)


## YouTube Channels
*    [Friends of Tracking](https://www.youtube.com/channel/UCUBFJYcag8j2rm_9HkrrA7w) with David Sumpter, Javier Fernández, Laurie Shawm, Suds Gopaladesikan, Pascal Bauer, and Fran Peralta
*    [McKay Johns](https://www.youtube.com/channel/UCmqincDKps3syxvD4hbODSg)
*    [Barça Innovation Hub](https://www.youtube.com/channel/UC58nLq78KZGqxfSNFNRCgsQ) (English and Spanish)
*    [Mark Glickman](https://www.youtube.com/channel/UC-gtC2WYRAr_4eYRIUb4ovg) – for NESSIS talks, uploaded to his personal channel. Old talks are available on his [Metacafe channel](https://www.metacafe.com/channels/Mark%20Glickman/). See the official website [[link](http://www.nessis.org/)]
*    [42 Analytics](https://www.youtube.com/user/42analytics) – for SSAC conferences 
*    [StatsBomb](https://www.youtube.com/channel/UCmZ2ArreL9muPvH49Gaw0Bw)
*    [Opta](https://www.youtube.com/user/optasports) - including Opta Pro Forum talks
*    [STATS Insights](https://www.youtube.com/user/BloombergSports)
*    [Tifo Football](https://www.youtube.com/channel/UCGYYNGmyhZ_kwBF_lqqXdAQ)
*    [Football Whispers](https://www.youtube.com/channel/UCKrQ1kewgRUbrwl_LcqJ6pQ)
*    [Football Player Ratings](https://www.youtube.com/channel/UC64jAkIQX-hD3pSnnOmr2MA) by [Lars Magnus Hvattum](https://twitter.com/FLSimulator)
*    [The Coaches’ Voice](https://www.youtube.com/channel/UCuR-ZdVJtF3muYhYUQ-he-Q)

## Podcasts (Spotify links used where available)
*    [American Soccer Analysis](https://www.americansocceranalysis.com/podcasts)
*    [Analytics FC Podcast](https://analyticsfc.co.uk/podcast/)
*    [Big Data Sports](https://open.spotify.com/show/3Kv1yl0tCt1JDpD0AxtxZ7) (Spanish)
*    [Double Pivot Podcast](https://open.spotify.com/show/4lBU3spHZaQWJyUcCUbkY8)
*    [Differentgame - The Football Analytics Podcast](https://open.spotify.com/show/0EHSv20UxlqnOjaUNzdiGN?si=rc48L2eFRLCLXZyROU8GSw) by Paul Riley and Richard Shephard
*    [Expected Value](https://open.spotify.com/show/5xFeWbaaLFepY5n73SfWwr)
*    [Fanalytics](https://open.spotify.com/show/3G3LWoSWZdHW4Gg6igjIHU) with Mike Lewis 
*    [The Football Fanalytics Podacst](https://open.spotify.com/show/6JwWRPMaHfGicFBtl7nI3V?si=IwQ00tyTRPaBcW-0XLwS4w&nd=1)
*    [Football Today](https://open.spotify.com/show/1WRaXZgVlksph0IjsTNBaG?si=0zyUX59sTKqCRnq92SEylQ&nd=1)
*    [Laptop Gurus](https://open.spotify.com/show/3sPI2CtmRJeaShdqNjrGRH?si=1NRk7exnRWaNbqbDO0B72w)
*    [Measurables Podcast](https://open.spotify.com/show/1B2KCrfMM6sDfNICsyVDlW) by [Brendan Kent](https://twitter.com/brendankent)
*    [The Scouted Football Podcast](https://open.spotify.com/show/4qYVKC8RlHCJrwrRCx0w6H?si=M6xgCGtdTjiy0wEl1e2CJw)
*    [smarterscout: The Why in Analytics](https://open.spotify.com/show/2QP4KXajJ5xOfW1ny78nAf?si=NQAf_4XtSFeQXAZi1bbupQ) by Dan Altman
*    [StatsBomb](https://open.spotify.com/show/2EgxEas2CUsGpuH5AGWnAO?si=yvTrhRLGSBm7XanWZnd7lA)
*    [Target Scouting](https://open.spotify.com/show/2SJENgKp4BrmeufJPKC2TH?si=hq4tXC3sSKGkej4VU8w40w) by Luke Griffin
*    [Tifo Podcast](https://open.spotify.com/show/06QIGhqK31Qw1UvfHzRIDA?si=eJzpmtMeSPWUDP9fQ-5pqA)
*    [Three At The Back](https://open.spotify.com/show/4NbunP2podS7hIPD2BVlYF?si=OFwVjOucQP6LWZmnGmGqjg) by Opta Pro
*    [Zonal Marking](https://open.spotify.com/show/1o2ZogNQQmPKCntcdKnXPT)

## Blogs
*    [21st Club](https://www.21stclub.com/insight/) - blog posts available in hard-copy form in their [Changing the Conversation](https://www.amazon.co.uk/Changing-Conversation-Presents-Collection-Boardrooms/) series
*    [2+2=11](https://2plus2equals11.com/) by [Will Gürpinar-Morgan](https://twitter.com/WillTGM)
*    [5 Added Minutes](https://5addedminutes.com/) by [Omar Chaudhuri](https://twitter.com/OmarChaudhuri)
*    [8 Yards 8 Feet](https://8yards8feet.wordpress.com/author/simonlock1993/) by [Simon Lock](https://twitter.com/8Yards8Feet)
*    [Analytics FC](https://attackingcentreback.wordpress.com/)
*    [Attacking Center-back](https://attackingcentreback.wordpress.com/) by [JP Quinn](https://twitter.com/AttackingCB)
*    [Carey Analytics](https://careyanalytics.wordpress.com/) by [Mark Carey](https://twitter.com/MarkCarey93)
*    [DeepxG]() by [Thom Lawrence](https://twitter.com/lemonwatcher). Last updated November 29 2017.
*    [Differentgame](https://differentgame.wordpress.com/) by [Paul Riley](https://twitter.com/footballfactman)
*    [EFL Numbers](https://eflnumbers.wordpress.com/) by EFL Numbers (@eflnumbers)
*    [EightyFivePoints](http://eightyfivepoints.blogspot.com/) by Laurie Shaw (@EightyFivePoint)
*    [Experimental 361](https://experimental361.com/) by Ben Mayhew (@experimental361)
*    [FC Python](https://fcpython.com/category/blog) by FC Python (@FC_Python)
*    [Football Crunching](https://medium.com/football-crunching) by Ricardo Tavares (@rjtavares)
*    [Football Data Science](http://business-analytic.co.uk/blog/home-page/) by Dr. Garry Gelade (@GarryGelade)
*    [Football Philosophy](http://footballphilosophy.org/) by Joost van der Leij
*    [Football Science](https://www.footballscience.net/) by Michael C. Rumpf
*    [The Futebolist](https://medium.com/@thefutebolist) by [Ashwin Raman](https://twitter.com/AshwinRaman_)
*    [The Harvard Sports Analysis Collective](http://harvardsportsanalysis.org/topics/soccer/)
*    [Hudl](https://www.hudl.com/blog/)
*    [James W Grayson](https://jameswgrayson.wordpress.com/) by James W Grayson (@JamesWGrayson)
*    [Karun Singh](https://karun.in/blog/) by Karun Singh (@karun1710) 
*    [kwiatkowski.io](https://www.kwiatkowski.io/) by Marek Kwiatkowski (@statlurker)
*    [LukeBornn.com](http://www.lukebornn.com/) by Luke Bornn (@LukeBornn)
*    [Mackay Analytics](https://www.northyardanalytics.com/blog/) by Nils Mackay (@NilsMackay)
*    [Mackinaw Stats](https://mackayanalytics.nl/) by Mackinaw Stats (@MackinawStats)
*    [North Yard Analytics](https://www.northyardanalytics.com/blog/) by Dan Altman (@NYASports)
*    Opta Pro - old blogs removed by available using Wayback Machine
*    [patricklucey.com](http://patricklucey.com/index.html) by Patrick Lucey (@patricklucey)
*    [Penal.lt/y](http://pena.lt/y/) by Martom Eastwood (@penaltyblog)
*    [Piotr Wawrzynów – Football Analysis](https://wawrzynow.wordpress.com/) by [Piotr Wawrzynów](https://twitter.com/pwawrzynow)
*    [Proform AFC](https://proformanalytics.wordpress.com/) by Proform Analytics (@ProformAFC) - Mladen Sormaz (@Mladen_Sormaz) and Dan Nichol (@D4N_)
*    [SaddlersStats](https://www.saddlersstats.co.uk/)
*    [StatDNA](https://web.archive.org/web/20110707064735/https:/blog.statdna.com/) (last updated 01/06/2011 before Arsenal bought the company)
*    [StatsBomb](https://statsbomb.com/articles/)
*    [Stats Perform](https://www.statsperform.com/resources/)
*    [Stats and snakeoil](http://www.statsandsnakeoil.com/) by Ben Torvaney (@Torvaney , formally @stats_snakeoil)
*    [The Last Man Analytics](https://thelastmananalytics.home.blog/) by The Last Man Anayltics (@TLMAnalytics) – Ciaran Grant (@Ciaran_Grant)
*    [The Power of Goals](https://thepowerofgoals.blogspot.com/)
*    [winningwithanalytics.com]() by Bill Gerrard (@bill_gerrard_)
*    [Wooly Jumpers for Goal Posts](https://winningwithanalytics.com/) by The Woolster (@The_Woolster)
*    [Wyscout](https://blog.wyscout.com/)
*    [xG per Shot[(https://xgpershot.wordpress.com/) by [Parthe Athale](https://twitter.com/ParthAthale)


## Blog posts
*    [Assessing	The	Performance	of Premier League Goalscorers](https://opta.kota.co.uk/news-analysis/assessing-the-performance-of-premier-league-goalscorers/)** by [Sam Green](https://twitter.com/aSamGreen)
*    [Counting Across Borders](https://www.statsperform.com/resource/counting-across-borders/) by [Ben Torvaney](https://twitter.com/Torvaney)
*    [Defending Your Patch](https://deepxg.com/2016/02/07/defending-your-patch/) by [Thom Lawrence](https://twitter.com/lemonwatcher)
*    [Pass Footedness in the Premier League](https://statsbomb.com/2019/04/pass-footedness-in-the-premier-league/) by [James Yorke](https://twitter.com/jair1970)
- [Messi Walks Better Than Most Players Run](https://fivethirtyeight.com/features/messi-walks-better-than-most-players-run/) by [Bobby Gardiner](https://twitter.com/BobbyGardiner)
*    [Game of Throw-Ins](https://www.americansocceranalysis.com/home/2018/11/27/game-of-throw-ins) by [Eliot McKinley](https://twitter.com/etmckinley)
*    [Expected Threat](https://karun.in/blog/expected-threat.html) by [Karun Singh](https://twitter.com/karun1710)
*    [Passing Out at the Back](https://www.statsperform.com/resource/passing-out-at-the-back/) by [Will Gürpinar-Morgan](https://twitter.com/WillTGM)
*    [The 10 Commandments of Football Analytics](https://theathletic.co.uk/1692489/2020/03/23/the-10-commandments-of-football-analytics/) by [Tom Worville](https://twitter.com/Worville)
*    [Breaking Down Set Pieces ...](https://statsbomb.com/2019/05/breaking-down-set-pieces-picks-packs-stacks-and-more/) by [Euan Dewar](https://twitter.com/EuanDewar)
*    [Data Based Coaching: ...](https://www.americansocceranalysis.com/home/2020/3/19/data-based-coaching-how-to-incorporate-data-driven-decisions-into-your-coaching-workflow) by [Kieran Doyle](https://twitter.com/KierDoyle)
*    [Coaches Reward Goalscorers ...](https://www.americansocceranalysis.com/home/2020/3/30/coaches-reward-goalscorers-they-shouldnt) by [McKinley](https://twitter.com/etmckinley) and [John Muller](https://twitter.com/johnspacemuller)

## Papers
*    [Dynamic Analysis of Team Strategy in Professional Footbal](https://static.capabiliaserver.com/frontend/clients/barca/wp_prod/wp-content/uploads/2020/01/56ce723e-barca-conference-paper-laurie-shaw.pdf) by [Laurie Shaw](https://twitter.com/EightyFivePoint) and [Mark Glickman](https://twitter.com/glicko);
*    [A	 Framework	 for	 Tactical	 Analysis	 and	...](http://nessis.org/nessis11/rudd.pdf) by [Sarah Rudd](https://twitter.com/srudd_ok). Accompanying NESSIS talk on Metacafe [[link](https://www.metacafe.com/watch/7337475/2011_nessis_talk_by_sarah_rudd/)];
*    [An Extension of the Pythagorean Expectation ...](https://www.soccermetrics.net/wp-content/uploads/2013/08/football-pythagorean-article.pdf) by [Howard Hamilton](https://twitter.com/soccermetrics);
*    [Large-Scale Analysis of Soccer Matches ...](https://s3-us-west-1.amazonaws.com/disneyresearch/wp-content/uploads/20141211131038/Large-Scale-Analysis-of-Soccer-Matches-using-Spatiotemporal-Tracking-Data-Paper.pdf) by Alina Bialkowski et. al;
*    [Spatio-Temporal Analysis of Team Sports – A Survey](https://arxiv.org/pdf/1602.06994.pdf) by Joachim Gudmundsson and Michael Horton;
*    [Physics-Based	Modeling	of	Pass	Probabilities	in	Soccer](http://www.sloansportsconference.com/wp-content/uploads/2017/02/1621.pdf) by [Will Spearman](https://twitter.com/the_spearman) et. al.;
*    [Data-Driven	Ghosting	using	Deep	Imitation	Learning](http://www.sloansportsconference.com/wp-content/uploads/2017/02/1671-2.pdf) by [Hoang	M. Le](https://twitter.com/HoangMinhLe),	Peter	Carr,	Yisong	Yue,	and	[Patrick	Lucey](https://twitter.com/patricklucey);
*    [Beyond Expected Goals](http://www.sloansportsconference.com/wp-content/uploads/2018/02/2002.pdf) by [Spearman](https://twitter.com/the_spearman);
*    [Not All Passes Are Created Equal: ...](https://dl.acm.org/doi/pdf/10.1145/3097983.3098051) by [Paul Power](https://twitter.com/counterattack9) et. al;
*    [Wide Open Spaces: ...](http://www.sloansportsconference.com/wp-content/uploads/2018/03/1003.pdf) by [Javier Fernandez](https://twitter.com/JaviOnData) and [Luke Bornn](https://twitter.com/LukeBornn);
*    [Decomposing	the	Immeasurable	Sport: ...](http://www.sloansportsconference.com/wp-content/uploads/2019/02/Decomposing-the-Immeasurable-Sport.pdf) by [Fernandez](https://twitter.com/JaviOnData), [Bornn](https://twitter.com/LukeBornn), and [Dan Cervone](https://twitter.com/dcervone0);
*    [Modelling the Collective Movement of Football Players](http://uu.diva-portal.org/smash/get/diva2:1365788/FULLTEXT01.pdf) by [Francisco José Peralta Alguacil](https://twitter.com/PeraltaFran23);
*    [Player Vectors: Characterizing Soccer Players’ Playing Style ...](https://tomdecroos.github.io/reports/ecml19_tomd.pdf) by [Tom Decroos](https://twitter.com/TomDecroos) and [Jesse Davis](https://twitter.com/jessejdavis1);
*    [Actions Speak Louder than Goals: ...](https://arxiv.org/pdf/1802.07127.pdf) by [Tom Decroos](https://twitter.com/TomDecroos), [Lotte Bransen](https://twitter.com/LotteBransen), [Jan Van Haaren](https://twitter.com/JanVanHaaren), and [Jesse Davis](https://twitter.com/jessejdavis1);
*    [Ready Player Run: Off-ball run identification and classification](https://static.capabiliaserver.com/frontend/clients/barca/wp_prod/wp-content/uploads/2020/01/40ba07f4-ready-player-run-barcelona.pdf) by [Sam Gregory](https://twitter.com/GregorydSam);
*    [SoccerMap: A Deep Learning Architecture for ...](https://arxiv.org/pdf/2010.10202.pdf) by [Javier Fernandez](https://twitter.com/JaviOnData) and [Luke Bornn](https://twitter.com/LukeBornn); and
*    [A new look into Off-ball Scoring Opportunity: ...](https://sportstomorrow.fcbarcelona.com/wp-content/uploads/2020/11/A_new_look_into_Off-ball_Scoring_Opportunity_taking_into_account_the_continuous_nature_of_the_game.pdf) by [Hugo M. R. Rios-Neto](https://twitter.com/hugoriosneto), Wagner Meira Jr., Pedro O. S. Vaz-de-Melo.

## Books
*    [Moneyball: The Art of Winning an Unfair Game](https://www.amazon.co.uk/Moneyball-Art-Winning-Unfair-Game/) by Michael Lewis
*    [The Numbers Game](https://www.amazon.co.uk/Numbers-Game-Everything-About-Football/) by [Chris Anderson](https://twitter.com/soccerquant) and [David Sally](https://twitter.com/DavidSally6)
*    [Football Hackers](https://www.amazon.co.uk/Football-Hackers-Science-Data-Revolution/) by [Christoph Biermann](https://twitter.com/chbiermann)
*    [Soccermatics](https://www.amazon.co.uk/Soccermatics-Mathematical-Adventures-Pro-Bloomsbury/dp/1472924142/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=&sr=) by [David Sumpter](https://twitter.com/Soccermatics)
*    [Soccernomics](https://www.amazon.co.uk/Soccernomics-England-Germany-France-Finally/) by Simon Kuper and [Stefan Szymanski](https://twitter.com/sszy)
*    [Mathletics: How Gamblers, Managers, and Sports Enthusiasts Use Mathematics in Baseball, Basketball, and Football](https://www.amazon.co.uk/Mathletics-Gamblers-Enthusiasts-Mathematics-Basketball/) by Wayne Winston
*    [Data Analytics in Football](https://www.amazon.co.uk/Data-Analytics-Football-Daniel-Memmert/) by [Daniel Memmert](https://twitter.com/DMemmert) and Dominik Raabe
*    [Sports Analytics: A Guide for Coaches, Managers, and Other Decision Makers](https://www.amazon.co.uk/Sports-Analytics-Coaches-Managers-Decision/) by [Ben Alamar](https://twitter.com/bencalamar)
*    [Outside the Box](https://www.amazon.co.uk/Outside-Box-Statistical-Journey-Football/) by [Duncan Alexander](https://twitter.com/oilysailor)
*    [Zonal Marking: The Making of Modern European Football](https://www.amazon.co.uk/Zonal-Marking-Making-European-Football/) by [Michael Cox](https://twitter.com/Zonal_Marking)
*    [The Mixer: The Story of Premier League Tactics, from Route One to False Nines](https://www.amazon.co.uk/Mixer-Story-Premier-League-Tactics/) by [Michael Cox](https://twitter.com/Zonal_Marking)
*    [Inverting the Pyramid](https://www.amazon.co.uk/Inverting-Pyramid-History-Football-Tactics/) by [Jonathan Wilson](https://twitter.com/jonawils)
*    [Sprawlball: A Visual Tour of the New Era of the NBA](https://www.amazon.co.uk/Sprawlball-Visual-Tour-New-Era/dp/1328767515/) by [Kirk Goldsberry](https://twitter.com/kirkgoldsberry)
*    [Numbers Don't Lie: New Adventures in Counting and What Counts in Basketball Analytics](https://www.amazon.co.uk/Numbers-Dont-Lie-Adventures-Basketball/) by Yago Colás

## Newsletters
*    [Grace on Football](https://onfootball.substack.com/) by [Grace Robertson](https://twitter.com/graceonfootball)
*    [space space space](https://spacespacespaceletter.com/author/johnmuller/) by [John Muller](https://twitter.com/johnspacemuller)
*    [Measureables](https://www.measurablespod.com/newsletter) by [Brendan Kent](https://twitter.com/brendankent)
*    [Stats Perform](https://www.statsperform.com/)

## Notable figures / Twitter Accounts
*    [2020 Analytics Twitter Top 1,000 Power Rankings](https://github.com/anenglishgoat/analyticsTwitterInteractions/blob/main/AnalyticsTwitterPageRank.csv), calculated by [Will Thomson](https://twitter.com/AnEnglishGoat)
*    [Football Analyst Community Rankings dashboard](https://public.tableau.com/profile/grecian#!/vizhome/FootballAnalystCommunityRankings/Dashboard1) by Neil Charles
*    [Football/soccer data analysts with publicly available work](https://docs.google.com/spreadsheets/d/1wjMVOpupmcF4hEG7PO4lY6l2mKsldGsnkyAULQwyAp8/edit?usp=sharing)

## Other resources lists
*    [Soccer Analytics Handbook](https://github.com/devinpleuler/analytics-handbook) by [Devin Pleuler](https://twitter.com/devinpleuler)
*    [Awesome Soccer Analytics]](https://github.com/matiasmascioto/awesome-soccer-analytics)

## Career Advice
*    [Getting into Sports Analytics](https://medium.com/@GregorydSam/getting-into-sports-analytics-ddf0e90c4cce) by Sam Gregory (@GregorydSam)
*    [Getting into Sports Analytics 2.0](https://medium.com/@GregorydSam/getting-into-sports-analytics-2-0-129dfb87f5be) by Sam Gregory (@GregorydSam)
*    [Best Football Analytics Pieces](https://medium.com/@GregorydSam/best-football-analytics-pieces-e532844b12e) by Sam Gregory (@GregorydSam)
*    [ow to become a football data scientist – Friends of Tracking](https://www.youtube.com/watch?v=9J8CwOtjOiw) with Pascal Bauer, Javier Fernández, Suds Gopaladesikan, Fran Peralta, and David Sumpter
*    [You Want to be a Performance Analyst?](https://thevideoanalyst.com/want-performance-analyst/) by The Video Analyst
*    [What do you need to learn to work in football analytics?](https://barcainnovationhub.com/what-do-you-need-to-learn-to-work-in-football-analytics/) by David Sumpter (@Soccermatics) for Barca Innovation Hub
*    [Careers in Sports Analytics](https://www.youtube.com/watch?v=0Y46KjeVsD0)

## Events and conferences
*    [OptaPro Analytics Forum](https://www.optasportspro.com/events/)
*    [StatsBomb Conference](https://statsbomb.com/conference/)
*    [BARÇA SPORTS ANALYTICS SUMMIT](https://barcainnovationhub.com/event/barca-sports-analytics-summit-2019/)
*    [MIT Sloan Sports Analytics Conference](http://www.sloansportsconference.com/)
*    [New England Symposium on Statistics in Sports (NESSIS](http://www.nessis.org/)
*    [Carnegie Mellon Sports Analytics Conference](http://www.cmusportsanalytics.com/conference2018.html)
*    [CASSIS](http://cascadiasports.com/)
*    [Tactical Insights 2020 Conference at King Power Stadium](https://www.lcfc.com/tacticalinsights)
*    [DFB Hackathon](https://www.dfb-akademie.de/hackathon-2-sts-akademie-eintracht/-/id-11009109)
*    [PSG Sports Analytics Challenge](https://www.agorize.com/fr/challenges/xpsg?lang=en)
*    [Football Data International Forum](https://eniit.es/football-data-international-forum/)
*    [Global Training Camp](http://gtc.analyticsinsport.com/)
*    [Great Lakes Analytics Conference](https://www.uwsp.edu/cols/Pages/GLAC/analyticsconference.aspx)
*    [MathSport International](http://www.mathsportinternational.com/
*    [Sports Analytics World Series](https://www.analyticsinsport.com/)
*    [Sportdata & Performance Forum](https://www.sportdataperformance.com/)
*    [Sports Technology Symposium](https://www.fcbarcelona.com/club/sports-technology-symposium)

## Jobs
*    [The Video Analyst](https://thevideoanalyst.com/jobs/)
*    [Opta](https://www.optasports.com/about/work-for-opta/)
*    [Stats Perform Job Opportunities](https://www.statsperform.com/stats-careers/) and [link](https://performacademy.csod.com/ux/ats/careersite/3/home?c=performacademy)
*    [Statsbomb](https://statsbomb.com/careers/)
*    [Wyscout](https://wyscout.com/careers/#job-openings) and careers@wyscout.com
*    [Hudl](https://www.hudl.com/jobs#jobs)
*    [Metrica Sports](https://apply.workable.com/metrica-sports/)
*    [Second Spectrum](https://www.secondspectrum.com/careers/opportunities.html)
*    [SciSports](https://www.scisports.com/jobs/)
*    [Football Radar](https://www.footballradar.com/careers/)
*    [Genius Sports](https://www.geniussports.com/careers) and [link](https://geniussports.gr8people.com/index.gp?method=cappportal.showPortalSearch&sysLayoutID=123)
*    [Gracenote](https://www.gracenote.com/company/careers/) and [link](https://careers.nielsen.com/en-us/?s=&post_type=openings&regions=na&locations=ca-emeryville&teams=&types=&schedules=&orderby=&order=&North+America=na&ame=&asia-pacific=&europe=&greater-china=&india=&latam=&na=ca-emeryville)
*    [Global Sports](https://www.globalsportsjobs.com/jobs)
*    [Smart Odds](https://www.smartodds.co.uk/Careers/Vacancies)
*    [FutbolJobs](https://futboljobs.com/en/search-football-jobs/)

## Miscellaneous
*    [Awesome Footbal](https://github.com/planetopendata/awesome-football): A collection of awesome football (national teams, clubs, match schedules, players, stadiums, etc.) datasets.
*    [Guide to Football/Soccer data and APIs](https://www.jokecamp.com/blog/guide-to-football-and-soccer-data-and-apis/)
*    [Association of Sports Analytics Professionals](https://www.sportsanalyticsprofessionals.com/)
*    [Expected Goal literature](https://docs.google.com/document/d/1OY0dxqXIBgncj0UDgb97zOtczC-b6JUknPFWgD77ng4/edit)
*    [FIFA EPTS (Electronic Performance and Tracking Systems)](https://football-technology.fifa.com/en/media-tiles/epts/)
*    [opensport (Google Group)](https://groups.google.com/forum/#!forum/opensport)
*    [Technical Report - 2018 FIFA World Cup](https://img.fifa.com/image/upload/evdvpfdkueqrdlbbrrus.pdf)
