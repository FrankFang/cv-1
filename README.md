# 部署方式

每次改完代码，必须运行这一行，才能正确的请求 JS 和 CSS：

```
 
yarn global add parcel@1.9.7
parcel build src/index.html --no-minify --public-url .
 
```
