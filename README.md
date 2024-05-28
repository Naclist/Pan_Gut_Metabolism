# Pan Gut Metabolism
A test program for cross-feeding net within human gut using metagenomic data.
用来记录和存放基于宏基因组数据预测人类肠道菌群代谢网络和疾病相关性的储存库。

## 2024年5月28日
目前基于的队列：
|路径|队列分组|来源信息|
|---|---|---|
|/titan/reads/public/IBD/ncbi/reads|IBD1|https://www.ncbi.nlm.nih.gov/bioproject/PRJEB7949/|
|/titan/reads/HMP/feces/results|IBD2+HMP1+HMP2|HMP|
|/titan/reads/public/IBD/Spanish|IBD3|https://www.ncbi.nlm.nih.gov/bioproject/PRJEB1220|

合计1599个样本

目前跑完的样本合计648个

使用归一化后的RPKM进行群落结构分析
仅PCA：

<img src="https://github.com/Naclist/Pan_Gut_Metabolism/assets/88537949/efa23c10-3102-44ee-85e9-5adfa5fedcef" width="40%">

仅UMAP：

<img src="https://github.com/Naclist/Pan_Gut_Metabolism/assets/88537949/f347e43c-4694-482f-a041-e27fee9ee699" width="40%">

PCA+UMAP（单细胞常用技巧）：

<img src="https://github.com/Naclist/Pan_Gut_Metabolism/assets/88537949/5a4a680c-d7c4-41a3-8ba5-8922cb750bd0" width="40%">

同时使用随机森林进行预测：

<img src="https://github.com/Naclist/Pan_Gut_Metabolism/assets/88537949/b607ef74-1d31-4efd-8d23-123bea198946" width="40%">


结果尚可

