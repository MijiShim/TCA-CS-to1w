# 📌 HW Week4 - POST 요청하기

## 1. 제목

requests 모듈을 활용하여 GET/POST 요청하기

## 2. 이름

> 김가영 (Sophia)


## 3. 제출일

> 24.09.30 (월)


## 4. 과제 목표

> GET과 POST의 차이점을 이해함으로써 적재적소에 활용하기 위함이라 생각합니다. 

## 5. GET과 POST의 차이점

> GET은 웹 페이지의 데이터만 읽어내는 데에 비해 POST는 사용자의 데이터를 서버에 전송하여 결과를 받는 방식입니다.

## 6. 응답 상태 코드 해석

> 1xx :
100 - 요청의 일부가 수신되었으며 나머지를 계속해서 보내도 된다는 의미
101 - 클라이언트가 요청한 프로토콜로 변경 중이라는 의미
2xx :
200 - 요청이 성공적으로 처리 되었다는 의미
201 - 요청이 성공적으로 처리 되었으며 새 리소스가 생성 되었다는 의미 
202 - 요청이 접수 되었지만 아직 처리가 되지 않았다는 의미
204 - 요청은 성공했지만 반환할 콘텐츠가 없다는 의미
3xx :
301 - 요청한 리소스가 영구적으로 이동되었음을 의미
302 - 요청한 리소스가 일시적으로 다른 위치에 있음을 의미
304 - 클라이언트가 캐시 된 리소스를 사용해도 된다는 의미
4xx : 
400 - 서버가 요청을 이해하지 못했음을 의미
401 - 인증이 필요함을 의미
403 - 서버가 요청을 거부했음을 의미
404 - 요청할 리소스를 찾을 수 없음을 의미
429 - 클라이언트가 너무 많은 요청을 보내고 있음을 의미
5xx :
500 - 서버에서 요청을 처리하는 중 오류가 발생했음을 의미
502 - 게이트웨이/프록시 서버가 상위 서버로부터 잘못된 응답을 받았음을 의미
503 - 서버가 일시적으로 요청을 처리할 수 없음을 의미 (서버 과부하/유지보수 중)
504 - 게이트웨이/프록시 서버가 상위 서버로부터 응답을 받지 못하였음을 의미


## 7. API 문서 활용 방법

> JSONPlaceholder는 개발자들이 API 테스트를 테스트하고 실습할 수 있는 무료 가상 API 서버입니다. 사용자가 테스트할 수 있도록 가상의 데이터를 제공한다는 특징이 
있습니다. 다양한 종류의 엔드 포인트를 제공하며 배우기 쉽고, 실습용으로 적합합니다. 