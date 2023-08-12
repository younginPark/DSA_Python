# Classes
- 클래스는 모든 자료구조가 클래스로 만들어지기 때문에 아주 중요

# Pointers
- 아래처럼 했을 때 num2는 num1에 들어간 11과 동일한 주소를 가리킴
```
num1 = 11
num2 = num1
```
- 이 상태에서 num2를 22라는 값으로 업데이트하면 num1도 같이 22로 바뀌지는 않고 11 그대로 가짐
  그리고 num1과 num2가 가리키는 값의 주소가 달라짐
- integer와 같은 값을 넣으면 immutable 하기 때문에 22로 업데이트하면 메모리에서 22를 갖는 공간을 새로 할당하게됨
- dictionary의 경우 num2에서 value의 값을 바꾸면 num1도 동일하게 값이 바뀌고 num1과 num2는 num2를 업데이트 하기 전의 메모리 주소를 동일하게 바라봄
- 만약 변수 3개가 각각 다른 dictionary value를 가리키다가 동일한 dictionary를 가리키게 되면 이전의 2개는 쓸모 없어지게 된다. 쓸모없어진거는 python에서 내부적으로 garbage collection을 돌려서 처리한다.