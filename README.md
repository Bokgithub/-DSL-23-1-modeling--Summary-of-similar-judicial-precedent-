# DSL-23-1-modeling--Summary-of-similar-judicial-precedent-

## DSL 23-1 Modeling Project B조

## Overview
[모델링 B조_ppt.pdf](https://github.com/Bokgithub/-DSL-23-1-modeling--Summary-of-similar-judicial-precedent-/files/11245894/B._ppt.pdf)


### 1. Topic

![image](https://user-images.githubusercontent.com/80932078/232370431-365ed2d7-8d04-44d9-84bd-5888d150df4d.png)


### 2. Data Crawling & Processing
- 저작권 판례 데이터 수집
- 데이터 전처리: html 언어 제거 및 dfsf
- Final Processed DAta


![image](https://user-images.githubusercontent.com/80932078/232370737-3135f629-25f4-4aa9-8150-68ce90dd698d.png)
![image](https://user-images.githubusercontent.com/80932078/232370757-892e240d-7045-44f0-b662-a578b62c699e.png)
![image](https://user-images.githubusercontent.com/80932078/232370772-7dd4acd7-ce1d-447d-9e3b-11a0c33c5726.png)
![image](https://user-images.githubusercontent.com/80932078/232370793-83b3e9cb-3d37-40a2-9021-43c482720a9c.png)
![image](https://user-images.githubusercontent.com/80932078/232370810-f0f4e604-ab03-4da6-9cd2-21c265c36437.png)

### 3. Model Explanation

![image](https://user-images.githubusercontent.com/80932078/232371267-48434c65-62a0-4972-b1ea-badcc1dfe9c9.png)

- SBERT : Sentence BERT
 ![image](https://user-images.githubusercontent.com/80932078/232371345-5b030eae-4454-4855-9b34-b944fd02834c.png)
 
 - Cosine Similarity
 
 ![image](https://user-images.githubusercontent.com/80932078/232371454-01000e33-5501-4259-b0f7-0ad260eb4262.png)

 
 ### 4. Modeling
 - Similarity Calculation
 ![image](https://user-images.githubusercontent.com/80932078/232371505-d7539454-182f-4d4d-b1ce-c75021133203.png)


### 5. Metric
ROGUE & Human Evaluation
![image](https://user-images.githubusercontent.com/80932078/232371595-aa97b189-00ad-4703-8d1f-032087a93cee.png)

 


## File Explanation

### 1. Data
- raw : raw data of judical precedent
- processed : processed data for model

### 2. Model

- Similarity_Calculation.ipynb : calculate similarity between judical precedent & input. output for three the most similar precedents.

- Summarization.ipynb : summary the precedents

- Model_composition.ipynb : Compose Similarity_Calculation and Summarization

### 3. Main
- Model_composition.ipynb : Compose Similarity_Calculation and Summarization

