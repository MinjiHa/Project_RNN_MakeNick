# Project_RNN_NickBot
RNN-LSTM 블로그 닉네임 생성 서비스 : 블로그 닉네임을 학습하여 사용자의 입력에 어울리는 닉네임 텍스트를 자동 생성하는 모델 구현

- Selenium 데이터 크롤링 (닉네임 7764건)
- Embedding 차원축소 (974 -> 50) 
- LSTM레이어로 RNN모델 구성
- 순방향학습으로 입력데이터 뒷부분 텍스트 자동생성
- 역방향학습으로 입력데이터 앞부분 텍스트 자동생성
- 순방향학습모델과 역방향 학습모델 결합하여
   영어닉네임 앞뒤 텍스트 자동생성기능 구현


 ![image](https://user-images.githubusercontent.com/63627272/89909110-ac420880-dc29-11ea-813c-1204b62fa6f7.png)
