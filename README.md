## eoLinker API 测试增强插件（自动化测试插件）
eoLinker提供了非常强大的在线API接口测试功能，在使用之前，请先安装 **eoLinker自动化测试增强插件** ，该插件为您提供了以下功能支持：
1. 线上网站、跨域、本地测试，支持通过远程网站访问本地localhost进行测试
2. 支持文件类型的请求参数
3. 支持更多请求协议
4. 支持简易、高级自动化测试
5. 支持全局变量等需要插件支持的测试

插件获取地址：[请点击这里获取插件](https://www.eolinker.com/#/plug/introduce "请点击这里获取插件")

目前插件支持Chrome以及Firefox浏览器，其中Chrome插件需要翻墙下载，或者安装由我们提供的离线安装包，Firefox则无需翻墙。

**注意**：eoLinker API 测试增强插件需要配合[eoLinker线上网站](https://www.eolinker.com "eoLinker线上网站")或者开源版产品使用。

---

#### 安装

**Chrome：**
1. 通过Google Market获取（推荐），能够自动更新版本。需要翻墙下载，否则无法访问，地址为：
	[https://chrome.google.com/webstore/detail/eolinker/mdbgchaihbacjfjeikflfbelidihhmfn](https://chrome.google.com/webstore/detail/eolinker/mdbgchaihbacjfjeikflfbelidihhmfn "https://chrome.google.com/webstore/detail/eolinker/mdbgchaihbacjfjeikflfbelidihhmfn")
	
2. 下载插件压缩包，手动导入，无法自动更新版本，无需翻墙。可在文件夹中找到相应版本。

**Firefox：**
1. 必须通过Firefox addon市场下载，地址为：
[https://addons.mozilla.org/zh-CN/firefox/addon/eolinker/](https://addons.mozilla.org/zh-CN/firefox/addon/eolinker/ "https://addons.mozilla.org/zh-CN/firefox/addon/eolinker/")

---

#### 检测

在需要通过插件进行测试的功能中，会有相应的提示是否已经正确安装插件，如果正常安装插件，则会显示类似的界面：

![](http://data.eolinker.com/course/hrDhmQW598c9b26f75684b14b09ce9f22898b6ffcf9481b)

若看到黄色提示框，则表示插件尚未正确安装或者版本过旧，需要安装或者更新：

![](http://data.eolinker.com/course/TKg88gsd74def9adc4f3accddc736b729323dbcece971ff)

---

#### 更新日志
**V4.5 (2018-10-24)**
* 支持json校验类型判断
* 修复英文版本并行测试未加入历史记录bug
* 修复自动化测试测试全部某些bug
* 修复用例测试某些头部发送错误bug
* 修复用例测试后置代码无法使用通用函数bug
* 优化过滤错误请求头部
* 取消支持json校验中的#字符用法

**V4.0 (2018-08-26)**
* 支持分享页面使用通用函数
* 支持自动化测试前置代码response
* 支持同名query
* 修复formdata转json传值不能为空bug
* 修复多个同名文件请求bug
* 修复数据结构类型#号
* 修复快速测试历史记录
* 优化请求错误提示信息

**v2.0.7 (2018-04-09)**
* 支持代码注入CrytoJS加密算法
* 支持ui自动化测试失败继续执行
* 支持代码注入境变量继承
* 修复完全匹配bug
* 修复ui自动化测试restful请求bug
* 修复form-data转json某些bug
* 修复注入代码某些bug
* 优化query参数处理
* 优化高级自动化测试文件参数处理

**v2.0.4 (2018-03-13)**
* 修复注释生成文档bug
* 新增批量自动化测试单用例测试

**v2.0.3 (2018-03-08)**
* 修复自动化测试报告显示问题
* 修复restful与环境变量参数冲突bug
* 优化环境变量匹配规则

**v2.0.2 (2018-02-28)**
* 修复代码注入环境变量baseUrl
* 修复自动化测试环境变量额外参数bug
* 修复自动化测试关联参数双引号bug
* 修复历史纪录bug
* 优化302请求header继承问题
* 优化浏览器兼容

**v2.0.1 (2018-02-21)**
* 支持自动化测试前置用例
* 支持自动化测试单次测试历史记录
* 支持自动化测试cookie继承
* 优化自动化测试返回头部
* 优化encodeURI
* 修复不兼容开源版本请求方法问题
* 修复自动化测试timelimitContinue
* 修复批量自动化头部发送bug
* 修改ui自动化测试引用关联参数方式

**v2.0.0 (2018-02-20)**
* 修复部分问题

**v1.9.9 (2018-02-1)**
* 支持批量自动化测试
* 支持普通测试前置后置代码
* 支持自动化测试ui模式报告
* 支持自动化测试高级模式文件参数
* 修复自动化测试高级模式某些bug
* 修复发送header不兼容某些url问题
* 修复自动化测试json正则匹配问题
* 优化环境变量与各类测试信息的优先级
* 优化各类测试中止逻辑
* 优化开源版本自动化测试信息获取

**v1.9.8 (2018-01-15)**
* 修复部分问题

**v1.9.7 (2018-01-11)**
* 支持raw全局变量
* 支持自动化高级测试自主选择超时请求是否继续
* 支持自动化测试json校验对象(null 等)和数组
* 支持formdata转Json判断类型
* 支持独立部署版测试报告
* 修复自动化测试json校验某些bug
* 修复火狐浏览器批量测试不全bug
* 优化普通版测试通信方式

**v1.9.6 (2018-01-06)**
* 修复自动化测试无法自定义header的问题
* 自动化测试支持获取返回结果的header

**v1.9.5 (2017-12-14)**
* 修复自动化测试不校验bug
* 修复识别注释生成文档代码文件为空bug
* 支持开源版本自动化测试
* 识别注释生成文档支持多种语言

**v1.9.2 (2017-12-05)**
* 支持根据代码生成文档

**v1.9.1 (2017-11-29)**
* 修复自动化测试部分情况下无法判断值的问题

**v1.9.0 (2017-11-28)**
* 免费版本支持自动化测试
* 优化现有自动化测试的功能

**v1.8.9 (2017-11-24)**
* 修复在非eoLinker网站上报错的问题

**v1.8.8 (2017-11-20)**
* 修复自动化测试参数无法关联的bug

**v1.8.7 (2017-11-19)**
* 支持自动化测试
* 修复部分问题

**v1.8.5 (2017-11-7)**
* 修复部分问题

...更多版本更新请前往eolinker官网查看
