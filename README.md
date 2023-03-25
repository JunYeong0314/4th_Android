# 4th_Android

## 1. 자신의 브랜치에 프로젝트 업로드하기

1️⃣ 본인의 스터디 repository 상단의 **Fork** 버튼을 누른 후, 생성합니다.
(1~2번을 건너뛰고 Fork 대신 Clone을 사용하셔도 괜찮습니다! 
Fork한 repository에서의 커밋은 잔디에 적용되지 않는다는 점 유의, Clone은 적용🙆‍♀️)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ee42149c-86a3-4484-a64a-e1c17e426e6b/Untitled.png)

2️⃣ 이처럼 본인의 repository에 포크된 것을 확인하실 수 있습니다🍴

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6bbf96a2-e285-4075-a2af-394de8bc9919/Untitled.png)

3️⃣ 본인의 **프로젝트를 감싸는 폴더**를 생성해줍니다 (감싸는폴더>**닉네임 폴더**>프젝파일)
     (main으로 병합하는 과정에서 코드 충돌 방지 위함)

4️⃣ 해당 폴더에서 `**git init**` 명령어를 통해 .git 폴더를 생성해줍니다. 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5fee298a-a37d-4462-a66c-80851e5f1bce/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fa55e4db-d0d6-460d-821d-0711f94307ab/Untitled.png)

5️⃣ `**git remote add origin 레포지토리주소**` 명령어를 통해 레포지토리와 프로젝트를 연결한다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/53630275-7fe4-42ac-b2f1-f4c914ff5f09/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4fe99bad-5a8d-4fe7-9333-7aec5fe097e1/Untitled.png)

6️⃣ `**git pull origin main**` 명령어를 통해 깃허브 main 브랜치 변경사항을 로컬에 동기화 시켜줍니다. (현재는 README.md 파일이 깃허브에 존재하기 때문에 필요)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dff057f6-b948-4e81-922e-9dfd0e153e5f/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ce0c7645-8f18-4d2e-bcef-df5308305f16/Untitled.png)

7️⃣ `**git branch 닉네임**` 명령어를 통해 자신의 브랜치를 생성합니다.

8️⃣ `**git checkout 닉네임**` 명령어를 통해 방금 만든 자신의 브랜치로 이동합니다. 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dc373343-c5b3-4ba6-bd58-c5c9436da8f3/Untitled.png)

9️⃣ `**git add .**` 명령어를 통해 업로드할 코드 (전체)를 선택하고, `**git commit -m “커밋메시지”**` 명령어를 통해 작업마다 commit을 진행합니다.

<aside>
💡 ***커밋컨벤션(커밋 규칙)**

CHORE: 코드 수정, 내부 파일 수정

FEAT: 새로운 기능 추가

FIX: 버그, 오류 수정

DOCS: README 등의 문서 수정

REFACTOR: 전면 수정(코드 리펙토링)

TEST: 테스트 코드 추가 및 수정

</aside>

🔟 `**git push origin 닉네임(브랜치이름)**` 명령어를 통해 **본인의 브랜치**로 push를 진행합니다.

(⚠git push origin main 명령어를 사용해 main에 push하지 않도록 주의해주세요!) 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bf4553eb-8e9c-42ba-839b-dcd9f2736742/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/05eea113-a19a-4cba-810b-7827e7d3fba2/Untitled.png)

→ 이와 같은 형태로 업로드 되어야 합니다! 해당 폴더 이름은 닉네임으로 부탁드려요
     (프로젝트_닉네임 말고 그냥 “닉네임” !!)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/73017c13-2494-451e-8580-b09697eeb06c/Untitled.png)

* 7~8번 과정을 통해 본인의 브랜치에 commit 및 push 진행하시면 됩니다 😊

## 2. Main 브랜치로 **PR(Pull Request)** 날리기

여러분의 협업 연습과 푸릇푸릇한 잔디🌱를 위해! TMI. 잔디는 main 브랜치와 merge되면 브랜치에 커밋했던 잔디가 한 번에 심어집니다 ~~축구장 한 번 만들어보자구요⚽~~)

1️⃣ 푸시한 후, main 브랜치에 compare&pull request가 뜨면 해당 버튼을 클릭하기!
     뜨지 않는다면 Pull requests의 new pull request를 선택한 후, 
     **compare는 본인의 브랜치, base는 main 브랜치**로 설정한다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c8a6fc17-e93d-4dcd-a01f-3442a86e45d8/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f7df684b-1101-4ebc-ae80-4cdd8f757ac1/Untitled.png)

2️⃣ 아래와 같은 규칙을 지켜 Pull Request를 생성한다.

<aside>
💡 **Title: N주차미션_닉네임 (ex. 5주차미션_유닝이)**

**Reviewers(PR을 리뷰해 줄 팀원): 파트장 + 스터디원 중 (최소)1명**

→ 스터디원들의 미션을 확인하며 **리뷰, 칭찬, 피드백** 등을 진행합니다! 
    (스터디 내에서 논의해 각자 최소 1명의 스터디원 코드 리뷰 진행)

→ 최종적으로 파트장이 워크북 및 코드 제출을 확인한 후, 
    main으로 merge하도록 하겠습니다 :)

**Assignees(PR 담당자): 본인**

**Labels: mission**

</aside>

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/828c97d3-aab4-4973-8826-1d476e39f813/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b24f93d6-4a6a-455d-b7c2-1da95f00470f/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5295c376-25d7-4359-ba43-fc3268fdc073/Untitled.png)

→ 리뷰를 남기지 않으면 merge가 불가능하도록 설정했습니다!
    **그러니까 잊지 말고 스터디원 코드리뷰 한 글자라도 적어줍시다 🙌**

3️⃣ 스터디 시간에 다른 reviewers들의 comment를 기다렸다가 확인하기 !

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/62cb644e-a59c-4bea-aa4c-e4c39f380582/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/19e85328-38a1-47b3-85d2-019284d37c44/Untitled.png)

→ 이후 머지를 진행하여 메인에서 다음과 같은 형태로 관리할 예정
~~(아니 몽쉘 먹으면서 적고 있어서 그러는데,, 몽쉘이 엄청 작아졌어요 여러분,, 진 짜 한 입 끝.)~~

## 3. 스터디원 **코드 리뷰**해주기

1️⃣ 리뷰하고자 하는 PR에 들어가서 스터디원의 코드를 살펴보고 Review changes에 들어간다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b24f93d6-4a6a-455d-b7c2-1da95f00470f/Untitled.png)

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f5c95dff-8f4b-4502-a5a2-a1490b72fafc/Untitled.png)

2️⃣ 스터디원의 코드를 살펴보고 피드백과 칭찬을 아낌없이 마구마구 적는다.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/50001b53-5768-4047-aea8-f7af3d3cd31b/Untitled.png)

Comment : 일반적인 커멘트
**Approve : 승인 = “머지해도 괜찮다” (Approve로 선택해야 승인이 됩니다!)**
Request changes : 변경 요청, 승인 거부

3️⃣ 이후, Submit review를 눌러 reviewer로써 할 일을 마친다,*
