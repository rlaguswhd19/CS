# SpEL(Spring Expression Language)

스프링 EL이란?

* 객체 그래프를 조회하고 조작하는 기능을 제공한다.
* Unified EL과 비슷하지만, 메소드 호출을 지원하여, 문자열 템플릿 기능도 제공한다.
* OGNL, MVEL, JBOss EL등 Java에서 사용할 수 있는 여러 EL이 있지만,  SpEL은 모든 스프링 프로젝트 전반에 걸쳐 사용할 EL로 만들었다.
* 스프링 3.0부터 지원



문법

* #{"표현식"}
* ${"프로퍼티"}
* 표현식은 프로퍼티를 가질 수 있지만, 반대는 안 됨.
  * #{${my.data} + 1}
* 레퍼런스 참고



실제로 어디서 사용하나?

* @Value 애노테이션
* @ConditionalOnExpression 애노테이션
* 스프링 시큐리티
* 스프링 데이터
  * @Query
* Thymeleaf







