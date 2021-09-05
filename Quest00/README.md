# Quest 00. 데브옵스란 무엇인가

## Introduction
* 이번 퀘스트에서는 데브옵스가 무엇인지, 이러한 개념이 왜 나오게 되었는지 등에 대해 다룰 예정입니다.

## Resources
* [DevOps란 무엇입니까?](https://aws.amazon.com/ko/devops/what-is-devops/)
* [DevOps란?](https://azure.microsoft.com/ko-kr/overview/what-is-devops/)
* [DevOps](https://cloud.google.com/devops/?hl=ko)
* [DevOps](https://en.wikipedia.org/wiki/DevOps)

## Checklist
* 만약 비개발자에게 데브옵스가 무엇인지 설명하게 된다면 어떻게 설명할 수 있을까요?
* 데브옵스라는 개념 이전의 소프트웨어 개발은 어땠을까요? 어떤 요구사항을 충족하기 위해 데브옵스라는 개념이 생겼을까요?
* 데브옵스 엔지니어가 따로 존재하는 조직과 따로 존재하지 않는 조직은 각각 어떤 장단점을 가지고 있을까요?

## Quest
* 발급받은 AWS 계정에 접속해 봅니다.
* 본인의 루트 AWS 엑세스 키 ID와 비밀 엑세스 키를 생성하고, 본인의 로컬 머신에 저장해 놓습니다.
* 새로운 무언가를 생성하지는 않은 상태에서, 어떤 것들이 있는지 둘러봅니다!
* 과제 리뷰용 IAM 계정을 하나 만들어서 저에게 알려 주세요.
  * 콘솔의 IAM 메뉴에 들어가서, 왼쪽의 `엑세스 관리` -> `사용자`에 들어가서 `사용자 추가`를 클릭합니다.
  * 사용자 이름에 `kcho@knowre.com`을 입력하고, 엑세스 유형에 `프로그래밍 방식 엑세스`와 `AWS Management Console 액세스`를 모두 클릭합니다.
  * `자동 생성된 비밀번호`와 `비밀번호 재설정 필요`를 체크합니다.
  * `권한 설정`에서 `기존 정책 직접 연결`을 선택한 뒤, `AdministratorAccess`를 체크하고, 하단의 `다음:태그`와 `다음:검토`를 계속해서 누른 뒤, 사용자를 만듭니다.
  * `액세스 키 ID`와 `비밀 액세스 키`, `비밀번호`, 그리고 위의 안내에 써 있는 접속을 위한 `https://[12자리숫자].signin.aws.amazon.com/console` URL을 저에게 보내 주시면 됩니다!

## Advanced
* SRE(Site Reliability Engineering)는 어떤 개념일까요?
* 미래의 데브옵스 직무는 어떻게 변화할까요? 여러 가지 미래를 상상해 봅시다!
