# A collection of domains that spread unreliable information

**Authors: Jana Lasser, Graz University of Technology (jana.lasser@tugraz.at), Valentin Rupp**  
**Contact:** If you are aware of additional lists that are not part of this collection yet, especially in other languages than English, please let us know. If you have questions regarding individual domains, please contact the authors of the list that includes that domain.

## Sources
The collection started with a list of sources referenced by [Galotti et al. 2020](https://www.nature.com/articles/s41562-020-00994-6#Sec4) and was since expanded with updated versions of the initial domain collections and extended by additional curated lists. A cleaned and de-duplicated list ist stored under ```data/clean```.

The lists that are ingested and combined into a larger list below stem from several sources. Some of them fact-checking collectives, some of them individual scholars or journalists that collected and curated lists of domains that spread unreliable information. Snapshots of the lists that were taken on May 18th 2021 are stored under ```data/raw```. The table below lists the individual collections included in this meta-list:

| Author | Article | List source | Included | Last update | Note | License |
| ------ | ------- | ----------- | -------- | ---------- | ---- | ------- |
| Melissa Zimdars | https://www.washingtonpost.com/posteverything/wp/2016/11/18/my-fake-news-list-went-viral-but-made-up-stories-are-only-part-of-the-problem/ | https://docs.google.com/document/d/10eA5-mCZLSS4MQY5QGb5ewC3VAL6pLkT53V_81ZyitM/preview | yes | 2016 | It is a bit unclear when this list was last updated | [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
Buzzfeed | https://www.buzzfeednews.com/article/craigsilverman/inside-the-partisan-fight-for-your-news-feed | https://github.com/BuzzFeedNews/2017-08-partisan-sites-and-facebook-pages/tree/master/data | yes | 2018-08-08 | | none specified |
Fake news watch | https://web.archive.org/web/20180213181029/http://www.fakenewswatch.com/ | https://web.archive.org/web/20180213181029/http://www.fakenewswatch.com/ | yes | 2016-01-18 | | none specified |
Politifact | https://www.politifact.com/article/2017/apr/20/politifacts-guide-fake-news-websites-and-what-they/ | https://e.infogr.am/politifacts_fake_news_almanac?parent_url=https%3A%2F%2Fwww.politifact.com%2Farticle%2F2017%2Fapr%2F20%2Fpolitifacts-guide-fake-news-websites-and-what-they%2F&src=embed# | yes | 2017-11-09 | | none specified |
Fletcher et al. | https://reutersinstitute.politics.ox.ac.uk/our-research/measuring-reach-fake-news-and-online-disinformation-europe | Is a compilation of individual smaller lists (Butac, Bufale, Bufalopedia and Décodex) in itself | see below | see below | several smaller lists, mainly focused on Italian and French misinformation spreading domains | see below |
Butac | https://reutersinstitute.politics.ox.ac.uk/our-research/measuring-reach-fake-news-and-online-disinformation-europ | https://www.butac.it/the-black-list/ | yes | 2021-05-18 | Mostly italian sites, domain names cleaned and expanded manually, facebook pages excluded | none specified |
Bufale | https://reutersinstitute.politics.ox.ac.uk/our-research/measuring-reach-fake-news-and-online-disinformation-europ | https://www.bufale.net/the-black-list-la-lista-nera-del-web/ | yes | 2018 | labels translated to English by italian native speaker | none specified |
Bufalopedia | https://reutersinstitute.politics.ox.ac.uk/our-research/measuring-reach-fake-news-and-online-disinformation-europ | https://bufalopedia.blogspot.com/p/siti-creatori-di-bufale.html | yes | 2020-05-05 | Mostly Italian sites, some international, changed label of “the onion” from fake news to satire. “Fake news” label reflects international sites | none specified |
Décodex | https://reutersinstitute.politics.ox.ac.uk/our-research/measuring-reach-fake-news-and-online-disinformation-europ | https://www.lemonde.fr/verification/ | no | unknown | French fact checking service from le Monde, no access established yet | |
Girnberg et al. | https://science.sciencemag.org/content/363/6425/374.abstract | https://github.com/LazerLab/twitter-fake-news-replication/blob/master/domains/domain_coding/data/black_sites.txt | yes | 2019-01-28 | | none specified |
Media bias fact check | https://mediabiasfactcheck.com/ | Various sub-sites with link lists | yes | 2021-05-21 | domains are labelled by the sub-site they appear on | none specified |
Snopes’ field guide to fake news sites | | https://www.snopes.com/news/2016/01/14/fake-news-sites/ | see below | 2016-01-14 | one of the sources of the CJR list | see below |
FakeNewsCodes | | http://www.fakenewscodex.com/ | see below | 2018-12-05 | one of the sources of the CJR list | see below |
FactCheck.org | | https://www.factcheck.org/2017/07/websites-post-fake-satirical-stories/ | see below | 2018-11-02 | one of the sources of the CJR list | see below |
Columbia Journalism review | https://www.cjr.org/fake-beta | https://www.cjr.org/fake-beta and more detailed data at https://docs.google.com/spreadsheets/d/1ck1_FZC-97uDLIlvRJDTrGqBk0FuDe9yHkluROgpGS8/edit#gid=2037798083 | yes | 2021-04 | Up-to-date compilation of lists from FactCheck.org, FakeNewsCodex, OpenSources, PolitiFact and Snopes. Entries with more than one label were expanded into several rows | none specified |

## Unification of labels
Below we provide tables listing the mapping of the individual site's labels and label descriptions to an accuracy (A) and transparency (T) scale. The mappings are also available in the file `data/resources/labels.csv`.

### Bufalopedia
| Label | Description | A | T |
| ----- | ----------- | - | - |  
| misleading  |  - | 2 | 1 |  
| satire | Sites/accounts that are fairly clearly recognizable as satire or parody, but still occasionally claim victims | 1 | 2 |  
| fake news | It is also to be considered suspicious, and at high risk of hoax, any news coming from names like these | 1 | 1 |     

### Bufale
| Label | Description | A | T |
| ----- | ----------- | - | - |
| false satire | Some of them have been around for quite some time, but in 2015 there has been a considerable increase in ‘fake newspapers’, or rather those domains that have misled many users because of their names that are easily confused with the most famous newspapers. Many of these claim to be ‘satirical’ even if, in some cases, they have nothing to do with ‘satire’. Many of these sites, however, have not been updated for some time, due to the fact that today, most users have learned to recognize ‘fake newspapers’. | 1 | 1 |  
| hoaxes and medical and scientific disinformation | - | 1 | 1 |  
| political disinformation | - | 1 | 1 |  
| religious and racially motivated disinformation | - | 1 | 1 |  
| scandalous hoaxes | - | 1 | 1 |  
| political and racial hoax | - | 1 | 1 |  
| clickbait | News aggregators, copy pasters, with no fact
checking and catchy headlines to attract the reader. | 2 | 2 |  
| websites of conspiracy theorists and hoax spreaders | New World Order, chemtrails, aliens, 9/11... you name it. | 1 | 1 |  
| social media sites of conspiracy theorists and hoax spreaders | - | 1 | 1 |  

### Butac
| Label | Description | A | T |
| ----- | ----------- | - | - |
| close to Qanon | The sites (Italian and not) close to the disinformation of QAnon. | 1 | 1 |
| pseudoscience | Sites that propose experiments, inventions, treatments that have no scientific merit or insufficient evidence. | 1 | 1 |
| pseudojournalism and politics | In this black list there are sites that use the language of journalism to write articles often based on nothing that bring water to their mill, whatever it is. It can be about politics, religion, ideals. They are sites that hurt, because many of those who read them are there because they are like-minded, and they can’t distinguish
between real news and news fueled only by cheering for this or that faction, or they copy news from unreliable sources without doing any verification. |1  | 1 |
| pseudojournalism blogs | - | 1 | 1 |
| pseudoscience blogs | - | 1 | 1 |
| pseudomedicine | Actually this black list should be much longer, but almost always the other sites that publish news of pseudo medicine have as source one of the following pages. These are dangerous pages, because they peddle cures that have no foundation, often recommending books and treatments - for a fee - sold and written by the same people who invented these miraculous cures. | 1 | 1 |
| conspiracy | The pages in this black list believe in one or another conspiracy theory, assuming that what mainstream information says is false. I have not yet understood if the minds behind these pages are ‘accomplices’ of those who invented these theories for profit or if they are just other ‘cheated’. | 1 | 1 |
| conspiracy blogs | - | 1 | 1 |

### Buzzfeed News
| Label | Description | A | T |
| ----- | ----------- | - | - |
| left bias | - | 3 | 2 |   
| right bias | - | 3 | 2 |   

### Columbia Journalism Review
| Label | Description | A | T |
| ----- | ----------- | - | - |
| bias | - | 3 | 2 |   
| unreliable | - | 2 | 1 |   
| fake | - | 1 | 1 |   
| conspiracy | - | 1 | 1 |   
| satire | - | 1 | 2 |   
| clickbait | - | 2 | 2 |   

### Fake News Watch
| Label | Description | A | T |
| ----- | ----------- | - | - |
| fake/hoax | Fake/Hoax News sites are satire sites that are not funny. They are an attempt to play on gullible people who do not check sources and will just pass the news on as if it were really true. | 1 | 1 | 
| satire | Satire websites are sites that make fun of the news. The stories are typically over the top and meant to be funny. | 1 | 2 | 
| clickbait | Clickbait websites are sites that take bits of true stories but insinuate and make up other details to sew fear. Most of these are conspiratorial in nature are very unreliable. | 2 | 2 | 

### Media Bias Fact Check
| Label | Description | A | T |
| ----- | ----------- | - | - |
| questionable sources | A questionable source exhibits one or more of the following: extreme bias, consistent promotion of propaganda/conspiracies, poor or no sourcing to credible information, a complete lack of transparency and/or is fake news. Fake News is the deliberate attempt to
publish hoaxes and/or disinformation for the purpose of profit or influence. Sources listed in the Questionable Category may be very untrustworthy and should be fact checked on a per article basis. Please note sources on this list are not considered fake news unless specifically written in the reasoning section for that source. | 1 | 1 |   
| conspiracy / pseudoscience | Sources in the Conspiracy-Pseudoscience category may publish unverifiable information that is not always supported by evidence. These sources may be untrustworthy for credible/verifiable information, therefore fact checking and further investigation is recommended on a per article basis when obtaining information from
these sources. | 1 | 1 |   
| right bias | These media sources are moderately to strongly biased toward conservative causes through story selection and/or political affiliation. They may utilize strong loaded words (wording that attempts to influence an
audience by using appeal to emotion or stereotypes), publish misleading reports and omit reporting of information that may damage conservative causes. Some sources in this category may be untrustworthy. | 3 | 2 |   
| center right bias | These media sources are slightly to moderately conservative in bias. They often publish factual information that utilizes loaded words (wording that attempts to influence an audience by using appeal to emotion or stereotypes) to favor conservative causes. These sources are generally trustworthy for information, but may require further investigation. | 4 | 3 |   
| left center bias | These media sources have a slight to moderate liberal bias. They often publish factual information that utilizes loaded words (wording that attempts to influence an audience by using appeal to emotion or stereotypes) to favor liberal causes. These sources are generally trustworthy for information, but may require further investigation. | 4 | 3 |   
| left bias | These media sources are moderately to strongly biased toward liberal causes through story selection and/or political affiliation. They may utilize strong loaded words (wording that attempts to influence an audience by using appeal to emotion or stereotypes), publish misleading reports and omit reporting of information that may damage liberal causes. Some sources in this category may be untrustworthy. | 3 | 2 |   
| least biased | These sources have minimal bias and use very few loaded words (wording that attempts to influence an audience by using appeal to emotion or stereotypes). The reporting is factual and usually sourced. These are the most credible media sources. | 5 | 3 |   
| satire | These sources exclusively use humor, irony, exaggeration, or ridicule to expose and criticize people’s stupidity or vices, particularly in the context of contemporary politics and other topical issues. Primarily these sources are clear that they are satire and do not attempt to deceive. | 1 | 2 |   
| pro science | These sources consist of legitimate science or are evidence based through the use of credible scientific sourcing. Legitimate science follows the scientific method, is unbiased and does not use emotional words. These sources also respect the consensus of experts in the given scientific field and strive to publish peer reviewed science. Some sources in this category may have a slight political bias, but adhere to scientific principles. | 5 | 3 |   

### Melissa Zimdars – Washington Post
| Label | Description | A | T |
| ----- | ----------- | - | - |
| bias | Sources that come from a particular point of view and may rely on propaganda, decontextualized information, and opinions distorted as facts. | 3 | 2 | 
| fake | Sources that entirely fabricate information, disseminate deceptive content, or grossly distort actual news reports. | 1 | 1 | 
| conspiracy | Sources that are well-known promoters of kooky conspiracy theories. Ex: 9/11 conspiracies, chem-trails, lizard people in the sewer systems, birther rumors, flat earth ‘theory’, fluoride as mind control, vaccines as mind control etc. | 1 | 1 | 
| unreliable | Sources that may be reliable but whose contents require further verification or to be read in conjunction with other sources. | 2 | 1 | 
| satire | Sources that use humor, irony, exaggeration, ridicule, and false information to comment on current events. | 1 | 2 | 
| hate | Sources that actively promote racism, misogyny, homophobia, and other forms of discrimination. | - | - | 
| clickbait | Sources that provide generally credible content, but use exaggerated, misleading, OR questionable headlines, social media descriptions, and/or images. These sources may also use sensational language to generate interest, clickthroughs, and shares, but their content is typically verifiable. | 2 | 2 | 
| political | Sources that provide generally verifiable information in support of certain points of view or political orientations. | 3 | 2 | 
| junksci | Sources that promote pseudoscience, metaphysics, naturalistic fallacies, and other scientifically dubious claims. | 1 | 1 | 
| rumor | Sources that traffic in rumors, gossip, innuendo, and unverified claims. | 2 | 2 | 
| unknown | Sources that have not yet been analyzed (many of these were suggested by readers/users or are found on other lists and resources). | - | - | 
| reliable | Sources that circulate news and information in a manner consistent with traditional and ethical practices in journalism (Remember: even credible sources sometimes rely on clickbait-style headlines or occasionally make mistakes. No news organization is perfect, which is why a healthy news diet consists of multiple sources of information). | 5 | 3 | 
| state | Sources in repressive states operating under government sanction. | 3 | 2 | 

### Politifact
| Label | Description | A | T |
| ----- | ----------- | - | - |
| Imposter site | Adding to the fog of fake news online, several websites appear to try to confuse readers into thinking they are the online outlets of traditional or mainstream media sources. These sites attempt to trick readers into thinking they are newspapers or radio or television stations. Like many other fake news sites, it’s very difficult to see who owns them, thanks to private registrations. | 1 | 1 |  
| Fake news | There’s little consistency of content or style among fake news sites – the common thread appears to be that they distribute fabricated content, but the reasons aren’t always apparent. | 1 | 1 |  
| Parody site | It can be difficult to parse what the aims of these parody sites may be. They could be writing stories purely for entertainment, or they may be trolling a particular set of voters. These websites may or may not make it clear on individual links that their stories are fake, but will almost always say in a disclaimer somewhere on their site that their content is exaggerated or fictional. | 1 | 2 |  
| Some fake stories | We have checked statements from sites that appear to carry real content, but contained one or more fake news stories. We don’t know whether this is intentional or accidental, but it happens. | 2 | 1 |  

## Usage & license
This compilation is a collection of a number of smaller lists. Only Melissa Zimdar's list explicitely states a license and usage requirements, all other lists do not. The source table above lists license availability for each of the sources individually as well. As we are not the owners of these lists, we cannot give them licenses. As far as our own work in compiling and cleaning these lists is concerned, we assign a [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.en) license.