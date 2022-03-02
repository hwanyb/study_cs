# HTTP & HTTPS
## HTTP란 무엇인가요?
HTTP란 `Hyper Text Transfer Protocol`의 약자로, 풀어서 설명하면 하이퍼텍스트를 전송하기 위해 사용되는 통신규약입니다.
즉 인터넷에서 HTML과 같은 **문서를 웹브라우저가 웹서버에 요청할 때에의 규칙**이라고 할 수 있습니다.
- 하이퍼텍스트(Hyper Text)란?<br />
하이퍼텍스트는 **한 문서에서 다른 문서로 이동할 수 있도록 하는 초월적인(Hyper) 글**(Text)입니다.
- 프로토콜(Protocol)이란?<br />
프로토콜은 원래 외교상의 언어로써 의례나 국가간의 약속을 의미하는데, 네트워크에서는 어떤 시스템이 다른  시스템과 통신을 원활하게 수용하도록 해주는 `통신 규약, 약속`이라고 할 수 있습니다.
## HTTPS란 무엇인가요?
HTTPS는 기본 골격이나 사용 목적 등은 HTTP와 거의 동일하지만, 데이터를 주고 받는 과정에 `보안`요소가 추가되었다는 것이 가장 큰 차이점입니다.
**HTTPS를 사용하면 서버와 클라이언트 사이의 모든 통신 내용이 암호화됩니다.**
## HTTP와 HTTPS의 차이점이 무엇인가요?
HTTP는 `암호화`가 추가되지 않았기 때문에 보안에 취약한 반면, **HTTPS는 데이터 암호화가 추가된 프로토콜이기 때문에 안전하게 데이터를 주고받을 수 있습니다.**<br />
하지만 HTTPS를 이용하면, 암호화/복호화 과정이 필요하기 때문에 HTTP보다 속도가 느립니다.<br />
HTTPS는 인증서를 발급하고 유지하는 데에 추가비용이 발생합니다. 따라서 **단순 정보 조회와 같은 사이트는 HTTPS를 이용**하고, **개인정보와 같은 민감한 데이터를 주고 받는다면 HTTPS를 이용**해야 합니다.