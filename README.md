![header](https://capsule-render.vercel.app/api?type=rect&color=gradient&height=100&section=header&text=Good%20Commit%20Message&fontSize=30&fontAlign=50&fontAlignY=50)

> :memo: 좋은 커밋 메시지 작성하기 <br>
> 레포지토리를 관리하는 중 기존 커밋 메시지들이 너무 지저분해서 규칙을 정하고 정리하기 위해 작성했습니다.

## :bookmark: Commit Message

### 구조

```
{type}({scope}): subject //header

{body} //body

{footer} //footer
```

### 규칙

- #### Header(필수)

  - 본문과 빈 행으로 구분한다.
  - 50글자 내로 제한한다.
  - 첫 글자는 대문자로 작성한다.
  - 끝에 특수문자를 넣지 않는다.
    > 마침표, 느낌표, 물음표
  - 명령문으로 작성한다.
    > 한글로 작성 시: "고침", "추가", "삭제", "변경" 등<br>
    > 영어로 작성 시: "Fix", "Add", "Delete", "Change" 등
  - 과거형으로 작성하지 않는다.

- #### Body(생략 가능)

  - 각 행은 72글자 내로 제한한다.
  - 어떻게 보다는 무엇과 왜를 설명한다.

- #### Footer(생략 가능)

  - 이슈 트래커 ID 작성한다.
  - "유형: #이슈 번호" 형식으로 작성한다.
    > Resolves: #123, #1234<br>
    > Ref: #124
  - 여러 개의 이슈 번호를 적을 때는 쉼표로 구분한다.
  - 이슈 트래커 유형
    > Fixes: issue 수정중<br>
    > Resovles: issue 해결<br>
    > Ref: 참고할 issue가 있을 때 사용<br>
    > Related to: 해당 커밋에 관련된 issue 번호 (아직 해결되지 않은 경우)

## :bulb:Header

- ### Type

  |    태그 이름     |                                     설명                                      |                       관련 Emoji                       |
  | :--------------: | :---------------------------------------------------------------------------: | :----------------------------------------------------: |
  |       Feat       |                           새로운 기능을 추가할 경우                           |                   :sparkles:sparkles                   |
  |       Fix        |                               버그를 고친 경우                                |                        :bug:bug                        |
  |      Design      |                         CSS 등 사용자 UI 디자인 변경                          |                   :lipstick:lipstick                   |
  | !BREAKING CHANGE |                                  대규모 수정                                  |                       :boom:boom                       |
  |     !HOTFIX      |                    급하게 치명적인 버그를 고쳐야하는 경우                     |                  :ambulance:ambulance                  |
  |      Style       |           코드 포맷 변경, 세미 콜론 누락,<br> 코드 수정이 없는 경우           |                        :art:art                        |
  |     Refactor     |                            프로덕션 코드 리팩토링                             |              :recycle:recycle<br>:zap:zap              |
  |     Comment      |                               주석 추가 및 변경                               |                       :bulb:bulb                       |
  |       Docs       |                              문서를 수정한 경우                               |                       :memo:memo                       |
  |       Test       |            테스트 추가, 테스트 리팩토링<br>(프로덕션 코드 변경 X)             |                  :test_tube:test_tube                  |
  |      Chore       | 빌드 태스트 업데이트, 패키지 매니저를 설정하는 경우<br>(프로덕션 코드 변경 X) |      :building_construction:building_construction      |
  |      Create      |                             새파일을 생성한 경우                              |                      :newspaper:                       |
  |      Rename      |             파일 혹은 폴더명을 수정하거나<br>옮기는 작업만인 경우             |                      :truck:truck                      |
  |      Remove      |                      파일을 삭제하는 작업만 수행한 경우                       |                         :fire:                         |
  |      Update      |                         여러가지 복합적인 변경인 경우                         | :raised_hands:raised_hands<br>:wastebasket:wastebasket |

- ### scope
  - 추가적인 문맥 정보를 제공하기 위한 목적으로 괄호 안에 작성
    > Fix(database)

## :books:Referenced

- [Plus Ultra-'협업을 위한 git 커밋컨벤션 설정하기'](https://overcome-the-limits.tistory.com/)
- [나를 남기다-'Gitmoji 사용하기'](https://treasurebear.tistory.com/70)
