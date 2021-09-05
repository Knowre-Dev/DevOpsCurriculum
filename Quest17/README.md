# Quest 17. 서비스의 운영 (1): 서버 들여다 보기

## Introduction
* 이번 퀘스트에서는 서비스 운영을 위한 리눅스 커맨드와 모니터링에 대해 다루겠습니다.

## Topics
* 리눅스의 커맨드들: `lsof`, `df`, `top`, `free`, `nmon`, `iostat`, `ifconfig`, `crontab`
* Cloudwatch
* Grafana

## Resources
* [20 Command Line Tools to Monitor Linux Performance](https://www.tecmint.com/command-line-tools-to-monitor-linux-performance/)
* [Amazon CloudWatch 지표 사용](https://docs.aws.amazon.com/ko_kr/AmazonCloudWatch/latest/monitoring/working_with_metrics.html)
* [Getting started with Grafana](https://grafana.com/docs/grafana/latest/getting-started/getting-started/)

## Checklist
* 위 Topics의 리눅스 커맨드들은 어떤 커맨드인가요? 운영 중 어떤 상황에 쓸 수 있을까요?
* Cloudwatch는 어떤 서비스인가요? 우리가 구축한 시스템 관련하여, Cloudwatch에서 제공하는 메트릭들 중 유용한 것은 어떤 것이 있을까요?
* Grafana는 어떤 역할을 하는 툴인가요? Grafana 외에 비슷한 일을 하는 툴은 무엇이 있을까요?

## Quest
* 리눅스 시스템의 모니터링이나 상태 파악을 위한 커맨드를 연습해 보세요.
* Grafana를 통해 지금까지 구축한 전체 시스템에 대한 모니터링 페이지를 구축해 보세요.
* 서버가 비정상 상태일 때, 혹은 서버의 대수에 변화가 있을 때 운영자가 알 수 있도록 슬랙을 통해 Alert을 설정해 보세요.

## Advanced
* 리눅스 시스템을 웹 서버 용도로 사용할 때, 서비스하는 트래픽의 특성에 따라 CPU, 메모리, 파일 I/O 중 어떤 것들이 중요하게 될까요?
