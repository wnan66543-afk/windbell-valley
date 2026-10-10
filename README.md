# 风铃溪谷 · Windbell Valley

手绘村庄场景：邮差少女与白狐沿着春日小路，走过山坡住居、村中集市和河岸水车。
在线体验：https://yuanyang749.github.io/windbell-valley/

## 内容

- **动画游览** `assets/scene.mp4` — 42 秒、1280×720、30fps，H.264 + AAC
  - 镜头从山坡跟随少女横向游览至河岸
  - 园丁浇花、面包师挥手、老人桥上吹笛三位 NPC 独立循环
  - 原创配乐《风铃溪谷圆舞曲》：C 大调 3/4 拍 72 BPM，长笛 + 尼龙弦吉他 + 弦乐 + 钟琴 + 贝斯
- **完整地图** `assets/windbell-valley.png` — 6324×724，三街区横向手绘大地图
- **封面** `assets/scene-poster.png`
- **无声版** `assets/scene-silent.mp4`
- **配乐** `assets/music-waltz.wav`（48kHz 立体声）/ `assets/music-waltz.mid`（MIDI 乐谱）

## 网页

`index.html`（纯静态，相对路径）：

- 动画游览 / 大地图切换
- 大地图鼠标与触屏横向拖动，三街区一键跳转
- 园丁 / 面包师 / 老人视频时间跳转
- 默认静音自动播放，「开启音乐」取消静音
- 视频与大地图下载入口，手机适配

## 制作说明

详见 `PROMPT.md`。全部素材（背景、角色、动作、配乐）均为本项目原创生成，
合成与作曲代码见工作目录脚本。
