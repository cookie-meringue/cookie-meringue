## 안녕하세요, 머랭(김대현)입니다.

백엔드 플랫폼과 미들웨어를 개발합니다.

시스템의 동작을 깊이 이해하는 것을 좋아하고, 소프트웨어 생태계의 발전을 위해 오픈소스에 기여합니다.

## 대표 프로젝트

### [MMMQ](https://github.com/moko-meringue/mmmq)

- 토픽별 메시지 발행과 전달을 지원하는 Java 기반 메시징 미들웨어입니다.
- 생산자가 메시지를 발행하면 브로커가 해당 토픽을 구독하는 소비자에게 전달합니다.
- 메시지를 디스크에 저장하고, 소비자별 소비 위치를 체크포인트로 관리합니다.

### [Blocking Queue Analysis](https://github.com/moko-meringue/blocking-queue-analysis)

- Java의 ArrayBlockingQueue와 LinkedBlockingQueue를 비교·분석한 프로젝트입니다.
- JMH, JFR, Linux perf로 처리량, 락 경합, 캐시 관련 지표를 측정했습니다.
- 생산자와 소비자 구성에 따른 차이를 분석해 MMMQ의 큐 선택 근거를 정리했습니다.

## 오픈소스

### Spring Framework

| PR | 제목 |
| --- | --- |
| [#37448](https://github.com/spring-projects/spring-framework/pull/37448) | Make ReadOnlyHttpHeaders.headerSet values unmodifiable |
| [#37447](https://github.com/spring-projects/spring-framework/pull/37447) | Update `CompositeFilter.destroy()` Javadoc link |
| [#37445](https://github.com/spring-projects/spring-framework/pull/37445) | Destroy all filters in `CompositeFilter` despite failures |
| [#37431](https://github.com/spring-projects/spring-framework/pull/37431) | Copy query parameter lists when building UriComponents |
| [#37430](https://github.com/spring-projects/spring-framework/issues/37430) | Destroy all filters in `CompositeFilter` even if one fails |
| [#37322](https://github.com/spring-projects/spring-framework/pull/37322) | Fix cached ID reuse after commit failure in MySQLMaxValueIncrementer |
| [#37321](https://github.com/spring-projects/spring-framework/pull/37321) | Fix connection leak in MySQLMaxValueIncrementer |
| [#37296](https://github.com/spring-projects/spring-framework/pull/37296) | Align DispatcherServlet bean detection logs |
| [#37293](https://github.com/spring-projects/spring-framework/pull/37293) | Remove unchecked cast in DispatcherServlet |
| [#36814](https://github.com/spring-projects/spring-framework/pull/36814) | Optimize ClassNameReader.getClassName via direct ASM API |
| [#36714](https://github.com/spring-projects/spring-framework/pull/36714) | Data is lost for joined DataBuffer in DataBufferUtils |
| [#36555](https://github.com/spring-projects/spring-framework/pull/36555) | Fix incorrect Javadoc in HandlerMethodReturnValueHandlerComposite regarding caching |
