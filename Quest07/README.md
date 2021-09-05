# Quest 07. 여러 대의 서버로 서비스 하기

## Introduction
* 이번 퀘스트는 여러 대의 서버를 통해 안정적인 서비스를 만드는 방법을 다룹니다.

## Topics
* Switch
  * L2 Switch
  * L3 Switch
  * L4 Switch
  * L7 Switch
* Load Balancer
  * 리스너
  * 대상그룹
  * 상태 검사

## Resources
* [ELB](https://aws.amazon.com/ko/elasticloadbalancing)
* [Single point of failure](https://en.wikipedia.org/wiki/Single_point_of_failure)

## Checklist
* Single Point of Failure는 어떤 개념일까요?
* 여러 대의 서버로 서비스할 때의 장점은 무엇일까요? 또 주의해야 할 점은 무엇일까요?
* AWS에서 제공하는 로드밸런서에는 어떤 종류가 있나요? 각각의 용도는 무엇일까요?
* AWS 로드밸런서의 리스너 규칙을 이용해 어떤 일들을 할 수 있을까요?
* AWS의 여러 리전(서울, 도쿄 등)으로 로드밸런싱을 하는 것도 가능할까요?

## Quest
* EC2 인스턴스를 한 대 더 늘리고, 앞단에 ELB를 사용하여 두 대를 로드밸런싱 해 보세요. 직전 퀘스트에서 만들었던 컨테이너를 이용하시면 됩니다.
* 두 대의 서버 모두에 번갈아 요청이 들어오는지 확인해 보세요.
* 만약 한 대의 서버의 컨테이너를 내렸을 때, 자동으로 나머지 한 대의 서버로만 요청이 가게 되도록 설정해 보세요. Application Load Balancer를 이용해서 구현해 봅시다!

## Advanced
* Sticky Session이란 어떤 개념일까요?
