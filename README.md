# flutter-playground

## DART

### Compiler

- JIT (Just In Time)
  - 실행 시점에 코드를 컴파일
  - 빌드 시간이 빠름
  - Hot Reload, Hot Restart 가능
- AOT (Ahead Of Time)
  - 미리 컴파일
  - 바이너리 파일 생성
  - 빌드 시간이 오래 걸림
  - 실행 시간이 빠름
  - 배포 가능

### Type

- String
  - ''로 감싸서 사용
  - $변수명으로 변수 사용 가능
- var
  - 자료형을 추론하여 할당
  - 자료형이 결정되면 변경 불가
  - typescript의 let과 유사
- dynamic
  - 자료형도 동적으로 변경 가능
  - typescript의 any와 유사
- nullable
  - 자료형 뒤에 ?를 붙여서 null을 허용
  - 자료형 뒤에 !를 붙여서 null을 허용하지 않음
  - ??: null일 경우 대체할 값을 지정
    - ex) var a = b ?? 0;
    - b가 null이면 0을 대입
