>Feature

>Local Variable Type Inference
>See also Local Variable Type Inference: Style Guidelines

### 특징
```
지역 변수 타입을 추론하다?

이는 너무 긴 이름, 중복되는 이름을 줄이기 위해 나온 기능이다.

CertificateRevokedException exception = new CertificateRevokedException(new Date(), null, null, null);

이런 게 있다고 하면

var exception = new CertificateRevokedException(new Date(), null, null, null);

이렇게 var만 쓰면 자바가 타입을 알아서 맞춘다.

var은 variable에서 따온 것 같다. 그리고 예약어다.

그리고 local이란 걸 보면 지역변수이고 제한적으로만 쓰이는것 같다.


```

- - -

>Description

>Introduced in this release.
>Local-Variable Type Inference extends type inference to declarations of local variables with initializers.

### 설명
```
```
