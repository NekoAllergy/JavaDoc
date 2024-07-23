> Feature
> Java Platform module system, see Project Jigsaw on OpenJDK.
### 특징
```
자바 플랫폼 모듈 시스템이란
모듈 > 비슷한 기능을 모아둔 것 > 모듈이 모여 어플리케이션을 만든다.
여러 모듈을 모아두고 사용할 수 있게 사용자들을 한 곳에 모아주는 역할이 플랫폼이라고 생각한다. > 사용자와 공급자를 연결함



Project Jigsaw란?
직역하면 프로젝트 퍼즐이다.

왜 퍼즐일까 생각해보니 공식문서에는 나오지 않지만 모듈을 퍼즐같은 개념과 비슷해서 그랬나보다.

이 프로젝트는 모듈화에 중점을 뒀다고 나온다.
모듈의 정의, 모듈의 변경이 앱에 영향을 주지않는 것 등등
모듈이 뭔지 모듈이 어떤 특징을 가져야하는지에 대한 문서가 프로젝트 직쏘의 초안에 있다.



공식문서에서 중요해보이는 모듈화의 이유를 몇가지 가져왔다.

"플랫폼 모듈화 > 모듈 시스템은 최소 구성으로 현재 Java ME CDC 플랫폼 크기의 API를 정의하는 Java SE API의 중간 수준 모듈화를 지원해야 합니다.
JDK가 제한 없이 계속 성장하는 것을 방지하는 안전 밸브를 제공해야 합니다."

"개발자는 모듈 시스템의 가장 중요한 소비자입니다.
Maven, OSGi 번들, .NET 어셈블리 또는 UNIX 공유 라이브러리에 익숙한 사람은 Java 모듈에 즉시 익숙해지고 생산적이어야 합니다.
컴파일-링크-디버그 주기는 빨라야 하며 문제를 빠르게 진단할 수 있어야 합니다.
모범 사례를 장려하지 않는 기능은 생략해야 합니다."



대충 결론요약하면 모듈화란 모듈끼리 원하면 연결, 분리, 대체가 가능하며 그것이 전체에 큰 영향을 주지않는 새로운 방법론인 것 같다.



  

Project Jigsaw는 아래 링크에서 확인 가능하다.
```
https://openjdk.org/projects/jigsaw/

- - -

> Description
> Introduced in this release.

> The Java Platform module system introduces a new kind of Java programing component, the module, which is a named, self-describing collection of code and data.
> Its code is organized as a set of packages containing types, that is, Java classes and interfaces; its data includes resources and other kinds of static information.
> Modules can either export or encapsulate packages, and they express dependencies on other modules explicitly.
### 설명
```

```

- - -

### JEP
https://openjdk.org/projects/jigsaw/spec/
