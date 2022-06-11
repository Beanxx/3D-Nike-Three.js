# 3D-Nike-Three.js

[https://beanxx.github.io/3D-Nike-Three.js/nike.html](https://beanxx.github.io/3D-Nike-Three.js/nike.html)

<img width="1168" alt="스크린샷 2022-06-12 오전 1 47 08" src="https://user-images.githubusercontent.com/64299610/173197667-ff5ddb94-73c0-44d6-993c-392f77d9b375.png">

<br/>
<br/>
<hr/
>

➰ html 파일에서 Three.js 모듈을 불어오는 과정에서 `<script type="module"/>` code 부분에서 아래와 같은 에러 발생
<img width="716" alt="스크린샷 2022-06-12 오전 2 42 34" src="https://user-images.githubusercontent.com/64299610/173199104-0183623b-b8df-435b-8d80-1f04c7b091e9.png">

찾아보니까 CORS 관련 에러였다. 아래 링크의 사이트에서 잘 설명해줌! <br/>
여기에 나와있는 해결방법으로 문제를 해결할 수 있었다.🫠

[Local에서 CORS policy 관련 에러가 발생하는 이유](https://velog.io/@takeknowledge/%EB%A1%9C%EC%BB%AC%EC%97%90%EC%84%9C-CORS-policy-%EA%B4%80%EB%A0%A8-%EC%97%90%EB%9F%AC%EA%B0%80-%EB%B0%9C%EC%83%9D%ED%95%98%EB%8A%94-%EC%9D%B4%EC%9C%A0-3gk4gyhreu)

🫶 브라우저에서 바로 실행시키는 것이 아니라 프로젝트 폴더에서 `npx http-server`로 서버를 실행시켜 해당 포트로 접속!

```shell
    npm install http-server -g
    npx http-server
```

📎 `http://127.0.0.1:8080`
