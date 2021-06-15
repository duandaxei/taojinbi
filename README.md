# taobao_taojinbi
本项目主要用于自动执行淘金币及芭芭农场相关任务，**后续代码持续更新，转载引用请注明出处，你的☆就是我的动力**

# 测试环境
华为P30Pro + [autojs4.1.1](https://share.weiyun.com/owu3tBNr) + [淘宝v10.1.0](https://www.wandoujia.com/apps/32267/history)
(*华为P30Pro屏幕大小为1080x2340,此分辨率对特殊任务支持最佳*)

# 脚本功能列表
 - 自动执行淘金币所有浏览任务
 - 自动执行[逛好店领一大波金币]任务 (包含浏览10s+10金币任务/收藏店铺+10金币)
 - 自动执行[逛蚂蚁庄园喂小鸡]任务
 - 自动执行[签到领取话费充值金]任务
 - 自动执行[淘宝成就签到/月账单任务]
 - 自动执行[淘宝人生逛街领能量]掷色子任务 (需截图权限)
 - 自动执行[逛农场领免费水果]任务 (需截图权限,包括全部子任以及支付宝芭芭农场任务)
 - 自动执行[蚂蚁森林]任务,收取好友能量 (需截图权限)
 - 自动执行[淘金币夺宝]任务
 - 自动执行[天天步数红包赛]任务
 - 浏览任务完成立即返回，无需额外等待
 
**关于芭芭农场升级0.01%的2种解决方法：方法1:在淘宝中执行完任务后关闭autojs，然后在支付宝中升级；方法2:在手机应用设置中清除淘宝的本地数据，重新登录淘宝后再升级 (推荐方法1)**

关于‘宝卡’任务，本人淘金币列表中无该任务，因此无法测试。若无法成功执行，请在参数配置页“简单任务跳过关键字”中添加对应任务关键字，即可跳过该任务

# 更新日志

**v1.7.2** 2021年6月15日21:23:04
1. 阅读小说卡顿问题
2. 淘金币夺宝，兑换关键字修改问题
3. 红包签到跳转失败 (后续可能使用url进行跳转)

**v1.7.1** 2021年6月2日21:23:04
1. 喂小鸡任务直接返回
2. 简单任务跳过六一淘金币专场活动

**v1.7.0** 2021年5月31日23:18:43
 1. 淘金币新增618喵币活动 (只在淘金币执行一次)
 2. 解决部分简单浏览任务下滑问题
 3. 阅读小说转特殊任务

**v1.6.10** 2021年5月16日11:03:51
1. 解决芭芭农场"精选"任务下滑才时间过短问题
2. 解决淘宝人生掷色子任务中“神秘礼物”无法取消问题

**v1.6.9** 2021年5月13日23:06:38
1. 解决芭芭农场"精选"任务下滑才得奖励问题
2. 添加"每日领红包任务"
3. 解决去“天猫APP”任务，但没有安装天猫的问题

**v1.6.8** 2021年5月3日15:16:44
1. 解决浏览精选宝贝，下滑才计时的问题

**v1.6.7** 2021年4月25日21:31:14
1. 淘宝人生加载过慢
2. 收藏店铺关键字更新为‘订阅+10’

**v1.6.6** 2021年3月26日17:59:33
1. 解决消消乐升级后，手机back键无效问题(必须点击左上角图标- -)以及跳过指定界面

**v1.6.5** 2021年3月16日20:11:36
1. 解决支付宝芭芭农场点击领取无效问题
2. 解决淘金币夺宝名称更改问题

**v1.6.4** 2021年3月13日10:11:36
1. 解决逛好店领大量金币任务的关键字(关键字被添加了浏览10秒)被修改问题
2. 解决步数打开任务的关键字被修改的问题
3. 解决去天猫APP任务的子标题关键字被修改的问题
4. 解决喂小鸡任务的关键字被修改问题

**v1.6.3** 2021年3月12日17:33:06
1. 取消店铺订阅，淘宝版本升级，我的主页中关注店铺修改为订阅店铺
2. 解决淘宝人生掷色子关键字更名问题和加载过慢问题
3. 淘宝成就签到关键字更名问题

**v1.6.2** 2021年3月9日20:35:57
1. 解决芭芭农场淘宝人生装扮抽奖后无奖励问题
2. 解决支付宝芭芭农场任务不执行问题

**v1.6.1** 2021年3月3日19:35:24
1. 添加[简单任务跳过关键字]配置,可跳过不想执行的简单浏览任务，比如刚出的“根据图片找商品同款”和“步数”打卡任务,目前内容为“商品同款”，多个可使用‘|’分割
2. 修改进入芭芭农场的进入方式为：我的淘宝->芭芭农场

**v1.6.0** 2021年3月1日19:07:42
1. 添加芭芭农场内全任务(包括支付宝芭芭农场)，可单独执行。关于芭芭农场升级0.01%的2种解决方法：方法1:在淘宝中执行任务后，关闭autojs,在支付宝中升级；方法2:在手机应用设置中清除淘宝的本地数据，重新登录后再升级 (推荐方法1)
2. 删除淘宝通知权限权限任务
3. 添加每月一次的[淘宝成就月账单]任务


**v1.5.12** 2021年2月19日19:23:43
1. 新增[淘宝人生新春抽红包任务]，解决该任务未执行导致淘宝签到任务无法出现问题
2. 解决薅羊毛充值金无法领取问题
3. 取消年货节任务

**v1.5.11** 2021年2月12日21:34:22
1. 年货节添加任务[淘宝无门槛红包]和[淘宝人生]
2. 夺宝任务,[立即参与]按钮->[立即夺宝]
3. 步数打卡为修改为简单浏览任务

**v1.5.10** 2021年2月1日21:35:28
1. 淘宝删除了“年货节浇灌福气”入口，解决无法进入该活动问题

**v1.5.9** 2021年1月31日10:03:16
1. 解决农场合种“继续努力”弹窗问题
2. 淘金币夺宝“查看上一次奖励”无法返回问题(吐槽一下1次居然增加到200淘金币了)

**v1.5.8** 2021年1月29日20:05:59
1. 更新[取消所有店铺关注]任务
2. 淘宝年货任务新增领取次日奖励,新增[浏览金币小镇任务]
3. 解决100金币夺宝任务"去“我的奖品”查看"弹窗问题

**v1.5.7** 2021年1月26日19:02:03
1. 解决[活力步数兑换红包任务]点击免费领取失效问题
2. 解决[领话费充值金任务]卡住问题

**v1.5.6** 2021年1月23日12:46:30
1. 解决新版支付宝蚂蚁森林界面更新问题
2. 修复年货节浇灌福气btn_col为空报错问题

**v1.5.5** 2021年1月22日20:04:48
1. 解决消消乐返回界面调整为“暂时离开和集福气”而导致无法返回到主界面问题
2. 发布[taojinbiv1.5.5]apk版，支持在线秒检测并更新到最新版本

**v1.5.4** 2021年1月21日11:54:11
1. 修复年货节浇灌福气运行错误问题，暂未发现升级才加0.02%的原因，实在不行请重装最新淘宝手动执吧

**v1.5.3** 2021年1月20日20:46:10
1. 淘宝v9.0.0测试年货节浇灌福气任务
2. 新版年货节浇灌福气任务默认执行2次，解决漏掉新刷新的简单任务(不同的淘宝用户，特殊任务不一样)

**v1.5.2** 2021年1月19日19:59:32
1. 修复掷骰子任务-弹窗礼包问题
2. [去年货节浇灌福气]界面布局更新，添加了[消消乐任务]，非P30Pro手机建议单独执行[去年货节浇灌福气]全任务

**v1.5.1** 2021年1月18日20:34:58
1. 解决[年货节浇灌福气]任务中"集福气"按钮的text变化问题
2. 恢复[加载配置]按钮,解决脚本最新配置和用户配置不匹配问题(用户自定义配置后，请和最新脚本进行比对后再加载，否则可能会导致新脚本一些功能因为旧的配置而无法使用)

**v1.5.0** 2021年1月17日19:28:30
1. 更新UI界面，用户可以在主主界面选择执行选定的任务，在配置界面配置对应的任务关键字,用户可自行修改(**解决活动经常更换名称问题**)
2. 新增[年货节浇灌福气]任务,用户可在淘金币列表选择中勾选[年货节浇灌福气]任务进行执行，若未勾选[执行福气全部子任务]，只会执行[年货节浇灌福气]的签到任务和施肥;用户也可单独执行该任务(在程序主界面下拉可见，单独执行默认运行全部子任务)
3. 添加[保存当前配置]按钮用于保存当前用户的选择项和关键字配置信息，下一次启动默认自动加载上传保存的配置信息

**v1.4.2** 2021年1月14日19:19:03
1. 修复直播活动更新后无法返回问题
2. 延长点击关注店铺时长，解决网络卡顿导致关注不成功问题
3. 发布[淘金币v1.4.2]apk版，**请提前为程序开启无障碍服务和悬浮框权限**
4. 由于个人问题(年后换工作)，以后将不定期维护该项目，望谅解

**v1.4.1** 2021年1月12日19:46:43
1. 修复[淘金币夺宝任务]下注太快无奖励问题
2. 添加[保存选择项状态]按钮用于保存当前用户的任务选择状态

**v1.4.0** 2021年1月11日20:30:34
1. 更新UI界面，所有特殊任务都在列表中可选择执行
2. 添加[淘金币夺宝任务],需花费100淘金币，做人还是需要点理想，说不定就中了呢
3. 新增[直接启动支付宝蚂蚁森林偷取好友能量]按钮,需提前添加蚂蚁森林到首页
4. 新增[取消所有关注的店铺]按钮用于取消所有关注的店铺，**慎用**

**v1.3.11** 2021年1月10日09:36:43
1. 淘宝升级到v9.18.0
2. 修复淘宝新版本[天天红包赛]弹窗问题

**v1.3.10** 2021年1月7日19:50:28
1. 修复[关注+10]单击问题，感谢Sirius2s的提醒
2. 发布[淘金币v1.3.10]apk版

**v1.3.9** 2021年1月3日21:58:23
1. 删掉淘金币夺宝任务(下注才能获取能量)，不知道你们中过没有，反正我全输光了-  -

**v1.3.8** 2020年12月29日19:42:37
1. 更新[淘金币夺宝任务]的关键字名称

**v1.3.7** 2020年12月28日19:32:31
1. 应网友请求，添加[去天猫APP领红包任务]到任务选择栏中

**v1.3.6** 2020年12月24日19:22:57
1. 解决消消乐完成消除回到主界面，出现[再玩一次]弹窗问题
2. 淘金币auto.js-v1.3.6全任务视频演示：https://www.bilibili.com/video/BV1Dt4y1k7xq/

**v1.3.5** 2020年12月23日20:13:04
1. 解决[淘宝吃货任务]弹窗导致无法返回问题
2. 解决[消消乐任务]弹窗导致无法返回问题
3. 在[开启淘宝通知权限任务]中暂时关闭终端显示
4. 删除了活力中心脚本，有需要的可在[v1.3.4页面](https://github.com/JavisPeng/taojinbi/tree/v1.3.4)下载
5. 所有任务默认检查执行3次，每次执行后检查是否在淘金币列表界面，不在则跳转到该界面，防止back函数导致乱跳转问题
6. 发布[淘金币v1.3.5]apk版

**v1.3.4** 2020年12月22日19:46:20
1. 淘金币新增[淘宝通知权限任务],开启后会再执行关闭 (默认在通知关闭下才有该任务,在华为机上测试通过)
2. 查找‘赚金币’按钮时间由3秒修改为8秒，兼容部分机型卡顿问题
3. 个人精力有限，今后只重点维护淘金币任务，因而把活力中心代码分离出来(huoli.js)，后期不在维护该脚本，有需要的可在[v1.3.4页面](https://github.com/JavisPeng/taojinbi/tree/v1.3.4)下载
4. **至此淘宝币全任务在P30Pro上测试通过**，当然不包含特定时间刷的任务和下单任务

**v1.3.3** 2020年12月21日19:50:31
1. 用户可在文件开头中定义，需跳过不执行的简单浏览任务主题关键字
2. 用户可在文件开头中定义[去天猫APP领红包任务]是否执行
3. 解决活力中心[1000步换红包任务]执行失败问题
4. 发布[淘金币v1.3.3]apk版

**v1.3.2** 2020年12月20日11:44:35
1. 修复淘金币在任务列表中继续返回导致任务结束问题,
2. 淘宝人生掷色子任务中，添加了自动领取包裹和奖励，解决任务卡住问题

**v1.3.1** 2020年12月19日13:18:57
1. 淘金币任务列表新增[100淘金币夺宝任务]
2. 解决活力中心训练时无法单击关闭按钮问题

**v1.3.0** 2020年12月18日19:56:49
1. 应网友请求，附加**活力中心任务**(包括自动浏览任务和自动点击训练按钮),默认在淘金币完成后执行，若只执行活力中心任务,可在main函数注释掉taojinbi_task()这行
2. 整合特殊任务[逛直播间任务]到简单浏览任务中

**v1.2.3** 2020年12月17日20:50:41
1. 消消乐和蚂蚁森林任务中暂时隐藏终端,对应任务结束后再显示 (不隐藏可能收取不到全部能量)
2. 发布[淘金币v1.2.3]apk版

**v1.2.2** 2020年12月16日19:36:39
1. 新增蚂蚁森林任务，支持自定义'找能量'收取好友能量的次数
2. 解决'天猫领红包任务'，取消了'继续逛逛'按钮问题

**v1.2.1** 2020年12月14日19:57:06
1. 新增消消乐任务，需截图权限，目前在测试P30Pro上测试通过
2. 考虑到不同的机型，某些需截图权限的特殊任务可能会不兼容，启动时添加了可选的额外执行的任务： ['淘宝人生掷色子任务', '逛农场领免费水果任务', '消消乐任务']
3. 添加了APK发布版，用户可直接运行

**v1.2.0** 2020年12月13日20:52:53
1. 简化代码删减了双12的部分
2. 对需要截图功能的[淘宝人生逛街领能量]和[逛农场领免费水果] 设置了是否执行的全局变量，用户可选择是否执行该任务
3. 任务执行等待时间设置为全局变量，默认为15秒

**v1.1.4** 2020年12月12日21:04:28
1. 修复淘金币看直播任务，有时不能返回问题

**v1.1.3** 2020年12月11日20:13:13
1. 修复天猫app没安装，等待过长问题
2. 修复特殊任务后，新出简单浏览任务遗漏问题
3. 无法修复'双12红包兑现红包太少问题'

**v1.1.2** 2020年12月10日20:38:12
1. 解决淘金币执行过程中会返回到主页面问题(本质是按钮单击没有生效)
2. 把淘宝人生、逛好店任务、喂小鸡任务、逛直播间任务添加到特殊任务中
3. 解决芭芭农场双12任务后，淘金币没有肥料问题

**v1.1.1** 2020年12月9日19:36:44
1. 修复逛新加任务不能获取问题 
3. 某些任务(拍照识图)只在最新版淘宝中才存在,当前淘宝已换成最新版v9.16.0,经测试金币还是同样的奖励

**v1.1.0** 2020年12月8日19:51:51
1. 代码基本重构，为适应不同机型，添加了截图查找功能(**需授予截图权限**)
2. 添加任务运行选择功能，可单独执行任务

# 使用说明
## Auto.js中运行
1. 下载 [autojs4.1.1](https://share.weiyun.com/owu3tBNr)
2. 在电脑端下载taojinbi.js文件，使用电脑端qq或微信发给手机端
3. 导入js文件到autojs(可直接在微信/QQ/文件浏览中选择使用其他方式打开)
4. 在autojs中开启无障碍服务并点击运行导入的js文件

auto.js视频运行教程:https://www.bilibili.com/video/BV1Dt4y1k7xq/


## 淘金币app运行
1. 在[release页面](https://github.com/JavisPeng/taojinbi/releases)下载taojinbi.apk并安装
2. 为淘金币开启无障碍服务和悬浮框权限(悬浮框权限在华为手机：设置->应用->应用功能->淘金币->显示在其他应用的上层->允许)

淘金币app视频运行教程：https://www.bilibili.com/video/BV1kp4y1q7CD/


# 免责声明
为本人Auto.js学习交流的开源非营利项目，仅作为程序员之间相互学习交流之用，使用需严格遵守开源许可协议。严禁用于商业用途，禁止使用进行任何盈利活动。对一切非法使用所产生的后果，本人概不负责。
