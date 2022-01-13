# :bulb: YouTube data Crawling / video hits prediction model 

### :dart: Objectives 
- YouTube 영상 정보 (채널명/구독자수/영상 제목/조회수/업로드 날짜/좋아요/싫어요), 특히 자연어처리를 거친 영상 제목을 수치화한 후의 변수를 포함하여 '조회수 예측 모델' 형성해보기 

### :memo: Project goes:
- Dataset: Selenium / BeutifulSoup 활용, YouTube 영상 정보 수집 crawling (채널명/구독자수/조회수/업로드 날짜/좋아요/싫어요)
- YouTuber 7인의 영상 정보 수집 -> 총 4568개의 데이터셋 (youtuber_crawling_data.csv) 생성 
- 영상 제목 NLP기법 및 Word Cloud 형성 하여, (언급 빈도/시기별/날짜별) 핵심 키워드 처리
- 영상 제목과 다른 영향 인자들로 '조회수 예측 모델' 형성하여, 크리에이터들을 위한 자신의 YouTube 채널 관리에 도움이 되길..

### :memo: Extra plan
- 썸네일 이미지 또한 활용하여 '조회수 예측 모델' 형성 해보기
- 요리 외 더욱 다양한 분야의 영상들을 (영상 제목 / 썸네일 이미지) 활용하여 '영상 컨텐츠 분야 자동 분류 모델' 형성 해보기
