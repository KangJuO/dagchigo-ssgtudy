
# let, var, const 변수키워드

### 💎 let
**'let'** 은 let으로 result를 선언하고 값을 할당하지 않고 나중에 값을 할당할 수 있는 변수선언 키워드이다.이렇게 let을 쓰는 경우는 값을 조건에 따라 다르게 할당하고 싶을 때 우선 변수, 즉 값을 넣을 메모리를 확보한 후 값을 나중에 넣어주는 경우에 쓰인다.

<img width="635" alt="스크린샷 2021-10-26 오전 9 43 11" src="https://user-images.githubusercontent.com/80687195/139067093-a10eaf0d-3acf-44c8-92f2-5ce637fc59e2.png">


### 💎 var
**'var'** 은 const와 다르게 나중에 선언이 가능하다 나중에 선언하게 되어도 error는 나지않고 값이 undefined으로 나오게 된다.즉, error를 맞이하지 않게 된다. 이것이 const와 let에 다른 점이다.

하지만, const를 사용하여 선언한 경우에는 값을 재할당할 수 없지만, var은 함수 스코프를 넘어서도  변수사용이 가능하다는 장점이 때로는 단점으로 작용이 된다. 즉, 한 변수에 지정된 값만이 들어가야하는데 다시 재할당이 되거나, 함수안에서 return해야하는 값이 다른게 반영되어서 나오게되므로, 사용을 자제하고 적절하게 사용하는게 좋다.

<img width="634" alt="스크린샷 2021-10-26 오전 9 43 35" src="https://user-images.githubusercontent.com/80687195/139068417-d29eebd0-acae-4503-98a2-1e92f8dc73a0.png">

### 💎 const
**'const'** 은 const으로 fruitName를 선언하고 값을 꼭 할당한 후에 변수를 사용할 수 있다. let처럼 할당된 값을 바꿀 수 없으며, 또한 만약에 const로 선언한 변수를 쓰고 싶을 경우 const로 선언한 후에 써야한다. 만약 내가 함수를 사용하고 나서 나중에 const를 선언한 경우에 error를 맞이하게 될 것이다.

<img width="637" alt="스크린샷 2021-10-26 오전 9 43 23" src="https://user-images.githubusercontent.com/80687195/139067169-cbf6a199-58f3-4c69-890c-cf81d78470d8.png">


