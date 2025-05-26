---
title: 联系方式
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

欢迎校内外喜欢和支持VEX的各位同仁联系

{%
  include button.html
  type="email"
  text="13605046617@163.com"
  link="13605046617@163.com"
%}
{%
  include button.html
  type="phone"
  text="13605046617"
  link="+86 13605046617"
%}
{%
  include button.html
  type="address"
  tooltip="我们的地址"
  link="https://www.bing.com/search?q=%E5%90%8C%E6%B5%8E%E5%A4%A7%E5%AD%A6%E5%98%89%E5%AE%9A%E6%A0%A1%E5%8C%BA%E5%9C%B0%E5%9B%BE&qs=n&form=QBRE&sp=-1&ghc=1&lq=0&pq=%E5%90%8C%E6%B5%8E%E5%A4%A7%E5%AD%A6%E5%98%89%E5%AE%9A%E6%A0%A1%E5%8C%BAdi%27t&sc=0-12&sk=&cvid=B88F97F7791B485087041886E78A7480"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/sys/sys_1.jpeg"
  caption="实验室概况"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/sys/sys_2.jpeg"
  caption="实验室概况"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
上海市杨浦区曹安公路4800号
{% endcapture %}

{% capture col2 %}
同济大学电子与信息工程学院
{% endcapture %}

{% capture col3 %}
同济大学VEX实验室
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
