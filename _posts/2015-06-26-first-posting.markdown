---
layout: post
permalink: /2016/Exam01
title: "첫번째 포스팅"
description: ""
category: post
tags: [posting, cook blog]
---

` 루비 코드 `

` 1. 깃허브 페이지에서 새로운 저장소(New Repository)를 만들고 클론 주소를 복사 `

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

{% highlight bash %}
~ $ jekyll build
# => ./_site 에 현재 폴더의 내용으로 사이트를 생성합니다

~ $ jekyll build --destination <destination>
# => <destination> 에 현재 폴더의 내용으로 사이트를 생성합니다

~ $ jekyll build --source <source> --destination <destination>
# => <destination> 에 <source> 폴더의 내용으로 사이트를 생성합니다

~ $ jekyll build --watch
# => ./_site 에 현재 폴더의 내용으로 사이트를 생성하고,
#    변경사항을 감지하면 자동으로 다시 생성합니다.
{% endhighlight %}

{% highlight ruby linenos %}
if "fablic".length > 3
  puts 'ya'
else
  puts 'nop'
end  
{% endhighlight %}

<div class="note">
  <h5>ProTip™: UTF-8로 작성된 CSS나 기타 파일들을 JeKyll에서 실시간 수정 할 때</h5>
  <p>
    커맨드 프롬프트에서 UTF-8 코드 페이지로 변경 해야 하는데 변경 방법은
    <code> chcp 65001 </code> 로 입력하면 <br>UTF-8 코드페이지로 변경.
  </p>
</div>

<div class="note info">
  <h5>페이지 나누기는 오직 HTML 파일에서만 작동합니다</h5>
  <p>
    페이지 나누기는 Markdown 이나 Textile 파일에서는 작동하지 않습니다. 오직
    HTML 파일 안에서 사용될 때에만 작동합니다. 보통 이 기능은 포스트 목록에
    사용하기 때문에, 큰 문제가 되지는 않을 것입니다.
  </p>
</div>

<div class="note warning">
  <h5>첫 페이지 경계조건을 주의하세요</h5>
  <p>
    Jekyll 은 'page1' 폴더를 생성하지 않기 때문에, 위 코드는 <code>/page1</code>
    링크에 대하여 올바르게 작동하지 않습니다. 만약 이것이 문제가 된다면 아래의
    방법을 참고하세요.
  </p>
</div>

<div class="note unreleased">
  <h5>이 표시는 아직 릴리스 되지 않는 기능을 가리킵니다</h5>
  <p>이 웹사이트는 아직 릴리스 되지 않는 버전에 대한 내용도 일부 포함하고
    있습니다.</p>
</div>