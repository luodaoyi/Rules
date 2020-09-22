# RULES
使用教程

## OpenWrt openclash 插件使用方法
1. 设置

运行模式: Fake-IP
代理模式: Rule

2. 全局->版本更新
更新内核和客户端

3. 加载配置


下载 dler.yaml
替换 {managed_token} 为dler控制台 [https://dlercloud.com/user](https://dlercloud.com/user) 的 $managed_token

```shell
sed -i "s/{managed_token}/xxxxxxxx/" dler.yaml
```

打开 配置文件管理:
上传dler.yaml

4. 启用

切换到运行状态
点击切换到dler.yaml配置文件