# sblog

2020.2.23
变更HTML/CSS的学习计,创建新的分支feature1,作为快速示例

2020.2.22 by XuWenchao
练习使用git,完成GitHub注册,创建了一个分支dev,再次修改readme

2020.2.19 by XuWenchao
在B站的全栈之巅作品"Element UI + NodeJs(Express)全栈开发后台管理界面"视频基础上，本版本增加以下内容：
1、ListArticle页面增加了<el-pagination>组件，用于数据增多后的分屏显示
2、增加了ListArticle页面的状态存储功能，用户因新增/编辑文章等原因暂时离开当前页面时，再次返回ListArticle能够直接进入离开前的状态
2.1 引入了Vuex存储页面的pageSize和currentPage，可以响应式更新（当前暂没体现优势，学习一下留待以后扩展用）
2.2 引入浏览器端本地存储功能，pageSize使用localStorage保存用户操作习惯，currentPage使用sessionStorage保存当前页面序号

目前尚未建立索引，留待下一步解决

## Project setup
```
cnpm i -DS
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
