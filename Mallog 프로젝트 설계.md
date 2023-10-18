
## 도메인 설계
1. /mallog/[user]
	- 유저의 Github 내용과 Mallog 카테고리 서머리를 표로 나타내고
	- 유저의 Github 잔디와 Mallog 잔디를 노출해주고 
	- 유저가 작성한 도큐먼트의 카테고리 별로 어떤 문서를 작성하고 참고하고 있는지 Graph 
		- Graph로 네비게이팅도 가능하게 만든다. 
2. /mallog/[user]/[content]
	- markdown 형식의 컨텐츠가 노출됨 
	- 내 글이 아니라면 (구독버튼 있음)
3. /mallog/[user]/write?content-id=[cid]
	- markdown editor
	- markdown meta data editor
	- linking
	- categorizing
4. /mallog
	- 유저 관심있어 하는 글 보여주는 섹션
		- 유저 github내용과, 가장 활발한 유저의 카테고리 기준
	- 최근 구독한 글의 카테고리 기준 
	- 검색기능 

5. Global
	- PWA를 이용한 푸시, 오프라인 에디팅 기능 구현

## 필요 서비스 api
1. Github API
	1. NextAuth를 이용한 OAuth
	2. user profile
	3. user 잔디
	4. user repo summary
2. Mallog (구현 필요)
	1. 유저 테이블 및 암호화
		1. 유저테이블
		2. 유저 <-> 구독 
		3. 유저 <-> 서머리
	2. 블로그
		1. 컨텐츠 식별자 테이블
		2. 컨텐츠 식별자 테이블 <-> 컨텐츠 식별자 테이블
		3. 컨텐츠 식별자 테이블 <-> 카테고리 테이블
		4. 컨텐츠 식별자 테이블 <-> 컨텐츠 메타데이터 테이블 
		5. ... etc
		