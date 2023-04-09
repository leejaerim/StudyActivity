### 목표

- 움직이는 물결(웨이브)를 만들어 보고자 한다.

### 학습 자료

 - [Interactive Developer의 HTML5 Canvas Tutorial : 움직이는 웨이브 만들기](https://www.youtube.com/watch?v=LLfhY4eVwDY&t=11s)
 - [MDN web doc](https://developer.mozilla.org/ko/docs/Web/API/window/requestAnimationFrame)

### 학습 내용

- HTML5 태그 중 하나인 canvas와 canvas와 연관된 기능 함수를 이용해 웨이브를 그린다.
- `canvas.beginPath()` 와 `canvas.closePath()`는 선을 그리고 선을 닫는 함수
- `requestAnimationFrame` 함수는 브라우저에게 애니메이션 업데이트 하도록 하며, 업데이트 전 실행된 콜백함수를 인자로 받습니다.
- `quadraticCurveTo`함수는 직선이 아닌 베지에 곡선을 그리도록 합니다.