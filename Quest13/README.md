# Quest 13. 마이크로서비스와 람다

## Introduction
* 이번 퀘스트에서는 마이크로서비스의 개념과 람다 서비스에 대해 알아보겠습니다.

## Topics
* 마이크로서비스
* Lambda
* API Gateway

## Resources
* [제프 베조스의 메일](https://news.hada.io/topic?id=638)
* [Microservices](https://www.redhat.com/ko/topics/microservices/what-are-microservices)
* [AWS Lambda](https://docs.aws.amazon.com/ko_kr/lambda/latest/dg/welcome.html)
* [API Gateway](https://docs.aws.amazon.com/ko_kr/apigateway/latest/developerguide/welcome.html)

## Checklist
* 마이크로서비스가 무엇인가요? 이러한 구조의 장점은 무엇일까요?
* AWS Lambda는 어떤 서비스일까요? 이러한 서비스는 어떤 특징을 가지고, 어디에 쓰일 수 있을까요?
  * AWS Lambda의 Cold start와 Warm start는 어떤 개념일까요? Lambda의 동시성이란 무엇일까요?
  * AWS Lambda의 Layer는 어떤 개념일까요?
* API Gateway는 어떤 서비스인가요? 어떤 설정을 할 수 있을까요?

## Quest
* AWS Lambda와 API Gateway를 이용해 새로운 웹서비스를 하나 구축해 보세요. (기존 컨테이너 기반의 서비스는 그대로 둡니다!)
* 만들어 둔 정적인 웹사이트에서, 기존 컨테이너 기반의 API에 더해 Lambda 기반의 API 역시 활용할 수 있도록 수정해 보세요.
* API Gateway를 통해 서비스 되고 있는 API가 우리만의 도메인을 가지고 HTTPS로 서비스될 수 있도록 하려면 어떻게 해야 할까요?

## Advanced
* 마이크로서비스 아키텍쳐의 단점은 무엇일까요? 이를 해결하기 위해 어떤 방법론들이 제시되고 있을까요?
* 카오스 엔지니어링이란 무엇일까요?
