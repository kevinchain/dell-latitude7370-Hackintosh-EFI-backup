# dell-latitude7370-Hackintosh-EFI-backuppe
## 本配置禁止作为商用 

***仅需替换efi中的clover文件夹，efi中包含我的引导信息可能会找不到mac的安装盘*** 

***更换1820a网卡需屏蔽针脚！！！！*** 

***修改dvmt存在风险！！！***   

**更新 2020-3-29** 

修复开机苹果LOGO变大的问题，添加显卡信息

**更新 2020-2-13** 

 修复facksmc.kext 导致有一定概率无法启动的问题

**更新 2020-2-11**  

修复温度显示

**更新 2019-12-15**
添加dsdt补丁，修复电量显示问题和休眠问题

**更新 2019-11-12**  

修复type-c接口（修眠后会失效）  

声卡耳机修复脚本： [链接](https://github.com/mikeTOliu/daliansky-ALCPlugFix)  

触摸板手势是真的没办法了，求大佬帮忙

---
**更新 2019-11-7** 

修复无故重启，优化网卡驱动，声卡确认内建可用，修复杂音，择期更新内建脚本

--- 
## 戴尔latitude7370 clover 配置

Dell latitude 7370 

Cpu:core m5 

Gpu : hd515 

wifi替换为dw1820a

**首先进入gurb执行以下代码修改dvmt大小** 

**（该操作存在风险，如对设备有任何损坏本人概不负责）**

`setup_var 0x432 0x3`
- 可正常使用
  
    1. 显卡驱动正常  

    2. 声卡内建耳机孔扬声器正常

  3. 内置键盘正常
  4. 变频正常 
  5. 触摸屏正常
  6. 亮度休眠正常  
  7. 电池显示正常
  8. airdorp 正常

- 存在的问题
  1. 触摸板手势无法使用
  2. 雷电接口无法热插拔 
   
