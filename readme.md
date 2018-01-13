# 纪录片电影 Revolution OS （《操作系统革命》）中文字幕修订计划

原字幕由 geekbone.org / shlug.org / yinux / WiDE 等倾力制作。

其中我最喜欢的简体中文版本，字幕文本文件似乎已失传，只有嵌在rmvb里的版本，可惜。甚至连当时的先驱者们的讨论站点都不存在了，只有存档：
http://unixresources.net/linux/clf/linuxtalk/archive/00/00/38/93/389339.html

## 修订缘由
1. 该纪录片拍摄发行于2001年，字幕发布于2004年（或更早）。当年为了适应低分辨率屏幕，所使用的字体较大，导致大量手工换行；
2. 同上一条原因，部分长句被迫断句导致阅读体验不佳；
3. 部分时间轴需要修正；
4. 润色 + 修正翻译；
5. `srt`不支持高级格式控制；
6. 有必要的话会加上背景介绍注释。

## 计划

1. [x] 先根据现有英文`srt`字幕，转换为`ass`字幕并修订时间轴。包括合并句子、重新断句、修正时间、订正错误等；
2. [ ] 考证现存字幕（http://www.linuxforum.net/ 译制的的版本）
3. [ ] 根据现有中文字幕，与新英文时间轴进行合并、适配；
4. [ ] 修正、润色新中文字幕；
5. [ ] 可能会新开一套注释字幕，如名词解释、人物传记、地理介绍、吐槽等。

## 协议
GPL 2.0

## 附录
1. 活跃的工程文件为项目根目录下的 `Revolution.OS.2001.DVDRip.Mkv-RETRO.English.ass`
2. 我自己使用`Aegisub`作为字幕软件
3. 若您有兴趣参与，可以先开一个 `Issue Ticket` 让大家知道你想做哪一部分（可从`Chapters.xml`看到章节列表以及时间）
4. 视频时间轴基于原版DVD镜像：
```
magnet:?xt=urn:btih:C78C0E9C88CCC1649D41A8653ED78C447B02A16E&dn=Revolution%20OS&tr=udp%3a%2f%2ftracker.leechers-paradise.org%3a6969&tr=udp%3a%2f%2fzer0day.ch%3a1337&tr=udp%3a%2f%2fopen.demonii.com%3a1337&tr=udp%3a%2f%2ftracker.coppersurfer.tk%3a6969&tr=udp%3a%2f%2fexodus.desync.com%3a6969
```
5. 我最喜欢的简体中文版本（字幕文本文件似乎已失传，只有嵌在rmvb里的版本）
> 那是在2000年例会（Agenda 2000）期间 
> 参加人的里有个叫Craig Mundie的家伙 
> 是Microsoft公司的一个大头头 
> 我觉得，嗯，是管客户产品的副总裁吧，或是 
> 和那差不多的大头。 
> 实际上，我并未和他正式会面 
> 我...我只是碰巧在电梯里撞见他的 
> 我看了看他的徽章说： 
> “哦，你替Microsoft工作的吧。” 
> 他回头看了我，说：“哦，是的。你呢？” 
> 我想他对我不屑一顾 
> 我的意思是，他是那种典型的，西装革履的家伙 
> 瞧着一个衣衫不整的黑客 
> 我狠狠的瞪了他一眼，说： 
> “我是你最可怕的噩梦。” 