+++
title = "Retweet Us, We Will Retweet You: Spotting Collusive Retweeters Involved in Blackmarket Services"
date = 2018-06-22T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Hridoy Sankar Dutta", "**Aditya Chetan**", "Brihi Joshi", "Tanmoy Chakraborty"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In *IEEE/ACM International Conference on Social Networks Analysis and Mining (ASONAM)*."
publication_short = "In *ASONAM*"

# Abstract and optional shortened version.
abstract = "Twitter has increasingly become a popular platform to share news and user opinion. A tweet is considered to be impor- tant if it receives high number of affirmative reactions from other Twitter users via Retweets. Retweet count is thus considered as a surrogate measure for positive crowd-sourced reactions – high number of retweets of a tweet not only help the tweet being broadcasted, but also aid in making its topic trending. This in turn bolsters the social reputation of the author of the tweet. Since social reputation/impact of users/tweets influences many decisions (such as promoting brands, advertisement etc.), several blackmarket syndicates have actively been engaged in producing fake retweets in a collusive manner. Users who want to boost the impact of their tweets approach the blackmarket services, and gain retweets for their own tweets by retweeting other customers’ tweets. Thus they become customers of blackmarket syndicates and engage in fake activities. Interestingly, these customers are neither bots, nor even fake users – they are usually normal human beings; they express a mix of organic and inorganic retweeting activities, and there is no synchronicity across their behaviors. \nIn this paper, we make a first attempt to investigate such blackmarket customers engaged in producing fake retweets. We collected and annotated a novel dataset comprising of customers of many blackmarket services and characterize them using a set of 64 novel features. We show how their social behavior differs from genuine users. We then use state-of-the-art supervised models to detect three types of customers (bots, promotional, normal) and genuine users. We achieve a Macro F1-score of ```0.87``` with __SVM__, outperforming four other baselines significantly. We further design a browser extension, ___SCoRe___ which, given the link of a tweet, spots its fake retweeters in real-time. We also collected users’ feedback on the performance of ___SCoRe___ and obtained ```85%``` accuracy."
abstract_short = "A novel collection of 64 features is presented that allows us to detect participants of blackmarket services in a more accurate manner than the existing state-of-the-art methods used for detecting fake accounts and bots on Twitter. This paper, to the best of our knowledge, is the first attempt to classify participants of collusive retweeting activities on Twitter and highlight how they differ from genuine users and bots."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["example-external-project"]
# tags = ["OSNs", "machine learning", "Data Science"]
# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/1806.08979"
url_code = "https://github.com/LCS2-IIITD/collusive-retweeters-ASONAM-2018"
url_dataset = "https://github.com/LCS2-IIITD/collusive-retweeters-ASONAM-2018/tree/master/data"
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "osnbg.png"
caption = "Image taken from: https://dhs.stanford.edu/gephi-workshop/twitter-network-gallery/"

+++

