## README

- git 협업 방법 fork 방식 참고 자료: https://seungwubaek.github.io/tools/git/contributing_using_pull_request/

## GIT 사용방법 
### **1. git bash 실행**

### **2. clone명령실행** 

`$ git clone https://github.com/vvspearlvvs/MultiCampus_Project`

### **3. status 명령실행** 

생성된 MultiCampus_Project 확인 및 status 확인

**`$ git status`**

아래와 같은 메세지 확인이 되면 정상

> On branch main
> Your branch is up to date with 'origin/main'.
>
> nothing to commit, working tree clean

### **4. 원하는 폴더에 자기가 한 결과물 넣음**

예시: [데이터분석/kjj항공데이터처리] 폴더를 생성하고, 그 안에 파일들을 넣음

### **5. status 명령실행** 

`$ git status`

아래와 같은 메세지 확인 및 Untracked files에 무엇인가 생겨난기록이 뜨면 정상

> On branch main
> Your branch is up to date with 'origin/main'.
>
> Untracked files:
>   (use "git add <file>..." to include in what will be committed)
>
> nothing added to commit but untracked files present (use "git add" to track)

### **6. add 명령실행**

참고로 tab으로 프로젝트 경로 자동완성가능

`$ git add 파일명`

예시 : $ git add 데이터_분석/kjj_항공데이터처리/

### **7. commit 명령실행**

`$ git commit -m "커밋메세지" `

예시: git commit -m "20210812 : 2021년 항공데이터 처리 by kjj"

### **8. puhs 명령실행** 

`$ git push -u origin main`
