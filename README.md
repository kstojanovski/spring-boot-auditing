# Spring Boot Auditing
# Introduction
This section is dedicated to the auditing solutions in Spring Boot applications.
There are auditing on different levels:
  - the persistence layer, when executing CRUD operations.
  - inbound request i.e. via a REST endpoint, when this service is called over http/s.
  - authentication/authorization, on user login, or service authorization.
# Source
The following links show examples of implementing the approaches:
- General
  - https://docs.spring.io/spring-boot/reference/actuator/auditing.html
  - https://www.jvt.me/posts/2022/01/13/spring-boot-actuator-audit/
  - https://docs.spring.io/spring-data/rest/reference/data-commons/auditing.html
- Security
  - General
    - https://www.baeldung.com/spring-boot-authentication-audit
    - https://www.youtube.com/watch?v=lGULtrZqk-c
  - AuditorAware
    - https://medium.com/thefreshwrites/jpa-auditing-spring-boot-spring-security-575c77867570
- JPA Auditing
  - General
    - https://www.techgeeknext.com/spring-boot/spring-boot-audit-log-jpa
  - AuditorAware
    - https://docs.spring.io/spring-data/jpa/reference/auditing.html
    - https://www.javaguides.net/2018/09/spring-data-jpa-auditing-with-spring-boot2-and-mysql-example.html
  - Hibernate Envers
    - https://www.baeldung.com/database-auditing-jpa
    - https://www.youtube.com/watch?v=5CT512srEYQ
    - https://www.youtube.com/watch?v=W1Rtn28lHU8
  - JaVers
    - https://www.baeldung.com/spring-data-javers-audit
