# IPRS官网

## 部署方法

复制dist到静态服务器文件夹下

## 开发方法

1. 安装nodejs开发环境
2. 安装依赖
```shell
npm install
```
3. 启动开发服务器
```shell
npm start
```
3. 打包
```shell
rm -rf ./dist
npm run build
```

## 生产环境优化
1. 配置强制缓存
1. 配置cdn