## 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
컨테이너 기술은 실행에 필요한 모든 파일을 포함한 전체 실행 환경에서 애플리케이션을 패키징하고 격리할수있는 기술이다. 전체 기능을 유지하면서 컨테이너화된 애플리케이션 환경을 쉽게 이동할수있다. 또한 보안적으로 컨테이너 파이프라인에 보안을 구축하고 인프라를 보호하여 컨테이너의 안전성과 신뢰성을 보장할수있다. 컨테이너를 활용하면 개발자와 운영팀간의 담당영역을 분리하여 충돌을 줄일수있고, 개발과 배포를 간소화한다.

## 도커란 무엇입니까? (100자 이내로 요약)
도커는 Go 언어로 작성된 리눅스 컨테이너 기반의 오픈소스 가상화 플랫폼이다. 쉽게 컨테이너로 실행하고 관리할수있게 해주는 것으로, 다양한 이유로 계속해서 서버환경이 바뀌는 경우를 해결할수있게 되었다. 

## 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?

- **도커 파일** : 도커파일은 도커 이미지를 생성하기 위한 설정파일이다. 파일에 작성된 명령을 통해서 이미지를 생성한다.

- **도커 이미지** : 컨테이너의 설계도라고 생각할수있다. 변형이 불가능하고, 컨테이너없이 존재가 가능하다. 컴퓨팅 자원을 필요로 하지않고, 단한번만 생성이 가능하다.
 
- **도커 컨테이너** : 도커 컨테이너는 도커이미지의 인스턴스라고 볼수있다. 이미지를 실행시켜야 존재하는 것이로, 실행을 위해 컴퓨팅 자원이 필요하고, 같은 이미지로 부터 다수의 컨테이너를 생성가능하다.