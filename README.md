# 个人导航之家

#### 介绍
个人导航之家Demo [演示地址1](https://linkes.gitee.io/home/) ，[演示地址2](https://mason2woods.github.io/home/)

#### LOGO缓存机制

- 首次加载时从网络获取LOGO并转为base64缓存到 LocalStorage
- 后续直接从 LocalStorage 读取，不再请求网络
- 添加新网站时自动获取并缓存LOGO
