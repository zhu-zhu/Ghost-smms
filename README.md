# Ghost-smms
Ghost博客的上传图片改为上传到[SM.MS](https://sm.ms/)图床

# Installation
> 由于ghost对于node.js版本要求过于严格，虽说支持10+，但是照着官网写了Storage Adapters插件却无法使用，原因是需要使用8^的node版本，而我的服务器node是10，所以只能更改源码

```shell
# 在you_ghost_path/content/目录下创建/adapters/storage把LocalFileStorage.js丢进去
cd you_ghost_pathcontent/adapters/storage
git clone https://github.com/zhu-zhu/Ghost-smms.git
restart ghost
```

如果放在content/adapters/storage目录下无法使用
```shell
cd you_ghost_path\current\core\server\adapters\storage
# 将本LocalFileStorage.js替换源目录的LocalFileStorage.js
# 重新启动ghost
```
# Down
