<div align="center">

<img src="https://avatars.githubusercontent.com/u/138054042?v=4" width="116" alt="头像" />

<h1>俊翔不会玩</h1>

<p><i>一个汽修生，计算机只是兴趣使然</i></p>

<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
<img alt="Ren'Py" src="https://img.shields.io/badge/Ren'Py-FF7F7F?style=flat-square&logo=renpy&logoColor=white" />
<img alt="Shell" src="https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
<img alt="Flask" src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
<img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />

<br/>

<img alt="Folia" src="https://img.shields.io/badge/Folia%20%2F%20Folium%20模组-6A5ACD?style=flat-square" />
<img alt="ComfyUI" src="https://img.shields.io/badge/ComfyUI%20SDXL-1F6FEB?style=flat-square&logo=python&logoColor=white" />
<img alt="AstrBot" src="https://img.shields.io/badge/AstrBot-12B886?style=flat-square&logo=python&logoColor=white" />


<br/><br/>

<img alt="Profile views" src="https://komarev.com/ghpvc/?username=junxiang255&style=flat-square&color=ff2d78" />
<img alt="Followers" src="https://img.shields.io/github/followers/junxiang255?style=flat-square&color=6cf&labelColor=30363D" />
<img alt="Stars" src="https://img.shields.io/github/stars/junxiang255?affiliations=OWNER&style=flat-square&color=ffd43b&labelColor=30363D" />

</div>

---

### 🧑‍💻 关于我

- 🐍 **Python 脚本兜底**：Selenium 自动签到、AstrBot 插件调本地 ComfyUI 出 SDXL 图。
- 🌐 **也自己搭站**：Flask + MySQL 的站点跑在宝塔面板上，榜单后台带登录。
- 🎮 **二次元浓度超标**：Ren'Py 做 9-nine- 主题模板（素材自己解包），Magisk 开机动画只做了希亚的 —— 因为希亚是对的。
- 🌱 **现在在补**：几个半成品收尾（签到脚本、ComfyUI 插件），以及把自用工具做到「别人装上就能用」。

---

### 🚀 项目

**主力三个**

| 项目 | 它解决什么 | 技术 |
|---|---|---|
| [**bili-mv-window**](https://github.com/junxiang255/bili-mv-window) `MIT` | 换歌自动去 B 站找这首歌的 MV，用可拖动小窗或播放页背景放出来 —— **只放画面，不放声音**。匹配度打分公开可调（UP 主含歌手名 +34 优先于标题含歌手名 +18，翻唱/鬼畜 −55）；6 级取流降级链；扫码登录解锁 1080P/4K；每个视频各记各的音画偏移 | JavaScript / Node main · Folium |
| [**Lyricon-MGAide-Provider**](https://github.com/junxiang255/Lyricon-MGAide-Provider) `Apache-2.0` | 毛怪助手（MG Aide）的歌词 provider：hook `MusicViewModel`，反射取歌名/歌手/进度/逐字时间轴，推给词慕做**状态栏逐字（KTV）歌词**，含翻译行 | Kotlin · Compose · LSPosed |
| [**renpy-9nine-Template**](https://github.com/junxiang255/renpy-9nine-Template) ★3 | Ren'Py 的 9-nine- 模板，素材来自游戏解包，解压进 Ren'Py 项目目录即可开写。puppet 社作品 | Python / Ren'Py |

**站点与脚本**

| 项目 | 一句话 | 状态 |
|---|---|---|
| [**qiu_web**](https://github.com/junxiang255/qiu_web) `小秋的垃圾站` | Flask 单页站点：PC / 手机双版首页、垃圾桶之夜名单页、带登录的榜单管理后台，数据走 MySQL（`ranking` / `user` 两表，密码 `werkzeug` 哈希）。这次重写做了资源归位、60 处引用重写、接口从写死的 `http://…` 改成站内相对路径、密钥外置成环境变量，顺手修掉「手机版跳不动」「页面没引 jQuery 却在用 `$.ajax`」这类老 bug | 在建 · 域名未启用 |
| [renpy-bilibili-Download-videos](https://github.com/junxiang255/renpy-bilibili-Download-videos) | 拿 Ren'Py 视觉小说引擎做图形界面，下载 B 站 / 快手视频 | 可用 |
| [MGClub-signin-Script](https://github.com/junxiang255/MGClub-signin-Script) | Selenium + Edge 驱动，自动登录毛怪俱乐部、签到，再用 Cookie 查签到状态 | 自述半成品 |
| [astrbot_plugin_comfyui](https://github.com/junxiang255/astrbot_plugin_comfyui) | AstrBot 插件，调本地 ComfyUI 的 API 跑 SDXL 文生图 | 半成品，模型变量要按本地改 |
| [astrbot_plugin_cloudmusic](https://github.com/junxiang255/astrbot_plugin_cloudmusic) | 爬网易云音乐的 AstrBot 插件 | 在建（仓库还是模板） |
| [9nine-Magisk-Boot-Animation-Module](https://github.com/junxiang255/9nine-Magisk-Boot-Animation-Module) | 9-nine- 开机动画 Magisk 模块，目前只有希亚 | 可用 |


---

### 📊 数据

<div align="center">

<img width="800" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=junxiang255&theme=tokyonight" />

<br/>

<img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=junxiang255&theme=tokyonight" />
<img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=junxiang255&theme=tokyonight" />

<br/>

<img height="165" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=junxiang255&theme=tokyonight" />
<img height="165" src="https://streak-stats.demolab.com?user=junxiang255&locale=zh&theme=tokyonight&hide_border=true&background=1a1b27&ring=ff2d78&fire=ff2d78&currStreakLabel=ff2d78" />

</div>

---

<div align="center">

想用哪个直接进仓库翻 README，装不上就在 Issue 里喊我。

<sub>There is no "exception" in this library</sub>

</div>
