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
	- 검색바 
	- Hot 게시물 
	- 로그인한 유저면 너가 관심있어하는 게시물
- mallog.com/about
	- Mallog 소개페이지 
- malllog.com/[user]
	- 유저의 블로그 메인 페이지
	- 유저의 블로그 카테고리 보여주는 펲이지 
	- 유저의 블로그 활동내역 잔디(파도) 노출 
- mallog.com/[user]/portfoilo
- mallog.com/[user]/[contents]
- mallog.com/[user]/write-contents
	- mallog.com/[user]/write-contents&cid=[contentsId]
- mallog.com/[user]/write-question
	- mallog.com/[user]/write-question&qid=[quentionId]
- mallog.com/[user]/settings

### API 설계 
###### Auth
- 회원가입
- 로그인
- 로그아웃
###### Search 
- 검색

###### User Portfoilo
- 포트폴리오 조회
- 포트폴리오 수정/저장 

###### User Blog
- 메인페이지조회
- Blog Detail 조회 
- Blog 수정/저장 
- Draft 작성 수정 저장 
- Draft 배포 

