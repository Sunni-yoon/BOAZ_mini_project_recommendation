# BOAZ 미니 프로젝트
🚩 요기요 치킨집 리뷰 데이터를 활용하여 치킨집을 추천해주는 추천시스템을 구현하는 것이 목표

<b>
<b>

## 데이터
요기요 치킨 리뷰 데이터

3. 추천
통계, Matrix Factorization, 리뷰 이용

4. 다양한 인사이트 도출
5. 의의
데이터 수집부터 전처리, 구현까지 경험할 수 있었음
통계, matrix factorization, 자연어 처리 등 여러 가지 방식을 이용해 데이터 수집
6. 한계
다른 사람이지만 같은 id로 보이는 문제가 있어 단순 코사이 유사도 기반으로는 정확한 추천에 어려움이 있음
'치킨'에만 한정되어 있어 도메인 특성의 영향이 있는지 확인이 어려움
과적합의 위험
7. 보완할 점
id가 왼쪽 두 글자만 나와 더 정확한 추천을 위해 보완
하이퍼 파리미터 튜닝을 통해서 성능을 올렸지만 과적합의 위험이 있기 때문에 앙상블이나 여러 기법 등 사용
데이터의 경우 정보가 적어 추천의 한계가 있음
