## π‘ μΌνλͺ° μλλ‘μ΄λ μ± λ§λ€κΈ°

### νλ‘μ νΈ λͺ©μ : 
π μ½νλ¦° + μ€νλ§νλ μμν¬ = μ½νλ§ κΈ°μ λ‘ μΌνλͺ° μ± λ§λ€κΈ° κ΅¬ννκΈ° 


### μ¬μ©κΈ°μ 
+ Kotlin
+ Spring Framework
+ Gradle
+ MySQL

### νμ€νΈ λ°°ν¬
+ AWS 

### DDD (λλ©μΈ μ£Όλ μ€κ³)

### κ°λ°νκ²½
+ InteliJ
+ Android Studio 3.3.2


### νΈλ¬λΈ μ΄μ

#### β Run Error
<details>
<summary>Run μ€ν μ€λ₯</summary>
<div markdown="1">

- Error starting ApplicationContext. To display the conditions report re-run your application with 'debug' enabled.
- μμΈ: aplication.yml μ€μ μ μνμ¬ μ€λ₯ λ°μ

### π‘ ν΄κ²° λ°©λ²
<details>
<summary>Run μ€ν μ€λ₯ κ°μ </summary>
<div markdown="1">

  
#### application.yml
~~~
spring:
  datasource:
    url: jdbc:mysql://127.0.0.1:3306/μ€ν€λ§ λͺ?useUnicode=true&serverTimezone=UTC
    username: μμ΄λ
    password: λΉλ°λ²νΈ
    data-username: μμ΄λ
    data-password: λΉλ°λ²νΈ
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
