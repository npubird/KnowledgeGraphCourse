# A systematic course about knowledge graph for graduate students, interested researchers and engineers. 
东南大学《知识图谱》研究生课程  
时间：2019年春季（2月下旬\~5月中旬）  
每周五下午2:00\~4:30  
地点：东南大学九龙湖校区, 纪忠楼Y205


# 课程内容
## 第1讲 知识图谱概论 （2019-3-1,2019-3-8）
1.1 知识图谱起源和发展  
1.2 知识图谱 VS 深度学习  
1.3 知识图谱 VS 关系数据库 VS 传统专家库  
1.4 知识图谱本质和核心价值  
1.5 知识图谱技术体系    
1.6 典型知识图谱  
1.7 知识图谱应用场景  
**课件下载**:[partA](https://github.com/npubird/KnowledgeGraphCourse/blob/master/pub-1知识图谱概论A.pdf)   [partB](https://github.com/npubird/KnowledgeGraphCourse/blob/master/pub-1知识图谱概论B.pdf)   [partC](https://github.com/npubird/KnowledgeGraphCourse/blob/master/pub-1知识图谱概论C.pdf)
## 第2讲 知识表示 (2019-3-15)  
2.1 知识表示概念  
2.2 知识表示方法  
+ 语义网络  
+ 产生式系统  
+ 框架系统  
+ 概念图  
+ 形式化概念分析  
+ 描述逻辑  
+ 本体  
+ 本体语言  
+ 统计表示学习   
**课件下载**:[partA](https://github.com/npubird/KnowledgeGraphCourse/blob/master/pub-2知识表示.pdf)

## 第3讲 知识建模 （2019-3-15，2019-3-22）
3.1 本体  
3.2 知识建模方法 
+ 本体工程   
+ 本体学习  
+ 知识建模工具  
+ 知识建模实践  

## 第4讲 知识抽取基础:问题和方法（2019-3-22）
4.1 知识抽取场景  
4.2 知识抽取挑战  
4.3 面向结构化数据的知识抽取  
4.4 面向半结构化数据的知识抽取  
4.5 面向非机构化数据的知识抽取  


# 附录A：经典文献选读

## 知识图谱构建
1. Dong X, Gabrilovich E, Heitz G, et al. [Knowledge vault: A web-scale approach to probabilistic knowledge fusion](https://ai.google/research/pubs/pub45634.pdf). KDD2014: 601-610.  
1. Suchanek F M, Kasneci G, Weikum G. [Yago: a core of semantic knowledge](http://www2007.wwwconference.org/papers/paper391.pdf). WWW2007: 697-706.  
1. Hoffart J, Suchanek F M, Berberich K, et al. [YAGO2: A spatially and temporally enhanced knowledge base from Wikipedia](https://people.mpi-inf.mpg.de/~kberberi/publications/2013-ai.pdf). Artificial Intelligence, 2013, 194: 28-61.  
1. Navigli R, Ponzetto S P. [BabelNet: The automatic construction, evaluation and application of a wide-coverage multilingual semantic network](http://web.informatik.uni-mannheim.de/ponzetto/pubs/navigli12b.pdf). Artificial Intelligence, 2012, 193: 217-250.  
1. Auer S, Bizer C, Kobilarov G, et al. [Dbpedia: A nucleus for a web of open data](http://editthis.info/images/swim/d/d8/Dbpedia_-_open_data.pdf). ISWC2007: 722-735.  
1. Mitchell T, Cohen W, Hruschka E, et al. [Never-ending learning](https://dl.acm.org/ft_gateway.cfm?id=3191513&type=pdf). Communications of the ACM, 2018, 61(5): 103-115. [earlier work](https://www.aaai.org/ocs/index.php/AAAI/AAAI10/paper/viewFile/1879/2201)  

## 知识表示和建模
1. Sowa J F. Knowledge representation: logical, philosophical, and computational foundations. 1999.  
2. Noy N F, McGuinness D L. [Ontology Development 101: A Guide to Creating Your First Ontology](http://ftp.ksl.stanford.edu/people/dlm/papers/ontology-tutorial-noy-mcguinness.pdf). [another version](http://www.corais.org/sites/default/files/ontology_development_101_aguide_to_creating_your_first_ontology.pdf) 

## 知识抽取
* **信息抽取**
1. Etzioni O, Cafarella M, Downey D, et al. [Web-scale information extraction in knowitall:(preliminary results)](http://www2004.org/proceedings/docs/1p100.pdf).WWW2004: 100-110.  
2. Banko M, Cafarella M J, Soderland S, et al. [Open information extraction from the web](https://www.aaai.org/Papers/IJCAI/2007/IJCAI07-429.pdf). IJCAI2007, 7: 2670-2676.  
3. Sarawagi S. [Information extraction](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.442.2007&rep=rep1&type=pdf). Foundations and Trends® in Databases, 2008, 1(3): 261-377.  
3. Fader A, Soderland S, Etzioni O. [Identifying relations for open information extraction](https://aclanthology.info/pdf/D/D11/D11-1142.pdf). EMNLP2011: 1535-1545.  
4. Fan J, Kalyanpur A, Gondek D C, et al. [Automatic knowledge extraction from documents](http://brenocon.com/watson_special_issue/05%20automatic%20knowledge%20extration.pdf). IBM Journal of Research and Development, 2012, 56(3.4): 5: 1-5: 10.  
5. Hearst M A. [Automatic acquisition of hyponyms from large text corpora](http://www.aclweb.org/anthology/C92-2082). ACL1992: 539-545.  

* **实体识别** 

* **关系抽取**  
1. Wang C, Kalyanpur A, Fan J, et al. [Relation extraction and scoring in DeepQA](http://brenocon.com/watson_special_issue/09%20relation%20extraction%20and%20scoring.pdf). IBM Journal of Research and Development, 2012, 56(3.4): 9: 1-9: 12.  
2. Han X, Zhu H, Yu P, et al. [FewRel: A Large-Scale Supervised Few-Shot Relation Classification Dataset with State-of-the-Art Evaluation](https://arxiv.org/pdf/1810.10147). EMNLP2018.  

* **事件抽取**  


## 知识融合  
1. Shvaiko P, Euzenat J. [Ontology matching: state of the art and future challenges](https://hal.inria.fr/hal-00917910/document). IEEE Transactions on knowledge and data engineering, 2013, 25(1): 158-176.  
2. Noy N F, Musen M A. [Algorithm and tool for automated ontology merging and alignment](https://www.aaai.org/Papers/AAAI/2000/AAAI00-069.pdf). AAAI2000.  
3. Do H H, Rahm E. [COMA: a system for flexible combination of schema matching approaches](http://www.vldb.org/conf/2002/S17P03.pdf).VLDB2002: 610-621.  
4. Doan A H, Madhavan J, Domingos P, et al. [Learning to map between ontologies on the semantic web](http://secs.ceas.uc.edu/~mazlack/CS716.f2006/Semantic.Web.Ontology.Papers/Doan.02.pdf). WWW2002: 662-673.  
5. Ehrig M, Staab S. [QOM–quick ontology mapping](http://www.scs.carleton.ca/~armyunis/knowledge-managment/papers/QOM-Quick%20Ontology%20Mapping.pdf). ISWC2004: 683-697.  
6. Qu Y, Hu W, Cheng G. [Constructing virtual documents for ontology matching](https://www.researchgate.net/profile/Yuzhong_Qu/publication/221022499_Lecture_Notes_in_Computer_Science/links/5483bb9f0cf25dbd59eb0ff0/Lecture-Notes-in-Computer-Science.pdf). WWW2006: 23-31.  
7. Li J, Tang J, Li Y, et al. [RiMOM: A dynamic multistrategy ontology alignment framework](https://ieeexplore.ieee.org/abstract/document/4633358/). IEEE Transactions on Knowledge and data Engineering, 2009, 21(8): 1218-1232.  
8. Mao M, Peng Y, Spring M. [An adaptive ontology mapping approach with neural network based constraint satisfaction](http://gesispanel.gesis.org/preprints/index.php/ps/article/download/209/368). Journal of Web Semantics, 2010, 8(1): 14-25.  
9. Hu W, Qu Y, Cheng G. [Matching large ontologies: A divide-and-conquer approach](http://dit.unitn.it/~p2p/RelatedWork/Matching/MatchingLargeOntologies.pdf). Data & Knowledge Engineering, 2008, 67(1): 140-160.  
10. Papadakis G, Ioannou E, Palpanas T, et al. [A blocking framework for entity resolution in highly heterogeneous information spaces](http://disi.unitn.it/~themis/publications/erframework-tr12.pdf). IEEE Transactions on Knowledge and Data Engineering, 2013, 25(12): 2665-2682.  
11. Wang P, Zhou Y, Xu B. [Matching large ontologies based on reduction anchors](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI11/paper/download/3145/3697). Twenty-Second International Joint Conference on Artificial Intelligence. 2011.  
12. Niu X, Rong S, Wang H, et al. [An effective rule miner for instance matching in a web of data](http://xingniu.org/pub/ruleminer_cikm12.pdf). CIKM2012: 1085-1094.  
13. Papadakis G, Ioannou E, Palpanas T, et al. [A blocking framework for entity resolution in highly heterogeneous information spaces](http://disi.unitn.it/~themis/publications/erframework-tr12.pdf). IEEE Transactions on Knowledge and Data Engineering, 2013, 25(12): 2665-2682.  
14. Li J, Wang Z, Zhang X, et al. [Large scale instance matching via multiple indexes and candidate selection](http://disi.unitn.it/~p2p/RelatedWork/Matching/KBS13-Li-et-al-large-instance.pdf). Knowledge-Based Systems, 2013, 50: 112-120.  
15. Hu W, Chen J, Qu Y. [A self-training approach for resolving object coreference on the semantic web](http://dit.unitn.it/~p2p/RelatedWork/Matching/A%20self-training%20approach_Hu_www11.pdf). WWW2011: 87-96.  
16. Tang J, Fong A C M, Wang B, et al. [A unified probabilistic framework for name disambiguation in digital library](http://keg.cs.tsinghua.edu.cn/jietang/publications/TKDE12-Tang-Name-Disambiguation.pdf). IEEE Transactions on Knowledge and Data Engineering, 2012, 24(6): 975-987.  
17. Zhang Y, Zhang F, Yao P, et al. [Name Disambiguation in AMiner: Clustering, Maintenance, and Human in the Loop](http://keg.cs.tsinghua.edu.cn/jietang/publications/kdd18_yutao-AMiner-Name-Disambiguation.pdf). KDD2018: 1002-1011.  
18. Ngomo A C N, Auer S. [LIMES—a time-efficient approach for large-scale link discovery on the web of data](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI11/paper/viewFile/3125/3692). IJCAI2011.  

 


## 知识图谱嵌入  
1. Wang Q, Mao Z, Wang B, et al. [Knowledge graph embedding: A survey of approaches and applications](http://download.xuebalib.com/3at6CEQL3eBi.pdf). IEEE Transactions on Knowledge and Data Engineering, 2017, 29(12): 2724-2743.  
2. Bordes A, Usunier N, Garcia-Duran A, et al. [Translating embeddings for modeling multi-relational data](http://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data.pdf). NIPS2013: 2787-2795.  
3. Lin Y, Liu Z, Sun M, et al. [Learning entity and relation embeddings for knowledge graph completion](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/viewFile/9571/9523). AAAI2015.  
4. Wang Z, Zhang J, Feng J, et al. [Knowledge graph embedding by translating on hyperplanes](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/viewFile/8531/8546). AAAI2014.  
5. Wang Z, Zhang J, Feng J, et al. [Knowledge graph and text jointly embedding](http://www.aclweb.org/anthology/D14-1167). EMNLP2014: 1591-1601.  
6. Ji G, He S, Xu L, et al. [Knowledge graph embedding via dynamic mapping matrix](http://www.aclweb.org/anthology/P15-1067). ACL2015: 687-696.  
  


## 知识推理/知识挖掘  
1. Nickel M, Tresp V, Kriegel H P. [A Three-Way Model for Collective Learning on Multi-Relational Data](http://www.cip.ifi.lmu.de/~nickel/data/slides-icml2011.pdf). ICML2011: 809-816.  
2. Socher R, Chen D, Manning C D, et al. [Reasoning with neural tensor networks for knowledge base completion](https://papers.nips.cc/paper/5028-reasoning-with-neural-tensor-networks-for-knowledge-base-completion.pdf). NIPS2013: 926-934.  
3. Lao N, Cohen W W. [Relational retrieval using a combination of path-constrained random walks](https://link.springer.com/content/pdf/10.1007/s10994-010-5205-8.pdf). Machine learning, 2010, 81(1): 53-67.  
4. Lin Y, Liu Z, Luan H, et al. [Modeling relation paths for representation learning of knowledge bases](http://www.emnlp2015.org/proceedings/EMNLP/pdf/EMNLP082.pdf). EMNLP2015.  
5. Gardner M, Talukdar P, Krishnamurthy J, et al. [Incorporating vector space similarity in random walk inference over knowledge bases](http://www.aclweb.org/anthology/D14-1044). EMNLP2014: 397-406.  
6. Xiong W, Hoang T, Wang W Y. [DeepPath: A Reinforcement Learning Method for Knowledge Graph Reasoning](http://www.aclweb.org/anthology/D17-1060). EMNLP2017:564-573.  

## 知识存储/知识查询
1. Bornea M A, Dolby J, Kementsietsidis A, et al. [Building an efficient RDF store over a relational database](https://www.researchgate.net/profile/Patrick_Dantressangle/publication/262162010_Building_an_efficient_RDF_store_over_a_relational_database/links/54f718680cf210398e9184bc/Building-an-efficient-RDF-store-over-a-relational-database.pdf). SIGMOD2013: 121-132.  
2. Huang J, Abadi D J, Ren K. [Scalable SPARQL querying of large RDF graphs](http://www.cs.umd.edu/~abadi/papers/sw-graph-scale.pdf). Proceedings of the VLDB Endowment, 2011, 4(11): 1123-1134.  
3. Zou L, Özsu M T, Chen L, et al. [gStore: a graph-based SPARQL query engine](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.386.7427&rep=rep1&type=pdf). The VLDB Journal—The International Journal on Very Large Data Bases, 2014, 23(4): 565-590.  
  
## 人机交互  
1. Ferrucci D A. [Introduction to “this is watson”](https://ieeexplore.ieee.org/abstract/document/6177724/). IBM Journal of Research and Development, 2012, 56(3.4): 1: 1-1: 15.  
2. Lally A, Prager J M, McCord M C, et al. [Question analysis: How Watson reads a clue](http://www.patwardhans.net/papers/LallyEtAl12.pdf). IBM Journal of Research and Development, 2012, 56(3.4): 2: 1-2: 14.  
3. Zhou H, Young T, Huang M, et al. [Commonsense Knowledge Aware Conversation Generation with Graph Attention](https://www.ijcai.org/proceedings/2018/0643.pdf). IJCAI. 2018: 4623-4629.  

# 附录B：最新进展论文选读(近1年内)
1. Bhatia S, Dwivedi P, Kaur A. That’s Interesting, Tell Me More! [Finding Descriptive Support Passages for Knowledge Graph Relationships](http://sumitbhatia.net/papers/iswc18.pdf). ISWC2018: 250-267. (Best Paper)  
2. Soulet A, Giacometti A, Markhoff B, et al. [Representativeness of Knowledge Bases with the Generalized Benford’s Law](https://a3nm.net/work/seminar/slides/20181115-soulet.pdf). ISWC2018: 374-390.  
3. Wang M, Wang R, Liu J, et al. [Towards Empty Answers in SPARQL: Approximating Querying with RDF Embedding](https://link.springer.com/chapter/10.1007/978-3-030-00671-6_30). ISWC2018: 513-529.  
4. Salas J, Hogan A. [Canonicalisation of monotone SPARQL queries](https://link.springer.com/chapter/10.1007/978-3-030-00671-6_35). ISWC2018: 600-616. (Best Student Paper)  
5. Pertsas V, Constantopoulos P, Androutsopoulos I. [Ontology Driven Extraction of Research Processes](https://pages.cs.aueb.gr/ipl/nlp/pubs/iswc2018.pdf). ISWC2018:162-178.  
6. Saeedi A, Peukert E, Rahm E. [Using link features for entity clustering in knowledge graphs](https://dbs.uni-leipzig.de/file/eswc_0.pdf). ESWC2018: 576-592. (Best Paper)  
7. Schlichtkrull M, Kipf T N, Bloem P, et al. [Modeling relational data with graph convolutional networks](https://arxiv.org/pdf/1703.06103). ESWC2018: 593-607. (Best Student Paper)  
8. Hamid Z, Giulio N, Jens L. Formal Query Generation for Question Answering over Knowledge Bases. ESWC2018:714-728.  
9. Zhou L, Gao J, Li D, et al. [The Design and Implementation of XiaoIce, an Empathetic Social Chatbot](https://arxiv.org/pdf/1812.08989). arXiv preprint arXiv:1812.08989, 2018.  
10. Dasgupta S S, Ray S N, Talukdar P. [HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding](http://www.aclweb.org/anthology/D18-1225). EMNLP2018: 2001-2011.  
11. Dubey M, Banerjee D, Chaudhuri D, et al. [EARL: Joint entity and relation linking for question answering over knowledge graphs](https://arxiv.org/pdf/1801.03825)ISWC2018: 108-126.  
12. Chen M, Tian Y, Chang K W, et al. [Co-training embeddings of knowledge graphs and entity descriptions for cross-lingual entity alignment](http://yellowstone.cs.ucla.edu/~muhao/slides/kdcoe.pdf). IJCAI2018.  
13. Janke D, Staab S, Thimm M. [Impact analysis of data placement strategies on query efforts in distributed rdf stores](http://mail.websemanticsjournal.org/preprints/index.php/ps/article/view/516/533). Journal of Web Semantics, 2018, 50: 21-48.  




