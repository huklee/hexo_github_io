---
title: Google Interview Preparation
date: 2017-01-18 17:26:12
tags:
---
# Google Interview Preparation
## 기술면접 팁
- `기술 면접에서 중요한 것은 정답을 만들어내는 것이 아니라 문제를 해결하는 방식이다.` 실세계의 공학문제는 정답이 없는 경우가 많다. 실세계 시스템은 복잡하고 요구사항이 상충하기 때문이다. 따라서, 항상 상충점trade-off을 고민하는 것이 공학이다. 혹 틀린 답을 도출할지라도 답이 나오는 과정에서 요구사항의 우선순위가 무엇이었는지, 가능한 옵션들은 어떤 것들이 있었는지, 어떤 상충점을 고려했는지, 결과를 어떻게 검증할 수 있는지 얘기할 수 있어야 한다. 문제 풀이 과정과 검증 방법을 아는 사람이 문제를 정말로 풀 수 있는 사람이다. 결국 문제풀이 과정이 정답보다 중요하다.
출처:구글 인터뷰 팁
- 면접관과 대화를 하면서 문제를 푸는 것도 중요하다. `면접관을 동료라고 생각하고 문제풀이를 짝 프로그래밍pair programming으로 생각하자.` 면접관의 질문을 확인하고 부족한 부분을 점검하고 코드를 어떻게 작성할지 대강의 플로우flow를 얘기하자. 코드를 작성하면서 본인이 어떻게 생각하고 있는지 말로 표현하면서 써내려 가는 것이 좋다. 때로 잘 못된 방향으로 가는 경우 면접관이 가이드를 해 줄 수도 있다.
출처:구글 인터뷰 팁
- `자기 소개는 짧게` : 자기소개에 에너지를 쏟지 말자. 면접관들은 후보자의 레쥬메를 읽고 들어온다. 후보자의 자기소개가 크게 필요하지 않다. 진짜 궁금하면 구체적인 사항을 물어본다. 3문장 정도로 요약하여 나는 현재 무슨일을 하고 주로 어떤 분야에서 일을 했는지 이야기하면 된다. 자랑할 만한 것이 있으면 키워드와 숫자로 주의를 끌도록 한다. 예를 들어, 나는 1970년대에 데니스 리치와 함께 유닉스를 만든 켄 톰슨입니다. 팍. 끝.
출처:구글 인터뷰 팁

## 기술 면접 준비과정 팁
- 만약 누군가가 나에게 "온싸이트 인터뷰를 하기 전, 이틀이 남았는데, 뭘 하는게 좋을까요?"라고 하면, 나 역시 `"mock-up interview를 적어도 두번 해보세요"`라고 할 것이다. 꼭 구글에 다니는 친구가 아니어도 되고, 심지어는 랩에 있는 다른 전산학 전공하는 친구를 붙잡고, 예상 문제를 설명해보는 것조차 너무나도 도움이 된다. 왜냐하면, `내가 실제로 알고 있는 것들을 조리있게 설명하는 것이, 내 머리속에 뭐라도 하나 더 채워넣는 것보다 훨씬 값지기 때문이다.`
출처:내가 구글 인터뷰 준비한 과정
- `Programming Interview Exposed`와 `Cracking the Coding Interview `책에 나온 문제들은 2~3년 전에 사용되었던 문제라 더 이상 질문하지 않는 경우가 많다. 그에 비해 위 웹싸이트에는 (불완전할지 몰라도) 최근 문제들이 올라와있다. 그래서 약간 눈여겨 봐야한다.
출처:내가 구글 인터뷰 준비한 과정
- 구글에서 배포하여 사람들이 많이 사용해본 map reduce라던가, `go 프로그래밍 언어 같은 것을 알아서 나쁠 것은 없다`. 인터뷰를 하면서 짜투리 답으로 내가 꺼집어 내었다가 약간 플러스가 된 것 같았었다. 또, 구글 product들을 미리 약간 알고 있어서 인터뷰가 다 끝났을 때, 내가 이미 잘 알고 있는 product그룹에서 온 인터뷰어에게 아주 핵심을 찌르는 질문을 하는 것도 플러스가 될 수 있겠다.
출처:내가 구글 인터뷰 준비한 과정
- 주의할 점은, 대부분 인터뷰에 낙방한 친구들이 올려놓은 문제이기 때문에, 일반 인터뷰 문제들이 a->b->c->d->e 단계로 구성되어 있다면, 이 웹싸이트에 올라온 문제들은 a 혹은 b단계의 문제만 올라와 있는 경우가 많다. 그리고 일부 퍼즐 문제들은 소프트웨어 엔지니어들한테 물어보는 질문이 아니라 마케팅하는 사람들한테 물어보는 퍼즐 문제들도 있으니, 어떤 문제가 소프트웨어 엔지니어에게 물어본 질문이었는지 잘 알아봐야한다.
출처:내가 구글 인터뷰 준비한 과정

