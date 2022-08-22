# 部署

每次修改完代码，需要运行以下代码才能成功请求 css 和 js

```
parcel bulid src/index.html --public-url .

```

如果bulid报错plugin不是函数时，运行以下代码，然后再重复第一行代码，即可成功

```
npm i parcel-plugin-clean-dist

```
