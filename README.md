# 2️⃣️ Git 협업

![git-collaboration](https://media.licdn.com/dms/image/C4E0DAQGYq7DdDvIr6g/learning-public-crop_288_512/0/1568669538450?e=2147483647&v=beta&t=jbk5EPqUfoeQQbGBYFVVpO6_iW_0ZMskzP2qIx4MtnQ)  
앞서 학습한 git 커맨드를 이용해 간단한 계산기를 함께 만들어봅시다. 이 과정에서 작업내용을 되돌려보기도 하고, 충돌도 해결해보고, 자신의 브랜치를 최신 상태로 업데이트해보기도 합니다.

## 시나리오

### [사칙연산]

1. 스터디원은 `step-2` 템플릿을 활용해 생성한 레포지토리를 자신의 로컬로 Clone합니다.
2. 스터디원는 main으로부터 자신의 브랜치를 만들고, 맡은 기능을 개발한 뒤 Pull Request를 올립니다.
3. 실습 후 스터디장은 레포지토리를 삭제합니다.

## 진행
![github-flow](./images/github-flow.png)  

### 1. ISSUE

- 각 참가자는 calculator.py 내 한 함수를 맡아 이슈를 생성합니다.
- [Issues] -> [New Issue] -> [할일 목록]
- 제목은 'Calculator - <함수> 구현'으로 적습니다.
- Assignee에 자기 자신을 붙입니다.

### 2. BRANCH

- 모든 참가자는 main으로부터 `feat/이슈넘버-이름-함수명`으로 브랜치를 생성합니다.
  - ex) feat/2-GiyunKim-add
- 이후 생성한 브랜치로 이동합니다.

### 3. ADD, COMMIT, PUSH

- 모든 참가자는 생성한 브랜치에서 함수를 구현하고, ADD 및 COMMIT 합니다.
- 이후 COMMIT을 원격 리포지토리에 PUSH 합니다.


### 4. PULL REQUEST

- 구현한 함수에 대해 Pull Request를 올립니다.
- PR 본문에 'close #이슈번호'를 달아 Merge와 동시에 이슈를 닫도록 합니다.

### 5. MERGE

- 조장은 PR을 리뷰한 후 머지(MERGE)합니다.

### 6. PULL
- 모든 참가자는 최신 레포지토리를 로컬로 불러와(PULL) 변경내역을 확인합니다.

