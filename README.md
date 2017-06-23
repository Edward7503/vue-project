# my-vue-project

> this is my first vue project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).


# vue 环境的搭建(mac端)
# 1. 安装 vue(最新稳定版本)
    注: 因为 npm 在国内的下载网速可能会比较慢,所以需要使用 淘宝的 npm 镜像 cnpm;
    1) cnpm 安装:
        sudo npm install -g cnpm --registry=https://registry.npm.taobao.org
    2) vue 脚手架的安装（使用 vue命令之前必须先安装vue的脚手架 vue-cli ）
        sudo cnpm install -g vue-cli
    3) 在你的项目目录中搭建 vue 的项目（cd 路径）
        vue init webpack 项目名称
    4) 下载所有的依赖到当前的目录下(vi package.json 查看所有依赖,查看后在末尾输入‘:q’ 返回),下载完成后,在你的目录下会多一个 node_modules 的文件夹;
        sudo cnpm install
    5) 运行该项目
        npm run dev  或者 cnpm run dev

    注:  后期的开发主要是在 src 目录下进行


    常用的命令行
        cd 位置   --- 到达当前路径下的某个位置
        pwd     --- 查看当前路径
        vi 文件名.后缀     --- 查看当前路径的某个文件
        ls     --- 查看当前路径下的所有内容
