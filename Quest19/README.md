# Quest 19. 스트레스 테스트

## Introduction
* 이번 퀘스트에서는 스트레스 테스트와 오토 스케일링에 대해 알아보겠습니다.

## Topics
* Stress Test
* Artillery
* AWS Auto Scaling
* Fargate Auto Scaling
* Lambda Concurrency

## Resources
* [Stress testing tutorial](https://www.guru99.com/stress-testing-tutorial.html)
* [Artillery](https://artillery.io/)
* [AWS AutoScaling](https://aws.amazon.com/ko/about-aws/whats-new/2018/01/introducing-aws-auto-scaling/)
* [Auto Scaling](https://aws.amazon.com/ko/blogs/korea/category/compute/auto-scaling/)
* [ECS Auto Scaling](https://docs.aws.amazon.com/ko_kr/AmazonECS/latest/developerguide/service-auto-scaling.html)
* [Lambda Concurrency](https://docs.aws.amazon.com/lambda/latest/dg/configuration-concurrency.html)

## Checklist
* 스트레스 테스트는 왜 하는 것일까요?
* 스트레스 테스트의 진행에는 어떤 방법론들이 있을까요?
* AWS의 Auto Scaling은 어떤 서비스일까요? Fargate에서는 어떻게 적용할 수 있을까요?
* Lambda의 동시 실행은 어떠한 개념일까요? 부하가 많은 서비스에서 이 지표를 어떻게 모니터링 해야 할까요?

## Quest
* 우리의 컨테이너 기반 서버를 일부러 약간 무겁게 만들어 봅시다. 일부러 서버의 부하를 주려면 어떤 방법이 있을까요?
* Artillery를 이용하여 스트레스 테스트 시나리오를 작성하고, 부하를 가해 보세요.
* Fargate의 Auto Scaling 기능을 설정하여, 초당 일정 이상의 부하가 걸리면 자동으로 컨테이너를 늘리고, 부하가 줄면 자동으로 컨테이너의 수를 줄이게 만들어 보세요.

## Advanced
* 실제 세상에서 자주 업데이트 되는 서비스가 있다고 할 때, 이런 서비스를 스트레스 테스트 하는 데에는 어떤 전략들이 있을까요? 각각의 전략들은 어떤 상황에서 사용될 수 있을까요?
