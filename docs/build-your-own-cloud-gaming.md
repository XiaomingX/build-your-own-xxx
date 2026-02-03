# 构建自己的云游戏/云手机平台

这类项目主要聚焦远程渲染、低延迟视频传输与输入回传，适合搭建云游戏平台、云电脑或云手机能力。

## 代表项目

- [CloudGamePlatform](https://github.com/hubin858130/CloudGamePlatform)  
  云游戏/云电脑整体方案，覆盖虚拟化、渲染与推流，适合做全栈参考。
- [cloud-game](https://github.com/giongto35/cloud-game)  
  Web 端复古游戏云平台，适合做轻量试玩或怀旧游戏的浏览器直玩体验。
- [CloudPhone](https://github.com/lloves/CloudPhone)  
  云手机 PaaS，侧重 Android 云端运行与 WebRTC 推流，适合移动端场景。

## 技术要点

- 低延迟推流：WebRTC/RTSP + 硬件编码（NVENC/AMF/QSV）。
- 图形虚拟化：vGPU 或多实例 GPU 资源复用。
- 输入回传：键鼠/触控/手柄映射与防抖处理。
- 编解码链路：H.264/H.265、软硬解码与弱网自适应。

## 适用场景

- 云游戏试玩与会员订阅平台。
- 云手机/云电脑远程办公与批量测试。
- 轻量级浏览器端游戏聚合。
