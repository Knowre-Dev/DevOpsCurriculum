# Quest 12. DNS와 HTTPS

## Introduction
* 이번 퀘스트에서는 DNS에 대한 더 깊은 이해와 함께, HTTPS와 TLS에 대해 알아보겠습니다.

## Topics
* DNS
* Route53
* HTTPS
* TLS
* Certificate Manager
* HTTP/3

## Resources
* [DNS Servers](https://www.redhat.com/sysadmin/dns-domain-name-servers)
* [What is DNS](https://aws.amazon.com/ko/route53/what-is-dns/)
* [Route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/getting-started.html)
* [HTTPS protocol explained](https://anushadasari.medium.com/the-https-protocol-explained-under-the-hood-c7bd9f9aaa7b)
* [TLS](https://www.internetsociety.org/deploy360/tls/basics/)
* [AWS Certificate Manager](https://docs.aws.amazon.com/ko_kr/acm/latest/userguide/acm-overview.html)
* [HTTP3 explained](https://http3-explained.haxx.se/ko)

## Checklist
* DNS의 레코드에는 어떤 종류들이 있나요? 이 종류들은 어떤 용도로 쓰일까요?
* Route53의 Alias 기능이란 무엇인가요?
* 대부분의 최신 브라우저에서는 HTTP 대신 HTTPS가 권장됩니다. 이유가 무엇일까요?
* HTTPS와 TLS는 어떤 식으로 동작하나요? HTTPS는 어떤 역사를 가지고 있나요?
* HTTPS의 서비스 과정에서 인증서는 어떤 역할을 할까요? 인증서는 어떤 체계로 되어 있을까요?
* HTTP/3은 기존 버전과 어떻게 다를까요? HTTP의 버전 3이 나오게 된 이유는 무엇일까요?

## Quest
* `xxx.knowre.com`에 해당하는 커스텀 도메인을 하나 부여해 드리겠습니다. Route53을 활용하여 이 도메인의 자체 네임서버를 구축해 보세요.
* Cloudfront에 연결된 정적인 웹사이트와 ECS에서 서비스 되는 API 서버가 위 도메인으로 서비스 되도록 설정과 연결해 보세요.
* Certificate Manager를 통해 인증서를 만들어 보세요. 그리고 위 두 서비스가 HTTPS로 서비스될 수 있도록 바꿔 보세요.
* HTTP로 접속했을 때 HTTPS로 리다이렉트 되도록 설정해 보세요.

## Advanced
* DNS의 TTL은 무엇인가요? 실제 리얼 월드에서는 이 DNS의 TTL이 어떻게 동작하고 있을까요?
* 사용중인 OS에서 인정하는 Root CA에는 어떤 기관들이 있을까요? 만약 이 기관중 하나의 인증서 키가 유출된다면 어떤 일이 일어날까요?
