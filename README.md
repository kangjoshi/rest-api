#### HATEOAS
- API로 부터 반환되는 리소스에 해당 리소스와 관련된 하이퍼 링크를 포함

##### 장점
- 기존 API의 경우 엔드포인트 URL이 정해지면 변경하기 어렵고, 만약 변경이 되면 관련된 모든 클라이언트 수정이 필요하다.
- HATEOAS의 경우 반환되는 리소스에 관련된 링크를 제공하므로 클라이언트가 사용하는 API의 엔드포인트를 API에서 결정할 수 있다.
- 클라이언트는 최소한의 API만 알고 있고 반환되는 리소스의 링크 정보로 호출할 API 주소를 결정

##### 스프링 HATEOAS
- 하이퍼링크를 스프링에서 지원
- 컨트롤러에서 리소스를 반환하기 전 해당 리소스에 링크를 추가할 수 있도록 기능 제공
