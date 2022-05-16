## Annotation 종류
- @Getter
    - 선언된 모든 필드의 get메소드 생성
- @RequiredArgsConstructor
    - final 필드가 포함된 생성자 생성
- @RequestParam
    - 외부에서  api로 넘긴 파라미터를 가져옴
    ```java
    public HelloResponseDto helloDto(@RequestParam("name") String name){}
