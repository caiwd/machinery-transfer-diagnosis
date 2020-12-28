# machinery-transfer-diagnosis
   
论文《融合机理模型与迁移学习的旋转机械故障诊断》验证案例的代码和数据，验证数据用到了美国凯斯西储大学轴承数据中心的故障数据（https://csegroups.case.edu/bearingdatacenter/pages/download-data-file ）
美国机械故障预防技术学会数据集（https://www.mfpt.org/fault-data-sets ）
GFK和TCA的核心函数来源于微软亚洲研究院的王晋东博士（https://github.com/jindongwang/transferlearning ）
引用记录已保留，如有侵权请联系我删除！个人邮箱：caiweidon@qq.com

各个文件夹的描述如下：

code: 包含论文实验数据的所有代码，运行BATCH_ALL.py将运行整个验证案例，包括数据划分，数据预处理，数据集生成，模型训练，提出方法和对比方法实验结果计算

data: 原始实验数据

model: 训练完成的模型文件

img：图片存储

log: 训练过程记录（.log）以及实验结果（.xlsx）


Python版本以及相关库版本如下：

python==3.7.9

pytorch==1.6.0+cu101, CUDA==10.1

scikit-learn==0.23.2

numpy==1.19.2+mkl

scipy==1.3.1

npTDMS==0.28.0

pandas==1.1.1

openpyxl==3.0.5

原始数据和训练完成的模型文件过大已将其上传至百度云: https://pan.baidu.com/s/1Iyw_B4X96mRaWuBWckQl9A 提取码: 1hyj
