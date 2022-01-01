# 1. 개요
Google sentencepiece 빌드 연습

# 2. implement
### 2.1. 데이터 다운로드
web-crawler폴더 안에서 'python kowiki.py'를 실행 하여 kowiki_yyyymmdd.csv를 다운로드
### 2.2. csv2text
csv2txt.py를 실행하여 csv를 text로 변경된 파일 생성
### 2.3. sentencepiece buld 실행
sentencepiece_build.py를 실행하여 kowiki.txt를 파일에 있는 센텐스를 통해 학습된 kowiki.model 파일 생성
### 2.4. build된 결과 확인
학습된 kowiki.model로 센텐스에서 토큰으로 분리 되는 결과 확인

# 3. Referenc
[https://paul-hyun.github.io/vocab-with-sentencepiece/](https://paul-hyun.github.io/vocab-with-sentencepiece/)
