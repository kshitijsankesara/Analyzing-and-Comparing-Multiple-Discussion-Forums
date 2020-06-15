# Analyzing and Comparing Multiple Discussion Forums  

For my IST 664: Natural Language Processing coursework, I analyzed the Wikipedia discussion forum and NPS Chat Corpus to understand the top words and frequency of each. *I analyzed 15 XML documents that contain over 10000 posts.* I aim to compare both the forums and check which text appears to be more formal and which one is grammatically correct. I analyzed all the slang words, incorrect spellings, and short form of words too. 

**Data Pre-Processing:**
1. Removed the HTML tags from the file
2. Perform Word Tokenization
3. Converted all words to lowercase
4. Removed the stopwords
5. Removed characters which are not alphabets

**Analysis:**
1. Found Top 50 words and their frequency using FreqDist class
2. Found Top Bigrams with raw frequency
3. Found Words and their Mutual Information Score
4. Comparison of both the results

**Libraries: BeautifulSoup, NLTK**

**Language: Python**
