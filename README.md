# Skills-Requirements-Analysis-using-NLP

## 1. Introduction

   In today's job market, there's a growing need for people who are good at data analysis. This demand is especially high in sectors like Banking, Media & Entertainment, and Healthcare, where working with big sets of data is common. Many individuals are keen on starting a career in technology, specifically as a data analyst. However, becoming a data analyst involves learning various skills. To make things a bit tricky, different industries look for different skills. For those who are just starting out, figuring out which skills are most important can be a bit confusing.
   Our project is here to help with that. We're collecting information from popular job websites and carefully studying job descriptions to figure out the main skills you need to be a successful data analyst. The goal is to make things easier for people who are just starting out, giving them a clear idea of the skills that really matter in the real world of data analysis jobs. This project is all about helping newcomers make smart choices when it comes to developing the skills they need to succeed in the field.
   The primary objectives of this project are to facilitate individuals in discerning the pivotal skills requisite for a data analyst role and to offer comprehensive insights into the skill sets sought after by various industries. Employing the Python programming language, coupled with Natural Language Processing (NLP) techniques, we aspire to conduct a rigorous analysis of job descriptions pertinent to data analyst positions.
   
## 2. Research Questions

   - What skills are most required for Data Analysts?
   - What technical skills are most required for Data Analysts?
   - What soft skills are most required for Data Analysts?
   - What programming languages are most required for Data Analysts?
   - What skills are good to have for more opportunities in Data Analyst jobs?


## 3. Methodology

   The project's methodology employs a multifaceted approach to achieve its objectives. Initially, Python libraries like BeautifulSoup and Scrapy are utilized for web scraping, enabling the extraction of relevant data from leading job websites featuring data analyst positions. Subsequently, the collected job descriptions undergo thorough preprocessing to ensure data integrity and suitability for analysis. This preprocessing includes removing rows with missing values, eliminating stopwords and punctuation, converting text to lowercase, and lemmatizing words to standardize the dataset. Following preprocessing, the dataset is segmented into unigrams and bigrams, facilitating a detailed analysis of individual words and adjacent word pairs. After that, we use Rule-based approach and Word Embeddings approach to match words in the job descriptions with predefined skill keywords then we select the one with better performance for identifying the relevant skills. Finally, the results are visualized to pinpoint which skills are in highest demand in the data analyst job market.
