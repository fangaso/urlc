# Urlcreate
使用Cloudflare Workers和KV生成短链接

# API

[API Documentation (API文档)](API.md)

# 开始
### 去Workers KV中创建一个命名空间

<img src="https://cdn.jsdelivr.net/npm/imst@0.0.4/20201205232805.png">

### 去Worker的Settings选选项卡中绑定KV Namespace

<img src="https://cdn.jsdelivr.net/npm/imst@0.0.4/20201205232536.png">

### 其中Variable name填写`LINKS`, KV namespace填写你刚刚创建的命名空间

<img src="https://cdn.jsdelivr.net/npm/imst@0.0.4/20201205232704.png">

### 复制本项目中的`index.js`的代码到Cloudflare Worker 

### 点击Save and Deploy

# 示例
https://urlc.ml/

注意：所有由Demo网站生成的链接24小时后会自动失效，如需长期使用请自行搭建。
