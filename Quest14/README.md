# Quest 14. 코드로 인프라 관리하기

## Introduction
* 이번 퀘스트에서는 인프라를 코드로 관리하는 법에 대해 알아보겠습니다.

## Topics
* IaC
* Terraform
  * State
  * Import
  * AWS Provider

## Resources
* [Infrastructure as Code](https://en.wikipedia.org/wiki/Infrastructure_as_code)
* [Terraform](https://www.terraform.io/intro/index.html)
* [Introducing Terraform](https://www.44bits.io/ko/post/terraform_introduction_infrastrucute_as_code)
* [Terraform state](https://www.terraform.io/docs/state/index.html)
* [Terraform Provider](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)

## Checklist
* IaC(Infra as Code)는 어떤 개념인가요? 이러한 개념이 왜 생기게 되었을까요?
* 테라폼은 어떤 소프트웨어인가요? 다른 IaC와 비교하여 어떤 장점을 가지고 있을까요?
* 테라폼의 State는 무엇일까요? 기존에 AWS 콘솔을 통해 정의된 리소스를 테라폼의 State에 가져오려면 어떻게 해야 할까요?

## Quest
* 지금까지 구축했던 다음의 인프라를 모두 삭제하고 테라폼 코드로 재구축해 보세요.
  * VPC
  * Fargate 기반의 API 서비스
  * 람다 기반의 서비스
  * S3와 Cloudfront 기반의 정적 웹사이트

## Advanced
* 테라폼 외의 IaC 툴에는 어떤 것이 있을까요? 테라폼에 비해 어떤 장점들을 가지고 있을까요?
