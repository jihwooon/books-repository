## 1일
<details>
<summary>이번 스터디를 통해 무엇을 배울 수 있을까요?</summary>

</details>

## 목차
* Chapter 1 웹과 네트워크의 기본에 대해 알아보자
* Chapter 2 간단한 프로토콜 HTTP

## Chapter 1

### 1.1 웹은 HTTP로 나타낸다.
<details>
<summary>웹은 서버에 요청했을때 어떻게 리소스를 받아오는지 과정을 설명해보세요.</summary>
 
* 웹 브라우저의 주소창에 URI에 의지해 웹서버로부터 리소스 정보를 얻고 응답 받은 리소스를 웹 클라이언트로 전송한다.
* 이 과정을 결정하는 것이 HTTP이다.
</details>

### 1.2 HTTP는 이렇게 태어났고 성장했다.
<details>
<summary>웹은 만들어진 목적은 무엇인가?</summary>

* 웹은 지식 공유를 하기 위해 만들어졌다.
</details>

### 1.3 네트워크의 기본은 TCP/IP
<details>
<summary>TCP/IP가 무엇인데 네트워크 기본인가?</summary>
네트워크는 TCP/IP라는 프로토콜안에서 움직이고 있습니다.
</details>

<details>
<summary>TCP/IP가 프로토콜 집합인 이유는?</summary>
인터넷의 필요한 요소들의 프로토콜을 모은 것이 TCP/IP입니다.
</details>

<details>
<summary>TCP/IP의 계층 역활이 무엇인가요?</summary>

1. 애플리케이션 계층  
2. 트랜스포트 계층  
3. 네트워크 계층  
4. 링크 계층  
</details>

<details>
<summary>TCP/IP의 계층형으로 관리하면 이점은 무엇인가요?</summary>

1. 계층의 내부를 자유롭게 설계 할 수 있습니다.  
2. 계층화하면 설계를 편하게 할 수 있습니다.
</details>

<details>
<summary>IP/TCP/DNS는 HTTP 프로토콜에서 무슨 역활은 하는가?</summary>

* IP는 패킷을 상대방에기 전달하는 역활은 합니다.
* IP는 MAC 주소에 의존해서 통신을 합니다.

* TCP는 대용량의 데이터를 보내기 쉽게 작게 분해하여 상대에게 보내고, 정확하게 도착했는지 확인하는 역활을 담당합니다.

* DNS는 Domain Name System으로 IP 주소 대신 이름을 상대의 컴퓨터에 지정합니다.
</details>

### 1.4 URI와 URL

<details>
<summary>URI과 URL의 차이는 무엇인가?</summary>

* URI는 리소스 식별자고, URL은 Uniform Resource Locator로 웹페이지의 입력하는 주소를 뜻합니다. 
</details>


## Chapter 2 간단한 프로토콜 HTTP

### 2.1 HTTP는 클라이언트와 서버 간에 통신을 한다.

<details>
<summary>Http는 스테이트리스 상태 입니다. 이점은 무엇인가요?</summary>

* 스테이트리스는 상태를 유지하지 않는다는 점에서 서버의 CPU나 메모리 같은 리소스의 소비를 억제 할 수 있습니다.
</details>