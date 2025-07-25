# HelloGitHub Vol.20
> Passion is the best teacher. **HelloGitHub** inspires your interest in open-source!
<p align="center">
    <img src='https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/cover.jpg' style="max-width:100%;"></img>
</p>

## Table of Contents

Click the **「Table of Contents」** icon at the top-right corner to open the navigation and enjoy a better reading experience.

![](https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/catalog.png)

## Content
> **The content of this issue is as follows**｜Updated on the **28th** of each month

### C#
1、[csharplang](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/dotnet/csharplang)：C# 语言设计官方项目，在这里你可以直接参与讨论。同时还有：
- 语言特色提议
- C# 语言设计会议记要
- 完整的 C# 6 语言规范（草案）
- 语言版本历史摘要


### C++
2、[robomongo](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/Studio3T/robomongo)：免费、开源的 MongoDB 跨平台桌面管理工具，支持 Windows、Linux、Mac


<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/6580000.png' style="max-width:80%; max-height=80%;"></img></p>

### CSS
3、[magic-of-css](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/adamschwartz/magic-of-css)：一套可以让你成为“魔术师”的 CSS 教程（英文）


4、[milligram](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/milligram/milligram)：极简风格的 CSS 框架，而且文件很小


<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/47775741.png' style="max-width:80%; max-height=80%;"></img></p>

### Go
5、[monkey](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/haifenghuang/monkey)：用 Go 语言写的解析器，包含诸多语言特性。入门实践项目，适合新手熟悉 Go 语言和语言解析器入门


### Java
6、[Android-Pay](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/mayubao/Android-Pay)：支持微信和支付宝两种主流支付的集成库，示例代码如下：
```java
//1.创建微信支付请求
WechatPayReq wechatPayReq = new WechatPayReq.Builder()
        .with(this) //activity实例
        .setAppId(appid) //微信支付AppID
        .setPartnerId(partnerid)//微信支付商户号
        .setPrepayId(prepayid)//预支付码
//      .setPackageValue(wechatPayReq.get)//"Sign=WXPay"
        .setNonceStr(noncestr)
        .setTimeStamp(timestamp)//时间戳
        .setSign(sign)//签名
        .create();
//2.发送微信支付请求
PayAPI.getInstance().sendPayRequest(wechatPayReq);

//关于微信支付的回调
//wechatPayReq.setOnWechatPayListener(new OnWechatPayListener);
```


