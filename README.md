# Deep-Learning-and-Common-Factors_IPCA

1.MIT lisence © Liu  Xiaoquan，Assistant Professor HKCHC 

2.本文件包括“深度学习与共同因子“研究论文的Python代码；

3.Python代码的运行环境为Anaconda的jupyter Lab；

4.数据链接：ACELIU0852/DeepLearningCommonFactor_DLvsIPCA     （数据为Hong Kong Chu Hai College向CSMAR公司采购，请遵守相关相关版权限制）

5.在论文研究中，我们对数据缺失值的处理，使用了排除法和均值填充法。在第一种方法下的数据观测值较少，在第二种情况下的数据观测值4-5亿个。论文初稿中使用观测值较少的数据集，在9月24日的论文提交稿和代码中实际使用4-5亿个观测值的数据集。论文中的描述若与本处的数据观测值数量存在差异的情况，主要原因在于此。在论文初稿中收益率观测值的标准化采用年化波动率的方式，本次更新的方式的标准化与所有特征变量的标准化方式一致，即原始观测值减去均值再除以标准差。该处理方式使得论文可以更好的与IPCA的benchmark模型进行对比。

6.作者在研究过程中使用3.6 TFLOPS的单GPU算力（大约为NVIDIA的RTX3050算力的一半），运行一次”论文代码.ipynb“的完整模型训练（包括稳健性检验的时间序列交叉验证）需要的计算时间介于2-3个小时之间。需要复刻论文代码的读者，请酌情考虑配置和算力的消耗时间情况。
