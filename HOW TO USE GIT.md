![1](HOW%20TO%20USE%20GIT.assets/1.png)

1. <b>`` pwd``</b> 명령어로 현재 위치를 확인합니다.

2. <b>``cd`` </b>명령어를 통해 원하는 경로로 이동합니다.

   - 저는 Desktop/ (바탕화면)으로 이동하고 새폴더로 이동했습니다.

   - 잘못된 경로로 접근했으면 **``cd..``**을 통해 상위 디렉토리로 이동할 수 있습니다

3. 원하는 디렉토리에서 **``git clone`` repository url ** 을 진행합니다. 

   - repository url은 git허브에서 복사할 수 있습니다.

   - ![8](HOW%20TO%20USE%20GIT.assets/8.png)

     > code라고 쓰인 초록색 버튼을 누르면 주소를 확인할 수 있습니다

![2](HOW%20TO%20USE%20GIT.assets/2.png)

![3](HOW%20TO%20USE%20GIT.assets/3.png)

4. 지정한 폴더에, clone 받은 github repository와 같은 이름의 폴더가 생겼습니다.
   - MultiCampus_Project **``.git``** 폴더가 생겼으므로 github와 로컬 저장소가 성공적으로 연결 됐습니다.
   - ![4](HOW%20TO%20USE%20GIT.assets/4.png)
   - 폴더내부에서 작업을 진행합니다 (저는 새로 추가한 파일.ipynb를 새로 생성했습니다.)

![5](HOW%20TO%20USE%20GIT.assets/5.png)

5. **``.git``** 폴더가 있는 디렉토리에서만 push, pull 할 수 있습니다.

   - **``.git``** 폴더가 있는 MultiCampus_Project 폴더로 이동합니다. (현재 위치 확인할 것)
   - 이동하지 않고 git에 관한 명령어를 사용한 결과 에러가 발생했습니다 (fatal: not a ...)

6. **``git add .``** (.은 현재 폴더에있는 전체를 올리겠다는 뜻입니다)

   - **``git add 파일명``** 명령어를 통해 특정 파일만 add할 수도 있습니다

   ![6](HOW%20TO%20USE%20GIT.assets/6.png)

7. **``git commit -m 커밋메세지``**

   - 어떤 저장본인지 구분할 수 있게 커밋메세지를 설정합니다.

8. **``git push -u origin main``**

   - github에 업로드 (push)합니다. 
   - 첫번째 push이후로는 **``git push``** 까지만 입력해도 push할 수 있습니다

![7](HOW%20TO%20USE%20GIT.assets/7.png)

앞서 생성했던 새로 추가한 파일.ipynb가 github에 업로드된 것을 확인할 수 있습니다.