7、[AndroidSwipeLayout](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/daimajia/AndroidSwipeLayout)：[代码家](https://github.com/daimajia)开源的滑动布局库，不用多说什么了。动起手来试试，然后通过阅读代码学习大神们的编程技巧，有一天你也可以做出有价值、流行的开源库


<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/23301468.gif' style="max-width:80%; max-height=80%;"></img></p>

### JavaScript
8、[flowhub](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/yyued/flowhub)：仅 6KB 通过简单的 API & 自由组合的链式写法，轻松订阅管理各类事件流。示例代码如下：
```javascript
import $hub from 'hub-js';

// 定义一个 “test” 监听器
$hub.listen('test', ( data ) => {
    console.log( 'test', data );
});

setInterval(( ) => {
    // 发出 “test” 事件
    $hub.emit('test', { code: 1 });
}, 1000);
```


9、[IDValidator](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/mc-zone/IDValidator)：中国大陆个人身份证号验证，支持 15、18 位身份证号，API 如下：
- `isValid` 验证号码是否合法，合法返回 True，不合法返回 False
- `getInfo` 号码合法时返回分析信息（地区、出生日期、性别、校验位），不合法返回 False
- `makeID` 伪造一个符合校验的 ID


10、[livepython](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/agermanidis/livepython)：可视化、实时追踪展示 Python 代码


<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/105598718.gif' style="max-width:80%; max-height=80%;"></img></p>

11、[nba-go](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/homerchen19/nba-go)：可以用命令终端查看 NBA 比赛，包括比赛开始时间表、实时比分情况、文字直播（英文）等。终端看 NBA，你才是最潮的。安装命令 `npm install -g nba-go`


<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/108231108.png' style="max-width:80%; max-height=80%;"></img></p>

12、[React-Cnode](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/Juliiii/React-Cnode)：适合新手的 React 全家桶项目学习，同时附有作者在开发中的一些[思考](http://www.jianshu.com/p/43c604177c08)


<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/101363122.gif' style="max-width:80%; max-height=80%;"></img></p>

### Kotlin
13、[Flesh](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/Kerr1Gan/Flesh)：如果你是一位想学习一下 Kotlin 的同学，那么 Flesh 是一个适合学习、练手、入门的项目。从中可以学到 Java 与 Kotlin 间的相互调用、爬虫操作。这是个诚意（福利）满满的项目，快去下载、加入到这个项目中吧


<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/102702014.gif' style="max-width:80%; max-height=80%;"></img></p>

14、[kotlin-guides](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/android/kotlin-guides)：这份指南提供了在使用 Kotlin 编写 Android 程序时要遵循的一系列规则


### Python
15、[joblib](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/joblib/joblib)：使用 Python 方便的进行并行计算，示例代码如下：
```python
from joblib import Parallel, delayed
from math import sqrt
Parallel(n_jobs=1)(delayed(sqrt)(i**2) for i in range(10))
```


16、[records](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/kennethreitz/records)：Kenneth Reitz 大神的`for Humans™`系列，Records 是一个支持大多数主流关系数据库的原生 SQL 查询第三方库。API 友好，使用简单、支持命令行模式、功能多样。与此同时该库只有 500 行代码，可以当作入门阅读源码的项目，同时学习大神的编程技巧与习惯，示例代码如下：
```python
import records

db = records.Database('postgres://...')  # 连接数据库
rows = db.query('select * from active_users')  # 执行原生 SQL
# 遍历结果
for r in rows:
    print(r.name, r.user_email)

# 友好的 print 格式
print(rows.dataset)
# username|active|name      |user_email       |timezone
# --------|------|----------|-----------------|--------------------------
# model-t |True  |Henry Ford|model-t@gmail.com|2016-02-06 22:28:23.894202

# 支持将结果导出成不同格式
print(rows.export('json'))  # json
print(rows.export('csv'))  # csv
print(rows.export('yaml')) # yaml
rows.export('df')  # pandas 的 df 对象
with open('report.xls', 'wb') as f:
    f.write(rows.export('xls'))  # xls
```


17、[tldr-python-client](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/tldr-pages/tldr-python-client)：Linux man 解释一般都太长了，很多时候我们就想用一些比较常用的命令，但却记不起来。这个时候如果不 Google，就可以用 [tldr（简化 man 的工程）](https://github.com/tldr-pages/tldr)。该项目为 Python 客户端实现


<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/17429141.png' style="max-width:80%; max-height=80%;"></img></p>

18、[zdict](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/zdict/zdict)：方便的终端字典工具，支持多种字典和参数、翻译结果高亮、以及交互模式查询。安装命令 `pip install zdict` （仅支持 Python3）。查询效果如下图所示：


<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/34254274.png' style="max-width:80%; max-height=80%;"></img></p>

### AI
19、[angel](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/Angel-ML/angel)：腾讯开源的高性能分布式机器学习平台，具有广泛的适用性和稳定性，模型维度越高。它将高维度的大模型合理切分到多个参数服务器节点，并通过高效的模型更新接口和运算函数，以及灵活的同步协议，可以实现各种高效的机器学习算法


<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/89322848.png' style="max-width:80%; max-height=80%;"></img></p>

### Other
20、[github-cheat-sheet](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/tiimgreen/github-cheat-sheet)：GitHub 和 Git 的秘籍，[中文](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.zh-cn.md)


21、[hangzhouYunQi2017ppt](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/Alibaba-Technology/hangzhouYunQi2017ppt)：2017 杭州云栖大会精华 PPT，[移步到阿里云下载与浏览](https://yq.aliyun.com/articles/231065)


22、[nodebestpractices](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/goldbergyoni/nodebestpractices)：Node.js 最佳实践列表（英文）


23、[vim-game-code-break](https://hellogithub.com/en/periodical/statistics/click?target=https://github.com/johngrib/vim-game-code-break)：Vim 中的打砖块游戏。在 Vim 实现打砖块游戏的插件。

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/20/94041124.gif' style="max-width:80%; max-height=80%;"></img></p>



<p align="center">
    <a href="https://github.com/521xueweihan/HelloGitHub/blob/master/content/en/HelloGitHub19.md">『Previous』</a> | <a href='https://github.com/521xueweihan/HelloGitHub/issues/899'>Feedback</a> | <a href="https://github.com/521xueweihan/HelloGitHub/blob/master/content/en/HelloGitHub21.md">『Next』</a>
</p>

---
<p align="center">
    👉 <a href='https://hellogithub.com/en/periodical'>Submit open-source project!</a> 👈<br>
</p>

## Sponsor


<table>
  <thead>
    <tr>
      <th align="center" style="width: 80px;">
        <a href="https://www.compshare.cn/?utm_term=logo&utm_campaign=hellogithub&utm_source=otherdsp&utm_medium=display&ytag=logo_hellogithub_otherdsp_display">          <img src="https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/ucloud.png" width="60px"><br>
          <sub>UCloud</sub><br>
          <sub>超值的GPU云服务</sub>
        </a>
      </th>
      <th align="center" style="width: 80px;">
        <a href="https://www.upyun.com/?from=hellogithub">
          <img src="https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/upyun.png" width="60px"><br>
          <sub>CDN</sub><br>
          <sub>开启全网加速</sub>
        </a>
      </th>
      <th align="center" style="width: 80px;">
        <a href="https://github.com/OpenIMSDK/Open-IM-Server">
          <img src="https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/im.png" width="60px"><br>
          <sub>OpenIM</sub><br>
          <sub>开源IM力争No.1</sub>
        </a>
      </th>
      <th align="center" style="width: 80px;">
        <a href="https://www.qiniu.com/products/ai-token-api?utm_source=hello">
          <img src="https://raw.githubusercontent.com/521xueweihan/img_logo/master/logo/qiniu.jpg" width="60px"><br>
          <sub>七牛云</sub><br>
          <sub>百万 Token 免费体验</sub>
        </a>
      </th>
    </tr>
  </thead>
</table>


## Disclaimer
<a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width: 0" src="https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png"></a><br>
This work is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.
