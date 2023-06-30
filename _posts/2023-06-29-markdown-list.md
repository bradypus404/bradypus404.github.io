---
layout: post
title: Welcome to Jekyll!???
subtitle: A awesome static site generator.
author: Jinha
categories: jekyll
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
tags: jekyll theme yat
sidebar: []
---
### ↑ Banner

### Markdown 설명

이 페이지는 `markdown`의 형식의 예제들을 적어놓은 설명서이다.

제목 리스트
'''
제목 입니다.
'''

'###' ###  큰 제목
'##' ## 중간 제목
'#' # 작은 제목

## section 1

코드를 적을때는 아래와 같이 작성하면 된다.

{% highlight ruby %}
def print_hi(name)
puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

## section 2

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

$ a \* b = c ^ b $

$ 2^{\frac{n-1}{3}} $

$ \int_a^b f(x)\,dx. $

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

## Image 삽입
ScreenShot <br>
--------
![linux](../assets/images/post/linux.jpg)


<img src="../assets/images/post/linux_windows_logos-600x400.jpg", height="100x", width="100px">
