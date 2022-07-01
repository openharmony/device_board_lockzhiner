# device_board_lockzhiner

## 介绍

该仓库托管福州市凌睿智捷电子有限公司开发的产品样例代码，主要包括小凌派-RK2206开发板的相关案例代码。

### 开发板简介

**小凌派-RK2206开发板**

小凌派-RK2206开发板主控器为瑞芯微高性能、高性价比的RK2206芯片，搭载OpenHarmony轻量级操作系统，内置WiFi/AP功能、NFC功能、液晶显示接口以及E53接口，E53接口兼容各类传感器模块，便于多样化的IoT物联网应用；目前小凌派-RK2006开发板已经拥有20+个成熟的应用案例，以及完善的教学课程，可广泛的应用于智慧城市、智能家居、智慧教学、智慧车载以及智慧医疗等多种场景。

## 目录

代码路径：

```
device/board/lockzhiner/                 # vendor_lockzhiner 仓库路径
└── BUILD.gn
└── Kconfig.liteos_m.boards
└── Kconfig.liteos_m.defconfig.boards
└── lingpi				                 # 小凌派-RK2206开发板的目录
    └── BUILD.gn
    └── Kconfig.liteos_m.board
    └── Kconfig.liteos_m.defconfig.board
    └── liteos_m		
        └── BUILD.gn
        └── config.gni			         # 交叉编译脚本
└── README.md
```

## 使用说明

-[小凌派-RK2206开发板编译环境搭建](https://gitee.com/openharmony-sig/device_soc_rockchip/blob/master/rk2206/README_zh.md)

-[小凌派-RK2206开发板案例使用说明](https://gitee.com/openharmony-sig/vendor-lockzhiner/blob/master/lingpi/samples/README_zh.md)

## 相关仓

* [vendor/lockzhiner](https://gitee.com/openharmony-sig/vendor-lockzhiner)
* [device/soc/rockchip](https://gitee.com/openharmony-sig/device_soc_rockchip)

