---
layout: post
title: 제대로 작동하려나
subtitles: ProTips!
date : 2020-07-03 02:45
tag: [Tips, Github, Notion, C++]
---
# Modern C++ Cookbook - Chapter 1

## 1. 가능한 한 auto 사용하기

### ▶ 'auto'의 장점

1. 변수 초기화를 놓치지 않도록 도와준다. auto는 반드시 초기화가 되어야하기 때문이다.
2. auto는 항상 올바른 타입을 사용하는 것을 보장한다. 암시적인 형변환이 발생하지 않는다.
3. OOP 원칙에 부합한다. 변화에 개방적이다.
4. 타이핑이 적어지고 실수할 확률이 적어진다.
5. 타입이 항상 오른쪽에 위치하는 일관된 코딩 스타일을 제공한다.

    ```cpp
    int *var = new int (5) // 양쪽 모두에 type specifier가 존재한다.
    auto var = new int (5) // 오른쪽에만 type specifier가 존재한다.
    ```

### ▶ 'auto'의 단점

1. 

## 2. 타입 별칭 및 별칭 템플릿 생성

## 3. 균일한 초기화 이해하기

## 4. 범위가 지정된 열거형 사용하기

## 5. 사용자 정의 타입에 대한 범위 기반 for loop 제작

## 6. 구조적 바인딩을 사용해 다중 반환값 처리하기
