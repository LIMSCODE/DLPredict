# DLPredict
DeepLearning Multimodal Predict <br>
![image](https://github.com/user-attachments/assets/b8b416c4-27d7-40d4-963f-742ce72f8f39)

### 사용자데이터.csv
```
화장품상품명
설명
이미지
매출액
리뷰,평점
검색기록
```

### LLMTraining.json (LLM학습데이터)
```
context: "사용자가 구매했던 화장품상품명,설명,이미지,매출액,리뷰,평점과 검색기록은 ...입니다.
          이러한 사용자행동데이터를 통한 상품추천결과는 ...입니다.",
question: "'사용자가구매했던상품명', '검색기록' 을 토대로 상품추천결과는?"
answer: { "product_name": "화장품추천결과", "description": 설명 }
```

### LLM추천결과.csv
```
화장품상품명
설명
이미지
매출액
리뷰,평점
검색기록
+ ` 상품추천결과, 상품추천결과RAG `
```

### 매출액예측결과.xlsx
추천된상품의 매출액예측 및 분포비교
