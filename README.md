原项目扫描多了会导致卡死白屏，所有在这个修复版上增加了点小功能https://github.com/XinCaoZ/RouteVulScanPlus

1.自定义减少误报，正则过滤响应包里的内容。  
    在Config_yaml.yaml里对应respCustomFilter
![222](https://raw.githubusercontent.com/d1sbb/RouteVulScanPlus/refs/heads/master/img/222.png)
    例子：`respCustomFilter: '("status":404)|(Disallow: /)'`
![111](https://raw.githubusercontent.com/d1sbb/RouteVulScanPlus/refs/heads/master/img/111.png)
2.startTime改为上海时区  

原项目
https://github.com/F6JO/RouteVulScan/blob/main/README.md

如果出现error报错，请先下载https://github.com/F6JO/RouteVulScan/releases/tag/RouteVulScan1.5.4里的jar包

并且放到你的burp设置Extensions -> Java environment里的文件夹里（因为我懒的继续学完整编译jar包了）
