**# TIL (Today I Leaned)**

오늘 하루 배운 내용을 정리합니다.![image-20220317173949921](C:\Users\82107\AppData\Roaming\Typora\typora-user-images\image-20220317173949921.png)

1. workig directory 에 파일 생성

   - `touch day01.md`

     

2. stage area 로 파일 전송

   - `git add day01.md`
   - 전송하고 저장해야 다음단계로 진행 가능
   - `git status` 로 확인

   

3. commit 하여 최종본 전송

   - `git commit -m "first commit"`
   - `git log` `git log --oneline` 으로 확인

   

4.  전송한 ver1 을 깃허브에 보냄
   - `git remote add origin https://github.com/Heewon1/TIL.git` 연결
   - `git remote -v` ㅇㅅㅇ
   - `git push origin master` 이거 해야 깃헙페이지에서 갱신됨