# Quest 04. 나의 첫 웹 서비스

## Introduction
* 이번 퀘스트에서는 웹 서비스를 만드는 기초적인 방법과 구성에 대해 알아보겠습니다.

## Topics
* 데몬
* 포트와 소켓
* 프록시(리버스 프록시, 포워드 프록시)

## Resources
* [Daemon Process](https://www.quora.com/What-is-a-daemon-process-in-Linux)
* [Reverse Proxy](https://www.nginx.com/resources/glossary/reverse-proxy-server/)

## Checklist
* 서버 환경에서 데몬이란 무엇일까요? node.js 서버를 데몬으로 만들려면 어떻게 해야 할까요?
* nginx와 같은 리버스 프록시 서버를 사용하는 이유는 무엇일까요?

## Quest
* vi를 이용하여, node.js의 3000번 포트로 기본적인 웹서버를 만든 후 띄워 보세요.
* 로컬 머신을 통해 띄운 웹서버의 3000번 포트에 접속해 보세요. AWS 콘솔에서 보안 그룹을 조정하려면 어떻게 해야 할까요?
* 서버의 앞쪽에 nginx를 설치하여 80포트를 통해 외부로 서비스 해 보세요.
* 서버에 터미널 접속을 종료해도 서버가 뜰 수 있게 해 보세요.

## Advanced
* 리눅스 시스템의 PID 1번 프로세스는 무엇일까요? systemd와 init.d는 어떤 시스템이고 어떤 차이가 있을까요?
* AWS의 보안 그룹 시스템은 어떻게 구성되어 있을까요? 일반적인 방화벽 시스템은 어떤 설정들이 가능할까요?
