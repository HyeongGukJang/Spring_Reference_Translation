1. "스프링"의 의미
용어 "봄"은 다른 맥락에서 다른 것을 의미합니다. 모든 것이 시작된 Spring Framework 프로젝트 자체를 참조하는 데 사용할 수 있습니다. 
시간이 지남에 따라 다른 Spring 프로젝트가 Spring Framework 위에 빌드되었습니다. 대부분의 경우 사람들이 "봄"이라고하면 전체 프로젝트 가족을 의미합니다. 
이 참조 문서는 기초 인 Spring Framework 자체에 초점을 맞추고 있습니다.
Spring Framework는 모듈로 나뉩니다. 애플리케이션은 필요한 모듈을 선택할 수 있습니다. 
핵심은 구성 모델 및 종속성 주입 메커니즘을 포함한 핵심 컨테이너의 모듈입니다. 
그 외에도 Spring Framework는 메시징, 트랜잭션 데이터 및 지속성, 웹을 포함한 다양한 애플리케이션 아키텍처에 대한 기본 지원을 제공합니다. 
또한 Servlet 기반 Spring MVC 웹 프레임 워크와 병렬로 Spring WebFlux 반응 웹 프레임 워크를 포함합니다.
모듈에 대한 참고 사항 : Spring의 프레임 워크 jar는 JDK 9의 모듈 경로 ( "Jigsaw")에 배포 할 수 있습니다. 
Jigsaw 지원 응용 프로그램에서 사용하기 위해 Spring Framework 5 jar에는 jar 아티팩트와 독립적 인 안정적인 언어 수준 모듈 이름 ( "spring.core", "spring.context"등)을 정의하는 "Automatic-Module-Name"매니페스트 항목이 함께 제공됩니다. 
이름 (항아리는 "."대신 "-"로 동일한 이름 지정 패턴을 따릅니다. 
(예 : "spring-core"및 "spring-context")). 물론 Spring의 프레임 워크 jar는 JDK 8 및 9+의 클래스 경로에서 계속 잘 작동합니다.