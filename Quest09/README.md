# Quest 09. 정적인 컨텐츠 서비스 하기

## Introduction
* 이번 퀘스트를 통해 정적인 컨텐츠의 서비스와 CDN의 개념, 그리고 HTTP 캐싱에 대해 알아보겠습니다.

## Topics
* S3
* Cloudfront
* HTTP Cache
* CORS
* Invalidation(Purging)

## Resources
* [Amazon S3](https://aws.amazon.com/ko/s3/)
* [콘텐츠 전송 네트워크(CDN)](https://www.akamai.com/ko/our-thinking/cdn/what-is-a-cdn)
* [Amazon Cloudfront](https://aws.amazon.com/ko/cloudfront/)
* [HTTP caching](https://developer.mozilla.org/ko/docs/Web/HTTP/Caching)
* [교차 출처 리소스 공유 (CORS)](https://developer.mozilla.org/ko/docs/Web/HTTP/CORS)


## Checklist
* AWS의 S3는 어떤 서비스일까요?
* AWS의 Cloudfront는 어떤 서비스일까요?
* HTTP의 캐싱은 어떤 식으로 이루어질까요?
* CORS는 무엇인가요? 어떤 헤더를 통해 구현되나요? EC2 서버나 S3에 구현하려면 어떻게 해야 할까요?

## Quest
* 만들어 둔 서버 API로부터 특정 정보를 받아 웹 서비스로 뿌려주는 클라이언트를 개발해 봅시다. 웹 브라우저의 fetch API를 이용하면 됩니다! (HTTPS는 사용하지 않아도 무방합니다)
* 이를 S3에 배포하고, Cloudfront를 통해 서비스하는 인프라를 구성해 봅시다.
* 클라이언트를 수정 배포했을 때, 수정사항이 Cloudfront를 통해 최대한 빨리 반영되게 하려면 어떻게 해야 할까요?

## Advanced
* CDN은 어떤 기술일까요? 어떤 장점이 있을까요? 어떻게 구현되는 기술일까요?
* S3의 스토리지 클래스는 어떤 것이 있을까요? 이를 통해 어떤 응용을 할 수 있을까요?
