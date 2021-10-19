---
layout: page
title: About
description: 打码改变世界
keywords: ywq
comments: true
menu: 关于
permalink: /about/
---



这是个懒人，如果不是与游戏相关的，请不要期望他会写什么（除了编程）



## 联系

暂无

## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
