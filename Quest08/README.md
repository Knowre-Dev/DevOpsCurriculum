# Quest 08. 배포 자동화 하기

## Introduction
* 이번 퀘스트에서는 여러 대의 서버에 자동 배포를 구현하는 방법에 대해 알아보겠습니다.

## Topics
* Systems Manager
* Fargate
* Blue/Green Deployment

## Resources
* [Systems manager](https://aws.amazon.com/ko/systems-manager/)
* [AWS Fargate](https://aws.amazon.com/ko/fargate)
* [Blue-Green Deployment](https://www.redhat.com/ko/topics/devops/what-is-blue-green-deployment)

## Checklist
* AWS의 Systems Manager는 어떤 서비스인가요?
* AWS의 Fargate는 어떤 서비스인가요? 어떤 장점을 가지고 있나요?
* Blue/Green Deployment라는 것은 어떤 개념일까요?

## Quest
* AWS의 Systems Manager를 이용하여, 로컬 CLI에서 컨테이너 이미지를 배포하고 리모트 서버에서 그 이미지를 교체하여 띄울 수 있게 해 보세요. 쉘 스크립트 한 개로 이 모든 것이 이루어질 수 있게 하면 가장 좋습니다!
* 이번에는 EC2 대신 Fargate를 이용하여 같은 서비스를 구현해 보세요. 수동으로 배포하려면 어떻게 해야 할까요?
* Fargate에도 처음에 EC2에 한 배포 자동화를 구현해 보세요. 이 역시 쉘 스크립트 한 개로 이 모든 것이 이루어질 수 있게 하면 가장 좋습니다!

## Advanced
* 컨테이너 오케스트레이션이란 무엇일까요? 이를 달성하기 위한 방법으로 Fargate 외에 어떤 수단들이 있을까요?
