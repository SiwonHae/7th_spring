### java의 Exception 종류들
- 컴파일 시점에 발생하는 예외로 Checked Exception이 있다. Exception을 상속받으며 IOException, SQLException, ClassNotFoundException 등이 있다.
- 런타임 시 발생하는 예외로 Unchecked Exception이 있다. RuntimException을 상속받으며 NullPointerException, ArrayIndexOutOfBoundsException 등이 있다.
- 애플리케이션 코드에서 직접 처리하지 않는 예외로 Error가 있다. OutOfMemoryError, StackOverflowError 등이 해당된다.
### @Valid
- 객체의 필드 값이 유효한지 검증할 때 사용된다.