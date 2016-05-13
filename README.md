# MRedrock Exam 2016

## 聚餐

**聚餐！( 2016.5.14 晚 )**    —— 具体另行通知<br/>
问我为什么这个时间？我会告诉你为什么春节要贴春联<br/>
请同学们遵守移动的传统，没有正当理由不许请假 （听说来者加分，不来扣分哟<br/>

## 考核

- 考核题目：一个十分简易的使用QQ音乐数据但又不是QQ音乐的**联网播放器**
- 考试时间：**5.14 0:00 - 5.15 24:00 ( 共48小时 )**
- 考核地点：不允许在飞机上参加本次考核，其他任意
- 考核对象：**Android**、**iOS**、**Win**
- 提交方式：[Github](https://github.com/)  ( 导师请收齐

### 注意事项

- Android 的同学们请兼容到 **API 14** （ 一点都不过分吧？
- 不准使用第三方库，自己封装的可以
- 请编写好 [Github](https://github.com/) 的 **README** 最好有录屏 （ 嗯！我懒
- 请在5.15 24:00之前 `commit`，之后的 `commit` 一律无效
- 导师不回答任何和代码有关的问题，请吃饭可以，但不加分
- 请放心使用 [Google](https://www.google.com/)、[Bing](https://www.bing.com/) 等搜索引擎

### API
[ShowAPI - QQ音乐API](https://www.showapi.com/api/lookPoint/213/4)
> 文档写得很清楚，自己去注册一个获取下权限！做不到这个的望天吧，说不准老天会帮你。
> 文档左侧有分类，注意有 **3** 个 API 哟！

### 具体内容

考核内容分 **必做题** 与 **选做题**  ( 会标注 ) 个方面，所以请不要被题目吓到，选做是干嘛？加分撒！<br/>
遇到难题就跳，不要恋战！必做题也不见得全要做出来，赶快前进！<br/>
本次考核 UI 不限定，完成功能为主 （ 三个平台我也不好限定 UI，你说是么？<br/>

#### **一、热门榜单**

1. 使用选项卡切换热门内容 (欧美、内地等)
2. 热门内容用列表呈现
3. 每一项显示歌曲名、歌手名、专辑图片 (小图)、播放按钮 ( 播放并添加到播放列表)、下载按钮
4. **[ 选做 ]** 多选添加到播放列表

#### **二、查询页面**

1. 和热门榜单显示的东西差不多，还不都是歌曲……
2. 和榜单不同，有 `page` 参数，请做好换页

#### **三、歌曲详细**

1. 显示歌曲名、歌手名、专辑图片 (大图)
2. 播放进度显示
3. 开始/暂停播放等常见播放器操作
4. **[ 选做 ]** 滚动歌词

#### **四、播放列表**

1. 当然得有常见的播放器操作 ( 显示当前播放、换歌、开始、暂停等 )
2. 单曲循环、列表循环、顺序播放、随机播放
3. 移除歌曲
4. 请做好保存，不要下次打开APP记录都没了！( 请使用 **数据库** 存储，嗯哼

#### **五、歌曲播放**

1. 流媒体播放
2. **[ 选做 ]** 本地音乐播放 
3. **[ 选做 ]** 为了在没有wifi的情况下，不出现耗流量情况，又要听一些听过的歌 （ 聪明的你应该知道怎么做才对

#### **六、歌曲下载**

1. 下载成功……
2. **[ 选做 ]** 下载列表界面显示下载进度
3. **[ 选做 ]** 通知栏显示下载进度

#### **七、后台操作**

1. **[ 选做 ]** 后台听歌
2. **[ 选做 ]** 后台下载

#### **八、还想说点什么**

唉、其实这些都不重要。看了这么多，你眼前出现了个啥？不就是个普通的播放器么！
就是嘛、按照自己日常使用的播放器功能去做就是了。<br/>
上面说的那么多，也就是帮你整理一下功能罢了。还是鼓励 **自由发挥**（ 这点也很重要<br/>
以上功能做不出来可以 **跳过**，当然对 **得分有一定影响**，但还是要想办法让你APP看起来 **完整**，不要看起来什么功能都有，结果全是假的来见老夫，我会踢人的我跟你讲。<br/>

### 其他

- 清晰的代码、合理的封装加分
- 对细节逻辑的处理得当加分 ( 多乱操作一下，用户和你的操作方法是不同的
- 舒服的视觉交互加分 ( 如果我看不懂怎么用，不要怪我
- 做好图片之类的缓存加分
- 有余力的同学自己添加合理的功能加分 ( 不合理会被当做是套路作文无视
