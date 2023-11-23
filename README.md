# git_connect

# git 설치 --> 기본값으로 그대로 설치했음

# 시작 버튼에서 Git Bash 열기(실행)
![image](https://github.com/gogoringhye/git_connect/assets/145514996/35a9bc5e-f865-4089-aa6f-d5b45a778c10)

![image](https://github.com/gogoringhye/git_connect/assets/145514996/2f128e3b-0778-4127-baac-c974d0174f92)

```
git config --global user.name "gogoringhye"
```

# github 가입시 입력한 이메일과 동일해야한다.
```

git config --global user.email "sugang7979@gamil.com"
```

# 정보 확인하기
```
$ git config --list
```
![image](https://github.com/gogoringhye/git_connect/assets/145514996/a9e35240-2415-4c9f-9599-7b06f4cf6792)

👶 ⬆️의 내용은 git을 다운받은 뒤로 컴퓨터에 한번만 설치하면 됨

--------

--------(선을 조금만 그어도 저장시 줄이 그여있음)

# GitHub에 코드 업로드하기 🥶

1. 초기화

비주얼스튜디오에 폴더 끌어와서 뉴터미널(clear 또는 cls 치면 에러난 것 정리 가능) 누르고 git init 작성
```
git init
```

# .git이라는 폴더가 생성

2. 파일 올리기

```
git add .
```

3. 히스토리 만들기
```

git commit -m "내가 적고싶은 메세지" 
```
# 메세지에는 한글이 가능함
# -m은 메세지의 준말

4. Github repository랑 내 로컬 프로젝트랑 연결(깃업에 프로젝트를 올릴 repository를 먼저 만들어야한다)
# 아래 주소는 깃업에서 만든 repository에서 복사해서 가져와야한다(repository를 만들 때 read.me 선택하지 말기)

```

git remote add origin https://github.com/gogoringhye/webstandard.git
```
![image](https://github.com/gogoringhye/git_connect/assets/145514996/f67e899b-128d-471c-9605-9a601c634961)

5. 잘 연결되었는지 확인(필수 아님)
```

git remote -v
```

6. GitGub에 자료 올리기
```

git push origin master
```

# ⬆️ 여기까지 하면 GitHub의 repository에 자료가 올라가 있다.


그리고나서 netlify--> Sites--> Add new site--> import--> Deploy with GitHub--> 원하는 파일 업로드


--------------
# git hub에 계속 업데이트 하는 법 ⛑

# 👀 수정된 파일 git hub에 올리는 법
※이전에 올린 깃허브 파일과 새로 올릴 파일 경로가 같아야 함
※VS에는 올릴 파일만 남겨두고 다 지워야함

[TERMINAL]

1. 추가할 파일 더하기
```
git add .
```
2. 히스토리 만들기
```
git commit -m "두번째 수정(하고싶은 말)
```
3. git hub에 올리기
```
git push origin master
```

# 🥵 단) 올릴 때 오류가 발생한다면 
```
1. 다시 git hub의 내용을 끌어와야한다
```
git pull origin master
```
2. 히스토리 만들기
```
 git commit -m "수정된 메세지(하고싶은 말)
```
3. git hub에 올리기
```
- git push origin master
```
