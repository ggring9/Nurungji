(작성중..)

# 누룽지

## 개요

- 슬랙용 운세 챗봇

> 당신의 행운을 긁어모아드립니다.

### 문제상황 

- 동일 input에 대해 운세사이트마다 서로 다른 운세를 출력함

### 해결방향

- 사용자에게 가장 긍정적인 운세 3가지만 출력함으로써 긍정적인 사용자 경험을 제공

- 다음의 3개의 사이트에서 운세정보를 크롤링한다.

- http://www.unsin.co.kr/

- http://shinhan.haezone.com/

- http://www.yuksul.com/

## 사용된 언어, 패키지, 라이브러리

- Python 3

- Flask

- Beautiful Soup

## 파일 설명

- WebParser.py

- WordCollector.py

- Test.py

- requirements.txt

- LuckScore.csv

## 구동 순서 및 결과

## 사용 방법

- 챗봇 구동 후 @[BOT_NAME] YYYY/MM/DD/HH:mm/양음력/성별

> @누룽지 2009/07/14/22:25/양력/남

## 발전 방향

- 챗봇 내 문맥 인지를 통한 긍/부정성 인식 알고리즘 개선
