# 欢迎查阅Test Scenario Points HTML（App测试场景点自动化框架体系）
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
![](https://testerhome.com/uploads/photo/2019/ebf9c2e2-2dc1-447a-9e69-650204a33ae7.gif!large)

    Test Scenario Points HTML是一个在线编写测试场景点的自动化框架，实现了效果图和测试场景点一体化预览，方便测试评审
        •  该框架包含导航标签，新增模块，删除模块，读取模块，保存模块等功能
        •  【新增模块】实现了在线插入UI效果图，效果图来源于 [蓝湖](https://lanhuapp.com)
        •  【删除模块】实现了一键删除单个或多块功能模块
        •  【读取模块】实现了一键读取单个或多个功能模块
        •  【保存模块】实现了一键保存单个或多块功能模块

 ---
### 框架介绍
    HTML + CSS + JS + Excel + 蓝湖
        •  使用HTML作为项目编程语言，方便网页预览，编辑
        •  使用CSS作为样式编程语言，方便加载界面样式效果
        •  使用JS作为动态脚本语言，方便加载动画效果
        •  使用Excel作为场景点保存文件，方便一键导入
        •  使用蓝湖作为UI效果图的共享平台，方便获取图片地址

 ---
### 安装运行
    1.  使用Git克隆下载源码，命令：git clone https://gitee.com/hagyao520/Test-Scenario-Points-HTML.git
    2.  克隆完成后，打开Test-Scenario-Points-HTML下【index.html】文件即可
    3.  使用编辑器打开【index.html】，可以进行修改相关内容
    4.  使用【测试场景点.xlsx】，管理所有测试场景点

 ---
### 使用说明
#### 一、新增模块：  
![](https://testerhome.com/uploads/photo/2019/fb944cfb-e701-4f3c-9cf0-dbf965e8a7f1.gif!large)
 1. 点击新增模块按钮，输入模块跳转链接，一般对应产品原型的地址，例如：【https://oh2e7m.axshare.com】
 2. 输入模块名称，例如：【一. 登录界面】
 3. 输入测试场景点，例如：【手机号丨获取验证码丨更换手机号丨登录】
 4. 输入图片地址，例如：【https://alipic.lanhuapp.com/SketchCoverf0707de649e522dd7bc39b0d9df53f11】
 5. 点击确认按钮，即可新增模块成功，自动生成UI效果图和场景点编辑框
 - PS：编辑测试场景点时，没一行需要以【；】结尾，最后一行需要加空格【； 】  

 #### 二、删除模块：
![](https://images.gitee.com/uploads/images/2019/0808/154356_ea10dfac_1325509.gif)
  1. 点击删除模块按钮，选择要删除的模块，例如：【全部】或【XXX模块】
  2. 点击确认按钮，即可删除模块成功，删除后页面移除该模块

#### 三、保存模块：
![](https://testerhome.com/uploads/photo/2019/da6b4a14-b9a1-4c20-940f-c70804b8bf98.gif!large)
 1. 点击保存模块按钮，输入保存的模块序号，新增会自动+1，默认即可，例如：【1】
 2. 点击确认按钮，弹出下载提示，即可保存模块成功，自动保存成Excel文件
 - PS：Excel默认保存成.xls格式，需要重新另存成.xlsx格式

#### 三、读取模块：
![](https://images.gitee.com/uploads/images/2019/0808/154355_312597f0_1325509.gif)
 1. 点击读取模块按钮，再点击选择文件按钮，选择要读取的Excel文件，例如：【一. 登录界面.xlsx】
 2. 读取成功后会自动获取所有模块，选择要读取的全部或单个模块，例如：【全部】
 3. 点击确认按钮，即可读取模块成功，读取成功后页面会自动生成该模块内容

 ---
### 七、感谢
#### 如果您觉得这个框架对您有用，您可以捐赠下我，让我有理由继续下去，非常感谢。
![](https://images.gitee.com/uploads/images/2019/0808/154355_a1e644e2_1325509.png)

**非常感谢您花费时间阅读，祝您在这里记录、阅读、分享愉快！**
**欢迎留言评论，有问题也可以联系我或者加群交流...**

作者：[@刘智King](http://shang.qq.com/email/stop/email_stop.html?qq=1306086303&sig=a1c657365db7e82805ea4b2351081fc3ebcde159f8ae49b1&tttt=1)         
QQ：1306086303     
Email：hagyao520@163.com

> QQ官方交流群 126325132
<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=346d11a1a76d05086cd48bc8249126f514248479b50f96288189ab5ae0ca7ba5"><img border="0" src="//pub.idqqimg.com/wpa/images/group.png" alt="软件测试开发交流群" title="软件测试开发交流群"></a>