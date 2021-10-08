# BERT Based Topic-Specific Crawler

This paper presents a multi-thread web crawler using a Sentence Bidirectional Encoder Representations from Transformers ([S-BERT]((https://arxiv.org/abs/1908.10084))). The S-BERT is used to calculate the similarity between the predefined classes and the text of the downloaded web pages.

![image](https://user-images.githubusercontent.com/1148381/124077128-cfe38c80-da4f-11eb-97e1-158e5aae7d36.png)

## Authors

* Yahya Tawil.
* [Dr. Saed ALQARALEH](https://scholar.google.com.tr/citations?user=Pz8eE28AAAAJ&hl=en).


## ASYU 2021 Conferance Paper Presentation 
Available on [Youtube](https://youtu.be/5r8Snv5E_Vk).

## Organization

This Repo is organized like the following: 

* Code: inside this folder there are `downloader_V_0_10.ipynb` which is the crawler code written and tested using Google Colab and also `evaluator.ipynb` which is a simple code to evaluate the results (inform of csv file) of crawler (calculate the true positives and false positives for each topic)

* Report: A report in both PDF and Latex source. 

* Results: CSV files as an examples of an output after running the code for hours. 

# Instructions

To run the code, use downloader_V_0_10.ipynb and run it directly in Google colab. Make sure to select the right settings by changing the `conf` dictonary in the code.  

