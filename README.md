# DQ-mail

## 1 Usage
```
npm install
```

```
npm run serve
```

```
npm run build
```

## 2 Primary directory structure

```markdown
|-- DQ-MALL
    |-- babel.config.js           
    |-- package-lock.json
    |-- package.json                            #项目依赖包的配置文件
    |-- postcss.config.js
    |-- README.md
    |-- vue.config.js
    |-- public
    |-- src
        |-- App.vue				#项目入口文件
        |-- main.js				#项目的核心文件
        |-- assets				#存放第三方静态资源
        |   |-- css
        |   |-- img
        |-- common				#公共的js文件
        |-- components
        |   |-- common				#公共的组件
        |   |   |-- gridView		        #封装商品排列组件
        |   |   |-- navbar			#封装导航栏组件
        |   |   |-- scroll			#封装better-scroll组件
        |   |   |-- swiper			#封装轮播图组件
        |   |   |-- tabbar			#封装底部导航栏组件
        |   |-- content				#与业务相关的组件
        |       |-- backTop			#回到顶部的组件
        |       |-- Icon
        |       |-- mainTabbar
        |       |-- tabControl
        |-- network				#与后端交互相关的js文件
        |-- router				#路由js文件
        |-- store				#仓库ja文件
        |-- views					
            |-- cart				#购物车页面
            |-- category			#商品分类页面
            |-- detail				#商品详情页面
            |-- home				#首页
            |-- profile				#个人中心页面

```

## 3  Project screenshots 

1. home page

   home page - FIG. 1 :

   ![home page - FIG. 1](https://raw.githubusercontent.com/DQ-Li/DQ-MALL/master/src/assets/img/markdown/homePageFig1.png)

   home page - FIG. 2 :

   ![home page - FIG. 2](https://raw.githubusercontent.com/DQ-Li/DQ-MALL/master/src/assets/img/markdown/homePageFig2.png)

   

2. category page

   category page - FIG. 1 :

   ![category page - FIG. 1](https://raw.githubusercontent.com/DQ-Li/DQ-MALL/master/src/assets/img/markdown/categoryPageFig1.png)

   category page - FIG. 2 :

   ![category page - FIG. 2](https://raw.githubusercontent.com/DQ-Li/DQ-MALL/master/src/assets/img/markdown/categoryPageFig2.png)

3. detail page

   detail page - FIG. 1 :

   ![detail page - FIG. 1](https://raw.githubusercontent.com/DQ-Li/DQ-MALL/master/src/assets/img/markdown/detailPageFig1.png)

   detail page - FIG. 2 :

   ![detail page - FIG. 2](https://raw.githubusercontent.com/DQ-Li/DQ-MALL/master/src/assets/img/markdown/detailPageFig2.png)

4. cart page

   cart page - FIG. 1 :

   ![cart page - FIG. 1](https://raw.githubusercontent.com/DQ-Li/DQ-MALL/master/src/assets/img/markdown/cartPageFig1.png)

5. profile page

   profile page - FIG. 1 :

   ![profile page - FIG. 1](https://raw.githubusercontent.com/DQ-Li/DQ-MALL/master/src/assets/img/markdown/profilePageFig1.png)
