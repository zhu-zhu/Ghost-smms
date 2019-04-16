# Ghost-smms
Ghost博客的上传图片改为上传到[SM.MS](https://sm.ms/)图床

# Installation
> 由于ghost对于node.js版本要求过于严格，虽说支持10+，但是照着官网写了Storage Adapters插件却无法使用，原因是需要使用8^的node版本，而我的服务器node是10，所以只能更改源码

```shell
cd you_ghost_path\current\core\server\adapters\storage
将本LocalFileStorage.js替换源目录的LocalFileStorage.js
重新启动ghost
```

# Down
