


- 유저 테이블 
	- 유저 id
	- 유저 key 값 ?
	- 생성일자
---
- 포트폴리오-work exp
	- 유저 id 외래키 
	- 생성일자
	- last modi 
	- experiences - project
- 포트폴리오 - introduce
	- 유저 id 외래키 
	- 생성일자
	- last modi 
	- introduce. markdown ?
- 포트폴리오 - skills 
	- 유저 id 외래키
	- 생성일자
	- last modi 
	- skills array 
- 포트폴리오 - profile 
	

- 유저 포트폴리오 
- 블로그 
	- Post 

## 테이블 설계 

## 도메인 기능 설계
- mallog.com
	- [1차] mallog의 about 페이지 및 pwa 다운로드 및 어플 다운로드 소개 
	- [2차]mallog 메인페이지 Hot 게시물 및 카테고리 검색 
	- [2차] 퀘스천 목록
- mallog.com/devlog
	- [2차]mallog 개발 devlog
- mallog.com/[user]
  유저 블로그 메인페이지
	- 블로그 그래프
	- github 잔디 + 블로그 파도
	- 블로그 카테고리 그래프 
- mallog.com/[user]/portfoilo
	- [2차] 유저 포트폴리오 페이지 
- mallog.com/[user]/settings
	- [2차]포트폴리오 테마 설정
	- [2차]블로그 테마 설정 
- mallog.com/allocation?id=[postId]&from=[questionId]
	- 에디팅 페이지 
	- markdown 형태입력 
	- 퀘스천 기능
	- 링크기능
	- 이미지 삽입 
- mallog.com/[user]/subscribe 
- mallog.com/[user]/draft
	- mallog.com/[user]/write?