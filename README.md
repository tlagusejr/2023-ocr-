# 2023-ocr-
7월 5일 시작~
ocr 공부를 위해서 해당 컴페티션(옛날에 열렸던)의 정확성을 높여 볼 계획입니다.
참고: https://dacon.io/competitions/official/236042/overview/description
데이터 eda 결과

1. 흐릿한 사진이 있음 (잡음 제거가 효과적 일 수 있음)
2. rnn을 사용하는데 rnn 말고 다양한 모델 시도

1. 먼저 베이스 라인을 돌려보고 각종 노이즈 알고리즘 실시
2. 괜찮아 보이는 노이즈 제거 알고리즘 사용 후 모델을 바꿔가기
3. 마지막으로 파라미터 optimization 사용
4. 경량 모델 테스트
