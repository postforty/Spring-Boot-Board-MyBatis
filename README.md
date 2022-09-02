## Spring Boot 웹 프로젝트 - 게시판 

+ 기술 스택
  + Framework: Spring Boot
    + Type: Gradle
    + Packaging: War(Web application Archive)
    + Java Version: 8
    + Language: Java
    + Dependencies
      + DevTools
      + JPA
      + MySQL
      + MyBatis
      + Thymeleaf
      + Web
      + Lombok
      + Logback
  + DB: MySQL 
  
+ 개발 내용
  + 게시글 목록 조회
  + 게시글 등록
  + 게시글 상세 화면
  + 게시글 수정
  + 게시글 삭제
  + 파일 첨부 및 다운로드
  
+ 성과
  + 데이터베이스 연동 관련 Hikari CP, MyBatis 사용
  + CRUD 구현
  + Logback slf4j를 이용한 로그 출력
  + Log4JDBC로 쿼리 로그 정렬
  + HandlerInterceptorAdapter로 인터셉터 구현
  + AOP 이용한 Transaction
  + @ConrtrollerAdvice 이용한 예외 처리
  + Apache의 Common Fileupload 라이브러리 활용한 파일 업로드
  
+ 참고 자료
  + 김인우. (2019). 스프링 부트 시작하기. 프로그래밍인사이트