## TODO
1. Data Structure간 장단점 및 특성 정리해 놓기
  - 특히 Tree, Binary tree 정도는 실제로 짜 보는 연습을 꼭 하자.
  - 추가로 혼자 구현해 보면서 설명 연습하기
  - Search에 대해서도 많이 까먹었으니 정리를 하자. Binary serach / BFS 정도는 바로 짤 수 있도록
2. C++ 사용한다면 std는 확실하게 해놓자
  - [Sequence Container](https://en.wikipedia.org/wiki/Sequence_container_(C%2B%2B)
    - std::vector
    - std::list
    - std::stack
    - std::queue
  - [Associative Container](https://en.wikipedia.org/wiki/Associative_containers)
    - std::set
    - std::map [참고](http://alones.kr/stl-%EC%BB%A8%ED%85%8C%EC%9D%B4%EB%84%88-%EB%A7%B5-stdmap-%EA%B0%84%EB%9E%B5-%EC%A0%95%EB%A6%AC%EC%99%80-%EC%98%88%EC%A0%9C/)
  -  [Strings](https://en.wikipedia.org/wiki/C%2B%2B_string_handling)
    - std::string [참고](http://makerj.tistory.com/127)
  - 사용법 간단히 정리
  - 각 인터페이스 정리
  - qsort / heapsort / disjointset (Union/Find)
3. mock-up interview 잡고 수행하기 (매주 한 번씩))
  - 부탁할 사람 : 김재완 / 김태환 / 이민우 / 남궁민 / 서윤화
4. etc
  - Design Pattern [참고](http://makerj.tistory.com/110)
5. System Design
  - [System Design Interview Tips](https://github.com/checkcheckzz/system-design-interview#tips)
  - [How do I prepare to answer design questions in a technical interview?](https://www.quora.com/How-do-I-prepare-to-answer-design-questions-in-a-technical-interview)
  - [8 Things You Need to Know Before a System Design Interview](http://blog.gainlo.co/index.php/2015/10/22/8-things-you-need-to-know-before-system-design-interviews/)
  - [System Design Interview Questions examples ](http://blog.gainlo.co/index.php/category/system-design-interview-questions/)
  - [Google System Design Interview Questions from Careercup](https://www.careercup.com/page?pid=google-interview-questions&job=software-engineer-interview-questions&topic=system-design-interview-questions)

## System Design

### Interesting Questions
 - [How would you implement google search](http://softwareengineering.stackexchange.com/questions/38324/how-would-you-implement-google-search)



# Links
## Codes & Github
[Preparation for coding interview](https://github.com/liwei606/interview)

## Books
[Programming Interviews Exposed](http://img105.job1001.com/upload/adminnew/2015-04-03/1428055089-N7PTLH6.pdf)

## Interview problems
[Retiring a Great Interview Problem](http://thenoisychannel.com/2011/08/08/retiring-a-great-interview-problem)

[Google interview problems](https://www.careercup.com/page?pid=google-interview-questions)

[Google Software Engineer questions](http://www.impactinterview.com/2009/10/140-google-interview-questions/#software_engineer)

[Google Software Engineer Test questions](http://www.impactinterview.com/2009/10/140-google-interview-questions/#software_engineer_in_test)

## 인터뷰 준비 방법
[알고리즘 인터뷰 가이드 : 준비편 by 구종만](http://theyearlyprophet.com/interviews-101-preparation.html)

[구글이 프로그래머를 뽑는 법](https://zublog.wordpress.com/2011/12/29/%EA%B5%AC%EA%B8%80%EC%9D%B4-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%A8%B8%EB%A5%BC-%EB%BD%91%EB%8A%94-%EB%B2%95/)

## 인터뷰 후기
## Google Korea
[불합격/길길 : 1st on-site 면접 후기](http://www.gilgil.net/?mid=communities_kr&search_target=title&search_keyword=%EB%A9%B4%EC%A0%91&document_srl=14060)

[불합격/길길 : 2,3,4 on-site 면접 후기](http://www.gilgil.net/?mid=communities_kr&search_target=title&search_keyword=%EB%A9%B4%EC%A0%91&document_srl=14456)

## Mountain View
[합격/내가 구글 인터뷰 준비한 과정](http://piniapple.egloos.com/3236258)

[불합격/폰인터뷰에서 줄줄이 떨어지는 이유 ](http://www.workingus.com/v3/forums/topic/software-engineer-%ED%8F%B0%EC%9D%B8%ED%84%B0%EB%B7%B0%EC%97%90%EC%84%9C-%EB%8B%A4-%EC%9E%98%EB%A6%AC%EB%8A%94-%EC%9D%B4%EC%9C%A0%EA%B0%80-%EB%AD%98%EA%B9%8C%EC%9A%94/)

[합격/구글 인터뷰 팁](http://sv-archives.blogspot.kr/2016/01/blog-post.html)

[합격/구글 취업기 by Sebastian Gabrie](http://radiofun.tumblr.com/post/106141877686/%EA%B5%AC%EA%B8%80-%EC%B7%A8%EC%97%85%EA%B8%B0-how-i-joined-google)
