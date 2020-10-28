# Artificial Intelligence Lecture
인공지능 수업 (4-2)


-------------------------------------------------
### 1. TF-IDF를 이용한 중요 단어 추출
- Data: 자연어 영어 문서 3개
- Preprcessing: 영어만 추출, 소문자로 통일 
- TF-IDF 구현: 문서마다 상위 k개 중요 단어 추출 (TF-IDF score가 높은 순) (공백 기준 토큰 분리)



--------------------------------------------------
### 2. Natural Language document Clustering
- Data: SMS dataset
- Preprocessing: 영어만 추출, 소문자로 통일
- Embedding: TF-IDF score가 높은 상위 200개 단어 (포함=1, 미포함=0 방식 임베딩) (공백 기준 토큰 분리)
- Model: K-means Clustering (k=2)



-------------------------------------------------
### 3. Decision Tree
- Data: Iris
- Model: Decision Tree
- Visualize: graphviz를 이용해 trained model visualize



-------------------------------------------------
### 4. Naive Bayes를 이용한 문장 감성분류
- Data: Positive, Negative label이 있는 자연어 dataset
- Embedding: Positive, Negative document에서 각각 중요도 상위 100개 (총 200개) 단어 사용 (CountVectorizer 방식 임베딩) (공백 기준 토큰 분리)
- Postprocessing: Vocabulary에 포함하는 단어가 없는 문서 (=0벡터 문서) 제거 
- Model: Naive Bayes



-------------------------------------------------
### 5. SVM을 이용한 스펨 메일 분류
- Data: SMS Spam/Non-spam data
- Embedding: (빈도 상위 300개 단어) + (Chi-square (카이제곱) score가 높은 상위 200개 단어) = 500차원 임베딩
- Model: SVM (Binary Classification)
