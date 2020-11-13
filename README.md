# KERIS_AI_hackathon_recycle_challenge
"Naver Smart Machine Learning Platform(NSML)을 이용하여 실제 인공지능 개발을 참여하는 AI 해커톤" 입니다.

### 문제
이곳에는 "본선 AI 문제" 에 대한 지금까지 연구했던 레포들을 모아놓았습니다.
* **연습용 AI 문제 : 영화 평점 예측문제**<br>
시놉시스, 감독, 배우 등 영화와 관련된 여러 데이터를 이용하여 곧 개봉 될 영화의 평점을 예측해보는 문제입니다.

* **본선 AI 문제 : 생활 폐기물 이미지 분류**<br>
이미지 분류 알고리즘을 통해 생활 폐기물 이미지를 분류하는 인공지능 알고리즘 개발하는 것입니다.

### 리더보드
[링크](https://ai.nsml.navercorp.com/ranking)를 눌러서 실시간으로 확인해 보세요!

## 폴더별 솔루션 내역
아래의 내용은 현 레포에 대해 어떻게 개선했고 어떻게 보완해 갔는지에 대해 서술 되어 있습니다.<br>
추후 솔류션별 결과도 공개하도록 하겠습니다.

초반부에는 Adam 모듈에서 여러 optimizer를 시도해 보았습니다.<br>
중반부부터 학습횟수를 증가시켰으며, betch_size, layer 등 개선해나가기 시작했습니다.
### KERIS014_recycle_challenge_2
생활 폐기물 이미지 분류하는 인공지능 알고리즘의 베이스 코드입니다. [원본](https://github.com/keris2020/hackathon/tree/main/recycle_challenge)

### KERIS014_recycle_challenge_5
optimizer를 기본 Adam에서 SDG로 교체해 보았습니다.

### KERIS014_recycle_challenge_8
optimizer를 기본 SDG에서 RMSprop로 교체해 보았습니다.

### KERIS014_recycle_challenge_9
optimizer를 기본 RMSprop에서 Adagrad로 교체해 보았습니다.
