## 安全通审核任务示例代码

### 1. 概要

此项目为下列服务端接口的示例代码

* [创建安全通审核任务](https://doc.yunxin.163.com/docs/jcyOTA0ODM/DA3OTIwNzg?platformId=50326) 
* [停止安全通审核任务](https://doc.yunxin.163.com/docs/jcyOTA0ODM/Dg5NzQ1MjM?platformId=50326) 

> 注：此处示例代码展示的目的仅为提供接入参考，建议在实际项目中考虑应用场景和需求自行编写。


### 2. 文件夹结构

此项目包含以下内容

- `src`: 源代码
- `lib`: 可能会使用的库

> 注：此项目lib中忽略超过1M的库，若有运行需要请自行添加


### 3. 运行

此处的示例代码不支持直接运行。

在实际运行之前，需要准备运行场景，并对示例代码的部分参数进行修改。

下面对运行需要的准备进行说明。

#### 3.1. 设置账户相关环境变量

    ```
    export APPKEY=<your app key>
    export APPSECRET=<your app secret>
    ```
#### 3.2. 创建音视频房间

请使用SDK或DEMO创建一个音视频房间，并记录下房间名`channelName`

在示例代码`TO BE REPLACED`标记处，替换以下参数

* channelName
* monitorUid (若无冲突，可不替换)
* detectType (可不替换)
* scFrequency (可不替换)
* callback (可不替换)

#### 3.3. 运行

可尝试运行，若返回错误，请参考[错误码](https://doc.yunxin.163.com/docs/jcyOTA0ODM/TQ3Njc1Nzg?platformId=50326)，或者联系云信团队以获得更具体的支持。



### 4. 联系方式

若对此项目有疑问，或者需要联系云信团队，请参考以下链接

* [网易云信](https://yunxin.163.com/?from=nim&clueFrom=nim)
* [网易云信/音视频通话2.0/服务端API](https://doc.yunxin.163.com/docs/jcyOTA0ODM/TE3OTc1ODU?platformId=50326)