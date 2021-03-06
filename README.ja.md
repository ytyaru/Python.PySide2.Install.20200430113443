[en](./README.md)

# PySide2.Install

　PySide2をインストールする。

# デモ

![demo](doc/demo.png)

# 開発環境

* <time datetime="2020-04-30T11:34:31+0900">2020-04-30</time>
* [Raspbierry Pi](https://ja.wikipedia.org/wiki/Raspberry_Pi) 4 Model B Rev 1.2
* [Raspbian](https://ja.wikipedia.org/wiki/Raspbian) buster 10.0 2019-09-26 <small>[setup](http://ytyaru.hatenablog.com/entry/2019/12/25/222222)</small>
* bash 5.0.3(1)-release
* Python 3.7.3
* Qt 5.11.2
* PySide

```sh
$ uname -a
Linux raspberrypi 4.19.97-v7l+ #1294 SMP Thu Jan 30 13:21:14 GMT 2020 armv7l GNU/Linux
```

# インストール

```sh
sudo apt -y install build-essential git cmake qt5-default libxml2 libxslt1.1 python-dev qtbase5-dev
sudo apt -y install qttools5-dev-tools libqt5clucene5 libqt5concurrent5 libqt5core5a libqt5dbus5 libqt5designer5 libqt5designercomponents5 libqt5feedback5 libqt5gui5 libqt5help5 libqt5multimedia5 libqt5network5 libqt5opengl5 libqt5opengl5-dev libqt5organizer5 libqt5positioning5 libqt5printsupport5 libqt5qml5 libqt5quick5 libqt5quickwidgets5 libqt5script5 libqt5scripttools5 libqt5sql5 libqt5sql5-sqlite libqt5svg5 libqt5test5 libqt5webkit5 libqt5widgets5 libqt5xml5 libqt5xmlpatterns5 libqt5xmlpatterns5-dev 

# Python3
sudo apt -y install python3-pyside2.qt3dcore python3-pyside2.qt3dinput python3-pyside2.qt3dlogic python3-pyside2.qt3drender python3-pyside2.qtcharts python3-pyside2.qtconcurrent python3-pyside2.qtcore python3-pyside2.qtgui python3-pyside2.qthelp python3-pyside2.qtlocation python3-pyside2.qtmultimedia python3-pyside2.qtmultimediawidgets python3-pyside2.qtnetwork python3-pyside2.qtopengl python3-pyside2.qtpositioning python3-pyside2.qtprintsupport python3-pyside2.qtqml python3-pyside2.qtquick python3-pyside2.qtquickwidgets python3-pyside2.qtscript python3-pyside2.qtscripttools python3-pyside2.qtsensors python3-pyside2.qtsql python3-pyside2.qtsvg python3-pyside2.qttest python3-pyside2.qttexttospeech python3-pyside2.qtuitools python3-pyside2.qtwebchannel python3-pyside2.qtwebsockets python3-pyside2.qtwidgets python3-pyside2.qtx11extras python3-pyside2.qtxml python3-pyside2.qtxmlpatterns python3-pyside2uic

# Python2
#sudo apt -y install python-pyside2.qt3dcore python-pyside2.qt3dinput python-pyside2.qt3dlogic python-pyside2.qt3drender python-pyside2.qtcharts python-pyside2.qtconcurrent python-pyside2.qtcore python-pyside2.qtgui python-pyside2.qthelp python-pyside2.qtlocation python-pyside2.qtmultimedia python-pyside2.qtmultimediawidgets python-pyside2.qtnetwork python-pyside2.qtopengl python-pyside2.qtpositioning python-pyside2.qtprintsupport python-pyside2.qtqml python-pyside2.qtquick python-pyside2.qtquickwidgets python-pyside2.qtscript python-pyside2.qtscripttools python-pyside2.qtsensors python-pyside2.qtsql python-pyside2.qtsvg python-pyside2.qttest python-pyside2.qttexttospeech python-pyside2.qtuitools python-pyside2.qtwebchannel python-pyside2.qtwebsockets python-pyside2.qtwidgets python-pyside2.qtx11extras python-pyside2.qtxml python-pyside2.qtxmlpatterns python-pyside2uic
```

# 使い方

```sh
git clone https://github.com/ytyaru/Python.PySide2.Install.20200430113443
cd Python.PySide2.Install.20200430113443/src
./run.sh
```

# 著者

　ytyaru

* [![github](http://www.google.com/s2/favicons?domain=github.com)](https://github.com/ytyaru "github")
* [![hatena](http://www.google.com/s2/favicons?domain=www.hatena.ne.jp)](http://ytyaru.hatenablog.com/ytyaru "hatena")
* [![mastodon](http://www.google.com/s2/favicons?domain=mstdn.jp)](https://mstdn.jp/web/accounts/233143 "mastdon")

# ライセンス

　このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

