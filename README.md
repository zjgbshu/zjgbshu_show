# zjgbshu_show
本人曾经做过的项目经历，包含本科&硕士毕业设计，实验室项目等。

## 商务投标系统
**项目信息**：实习公司内部项目，2024年8月——2024年9月，重要成员（全栈工程师）。


**简要介绍**：使用fastapi+vue+PostgreSQL架构开发了内部使用的商务投标系统，并完成了数据库设计、钉钉鉴权、钉钉OA工作流审批的研发内容，实现了包含权限设定、商务文件处理、与钉钉OA审批交互等功能。使用docker将程序打包镜像部署在云服务器上。


**项目展示**：
![Image text](6.bid_file/employee_list.png)
![Image text](6.bid_file/employee_edit.png)
![Image text](6.bid_file/employee_create.png)
![Image text](6.bid_file/filelist.png)
![Image text](6.bid_file/application.png)
![Image text](6.bid_file/login.png)
![Image text](6.bid_file/upload.png)
![Image text](6.bid_file/gitea.png)


## 基于GeoServer的移动对象轨迹可视化系统
**项目信息**：本科毕业设计，2021年9月——2022年6月，作者。


**简要介绍**：本系统托基于GeoServer和、WebGIS和Web应用前后端开发技术，论文按照软件工程的设计和开发流程，对系统进行了需求分析和可行性分析、系统设计、模块及系统实现和系统测试，北京市出租车轨迹进行可视化研究，能够实现通过基于本地开源地图上直观展示的GPS轨迹数据有更直观的认识，还可以进行对例如出租车等移动对象的行驶轨迹进行的可视化的查询和展示分析，发现运行特征和驾驶规律，进而能够对出租车的管理等交通领域的应用提供便利支撑。


**项目展示**：
![Image text](1.geoserver/all.png)
![Image text](1.geoserver/index1.png)
![Image text](1.geoserver/track-1.png)
![Image text](1.geoserver/track-2.png)
![Image text](1.geoserver/track-3.png)
![Image text](1.geoserver/list.png)
![Image text](1.geoserver/search.png)
![Image text](1.geoserver/taxi.png)




## 基于ChatGPT的医生病案助手
**项目信息**：参加学院竞赛的小项目，2023年2月——2023年6月，作者。


**简要介绍**：通过调用 ChatGPT-3.5Turbo&4的api ，结合llama-index库，使用Gradio框架，构建本地知识库问答系统。优化 prompt，专精于中医方面，主要投喂盆腔炎的相关文档，再结合语音文字互转等，达到音频输入输出的目的，医生可以编辑生成文本并可以保存为病案，进行导出的操作。（后续考虑经济原因，用本地部署的ChatGLM-6B替代了ChatGPT）。


**项目展示**：
![Image text](2.chatgpt/index.png)
![Image text](2.chatgpt/audio.png)
![Image text](2.chatgpt/chatbot.png)





## 谷粒商城
**项目信息**：学习尚硅谷springboot课程，2023年7月——2023年9月，作者。


**简要介绍**：商城系统基于SpringBoot和Vue，还使用了SpringCloud、MyBatis-Plus、Redis、nginx等，微服务架构，分布式事务，前后端分离等。


**项目展示**：


![Image text](3.guli/guli.png)





## 用于位置预测的时空轨迹数据研究
**项目信息**：论文研究，2023年3月——2023年12月，协助处理大量轨迹数据。


**简要介绍**：成都出租车轨迹数据集，约一个月，一万六千辆车，共十四亿行坐标数据，单个文件超过2G。原始数据未按时间排序且包含噪点。经过排序、筛选、更换时间戳，使用开源的TPTK清洗数据，去除噪点和异常时间空间轨迹。然后通过OpenStreetMap路网进行开源的FastMapMatching路网匹配，得到最后的输入数据，结果显示上图效果良好。


**过程展示**：


![Image text](4.traj/deal1.png)
![Image text](4.traj/deal2.png)






## 路网约束条件下基于图神经网络的轨迹预测方法研究与实现
**项目信息**：硕士毕业设计，2023年9月——至今 ，作者。


**简要介绍**：基于路网motif的图神经网络轨迹预测系统，该项目依托于真实路网中的motif，对路网的高阶结构属性进行挖掘，提出了路网中motif的发现算法，通过路网motif的邻接矩阵，应用于交通流量图的构建过程，再通过图注意力网络对交通流量图和个体轨迹图进行特征学习，以达到更好的预测效果。结果显示，该系统预测能力卓越。


**框架图**：

论文成果已录用，等待见刊中...
