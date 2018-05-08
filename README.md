
# 个人简历
## 个人信息

姓名：彭荣辉

学历：硕士

学校：杭州电子科技大学

专业：电子与通信工程

职位：前端开发

电话 13336133646

微信：a1341660796
## 实习意向
应聘实习职位：前端开发 

期望实习地点：杭州		

## 作品(项目)

### MusicRadio（音乐电台）

预览地址 https://pengxiaohui00.github.io/MusicRadio/code/index.html

技术栈：jQuery/SS3/响应式

作品功能介绍：

1.这是一个简单的音乐电台，拥有41种不同的音乐风格类型供你选择并随时切换。

2.还可以选择你喜欢的音乐，并添加到我的最爱歌单中，并本保存到浏览器本地，下次登入一直保存你喜欢的歌曲，除非你主动删除。

3.还有很酷的歌词提示，且具有旋转效果。

4.当然切换下一首，播放，暂停，时间，进度条显示等简单音乐播放器的一切效果它都有。

5.另外它还有满屏显示和响应式页面。

技术细节介绍：

1 .使用jQuery库来方便并大大的简化了代码。

2.通过Jonsp的方法请求数据，解决了同源策略的问题。

3.通过自定义事件的思路，使整体分为底部切换分类，和歌曲播放等两个模块并互不干扰。

4.通过模块化，封装函数的思路，先初始化，绑定事件，具体事件功能，请求数据，渲染数据等等，增加代码逻辑性，和复用性，极大简化的代码，并且减少了全局变量污染，很方便后期调试。

5.满屏通过设置把高度设置成100%,把高度通过设置vh，宽度通过媒体查询，实现响应式。

6.通过JQuery动画animate与DOM事件结合实现切换音乐风格类型，并通过加锁方法优化了功能。

7.通过audio对象的方法与DOM事件结合，实现音乐切换下一首，，播放，暂停，时间显示。

8.百度外链不允许他人播放，通过设置referrer，页面来源的请求头为空，解决bug.

9.监听音乐播放时状态，在音乐播放时显示相应的时间，进度条；通过定时器实现时时更新播放状态。

10.歌词匹配，通过把歌词字符串切割成数组，通过正则表达式匹配对应时间，转化成对象，属性为时间，值为对应歌词，然后在播放状态更新时添加对应歌词。

11.歌词旋转，音乐播放时把对应每行歌词，分割成单个字然后被span包含，通过定时器，给每个字依次添加animate.css中对应的旋转样式
。
12.把你选中喜欢的歌曲，收集到你最爱的歌单上，通过localStorage存储到浏览器本地。


### DoubanMovie（移动端豆瓣电影） 

预览地址 https://pengxiaohui00.github.io/project/DoubanMovie/index.html      

技术栈：移动端/jQuery/CSS3/响应式

项目功能介绍：

1.有三块内容分别展示豆瓣高分电影，最新的北美票房榜单电影，和与搜索相关的电影

2.详细展示了电影的相关信息如评分，导演，主演，年限，分类，被收藏数，并可点击跳转到对应页面，浏览详细信息；

3.点击底部相应图标，迅速切换相应内容，几乎无任何卡顿；

4.当请求数据时，显示加载图标，数据到来后隐藏

项目技术细节介绍：

1.设置meta，解决页面适配，与300 毫秒点击延迟；

2.设置动态 rem，媒体查询，实现响应式；

3.整体只设计一个页面，切换相应内容，减少卡顿；

4.通过封装函数，初始化，绑定事件，增加功能，减少变量污染与简化代码。

5.通过Jonsp的方法请求数据，解决了同源策略的问题。

6.将10条数据拼装成DOM展示在页面上，当滚动条底部区域时再次发送请求，并通过加锁与函数节流来优化功能；

### News（瀑布流新闻）

预览地址: https://pengxiaohui00.github.io/waterfallNews/News/news.html

技术栈：jQuery/CSS3/瀑布流

项目功能介绍：

1.通过瀑布流方式排列展示新闻图片内容

2.随着滚动条移动不断更新新闻

项目技术细节介绍：

1.通过Jonsp的方法请求数据，获取page=1的10条数据，并通过加锁优化功能；

2.把10条数据拼装成dom放到页面；

3.使用瀑布流去摆放dom位置，先通过计算出一排能够容纳几列元素，然后寻找各列之中所有元素高度之和的最小者，并将新的元素添加到该列上，然后继续寻找所有列的各元素之和的最小者，继续添加至该列上，如此循环下去，直至所有元素均能够按要求排列为止；

4. page++

5.load出现在可视区域内时，再次获取page的10条数据，重复循环；

## 自定义的一些组件

 代码地址：https://github.com/pengxiaohui00/module

#### 小作品：

 预览地址
 
###  musicPlayer https://pengxiaohui00.github.io/project/musicPlayer/music.html

### TheUserLogin https://pengxiaohui00.github.io/project/TheUserLogin/index.html

### ASongOfIceAndFire https://pengxiaohui00.github.io/project/ASongOfIceAndFire/index.html

### shoppingTrolley https://pengxiaohui00.github.io/project/shoppingTrolley2/index.html

### LaayLoading https://pengxiaohui00.github.io/project/LazyLoading/index.html

### waterfall https://pengxiaohui00.github.io/project/waterfall/index.html

### node.js搭建静态服务器 https://github.com/pengxiaohui00/node-server/tree/master/server1


## 博客地址  https://www.jianshu.com/c/73916acf9fd1

## 实习经历 
公司：杭州新华三通信技术有限公司

职位：园区交交换机部门，网络测试工程师

技术：计算机网络基础，命令行，tcl脚本，c语言；

工作内容：

ctc盒子OSPF路由特性测试 156/156;

ctc盒子OSPFV3路由特性测试 105/105;

## 专业技能
熟悉Javascript、Html/Html5、Css/Css3等前端开发技术，

熟悉jquery，对Vue有一定认识；

了解node.js，对npm与webpack的使用一定认识；
        
对浏览器兼容，与前端性能优化有一定了解；

了解计算机网络，TCP/IP，HTTP协议,C语言及常用Linux命令行；

了解Photoshop，firework，sublime,webstorm,git等前端工具的使用经验；

## 教育经历	
 2016.9-2019.4  	   杭州电子科技大学 	 电子信息学院          电子与通信工程 	       硕士
 
 2012.9-2016.6       赣南医学院         电子信息工程学院       生物医学工程          学士
 
 ## 所获奖项
 
 计算机二级C语言，
  
  英语四级，
  
  研究生电子设计大赛省3等奖
  
  研究生2等奖学金2次；     
  
 ##  	自我评价
 
 本人性格开朗，乐观豁达，待人友好，做事习惯专一认真。学习能力强。熟悉前端开发，具有良好的分析解决bug能力。喜欢编程，喜欢挑战，Bug不除，寝食难安，比较喜欢晚上通宵敲代码，不过一般是到晚上3，4点。具备较强的自我管理能力，拥有较好的团队协作和沟通能力，有强烈的责任心。期待能与技术大佬们一起工作，因为那样能使我少走很多弯路，学习到更多知识，并且能鞭策自己以更快的速度进步。
 
 
 
