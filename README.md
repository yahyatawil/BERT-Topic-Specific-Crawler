# Topic-Spesific-Crawler
This project is supervised by [Dr. Saed ALQARALEH](https://scholar.google.com.tr/citations?user=Pz8eE28AAAAJ&hl=en) and done by Yahya Tawil as a part of Data Mining and Knowledge Discovery course during my Master program. This is an implementation of a multiy thread topic-specific crawler based on topics specified by the user. The carawler will save also the images presented in the webpage using a unique hash number for each page. The topic classification of the content is based on cosine similarity between the BERT embedding of the content and the provided labels (based on [Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks](https://arxiv.org/abs/1908.10084)) . 

![image](https://user-images.githubusercontent.com/1148381/124077128-cfe38c80-da4f-11eb-97e1-158e5aae7d36.png)


This Repo is organized like the following: 

* Code: inside this folder there are `downloader_V_0_10.ipynb` which is the crawler code written and tested using Google Colab and also `evaluator.ipynb` which is a simple code to evaluate the results (in form of csv file) of crawler (calculate the true positives and false positive for each topic)

* Report: A report in both PDF and Latex source. 

* Results: CSV files as an examples of output after running the code for hours. 

# Instructions

To run the code, use downloader_V_0_10.ipynb and run it directly in Google colab. Make sure to select the right settings by changing the `conf` dictonary in the code.  
