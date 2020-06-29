# nlp-team-16-eng
for nlp sentiment analysis project

파일들을 보시기 위해서 크롬 브라우저를 사용하셔야 합니다.

메인 소스코드는 강의 실습자료인
https://colab.research.google.com/drive/1EMzEfTYjYLgEHjCCP1vEr9oOZLXMocGh?usp=sharing
를 참고하여 작성했습니다.

캐글 리더보드에 제출한 파일은 Team16_eng.ipynb를 사용했습니다.

프렌즈_CNN.ipynb 파일은 중간발표때에 구현했었던 코드입니다. 보고서 성능비교 부분에 적어 두었기 때문에 참고용으로 같이 업로드 했습니다.
프렌즈_CNN.ipynb는 조교님 github인 https://github.com/Parkchanjun/KU-NLP-2020-1 를 참조했습니다

실행방법
1. 구글드라이브에 Team16_eng.ipynb 파일을 업로드합니다. 이때, 구글드라이브의 루트 디렉토리에 업로드 해야합니다.

2. 구글드라이브에 "test"라는 폴더를 만듭니다.

3. "friends_train.json", "friends_dev.json", "friends_test.json", "en_data.csv" 네개의 파일을 그 폴더에 저장합니다.

4. 구글드라이브에 저장한 Team16_eng.ipynb파일을 코랩에서 실행시키고, 코드 블록들을 순서대로 실행시킵니다.

  ("training" block을 실행시키면 dev set으로 검증한 F1-score가 나옵니다)

  ("print out F1-score which is calculated with test dataset" block을 실행시키면 test set으로 검증한 F1-score가 나옵니다)

5. 맨 밑의 "this is for leader board csv file" block을 실행시키면 구글드라이브의 "test" 폴더에 "test_output.csv" 파일이 생성됩니다.
이 파일은 캐글 리더보드에 제출하는 용도로 사용됩니다.


