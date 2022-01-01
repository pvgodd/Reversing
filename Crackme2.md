## Crackme2

프로그램 실행 후

[![me2.png](https://i.postimg.cc/HLfgjrPH/me2.png)](https://postimg.cc/qtXY5vTZ)

name 과 serial 을 넣었더니 wrong serial 을 보여준다.

이 메세지를 보고 이벤트 시작점을 찾고 비교부분을 찾을 수 있을 것이다.

401238 - EP 부분이다.

push 401e14 를 하고 있다.

401e14에는 char "v" 를 가리키고 있다.

VB 전용 엔진을 사용하는 Visual Basic으로 제작되었다. 그러므로 Char "v" 인건가?

esp 값이 19ff70 으로 바뀌였다.

