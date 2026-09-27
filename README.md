# 陌岸 · Stranger Shores

独立于 blind-spot-game 的原创像素叙事试玩。居民使用由概念、交际意图与现场指认组成的虚构符号语言，不是逐汉字替换。你通过观察、取水、搬木料与协商，和他们一起修好船。

## 游玩

在 iPad Safari 或桌面浏览器打开网页即可。点地面行走；点人物/物件自动走近；也可拖动左下摇杆，按右下“互动”。“去哪里”提供地点导航。键盘支持 WASD / 方向键、E / 空格、J。

横竖屏均适配，声音默认关闭且只在用户点击后启用。进度与手记仅存本机 localStorage，无登录、遥测或外部服务；浏览器禁止存储时仍可在本次页面中玩完。不能保证跨设备同步。

这是单人短篇原型，包含一个岛、五个交互地点、八条见闻记录、可编辑猜想、两条取水途径、三种刻印结果及离岛结尾。没有联网双人模式。中文是动作观察和操作提示，不是 NPC 话语译文。

## 文件与开发

`index.html` 是完整可运行且包含全部图像的单文件源码。可直接托管在 GitHub Pages，无安装步骤。

模块化源文件另附 `source.zip`：`src/core.mjs` 语义与状态、`src/world.mjs` 瓦片关卡/碰撞/寻路、`src/game.js` 游戏循环与输入、`src/style.css` 布局。修改后在源目录运行 `node build.mjs`，用 `node tests.mjs` 检查。生成文件在 `dist/index.html`。

## 素材

- Kenney Tiny Town: https://kenney.nl/assets/tiny-town (CC0)
- Kenney Tiny Dungeon: https://kenney.nl/assets/tiny-dungeon (CC0)
- dutzy, based on russpuppy: https://opengameart.org/content/man-sprite-16x16 (CC0)
- CC0: https://creativecommons.org/publicdomain/zero/1.0/

原始16px图集、角色逐帧动画及地图分层绘制；关闭像素平滑。虚构文字以原创几何字形表示，不借用真实民族文字。海水纹理与提示音为程序生成。未使用《星露谷物语》的素材、代码或剧情。

2026-09-27 · v0.1
