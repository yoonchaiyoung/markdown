tex 문법 참조 링크 : https://ko.wikipedia.org/wiki/%EC%9C%84%ED%82%A4%EB%B0%B1%EA%B3%BC:TeX_%EB%AC%B8%EB%B2%95

식

$$
C = \frac{1}{2}\sum_{n=1}^N(t_{n}-y)^2
$$


줄바꿈하면 안 됨 한 줄 안에 써야 함

밑 지수 먼저
승수 나중

$$
C = \frac{1}{2}\sum_{n=1}^N\lVert t_{n} - y \rVert_2^2 = \frac{1}{2}\sum_{n=1}^N\sum_{i=1}^N(t_{n} - y_{i})^2
$$


문장안에 $C = \frac{1}{2}\sum_{n=1}^N(t_{n}-y)^2$ 식을 넣었다.


#### 줄 바꿈
$$
C = \frac{1}{2}\sum_{n=1}^N(t_{n}-y)^2\\
C = \frac{1}{2}\sum_{n=1}^N\lVert t_{n} - y \rVert_2^2 = \frac{1}{2}\sum_{n=1}^N\sum_{i=1}^N(t_{n} - y_{i})^2
$$

식 뒤에 \\ 두개를 달면 자동 렌더링됨.


$$
a = \frac{\sum_{i=1}^n(y_{i}-\bar{y})(x_{i}-\bar{x})}{\sum_{i=1}^n(x_{i}-\bar{x})^2}
$$

