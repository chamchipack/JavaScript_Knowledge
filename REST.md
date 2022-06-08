[REST]https://khj93.tistory.com/entry/%EB%84%A4%ED%8A%B8%EC%9B%8C%ED%81%AC-REST-API%EB%9E%80-REST-RESTful%EC%9D%B4%EB%9E%80  
[SOAP, REST]https://blog.wishket.com/soap-api-vs-rest-api-%EB%91%90-%EB%B0%A9%EC%8B%9D%EC%9D%98-%EA%B0%80%EC%9E%A5-%ED%81%B0-%EC%B0%A8%EC%9D%B4%EC%A0%90%EC%9D%80/  
[API] https://blog.wishket.com/api%EB%9E%80-%EC%89%BD%EA%B2%8C-%EC%84%A4%EB%AA%85-%EA%B7%B8%EB%A6%B0%ED%81%B4%EB%9D%BC%EC%9D%B4%EC%96%B8%ED%8A%B8/  
## REST 
Representational State Transfer의 약자로 자원을 이름(자원의 표현)으로 구분하여 해당 자원의 상태(정보)를 주고 받는 모든 것을 의미한다.
HTTP Method (GET, POST, PUT, DELETE)를 통해 해당 URI에 대한 CRUD를 적용하는것을 말한다.

## REST 구성요소
1. 자원 : HTTP URL
2. 자원에 대한 행위 : HTTP METHOD
3. 자원에 대한 행위의 내용 : HTTP Message Pay Load

## REST 장점
- HTTP 프로토콜의 인프라를 그대로 사용하므로 REST API 사용을 위한 별도의 인프라를 구축할 필요가 없다.
- 어떤 작업을 수행하는지 의도하는 바를 쉽게 파악할 수 있다.

## REST가 필요한 이유
- RESTful APIs 개발하는 가장 큰 이유는 Client Side를 정형화된 플랫폼이 아닌 모바일, PC, 어플리케이션 등 플랫폼에 제약을 두지 않는 것을 목표로 했기 때문이다.
- 즉, 2010년 이전만 해도 Server Side에서 데이터를 전달해주는 Client 프로그램의 대상은 PC 브라우저로 그 대상이 명확 했다. 그렇다 보니 그냥 JSP ASP PHP 등을 잉요한 웹페이지를 구성하고 작업을 진행하면 됐다.
- 하지만 스마트 기기들이 등장하면서 TV, 스마트 폰, 테블릿 등 Client 프로그램이 다양화 되고 그에 맞춰 Server를 일일이 만다는 것이 꽤 비효율적인 일이 되어 버렸다.
- 이런 과정에서 개발자들은 Client Side를 전혀 고려하지 않고 메시지 기반, XML, JSON과 같은 Client에서 바로 객체로 치환 가능한 형태의 데이터 통신을 지향하게 되면서 Server와 Client의 역할을 분리하게 되었다.

## 굳이 비교하자면
-페이로드는 인터넷을 통해서 전송되는 데이터입니다. 그렇기 때문에 페이로드가 ‘무거운’경우에는 더 많은 리소스가 필요합니다. REST는 HTTP와 JSON을 사용하기 때문에 페이로드의 무게를 가볍게 할 수 있습니다. 하지만 SOAP에서는 XML에만 의존합니다.
- 기존 SOAP보다 경량화되어 있기 때문에 모바일, 사물인터넷 등에 적합하다
- SOAP는 데이터포맷이 XML만 가능하고 rest는 html, xml, json 등 다양한 포맷이 가능함.

## REST API
REST의 원리를 따르는 API를 의미하는데 몇가지 규칙이 있다.
1. 동사보다는 명사를 사용한다
2. 대문자보다는 소문자를 사용한다
3. 언더바대신 하이픈을 사용한다.
4. 어떤 행위를 하는지 포함하지 않는다.

