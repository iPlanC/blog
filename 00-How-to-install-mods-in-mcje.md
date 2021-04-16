<!--
 * @Author: PlanC
 * @Date: 2021-04-16 12:06:01
 * @LastEditTime: 2021-04-16 14:29:22
 * @FilePath: \blog\00-How-to-install-mods-in-mcje.md
-->

# 如何在国际版Minecraft安装mod
###### 下文以安装适配1.16.5版本的wurst为例
<del>其实就是懒得再找mod了</del>

## 下载目标版本原版游戏
在启动器中配置页新建目标版本的配置档，下载完成启动成功后退出游戏。

## 选择forge还是farbic
这里通常是由mod所依赖的API来判断，以`wurst`为例他需要`farbicAPI`来加载，

### 下载farbic Installer
[https://maven.fabricmc.net/net/fabricmc/fabric-installer/0.7.3/fabric-installer-0.7.3.exe](https://maven.fabricmc.net/net/fabricmc/fabric-installer/0.7.3/fabric-installer-0.7.3.exe)
下载完成后打开选择对应版本和安装位置<sub>(一般默认)</sub>，点击安装

### 下载farbicAPI
[https://minecraft.curseforge.com/projects/fabric/files](https://minecraft.curseforge.com/projects/fabric/files)
通过人机验证后即可进入下载页面，对目标版本<sub>(1.16.5)</sub>的farbicAPI下载

### 安装mod
在启动器配置页，任意一个配置档点击文件夹图标，即可打开根目录，再次新建mods文件夹将`fabric-api-0.32.9+1.16.jar`拖入，并运行游戏测试，成功运行后将所需mod的jar包拖入，重启游戏测试，如果一切正常，恭喜，自此mod安装成功。
