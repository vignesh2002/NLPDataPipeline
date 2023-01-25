# NLPDataPipeline

This project is for news data scrappinng from the news.csv data set.
1. The news.csv file is converted to news.json (old content) for ease of use.
2. The 'content' column of each entry in the json file is extracted to scrap data from.
3. The text_preprocessing.ipynp file is used to extract important information from entire senctences. The SpaCy library was used to do the same.
   The following functionas were computed on the data:
   
   -> Stop words were removed.
   
   -> Punctuations and special charaters were removed.
   
   -> Sentences were split.
   
   -> Lemmatization was done.
   
   -> Frequency of each word was counted after these opertions.
   
   The output shortened sentences were saved to news.txt (new content).
   
4. The NLP_pipeline.ipynb is used to label, train and test the dataset created. 

The output of the testing is as follows: 
![image](https://user-images.githubusercontent.com/63063671/214640321-ac9ade91-79b5-402d-99dc-f25dcffca2ef.png)
