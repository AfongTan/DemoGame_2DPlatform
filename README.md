# 2D Platform Demo

这是由我个人开发的2D平台游戏Demo，涵盖了从游戏设计到功能实现、数据管理等多方面的内容。本项目展示了多种Unity开发技术的应用，旨在提供一个全面的游戏开发实例。

## SDK接入

- 完成百度定位SDK的接入，可在开始界面显示欢迎

![](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/welcome.gif)

## 角色控制和动画

- 基础的角色跳跃移动、攻击、平台的上下

  ![【GIF】](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/gamePlay.gif)

## 敌人AI

- 谁用BehaviourTreeDesigner，进行敌人AI开发，尝试创建可复用的action节点

![【GIF】](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/behaviouirTree_bat.gif)

![【GIF】](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/behaviouirTree_boar.gif)

![【GIF】](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/behaviouirTree_spider.gif)

## **Buff系统**：

- Buff系统的持续时间、触发频率、叠加方式等等，都可通过Excel配置表快速配置(目前只配置了两个buff)

![【luban图片】](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/buff_luban.png)

- 流血Buff

![【GIF】](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/buff_Bleeding.gif)

- 冰冻Buff

![【GIF】](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/buff_Forzeen.gif)

## 商店&背包&装备系统

- 完成商店等系统的UI及其功能，通过简单的Linq语法，可对商店、背包等物品进行条件排序

- 商店

![](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/ShopPanel.gif)

- 装备
![](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/equipmentPanel.gif)

- 所有的装备都是可配置的

![](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/item_luban.png)

## 在线奖励

- 根据玩家的在线时长解锁奖励

![【GIF】](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/RewardPanel.gif)

## 存档系统

- 通过Json进行数据的持久化，支持加载、删除存档

![](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/SaveLoad.gif)

## 场景切换

![【GIF】](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/LoadingPanel.gif)

## 背景无限滚动

![【Gif】](https://github.com/AfongTan/DemoGame_2DPlatform/blob/main/res/background.gif)

## 资源加载

- 本游戏使用AB包进行资源的加载，但是还未完成AB包的上传于下载相关内容

## 游戏试玩须知

1. **演示项目**：本游戏目前仅作Demo演示，没有任何的流程和指引，不代表最终品质
2. **游戏操作**：屏幕左下角控制上下左右，右边方向键，上键是交互，下键是跳跃，左键是攻击，右键是翻滚；按住下方向和跳跃键可以从平台掉落
3. **开启权限**：游玩前务必打开定位权限，否则无法获取定位信息，定位服务由百度提供
4. **版本须知**：目前只有安卓版本，也可以使用模拟器安装游玩
5. **未来方向**：目前游戏还有很多想法，所以很多未使用的资源也打包进去了，现存的资源也没有压缩、打图集；包括AB包也没有上传，而是放在StreamingAssets下，所以包体较大，这也是未来优化的方向

apk网盘地址：

> 链接：https://pan.baidu.com/s/17F6Ef9bBVl6Jogd1qCliRQ?pwd=0xf8 
> 提取码：0xf8 



