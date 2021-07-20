![header](https://capsule-render.vercel.app/api?type=rect&color=gradient&height=100&section=header&text=Good%20Commit%20Message&fontSize=30&fontAlign=50&fontAlignY=50)

> 좋은 커밋 메시지 작성하기 <br>
> 레포지토리를 관리하는 중 기존 커밋 메시지들이 너무 지저분해서 규칙을 정하고 정리하기 위해 만들었습니다.

## :bookmark: Commit Message

- ### 구조

  ```
  {type}({scope}): subject //header

  {body} //body

  {footer} //footer
  ```

- ### 규칙

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

## :books:Referenced

- [Plus Ultra-'협업을 위한 git 커밋컨벤션 설정하기'](https://overcome-the-limits.tistory.com/)
- [나를 남기다-'Gitmoji 사용하기'](https://treasurebear.tistory.com/70)
