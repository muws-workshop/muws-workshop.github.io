---
title: "Call for Papers"
---

Multimodal human understanding and analysis is an emerging research area that cuts through several disciplines like Computer Vision, Natural Language Processing (NLP), Speech Processing, Human-Computer Interaction, and Multimedia. Several multimodal learning techniques have recently shown the benefit of combining multiple modalities in image-text, audio-visual and video representation learning and various downstream multimodal tasks. At the core, these methods focus on modelling the modalities and their complex interactions by using large amounts of data, different loss functions and deep neural network architectures. However, for many Web and Social media applications, there is the need to model the human, including the understanding of human behaviour and perception. For this, it becomes important to consider interdisciplinary approaches, including social sciences, semiotics and psychology.

MUWS 2026 will gather novel, unpublished works in the context of representation learning for cross-cultural, human-created multimodal data. We especially look forward to the applicability of interdisciplinary ideas and theories, from semiotics over gestalt theory to multimodal computational research in fields like vision & language, information retrieval, human-computer interaction, explainable AI. 

Our workshop will equally consider both novel scientific methods and techniques for analysis, extraction and enrichment of multimodal data as well as application perspectives, such as the innovative use of tools and methods for providing rich interaction with multimodal data. We will organize the workshop under two sub-tracks:

### Track 1: Human-Centred Multimodal Understanding

This track aims to attract researchers working from various disciplines~(computer science, digital humanities, semiotics, etc.) in multimodal understanding with a focus on human-centred aspects. We will seek for original, both application-oriented and theoretical papers, and position papers that bridge both text and multimedia data. This track will cover novel research including, but not limited to, the following topics of interest:

- Multimodal modelling of human impressions and emotions in the context of the Web and social media
- Incorporating multi-disciplinary theories such as semiotics or Gestalt-theory into multimodal approaches and analyses
- Human-centred aspects in vision-language models
- Measuring and analysing cultural, social and multilingual biases in the context of the Web and social media
- Cross-modal and semantic relations in multimodal web data
- Multimodal human perception understanding
- Multimodal sentiment/emotion/sarcasm recognition
- Multimodal hate speech detection
- Multimodal misinformation detection
- Multimodal content understanding and analysis
- Multimodal rhetoric in online media


### Track 2: Multimodal Understanding Through Impactful World Events

The goal of this track is to bring together multimodal researchers from various fields to analyse joint, impactful research questions. For this purpose, we have introduced a collection of *news and social media data with both image and text* related to impactful world events. We have further extended the dataset for MUWS 2026 regarding two main aspects: (1) adding articles from recent events in 2025 and 2026 (e.g., protests against ICE, US tariffs, Iranian protests), and (2) including Portuguese resources (e.g., from Brazil, Portugal, etc.) to not only promote engagement with the local research community, making the track more relevant to Brazilian and Portuguese-speaking researchers, but also be aligned with broader movements in AI research toward multilingual and multicultural approaches.

Consequently, the dataset covers content published in different regions of the world, enabling various tasks, e.g., analysing how the same event is portrayed in countries with different cultural, economic, and regional background. To foster research, we will provide research questions including, but not limited to:
 

- **News Values:** How can news values such as the sentiment, superlativeness, or geographical, cultural, and domain (topic) proximity affect the human perception of an event?
- **Multimodal Cultural Bias:** How are world-wide events perceived across different cultures or languages?
- **Framing of Elites:** How do multimodal framing techniques employed by news outlets differ in their portrayal of elite figures, e.g., politicians during major electoral events? 
- **Sentiment across Cultures:** How does the sentiment expressed in news articles and social media posts, throughout textual and visual vary across different countries covering the same event?
- **Societal Impact:** How do world-wide events affect masses with regards to potential perceived consequences, and what is the role of each data modality on that perception?

The goal for participants is to develop novel research ideas based on the dataset but without requiring them to compete against each other. Each submitted work is expected to target some of the research questions while studying the unique aspect of the problem.

#### Dataset 1: Tweets posted by news companies around the world about Ukraine-Russia Conflict.

The dataset includes 1,524,826 tweets for 60 languages. 306,295 tweets include images and thus the `image_tags` is populated with the classified concepts, and it is an empty list in case the tweet does not include an image.

Each entry in the dataset is a single JSON line and has the following entries:

```
{
	'tweet_id': 
	'lang':
	'stanza_output':
	'stanza_named_entities':
	'sentiment':
	'stance':
	'channel':
	'country': 
	'verified':
	'image_tags':
}
```

Plus the typical entries that exist in a tweet: full body text, media URLs etc.


#### Dataset 2:  News bias categories `left`, `right`, `center` for main stream events

The dataset includes info where each line refers to a specific event. For each event, we then extracted the bias categories `left`, `right`, `center` and the corresponding news articles (their links). The articles are published between January 2025 - May 2026.

We also provide the individual article text and images from certain providers (AP News, BBC, CNN, Fox Business, Fox News, NBC News, Newsweek, New York Post, The New York Times, Politico, Reuters, The Guardian, The Hill, Washington Examiner, The Washington Post) that can be made available to work on. We have total 1919 stories and there are three articles for each story (one for each stance).


Each entry in the dataset is a single JSON line and has the following entries:

```
{
	'date':
	'headline':
	'headline_link':
	'topic':
	'topic_link':
	'tags':
	'summary':
	'left': {
		'source':
		'headline': 
		'link': 
		'rating_img': 
		'rating': 
		'summary': 
		'image_link': 
		'news_type': 
	}
	'right': { ... same structure as above ... }
	'center': { ... same structure as above ... }
	'more_left': [
		{
			'source':
			'headline': 
			'link': 
			'rating_img': 
			'rating': 
			'summary': 
			'all_sides_link': 
			'news_type': 
		},
		{ ... same structure as above ... }
	]
	'more_right': [ ... same structure as above ...]
	'more_center': [ ... same structure as above ...]
}
```

For each `headline` there is a left, right or center-oriented news article. We also have additional list of articles that also have the same bias categories under `more_left`, `more_right`, `more_center`.



#### Participation and accessing the datasets in Track 2
Please fill out this form with the required details (fullname, email etc.) and we will send the password protected link to your indicated email address.: [https://forms.gle/tLJEZfJsnYhW5dYg8](https://forms.gle/tLJEZfJsnYhW5dYg8)


## Important Dates (Anywhere on Earth)

- Submission deadline: July 16th, 2026
- Paper notification: August 6th, 2026
- Camera ready: August 20th, 2026
- Author registration: August 20th, 2026
- Workshop date: TBA

## Submission Page

- Submission Page: [via Open Review](https://openreview.net/group?id=acmmm.org/ACMMM/2026/Workshop/MUWS)

## Contact

If you have any problems or questions, please contact us via e-mail at: [muws-workshop@listserv.dfn.de](mailto:muws-workshop@listserv.dfn.de)
