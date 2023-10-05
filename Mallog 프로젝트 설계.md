포트폴리오와 함께 자신의 지식이 어떤 플로우로 정리되었고 그 정리된 내용을 볼 수 있는 사이트


### 주요 기능 
1. Markdown 형태의 에디터, 뷰어 
2. 포트폴리오 작성 기능 
3. 각 문서 작성중 퀘스쳔과 가설을 작성할 수 있고 
   이 질문들은 모두 unresolved question list가 된다. 
4. 다른 유저들의 퀘스쳔과 블로그 내용을 검색 할 수 있다. 
5. 기타 편의기능
	1. PWA로 모든 디바이스 커버 
	2. 포트폴리오 및 블로그 테마 설정 기능
	3. Github에 블로그(Markdown 형태로) 백업 

### 도메인 설계 
- mallog.com
- mallog.com/about
- malllog.com/[user]
	- 유저의 블로그 메인 페이지
	- 유저의 블로그 카테고리 보여주는 펲이지 
	- 유저의 블로그 활동내역 잔디(파도) 노출 
- mallog.com/[user]/about
- mallog.com/[user]/[contents]
- mallog.com/[user]/write&cid=[contentsId]
- mallog.com/[user]/write&cid=