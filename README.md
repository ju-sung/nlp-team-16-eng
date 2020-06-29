# nlp-team-16-eng
for nlp sentiment analysis project

소스코드는 강의 실습자료인
https://colab.research.google.com/drive/1EMzEfTYjYLgEHjCCP1vEr9oOZLXMocGh?usp=sharing
를 참고하여 작성했습니다.

실행방법
1. 구글드라이브에 Team16_eng.ipynb 파일을 업로드합니다. 이때, 구글드라이브의 루트 디렉토리에 업로드 해야합니다.

2. 구글드라이브에 "test"라는 폴더를 만듭니다.

3. "friends_train.json", "friends_dev.json", "friends_test.json", "en_data.csv" 네개의 파일을 그 폴더에 저장합니다.

4. 구글드라이브에 저장한 Team16_eng.ipynb파일을 코랩에서 실행시키고, 코드 블록들을 순서대로 실행시킵니다.

("training" block을 실행시키면 dev set으로 검증한 F1-score가 나옵니다)

("print out F1-score which is calculated with test dataset" block을 실행시키면 test set으로 검증한 F1-score가 나옵니다)

5. 맨 밑의 "this is for leader board csv file" block을 실행시키면 구글드라이브의 "test" 폴더에 "test_output.csv" 파일이 생성됩니다.
이 파일은 캐글 리더보드에 제출하는 용도로 사용됩니다.
