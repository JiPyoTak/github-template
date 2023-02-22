# Github Templates

## Github Commit Message

- 아래 명령어를 통해 해당 프로젝트에서 사용할 수 있다
  `git config commit.template .gitmessage`

```

#Co-authored-by: jintak0401 <jintak0401@naver.com>
#Co-authored-by: pyo-sh <pygosky@gmail.com>
#Co-authored-by: seoko97 <sukho1007@naver.com>

################
# <타입> : <제목> 의 형식으로 제목을 아래 공백줄에 작성
# 제목은 50자 이내 / 변경사항이 "무엇"인지 명확히 작성 / 끝에 마침표 금지
# 예) feat : 로그인 기능 추가
# 바로 아래 공백은 지우지 마세요 (제목과 본문의 분리를 위함)
#
#
################
# 본문(구체적인 내용)을 아랫줄에 작성
# 여러 줄의 메시지를 작성할 땐 "-"로 구분 (한 줄은 72자 이내)
#
#
################
# 꼬릿말(footer)을 아랫줄에 작성 (현재 커밋과 관련된 이슈 번호 추가 등)
# 예) Close #7
#
#
################
# feat : 새로운 기능 추가 (변경사항, 추가)
# fix : 버그 수정
# docs : 문서 수정
# test : 테스트 코드 추가
# refactor : 코드 리팩토링
# chore : 빌드 부분 혹은 패키지 매니저 수정사항
################
```

## Issues

### feature

```
---
name: feature issue template
about: Create about new feature
title: ''
labels: feature
assignees:
---

## :briefcase: **구현 개요**



## :white_check_mark: **진행 계획 및 현황**

- [ ]
```

### bug

```
---
name: Bug report
about: Create a report to help us improve
title: ""
labels: bug
assignees: jintak0401, pyo-sh, seoko97
---

## 🐛 **버그 설명**



## 🚦 **제시 혹은 요청하는 해결 방법**



## 🌄 **스크린샷**


<!---
## 🍟 **추가 내용**

--->
```

## PR

```
* Closes #이슈번호

## ✨ **구현 기능 명세**

## 🎁 **주목할 점**

## 😭 **어려웠던 점**

## 🌄 **스크린샷**
```
