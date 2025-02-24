---
layout: single
title: "롤의 정리"
categories: Calculus
tag: [정리, 미분, 증명]
side_bar:
    nav: "counts"
author_profile: false
toc: true
use_math: true
---

## 1. 롤의 정리 (Rolle's Theorem)
함수 $f$가 폐구간 $\left[ a,b\right]$에서 연속이고, 개구간 $\left(a,b\right)$에서 미분가능할 때, $f(a)=f(b)$ 이면 $f'(c)=0$ 을 만족하는 c가 구간 $\left(a,b\right)$에 적어도 하나 존재한다.
<br/><br/>

### 2. 증명
함수 $f$는 구간 내에서 연속이고 미분가능하므로, $f$는 다음 세 경우로 나눌 수 있다.<br/><br/>
**1. $f(x)=k\quad(k는 상수)$**
<br/><br/>이 경우 모든 점에서  $f'(x)=0$ 이므로 정리가 성립한다.
<br/><br/>
**2. $(a,b)에\ 속하는\ 어떤\ \ x\ 에서\ f(x)>f(a)\ 인\ 경우$**
<br/><br/>극값 정리에 의해 $f$ 는 폐구간 $\left[a,b\right]$에 반드시 최댓값을 갖는다. 이때 $f(a)=f(b)$ 이므로 개구간 $\left(a,b\right)$ 에 속하는 수 c에서 최댓값을 가져야 한다. 따라서 페르마 정리에 따라 $f'(c)=0$ 이다.
<br/><br/>
**3. $(a,b)에\ 속하는\ 어떤\ \ x\ 에서\ f(x)<f(a)\ 인\ 경우$**
<br/><br/>극값 정리에 의해 $f$ 는 폐구간 $\left[a,b\right]$에 반드시 최솟값을 갖는다. 이때 $f(a)=f(b)$ 이므로 개구간 $\left(a,b\right)$ 에 속하는 수 c에서 최솟값을 가져야 한다. 따라서 페르마 정리에 따라 $f'(c)=0$ 이다.
<br/><br/>

### 2.1. 귀류를 통한 증명
개구간 $\left(a,b\right)$에 속하는 모든 $x$에 대하여 $f'(x)\neq0$ 이라 가정하자. 극값 정리에 의해 연속함수 $f$는 닫힌구간 $\left[ a,b\right]$에서 반드시 최댓값 $M$과 최솟값 $m$을 갖는다. <br/>페르마 정리에 의해 구간 내에 어떠한 점도 극점이 될 수 없다. 따라서 구간의 양 끝 점인 $a$와 $b$에서 함수 $f$는 최댓값과 최솟값을 갖는다.
<br/>이때 $f(a)=f(b)$, 즉 $M=m$ 이므로 구간 $\left[ a,b\right]$에서 $f$는 상수함수이다. 이는 가정에 모순이므로 $f'(c)=0$ 를 만족하는 c가 열린구간 $\left(a,b\right)$에 적어도 하나 존재한다.
<br/><br/>

### 3. 롤의 정리의 기하학적 의미
롤의 정리는 조건을 만족하는 모든 함수는 접선의 기울기가 0인 점이 반드시 존재함을 의미한다.
<br/><br/>

### 4. 의의
미적분학에서 가장 중요하다고 해도 과언이 아닌 평균값 정리를 증명하는 기반이 된다.
<br/><br/> 

### 5. 기타
연속인 구간을 개구간으로 설정할 경우 $f(a), f(b)$ 가 존재하지 않는다.
또한 미분가능한 구간을 폐구간으로 설정할 경우 구간의 양 경계에서 좌미분 계수와 우미분 계수가 각각 존재하지 않아 미분가능함을 보장할 수 없다.
<br/><br/>

### 참고


### Reference
>James Stewart(2020). 『Calculus』(9th ed). Cengage Learning 
>Tom M. Apostol(1967). 『Calculus Volume 1: One-variable Calculus, with an Introduction to Linear Algebra』(2nd ed.). New York: Willey