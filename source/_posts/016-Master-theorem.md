---
title: Master theorem
date: 2017-02-04 16:34:57
tags:
 - algorithm
categories:
 - algorithm
---
# Master theorem
recursive algorithm을 구현할 때, 점화식으로부터 시간 복잡도를 구할 때 사용되는 theorem이다.

기본적으로 점화식이 다음과 같이 나올 경우에 대해서,
![General formula](/images/master_theorem_general_form.png)

다음 세 가지 usecase 로 나누어서 해당 algorithm의 time complexity를 측정하는 것이 가능하다.

![Case 1](/images/master_theorem_case1.png)

![Case 2](/images/master_theorem_case2.png)

![Case 3](/images/master_theorem_case3.png)

## Example
유명하게 알려져 있는 recursive algorithm에 Master theorem을 대입하면 다음과 같다.

![Case 3](/images/master_theorem_example.png)

## further questions
 - 각각 다음과 같은 식으로 점화식이 분리가 되어서 나올 때는 어떻게 식을 적용해야 하는 지는 좀 헷갈린다.

> T(n) = T(0.4n) + T(0.6n) + O(n)

> T(n) = T(0.4n) + T(0.2n) + O(n^2)


## Userful links
[Master theorem, Wikipedia](https://en.wikipedia.org/wiki/Master_theorem)
