# NERPapers
Worth-reading and awesome papers on Named Entity Recognition.

Suggestions about adding papers, repositories and other resources are welcomed!

*Since I am Chinese, I mainly focus on Chinese resources. Welcome to recommend excellent resources in English or other languages!*

值得一读的命名实体识别相关资源集合。

欢迎新增论文、代码仓库与其他资源等建议！

## Papers
- **Conditional Random Fields: Probabilistic Models for Segmenting and Labeling Sequence Data**. *John Lafferty, Andrew McCallum, Fernando C.N. Pereira*. (ICML 2001) [[paper]](https://repository.upenn.edu/cgi/viewcontent.cgi?article=1162&context=cis_papers) - ***CRF***
- **Chinese NER Using Lattice LSTM**. *Yue Zhang, Jie Yang*. (ACL 2018) [[paper]](https://arxiv.org/abs/1805.02023)
- **Hierarchically-Refined Label Attention Network for Sequence Labeling**. *Leyang Cui, Yue Zhang*. (EMNLP 2019) [[paper]](https://www.aclweb.org/anthology/D19-1422/)[[code]](https://github.com/Nealcly/BiLSTM-LAN) - ***LAN***
- **A Unified MRC Framework for Named Entity Recognition**. *Xiaoya Li, Jingrong Feng, Yuxian Meng, Qinghong Han, Fei Wu, Jiwei Li*. (ACL 2019) [[paper]](https://arxiv.org/abs/1910.11476)
- **TENER: Adapting Transformer Encoder for Named Entity Recognition**. *Hang Yan, Bocao Deng, Xiaonan Li, Xipeng Qiu*. (CoRR 2019) [[paper]](https://arxiv.org/abs/1911.04474)
- **TriggerNER: Learning with Entity Triggers as Explanations for Named Entity Recognition**. *Bill Yuchen Lin, Dong-Ho Lee, Ming Shen, Ryan Moreno, Xiao Huang, Prashant Shiralkar, Xiang Ren*. (ACL 2020) [[paper]](https://arxiv.org/abs/2004.07493)[[code]](https://github.com/INK-USC/TriggerNER)
- **FLAT: Chinese NER Using Flat-Lattice Transformer**. *Xiaonan Li, Hang Yan, Xipeng Qiu, Xuanjing Huang*. (ACL 2020) [[paper]](https://arxiv.org/abs/2004.11795)[[code]](https://github.com/LeeSureman/Flat-Lattice-Transformer)
- **Simplify the Usage of Lexicon in Chinese NER**. *Ruotian Ma, Minlong Peng, Qi Zhang, Zhongyu Wei, Xuanjing Huang*. [[paper]](https://www.aclweb.org/anthology/2020.acl-main.528/)[[code]](https://github.com/v-mipeng/LexiconAugmentedNER)
- **A Novel Cascade Binary Tagging Framework for Relational Triple Extraction**. *Zhepei Wei, Jianlin Su, Yue Wang, Yuan Tian, Yi Chang*. (ACL 2020) [[paper]]()[[code]](https://github.com/weizhepei/CasRel) - ***CasRel***
- **Lex-BERT: Enhancing BERT based NER with lexicons**. *Wei Zhu, Daniel Cheung*. (ICLR 2021) [[paper]](https://arxiv.org/abs/2101.00396)

## Survay & Tutorial
- **Few-Shot Named Entity Recognition: A Comprehensive Study**. *Jiaxin Huang, Chunyuan Li, Krishan Subudhi, Damien Jose, Shobana Balakrishnan, Weizhu Chen, Baolin Peng, Jianfeng Gao, Jiawei Han*. (CoRR 2020) [[paper]](https://arxiv.org/abs/2012.14978)

## Repositories & Toolkits
- [CLUEbenchmark / CLUENER2020](https://github.com/CLUEbenchmark/CLUENER2020) - Fine-grained NER for Chinese based on pretrianed language model
  - **CLUENER2020: Fine-grained Name Entity Recognition for Chinese**. *Liang Xu, Yu tong, Qianqian Dong, Yixuan Liao, Cong Yu, Yin Tian, Weitang Liu, Lu Li, Caiquan Liu, Xuanwei Zhang*. (CoRR 2020) [[paper]](https://arxiv.org/abs/2001.04351)
- [dsindex / ntagger](https://github.com/dsindex/ntagger) - reference pytorch code for named entity tagging
- [jiesutd / NCRF++](https://github.com/jiesutd/NCRFpp) - An open-source neural sequence labeling toolkit
  - **NCRF++: An Open-source Neural Sequence Labeling Toolkit**. *Jie Yang, Yue Zhang*. (ACL 2018) [[paper]](https://www.aclweb.org/anthology/P18-4013/)
- [lingluodlut / BioNER-Progress](https://github.com/lingluodlut/BioNER-Progress) - Tracking the progress in biomedical NER
- [lonePatient/BERT-NER-Pytorch](https://github.com/lonePatient/BERT-NER-Pytorch) - Chinese NER using BERT
- [loujie0822 / DeepIE](https://github.com/loujie0822/DeepIE) - Deep Learning for Information Extraction
- [percent4 / people_relation_extract](https://github.com/percent4/people_relation_extract) - 结合BERT+GRU+ATT模型，对自己收集的人物关系数据进行模型训练，用于人物关系抽取
- [scrapinghub / python-crfsuite](https://github.com/scrapinghub/python-crfsuite) - A python binding for crfsuite
- [ShulinCao / OpenNRE-PyTorch](https://github.com/ShulinCao/OpenNRE-PyTorch) - 上一项目的PyTorch版本
- [taku910 / CRF++](https://taku910.github.io/crfpp/) - A simple, customizable, and open source implementation of Conditional Random Fields (CRFs) for segmenting/labeling sequential data
- [THUNLP / Bert2Tag](https://github.com/thunlp/Bert2Tag) - Bert base sequence tagging on OpenKP
- [THUNLP / OpenNRE](https://github.com/thunlp/OpenNRE)

## Datasets
- [OpenKP](http://www.msmarco.org/leaders.aspx) - MS MARCO DataSets

## Blog Posts
- [Elesdspline / 【ACL2020论文尝鲜】如何以低成本的数据构建高效NER模型 TriggerNER？](https://zhuanlan.zhihu.com/p/145974989)
- [虎哥 / 手撕BiLSTM-CRF](https://zhuanlan.zhihu.com/p/97676647)
- [Jay Lou / 中文NER的正确打开方式: 词汇增强方法总结 (从Lattice LSTM到FLAT)](https://zhuanlan.zhihu.com/p/142615620)
- [Jay Lou / 工业界如何解决NER问题？12个trick，与你分享～](https://zhuanlan.zhihu.com/p/152463745)
- [Jay Lou / 工业界求解NER问题的12条黄金法则](https://mp.weixin.qq.com/s/MQRrEIJaFToIVLbnuKQZnw)
- [Jay Lou / 陈丹琦“简单到令人沮丧”的屠榜之作：关系抽取新SOTA！](https://mp.weixin.qq.com/s/xwljKL3FjY-Nw-Zll4x3pQ)
- [Jay Lou / 打开你的脑洞：NER如何进行数据增强 ？](https://mp.weixin.qq.com/s/JfqH3Bsw1JeL6Eqt03r2Og)
- [Jay Lou / Lex-BERT：超越FLAT的中文NER模型？](https://mp.weixin.qq.com/s/zsNpZ7M6C4pUOhWg1Bdf3A)
- [美团 / 美团搜索中NER技术的探索与实践](https://tech.meituan.com/2020/07/23/ner-in-meituan-nlp.html)
- [邱震宇 / 中文NER任务实验小结报告——深入模型实现细节](https://zhuanlan.zhihu.com/p/103779616)
- [苏剑林 / 你的CRF层的学习率可能不够大](https://kexue.fm/archives/7196)
- [王岳王院长 / 流水的NLP铁打的NER：命名实体识别实践与探索](https://zhuanlan.zhihu.com/p/166496466)
- [张成蹊 / 浅谈嵌套命名实体识别（Nested NER）](https://mp.weixin.qq.com/s/iB-gaxIygWLjS1mKwKUGog)
- [AI自然语言处理与知识图谱 Elesdspline / 综述：关系抽取，挑战与机遇并存！](https://mp.weixin.qq.com/s/6_hBsjXjC6EyKHrxbfsf_Q)
