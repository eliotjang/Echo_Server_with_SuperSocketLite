## SuperSocketLite 라이브러리 사용 에코 서버 실습

### 기술 스택 및 학습내용
- C#으로 개발된 네트워크 통신을 구현하는 오픈 소스 라이브러리인 SuperSocketLite를 사용하여 소켓 통신 구현

### 주요 특징
- 다양한 프로토콜 지원
  - 다양한 프로토콜을 지원하여 TCP, UDP 및 기타 네트워크 통신을 위한 다양한 프로토콜을 쉽게 구현
- 이벤트 기반 프로그래밍
  - 이벤트 기반의 프로그래밍 모델을 제공하여 연결, 데이터 수신 등과 같은 이벤트에 대한 핸들링 용이
- 고성능
  - C# 언어로 작성된 SuperSocketLite는 성능 면에서도 효율적으로 동작, 대용량 데이터 처리 및 고성능 네트워크 응용 프로그램에 적합
- 유연한 확장성
  - 확장성을 고려하여 설계되어 있어서 필요에 따라 커스텀 기능 추가 및 확장 용이

### 주요 소스코드 구현
- [MainServer.cs](EchoServer/MainServer.cs)
- [ReceiveFilter.cs](EchoServer/ReceiveFilter.cs)
- [Program.cs](EchoServer/Program.cs)
 
### 참고 자료
- [SuperSocketLite 오픈 소스 라이브러리](https://github.com/jacking75/SuperSocketLite)
