翻译自 https://github.com/rob-med/awesome-TS-anomaly-detection

# 绝佳的时间序列异常检测工具

> 对***时间序列*数据异常检测**的工具和数据集列表。

所有列表都是按字母顺序排列的。如果一个版本库最近一次提交的时间大于1年，或者作者明确提到，则该版本库被认为是 "未维护（not maintained） "的。

## 异常检测包

| 名称                                                         | 语言             | 简介                                                         | 许可证                                                       | 维护状态 |
| ------------------------------------------------------------ | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- |
| Expedia.com's [Adaptive Alerting](https://github.com/ExpediaDotCom/adaptive-alerting) | Java             | 流式异常检测与自动模型选择和拟合。Streaming anomaly detection with automated model selection and fitting. | Apache-2.0                                                   | ✔️        |
| Arundo's [ADTK](https://github.com/arundo/adtk)              | Python           | 异常检测工具包（ADTK）是一个Python包，用于无监督/基于规则的时间序列异常检测。 | MPL 2.0                                                      | ✔️        |
| Twitter's [AnomalyDetection](https://github.com/twitter/AnomalyDetection) | R                | AnomalyDetection是一个开源的R包，用于检测异常，从统计学的角度来看，在存在季节性和潜在趋势的情况下，它是稳健的。 | GPL                                                          | ❌        |
| Lytics' [Anomalyzer](https://github.com/lytics/anomalyzer)   | Go               | Anomalyzer实现了一套统计测试，这些测试产生了一组给定的数字输入（通常是一个时间序列）包含异常行为的概率。 | Apache-2.0                                                   | ❌        |
| [banpei](https://github.com/tsurubee/banpei)                 | Python           | 时间序列的离群点检测（Hotelling理论）和变化点检测（奇异谱变换）。 | MIT                                                          | ✔️        |
| Ele.me's [banshee](https://github.com/facesea/banshee)       | Go               | 周期性指标的异常检测系统。                                   | MIT                                                          | ❌        |
| [CAD](https://github.com/smirmik/CAD)                        | Python           | Contextual Anomaly Detection for real-time AD on streagming data（2016年NAB大赛获奖算法）。 | AGPL                                                         | ❌        |
| Mentat's [datastream.io](https://github.com/MentatInnovations/datastream.io) | Python           | 一个使用Python、Elasticsearch和Kibana进行实时异常检测的开源框架。 | Apache-2.0                                                   | ❌        |
| [DeepADoTS](https://github.com/KDD-OpenSource/DeepADoTS)     | Python           | 基于深度学习的7种异常检测技术在时间序列数据上的实现与评估.   | MIT                                                          | ✔️        |
| [Donut](https://github.com/korepwx/donut)                    | Python           | Donut是一种基于Variational Autoencoders的季节性KPIs的无监督异常检测算法。 | -                                                            | ✔️        |
| Yahoo's [EGADS](https://github.com/yahoo/egads)              | Java             | GADS是一个包含许多异常检测技术的库，这些技术适用于单一包中的许多用例，唯一的依赖是Java。 | GPL                                                          | ✔️        |
| [Hastic](https://github.com/hastic)                          | Python + node.js | 基于Grafana用户界面的时间序列数据异常检测工具。              | GPL                                                          | ✔️        |
| [LoudML](https://github.com/regel/loudml)                    | Python           | Loud ML是一个建立在TensorFlow之上的开源时间序列推理引擎。它对于预测数据、检测异常值以及使用未来知识自动处理数据非常有用。 | MIT                                                          | ✔️        |
| Linkedin's [luminol](https://github.com/linkedin/luminol)    | Python           | Luminol是一个用于时间序列数据分析的轻量级python库。它支持的两个主要功能是异常检测和相关。它可以用来研究异常的可能原因。 | Apache-2.0                                                   | ❌        |
| [MIDAS](https://github.com/bhatiasiddharth/MIDAS)            | C++              | MIDAS，是基于微集群的边缘流异常检测器的简称，它能从边缘流中检测出恒定时间和内存的微集群异常。 | Apache-2.0                                                   | ✔️        |
| Numenta's [Nupic](https://github.com/numenta/nupic)          | C++              | Numenta Platform for Intelligent Computing是Hierarchical Temporal Memory（HTM）的实现。 | AGPL                                                         | ✔️        |
| [oddstream](https://github.com/pridiltal/oddstream)          | R                | oddstream(数据流中的异常值检测)为大量流式时间序列数据集合中的异常序列的早期检测提供实时支持。 | GPL-3                                                        | ✔️        |
| [PyOD](https://pyod.readthedocs.io/en/latest/)               | Python           | PyOD是一个全面的、可扩展的Python工具箱，用于检测多变量数据中的离群对象。 | BSD 2-Clause                                                 | ✔️        |
| [PyOdds](https://github.com/datamllab/pyodds)                | Python           | PyODDS是一个端到端的Python系统，用于支持数据库的异常点检测。PyODDS提供了支持静态和时间序列数据的异常点检测算法。 | MIT                                                          | ✔️        |
| [PySAD](https://github.com/selimfirat/pysad)                 | Python           | PySAD是一个流式异常检测框架，拥有各种在线模型和整套实验工具。 | BSD 3-Clause                                                 | ✔️        |
| [rrcf](https://github.com/kLabUM/rrcf)                       | Python           | 流上异常检测的Robust Random Cut Forest算法的实现。           | MIT                                                          | ✔️        |
| [ruptures](https://github.com/deepcharles/ruptures/)         | Python           | Ruptures是一个离线变化点检测的Python库。该包提供了非稳态信号的分析和分割方法。 | BSD 2-Clause                                                 | ✔️        |
| EarthGecko [Skyline](https://github.com/earthgecko/skyline)  | Python3          | Skyline是一个实时的异常检测系统，它的构建是为了实现对数十万个指标的被动监测。 | MIT                                                          | ✔️        |
| Netflix's [Surus](https://github.com/netflix/surus)          | Java             | Robust Anomaly Detection (RAD) - Robust PCA的一个实现。      | Apache-2.0                                                   | ❌        |
| NASA's [Telemanom](https://github.com/khundman/telemanom)    | Python           | 利用LSTMs探测多变量时间序列数据中的异常现象的框架。包括来自火星科学实验室和SMAP任务的航天器异常数据和实验。 | [custom](https://github.com/khundman/telemanom/blob/master/LICENSE.txt) | ✔️        |
| Zillow's [Luminaire](https://github.com/zillow/luminaire)    | Python           | Luminaire是一个python包，为时间序列数据提供ML驱动的异常检测和预测解决方案。 | Apache-2.0                                                   | ✔️        |

## 相关包

本节包括一些用于异常检测相关任务的时间序列包，如预测和标记。

### 预测

| 名称                                                      | 语言     | 简介                                                         | 许可证       | 维护状态 |
| --------------------------------------------------------- | -------- | ------------------------------------------------------------ | ------------ | -------- |
| Amazon's [GluonTS](https://github.com/awslabs/gluon-ts)   | Python   | GluonTS是一个Python工具箱，用于围绕MXNet建立概率时间序列模型。GluonTS提供了用于加载和迭代时间序列数据集的实用工具，提供了可供训练的最先进的模型，还提供了用于定义你自己的模型的构建模块。 | Apache-2.0   | ✔️        |
| [pmdarima](https://github.com/tgsmith61591/pyramid)       | Python   | 移植R的*auto.arima*与scikit-learn友好的界面。                | MIT          | ✔️        |
| Facebook's [Prophet](https://github.com/facebook/prophet) | Python/R | Prophet是一个预测时间序列数据的程序。它是基于一个加法模型，在这个模型中，非线性趋势与年和周的季节性，再加上节假日进行拟合。 | BSD          | ✔️        |
| [PyFlux](https://github.com/RJT1990/pyflux)               | Python   | 该库有一系列良好的现代时间序列模型，以及一系列灵活的推理选项（frequentist 和Bayesian），可以应用于这些模型。 | BSD 3-Clause | ❌        |
| [SaxPy](https://github.com/seninp/saxpy)                  | Python   | SAX的一般实现，以及用于异常检测的HOTSAX。                    | GPLv2.0      | ✔️        |
| [seglearn](https://github.com/dmbee/seglearn)             | Python   | Seglearn是一个用于机器学习时间序列或序列的python包。它提供了一个集成的分割、特征提取、特征处理和最终估计器的pipeline 。 | BSD 3-Clause | ✔️        |
| [Tigramite](https://github.com/jakobrunge/tigramite)      | Python   | Tigramite是一个因果时间序列分析python包。它允许从高维时间序列数据集中有效地重建因果图，并对获得的因果依赖关系进行建模，以进行因果中介和预测分析。 | GPLv3.0      | ✔️        |
| [tslearn](https://github.com/rtavenar/tslearn)            | Python   | tslearn是一个Python包，它提供了用于分析时间序列的机器学习工具。这个包建立在scikit-learn、numpy和scipy库的基础上。 | BSD 2-Clause | ✔️        |

### 标注

| 名称                                                         | 语言                   | 简介                                                         | 许可证     | 维护状态 |
| ------------------------------------------------------------ | ---------------------- | ------------------------------------------------------------ | ---------- | -------- |
| Baidu's [Curve](https://github.com/baidu/Curve)              | Python                 | Curve是一个开源工具，可以帮助在时间序列数据上标注异常情况。  | Apache-2.0 | ✔️        |
| Microsoft's [Taganomaly](https://github.com/Microsoft/TagAnomaly) | R (dockerized web app) | 用于标记时间序列数据的简单工具。适用于单变量和多变量数据，提供使用Twitter的AnomalyDetection包进行异常预测的参考。 | MIT        | ✔️        |

## 基准数据集

- Numenta's [NAB](https://github.com/numenta/NAB)

> NAB是一种新型的基准，用于评估流式实时应用中的异常检测算法。它由超过50个标记的真实世界和人工时间序列数据文件以及为实时应用设计的新型评分机制组成。

- Yahoo's [Webscope S5](https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70)

> 数据集由真实和合成的时间序列组成，带有标记的异常点。该数据集测试了各种异常类型的检测精度，包括异常点和变化点。

- 2020 Skoltech's [SKAB](https://github.com/waico/SkAB)

> SKAB（Skoltech Anomaly Benchmark）是为评估异常检测算法而设计的。该基准目前包括30多个数据集和Python模块，用于评估算法。每个数据集代表了从测试平台上安装的传感器收集的多变量时间序列。所有实例都有标签，用于评估解决异常点检测和变化点检测问题的结果。

- 2018 AIOps's [KPI-Anomaly-Detection](https://github.com/NetManAIOps/KPI-Anomaly-Detection)

> 该数据集由多个真实场景的互联网公司的KPI（关键绩效指数）时间序列数据组成，并贴有地面真实标签。KPI分为两大类：服务KPI和机器KPI。服务KPI是反映Web服务规模和质量的性能指标，如页面响应时间、页面浏览量、连接错误次数等。机器KPI是反映机器（服务器、路由器、交换机）健康状况的性能指标，如CPU利用率、内存利用率、磁盘IO、网卡吞吐量等。数据集描述。
>
> 为了训练异常检测算法，我们提供的训练KPI数据如表1所示，包括四列。KPI ID、时间戳、KPI当时的值、时间是否异常（标签）。
>
> 表1训练KPI数据案例
>
> | KPI ID | Timestamp  | Value | Label |
> | ------ | ---------- | ----- | ----- |
> | 0      | 1503831000 | 10.8  | 0     |
> | 0      | 1503831060 | 12.3  | 1     |
> | ...    | ...        | ...   | ...   |
>
> 为了评估异常检测算法，我们提供的测试KPI数据如表2所示，包括两栏。KPI ID、时间戳，以及当时KPI对应的数值。
>
> 表2测试KPI数据案例
>
> | KPI ID | Timestamp  | Value |
> | ------ | ---------- | ----- |
> | 0      | 1503831000 | 10.8  |
> | 0      | 1503831060 | 12.3  |
> | ...    | ...        | ...   |



## 引用方法

If you would like to cite this repository, please use the following DOI:

[![DOI](https://camo.githubusercontent.com/2ce3e016d3bc58f11ff5fe48c247443fba8582871a3ccb77a79c7fbd07ef87b0/68747470733a2f2f7a656e6f646f2e6f72672f62616467652f3131343737383937392e737667)](https://zenodo.org/badge/latestdoi/114778979)

or use this BibTex

```
 @article{medico2020, 
          title={rob-med/awesome-TS-anomaly-detection}, 
          DOI={10.5281/zenodo.3972944}, 
          abstractNote={A collection of tools and datasets for anomaly detection on time-series data.}, 
          publisher={Zenodo}, author={Roberto Medico}, year={2020}, month={Aug}}
```