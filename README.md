主要使用 `extract-text-webpack-plugin` 实现 `js` 、`css` 公共代码提取，`html-webpack-plugin` 实现 `html` 多入口，`less-loader` 实现 `less` 编译，`postcss-loader` 配置 `autoprefixer` 实现自动添加浏览器兼容前缀，`babel-loader` 实现 `ES6` 转码功能。

## 使用

### 安装

```
npm install
```

### 开发

```
先执行 npm run buid 生成 dist 文件夹后 在执行 npm run dev 实时编译代码
```
> http://localhost:8080/view


### 构建

| 命令 | 说明 |
|----------|------|
| `npm run dev` | 开发环境构建，不压缩代码 |
| `npm run build` | 生产环境构建，压缩代码 |