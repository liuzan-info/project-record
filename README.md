# project-record
Record project plan and relative papers

## Plan
- 第一阶段
  预测ADR
- 第二阶段
  引入drug靶蛋白、drug参与通路，探究药物造成ADR的机制

## relative paper
- ADR机制复杂，仅通过drug-ADR网络便可以预测ADR，引入drug信息对预测的准确度没有提升。
- Lin, Jiao; Kuang, Qifan; Li, Yizhou; Zhang, Yongqing; Sun, Jing; Ding, Zhanling; Li, Menglong (2013). Prediction of adverse drug reactions by a network based external link prediction method. Analytical Methods, 5(21), 6120–. doi:10.1039/c3ay41290c https://pubs.rsc.org/en/content/articlelanding/2013/ay/c3ay41290c/unauth

有对以往方法的比较，比较全面 A knowledge graph embedding based approach to predict the adverse drug reactions using a deep neural network https://www.sciencedirect.com/science/article/pii/S1532046422001381 `无code`

综述 
- 2019
Duc Anh Nguyen, Canh Hao Nguyen, Hiroshi Mamitsuka, A survey on adverse drug reaction studies: data, tasks and machine learning methods, Briefings in Bioinformatics, Volume 22, Issue 1, January 2021, Pages 164–177, https://doi.org/10.1093/bib/bbz140 `code` https://github.com/anhnda/ADRPModels



待看
https://link.springer.com/article/10.1007/s40264-022-01190-3
https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-021-01402-3
https://link.springer.com/article/10.1007/s10489-022-03721-y
https://aacrjournals.org/cancerres/article/82/12_Supplement/6312/699548
https://aacrjournals.org/cancerres/article/82/12_Supplement/5063/700991
https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/abs/10.1002/jat.4354
期刊好像不是SCI https://www.degruyter.com/document/doi/10.1515/jib-2022-0007/html
https://link.springer.com/chapter/10.1007/978-3-030-95895-4_6
https://ieeexplore.ieee.org/abstract/document/9772327
https://www.mdpi.com/1420-3049/27/9/3004
https://academic.oup.com/bib/article-abstract/23/3/bbac134/6576451
https://www.nature.com/articles/s41598-022-10887-5
http://eprints.lums.ac.ir/3751/
https://academic.oup.com/bib/article-abstract/23/3/bbac140/6572660
https://pubs.acs.org/doi/abs/10.1021/acs.jcim.2c00765
https://link.springer.com/article/10.1007/s00500-022-06951-x
https://link.springer.com/chapter/10.1007/978-981-16-9573-5_37
https://www.mdpi.com/2227-9032/10/4/618
https://ieeexplore.ieee.org/abstract/document/9784963
https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00589-5
https://link.springer.com/article/10.1186/s12859-022-04610-4
https://ieeexplore.ieee.org/abstract/document/9726867
目前整理的大概是2022年以来的





## 其他方向
### 药物推荐
Dual Attention and Patient Similarity Network for drug recommendation https://academic.oup.com/bioinformatics/article/39/1/btad003/6972773`code`https://github.com/andylun96/DAPSNet
### ADR相关蛋白预测
Large-scale prediction of adverse drug reactions-related proteins with network embedding https://academic.oup.com/bioinformatics/article/39/1/btac843/6965019#390617152`code`https://github.com/rupinas/LAPINE
### 药物联用ADR预测
readme文档完善，数据已经整理为txt格式，适合学习 DAEM: Deep attributed embedding based multi-task learning for predicting adverse drug–drug interaction https://www.sciencedirect.com/science/article/pii/S0957417422023302 `code` https://github.com/AdverseDDI/

DeepPSE: Prediction of polypharmacy side effects by fusing deep representation of drug pairs and attention mechanism https://www.sciencedirect.com/science/article/pii/S0010482522007119  `code` https://github.com/ShenggengLin/

代码结构规范，值得学习 M2GCN: multi-modal graph convolutional network for modeling polypharmacy side effects https://link.springer.com/article/10.1007/s10489-022-03839-z  `code` https://github.com/farkguidao/M2GCN

解决了在graph中新药难以引入的问题  SimVec: predicting polypharmacy side effects for new drugs https://jcheminf.biomedcentral.com/articles/10.1186/s13321-022-00632-5 `code`  https://github.com/jbr-ai-labs/simvec
### 药物联用药效预测
NMI 代码齐全、数据完备 https://www.nature.com/articles/s42256-022-00541-0#code-availability `code` https://codeocean.com/capsule/1993810/tree/v1

将联用不良反应的预测作为辅助任务，进行多任务学习来改进联用药效的预测 Improving therapeutic synergy score predictions with adverse effects using multi-task heterogeneous network learning https://academic.oup.com/bib/article/24/1/bbac564/6958504?login=false `code`https://github.com/arantir123/HNEMA

Multi-way relation-enhanced hypergraph representation learning for anti-cancer drug synergy prediction https://academic.oup.com/bioinformatics/article-abstract/38/20/4782/6674505 `code` https://github.com/liuxuan666/HypergraphSynergy
### 可解释性机器学习
jupyter格式，完整的数据分析流程，适合入门 XML-CIMT: Explainable Machine Learning (XML) Model for Predicting Chemical-Induced Mitochondrial Toxicity https://www.mdpi.com/1422-0067/23/24/15655 `code`https://github.com/Rehman1995/XML-CIMT
### 药物重定位
基于网络方法的综述 https://www.ingentaconnect.com/content/ben/cdrr/2022/00000014/00000002/art00005