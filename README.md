# MultiDiagToolkit
## 多合一系统诊断工具箱

一个针对 Windows 系统的诊断修复工具箱

开发调试需求：[Mtee](https://ritchielawrence.github.io/mtee/)、Windows 环境

下载地址：[发布页](https://github.com/Jackstar1212/MutiDiagToolkit/releases)

内测群抢先体验 PreRelease，欢迎一起debug！

可通过我的主页邮箱联系到我

新版本请访问：https://www.nekomoe.fun/?p=69

### 20230316——1.0版本

基于vk加速器脚本框架修改，添加常用功能，整理如下：

  1、系统环境诊断
  
  2、代理程序诊断
  
  3、系统修复
  
  4、hosts修复工具
  
  5、DNS设置工具
  
  6、网络协议栈重置
  
  7、LSP修复
  
  8、关闭Windows防火墙
  
  9、开启Windows防火墙
 
 10、显示程序列表
 
 11、重置IE
 
 12、卓越性能模式
 
 13、DNS缓存域名记录
 
 14、恢复UAC
 
 15、禁用UAC
 
 16、Xbox平台修复
 
 17、图标变白修复
 
 18、自定义开机选择系统启动项等待时间
 
 19、Windows聚焦壁纸修复
 
 20、Windows电源选项恢复
 
 21、Windows Update更新安装问题（0x80070002/0x80070005）其他故障请使用系统修复
 
 22、taskmgr.exe没有与之关联的程序运行
 
 23、多种exe没有与之关联的程序运行
 
 24、打开可移动磁盘自动运行
 
 25、关闭可移动磁盘自动运行
 
 26、开启系统休眠
 
 27、关闭系统休眠
 
 28、取消Windows激活状态并重置评估期（慎用！会使Windows变为未激活状态！）
 
 29、组策略添加、修复（适用于家庭版添加组策略或者升级专业版后组策略丢失异常等问题）
 
 30、系统盘缓存垃圾清理（使用有风险，会清理日志文件等，请做好备份）
 
### 20230317——1.1版本

新增功能：修复桌面图标间距异常、窗口右上角关闭最大化最小化按钮异常

新增功能：微软商店问题修复

优化代码格式，调整代码规范性，调整窗口大小

### 20230318——1.2版本

新增功能：右键添加管理员取得所有权

新增功能：右键取消管理员取得所有权选项

新增功能：IE主页修复功能

新增功能：（WIN7限定）在较老的电脑上开启Aero透明毛玻璃效果

新增功能：Steam VAC屏蔽修复与闪退问题修复工具

优化大量注册表语法问题、修正异常功能、优化格式

### 20230318——1.3版本

新增功能如下：

（WIN7限定）在较老的电脑上开启Aero透明毛玻璃效果

Steam VAC屏蔽修复与闪退问题修复工具（打csgo报vac验证错误断开连接之类的选我）

清理本地FlashPlayer播放器记录（单文件FlashPlayer播放器的记录清理）

清除快捷方式小箭头（美化类：不要桌面上快捷方式左下角的小箭头）

恢复快捷方式小箭头（美化类：恢复桌面上快捷方式左下角的小箭头）

修复由于远程连接导致的剪贴板复制粘贴失效问题

停用vmmem，解决vmmem占用过高问题

停用TabletPC功能

记事本默认保存编码修改

加入Windows预览体验计划 原项目地址：[Windows Insider Channel](https://github.com/abbodi1406/offlineinsiderenroll/releases/tag/2.6.4)

查看电池健康度（看看电脑电池损耗如何）

优化代码，添加清屏操作，避免输出混乱

### 20230320——1.4版本

新增功能：

获取文件HASH值

禁用遥测系统跟踪等服务（系统隐私优化）

恢复遥测系统跟踪等服务（遇到异常了选我恢复）

禁用Windows Defender

启用Windows Defender

### 20230320——1.5版本

整合 MAS 微软激活脚本 原项目地址：[MAS 微软激活脚本](https://github.com/massgravel/Microsoft-Activation-Scripts)

### 20230321——2.0版本

重构目录，分类选项，更加清爽简洁

增加安全软件检测项目（虽然用处不大）

优化代码逻辑

### 20230321——2.1版本

新增功能：

EAC 卸载工具

Apex Legends 商店图片修复

逻辑优化，增加一些微不足道小功能

### 20230322——2.2版本

新增功能：

Windows Update 屏蔽与修复工具

一些单元组管理快捷启动

优化文字描述

### 20230323—2.2版本优化

增加大量小功能

改进目录

增加网络信息获取功能，修复解析成功率异常问题

### 20230325—2.4

逻辑优化

增加电源计划相关小功能，改进网络修复

### 20230326—2.5

修正hosts修改相关功能，新增hosts丢失修复

优化各个hosts修复相关环节，不再是简单清空，而是会还原Windows默认的实例等内容

优化大量命令表达，新增备份功能，新增少量快捷面板启动

启动速度和调用优化，增加系统信息 MD5 校验环节，防止信息篡改

### 20230327—2.6

格式优化，生成说明优化，新增文件说明

### 20230330—2.7

优化DNS设置功能，优化格式，支持ipv4和ipv6的dns设置

逻辑优化，支持动态检测系统环境，优化md5校验环节

### 20230403-2.8

取消屏幕分辨率校验，部分设备校验无效且会造成闪退问题

修正显卡信息获取，添加硬盘信息获取、主板信息获取，添加 ipv6 dns 查询、新增系统信息生成

### 20230405-3.0

增加快速启动选项，绕过系统信息生成，DNS查询改进，改进 IPv6 DNS 服务器查询
