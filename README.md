# Numeracy-600K: Learning Numeracy in Market Comments and Article Titles
# Introduction
Numeral is the crucial part of in narrative, especially in financial documents. We should not only analyze the text, but also need to assay the numeric information in depth. Numeracy-600K is a dataset for testing the numeracy of machines.

# Format
The Numeracy-600K dataset includes two subsets:

(1) Market Comments: This dataset is collected from Reuters, and consists of "id", "UNIQUE_STORY_INDEX", "offset", "length", and "magnitude" in json format.

(2) Article Titles: This dataset is collected from [The Examiner](https://www.kaggle.com/therohk/examine-the-examiner), and consists of "id", "title", "publish_date", "offset", "length", and "magnitude"

# Example
(1) Market Comments
```yaml
{

'id': 0

'UNIQUE_STORY_INDEX': '20160816085706nL3N1AX2ZW'

'offset': 52,

'length': 3,

'magnitude': 1

}
```

(2) Article Titles
```yaml
{

'id': 0

'title': '100 Most Anticipated books releasing in 2010',

'publish_date': '20100101',

'number': '2010',

'offset': 40,

'length': 4,

'magnitude': 4

}
```
# Download
Click [here](http://nlg.csie.ntu.edu.tw/nlpresource/Numeracy600K/Numeracy_600K_comment.zip) to download Market Comments data.
Click [here](http://nlg.csie.ntu.edu.tw/nlpresource/Numeracy600K/Numeracy_600K_article_title.json) to download Atricle Titles data.
> If you encounter issues when clicking the above link, please paste the link url to your browser url to download.


# How to Cite the Corpus
Please cite the following paper when referring to the Numeracy-600K in academic publications and papers.

Chung-Chi Chen, Hen-Hsen Huang, Hiroya Takamura and Hsin-Hsi Chen. 2019. Numeracy-600K: Learning Numeracy for Detecting Exaggerated Information in Market Comments. In Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (ACL 2019), Florence, Italy.
# Results Update - 20190824
Here is the latest results. pdf
# License
Numeracy-600K is licensed under the [Creative Commons Attribution-Non-Commercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

The full text of market comments are owned by Reuters.

The full text of article titles are prepared by Rohit Kulkarni, and under [CC0: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) license.
