# ShiftLibra
模仿对象
Elk - 旅行货币转换器 -- Apple Design Awards 获奖作品

原作地址 : https://itunes.apple.com/us/app/elk-travel-currency-converter/id1189748820?mt=8

使用第三方框架
1.SnapKit
2.AFNetworking
3.YYModel
4.pop
5.FMDB
6.FoldingCell
7.TPKeyboardAvoiding

功能实现
1.通过聚合数据API获取汇率更新
2.使用FoldingCell框架实现首页TableView展开
3.使用FMDB完成本地数据存储
4.通过SQLite语句实现模糊查找,排序等功能
5.使用pop动画实现设置界面弹出
6.设定"人民币本位"实现自定义汇率
7.使用TPKeyboardAvoiding实现货币列表界面键盘弹出问题
8.通过加载临时数据库解决第一次安装程序的网络加载数据缓慢的问题,网络加载完成后把临时数据库中信息加载到主数据库中
9.根据上次汇率更新时间以确定是否更新汇率,热门汇率1天更新一次,冷门汇率如果调用7天更新一次
10.封装英语版本
11.根据系统语言类型和手机定位是否在国内以确定语言版本
不足之处
1.细节动画存在不足

注意
只根据手机系统语言类型和定位地址切换语言版本,如要测试语言版本,可以在模拟器上变更系统语言或者定位到国外
汇率api使用的是聚合数据免费api,每天只可以测试100次,数据不一定更新得了

正在北京找工作中,有意向请联系我
15969574989@163.com

