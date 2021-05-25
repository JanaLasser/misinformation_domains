# A collection of domains that spread unreliable information

**Author: Jana Lasser, Graz University of Technology (jana.lasser@tugraz.at)**

The collection is based on a list initially compiled by [Galotti et al. 2020](https://www.nature.com/articles/s41562-020-00994-6#Sec4) and was since expanded with updated versions of the initial domain collections and extended by additional curated lists. A cleaned and de-duplicated list ist stored under ```data/clean```.

## A word of caution
The final version of the cleaned and de-duplicated list depends on somewhat arbitrary decisions on what to classify as "harmful" content. The cleaning and de-duplication process is performed in the script ```clean_misinformation_domains.ipynb```. Before using or building on this list, please have a look at the cleaning and de-duplication process and evaluate, if it fits your definition of "disinformation", "misinformation" or "fake news" and adapt accordingly!  

Also: since many of these sources have not been updated in quite a while, a large share of the domains in this list do not exist anymore. A quick spot-check of domains on May 24th 2021, checking which domains were mentioned in Tweets in the time span between April 24th and May 24th 2021 at least 10 times revealed that only about 30% of the domains classified as "disinformation" in the list were active at this point in time. 

## Sources
The lists that are ingested and combined into a larger list below stem from several sources. Some of them fact-checking collectives, some of them individual scholars or journalists that collected and curated lists of domains that spread unreliable information. Snapshots of the lists that were taken on May 18th 2021 are stored under ```data/raw```. The table below lists the individual collections included in this meta-list:

| Author | Article | List source | Included | Lat update | Note |
| ------ | ------- | ----------- | -------- | ---------- | ---- |
| Melissa Zimdars | https://www.washingtonpost.com/posteverything/wp/2016/11/18/my-fake-news-list-went-viral-but-made-up-stories-are-only-part-of-the-problem/ | https://docs.google.com/document/d/10eA5-mCZLSS4MQY5QGb5ewC3VAL6pLkT53V_81ZyitM/preview | yes | 2016 | It is a bit unclear when this list was last updated |
Buzzfeed | https://www.buzzfeednews.com/article/craigsilverman/inside-the-partisan-fight-for-your-news-feed | https://github.com/BuzzFeedNews/2017-08-partisan-sites-and-facebook-pages/tree/master/data | yes | 2018-08-08 | |
Fake news watch | https://web.archive.org/web/20180213181029/http://www.fakenewswatch.com/ | https://web.archive.org/web/20180213181029/http://www.fakenewswatch.com/ | yes | 2016-01-18 | | 
Politifact | https://www.politifact.com/article/2017/apr/20/politifacts-guide-fake-news-websites-and-what-they/ | https://e.infogr.am/politifacts_fake_news_almanac?parent_url=https%3A%2F%2Fwww.politifact.com%2Farticle%2F2017%2Fapr%2F20%2Fpolitifacts-guide-fake-news-websites-and-what-they%2F&src=embed# | yes | 2017-11-09 | |
Fletcher et al. | https://reutersinstitute.politics.ox.ac.uk/our-research/measuring-reach-fake-news-and-online-disinformation-europe | Is a compilation of individual smaller lists (Butac, Bufale, Bufalopedia and Décodex) in itself | see below | see below | several smaller lists, mainly focused on Italian and French misinformation spreading domains |
Butac | https://reutersinstitute.politics.ox.ac.uk/our-research/measuring-reach-fake-news-and-online-disinformation-europ | https://www.butac.it/the-black-list/ | yes | 2021-05-18 | Mostly italian sites, domain names cleaned and expanded manually, facebook pages excluded |
Bufale | https://reutersinstitute.politics.ox.ac.uk/our-research/measuring-reach-fake-news-and-online-disinformation-europ | https://www.bufale.net/the-black-list-la-lista-nera-del-web/ | yes | 2018 | labels translated to English by italian native speaker | 
Bufalopedia | https://reutersinstitute.politics.ox.ac.uk/our-research/measuring-reach-fake-news-and-online-disinformation-europ | https://bufalopedia.blogspot.com/p/siti-creatori-di-bufale.html | yes | 2020-05-05 | Mostly Italian sites, some international, changed label of “the onion” from fake news to satire. “Fake news” label reflects international sites |
Décodex | https://reutersinstitute.politics.ox.ac.uk/our-research/measuring-reach-fake-news-and-online-disinformation-europ | https://www.lemonde.fr/verification/ | no | unknown | French fact checking service from le Monde, no access established yet |
Girnberg et al. | https://science.sciencemag.org/content/363/6425/374.abstract | https://github.com/LazerLab/twitter-fake-news-replication/blob/master/domains/domain_coding/data/black_sites.txt | yes | 2019-01-28 | | 
Media bias fact check | https://mediabiasfactcheck.com/ | Various sub-sites with link lists | yes | 2021-05-21 | domains are labelled by the sub-site they appear on |
Snopes’ field guide to fake news sites | | https://www.snopes.com/news/2016/01/14/fake-news-sites/ | see below | 2016-01-14 | one of the sources of the CJR list |
FakeNewsCodes | | http://www.fakenewscodex.com/ | see below | 2018-12-05 | one of the sources of the CJR list |
FactCheck.org | | https://www.factcheck.org/2017/07/websites-post-fake-satirical-stories/ | see below | 2018-11-02 | one of the sources of the CJR list |
Columbia Journalism review | https://www.cjr.org/fake-beta | https://www.cjr.org/fake-beta and more detailed data at https://docs.google.com/spreadsheets/d/1ck1_FZC-97uDLIlvRJDTrGqBk0FuDe9yHkluROgpGS8/edit#gid=2037798083 | yes | 2021-04 | Up-to-date compilation of lists from FactCheck.org, FakeNewsCodex, OpenSources, PolitiFact and Snopes. Entries with more than one label were expanded into several rows |
