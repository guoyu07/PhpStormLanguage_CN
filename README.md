# PhpStorm简体中文语言包
虽然说对于IDE那么点的英文量来说没有啥必要汉化 PhpStorm ，但还是有很多人在搜索汉化版，所以开一个汉化项目。

## 文件结构

目录 | 说明
----|-----
+--releases | 转码后jar文件
+--src | 
   +---jar_lib | 转码后jar源文件
      +---resources_cn | 中文 
      \---resources_en | 英文
   \---messages | 汉化过程文件
       +---cn | 中文
       \---en | 英文
\---tools | 工具


## 参与汉化
> 本汉化项目托管于[Transifex.com](https://www.transifex.com/involvements/phpstorm "点击去Transifex一起翻译")
>
> 汉化进度:
>
>![](https://www.transifex.com/projects/p/phpstorm/resource/actionsbundleproperties/chart/image_png)

## 使用方法
1. 下载[resources_cn.jar](https://github.com/involvements/PhpStormLanguage_CN/raw/master/releases/resources_cn.jar)文件；
2. 复制resources_cn.jar到PhpStorm安装目录的 *[lib]* 文件夹，一般为 *[C:\Program Files (x86)\JetBrains\PhpStorm ()2016.2.1\lib]* ;
3. 重启PhpStorm。