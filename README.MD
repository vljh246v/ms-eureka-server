# 서비스 디스커버리 (서버)

## 의존성 추가
```xml
<dependency>
    <groupId>org.springframework.cloud</groupId>
    <artifactId>spring-cloud-starter-netflix-eureka-server</artifactId>
</dependency>
```

* 서버 API 구성
    * 등록된 서비스 목록을 수집하기 위한 API
    * 새로운 서비스 네트워크 위치 주소와 함께 등록하기 위한 API
    
* {host}:{port} 를 통해 UI 대시보드 확인 가능
* http://localhost:8761/eureka/apps 을 통해 서버 목록 호출 가능