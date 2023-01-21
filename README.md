# inflearn-toby-springboot

# 스프링 부트 시작하기
## 스프링 부트 소개
스프링 부트(Spring boot)는 스프링을 기반으로 실무 환경에 사용 가능한 수준의 독립실행형 애플리케이션을 복잡한 고민 없이 빠르게 작성할 수 있게 도와주는 여러가지 도구의 모음이다.
```
스프링과 스프링 부트는 다르다
```
## 스프링 부트의 핵심 목표
- 매우 빠르고 광범위한 영역의 스프링 개발 경험을 제공
- 강한 주장을 가지고 즉시 적용 가능한 기술 조합을 제공하면서, 필요에 따라 원하는 방식으로 손쉽게 변형 가능
- 프로젝트에서 필요로 하는 다양한 비기능적인 기술(내장형 서버, 보안, 메트릭, 상태 체크, 외부 설정 방식 등)
- 코드 생성이나 XML 설정을 필요로 하지 않음


## 컨테이너리스 웹 애플리케이션 아키텍처 (Containerless)
컨테이너의 관리를 신경쓰지 않아도 되는 아키텍처
스프링 레거시에서는 스프링 컨테이너가 서블렛 컨테이너(ex: tomcat)이 실행된 다음에 실행이 되는데, 이 서블렛 컨테이너가 오래된 기술이기도 해서 여러가지 배경 지식이 필요 했음 
서블렛 컨테이너의 설정정보 web.xml, war, deploy(너무 다양한 방식) 들이 너무 많고 다양하기 때문에 초기 구성에 너무 많은 시간을 씀
톰캣만 사용하면 그나마 괜찮은데 톰캣이 아닌 환경이라면 또 그 서블릿 컨테이너에대한 지식이 요구됨.
스프링 부트는 이와 같은 문제를 main메소드를 통해 내장된 톰캣서버를 구동하게끔 바꿈

## Opinionated(의견이 굉장히 강한)
기존 스프링 
- 극단적인 유연함 추구
- 다양한 관점을 수용
- Not opinionated
- 수많은 선택지를 다 포용

스프링 부트
- Opinionated : 자기 주장이 강한, 자기 의견을 고집하는, 독선적인
- 일단 정해주는 대로 빠르게 개발하고 고민은 나중에
- 스프링을 잘 활용하는 뛰어난 방법을 제공



