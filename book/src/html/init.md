# 一级标题

## 二级标题

...

###### 六级标题

---

### 文字效果

**这是加粗的文字**

_这是倾斜的文字_

**_这是斜体加粗的文字_**

~~这是加删除线的文字~~

---

### 引用内容

> 这是引用内容 adfga 这是引用内容 adfga 这是引用内容 adfga 这是引用内容 adfga
>
> > 引用内容
> >
> > > 引用内容

---

### 插入图片

![blockchain](https://upload-images.jianshu.io/upload_images/6860761-fd2f51090a890873.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/550/format/webp '区块链')

---

### 超链接

/超链接名/(超链接地址 '超链接 title')title 可加可不加

[简书](http://jianshu.com 'jianshu')

[百度](http://baidu.com)

## 列表

### 无序列表

语法：无序列表用 - + \* 任何一种都可以

- asdf

* sngib

- aobfo

### 有序列表

1. 列表内容
2. 列表内容
3. 列表内容

### 列表嵌套

语法 ：上一级和下一级之间敲三个空格即可

- 一级无序列表内容
  - 二级无序列表内容

## 表格

| 姓名 | 技能 | 排行 |
| ---- | :--: | ---: |
| 刘备 |  哭  | 大哥 |
| 关羽 |  打  | 二哥 |
| 张飞 |  骂  | 三弟 |

## 代码

语法：单行代码：代码之间分别用一个反引号包起来

`var a=10;`

代码块：代码之间分别用三个反引号包起来，且两边的反引号单独占一行

```
function fun(){
	echo "这是一句非常牛逼的代码";
}
fun();

```

## 流程图

````flow
st=>start: 开始
op=>operation: My Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
````

## 目录结构

<pre>
│  .gitignore          # 忽略文件,比如 node_modules
│  package.json        # 项目配置
│  README.md           # 项目说明
│  index.html          # 首页
│
├─ webpack.base.config.js         # webpack 基础配置
├─ webpack.dev.config.js          # webpack 开发配置
├─ webpack.prod.config.js         # webpack 生产配置
│
│
├─node_modules
│
├─dist                 # 打包完的文件会自动放在这里
│
└─src
    ├─ main.js         # 启动配置
    │
    ├─ router.js       # 路由配置
    │
    ├─components       # 组件
    │       │
    │       └─ app.vue # 入口组件,内含路由和公共部分
    │
    ├─views            # 视图(即路由)
    │
    ├─directives       # 自定义指令
    │
    ├─filters          # 自定义过滤器
    │
    ├─config           # 放置一些配置文件
    │
    ├─libs             # 放置一些工具函数
    │
    ├─images           # 放置图片
    │
    ├─styles           # 放置css
    │    │
    │    ├─ common.css # 通用css
    │    │
    │    └─ reset.css  # 页面初始化css
    │
    ├─fonts            # 放置iconfont字体
    │
    │
    └─template         # 放置html模板,webpack依赖此文件生成所需的html
         │
         │
         └─ index.ejs # 默认的html模板

</pre>
