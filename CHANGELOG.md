# lx-music-desktop change log

All notable changes to this project will be documented in this file.

Project versioning adheres to [Semantic Versioning](http://semver.org/).
Commit convention is based on [Conventional Commits](http://conventionalcommits.org).
Change log format is based on [Keep a Changelog](http://keepachangelog.com/).

## [0.3.3](https://github.com/lyswhut/lx-music-desktop/compare/v0.3.2...v0.3.3) - 2019-08-29

### 修复

- **messoer**的接口已经关闭，暂时切换到临时接口使用，部分功能受限。。。
- 修复设置界面更新出错时仍然显示更新下载中的问题
- 修复手动定位播放进度条时存在偏差的问题
- 屏蔽播放器中没有歌曲时对进度条的点击


## [0.3.2](https://github.com/lyswhut/lx-music-desktop/compare/v0.3.1...v0.3.2) - 2019-08-24

### 新增

- 新增酷狗排行榜其他音质下载

## [0.3.1](https://github.com/lyswhut/lx-music-desktop/compare/v0.3.0...v0.3.1) - 2019-08-24

### 修复

- 修复音量条主题适配

## [0.3.0](https://github.com/lyswhut/lx-music-desktop/compare/v0.2.3...v0.3.0) - 2019-08-24

### 新增

- 新增**MAC**及**Linux**版本（需要的可自行下载）
- 新增音量调整
- 新增任务栏播放进度条控制选项（现在可在设置界面关闭在任务栏显示的播放进度）
- 新增更新出错时的弹窗提示
- 从该版本起，非安装版也会有更新弹窗提醒了，但仍然需要手动下载新版本更新，版本信息可到设置页面查看

### 修复

- 强制把临时接口设置回 `messoer` 接口

## [0.2.3](https://github.com/lyswhut/lx-music-desktop/compare/v0.2.2...v0.2.3) - 2019-08-22

### 新增

- 新增任务栏程序标题改变功能（播放歌曲时任务栏标题将显示当前播放的歌曲）

### 修复

- 使用临时接口时，试听列表中的下载按钮仍然能点击的Bug
- 修复某些情况下歌曲链接未能缓存的问题

### 移除

- 移除临时接口（因服务器被攻击，本接口已关闭）
- 移除列表栏设置的隐藏专辑栏选项（感觉这个设置并没有什么luan用，并且还会打破布局）

## [0.2.2](https://github.com/lyswhut/lx-music-desktop/compare/v0.2.1...v0.2.2) - 2019-08-21

### 修复

- 修复下载过程中出错重试5次都失败后不会自动开始下一个任务的Bug
- 修复播放到一半URL过期时不会刷新URL直接播放下一首的问题

## [0.2.1](https://github.com/lyswhut/lx-music-desktop/compare/v0.2.0...v0.2.1) - 2019-08-20

### 优化

- 新增歌曲URL存储，当URL无效时才重新获取，以减少接口不稳定的影响

### 修复

- 修复歌曲加载无法加载时自动切换混乱的Bug
- 修复移除列表最后一首歌曲时播放器不停止播放的问题

## [0.2.0](https://github.com/lyswhut/lx-music-desktop/compare/v0.1.6...v0.2.0) - 2019-08-20

### 新增

- 新增**百度音乐**排行榜及其音乐直接试听与下载
- 新增网易云排行榜音乐直接试听与下载（目前仅支持128k音质）
- 新增酷狗排行榜音乐直接试听与下载（目前仅支持128k音质）

### 修复

- 修复更新弹窗历史版本描述多余的换行问题
- 修复歌曲无法播放的情况下歌词仍会播放的问题

## [0.1.6](https://github.com/lyswhut/lx-music-desktop/compare/v0.1.5...v0.1.6) - 2019-08-19

### 修复

- 修复列表多选音源限制Bug

## [0.1.5](https://github.com/lyswhut/lx-music-desktop/compare/v0.1.4...v0.1.5) - 2019-08-19

### 新增

- 新增搜索列表批量试听与下载功能
- 新增排行榜列表批量试听与下载功能
- 新增试听列表批量移除与下载功能
- 新增下载列表批量开始、暂停与移除功能

### 优化

- 优化歌曲切换机制

## [0.1.4](https://github.com/lyswhut/lx-music-desktop/compare/v0.1.3...v0.1.4) - 2019-08-18

### 新增

- 新增音乐来源切换，可到设置页面-基本设置 look look !
- 为搜索结果列表添加多选功能。
P.S：暂时没想好多选后的操作按钮放哪...

### 优化

- 重构与改进checkbox组件，使其支持不定选中状态
- 完善上一个版本的http请求封装并切换部分请求到该方法上
- 优化其他一些细节

## [0.1.3](https://github.com/lyswhut/lx-music-desktop/compare/v0.1.2...v0.1.3) - 2019-08-17

### 新增

- 新增win32应用构建

### 修复

- 修复安装包许可协议乱码问题
- **messoer 提供的接口已挂**，暂时切换到临时接口！

### 移除

- 由于messoer接口无法使用，QQ音乐排行榜直接播放/下载功能暂时关闭

## [0.1.2](https://github.com/lyswhut/lx-music-desktop/compare/v0.1.1...v0.1.2) - 2019-08-17

### 修复

- 修复更新弹窗的内容显示问题

## [0.1.1](https://github.com/lyswhut/lx-music-desktop/compare/v0.1.0...v0.1.1) - 2019-08-17

### 新增

- QQ音乐排行榜直接试听与下载（该接口貌似不太稳定，且用且珍惜！）

### 优化

- 优化http请求机制
- 更新关于本软件说明

### 修复

- 修复当上一个歌曲链接正在获取时切换歌曲请求不会取消的问题
- 修复切换歌曲时仍然播放上一首歌曲的问题

## [0.1.0] - 2019-8-16

* 0.1.0版本发布