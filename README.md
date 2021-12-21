# CommitRule

## commit 규칙
```
type(타입) : title(제목)

body(본문, 생략 가능)

Resolves : #issue, ...(해결한 이슈 , 생략 가능)

See also : #issue, ...(참고 이슈, 생략 가능)
```

## type
- feat : 새로운 기능 추가
- fix : 버그 수정
- docs : 문서 수정
- style : 코드 formatting, 세미콜론(;) 누락, 코드 변경이 없는 경우
- refactor : 코드 리팩토링
- test : 테스트 코드, 리팽토링 테스트 코드 추가
- chore : 빌드 업무 수정, 패키지 매니저 수정

## title
- 제목은 50자를 넘기지 않고, 마침표를 붙이지 않는다.
- 제목에는 위 커밋 종류를 함께 쓴다.
- 과거시제를 사용하지 않고 명령조로 작성한다.
- 제목과 본문은 한 줄 띄워 분리한다.
- 제목의 첫 글자는 반드시 대문자로 쓴다.
- 제목이나 본문에 이슈 번호(가 있다면) 붙여야 한다.

## body
- 선택사항이기에 모든 커밋에 본문 내용을 작성할 필요는 없다.
- 한 줄에 72자를 넘기면 안된다.
- 어떻게(How)보다 무엇을, 왜(What, Why)에 맞춰 작성한다.
- 설명뿐만 아니라, 커밋의 이유를 작성할 때에도 쓴다.
- Resolves, See also
- Issue Tracker ID를 작성할 때 사용한다.

## 자주쓰는 영어 표현
- Fix typo
  - 오타수정
- Fix A in B
  - B의 A를 수정합니다
- Fix A which B, Fix A that B
  - B절인 A를 수정합니다
