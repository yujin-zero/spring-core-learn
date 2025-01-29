# 🍃Spring-core-Learning

이 저장소는 Spring의 핵심 원리를 이해하고 기본기를 정리한 공간입니다. 

---


**SOLID 원칙 적용**


**테스트 코드 적용**


**스프링 컨테이너, 스프링 빈 공부**
- ApplicationContext
- BeanFactory
- AnnotationConfigApplicationContext
- GenericXmlApplicationContext
- AppConfig.class
- appConfig.xml
- BeanDefinition
- @Bean
- @Configuration


**싱글톤 컨테이너 공부**
- 스프링 DI 컨테이너
- stateless 설계


**컴포넌트 스캔 공부**
- @ComponentScan
- @Component
- @Controller
- @Repository
- @Service
- @Filter


**의존관계 자동 주입 공부**
- @Autowired
- 생성자 주입
- 수정자 주입
- 필드 주입
- 일반 메서드 주입
- @RequiredArgsConstructor
- @Qualifier
- @Primary


**빈 생명주기 콜백 공부**
- InitializingBean
- DisposableBean
- @Bean(initMethod = "", destoryMethod = "")
- @PostConstruct
- @PreDestroy


**빈 스코프 공부**
- @Scope("singleton")
- @Scope("prototype")
- ObjectProvider

