In this work, we focus on the political discourse on Reddit and YouTube. In contrast with Twitter, both Reddit and YouTube put a character limit of 10,000 characters for individual posts or comments allowing room for nuanced political discourse.

For YouTube, we consider a dataset of 60,000 user comments equally sampled from news videos hosted on the official YouTube channels of three major cable news outlets in the US: CNN, Fox News, and MSNBC (SI contains further details). We select this dataset because of the broad participation, topical diversity, and political relevance [Stanley, 2012; Bozell, 2004; Gil de Zúñiga, Correa, and Valenzuela, 2012; Hyun and Moon, 2016; Dutta et al., 2022; KhudaBukhsh et al., 2022; Ding, Horning, and Rho, 2023]. This dataset is considered a comprehensive snapshot of US political discourse [KhudaBukhsh et al., 2021] and has been used for in-the-wild audits of content moderation systems [Weerasooriya et al., 2023a] and misinformation datasets [Yoo and KhudaBukhsh, 2023]. In addition, to check for algorithmic chokehold, we create another separate dataset using comments from these three major cable networks concerning LGBTQ+ individuals. This dataset consists of 1,651 total comments for 2019 and 2024 with token-length exceeding 501.

To further support our hypothesis, we created two Reddit datasets dealing with 1) politics and 2) algorithmic chokehold. We used Arctic Shift Reddit API for the data collection. These datasets, which we collected from subreddits `r/Republican`, `r/Democrats`, `r/USPolitics` for political views, and `r/BlackPeopleTwitter`, are significant in their extensive scope and depth. They include titles, descriptions, and a substantial 454,449 comments across the subreddits for the years 2019 and 2024. For the experiments in this paper, we consider comments from subreddits `r/Republican`, `r/Democrats`, and `r/BlackPeopleTwitter` for the years 2019 and 2024. The dataset description is provided in Table 1.

### Reddit Dataset Summary

> **Table 1: The number of comments with more than 50 tokens in each subreddit for the years 2019 and 2024**

| Subreddit           | `r/Republican` | `r/Democrats` | `r/BlackPeopleTwitter` |
|---------------------|----------------|---------------|------------------------|
| 2019                | 16,325         | 17,747        | 289,242                |
| 2024                | 8,729          | 12,000        | 110,406                |

