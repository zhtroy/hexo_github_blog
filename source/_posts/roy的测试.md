---
title: roy的测试
date: 2018-10-11 15:16:24
tags: tag1
categories: [cat1, cat2]
---

测试一下
{% quote [author[, source]] [link] [source_link_title] %}
content
{% endquote %}

 


{%blockquote David Levithan Wide Awake , www.google.com %}
Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.
{% endblockquote %}
{% blockquote %}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem.
{% endblockquote %}

{% blockquote @DevDocs https://twitter.com/devdocs/status/356095192085962752 yesurl %}
NEW: DevDocs now comes with syntax highlighting. http://devdocs.io
{% endblockquote %}

{% codeblock helloworld %}
alert('Hello World!');
{% endcodeblock %}

{% codeblock lang:objc %}
[rectangle setX: 10 y: 10 width: 20 height: 20];
{% endcodeblock %}

{% codeblock _.compact http://underscorejs.org/#compact  %}
_.compact([0, 1, false, 2, '', 3]);
=> [1, 2, 3]
{% endcodeblock %}


{% pullquote  %}
content
{% endpullquote %}

{% post_link  hello-world %}
{% post_path hello-world yes %}

![](/images/foo.png)