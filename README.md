# 응용확률통계 8장 일원배치분산분석 계산기
👉🏻 https://jaewoogwak.github.io/caca/ 
## 사용 방법

모집단을 폼에 콤마로 구분해서 넣어주기만 하면 끝입니다.

예제로 설명드리겠습니다.

![tempImg 9](https://user-images.githubusercontent.com/62415600/177555905-166110b3-3b48-4328-bf3a-29f8a6201e15.jpg)


위에서 모집단 `A의 평균`과 `(Xa - X의 평균)^2`만 알면 SST, SSE를 구할 수 있으니 자유도를 구해서 MST, MSE까지 구할 수 있게 됩니다.

모집단 A에 대한 결과를 알고 싶으면 폼에다가 `290, 265, ... 293` 이렇게 콤마로 구분해서 입력해주세요.

그리고 각각의 모집단에 대해 `평균`과 `(X - X의 평균)^2` 값을 기록해둡시다.

위의 예제 기준으로 `A의 평균`은 280.5, `B의 평균`은 265.1 `C의 평균`은 264.8입니다. 

그리고 각각의 `(X - X의 평균)^2`는 1738.5, 1520.899, 947.6이 나옵니다. (소수점 쪼금 달라도 괜찮습니다)

그럼 이제 `SSt`는 위에서 구한 `A의 평균`은 280.5, `B의 평균`은 265.1 `C의 평균`은 264.8를 하나의 모집단으로 보고 다시 폼에 넣어주면

`(표본평균X - 표본평균X의 평균(전체평균))^2`을 구하는 것이나 마찬가지입니다.

그러면 `SSt`는 위에 구한 `(표본평균X - 표본평균X의 평균(전체평균))^2`에 `n`만 곱해주면 됩니다.

`n`은 10이니 답은 1612.46이 나오게 됩니다.

`SSE`는 각각의 `(X - X의 평균)^2` 1738.5, 1520.899, 947.6를 더해주면 끝입니다. 4206.99가 나옵니다.

