지금의 요구사항을 만족하긴 하지만 하나의 객체로 생성된 도메인들은 어디에서 어떻게 사용될지 모르니
역할과 책임을 분명하게 가져가는게 좋습니다 😄
이 이름의 검증에 대한 부분은 Car쪽에서 가져가는게 맞는 것 같아요
Car의 이름이니까요 🙇 -> ok

핵심 비지니스 로직을 가지는 객체를 domain 패키지,
UI 관련한 객체를 view 패키지에 구현한다.

MVC 패턴 기반으로 리팩토링해 view 패키지의 객체가
domain 패키지 객체에 의존할 수 있지만,
domain 패키지의 객체는 view 패키지 객체에
의존하지 않도록 구현한다.

고칠부분
ResultView에 있는 findWinner 책임 가지는
RoundRecords(List<RoundRecord>를 가지는 일급 컬랙션) 만들고 winner를 찾는 로직 추가
전반적인 코드 리팩토링 -> ok