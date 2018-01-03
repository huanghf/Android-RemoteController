# AndroidRemoteController
readme-中文
是一个远程控制第三方音乐播放器的项目。
在了解项目之前我们需要弄清楚2个知识点：
1、所有音乐播放App，它们都有注册耳机插拔的广播，还有就是你可以通过控制耳机按键来控制音乐播放，而耳机按键事件是可以模拟的，这就为控制第三方音乐播放器提供可能。
2、所有的音乐播放App，它们都会在通知栏有常驻的Notification来显示当前一些歌曲的信息，关于接收音乐信息的问题，这里指的是接收专辑、歌手专辑封面等等，那如何获取呢，一种方式是通过反射，但是普遍性比较差。在Android API 19中，谷歌为我们提供了RemoteController。
通过以上知识点，我们就能拿到第三方音乐播放App的各种音乐信息，并且控制第三方音乐播放。
readme-en
Is a project to remotely control third-party music players.
Before we understand the project we need to find out two knowledge points:
1, all music player App, they have registered headphones plug the radio, there is that you can control the headphone button to control music playback, and headphone button events can be simulated, which is to control the third-party music player may.
2, all the music player App, they will have a permanent notice Notification column to display some of the current song information on the reception of music information, here refers to receiving albums, artist album covers, etc., then how to get it One way is by reflection, but less universal. In Android API 19, Google provided us RemoteController.
Through the above knowledge point, we can get a variety of music information of third-party music player App, and control the third-party music player.
