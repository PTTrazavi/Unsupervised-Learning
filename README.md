# Unsupervised Learning - Clustering
用scikit-learn執行unsupervised learning的基礎，包含以下程式碼。  
### 1 Unsupervised Learning.ipynb
此範例說明如何將高維度的特徵降維以顯示在圖上，方法包含Principal Components Analysis(PCA)、Multidimensional scaling (MDS)、t-SNE。  
並說明如何用scikit-learn做clustering，方法包含K-means、Agglomerative clustering、DBSCAN clustering。  

### 2 text clustering.ipynb
此範例說明如何對未標簽的文章做分類，首先用TF-IDF(Term Frequency - Inverse Document Frequency)提取特徵，再用K-Means做分群。    

### 3 BBC news clustering.ipynb
此範例和上一例類似，做資料量較大的新聞分群。  

### 4 mnist auto encoder.ipynb
此範例用autoencoder(一種self-supervised learning)，做MNIST的分群。  
![image4](images/04.jpg)  

### 5 mnist multi-input.ipynb
此範例用shared layer技術，同時輸入兩張圖，判斷是否為同類別。  
![image5](images/05.jpg)  

### 6 BBC news multi-input.ipynb
此範例用shared layer技術，同時輸入兩篇文章，判斷是否為同類別。  

### TF-IDF
代表文章特徵的一種方法。  
![image1](images/01.jpg)  
![image2](images/02.jpg)  
![image3](images/03.jpg)  

## References
https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html  
https://www.coursera.org/learn/python-machine-learning?specialization=data-science-python  
https://www.coursera.org/learn/ml-foundations?specialization=data-science-python  
https://www.kaggle.com/sameersmahajan/people-wikipedia-data  
https://github.com/aspamers/autoencoder  
https://blog.keras.io/building-autoencoders-in-keras.html  
https://machinelearningmastery.com/lstm-autoencoders/  
https://keras.io/getting-started/functional-api-guide  
