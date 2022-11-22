splice 메소드

- splice()의 첫번째 파라미터가 음수일 때, 잘라낼 요소를 뒤에서부터 카운팅한다. 
- pressed.splice(-secretCode.length - 1, pressed.length - secretCode.length);
- pressed 배열의 길이가 7이 되는 순간, pressed.splice(-7,1)이 되어서 잘리는 것임


참고자료 : https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Global_Objects/Array/splice


