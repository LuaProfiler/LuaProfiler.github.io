---
layout: default
---

<body>
  <div class="index-wrapper">
    <div class="aside">
      <div class="info-card">
        <h1>Lua Profiler For Unity</h1>
        <a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=f6d6a82c582431a4faf0be2d894c486247cada47f6d515d9a0225ce1ae04faff"><img border="0" src="//pub.idqqimg.com/wpa/images/group.png" alt="LuaProfiler官方群" title="LuaProfiler官方群"></a>
      </div>
      <div id="particles-js"></div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
