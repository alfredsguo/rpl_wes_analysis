文件列表：
1. cnv_all.xls                            所有样本CNV结果表
2. cnv_summary.xls                        所有样本CNV结果统计表
3. cnv_acmg_deletion.xls                  Deletion有害性筛选ACMG评级统计表
4. cnv_acmg_duplication.xls               Duplication有害性筛选ACMG评级统计表
5. */*.cnv_annot.xlsx                     单个样本CNV结果及注释表
6. */00.cnv_summary_sample1.xls           单个样本有害性筛选ACMG评级统计表
7. */01.cnv_list_*.xls                    评级结果为VUS，LP, P的CNV基本信息
8. */02.cnv_decipher_*.xls                评级结果为VUS，LP, P的CNV注释信息
9. */plot/*_chr*.png                      CNV在每条染色体的分布情况图
10. */plot/*_chr*-*-*_*_CNV.png           评级结果为VUS，LP, P的CNV可视化展示图


1. cnv_all.xls:
(1) Sample：样本名
(2) CNV：CNV信息
(3) Type：CNV类型
(4) Chr：CNV染色体位置
(5) Start：CNV起始位置
(6) End：CNV终止位置
(7) Size：CNV长度
(8) CopyRatio：CNV拷贝数比例

2. cnv_summary.xls:
(1) Sample：样本名
(2) Total CNV：总的CNV数
(3) Deletion：缺失类型的CNV数
(4) Duplication：重复类型的CNV数

3. cnv_acmg_deletion.xls, 4. cnv_acmg_duplication.xls, 6. */00.cnv_summary_sample1.xls:
(1) Sample：样品名
(2) Total：总的变异位点数目
(3) Pathogenic：分类为致病的变异位点数目
(4) Likely pathogenic：分类为疑似致病的变异位点数目
(5) VUS：分类为意义未明的变异位点数目
(6) Benign：分类为良性的变异位点数目

5. */*.cnv_annot.xlsx:
(1) Sample：样本名
(2) cnv：CNV的染色体:起始位置-终止位置_CNV 类型
(3) Type：CNV类型。Duplication：扩增，Deletion：缺失；
(4) Chr：CNV染色体位置
(5) Start：CNV起始位置
(6) End：CNV终止位置
(7) Size：CNV片段大小
(8) CopyRatio：CNV拷贝数比例
(9) 致病性分类：Likely Benign，VUS，Likely Pathogenic，Pathogenic
(10) summary：CNV注释的综合性描述
(11) cytoband：染色体区带信息
(12) syndrome：CNV覆盖的OMIM数据库综合征信息，包含覆盖区域及综合征表型等
(13) gene：CNV覆盖的基因名称（包含protein gene和其他基因）
(14) gene_dosage：CNV覆盖的蛋白编码基因CDS区域比例
(15) omim_gene：CNV覆盖的OMIM数据库基因名称及区域比例
(16) ClinGen：ClinGen基因的经典转录本与 CNV 有 overlap 的，关于ClinGen数据库中haploinsufficiency_score和triplosensitivity_score的剂量敏感性的信息
(17) paper：CNV相关的文献信息
(18) patient：CNV相关的各种数据库的患者信息
(19) support：CNV在各种来源数据库的携带人群信息

7. */01.cnv_list_*.xls:
(1) Sample: 样品名
(2) Type: CNV类型。Duplication：扩增，Deletion：缺失；
(3) Chr：染色体号
(4) Start: CNV起始位置
(5) End: CNV终止位置
(6) Size: CNV片段大小
(7) CopyRatio: 拷贝数比例
(7) CytoBand: 染色体区带信息
(8) ClinilcalLevel: 临床分类
(10) Disease：相关疾病
(11) KeyGenes：关键基因

8. */02.cnv_decipher_*.xls:
(1) Sample: 样品名
(2) cnv: CNV的染色体:起始位置-终止位置_CNV 类型
(3) CopyRatio: 拷贝数比例
(4) CytoBand: 染色体区带信息
(5) Size: CNV片段大小
(6) ClinilcalLevel: 临床分类
(7) summary: CNV注释的综合性描述

9. */plot/*_chr*.png
CNV在每条染色体的分布情况图：横坐标表示染色体位置，纵坐标表示拷贝数。

10. */plot/*_chr*-*-*_*_CNV.png
评级结果为VUS，LP, P的CNV可视化展示图：横坐标表示CNV位置信息，纵坐标表示CNV类型。图中展示CNV覆盖的基因名称和CNV片段大小。
