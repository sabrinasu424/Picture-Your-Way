# Picture-Your-Way
#### Meng-Tien Tsai, Jia-yu Chang, Sabrina Yihua Su, Meng-Yun Duh, Yu-Ting Wang, Chien-Hung Shih
#### Building a picture based attraction recommendation system by combing LDA and K-Means in the structure of Scatter/Gather
[Webpage](http://35.201.182.2/main/index_b.php)|[3-minute demo/introduction](https://www.youtube.com/watch?v=Hjomt424dHA&feature=youtu.be)
### Abstract
The main purpose of this Picture Your Way is to build a picture-based attraction recommendation system. The proposed algorithm combines Latent Dirichlet Allocation (LDA) and K-Means in the structure of Scatter/Gather. Through this system, thousands of tourist attractions in Taiwan are recommended to users via a direct and prompt process, selecting pictures.
We leveraged the information of attractions listed in the governement open tourist attraction data and selected corresponding pictures from Instagram. The pictures ranked by Elo Rating System is moderately correlated to the realistic public preferences. The accuracy of LDA topics is 66%. The precision value for this proposed algorithm is 74%. And the system effectiveness calculated through the feedback of users is PR 72. Therefore, this system is proven to succeed in recommending suitable and beautiful attractions in Taiwan to users by using the proposed algorithm in this study.
* Data Resource: [Taiwan Open Government Data - Tourist Attraction Database](https://data.gov.tw/dataset/7777) (under the [Open Government Data License ](https://data.gov.tw/license#eng)), [Instagram](https://www.instagram.com/).
* Methods: Latent Dirichlet Allocation (LDA) Topic Modeling, K-means Clustering Algorithm, Elo Rating Algorithm, Natural Language Processing (NLP), PHP Web Development.
* Experimental Design: Spearman Correlation, Confussion Matrix (F-measure).
### Features
* Instant Demonstration: Distinguish attraction type through browsing pictures without reading long discriptions.
* Convenience: Reduce massive search time for users.
* Accuracy: Achieve optimal clustering and recommendation through machine learning algorithm training and careful evaluation.
* Aesthetic: Weight used pictures from the rankings aligned with public preferences to better meet user's need.
### Core Methods
* [Scatter/Gather](https://sigir.org/wp-content/uploads/2017/06/p148.pdf): A document clustering algorithm used to cluster massive documents within a short period of time, which allowed us to provide the optimal tourist attractions to users effectively.
* [LDA Topic Modeling](https://web.archive.org/web/20120207011313/http://jmlr.csail.mit.edu/papers/volume3/blei03a/blei03a.pdf): A machine learning algorithm used to extract latent topics from text data, which was leveraged in our first "Scatter" in the Scatter/Gather structure. (Unlike TF-IDF, LDA considers the term distributions in addition to term frequencies).
* [K-means Clustering](https://projecteuclid.org/download/pdf_1/euclid.bsmsp/1200512992): A unsupervised learning algorithm that provides instant clustering in this system. Under evaluation, it was proven feasible to extract the topic distribution from LDA for each tourist spot as the attributes in euclidean distance calcuation in K-means. This replaces the tradition sparse term-document matrix and reduces the time and space cost.
* [Elo Rating System](https://en.wikipedia.org/wiki/Elo_rating_system): A picture ranking algorithm inspired by the film, The Social Network (2010). Considering aesthetic as an important factor in picture selection, we trained the pictures using elo-rating algorithm to assign rankings and integrate in our system as the one of the demonstration basis.
### Techniques
領域           | 技術  |
--------------|:-----|
Analytics| [Python](https://www.python.org/)|
Front-end| Javascript, CSS, HTML|
Back-end  | [PHP](https://www.php.net/docs.php) |
Database|[MySQL](https://www.mysql.com/)|
Cloud Service|[Google Cloud Platform](https://cloud.google.com/gcp/getting-started?hl=zh-tw)|
