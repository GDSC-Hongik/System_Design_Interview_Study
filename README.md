# 가상 면접 사례로 배우는 대규모 시스템 설계 기초 스터디

GDSC OC
이찬진 , 장동호 , 이진호 , 이채린

---

## 📁 Project Structure

```
│
├─ (root dir)
│     │
│     ├─ ImNM (dir)
│     │     │
│     │     ├─  1장_사용자_수에_따른_규모_확장성.md
│     │     ├─  2장_개략적인규모추정.md
│     │     ├─  3장_모든_객체의_공통_메서드.md
│     │     ├─ .. 이하동일
│     │
│     ├─ binary-ho (dir)
│     │     │
│     │     ├─  .. 이하동일
│     │
│     ├─ .. 이하 동일
│
│
```

---

## 🔏 Rule

1. 주당 2~3장씩!
2. 일정
   - 주 1회 비대면으로!
3. 커뮤니케이션 툴
   - 급한 일정은 카톡!
   - 디스코드 이펙티브 자바 방 활용
4. 스터디 방식
   - 각자 모든 장 공부 및 간단히 정리(요약+느낀점 좋아요)

---

## 👨🏻‍💻Process

1. 서적과 강의보고 자유롭게 정리
2. 본인 깃허브이름의 branch 생성 후 커밋
3. 발표 전까지 정리한 내용 `Pull Request` 생성
4. 화요일 오후 4시 발표
5. 발표&질문 끝나면 `Approve` 체크

---

## 📚 목차

- **1장 사용자 수에 따른 규모 확장성**
- **2장 개략적인규모추정**
- **3장 시스템 설계 면접 공략법**
- **4장 처리율제한장치의설계**
- **5장 안정해시설계**
- **6장 키-값저장소설계**
- **7장 분산시스템을위한유일 ID 생성기설계**
- **9장 웹크롤러설계**
- **10장 알림시스템설계**
- **11장 뉴스피드시스템설계**
- **12장 채팅시스템설계**
- **13장 검색어자동완성시스템**
- **14장 유튜브설계**
- **15장구글드라이브설계**

---

## 📝 해당 주차 과제 가이드

### 📤 프로젝트 열기

- 프로젝트를 하나 생성하고 IntelliJ에서 원격 저장소를 연결해줍니다
- `git init` // 원격 저장소 init
- `git remote -v https://github.com/GDSC-Hongik/Effective-Java.git` // 원격 저장소 연결
- `git pull origin main`
- IntelliJ의 terminal에서 자신의 branch로 checkout을 해주세요
  - `git checkout origin [본인 github 아이디]`
- 작업은 해당 **본인 branch에서만** 진행해주세요 **(~~❌master branch❌~~)**
  - `git branch` : 현재 branch 확인

### 🏡 작업공간 생성

- (프로젝트 루트 디렉토리)
  - 본인 github 아이디명의 디렉토리 (본인 github 아이디로 설정해주세요!)
    - 해당 장.md

| 본인 github 아이디명의 디렉토리부터 만들고 시작하시면 됩니다! 😊

---

### 💾 중간 중간 commit 하기

- 파트 별로 작업을 끝냈거나 더 작은 단위로 작업을 끝낼 때 마다 commit을 해 주는 게 좋아요
- ❗commit convention ❗️

  - **Feat**: 새로운 기능 추가
  - **Fix**: 버그 수정
  - **Docs**: 문서 수정
  - **Style**: 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
  - **Refactor**: 코드 리펙토링
  - **Test**: 테스트 코드, 리펙토링 테스트 코드 추가
  - **Chore**: 빌드 업무 수정, 패키지 매니저 수정

- 예시: `git commit -m "[Feat(해당 파일): OO 기능 추가]"`

### ✍🏻 README.md 파일 작성하기

- 해당 주차 책을 공부하면서 알게 된 부분, 중요하다고 생각한 부분이 있다면 정리해 주세요!
  - 개념 정립도, 요약도 모두 좋습니다! 😊
- 해당 주차 강의를 들으면서 새롭게 알게 된 사실이나 추가적으로 더 공부한 부분이 있다면 정리해 주세요!

  - 요약도, 복습도 모두 좋습니다! 😊😊

- .md 파일은 mark down 언어로 작성된 파일을 뜻해요
  - [참고] https://gist.github.com/ihoneymon/652be052a0727ad59601#24-코드

---

### 🙌🏻 Github 레포지토리에 push하기

- 해당 주차의 강의를 모두 듣고 작업을 모두 끝냈다면, 프로젝트 변경 사항을 remote repository(github repository)에 push 합니다
  - `git push origin [본인 github 아이디 브랜치 명]` : git에 등록되어 있는 origin(github repository)에 있는 자신의 branch로 프로젝트의 변경 사항을 반영합니다
- push를 완료했다면 스터디 repository에서 pull request를 진행합니다
- PR(Pull Request)시 메세지 제목은 다음과 같이 `[OOO] 1주차 제출합니다.` 라고 적은 후 `create pull request` 버튼을 눌러주세요
- PR : `base: [main]` <- `compare: [본인 github 아이디]`

---
