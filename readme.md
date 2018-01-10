纪录片电影 Revolution OS （《操作系统革命》）中文字幕修订计划
===

原字幕由 geekbone.org / shlug.org / WiDE 等倾力制作。

修订缘由
===
1. 该纪录片拍摄发行于2001年，字幕发布于2004年（或更早）。当年为了适应低分辨率屏幕，所使用的字体较大，导致大量手工换行；
2. 同上一条原因，部分长句被迫断句导致阅读体验不佳；
3. 部分时间轴需要修正；
4. 润色 + 修正若干翻译错误；
5. `srt`不支持高级格式控制；
6. 有必要的话会加上背景介绍注释。

计划
===
1. [x] 先根据现有英文`srt`字幕，转换为`ass`字幕并修订时间轴。包括合并句子、重新断句、修正时间、订正错误等；
2. [ ] 根据现有中文字幕，与新英文时间轴进行合并、适配；
3. [ ] 修正、润色新中文字幕；
4. [ ] 可能会新开一套注释字幕，如名词解释、人物传记、地理介绍、吐槽等。

协议
===
GPL 2.0

PS
===
1. 活跃的工程文件为项目根目录下的 `Revolution.OS.2001.DVDRip.Mkv-RETRO.English.ass`
2. 我自己使用`Aegisub`作为字幕软件
3. 若果你有兴趣参与，可以先开一个 `Issue Ticket` 让大家知道你想做哪一部分（可从`Chapters.xml`看到章节列表以及时间）
4. 视频时间轴的确定基于原版DVD镜像：
```
magnet:?xt=urn:btih:C78C0E9C88CCC1649D41A8653ED78C447B02A16E&dn=Revolution%20OS&tr=udp%3a%2f%2ftracker.leechers-paradise.org%3a6969&tr=udp%3a%2f%2fzer0day.ch%3a1337&tr=udp%3a%2f%2fopen.demonii.com%3a1337&tr=udp%3a%2f%2ftracker.coppersurfer.tk%3a6969&tr=udp%3a%2f%2fexodus.desync.com%3a6969
```