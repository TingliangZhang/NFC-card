# NFC-card
NFC Business Card

参考

https://www.instructables.com/PCB-Business-Card-With-NFC/

## 元件选型

NFC Tag

NT3H1101W0FHKH / NT3H2111W0FHKH

https://www.nxp.com/part/NT3H2111W0FHK#/

XQFP没封装

换用

https://www.nxp.com/part/NT3H2111W0FT1#/

https://www.nxp.com/part/NT3H2111W0FTT#/



[TSSOP8](https://www.nxp.com/packages/SOT505-1)封装更薄，用NT3H2111W0FTT

https://www.digikey.cn/product-detail/zh/nxp-usa-inc/NT3H2111W0FTTJ/568-12902-1-ND/5872987?keywords=NT3H2111W0FTTJ

100	4.82480



## 尺寸

标准尺寸

85.6mm×54.0mm×1.0mm



## 天线设计

https://github.com/lachlanA/eagle-to-kicad

导入太麻烦了

用EAGEL导出DXF再用AutoCAD去掉焊盘等（可到Kicad里面编辑），导入到KiCad封装编辑器里面，但是没办法作为铜层，所以直接编辑源码

把F.Adhes全部替换为F.Cu

搞定



## PCB视频

https://www.bilibili.com/video/BV1dK4y1s72o

https://www.jlc.com/portal/factoryVideo/0/0



## 讲座需要Win软件：

腾讯会议

Powerpoint

Altium Designer 20+

KiCad 6.1+

Apowerec录屏

嘉立创下单小助手



## 换用Mac后：

https://support.apple.com/zh-cn/HT208721

安装时把kicad文件夹拷到libraries/application support里面需要授权。最好直接拖到文件夹里面而非快捷方式，这样才能链接库。

