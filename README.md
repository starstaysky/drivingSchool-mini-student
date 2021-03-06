# 驾校学车微信小程序（学员端）
这是一款用于学车平台为学员提供学车报名、预约练车服务的微信小程序  
This is a mini program project of WeChat

![license](https://img.shields.io/github/license/EpearthLtd/drivingSchool-mini-student.svg)
![GitHub release](https://img.shields.io/github/release/EpearthLtd/drivingSchool-mini-student/all.svg)
![Github commits (since latest release)](https://img.shields.io/github/commits-since/EpearthLtd/drivingSchool-mini-student/latest.svg)

## 技术参数
* 调试基础库：2.2.2
* 业务域名：https://develop.epearth.com

## 设计特色
* 全局变量设置根域名、资源域名、APP名称，简化变更小程序信息的步骤

## 设计功能模块
* 【已发布】轮播广告图
* 【已发布】在线客服（原生功能）
* 【已发布】预约练车
* 【已发布】记录查询
* 【已发布】手机绑定
* 【已发布】意见及BUG反馈（原生功能）
* 【已发布】拨打电话

## 基础系统
* 全局根域名
* 报名状态系统
* 预约及练车状态系统
* 练车进度系统

## 版本说明
* V1 静态海报广告：只包含广告展示和客服模块，没有约车功能
* V2 预约练车：包含预约练车的功能模块（开发中）

## 命名书写方法
* 小驼峰：页面文件命名、变量命名、参数命名
* 短横线：wxss命名、资源文件命名
```JavaScript
var thisIsExample   // 小驼峰变量参数命名示例
onShareAppMessage: function () {
                    // 小驼峰函数命名示例
},
```
```CSS
.color-bg-gray {    <!--短横线分隔命名示例-->
  background-color: #CCC;
}
```
## 链接
* [WeUI](https://github.com/Tencent/weui-wxss)

## 关于我们
* 官网：[成都曦璞科技有限公司官网](http://www.epearth.com)
* 新浪微博：[@曦璞公司](https://weibo.com/xipugongsi)
* 钉钉：[成都曦璞科技有限公司](https://h5.dingtalk.com/home/orgHome.html?corpId=dingaec3efd8fe21f19d35c2f4657eb6378f&token=7f52ac4cc9fc070c5c8457a4610c5006&from=share&_dt_no_comment=1)
