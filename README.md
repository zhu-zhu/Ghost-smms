# Ghost-smms

Ghost博客的上传图片改为上传到[SM.MS](https://sm.ms/)图床，[演示站](https://kangna.moe/post)

# Installation

## 下载 smms-cli

```shell
npm install smms-cli -g
```

## 更改图床

```shell
su { user }
# 你在ghost目录下创建的用户
cd you_ghost_path/versions/{ your_ghost_versions }/core/server/adapters/storage/
# 将本LocalFileStorage.js替换源目录的LocalFileStorage.js
# 重新启动ghost，根据提示启动ghost
```

# Down
