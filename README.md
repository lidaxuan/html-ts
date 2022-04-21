<!--
 * @Description: 
 * @Author: 李大玄
 * @Date: 2022-04-21 14:13:25
 * @FilePath: /html-ts/README.MD
-->
在html引入 .ts 文件实现热加载

不是有 tsc

在 ts 中如何加载第三方 模块


一个项目，是用TypeScript编写的，但是html中引入了.ts文件后报错了，有没有办法跳过tsc这个编译命令，不然每次都需要Tsc编译一下后再启动，有点麻烦

描述： 想跳过tsc这个命令，直接在html中引入.ts文件

.d.ts 就是对逻辑代码的补充说明


## 第一种

1.  `tsc --init` 生成 `tsconfig.json`

2. `npm install parcel-bundler --save-dev`

3. `npm init  ` 生成package.json
    加入命令 "dev": "parcel ./index.html"

4. 启动项目 `npm run dev`




`npm i @type/express --save-dev`