# TTScan介绍
此项目由pppXray升级而来，在原有基础上做了大量升级，升级后 爬虫引擎使用长亭的Rad，项目中自带Chrome，无需配置路径，Rad自动调用，漏洞扫描使用集成的Xray高级破解版，扫描更全面化，精细化，自动集成了各种环境，实现一键批量挖漏，支持自写poc
长期更新维护，下一步就是集成子域名实时监测，端口扫描，webhook通知，灯塔资产系统
# 特点

- 项目自带Chrome浏览器
- 项目自带Rad爬虫引擎
- 项目自带Xray高级破解版，对于目标会自动验证高级版POC
- 支持自写POC验证，放置在xraypoc目录下，每次扫描会自动调用
- 免环境配置，下载即用
- 支持批量漏洞扫描
- Xray批量化自动扫描

使用方法：
一，在target.txt里按行放置待扫描URL，如图：
![image.png](https://upload-images.jianshu.io/upload_images/20144153-8b15e688fa97ada0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

二、使用python3运TTScan-Py3即可
![image.png](https://upload-images.jianshu.io/upload_images/20144153-c77c99245c8176b9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


三、其他使用方法，和pppXray是一样的
添加命令行参数与自定义xray插件用法，可通过 --help查看
![image.png](https://upload-images.jianshu.io/upload_images/20144153-3436642cb37a6b80.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

漏洞结果保存在Save目录下

![image.png](https://upload-images.jianshu.io/upload_images/20144153-c7c409e9e86ad16e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
