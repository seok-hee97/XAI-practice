## 1. 신용대출 분석 데이터(loan)

### 1.1. 데이터 설명

데이터는 loanData.csv에 저장되어 있다. loanData는 19개의 칼럼으로 되어 있으며, 첫 번째 칼럼부터 18번째 칼럼까지는 대출 신청을 위한 사용자 정보가 저장되어 있으며 19번째 칼럼에는 대출 승인 여부가 이진(binary) 형태로 저장되어 있다.

### 1.2. 칼럼 설명

데이터 칼럼이 의미하는 내용은 다음과 같다.

1. id: 고객 아이디
2. gender: 대출 신청자 성별
3. age: 대출 신청자 나이
4. married: 결혼 유무
5. dependents: 가족 수
6. education: 학력
7. self_employed: 자영업 유무
8. business_type: 국세청 기준 대출 신청인 업종 코드
9. applicant_income: 대출 신청인 수입
10. applicant_work_period: 대출 신청인 근무 기간
11. coapplicant_income: 배우자 수입
12. credit_history: 금융서비스(대출) 이용 횟수
13. credit_amount: 대출중인 금액
14. property_area: 주거지 종류(Urban: 도시, Semiurban: 준도시, Rural: 시골)
15. property_type: 주거지 소유 여부(1: 자가, 2: 월세, 3: 전세, 4: 기타)
16. credit_rate: 신용등급
17. loan_amount: 대출 금액
18. loan_term: 대출 상환 기간
19. loan_status: 대출 승인 여부

### 1.3. 기타

8번 칼럼의 국세청 업종 코드는 이곳(https://www.venturein.or.kr/popup/BusinessCode.do)에서 확인할 수 있다.

Copyright(c)2019 Jaehyun Ahn All rights reserved. 
