原项目扫描多了会导致卡死白屏，所有在这个修复版上增加了点小功能https://github.com/XinCaoZ/RouteVulScanPlus
## 更新内容
1.自定义减少误报，正则过滤响应包里的内容。  
    在`Config_yaml.yaml`里对应`respCustomFilter`  
![222](https://raw.githubusercontent.com/d1sbb/RouteVulScanPlus/refs/heads/master/img/222.png)  
    例子：`respCustomFilter: '("status":404)|(Disallow: /)'`
![111](https://raw.githubusercontent.com/d1sbb/RouteVulScanPlus/refs/heads/master/img/111.png)  
2.startTime改为上海时区  

原项目
https://github.com/F6JO/RouteVulScan/blob/main/README.md
## 可能的报错
如果出现error报错，请先下载 https://github.com/F6JO/RouteVulScan/releases/tag/RouteVulScan1.5.4 里的jar包

并且放到你的burp设置Extensions -> Java environment里的文件夹里（因为我懒的继续学完整编译jar包了）
## 其他
![333](https://github.com/F6JO/RouteVulScan/blob/main/img/remove.jpg)
<img width="1323" alt="image" src="https://github.com/user-attachments/assets/6d3350f1-f94c-4b98-89ce-d8638360c12b">
