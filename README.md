# 初次使用vitepress
```
感受：
全局文档搜索文档待补充

```
## 选择或创建一个文件夹进去初始化
yarn init -y

## 安装2个开发依赖
yarn add -D vitepress vue

## 新建docs文件和相关markdown文件

## 配置package.json的scripts字段值
```json
"scripts": {
  "docs:dev": "vitepress dev docs",
  "docs:build": "vitepress build docs",
  "docs:serve": "vitepress serve docs"
}
```

# 此项目使用方法：

## 安装依赖
yarn

## 启动项目
yarn docs:dev