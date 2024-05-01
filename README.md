# vanna-chatbi

[vanna.ai](https://vanna.ai/) 原理探索


vanna是一个基于LLM和数据库进行自然语言交互的解决方案, 本项目探索了它的实现原理


## 运行

配置阿里云dashscope的api_key，即可开始运行demo.ipynb

```
vn=MyVanna({'api_key':'填写你的阿里云dashscope秘钥','model':'qwen-max'})
```

结合vanna源码，随着notebook运行可以轻松理解其底层实现原理