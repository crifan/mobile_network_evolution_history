# 5G

TODO:

把

* [Qualcomm Future of 5G Building a unified, more capable 5G air interface for the next decade and beyond](https://www.qualcomm.com/media/documents/files/making-5g-nr-a-commercial-reality.pdf)
* [The-5G-Guide_GSMA_2019_04_29_compressed.pdf](https://www.gsma.com/wp-content/uploads/2019/04/The-5G-Guide_GSMA_2019_04_29_compressed.pdf)

中关于5G技术内容整理过来

---

> 关于5G更多细节，详见：[5G技术概述](https://book.crifan.com/books/5g_tech_summary/website/)

* 5G
  * =`fifth generation`
  * `3GPP`组织制定的标准
  * 概述
    * ![5g_nr_unified](../../assets/img/5g_nr_unified.png)
  * 频段范围
    * `FR1`=`Frequency Range 1`
      * 包括 sub-6 GHz
    * `FR2`=`Frequency Range 2`
      * 包括了`mmWave`=`mm-wave`的24–100GHz
  * 2G到5G频谱对比
    * ![2g_to_5g_spectrum_usage](../../assets/img/2g_to_5g_spectrum_usage.png)
  * 相关技术
    * Massive MIMO
      * ![4g_anttena_5g_apaa](../../assets/img/4g_anttena_5g_apaa.png)
  * 架构
    * 总体架构
      * Reference Point Architecture of 5G Core Network
        * ![5g_ref_point_arch](../../assets/img/5g_ref_point_arch.png)
      * Service-based Architecture of 5G Core Network
        * ![5g_service_based_arch](../../assets/img/5g_service_based_arch.png)
    * 细节
      * Policy Control Mechanism in 5G Core Network
        * ![5g_arch_policy_ctrl](../../assets/img/5g_arch_policy_ctrl.png)
  * 核心元素=核心功能(function)
    * 包含
      * `AMF`=`Access and Mobility Management function`
      * `SMF`=`Session Management function`
      * `UPF`=`User plane function`
      * `PCF`=`Policy Control Function`
      * `AUSF`=`Authentication Server Function`
      * `UDM`=`Unified Data Management`
      * `AF`=`Application Function`
      * `NEF`=`Network Exposure function`
      * `NRF`=`NF Repository function`
      * `NSSF`=`Network Slice Selection Function`
    * Classification of 5G Core Networks
      * ![5g_cn_function_classification](../../assets/img/5g_cn_function_classification.png)

## 4G vs 5G

* 4G和5G技术参数对比

| Technology | Data Rates | Latency | Mobility Support | Spectrum Efficiency | Users Density |Energy Efficiency |
| ---------- | ---------- | ------------------------ | ------------------- | ------------- | ---------- |
| 5G (NR) | Avg 100 Mb/s<br/>Peak 20 Gb/s |  ~ 1 ms | >500 Km/h | x3 Better<br/>DL- 30 bits/Hz<br/>UL- 15bits/Hz |  1000K/Km<sup>2</sup> | x100 Better |
| 4G (LTE) | Avg 25 Mb/s<br/>Peak 300 Mb/s |  ~10- 50 ms | <=350 Km/h | DL – 6 bits/Hz<br/>UL- 4 Bits/Hz | ~ 2K/Km<sup>2</sup> | Moderate |

* 4G和5G核心网络功能演化对比
  * Comparison of 4G Core Network and 5G Core Network
    * ![4g_vs_5g_core_network](../../assets/img/4g_vs_5g_core_network.png)
  * Transformation of 4G Core Network Functions to 5G Core Network Functions
    * ![4g_vs_5g_cn_function_transform](../../assets/img/4g_vs_5g_cn_function_transform.png)
    * 具体细节
      * Transformation of MME into AMF&UDM
        * ![4g_vs_5g_mme_into_amf_udm](../../assets/img/4g_vs_5g_mme_into_amf_udm.png)

## 5G应用

* 应用
  * 概览
    * ![one_figure_view_all_5g_app](../../assets/img/one_figure_view_all_5g_app.jpg)
    * ![5g_essential_of_next_mobile](../../assets/img/5g_essential_of_next_mobile.jpg)
    * ![5g_expand_mobile_to_industry](../../assets/img/5g_expand_mobile_to_industry.jpg)

## 5G标准版本历史

* 5G标准版本历史
  * 图
    * ![5g_spec_evolution_history](../../assets/img/5g_spec_evolution_history.png)
    * ![5g_spec_development](../../assets/img/5g_spec_development.jpg)
    * THE 3GPP ROADMAP FOR RELEASE 15 AND 16
      * ![3gpp_5g_release_15_16](../../assets/img/3gpp_5g_release_15_16.png)
  * 文字
    * 2015年：开始研究
    * 2017年：第一次发布 5G NSA
    * 2018年：3GPP `Release 15`=5G `phase 1`
      * `eMBB`=`Enhanced Mobile Broadband`
      * `URLLC`=`Ultra-Reliable and Low Latency Communication`
    * 2020年6月：3GPP `Release 16`=5G `phase 2`
      * `mMTC`=`massive Machine Type Communication`
      * `V2V`=`Vehicle to Vehicle`
    * 预计2021年：`Release 17`

## 运营商支持5G情况

![global_mno_support_5g](../../assets/img/global_mno_support_5g.jpg)

