# Quest 15. 모노리포와 린팅

## Introduction
* 이번 퀘스트에서는 모노리포의 개념, 그리고 코드 파이프라인의 단계 중 하나인 린팅에 대해 다루겠습니다.

## Topics
* Monorepo
* Lerna
* Lint (eslint)

## Resources
* [Monorepo의 장점과 단점](https://medium.com/better-programming/the-pros-and-cons-monorepos-explained-f86c998392e1)
* [Lerna](https://github.com/lerna/lerna)
* [Lint](https://en.wikipedia.org/wiki/Lint)
* [ESLint](https://eslint.org/)

## Checklist
* 모노리포는 어떤 개념인가요? 모노리포를 적용할 때의 장단점은 무엇일까요?
* Lerna는 어떤 역할을 하는 소프트웨어인가요?
* 린팅은 어떤 개념인가요? 린팅을 할 때의 장점은 무엇일까요? 자바스크립트의 경우 어떻게 구현하는 것이 좋을까요?

## Quest
* 지금까지 만든 세 개의 자바스크립트 코드베이스(컨테이너 기반 API, 람다 기반 API, 정적 웹사이트)를 Lerna를 이용해 하나의 리포로 합쳐 보세요.
* eslint의 기본 설정을 이용해 이 코드들을 린팅해 보세요. 모든 패키지를 명령 하나로 한 번에 린팅하려면 어떻게 해야 할까요?

## Advanced
* Lerna 외의 모노리포 툴에는 어떤 것들이 있을까요? Lerna와는 어떤 점이 다를까요?
* ESLint는 내부적으로 어떤 원리로 코드를 분석할까요? 정적 분석이란 무엇일까요?
