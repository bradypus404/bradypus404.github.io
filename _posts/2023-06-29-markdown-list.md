---
layout: post
title: Markdown Guide
subtitle: test
date: 2023-06-29 00:00:00 +0900
author: Jinha
categories: Blog
banner:
  video: https://vjs.zencdn.net/v/oceans.mp4
  loop: true
  volume: 0.8
  start_at: 8.5
  image: https://bit.ly/3xTmdUP
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
  subheading_style: "color: gold"
tags: themea
sidebar: []
---
### ↑ Banner

# Markdown 설명

이 페이지는 `markdown`의 형식의 예제들을 적어놓은 설명서이다.

## 1. 글씨 크기 및 제목

---------------------

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

## 2. 목록

---------------------
### ● 순서없는 목록(글머리 기호: `*`, `+`, `-` 지원)
```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑
```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑


## 인용구
> 인용구
>> 인용구
>>> 인용구

## Image 삽입
ScreenShot <br>

---------------------
![linux](/assets/images/post/linux.jpg)

## 2. 코드 삽입

코드를 적을때는 아래와 같이 작성하면 된다.

{% highlight ruby %}
def print_hi(name)
puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

```cpp
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World!";
  return 0;
}
// prints 'Hi, Tom' to STDOUT.
```

```python
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("John", 36)

print(p1.name)
print(p1.age)
```

## 링크 삽입

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

$a \* b = c ^ b$

$a_1, a^2, a_1^2$
$y_i=x_i^3+x_{i-1}^2+x_{i-2}$

$2^{\frac{n-1}{3}}$

$$\int_a^b f(x)\,dx.$$
