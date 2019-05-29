---
layout: blog-list
title: 案例图库
permalink: /cases/

header: 海品照明案例
secondary: 根据不同行业客户的实际环境应用需求，提供定制化和最专业LED照明解决方案。
cover: https://zico.oss-cn-beijing.aliyuncs.com/test/esvnk.jpg
---

<div>
{% for post in site.posts %}
<div class="post-item">
	<a href="{{post.url}}" >
		<div style="background-image: url('{{post.cover}}')" class="cover"></div>
		<div class="content">
			<div class="title">{{post.title}}</div>
			<div class="summary">{{post.summary}}</div>
			<div class="view-detail">查看详情</div>
		</div>
	</a>
</div>
{% endfor %}
</div>
