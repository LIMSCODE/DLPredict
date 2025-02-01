# DLPredict
DeepLearning Multimodal Predict <br>
![image](https://github.com/user-attachments/assets/3ab68366-14a3-4a30-ba32-93eda500243e)

### 데이터수집
```
화장품상품명
설명
이미지
매출액
리뷰,평점
검색기록
```

### LLM학습 Json학습데이터
```
context: "사용자가 구매했던 화장품상품명,설명,이미지,매출액,리뷰,평점과 검색기록은 ...입니다. 이러한 사용자행동데이터를 통한 상품추천결과는 ...입니다.",
question: "'사용자가구매했던상품명', '검색기록' 을 토대로 상품추천결과는?"
answer: { "product_name": "화장품추천결과", "description": 설명 }
```
