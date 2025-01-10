# Pony Music Lryics
这个项目围绕由Narokath发布的MLP音乐合集（My Little Pony Friendship is Magic - Ultimate Soundtrack Collection v1.2），收集或制作歌词文件，供广大马迷使用。

并不是所有歌曲都将会制作歌词文件，目前，提供歌词的歌曲范围不包含intrumental类型、demo类型、credits类型。

目前，大多数歌曲歌词仍处于没有完善的阶段，具体确定可用的歌曲歌词请查看[check.md](./check.md)


## 关于音乐合集
My Little Pony Friendship is Magic - Ultimate Soundtrack Collection v1.2是由一位叫做 [Narokath](https://www.youtube.com/@Narokath) 的马迷发布的合集。

<details>
  <summary>Narokath发布音乐合集时的话(主要是一些ta的账号与联系方式，与本项目无关)</summary>
    Hey there! Thank you for watching! Feel free to check out the links below, I'd appreciate it! <3  <br>
    💜 Twitch: https://twitch.tv/Narokath_  <br>
    💚 Highlights: https://www.youtube.com/playlist?list=PLF6cLPRsseRHG4nKk63Ff5SZ6MJwXAfJ0  <br>
    ❤ Donation: https://streamlabs.com/narokath_/tip  <br>
    Twitter --------------- https://twitter.com/NarokathSocial  <br>
    BandCamp -------- https://Narokath.bandcamp.com  <br>
    Backloggd --------- https://www.backloggd.com/u/Narokath/  <br>
    MyAnimeList ----- https://myanimelist.net/profile/Narokath  <br>
    Steam ---------------- https://steamcommunity.com/id/NarokathGaming/  <br>
    Discord Server --- https://discord.gg/ye9fujZjjA  <br>
    SoundCloud ------- https://soundcloud.com/NarokathMusic  <br>
    Music Folder ------ https://mega.nz/folder/a5g3iAYD#ktzbZITDuutCO4KaPIC43w  <br>
    Instagram ---------- https://www.instagram.com/narokath_/  <br>
    Reddit ---------------- https://reddit.com/user/Ponyship  <br>
    Tumblr --------------- https://www.tumblr.com/blog/narokathsocial  <br>
    TikTok ---------------- https://www.tiktok.com/@narokath  <br>
    e-Mail ------------------------ NarokathContact@gmail.com  <br>
    Discord ID ----------------- Narokath # 5479  <br>
    Nintendo Switch ID --- SW-5409-1400-6328  <br>
    Original Music ------------------ https://www.youtube.com/playlist?list=PLF6cLPRsseREHGbbzFIn7Ha0aLkO3Lvp1  <br>
    Music Covers ------------------- https://www.youtube.com/playlist?list=PLF6cLPRsseREelO1trcMagfPCI9Vxph4S  <br>
    Chart Downloads ------------- https://mega.nz/folder/64wiEAZC#a8auC7axg4vbeiAo175GOQ  <br>
    MLP:FiM Soundtrack ------  https://mega.nz/folder/igYRhKJS#ub0xuCYekOIiMspcudBofw  <br>
    Stream VODs ------------------- https://www.youtube.com/playlist?list=PLF6cLPRsseRF61IRUHtbczocASEVOBl80  <br>
    Commentary Playlists ----- https://www.youtube.com/c/Narokath/playlists?view=50&sort=dd&shelf_id=5  <br>
Contains Explicit Language! Viewer Discretion is advised! <br>
</details>

<hr>

国内可以参考：EquestriaCN文章[(link)](https://www.equestriacn.com/2021/02/resources-download-pony-official-song-resources-integration.html)，包含一些该音乐包的介绍与下载途径。

## 使用方式
本项目的目录结构与音乐合集完全相同，所有的歌词与歌曲名称相同，如果是foobar2000播放器或potplayer播放器，复制进去后再播放音乐会自动读取。

建议使用foobar2000.

## 参与制作
由于该音乐合集中的一部分音乐与常见网络音乐平台有所差异，所以部分歌词文件不能直接使用。

如果想要参与项目，提交PR前请看着歌词至少听一遍，以确保歌词正确、匹配

歌词可以参考`灰机 mlp wiki`、`fandom mlp wiki`等网站。

### 格式
基本三要素：音乐名，歌手名，歌词制作者（署名）

```lrc
[ti:]
[ar:]
[by:珊瑚派]
```

- 采用**逐行**歌词，有较高要求者也可采用逐字
- 歌词时间戳格式为[分钟:秒.]  
- 歌词、歌曲名的中文都**不**是必须的
- 署名非必须，但要留有标签
- 
- 歌词正文开头**不**要带有作词等信息，如`[00:00.00] 作词 : MyLittlePony`
- 多歌手的歌曲的歌词需要带有角色名：
  1. 这个角色当前歌词只有一句：角色名方括号包裹，角色名放在本句歌词开头(有中文优先放中文的句子前，英文不再放)，并与歌词间隔一个空格
  2. 这个角色当前歌词多于一句（成段）：角色名方括号包裹，单独成句，放在这段歌词第一句之前

歌词文件示例：


```lrc
[ti:My Little Pony Theme Song]
[ar:Twilght Sparkle / Applejack / Rainbow Dash / Fluttershy / Rarity / Pinkie Pie]
[by:珊瑚派]

[00:00.00]My Little Pony
[00:00.00]我的小马驹
[00:02.11]My Little Pony
[00:02.11]我的小马驹
[00:03.84](Ahahahah...)
[00:06.08]My Little Pony
[00:06.08]我的小马驹
[00:08.43]I used wonder what friendship could be
[00:08.43][Twilght Sparkle] 曾经我好奇什么是友谊
[00:10.30]My Little Pony
[00:10.30]我的小马驹
[00:12.12]Until you all share its magic with me
[00:12.12][Twilght Sparkle] 直到你们与我分享魔力
[00:14.62]Big adventure
[00:14.62][Rainbow Dash] 难忘奇遇
[00:15.52]Tons of fun
[00:15.52][Pinkie Pie] 遍地欢喜
[00:16.69]A beautiful heart
[00:16.69][Rarity] 美丽心灵
[00:17.48]Faithfull and strong
[00:17.48][Applejack] 坚强卖力
[00:18.82]Sharing kindness
[00:18.82][Fluttershy] 善良客气
[00:19.70][Twilght Sparkle]
[00:19.94]It's an easy feat
[00:19.94]简单而容易
[00:21.07]And magic makes it all complete!
[00:21.07]魔力将这一切完美联系
[00:23.03](You have) My Little Pony
[00:23.03]我的小马驹
[00:25.25]Do you know you're all my very best friends!
[00:25.25][Twilght Sparkle] 你们交给我友谊的真谛！
[00:32.31]
```

```lrc
[ti:Equestria, the Land I Love]
[ar:Coloratura]
[by:]

[00:01.08]Equestria the land I love
[00:01.08]小马利亚 ，我爱的土地
[00:04.12]A land of harmony
[00:04.12]和谐之地
[00:08.13]Our flag does wave from high above
[00:08.13]我们的旗帜确实高高飘扬
[00:12.02]For ponykind to see
[00:12.02]给小马看
[00:17.45]Equestria a land of friends
[00:17.45]小马利亚是朋友的国度
[00:21.75]Where ponykind do roam
[00:21.75]小马在哪里游荡
[00:25.71]They say true friendship never ends
[00:25.71]人们说真正的友谊永远不会结束
[00:28.92]Equestria my home
[00:28.92]小马利亚我的家
[00:34.47]
```

```lrc
[ti:We Got The Beat]
[ar:瑞秋·普蕾顿]
[by:珊瑚派]

[00:06.54]Hey! Hey! Hey!
[00:09.52]Hey! Hey! Hey!
[00:11.75] [瑞秋·普蕾顿]
[00:12.31]See the ponies trottin' down the street
[00:15.53]Equestria is where they wanna meet
[00:18.71]They all know where they wanna go
[00:21.31]And they're trottin' in time
[00:22.70]And they're trottin', yeah
[00:23.98]They got the beat
[00:24.79]They got the beat
[00:26.25]They got the beat
[00:28.84]Yeah, they got the beat
[00:30.95]Go-go music really makes us dance
[00:33.95]Do the pony, puts us in a trance
[00:37.08]Do the watusi, just give us a chance
[00:39.33]That's when we fall in line
[00:41.60]'Cause we got the beat
[00:43.16]We got the beat
[00:44.58]We got the beat
[00:47.32]Yeah, we got it!
[00:49.22]
```
