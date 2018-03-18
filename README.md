# 아기사자의 질문

6기 수업이 거의 끝나갈 무렵 열심히 수업을 듣던 아기사자가 다가와 질문을 합니다.

"저 분명 강의랑 **똑같이** 따라만 쳤는데 에러메세지가 나와요!"

![baby](./img/baby.jpg)

> 앗! 야생의 아기사자이(가) 나타났다!

아기사자가 열심히 짠 에러페이지를 고쳐줍시다!



## version

- ruby : 2.4.0
- rails : 5.0.6



## debugging

1. 해당 Repo 를  clone 합니다.
2. `Rails s` 를 통해 나타나는 에러 메세지를 확인하며 시작!
3. 다음과 같은 기능이 오류없이 정상적으로 동작해야 합니다.
   - `Rails s` 이후 `localhost:3000`으로 접속후 어떠한 에러 페이지도 없어야 합니다.
   - `Post`의 **C**reate, **R**ead, **U**pdate, **D**elete
   - `Comment`의 **C**reate, **R**ead, **D**elete
   - **1 : N** Relation (`User`와 `Post`, `Post`와 `Comment`, `User`와 `Comment`)
4. 완성 확인을 위해 다음 유저 시나리오를 실제로 동작해보세요.
   - root_url 로 이동.
   - 회원 가입 => 로그인
   - 새 글 작성.
   - 생성된 글 확인.
   - 개별 게시글 수정 / 삭제.
   - index 확인.
   - 개별 게시글에서 댓글 작성 / 삭제 및 확인.



## 추가기능

- 좋아요 기능을 추가해주세요
  - 모델의 이름은 Like
  - 해당 기능과 관련된 액션은 posts_controller.rb에 작성
  - show페이지에 좋아요 버튼을 추가
  - 좋아요 버튼의 옆에 좋아요의 총 갯수 표시
  - 해당 글에 좋아요를 누르지 않은 상태
    - 좋아요 버튼
    - 버튼을 누르면 좋아요 갯수 증가 및 "좋아요 취소" 버튼으로 변경
  - 해당 글에 좋아요를 누른 상태
    - 좋아요 취소 버튼
    - 버튼을 누르면 좋아요 갯수 감소 및 "좋아요" 버튼으로 변경
- 완성된 사이트를 디플로이 해주세요
  - Amazon EC2 사용



## 제출방법

- 제출 항목
  - 원본 소스코드 주소(Github / Bitbucket)
  - Amazon EC2에 Deploy한 Public IP주소
- 제출 주소
  - https://goo.gl/forms/BdwnTsON6kPzmkKn2# baby-lion
