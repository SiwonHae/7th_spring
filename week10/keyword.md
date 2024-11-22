### Spring Security
- Spring에서 보안을 제공하는 프레임워크로 인증과 인가의 기능을 다룬다. 주요 기능으로는 인증, 인가, 세션 관리, CSRF 보호, 암호화 및 비밀번호 처리 등이 있다.

### 인증(Authentication)과 인가(Authorization)
- 인증 : 사용자의 신원을 확인하는 과정이다. 즉, 사용자가 누구인지 확인하는 과정으로, 보통 로그인 시 사용자 이름과 비밀번호를 통해 이루어진다. 인증이 성공하면 사용자는 시스템에 접근할 수 있는 자격을 얻는다.
- 인가 : 인증된 사용자가 특정 리소스나 기능에 접근할 수 있는 권한이 있는지를 결정하는 과정이다. 예를 들어, 관리자 권한을 가진 사용자만 특정 데이터를 수정할 수 있도록 설정하는 것이 이에 해당된다.