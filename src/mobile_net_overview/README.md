# 移动网络概述

总结移动网络相关知识。

## 概述

### 从1G到5G

* 相关名词和术语
  * 5GC Core
    * gNB, AMF, SMF, NSSF, UDM, AUSF, UPF
  * 4G LTE
    * eNB, MME, SGW, PGW, HSS, EIR, PCRF, OCS & OFCS
  * IMS
    * CSCFs, HSS, MGCF, MGW, AS, OCS & OFCS 
  * 3G
    * NB, HNB, HNBGW, RNC, MSC, SGSN, GGSN
  * 2G
    * BTS, BSC, MSC, HLR, EIR, VLR, SMSC, GMSC
  * TDM | PSTN
    * ISDN, ISUP, CAS
      * requires additional PSTN Network setup
  * Supports IPSec, TLS, SRTP, and MSRP

### 不同实现

* GL
  * Simulation of CSFB for Voice and SMS over SGs Interface
    * ![gl_simu_csfb_for_voice_sms_sgs](../../assets/img/gl_simu_csfb_for_voice_sms_sgs.jpg)
  * Simulation of IP-SM-GW for SMS over IMS Network
    * ![gl_simu_ip_sw_gw_for_sms_ims](../../assets/img/gl_simu_ip_sw_gw_for_sms_ims.jpg)
* 其他
  * ![other_network_arch_ims](../../assets/img/other_network_arch_ims.jpg)

## 网络接口

* 背景
  * 不同网络，不同运营商，很复杂
  * 希望不同用户可以互相沟通
* 涉及到
  * 不同网络之间的沟通：
    * NNI=Network-to-Network Interface
  * 终端网络和用户之间的沟通
    * UNI=User-to-Network Interface

## VoLTE和RCS

* 共同特点
  * 都是基于IMS架构演化出的新功能
* 共存
  * 运营商部署`VoLTE`时，往往也会部署`RCS`
    * 用于一步到位，支持全`IP`的网络
      * `RCS`可看成是旧的`SMS`和`MMS`的演化
  * 在某些特定场景下，（比如信号不够好？）`VoLTE`也会用`CS`的服务作为补充
  * 以`RCS`为基础的`VoWiFi`的电话，有时候可以作为`VoLTE`和`CS`的补充
