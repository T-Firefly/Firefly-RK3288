# Download Default Android SDK #
**WARNING: If you have downloaded the SDK before Dec 11, 2014, please download again from the cloud drive and make it uptodate.**

The SDK is huge (about 4 GiB). Please **DO NOT CLONE** from Bitbucket directly (It will fail due to network flow limit).

We have provided a tar ball of the .git directory at:

* [Baidu Pan](http://pan.baidu.com/s/1dDhDNGX#path=%252FDevBoard%252FFirefly-RK3288%252FSource%252FAndroid4.4)
* [Google Drive](https://drive.google.com/folderview?id=0B7HO8lbGgAqAdU1tbnNkY25udFE&usp=sharing)

Please check the md5 checksum before proceeding:
```
#!shell
$ md5sum /path/to/firefly-rk3288_android4.4_git_20141211.tar.gz
8fe99f519d487ff40c8bc7b5ded62887  firefly-rk3288_android4.4_git_20141211.tar.gz
```

If it is correct, uncompress it:
```
#!shell
mkdir -p ~/proj/firefly-rk3288
cd ~/proj/firefly-rk3288
tar xf /path/to/firefly-rk3288_android4.4_git_20141211.tar.gz
git reset --hard
git remote add bitbucket https://bitbucket.org/T-Firefly/firefly-rk3288.git
```

From now on, you can pull updates from Bitbucket:
```
#!shell
git pull bitbucket master:master
```

# Download PAD Android SDK #

The SDK is huge (about 4 GiB). Please **DO NOT CLONE** from Bitbucket directly (It will fail due to network flow limit).

We have provided a tar ball of the .git directory at:

* [Baidu Pan](http://pan.baidu.com/s/1dDhDNGX#path=%252FDevBoard%252FFirefly-RK3288%252FSource%252FAndroid4.4_Pad)
* [Google Drive](https://drive.google.com/open?id=0B7HO8lbGgAqAVVBnQkdmay1qSkU&amp;authuser=0)

Please check the md5 checksum before proceeding:
```
#!shell
$ md5sum /path/to/firefly-rk3288_pad_android4.4_git_20141218.tar.gz
4ba44765fa649bc5cddadd8b349aa8af  firefly-rk3288_pad_android4.4_git_20141218.tar.gz
```

If it is correct, uncompress it:
```
#!shell
mkdir -p ~/proj/firefly-rk3288_pad
cd ~/proj/firefly-rk3288_pad
tar xf /path/to/firefly-rk3288_pad_android4.4_git_20141218.tar.gz
git reset --hard
git remote add bitbucket https://bitbucket.org/T-Firefly/firefly-rk3288.git
```

From now on, you can pull updates from Bitbucket:
```
#!shell
git pull bitbucket pad:pad
```

Please visit the following website for more details of our Firefly-RK3288 devolopment board. Thank you.

http://www.t-firefly.com/en/

# 下载 默认版 Android SDK #
**注意：如果你在 2014-12-11 之前下载过源码，请重新到云盘下载并更新。**

SDK 非常巨大（约 4GiB），请**不要直接从 Bitbucket 下载 **仓库源码（由于流量限制的原因会出错）。

我们提供了 .git 目录的打包，放到云盘上以供下载：

* [百度云盘](http://pan.baidu.com/s/1dDhDNGX#path=%252FDevBoard%252FFirefly-RK3288%252FSource%252FAndroid4.4)
* [Google Drive](https://drive.google.com/folderview?id=0B7HO8lbGgAqAdU1tbnNkY25udFE&usp=sharing)

下载完成后先验证一下 MD5 码：
```
#!shell
$ md5sum /path/to/firefly-rk3288_android4.4_git_20141211.tar.gz
8fe99f519d487ff40c8bc7b5ded62887  firefly-rk3288_android4.4_git_20141211.tar.gz
```

确认无误后，就可以解压：
```
#!shell
mkdir -p ~/proj/firefly-rk3288
cd ~/proj/firefly-rk3288
tar xf /path/to/firefly-rk3288_android4.4_git_20141211.tar.gz
git reset --hard
git remote add bitbucket https://bitbucket.org/T-Firefly/firefly-rk3288.git
```

之后就可以从 Bitbucket 处获取更新的提交，保持同步:
```
#!shell
git pull bitbucket master:master
```
# 下载 PAD 版 Android SDK #

SDK 非常巨大（约 4GiB），请**不要直接从 Bitbucket 下载 **仓库源码（由于流量限制的原因会出错）。

我们提供了 .git 目录的打包，放到云盘上以供下载：

* [百度云盘](http://pan.baidu.com/s/1dDhDNGX#path=%252FDevBoard%252FFirefly-RK3288%252FSource%252FAndroid4.4_Pad)
* [Google Drive](https://drive.google.com/open?id=0B7HO8lbGgAqAVVBnQkdmay1qSkU&amp;authuser=0)

下载完成后先验证一下 MD5 码：
```
#!shell
$ md5sum /path/to/firefly-rk3288_pad_android4.4_git_20141218.tar.gz
4ba44765fa649bc5cddadd8b349aa8af  firefly-rk3288_pad_android4.4_git_20141218.tar.gz
```

确认无误后，就可以解压：
```
#!shell
cd ~/proj/firefly-rk3288_pad
tar xf /path/to/firefly-rk3288_pad_android4.4_git_20141218.tar.gz
git reset --hard
git remote add bitbucket https://bitbucket.org/T-Firefly/firefly-rk3288.git
```

之后就可以从 Bitbucket 处获取更新的提交，保持同步:
```
#!shell
git pull bitbucket pad:pad
```

想了解更多我们 Firefly-RK3288 开发板的详情，请浏览以下网址，谢谢！

  http://www.t-firefly.com
