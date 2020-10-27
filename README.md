# Artificial Intelligence Lecture
인공지능 수업 (4-2)



### 1. TF-IDF를 이용한 문서 중요 단어 추출
- 문서 전처리: 영어만 추출, 소문자로 통일 
- TF-IDF 구현
- 문서마다 상위 k개 중요 단어 추출 (TF-IDF score가 높은 순)


### 2. TF-IDF 기반 Document Embedding 후 Clustering
- data: SMS dataset
- 문서 전처리: 영어만 추출, 소문자로 통일
- TF-IDF score가 높은 상위 200개 단어로 문서 embedding
- K-means Clustering (k=2)


### 3. Decision Tree
- data: IRIS
- Decision Tree를 이용해 classification
- Visualize: graphviz를 이용해 trained model visualize


### 4. Naive Bayes를 이용한 문장 감성분류
- data: Positive, Negative label이 있는 dataset
- 
