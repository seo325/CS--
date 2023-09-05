1. RESTful API 
    resource ,method represntaion 3가지로 사용 
    Resource(자원, URI)
    Method(요청 방식, GET or POST 등)
    Representation of Resource(자원의 형태, JSON or XML 등)

2. 프레임워크와 리이브러리 
    라이브러리 ; 사용자가 흐름에 대한 제어가 필요한 상황 
    프레임워크 ; 전체적인 흐름을 자체적 제어


3. MSA란? 
    장점 - 일부 서비스에 장애가 발생하더라도 전체서비스에 장애 발생하지 않는다
        - 각각의 서비스들은 서로 다른 언어와 프레임웜크로 구성
        - 서비스 확장 용이
    단점 - 서비스 분리되어 테스팅이나 트랜잭션 처리 어렵다 
        - 서비스간 api 통신으로 그에 대한 비용
        - 호출이 연속적이기 때문에 디버깅 및 에러 트레이싱 어렵다 




        