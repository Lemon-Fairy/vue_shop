# vue_shop

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### 注意
  > 在el-cascader 级联选择器中有一个小问题就是渲染完父级分类之后级联选择器占满屏幕
  解决办法：为级联选择器设置高度
  ```css
  .el-cascader-panel {
    height: 300px;
  }
  ```
