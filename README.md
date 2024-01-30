
![6](https://github.com/dino-21/step6_board_Rest2/assets/80396471/546b7ade-c508-4724-93b4-de48bfc70b58)

![2](https://github.com/dino-21/step6_board_Rest2/assets/80396471/d5c1716c-5673-4bde-83d1-c883dea2adeb)

![1](https://github.com/dino-21/step6_board_Rest2/assets/80396471/a6f849fa-64b6-4ca2-b18f-751f84ce6450)




1 ex03_rest 프로젝트 폴더 

2 ReplyVO.java 클래스의 추가


3 ReplyMapper 클래스와 XML 처리
CRUD 작업을 테스트하기 전에 tbl_reply테이블이 tbl_board 테이블과 FK(외래키)의 관계로 
처리되어 있다는 점을 기억해야한다.


4 ReplyMapper 이용한 CRUD 작업  (단일 테스트와 유사하므로 등록, 수정, 삭제, 조회 작업을 처리한다.)

5 @Param 어노테이션과 댓글목록
한 게시글에 댓글이 50개면 페이징 처리해야한다.


6 서비스영역과 Controller 처리
ReplyService.java 인터페이스 만들기

7 ReplyServiceImpl.java 만들기

8 ReplyController의 설계

9. ReplyController.java 에서 crud확인
