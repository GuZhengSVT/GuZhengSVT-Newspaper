# 2026-11-13 科技

报道时段：11月12日 12:00 — 11月13日 12:00

## 人工智能

### IBM发布Granite 4.1 LLMON预览模型，用原生标记语言隔离指令与数据

11月13日 03:07 · 重要 · 可靠性 A

IBM Granite团队在Hugging Face发文，发布两个实验性预览模型granite-4.1-3b-LLMON-preview和granite-4.1-8b-LLMON-preview，基于Granite 4.1基座，训练目标是读取和生成LLMON标记文本；团队同时发布GitHub工具包。

LLMON全称LLM Object Notation，是一种面向大模型的原生标记语言。它用保留的特殊token作为结构分隔符，给指令、数据和约束打标签，并用唯一ID把指令与作用数据绑定。团队称，这样模型不必像处理JSON那样从普通字符推断嵌套和转义；JSON面向解析器设计，不是为因果语言模型设计。

IBM称，在部分基准上，隐藏在用户数据中的间接提示注入成功率降至接近零，而常规指令微调模型有较高概率被劫持；同时相对Granite 4.1 Instruct保持通用能力。

来源：[huggingface.co](<https://huggingface.co/blog/ibm-granite/llmon-an-llm-native-markup-language-now-in-granite>)

## 航天宇航

### UARX Space称OSSIE-D轨道转移飞行器完成首飞部署

11月13日 04:00 · 重要 · 可靠性 B

据UARX Space发布的新闻稿，西班牙公司UARX Space的轨道转移飞行器OSSIE-D已由SpaceX Falcon 9发射，并使用该公司SAU&RON 24分离系统完成部署。公司称OSSIE-D完全在西班牙设计制造，75%组件由公司内部开发。

DHV Technology提供的完整电源子系统在入轨后工作正常，包括太阳能阵列、PCDU和电池的初始遥测符合预期。UARX称，这是首次由同一家公司同时提供轨道转移飞行器和分离系统的任务。新闻稿没有给出具体发射日期。

来源：[spacenews.com](<https://spacenews.com/uarx-space-marks-a-milestone-for-spains-space-industry-with-the-maiden-flight-of-ossie-d-featuring-a-complete-power-subsystem-supplied-by-dhv-technology/>)

## 硬件

### Kioxia与Dell构建157PB单机架全闪存配置

11月13日 09:15 · 重要 · 可靠性 B

TechPowerUp报道，Kioxia与Dell在单个42U机架中构建了157PB原始闪存容量的配置，使用16台Dell PowerEdge R7725xd服务器、640块Kioxia 245.76TB LC9系列SSD，运行Dell ObjectScale对象存储平台。每台2U服务器装40块E3.L规格硬盘，16台占32U，剩余10U。

LC9为PCIe 5.0 NVMe硬盘，基于Kioxia第八代BiCS QLC和32 die堆叠。Kioxia称这是业界首个157PB单机架对象存储，依据是自家市场调查；报道指出，公告没有给出价格或可用时间。

来源：[techpowerup.com](<https://www.techpowerup.com/354767/kioxia-and-dell-build-a-157-pb-rack-with-640-ssds>)

## 数码

### 三星智能眼镜将于12月10日在美韩开售，内置Gemini

11月12日 22:00 · 重要 · 可靠性 A · 进展

三星11月12日宣布，其智能眼镜全系将于12月10日在美国和韩国发售，预售从当天开始。产品与Gentle Monster和Warby Parker合作，共30款设计；三星称整机约41克，内置Google Gemini，提供免手操作协助，可帮助用户理解周围环境并进行跨语言交流。

硬件包括1200万像素HDR相机、开放式扬声器和四麦克风阵列，搭载高通Snapdragon AR1 Gen 1平台，单次充电续航最长9小时，搭配充电盒最长72小时。产品计划12月10日发售，尚未上市。

来源：[news.samsung.com](<https://news.samsung.com/global/samsung-announces-december-release-for-intelligent-eyewear-bringing-a-smarter-way-to-see-the-world>)
