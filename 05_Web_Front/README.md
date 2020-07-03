# BIZZAN_web_front

> BIZZAN数字资产交易所之web端

## Install Prerequisites
The following dependencies are required to run an instance:

1. NodeJS - 9.11.2
2. Npm - 5.6.0

## Build Setup

``` bash
# install dependencies
npm i

cd 导font目录 管理员打开cmd
主要是windows平台缺少编译环境，
1、先运行： npm install -g node-gyp
2、然后运行：运行 npm install --global --production windows-build-tools 可以自动安装跨平台的编译器：gym
# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

```



## Future
1. 统一改用less,实验可以通过变量覆盖的方式定制主题;
2. iview组件按需引用;
3. exchange.vue等大文件，代码拆分/组件化;


## 前端开发规范
1. 页面使用驼峰法命名，如Exchange.vue,WithdrawRecord.vue,名称为英文单词，并且要能正确描述该模块功能
2. 变量命名禁止使用拼音，特别是拼音缩写
3. 页面比较多时应该使用文件夹做分类
4. 模块中data变量应该尽量少，比较多时应该使用子对象进行管理


