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