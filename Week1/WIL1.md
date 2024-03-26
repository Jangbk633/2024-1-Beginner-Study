## 첫 주 복습

깃허브와 컴퓨터 연결하기 위해서는

    git config --global user.name "이름"

    git config --global user.email "이메일"

식으로 작성한다.

github의 repository와 연동하기 위해서는

    git init

명령어를 입력 후 폴더 이름과 같게 해서 github에서 repository를 만든 후 코드를 복붙해서 실행해준다.

vscode에서 내 github repository에 upload하기 위해서는

    git add .

    git commit -m "주석"

    git push origin main

순으로 입력해야 한다.

특히

    git add

는 add 뒤에 ., <파일 이름> 등등을 붙임으로 add할 파일들을 따로 지정해주거나 모든 파일을 add해줄 수 있다.

그 외에도 add, commit등의 상태를 알아보고 싶으면

    git status

    git log

와 같은 명령어로 알아볼 수 있다.

<https://github.com/Jangbk633/Jangbk633>