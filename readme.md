## WaaS Express 과제

### 12월 23일
* todo list의 제목을 "HelloTODO"로 하기 위해서는 localhost:3000/todo?title=HelloTODO 로 접근해야 함

### 12월 24일
#### GET
![1224_1](./docsimg/1224_1.png)
#### POST
![1224_2](./docsimg/1224_2.png)
#### PUT
![1224_3](./docsimg/1224_3.png)
#### DELETE
![1224_4](./docsimg/1224_4.png)

#### 12월 25일: HTTP Header, File Type

text 선택 후 
http://localhost:3000/mime/homework?image=y로 보낸다

![1225_1](./docsimg/1225_1.png)



#### 12월 26, 27일: login 구현체
![1226_1](./docsimg/1226_1.png)
waas로 로그인하니 쿠키 생성이 확인된다.

![1226_code](./docsimg/1226_code.png)
다 하기 전에는 캡쳐를 깜빡하고 안해놔서 완성본이다.
```
14-18: ukth계정 추가
   19: redirect ./login/isLogin으로 변경
28-37: undefined, waas, 이외계정 3가지로 나누어 응답 설정
```

이상한 계정으로 로그인 시도하니
![1226_2](./docsimg/1226_2.png)

unauthorized 잘 뜬다
![1226_3](./docsimg/1226_3.png)

내 계정은
![1226_4](./docsimg/1226_4.png)

forbidden 뜬다.
![1226_5](./docsimg/1226_5.png)

waas 계정은
![1226_6](./docsimg/1226_6.png)

잘 뜬다(계정 저장옵션까지 뜬다 굳)
![1226_7](./docsimg/1226_7.png)
