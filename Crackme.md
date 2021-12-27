## Crackme
abexcm1.exe 파일을 이용하여 리버싱 분석을 한다.

> 어셈블리로 작성하여 EP 코드가 짧다.

---

###### Main Srceen

![crack1](https://i.postimg.cc/T1Q51Pqw/crack1.png)



처음 보이는 파일 화면이다.

현재 ESI 가 EP로 잡혀져있다. FFFFFFFF로 셋팅 된 것을 알 수 있다.

---

###### GetDriveType

![crack3](https://i.postimg.cc/KvR8BQmQ/crack3.png)

GetDriveType 이 끝나면서 EAX 값이 3이 된 것을 볼 수 있다.

EAX 값이 3인 이유는 드라이브의 고정된 미디어가 있으므로 함수의 반환 값이 3이 되었다.(RootPathName = "c:\\")

---

###### INC & DEC

![crack5](https://i.postimg.cc/1XTPvhyB/crack5.png)

INC 값을 1증가, DEC 값을 1 감소 시킨다.

###### EAX 와 ESI 값

![crack4](https://i.postimg.cc/RFRjDrLf/crack4.png)

EAX 와 ESI 값이 달리지는 것을 확인 할 수 있다.

---

