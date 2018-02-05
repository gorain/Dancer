# Dancer
>作者：郑君
>Author Junruoyu Zheng

***本软件具有极强的个人主义风格，如果不适应请勿使用***

*主界面*

![](./ReadMeFigures/main_window.jpg)

---
我没有什么：

- 音乐控制键只包含播放键/暂停键，不能切歌；
- 不能拖曳进度条，进度条仅供显示；
- 不能调节窗口大小；
- 仅有随机和单曲循环两种播放模式（包括歌单内随机播放）；
- 单击关闭不会直接退出，而是等待当前歌曲播放完（再次单击关闭可以强制退出）。

我有什么：

- [x] 非常注重随机播放的均匀性，独特的算法强制保证链路的多样性和播放的均匀性；
- [x] 播放信息全记录，用以生成年终总结；
- [x] 可以显示两行歌词；
- [x] 根据文件夹自动生成歌单；
- [ ] 自动云端同步；
- [ ] 可以选择只播放其中一个歌单；
- [x] 可以单曲循环；
- [x] 可以通过配置文件改变窗体主题颜色；
- [x] 帐号登录。

说明：

- 如果打算使用自己的数据库，在Mysql文件夹里有数据库定义。如果想使用我的云端数据库，可以去[这个网站](http://sued-wind.cc:8080/dancer/)上注册一个用户。
- 如果不打算修改源码，只需要把Dancer/Bin/Debug文件夹里的所有文件下载到本地即可。注意：fake文件要改成ini文件，并根据自己的情况修改配置（如设置数据库账户）
- 音乐按歌单放在不同文件夹中，所有文件夹放在一个目录下；
- Enjoy!
