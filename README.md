# hello-world

所有环境都要先安装依赖

npm是node的包管理工具，所以要先安装node

## 安装所有依赖
```
npm install
```

### 启动开发环境
```
npm run serve
```

### 打包
```
npm run build
```

- 开发中用的最多的就是src目录，一般都是在那个目录下写
- router.ts是配置路由的 之所以是.ts是因为用了typeScript插件（进行类型校验用）
- APP.vue是所以页面的基础
- views 目录里面就是每个页面
- components是组件：如果一个东西在多出用到最好是封装成组件
- main.ts 需要在全局引用的插件就在这里引用
- aseets 里面放一些静态的文件


