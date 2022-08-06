## 💡쇼핑몰 안드로이드 앱 만들기

### 프로젝트 목적: 
코틀린 + 스프링프레임워크 = 코프링 기술로 쇼핑몰 앱 만들기 구현하기 


### 사용기술
+ Kotlin
+ Spring Framework
+ Gradle
+ MySQL

### 개발환경
+ InteliJ


### 트러블 이슈

#### ✔ Run Error
<details>
<summary>Run 실행 오류</summary>
<div markdown="1">

- Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
- 원인: aplication.yml 설정을 안하여 오류 발생

### 💡 해결 방법
<details>
<summary>Run 실행 오류 개선</summary>
<div markdown="1">

  
#### application.yml
~~~
spring:
  datasource:
    url: jdbc:mysql://127.0.0.1:3306/스키마 명?useUnicode=true&serverTimezone=UTC
    username: 아이디
    password: 비밀번호
    data-username: 아이디
    data-password: 비밀번호
    driver-class-name: com.mysql.jdbc.Driver
  jpa:
    hibernate:
      ddl-auto: update
    database-platform: org.hibernate.dialect.MySQL5InnoDBDialect
~~~

</div>
</details>  

</div>
</details>  
