# joobo
주보를 바탕으로 정보를 찾아주는 챗봇

다음과 같은 방식으로 만들어볼 생각입니다.

1. 현재까지 저장된 홈페이지와 주보 정보를 Vector DB로 임베딩 합니다.
2. 해당 임베딩 정보를 통해 RAG를 구성합니다.
3. 최종적으로 서버에 올리고 서비스합니다.
