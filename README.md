# Streaming Monitor Admin #


### 개발환경 ###

* OS : Windows
* Language : JAVA 
* DataBase : MariaDB (Mysql) 
* DevTools : Eclipse (Spring tool Suite), HeidiSQL
* FrameWork : Spring, Bootstrap, Mybatis
* Libraries Tools : Maven

### 디렉토리 구조 ###

* src/main/java : 자바코드
* src/main/resources : 자바 코드에서 사용할 리소스
* src/test/java : 테스트 코드
* src/test/resources : 테스트 코드에서 사용할 리소스
* Libraries/Maven Dependencies : 라이브러리 관리 도구(jar)
* src : web디렉토리
* src/main/webapp/resources : 자바스크립트 및 CSS 등을 관리
* src/main/webapp/WEB-INF/classes : 컴파일된 클래스
* src/main/webapp/WEB-INF/spring : 스프링 프레임워크 및 Mybatis 환경설정 파일
* src/main/webapp/WEB-INF/views : html, jsp파일
* src/main/webapp : 외부 접근 가능
* src/main/web/WEB-INF : 외부접근 불가, Controller 를 경유해서 접근 가능
* pom.xml : maven에서 참조하는 설정 파일
* com/mwstory/smadmin/Dao : DB를 사용해 데이터를 조회하거나 조작하는 기능을 전담하는 클래스
* com/mwstory/smadmin/Interceptor : 특정 URL로 요청시 Controller로 가는 요청을 가로채는 클래스
* com/mwstory/smadmin/Map : SQL을 별도의 xml파일로 매핑하는 퍼시스턴스 프레임워크(Mybatis)
* com/mwstory/smadmin/Vo : 객체 및 사용하는 값들을 선언하는 클래스
* com/mwstory/smadmin/Controller : Model을 통해서 데이터를 가져오고, 그 제이터를 바탕으로 View를 제어해서 사용자에게 전달하는 클래스
