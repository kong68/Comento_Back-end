# 2Week - API 가이드 문서 작성

1) REST?
   - 웹에 존재하는 모든 이미지, 동영상, DB에 고유한 URL을 부여해 자원을 정의하고 자원에 대한 주소를 지정하는 방법론

2) API?
   - 응용 프로그램에서 사용할 수 있도록 운영체제나 프로그래밍 언어가 제공하는 기능을 제어할 수 있게 만든 인터페이스
  
3) 인터페이스?
   - 컴퓨터 시스템끼리 정보를 교환하는 공유 경계

4) REST API?
   - REST 특징 + API 제공
   - 자원: URL 형태
   - 행위: GET/POST/DELETE/PUT
   - 표현: JSON, XML
   - 이미지 출처: https://velog.io/@taylorkwon92/REST-API%EB%9E%80
     ![image](https://github.com/crazy-oung/planttech/assets/74444856/66aed414-7f2d-44d9-ba92-2e4b00ff8b5b)

5) HTTP 통신에 관하여
   - 네트워크 통신을 할때 "통신 프로토콜" HTTP 통신은 HTTP 프로토콜을 활용하여 Request, response 로 나뉜다.

6) HTTP Method
   - GET, POST, PUT, DELETE etc.
   - GET: 정보를 받아올 때 사용
   - POST: tofhdns wkdnjs todtjd
  
7) HTTP의 대표적 상태 코드
   - 2XX: 정상적으로 응답
   - 4XX: 클라이언트가 요청을 잘못했을 때
   - 5XX: 서버에서 알 수 없는 에러 발생
     
8) 브라우저에 URL입력 요청 서버 응답 과정
   - **URL 입력:** 사용자는 브라우저의 주소창에 웹 페이지의 URL을 입력합니다. URL은 Uniform Resource Locator의 약자로, 특정 자원이 위치한 주소를 나타냅니다.
   - **DNS 조회 (Domain Name System):** 브라우저는 입력한 URL에서 호스트명을 추출하고, 이를 IP 주소로 변환하기 위해 DNS 서버에 쿼리를 보냅니다. DNS는 도메인 이름과 IP 주소를 매핑하는 역할을 합니다.
   - **TCP 연결:** 브라우저는 서버의 IP 주소로 TCP/IP 연결을 시도합니다. 이 단계에서는 클라이언트(브라우저)와 서버 간에 안정적인 연결이 설정됩니다.
   - **HTTP 요청 전송:** 브라우저는 서버에게 웹 페이지나 자원을 요청하는 HTTP 요청을 생성하고, 이를 서버로 전송합니다. HTTP 요청은 GET, POST, PUT, DELETE 등의 메서드를 사용하여 요청의 목적을 명시합니다.
   - **서버 처리:** 서버는 받은 HTTP 요청을 해석하고, 요청된 자원을 찾거나 필요한 작업을 수행합니다. 이 단계에서는 데이터베이스 조회, 비즈니스 로직 실행 등이 포함될 수 있습니다.
   - **HTTP 응답 전송:** 서버는 클라이언트에게 HTTP 응답을 생성하고, 이를 클라이언트로 전송합니다. 응답에는 상태 코드, 헤더, 본문 등이 포함됩니다.
   - **TCP 연결 종료:** 클라이언트와 서버 간의 TCP 연결이 안전하게 종료됩니다. 이후 클라이언트는 받은 응답을 처리하여 화면에 웹 페이지를 표시하거나 필요한 동작을 수행합니다.

참고자료
- https://velog.io/@taylorkwon92/REST-API%EB%9E%80
- https://steemit.com/kr/@yahweh87/it-api
- https://yummy0102.tistory.com/105
