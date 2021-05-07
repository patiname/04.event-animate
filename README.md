##event,animate

\*이벤트
=>사용자가 어떠한 행동을 했을때 다른 결과값을 반환함

\*마우스 이벤트
1.mousemove
=>요소안에서 마우스가 움직였을때

2.mouseenter
=>요소안에 마우스가 들어갔을때

3.mouseleave
=>요소안에서 마우스가 떠났을때

4.mousedown
=>요소를 눌렀을때

5.mouseup
=>요소에 마우스를 눌렀다 뗏을때

6.click
=>요소를 눌렀다가 뗏을때

7.dblclick
=>더블클릭

8.hover
=>요소에 마우스를 올렸다가 내렸을때
=>콜백함수 이용

\*콜백함수
=>명령어를 한번 실행하고 난다음 다른 명령어를 실행시킴

$(선택자).명령어(function(){
다른식
}, function(){
또 다른식
});

\*애니메이트
=>요소에 애니메이션을 적용할수있음
=>$(선택자).animate({
속성: 속성값
},시간,가속도,콜백함수)
=>width,height
=>margin
=>padding
=>position
=>opacity
=>scroll
