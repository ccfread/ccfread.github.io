# 关于本站  

2014年12月23

注册阿里云账户并购买服务器

2015年1月27

购买域名~~ilomoo.com~~(23年4月售出)，使用wp建立第一个博客站点，写一些生活和工作

2015年4月7

总历时2个多月终于备案通过。京ICP备15015906号

2015年5月7

阿里云购买~~ihbzy.com~~

2015年8月6

服务器续费太贵了，学生负担不起，转战虚拟主机，免费版，2年期限

2017年3月4

重新开通阿里云ECS

2017年4月20

购入~~lrbiji.com lrbiji.cn ilomoo.net.cn~~(21年没再续费),作为工具和导航站

2022年2月6

主机到期停止服务，当时觉得博客写的一塌糊涂就没把写的东西做备份(现在挺后悔)。云解析DNS付费版实例释放

2023年4月19

又回到阿里购买服务器，继续使用wp建立博客站点，依旧写一些生活琐事并记录一下学习编程的过程(自学JAVA)，不知道这次能记录多久，毕竟我已经是一个父亲

2023年5月

相继购买域名 ~~ziqiezi.com~~ / ezxmt.com(主站) / ezxmt.cn / lazymt.com 

2023年5月24

购入CorePress Pro主题。感觉这个主题响应速度不错，页面也比较简洁，暂时足够我使用了

2023年……

未完待续。希望全家平平安安，孩子顺利成长。如果你有幸看到这里，也祝陌生的你一切顺利，心想事成。



# fread 的测试内容

这里是文章的内容，下面还可以写代码

```Java
 public static void main(String[] args){
    System.out.print("hello world!");
 }
```

 ```js
grunt.initConfig({
  assemble: {
    options: {
      assets: 'docs/assets',
      data: 'src/data/*.{json,yml}',
      helpers: 'src/custom-helpers.js',
      partials: ['src/partials/**/*.{hbs,md}']
    },
    pages: {
      options: {
        layout: 'default.hbs'
      },
      files: {
        './': ['src/templates/pages/index.hbs']
      }
    }
  }
};
```
目前还可以点击现在的地址[悠闲小馒头](https://ezxmt.com "悠闲小馒头")

<!-- 这里使用的就是已经定义好的地址，方便多次使用-->
还可以用这种方式点击[小馒头][freadhttp]

<!-- 定义一个标签，获取叫引用链接，什么地方都能直接使用 freadhttp -->
[freadhttp]:https://www.ezxmt.com "呦，小馒头"
还能展示图片呢，怎么展示呢，看下面的图，这个图片能点击
![这里是图片的 名字](https://octodex.github.com/images/stormtroopocat.jpg "鼠标放上去了")

给汉子加拼音，或者同类效果
    
[醊]^(zhui)

另一种展示图片的方案
![Alt text][srcccc]

[srcccc]: https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat"