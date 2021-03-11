# spring_board

게시판

* 요구사항
1차 목표
- 홈: 글목록
- 글 클릭하면 상세보기
- 글쓰기 기능
- 댓글 기능
- 글목록을 원하는 순서대로 정렬하는 기능: 최신댓글작성일/글작성일

2차 목표
- 회원가입
- 로그인


모든 과정을 티스토리 블로그에 공유한다.
210308:환경설정
210309:환경설정


개발환경:
1) Back-End
  - Language: JAVA jdk-11.0.10
  - FrameWork: Spring, mybatis
  - Server: Apache Tomcat9.0
  - IDE: STS3(Eclipse)
  - Database: mySQL

2) Front-End
  - Language: Javascript, HTML5, CSS3






1. REST API의 Best practice

REST API 원칙에 대해서 최소 3~4 일 정도의 시간을 투자해서 많은 문서들을 보는 것을 추천합니다. github에 있는 오픈소스를 보는 것도 방법이고, 유튜브나 여러 문서들을 상세히 살펴보는 것이 매우 중요합니다. 유명한 IT회사에서 OpenAPI Spec 문서를 보면서 힌트를 얻는 것도 큰 도움이 됩니다.

그래서 결과물은 적어도 어떤 endpoints들이 필요한지 README.md에 문서로 작성해 줍니다.



2. Frontend의 Best practice

Frontend는 HTML, CSS, Javascript만 있는 것은 아닙니다. 그 이상으로 Typescript를 사용하는 것이 장점인지, 어떤 패턴을 사용해야 하는지 Best practice를 살펴보는 것이 중요합니다.

예를 들어 React를 선택했다면 typescript와 redux pattern을 사용하고, 패턴에 대한 이해를 몇일 정도 충분히 공부할 시간이 필요합니다. 물론 문서를 README.md에 작성합니다.



3. DB 스키마 설계

사실 게시판 스키마 설계도 검색을 통해서 많은 정보를 얻을 수 있습니다. 하지만 데이터베이스 정규화와 함께 설계에 대한 서적을 읽으면서 스키마를 만들어 봅니다. 문서를 만들어 놓고, 나중에 사용을 위해서 스키마 생성 스크립트도 만들어 놓습니다.

