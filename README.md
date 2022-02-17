# IE Dataset Zoo
Information extraction dataset zoo.

Contributed by **[Ningyu Zhang](https://person.zju.edu.cn/en/ningyu)**, **Shumin Deng**.


# Named Entity Recognition

| Dataset | #Type.|#Inst.|Feature|Source |Resource| Origin |  
|---------|------:|------:|-------:|-------:|-------:|----------| 
|    Few-NERD    |    66   | 188,200      | Few-shot| Wikipedia+Wikidata |  [url](http://47.92.96.190/dataset/fewnerd.tar.gz)     |  [url](https://ningding97.github.io/fewnerd/)  |   



# Relation Extraction

## Sentence-Level

| Dataset | #Rel.|#Inst.|Feature|Source |Resource| Origin |  
|---------|------:|------:|-------:|-------:|-------:|----------| 
|    Fewrel    |    100   | 44,800      | Supervised| Wikipedia+Wikidata |  [url](http://47.92.96.190/dataset/fewrel.tar.gz)     |  [url](http://www.zhuhao.me/fewrel/)        |      
|    TACRED    |    42   | 68,120    | Supervised |Newswire+web  |  -    |  [url](https://nlp.stanford.edu/projects/tacred/)        |  
|    Semeval     |   19    |   8,000    | Supervised|Web|  [url](http://47.92.96.190/dataset/semeval.tar.gz)     |  [url](https://www.kaggle.com/drtoshi/semeval2010-task-8-dataset#__sid=js0)        |    
|    Wikidata     |    352   | 495,883      | Distent-supervision|Wikipedia+Wikidata|  [url](http://47.92.96.190/dataset/wikidata.tar.gz)     |  [url](https://public.ukp.informatik.tu-darmstadt.de/UKP_Webpage/DATA/WikipediaWikidataDistantSupervisionAnnotations.v1.0.zip)        |    
|    NYT10(tsinghua)     |   53    |   522,043    |Distent-supervision | NYT+Freebase|  [url](http://47.92.96.190/dataset/nyt10.tar.gz)     |  [url](https://github.com/thunlp/OpenNRE/)        |    
|    NYT10-large(tsinghua)     |   53    |   570,088   |Distent-supervision | NYT+Freebase|  [url](http://47.92.96.190/dataset/nyt10-large.tar.gz)     |  [url](https://github.com/thunlp/HNRE)      
|    NYT-Wikidata     | 100      |  882,177   | Distent-supervision| NYT+Wikidata |   [url](http://47.92.96.190/dataset/NYT-Wikidata.tar.gz)     |  [url](https://github.com/thunlp/PathNRE)        |   
|    NYT10-29     |    29   | 70,339    | Distent-supervision| NYT+Freebase |   [url](http://47.92.96.190/dataset/NYT10.rar)     |  [url](https://github.com/truthless11/HRL-RE/tree/master/data)        |    
|    NYT11-12    |     12  |  62,648   | DS+supervised|  NYT+Freebase|   [url](http://47.92.96.190/dataset/NYT11.rar)     |  [url](https://github.com/truthless11/HRL-RE/tree/master/data)        |  
|   NYT-manual    |    24   | 235,982  |Distent-supervision| NYT+Freebase   |   [url](http://47.92.96.190/dataset/nyt-manual.tar.gz)     |  [url](https://github.com/INK-USC/USC-DS-RelationExtraction)        |  
|   NYT-Wiki(zju)    |  73    | 1,989,377 |Distent-supervision| NYT-Wikipedia-Wikidata   |   [url](http://47.92.96.190/dataset/nyt-wiki.zip)     |  [url](https://github.com/zxlzr/RAN/tree/master/data/NYT-Wiki)        |  
|    Wiki-KBP    |    19   |  23,784  |Distent-supervision| Wikipedia+KBP+Freebase  |   [url](http://47.92.96.190/dataset/kbp.tar.gz)     |  [url](https://github.com/INK-USC/USC-DS-RelationExtraction)        |    
|    PubMed-BioInfer     |   94  | 1,580 | Distent-supervision |  PubMed+NESH     | -   |  [url](https://github.com/INK-USC/USC-DS-RelationExtraction)        |    
|    WebNLG     |   14    | 75,325    |  Supervised | Web |   -   |  [url](https://drive.google.com/open?id=1zISxYa-8ROe2Zv8iRc82jY9QsQrfY1Vj)        |    
|    SKE     |    50   |   173,108  | Supervised | Web  |   [url](http://47.92.96.190/dataset/ske.tar.gz)     |  [url](https://ai.baidu.com/broad/download?dataset=sked)        |    
|    KBP37     |    37  |  15,916   | Supervised  | Web |   [url](http://47.92.96.190/dataset/ske.tar.gz)     |  [url](https://github.com/zhangdongxu/kbp37)        |  
|    T-REx    |   642   |  6.3M  | Distent-supervision   | Wikipedia+Wikidata |  -   |  [url](https://hadyelsahar.github.io/t-rex/)        |  
|   Google-RE    |   5   |  59,576  | Supervised | Wikipedia |  -    |  [url](https://github.com/google-research-datasets/relation-extraction-corpus)        |  
|   ADE   |    3  | 23,516 | Supervised|  Medical Report | [url](http://47.92.96.190/dataset/ade.tar.gz)     |  [url](https://github.com/davidsbatista/Annotated-Semantic-Relationships-Datasets)        |  
|   WebRED   |    523  | 107,819 | Supervised|  World Wide Web| -     |  [url](https://github.com/google-research-datasets/WebRED)        |  

Other Datasets

- [WikiReading](https://github.com/google-research-datasets/wiki-reading) 

## Document-Level

| Dataset | #Rel.|#Inst.|Feature|Source |Resource| Origin |  
|---------|------:|------:|-------:|-------:|-------:|----------| 
|   DocRED   |    3  | 3,053 | Supervised|  Wikipedia | -   |  [url](https://github.com/thunlp/DocRED)        |  
|   CDR   |    3  | 500 | Supervised|  Medical | -    |  [url](https://github.com/fenchri/edge-oriented-graph)        |  
|   GDA   |    3  | 23,353 | Supervised|  Medical | -   |  [url](https://github.com/fenchri/edge-oriented-graph)        |  
 
# Event Extraction


| Dataset |# Inst.|Feature|Source |Resource| Origin |  
|---------|------:|-------:|-------:|-------:|----------| 
|    ACE05    |   599        | Supervised| Web  |  -  |  [url](https://catalog.ldc.upenn.edu/LDC2006T06)        |      
 |    FewEvent(zju)  |    71,385      | Supervised| ACE05+_TAC-KBP17| [url](http://47.92.96.190/dataset/FewEvent.tar.gz)   |  [url](https://github.com/231sm/Low_Resource_KBP)        | 
 |   CCKS2019_Event   |    17,815       | Supervised|  Financial Announcements  |  [url](http://47.92.96.190/dataset/ccks2019_event.tar.gz) |  [url](https://www.biendata.com/competition/ccks_2019_4/data/)        | 
 |  Doc2EDAG    |       32,040    | Supervised| Financial Announcements | [url](http://47.92.96.190/dataset/doc2edag.tar.gz) |    [url](https://github.com/dolphin-zs/Doc2EDAG)        | 
 |  Maven    |       1,276,000    | Supervised| Wikipedia| - |    [url](https://github.com/THU-KEG/MAVEN-dataset)        | 

# How to Cite


