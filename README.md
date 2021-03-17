# aws-ec2-starter
aws ec2를 사용하면서 겪은 문제를 기록하는 저장소입니다.

1. AWS EC2 인스턴스 생성하기

  원하는 OS, 포트접근 설정, 트래픽 제어 설정을 직접 할 수 있다.
  
   나는 window보다는 linux계열을 사용해보고 싶어서 
  > OS : Ubuntu 18.04(LTS)
  > 
  > Instance Type : t2.micro
   
 이렇게 설정했다.

2. .pem 키 발급받아 AWS 접속

  SSH 커멘드라인 클라이언트, putty 등으로 서버에 접속 가능
  
  나는 putty를 사용했다.
  
  1) puttygen을 통해 .pem -> .ppk 로 변환
  2) ppk를 사용해 서버 접속

  참고 - [AWS 서버 접속 참고](https://www.notion.so/AWS-f9695a6e57304deaa2a43d22f3c4564f)
  
  
