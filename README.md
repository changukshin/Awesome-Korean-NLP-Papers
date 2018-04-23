# Awesome Korean NLP Papers

This respository provides list of Korean NLP papers.

Feel free to contribute!



## Index

1. [How To Contribute](#how-to-contribute)
2. [Conference and Journal List](#conference-and-journal-list)
3. [POS Tagging and Morpheme Analysis](#pos-tagging-and-morpheme-analysis)
4. [Dependency Parsing](#dependency-parsing)
5. [Named Entity Recognition](#named-entity-recognition)
   1. [ETRI dataset](#etri-dataset)
   2. [Other dataset](#other-dataset)
6. [Semantic Role Labeling](#semantic-role-labeling)
7. [Emotion Recognition](#emotion-recognition)
8. [Sentiment Analysis](#sentiment-analysis)
9. [Coreference Resolution](#coreference-resolution)
10. [Question Answering](#question-answering)
11. [Translation](#translation)
12. [Dialogue Management](#dialogue-management)
13. [Document Classification](#document-classification)
14. [Document Summarization](#document-summarization)
15. [Image Captioning](#image-captioning)
16. [Keyword Extraction](#keyword-extraction)
17. [Grammatical Error Correction](#grammatical-error-correction)
18. [Relation Classification](#relation-classification)
19. [Natural Language Generation](#natural-language-generation)
20. [Speech Act Classification](#speech-act-classification)
21. [Abusive Detection](#abusive-detection)
22. [Transliteration](#transliteration)
23. [Document Similarity](#document-similarity)
24. [Automatic Speech Recognition](#automatic-speech-recognition)
25. [Word Sense Disambiguation](#word-sense-disambiguation)
26. [Tools](#tools)
27. [Dataset](#dataset)



## How To Contribute

Feel free to

* Add/Modify wrong or blank informations of papers.
* Add/Modify wrong or blank informations of conferences.

And you can open issue

* When a paper you want to find is missing.
* Whenever else you want to contribute.

Please consider sending PR first. It is a great help to keep this list up-to-date.

Please, do not hesitate to create an issue. It always helps this repository to be informative and healthy.



## Conference and Journal List

| Conference<br />/Journal | Date                | Web Page                                 | Paper List                               |
| ------------------------ | ------------------- | ---------------------------------------- | ---------------------------------------- |
| 2015 정보과학회<br />동계학술대회   | 2015. 12. 17. ~ 18. |                                          | [LINK](http://www.kiise.or.kr/conference02/data/pb/2015WC.pdf) |
| 2016 HCLT                | 2016. 10. 7. ~ 8.   | [LINK](https://sites.google.com/site/2016hclt/home) | [LINK](https://sites.google.com/site/2016hclt/jalyosil) |
| 2017 HCLT                | 2017. 10. 13. ~ 14. | [LINK](https://sites.google.com/view/hclt2017/) | [LINK](https://sites.google.com/view/hclt2017/%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8?authuser=0) |



## POS Tagging and Morpheme Analysis

| Date      | Conference<br />/Journal | Paper                                    | Metric          | Dataset |
| --------- | ------------------------ | ---------------------------------------- | --------------- | ------- |
| 2012. 5.  | 정보과학회논문지                 | [기분석 부분 어절 사전을 활용한<br />한국어 형태소 분석기](http://kiise.or.kr/e_journal/2012/5/SA/pdf/09.pdf) | ACC:95.84       | 세종      |
| 2012. 10. | HCLT                     | [CRF에 기반한 한국어 형태소 분할 및 품사 태깅](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&ved=0ahUKEwic8aKRr6bSAhVHgbwKHRNDB2gQFggmMAI&url=http%3A%2F%2Fsociety.kisti.re.kr%2Fsv%2FSV_svpsbs03V.do%3Fmethod%3Ddownload%26cn1%3DCFKO201208355727429&usg=AFQjCNH2oH3rtZ_20m6BivXaF7szGR5jaw&sig2=g15iYcQoSP6DX0ccdCxiew)              | F1:96.19                | 세종         |
| 2013. 1.  | 정보과학회논문지                 | [음절 단위의 한국어 품사 태깅에서 원형 복원](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE02112476) |                 |         |
| 2013. 10. | HCLT                     | [CRF기반  한국어 형태소 분할 및 품사 태깅에서<br />두 단계 복합형태소 분해 방법](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0ahUKEwic8aKRr6bSAhVHgbwKHRNDB2gQFggbMAA&url=http%3A%2F%2Fsociety.kisti.re.kr%2Fsv%2FSV_svpsbs03V.do%3Fmethod%3Ddownload%26cn1%3DCFKO201308355727353&usg=AFQjCNFsEWXKlh3zbyqoCCB6tbUPH_mJ4w&sig2=IXIrM4863a3bkfrbVm2DDw) | F1:97.23        | 세종      |
| 2013. 10. | HCLT                     | [Semi-CRF or Linear-Chain CRF?<br />한국어 형태소 분할 및 품사 태깅을 위한 결합 모델 비교](http://ocean.kisti.re.kr/IS_mvpopo213L.do?ResultTotalCNT=37&pageNo=1&pageSize=10&method=view&acnCn1=&poid=sighlt&kojic=OOGHAK&sVnc=y2013m10a&id=1&setId=&iTableId=&iDocId=&sFree=&pQuery=%28kojic%3AOOGHAK%29+AND+%28voliss_ctrl_no%3Ay2013m10a%29) | CRF/F1:97.23<br />Semi-CRF/F1:96.83                 | 세종         |
| 2013. 10. | 정보과학회논문지                 | [품사 태깅 말뭉치에서 추출한 n-gram을 이용한<br />음절 단위의 한국어 형태소 분석](http://kiise.or.kr/e_journal/2013/12/sa/pdf/13.pdf) |                 | 코난      |
| 2013. 12. |                          | [Structural SVM을 이용한<br />한국어 띄어쓰기 및 품사 태깅 결합 모델](http://kiise.or.kr/e_journal/2013/12/sa/pdf/09.pdf) | F1:98.03        |         |
| 2014.     | 정보과학회논문지                 | [래티스상의 구조적 분류에 기반한<br />한국어 형태소 분석 및 품사 태깅](http://kiise.or.kr/e_journal/2014/7/SA/pdf/07.pdf) | F1:94.07        | ETRI    |
| 2014. 6.  | KCC                      | [구기반 통계적 모델을 이용한 한국어 형태소 분할 및 품사 태깅](https://www.dbpia.co.kr/Article/NODE02444100) |                 |         |
| 2014. 12. | 정보과학회<br />동계학술대회        | [딥러닝에 기반한 한국어 품사 태깅](www.dbpia.co.kr/Article/NODE06228668) |                 |         |
| 2015. 11. | 정보과학회논문지                 | [딥 러닝을 이용한 한국어 형태소의 원형 복원 오류 수정](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06546841) |                 |         |
| 2016. 6.  | KCC                      | [Sequence-to-sequence 모델을 이용한<br />한국어 형태소 분석 및 품사 태깅](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07017613) |                 |         |
| 2016. 10. | HCLT                     | [품사 분포와 Bidirectional LSTM CRFs를<br />이용한 음절 단위 형태소 분석기](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo2NzdmNzNiZmM1YzRkZDE0) | ACC:97.09       |         |
| 2016. 10. | HCLT                     | [seq2seq 주의집중 모델을 이용한 형태소 분석 및 품사 태깅](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo0M2NjMjE3MDk4MjY4ZDJh) | 음절 ACC:91.28    | 세종      |
| 2016. 10. | HCLT                     | [단순화된 어절을 단위로 하는 한국어 품사 태거](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo1ZDFiNmE1NzM3N2JlM2Iz) | Precision:90.81 |         |
| 2017. 1.  | 정보과학회논문지                 | [Sequence-to-sequence 모델을 이용한<br />한국어 형태소 분석 및 품사 태깅](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07091261) | F1:97.15        | 세종      |
| 2017. 6.  | KCC                      | [Sequence-to-Sequence 기반<br />다중 발화 후보를 이용한 형태소 분석기](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201704&num=8768&pg=3&seGubun=9&seGubun1=&SnxGubun=%C6%F7%BD%BA%C5%CD&searchBy=&searchWord=) | F1:76.54        |         |
| 2017. 10. | HCLT                     | [오타에 강건한 자모 조합 임베딩 기반 한국어 품사 태깅](http://blog.naver.com/PostView.nhn?blogId=naver_search&logNo=221123989668&redirect=Dlog&widgetTypeCall=true&directAccess=false) | ACC:97.50       |         |



## Dependency Parsing

| Date      | Conference<br />/Journal       | Paper                                    | Metric                                   | Dataset   |
| --------- | ------------------------------ | ---------------------------------------- | ---------------------------------------- | --------- |
| 2008. 10. | HCLT                           | CRFs를 이용한 강건한 한국어 의존구조 분석                | UAS:87.30                                | 세종+KIB    |
| 2008. 12. | 한국어정보학회                        | [SVM을 이용한 결정적 한국어 의존 구문분석](http://www.earticle.net/Article.aspx?sn=103226) | UAS:88.25                                | KIBS95    |
| 2010. 3.  | 한국시뮬레이션<br />학회논문지             | [다단계 구단위화를 이용한 고속 한국어 의존구조 분석](http://ocean.kisti.re.kr/downfile/volume/simul/SMROBX/2010/v19n1/SMROBX_2010_v19n1_103.pdf) | UAS:86.01                                |           |
| 2011. 4.  | 정보과학회논문지                       | [자질 가중치의 기계학습에 기반한 한국어 의존파싱](http://ocean.kisti.re.kr/downfile/volume/kiss/JBGHF3/2011/v38n4/JBGHF3_2011_v38n4_214.pdf) | UAS:88.15                                | 세종        |
| 2011      | ACL-WorkShop<br />(SPMRL 2011) | [Statistical Dependency Parsing in Korean:<br />From Corpus Generation To Automatic Parsing](http://www.aclweb.org/anthology/W11-3801) | UAS:85.47<br />LAS:83.74<br />FNC:94.57  | 세종        |
| 2013. 10. | 정보과학회논문지                       | [키어절을 이용한 새로운 한국어 구문분석](http://kiise.or.kr/e_journal/2013/10/sa/pdf/05.pdf) | F1:87.03                                 |           |
| 2014. 1.  | 정보과학회논문지                       | [지배소 후위 집합을 이용한<br />한국어 의존 구문 분석 알고리즘](http://kiise.or.kr/e_journal/2014/1/SA/pdf/09.pdf) | UAS:87.52                                | 세종        |
|           |                                | 신경망과 제약만족 알고리즘을 이용한 한국어 구문분석             |                                          |           |
| 2015. 8.  | 정보과학회논문지                       | [순환 신경망을 이용한 전이 기반 한국어 의존 구문 분석](http://kiise.or.kr/e_journal/2015/8/KTCP/pdf/09.pdf) | UAS:90.33                                | KIBS      |
| 2015. 12. | 정보과학회<br />동계학술대회              | [통계 정보를 이용한 구문분석 트리 후보의 순위화 방법](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06602443) |                                          |           |
| 2016. 6.  | APIC-IST                       | [Improving Korean Dependency Parsing<br />performance using predicate-argument features](bozon.nlp.wo.tc/?f=158c7ea1f1d480) | UAS/자동형태:84.39<br />LAS/자동형태:81.91       | 세종        |
|           | KCC                            | [Stack LSTM을 이용한 전이 기반 한국어 의존 파싱](www.dbpia.co.kr/Article/NODE07017626) |                                          |           |
| 2016. 10. | HCLT                           | [Sequence-to-sequence 모델을 이용한<br />한국어 구구조 구문 분석](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo3YmJhYzdlZDdhODEwMTk3) | F1:89.03                                 | 세종        |
| 2016. 10. | HCLT                           | [Stack LSTM 기반 한국어 의존 파싱을 위한<br />음절과 형태소의 결합 단어 표상 방법](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDpkNWY5NmJkMGRmYTFhOGE) | UAS/정답형태:93.65<br />LAS/정답형태:91.57<br />UAS/자동형태:90.44<br />LAS/자동형태:88.17 | 세종        |
| 2016. 10. | HCLT                           | [의존 경로와 음절단위 의존 관계명 분포 기반의<br />Bidirectional LSTM CRFs를 이용한<br />한국어 의존 관계명 레이블링](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo1MjFiOWYyMTMxNjFmM2Y0) | 의존관계F1:96.01                             | 세종        |
| 2016. 12. | 정보과학회<br />동계학술대회              | [멀티 태스크 학습 기반<br />포인터 네트워크를 이용한 한국어 의존 구문 분석](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201612&num=6763&pg=52&seGubun=&seGubun1=&SnxGubun=%B1%B8%B5%CE&searchBy=&searchWord=) | UAS/자동형태:91.65<br />LAS/자동형태:89.34       | 세종        |
| 2017. 6.  | KCC                            | [Deep Biaffine Attention을 이용한 한국어 의존 파싱](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201704&num=8849&pg=2&seGubun=9&seGubun1=&SnxGubun=%B1%B8%B5%CE&searchBy=&searchWord=) | UAS/자동형태:91.78<br />LAS/자동형태:89.76       | 세종        |
| 2017. 6.  | KCC                            | [전이기반 순환유닛을 이용한<br />SyntaxNet 기반 한국어 의존 파싱](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201704&num=9020&pg=1&seGubun=9&seGubun1=&SnxGubun=%C6%F7%BD%BA%C5%CD&searchBy=&searchWord=) | UAS:90.33<br />LAS:88.69                 | SPMRL '14 |



## Named Entity Recognition

### ETRI dataset

| Date      | Conference<br />/Journal | Paper                                    | Performance(F1)<br />/Dataset            | Tagset   |
| --------- | ------------------------ | ---------------------------------------- | ---------------------------------------- | -------- |
| 2006. 10. | HCLT                     | [Conditional Random Fields를<br />이용한 세부 분류 개체명 인식](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE01065776) | 83.40/ETRI-QA                            | ETRI-147 |
| 2010. 12. | 인지과학회<br />논문지           | [Structural SVMs 및 Pegasos<br />알고리즘을 이용한 한국어 개체명 인식](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE01571100) | 86.79/ETRI-Sports<br />85.43/ETRI-TV     | ETRI-15  |
| 2014. 12. | KCC                      | [딥러닝을 이용한 개체명 인식](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06228667) | 89.03/ETRI-TV-PLO                        | ETRI-PLO |
| 2015. 12. | 정보과학회<br />동계학술대회        | [Word Embeddings 자질을 이용한<br />한국어 개체명 인식 및 분류](http://www.eiric.or.kr/KeyDocs/tmp/FN_1512160193649.pdf) | 89.03/ETRI-TV<br />89.98/ETRI-Sports<br />81.32/ETRI-IT | ETRI-15  |
| 2016. 6.  | 정보과학회논문지                 | [Word Embedding 자질을 이용한<br />한국어 개체명 인식 및 분류](bozon.nlp.wo.tc/?f=158c7ea1f13842) | 89.81/ETRI-TV<br />90.04/ETRI-Sports     |          |
| 2016. 6.  | KCC                      | [문자 기반 LSTM CRF를 이용한 개체명 인식](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201607&num=5313&pg=10&seGubun=&seGubun1=&SnxGubun=%C6%F7%BD%BA%C5%CD&searchBy=&searchWord=) | 86.53/ETRI                               | ETRI     |
| 2016. 10. | HCLT                     | [문자 기반 LSTM-CRF 한국어<br />개체명 인식을 위한 사전 자질 활용](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoxMGQxYmVmMWJiMTc5ZWFh) | 89.34/ETRI                               | ETRI     |

### Other dataset

| Date      | Conference<br />/Journal | Paper                                    | Performance<br />(F1) | Tagset<br />(N of Tags)                  |
| --------- | ------------------------ | ---------------------------------------- | --------------------- | ---------------------------------------- |
| 2008. 6.  | 한국정보과학회<br />강원지부 학회논문   | [2단계 최대 엔트로피 모델을 이용한 한국어 개체명 인식](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE01072690) | 85.20                 | P, L, O                                  |
| 2010      |                          | [기계학습 기반 개체명 인식을 위한 사전 자질 생성](https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0ahUKEwjR99uH6ebYAhWEkZQKHdrzBg8QFggqMAA&url=http%3A%2F%2Fcentral.oak.go.kr%2Fjournallist%2Farticlepdf.do%3Bjsessionid%3D0D5CB7B22346E7BD81E78FC4B6D5A0C0%3Furl%3D%2Frepository%2Fjournal%2F10192%2FGGJBCP_2010_v41n2_31.pdf&usg=AOvVaw3qXF1ThbyRKvJKmLKJfivK) | 90.40                 |                                          |
| 2013      | HCLT                     | [대화형 개인 비서 시스템을 위한 하이브리드<br />방식의 개체명 및 문장목적 동시 인식기술](http://nlp.kookmin.ac.kr/hclt2013/HCLT2013_papers_final.pdf) | 93.50                 | P, L, D, T, Cycle,<br />Title, Currency,<br />Number |
| 2015. 6.  | KCC                      | [Long-Short-term memory 기반의<br />Recurrent Neural Network를 이용한 개체명 인식](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06394172) |                       |                                          |
| 2016. 6.  | KCC                      | [개체명 사전과 원시 말뭉치를 이용한<br />준지도 학습 기반 개체명 인식 모델](http://nlp.kangwon.ac.kr:8080/demo/KACTEIL-KNE_B/KNE_paper.pdf) | 96.70                 | (3)                                      |
| 2016. 2.  | 정보과학회논문지                 | [원거리 감독과 능동 배깅을 이용한 개체명 인식](http://kiise.or.kr/e_journal/2016/2/JOK/pdf/15.pdf) | 76.42                 | (11)                                     |
| 2016. 9.  | 정보처리학회논문지                | [조건부 랜덤 필드를 이용한 특허 문서의 개체명 인식](http://society.kisti.re.kr/sv/SV_svpsbs03V.do?method=download&cn1=JAKO201630765902875) | 65.40                 | (5B+5I+O)                                |
| 2016. 10. | HCLT                     | [품사 임베딩과 음절 단위 개체명 분포 기반의<br />Bidirectional LSTM CRFs를 이용한 개체명 인식](https://docs.google.com/viewer?(%EC%9C%A0%ED%99%8D%EC%97%B0,%20%EA%B3%A0%EC%98%81%EC%A4%91)%20a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo1NjdmNjFlMjJhYjQ1OWI2) | 79.52                 |                                          |
| 2016. 10. | HCLT                     | [의생명 분야의 개체명 인식에서 순환형 신경망과 조건적 임의 필드의 성능 비교](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDozZjIzNDZlY2UzODIzOTBl) | 72.82                 |                                          |
| 2016. 12. | 정보과학회<br />동계학술대회        | [자소 편집거리를 이용한 한글 트위터 개체명 인식](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07115922) | 83.51                 |                                          |
| 2016. 12. | 정보과학회<br />동계학술대회        | [식품 도메인 개체명 인식을 위한 문자 기반 LSTM CRF](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07115928) |                       |                                          |
| 2017. 3.  | 정보과학회논문지                 | [Bidirectional LSTM CRF 기반의<br />개체명 인식을 위한 단어 표상의 확장](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07121169) | 80.68                 |                                          |
| 2017. 6.  | KCC                      | [CNN을 이용한 대화와 같은 짧은 문장에서 개체명 인식](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201704&num=9018&pg=2&seGubun=9&seGubun1=&SnxGubun=%C6%F7%BD%BA%C5%CD&searchBy=&searchWord=) | 88.56                 |                                          |
| 2017. 6.  | KCC                      | [순환 신경망과 합성곱 신경망을 이용한 개체명 인식](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201704&num=8762&pg=4&seGubun=9&seGubun1=&SnxGubun=%C6%F7%BD%BA%C5%CD&searchBy=&searchWord=) | 75.53                 |                                          |
| 2017. 10. | HCLT                     | [한국어 특질을 고려한 단어 벡터의<br />Bi-LSTM 기반 개체명 모델 적용](http://semanticweb.kaist.ac.kr/home/images/e/ea/%ED%95%9C%EA%B5%AD%EC%96%B4_%ED%8A%B9%EC%A7%88%EC%9D%84_%EA%B3%A0%EB%A0%A4%ED%95%9C_%EB%8B%A8%EC%96%B4_%EB%B2%A1%ED%84%B0%EC%9D%98_Bi-LSTM_%EA%B8%B0%EB%B0%98_%EA%B0%9C%EC%B2%B4%EB%AA%85_%EB%AA%A8%EB%8D%B8_%EC%A0%81%EC%9A%A9.pdf) |                       |                                          |
| 2017. 12. | 정보과학회논문지                 | [자질 보강과 양방향 LSTM-CNN-CRF<br />기반의 한국어 개체명 인식 모델](http://www.earticle.net/Article.aspx?sn=317610) | 89.40                 |                                          |



## Semantic Role Labeling

| Date      | Conference<br />/Journal                 | Paper                                    | Metric                           |
| --------- | ---------------------------------------- | ---------------------------------------- | -------------------------------- |
| 2015      | 정보과학회논문지                                 | [Structural SVM 기반의 한국어 의미역 결정](https://www.dbpia.co.kr/Journal/ArticleDetail/NODE06097446) | F1:76.04                         |
| 2015. 6.  | KCC                                      | [딥 러닝을 이용한 한국어 의미역 결정](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06394187) | F1:76.96                         |
| 2015. 12. | 한국정보과학회<br />학술대회                        | [Bidirectional LSTM CRF를 이용한<br />End-To-End 한국어 의미역 결정](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06602453) | F1:78.16                         |
| 2015      | 인지과학회                                    | [한국어 의미역 결정을 위한 Korean PropBank<br />확장 및 도메인 적응 기술 적용](www.dbpia.co.kr/Article/NODE06586490) |                                  |
|           |                                          | A study of Korean Semantic Role Labeling using Word sense |                                  |
| 2016      | Advanced Science and<br />Technology Letters | [Korean Semantic Role Labeling<br />Using Korean PropBank Frame Files](http://onlinepresent.org/proceedings/vol142_2016/15.pdf) | ACC:90.00                        |
| 2016. 10. | HCLT                                     | [음절의 의미역 태그 분포를 이용한<br />Bidirectional LSTM CRFs 기반의 한국어 의미역 결정](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo1M2MzZGVjNDk3NjUzYzU4) | F1:66.13                         |
| 2016. 10. | HCLT                                     | [CRF를 이용한 복수 의미역 문제 해결](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo3YTdiZTcxY2IyNzBkOTMy) | F1:74.47                         |
| 2016. 10. | HCLT                                     | [Input-feeding RNN Search 모델과 CopyNet을 이용한 한국어 의미역 결정](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDozYzc4MTdiOWQ0OGNkNWI3) | 어절AIC:71.58<br />Label AIC:79.42 |
| 2016. 10. | HCLT                                     | [베이지안 모형 기반 한국어 의미역 유도](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo2Yjg1M2U2NjZkYzE4NjNj) | F1*:83.26                        |
| 2016. 12. | 정보과학회논문지                                 | [격틀 사전과 하위 범주 정보를 이용한 한국어 의미역 결정](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07079316) | F1:78.47                         |
| 2017. 1.  | 정보과학회논문지                                 | [Stacked Bidirectional LSTM-CRFs를 이용한<br />한국어 의미역 결정](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07091258) | F1:78.57                         |
| 2017. 6.  | KCC                                      | [형태 의미 정보를 이용한 한국어 의미역 결정](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201704&num=8851&pg=2&seGubun=9&seGubun1=&SnxGubun=%B1%B8%B5%CE&searchBy=Subject&searchWord=) | F1:77.36                         |
| 2017. 6.  | KCC                                      | [문자 기반 LSTM CRF를 이용한 한국어 의미역 결정](https://www.dbpia.co.kr/Journal/ArticleDetail/NODE07207765) |                                  |
| 2017      | International Journal<br />of Database Theory<br />and Application | [A Study of Dictionary Based<br />Korean Semantic Role Labeling](http://www.sersc.org/journals/IJDTA/vol10_no7/6.pdf) |                                  |
| 2017. 10. | HCLT                                     | Highway BiLSTM-CRFs 모델을 이용한<br />한국어 의미역 결정 |                                  |



## Emotion Recognition

| Date      | Conference<br />/Journal | Paper                                    | Metric    | Number of Tags |
| --------- | ------------------------ | ---------------------------------------- | --------- | -------------- |
| 2002      | 석사학위논문                   | [Hybrid Naive Bayes HMM 기법을 사용한<br />텍스트로부터의 감정 분류](https://bi.snu.ac.kr/Publications/Theses/MoonHK_MS02.pdf) |           | 7              |
| 2010      | 인지과학회                    | [대화 시스템을 위한 사용자 발화 문장의 감정 분류](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE01571093) | F1:62.80  | 9              |
| 2013. 6.  | 정보과학회논문지                 | [한글 마이크로블로그 텍스트의<br />감정 분류 및 분석](http://kiise.or.kr/e_journal/2013/6/DB/pdf/02.pdf) |           |                |
| 2013. 11. | 한국엔터테인먼트<br />산업학회 학술대회  | [기계 학습을 이용한 한글 텍스트 감정 분류](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE02367979) | F1:72.00  | 9              |
| 2014. 6.  | KCC                      | [기계 학습을 이용한 한글 텍스트 감정 분류 및 분석](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE02444514) |           |                |
| 2015. 10. | HCLT                     | 임베딩 자질을 이용한 대화의 감정 분류                    | ACC:72.89 | 9              |
| 2016. 10. | HCLT                     | [CNN-LSTM을 이용한 대화 문맥 반영과 감정 분류](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo0M2JmNDUwNWFlNmFiZTMy) | ACC:82.93 | 11             |



## Sentiment Analysis

| Date      | Conference<br />/Journal                 | Paper                                    | Metric     | Tagset |
| --------- | ---------------------------------------- | ---------------------------------------- | ---------- | ------ |
| 2010. 4.  | 정보과학회논문지                                 | [감정 단어의 의미적 특성을 반영한<br />한국어 문서 감정분류 시스템](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE01427887) | F1:80.18   | P/N    |
| 2012. 5.  | 언어과학연구                                   | [감성 분석 연구의 현황과 말뭉치에 기반한 사례 분석<br />: 영화평 자료를 중심으로](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06607901) | 83.82      | P/N    |
| 2014. 11. | 대한산업공학회                                  | [SVM과 HCRF를 이용한 텍스트 문서 감정 분류 모델](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE02511231) | F1:86.00   | P/N    |
| 2014      | Advanced Science and<br />Technology Letters | [Sentiment Classification of Movie Reviews<br />Using Korean Sentiment Dictionary](http://onlinepresent.org/proceedings/vol76_2014/9.pdf) | ACC*:81.50 | P/N    |
| 2014. 2.  | Journal of Korea<br />Multimedia Society | [한국어 트위터의 감정 분류를 위한<br />기계학습의 실증적 비교](https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=web&cd=8&ved=0ahUKEwjVisXXl-fYAhWGJZQKHWoGBpMQFghFMAc&url=http%3A%2F%2Fwww.kpubs.org%2Farticle%2FarticleDownload.kpubs%3FdownType%3Dpdf%26articleANo%3DMTMDCW_2014_v17n2_232&usg=AOvVaw06JI0iy1EOrJUsGlNMGWhZ) |            |        |
| 2015. 12. | 정보과학회<br />동계학술대회                        | [RNN과 attention mechanism을 이용한 감성분석](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06602450) | ACC:80.41  | P/N    |
| 2016. 5.  | 정보처리학회논문지                                | [감성 분석 및 감성 정보 부착 시스템 구현](http://210.101.116.28/W_files/kiss9/52809368_pv.pdf) | ACC:76.00  | P/N/N  |
| 2016. 10. | HCLT                                     | [WPM(Word Piece Model)을 활용한 구글 플레이스토어 앱의 댓글 감정 분석 연구](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoyMDQ3ZDk4NzhlMzMzM2Rk) |            | P/N    |
| 2016. 10. | HCLT                                     | [영어 SentiWordNet을 이용하여 구축된 한국어 감성어휘사전의 성능과 한계 연구](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo1MjEzZTkyYWRkNmFmZjI0) |            |        |
| 2016. 10. | HCLT                                     | [MUSE 감성주석코퍼스를 활용한 문장 극성과 키워드 극성간의 불일치 현상에 대한 분석](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoyOTZmMDViMGEzODg1ZDBl) |            |        |
| 2017. 2.  |                                          | [의미 정보가 강화된<br />워드 임베딩을 통한 감성 분석](http://www.sersc.org/journals/AJMAHS/vol7_no2_2017/32.pdf) | ACC:82.30  |        |
| 2017. 6.  | KCC                                      | [합성 곱 신경망을 이용한 한글 텍스트 감성 분류기 설계](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07207332) | ACC:87.88  |        |
| 2017. 6.  | KCC                                      | [Skip-Connected LSTM을 이용한 감성 분석](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07207329) | ACC:81.47  |        |

 

## Coreference Resolution

| Date      | Conference<br />/Journal | Paper                                    | Metric                         |
| --------- | ------------------------ | ---------------------------------------- | ------------------------------ |
| 2014. 6.  | KCC                      | [SVM 기반의 Mention Pair Model을 이용한 한국어 상호참조해결](http://insight.dbpia.co.kr/article/related.do?nodeId=NODE02444109) | F1:61.67                       |
| 2014. 11. | 정보과학회논문지                 | [Multi-pass Sieve를 이용한 한국어 상호참조해결](http://kiise.or.kr/e_journal/2014/11/JOK/pdf/15.pdf) | MUC:58.97<br />CoNLL:60.65     |
| 2015. 4.  | 정보과학회논문지                 | [SVM 기반의 멘션 페어 모델을 이용한한국어 상호참조해결](http://kiise.or.kr/e_journal/2015/4/KTCP/pdf/09.pdf) | CEAFE-F1:61.75                 |
| 2015. 6.  | KCC                      | [딥러닝을 이용한 가이드 멘션페어 한국어 상호참조해결](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06394188) |                                |
| 2016. 2.  | 석사학위논문                   | [규칙과 기계학습을 이용한 한국어 상호참조해결](http://cs.kangwon.ac.kr/~parkce/seminar/CoreferenceResolutionForKorean_paper.pdf) |                                |
| 2016. 6.  | KCC                      | [시브 자질 기반 랜덤 포레스트를 이용한<br />한국어 상호참조 해결](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07017614) | CoNLL:62.00                    |
| 2016. 10. | HCLT                     | [포인터 네트워크를 이용한 멘션 탐지](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07226475) | 상호참조F1:52.69<br />멘션탐지F1:80.75 |
| 2016. 11. | 정보처리학회논문지                | [랜덤 포레스트를 이용한 한국어 상호참조 해결](http://kiss.kstudy.com/thesis/thesis-view.asp?key=3483575) |                                |
| 2016. 12. | 정보과학회<br />동계학술대회        | [계층적 포인터 네트워크를 이용한 상호참조해결](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07115923) | F1:72.43                       |
| 2017. 5.  | 정보과학회논문지                 | [포인터 네트워크를 이용한<br />한국어 대명사 상호참조해결](http://kiise.or.kr/e_journal/2017/5/JOK/pdf/07.pdf) | 81.40                          |
| 2017. 6.  | KCC                      | [Bi-directional Multiple Timescale GRU 기반<br />포인터 네트워크를 이용한 상호참조해결](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07207325) | F1:71.05                       |
| 2017. 6.  | KCC                      | [k-Max Pooling을 적용한<br />Cluster-Pair Encoder를 이용한 상호참조해결](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07207318) | MUC:64.05<br />F1:54.76        |



## Question Answering

| Date      | Conference<br />/Journal       | Paper                                    | Metric      |
| --------- | ------------------------------ | ---------------------------------------- | ----------- |
| 2003      |                                | [한국어 질의응답시스템을 위한 지지벡터기계 기반의 질의유형분류기](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE00615690) |             |
| 2004      |                                | [한국어 질의응답시스템에서 구문정보에 기반한 질의분석](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE00629069) | Precision*  |
|           |                                | [어휘 의미 정보를 이용하는 질의응답 시스템의 질의유형 분류](http://203.237.168.42/IMG/01/000000002834/SERVICE/000000002834_01.PDF) |             |
| 2011      | HCLT                           | [실시간 검색어를 이용한 주제어 기반의 질의응답시스템](https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=web&cd=22&ved=0ahUKEwiarffu5b_UAhWEkpQKHR8XBYcQFgiDATAV&url=http%3A%2F%2Fsociety.kisti.re.kr%2Fsv%2FSV_svpsbs03V.do%3Fmethod%3Ddownload%26cn1%3DCFKO201108355727520&usg=AFQjCNFDCazU496M-lJPp-wL3arkgl4ZKA&sig2=wzWRhGqtMeB-l0K4yr49jA) |             |
| 2012. 2.  | 정보과학회논문지                       | [오픈 도메인 질의응답을 위한 검색문서 제약 및 정답유형 분류기술](http://kiise.or.kr/e_journal/2012/2/SA/pdf/06.pdf) |             |
| 2013      | HCLT                           | [질의 응답 시스템을 위한 반교사 기반의 정답 유형 분류](https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=web&cd=7&ved=0ahUKEwinwJTH6L_UAhXJnpQKHVwiBPIQFghEMAY&url=http%3A%2F%2Fsociety.kisti.re.kr%2Fsv%2FSV_svpsbs03V.do%3Fmethod%3Ddownload%26cn1%3DCFKO201308355727361&usg=AFQjCNHnGs0DBceX4XMpdCLCqezUF5Ny-A&sig2=F8UaAE3mQq9LNjdhnef8Fg) |             |
| 2014. 4.  | 정보처리학회논문지                      | [Q&A 문서의 검색 결과 요약을 활용한 질의응답 시스템](https://www.google.co.kr/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&ved=0ahUKEwjNoYPg27_UAhUCGJQKHVt7B0EQFggwMAI&url=http%3A%2F%2Fsociety.kisti.re.kr%2Fsv%2FSV_svpsbs03V.do%3Fmethod%3Ddownload%26cn1%3DJAKO201416060569820&usg=AFQjCNHNzft8QD85oQZ4NitWBfzE80YPqg&sig2=L-y8Duwah3JEVdibIVJP2w) |             |
| 2015. 10. | ISWC NLIWoD<br />2015 Workshop | [Design and Implementation of an Evaluator for Building<br />a Good Knowledge Base in Question Answering](http://semanticweb.kaist.ac.kr/home/images/4/41/Design_and_Implementation_of_an_Evaluator_for_Building_a_Good_Knowledge_Base_in_Question_Answering.pdf) |             |
| 2015. 12. | 정보과학회<br />동계학술대회              | [질의응답 시스템에서 처음 보는 단어의 효율적인 처리](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06602913) |             |
| 2016. 6.  | KCC                            | [질의응답 시스템 성능 개선을 위한 질의 트리플 확장](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07017707) |             |
| 2016. 10. | HCLT                           | [한국어 질의응답 시스템을 위한 프레임 시멘틱스 기반 질의 의미 분석](http://semanticweb.kaist.ac.kr/home/images/c/c5/%ED%95%9C%EA%B5%AD%EC%96%B4_%EC%A7%88%EC%9D%98%EC%9D%91%EB%8B%B5_%EC%8B%9C%EC%8A%A4%ED%85%9C%EC%9D%84_%EC%9C%84%ED%95%9C_%ED%94%84%EB%A0%88%EC%9E%84_%EC%8B%9C%EB%A9%98%ED%8B%B1%EC%8A%A4_%EA%B8%B0%EB%B0%98_%EC%A7%88%EC%9D%98_%EC%9D%98%EB%AF%B8_%EB%B6%84%EC%84%9D.pdf) | F1:81.37    |
| 2016. 10. | HCLT                           | [질의응답 시스템에서 형태소임베딩 모델과<br />GRU 인코더를 이용한 문장유사도 측정](http://koasas.kaist.ac.kr/bitstream/10203/219384/1/%EC%9D%B4%EB%8F%99%EA%B1%B4HCLT2016_%EC%A7%88%EC%9D%98%EC%9D%91%EB%8B%B5%20%EC%8B%9C%EC%8A%A4%ED%85%9C%EC%97%90%EC%84%9C%20%ED%98%95%ED%83%9C%EC%86%8C%EC%9E%84%EB%B2%A0%EB%94%A9%20%EB%AA%A8%EB%8D%B8%EA%B3%BC%20GRU%20%EC%9D%B8%EC%BD%94%EB%8D%94%EB%A5%BC%20%EC%9D%B4%EC%9A%A9%ED%95%9C%20%EB%AC%B8%EC%9E%A5%EC%9C%A0%EC%82%AC%EB%8F%84%20%EC%B8%A1%EC%A0%95.pdf) | TOP5*:51.63 |
| 2016. 10. | HCLT                           | [딥러닝과 정보검색을 결합한 질의응답 시스템](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoyZTRmMDQwODJkNzAwMzYx) |             |
| 2017. 10. | HCLT                           | [심층적 의미 매칭을 이용한 cQA 시스템 질문 검색](http://blog.naver.com/PostView.nhn?blogId=naver_search&logNo=221123989668) | P@1:51.5    |



## Translation

| Date      | Conference<br />/Journal | Paper                                    | Metric     |
| --------- | ------------------------ | ---------------------------------------- | ---------- |
| 2014. 8.  | 정보과학회논문지                 | [위키피디아로부터 한국어-영어 병렬 문장 추출](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE02457679) |            |
| 2016. 10. | HCLT                     | [극한 언어 환경에 대응 가능한 영한 자동 주소번역 시스템](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoyNTBlNTZiYmY1ZmQ3ODUx) | ACC:95.39  |
| 2016. 10. | HCLT                     | [말뭉치 자동 확장을 통한 SMT 성능 향상에 대한 연구](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo0NTEwMmYxYjI1NWI0ZTli) | BLEU:24.26 |





## Dialogue Management

| Date      | Conference<br />/Journal | Paper                                    | Metric                                   |
| --------- | ------------------------ | ---------------------------------------- | ---------------------------------------- |
| 2014      | 정보과학회<br />동계학술대회        | [Hidden Markov Model을 이용한 대화 의도 모델링](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06229011) |                                          |
| 2016. 10. | HCLT                     | [격틀과 워드 임베딩을 활용한 유사도 기반 대화 모델링](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo1ZDdjY2Y3NWU0ZmY2Yjhh) | MRR:93.9                                 |
| 2016. 10. | HCLT                     | [Long Short-Term Memory를 이용한 통합 대화 분석](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoyZmNhNDRjODZlYmRjMWUy) | 감정ACC:58.08<br />화행ACC:82.60<br />서술자ACC:62.74 |
| 2016. 12. | 정보과학회<br />동계학술대회        | [Konvbot: 한국어 대화 모델 - 아침, 가정환경을 중심으로](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07115970) |                                          |
| 2017. 6.  | KCC                      | [합성곱 신경망을 이용한 음절 표상의 학습을 통한<br />대화 시스템의 사용자 발화 의도 분석](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07207324) | ACC:92.84                                |
| 2017. 6.  | KCC                      | [End-to-end learning을 이용한 한국어 단문 응답 시스템 개발](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07207353) |                                          |
| 2017. 8.  | 컴퓨터교육학회                  | Hybrid Code Network를 이용한 한국어 식당 예약 시스템 모델 |                                          |
| 2017. 10. | HCLT                     | [MTRNN을 이용한 한국어 대화 모델 생성](http://bozon.nlp.wo.tc/?f=159e856b9eea81)                  | BLEU4:0.22                               |
| 2017. 10. | HCLT                     | 도메인 특정 지식을 결합한 End-to-End Learning 방식의<br />한국어 식당 예약 대화 시스템 모델 개발 | Per Response:0.95<br />Per Dialogue:0.64 |



## Document Classification

| Date      | Conference<br />/Journal | Paper                                    | Metric   |
| --------- | ------------------------ | ---------------------------------------- | -------- |
| 2012. 4.  | 한국전자거래학회<br />춘계학술대회     | [청킹 기반 특징 추출을 통한 문서 분류 시스템의 성능 향상](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE01954443) |          |
| 2016. 10. |                          | [문서 분류 알고리즘을 이용한 한국어 스팸 문서 분류 성능 비교](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE00768067) | F1:98.40 |
| 2016. 10. | HCLT                     | [Doc2Vec을 활용한 CNN기반<br />한국어 신문기사 분류에 관한 연구](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDo2OTE0MDMzNTVjYzA4MWRh) |          |
| 2017. 6.  | KCC                      | [한국어자모단위기반의 Convolution Neural Network를<br />이용한 텍스트 분류](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201704&num=8850&pg=2&seGubun=9&seGubun1=&SnxGubun=%B1%B8%B5%CE&searchBy=Subject&searchWord=) |          |
| 2017. 10. | HCLT                     | [대규모 분류 체계에서 계층적 샘플링을 활용한 문서의 분류](http://blog.naver.com/PostView.nhn?blogId=naver_search&logNo=221123989668&redirect=Dlog&widgetTypeCall=true&directAccess=false) |          |



## Document Summarization

| Date      | Conference<br />/Journal | Paper                                    | Metric                                   |
| --------- | ------------------------ | ---------------------------------------- | ---------------------------------------- |
| 2016. 10. | HCLT                     | [Copy Mechanism과 Input Feeding을 이용한<br />End-to-End 한국어 문서요약](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoxYmU3MDcxMTcyOTkxYTNj) | ROUGE-1:35.92<br />ROUGE-2:15.37<br />ROUGE-L:29.45 |
| 2016. 12. | 정보과학회<br />동계학술대회        | [lexrankr: LexRank 기반 한국어 다중 문서 요약](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201612&num=6769&pg=51&seGubun=&seGubun1=&SnxGubun=%C6%F7%BD%BA%C5%CD&searchBy=&searchWord=) | F1:53.40                                 |
| 2017. 5.  | 정보과학회논문지                 | [복사 방법론과 입력 추가 구조를 이용한<br />End-to-End 한국어 문서요약](http://kiise.or.kr/e_journal/2017/5/JOK/pdf/08.pdf) | ROUGE-1:35.92<br />ROUGE-2:15.37<br />ROUGE-L:29.45 |



## Image Captioning

| Date      | Conference<br />/Journal | Paper                                    |
| --------- | ------------------------ | ---------------------------------------- |
| 2015. 12. | 정보과학회<br />동계학술대회        | Recurrent Neural Network를 이용한 이미지 캡션 생성  |
| 2016. 8.  | 정보과학회논문지                 | [Recurrent Neural Network를 이용한 이미지 캡션 생성](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE06737196) |
| 2016. 12. | 정보과학회<br />동계학술대회        | [딥러닝을 이용한 한국어 이미지 캡션 생성](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201612&num=6779&pg=1&seGubun=13&seGubun1=&SnxGubun=%C6%F7%BD%BA%C5%CD&searchBy=&searchWord=) |
| 2017. 10. | HCLT                     | LSTM을 이용한 한국어 이미지 캡션 생성                  |



## Keyword Extraction

| Date      | Conference<br />/Journal | Paper                                    | Metric |
| --------- | ------------------------ | ---------------------------------------- | ------ |
| 2002. 10. | 정보과학회논문지                 | [주성분 분석을 이용한 문서 주제어 추출](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE00614779) |        |
| 2010      | 한국정보통신<br />학회논문지        | [비감독 학습 기법에 의한 한국어의 키워드 추출](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE02251588) | F1:65  |
| 2015. 2.  | 한국컴퓨터정보<br />학회논문지       | [TF-IDF와 소설 텍스트의 구조를 이용한 주제어 추출 연구](http://insight.dbpia.co.kr/article/related.do?nodeId=NODE06533140) |        |
| 2016. 10. | HCLT                     | [한글 문서의 단어 동시 출현 정보에 개선된<br />TextRank를 적용한 키워드 자동 추출 기법](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoxOGM5ODFhNTNkN2I4OTlk) |        |



## Grammatical Error Correction

| Date      | Conference<br />/Journal | Paper                                    | Metric     |
| --------- | ------------------------ | ---------------------------------------- | ---------- |
| 2016. 6.  | KCC                      | [딥러닝을 이용한 한국어 자동 띄어쓰기](http://insight.dbpia.co.kr/article/related.do?nodeId=NODE07017628) | 어절F1:92.32 |
| 2016. 10. | HCLT                     | Default 연산 알고리즘을 적용한 통계적 문맥의존 철자오류 교정 기법의 성능 향상 |            |
| 2017. 6.  | KCC                      | [말뭉치 확장 기법을 이용한 음절 단위 한국어 문장 교정 시스템](http://www.eiric.or.kr/community/m_post2.php?m=view&gubun=201704&num=9022&pg=1&seGubun=9&seGubun1=&SnxGubun=%C6%F7%BD%BA%C5%CD&searchBy=&searchWord=) |            |
| 2017      |                          | [한글 편집거리 알고리즘을 이용한 한국어 철자오류 교정방법](http://kism.or.kr/file/memoir/6_1_2.pdf) |            |



## Relation Classification

| Date     | Conference<br />/Journal | Paper                                    | Metric   |
| -------- | ------------------------ | ---------------------------------------- | -------- |
| 2017. 6. | KCC                      | [Input Attention 기반 LSTM-CNN 모델을 이용한 Relation Classification](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201704&num=9028&pg=1&seGubun=9&seGubun1=&SnxGubun=%C6%F7%BD%BA%C5%CD&searchBy=&searchWord=) | F1:69.30 |



## Natural Language Generation

| Date      | Conference<br />/Journal | Paper                                    | Metric |
| --------- | ------------------------ | ---------------------------------------- | ------ |
| 2016. 10. | HCLT                     | [온톨로지 기반의 문서생성 시스템](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoyZjJhYWI1NWM4YjZlZGNh) |        |
| 2017. 6.  | KCC                      | [Sequence-to-sequence 모델을 이용한 자연어생성](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201704&num=9027&pg=1&seGubun=9&seGubun1=&SnxGubun=%C6%F7%BD%BA%C5%CD&searchBy=&searchWord=) |        |



## Speech Act Classification

| Date      | Conference<br />/Journal         | Paper                                    | Metric   |
| --------- | -------------------------------- | ---------------------------------------- | -------- |
| 2015. 1.  | Pattern Recognition<br />Letters | [New feature weighting approaches for speech-act classification](https://www.sciencedirect.com/science/article/pii/S0167865514002803) |          |
| 2017. 6.  | KCC                              | [대화문맥을 이용한 심층학습 기반 다중-태그 화행분석 모델](http://www.eiric.or.kr/community/post2.php?m=view&gubun=201704&num=8852&pg=2&seGubun=9&seGubun1=&SnxGubun=%B1%B8%B5%CE&searchBy=&searchWord=) |          |
| 2017. 10. | HCLT                             | CNN-LSTM 신경망을 이용한 발화 분석 모델               |          |
| 2017. 10. | HCLT                             | [CNN을 이용한 발화 주제 다중 분류](http://blog.naver.com/PostView.nhn?blogId=naver_search&logNo=221123989668) | F1:98.73 |



## Abusive Detection

| Date     | Conference<br />/Journal | Paper                                    | Metric   |
| -------- | ------------------------ | ---------------------------------------- | -------- |
| 2017. 6. | KCC                      | [반자동 학습 기반의 비속어 및 욕설 탐지 시스템](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE07207189) | F1:84.23 |



## Transliteration

| Date      | Conference<br />/Journal | Paper                                    | Metric   |
| --------- | ------------------------ | ---------------------------------------- | -------- |
| 2017. 10. | HCLT                     | [Distance LSTM-CNN with Layer Normalization을 이용한음차 표기 대역 쌍 판별](http://blog.naver.com/PostView.nhn?blogId=naver_search&logNo=221123989668) | F1:89.70 |



## Document Similarity

| Date      | Conference<br />/Journal | Paper                                    | Metric |
| --------- | ------------------------ | ---------------------------------------- | ------ |
| 2016. 10. | HCLT                     | [문서의 공기관계를 이용하여 국가 R&D 보고서간 유사도 계산](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoxNDg5YjhlZmJjMzEyNzNk) |        |



## Automatic Speech Recognition

| Date      | Conference<br />/Journal | Paper                                    | Metric   |
| --------- | ------------------------ | ---------------------------------------- | -------- |
| 2016. 10. | HCLT                     | [음성 인식 오류 수정을 위한 Trie 기반 사전을 이용한 Guided Sequence Generation](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnwyMDE2aGNsdHxneDoyNGMxYzExM2VmN2YzNWE5) | WER:7.05 |



## Word Sense Disambiguation

| Date      | Conference<br />/Journal | Paper                                    | Metric |
| --------- | ------------------------ | ---------------------------------------- | ------ |
| 2017. 10. | HCLT                     | [코어넷을 활용한 비지도 한국어 어의 중의성 해소](http://semanticweb.kaist.ac.kr/home/images/3/33/%EC%BD%94%EC%96%B4%EB%84%B7%EC%9D%84_%ED%99%9C%EC%9A%A9%ED%95%9C_%EB%B9%84%EC%A7%80%EB%8F%84_%ED%95%9C%EA%B5%AD%EC%96%B4_%EC%96%B4%EC%9D%98_%EC%A4%91%EC%9D%98%EC%84%B1_%ED%95%B4%EC%86%8C.pdf) |        |



## Tools

| Date | Conference<br />/Journal | Paper                                    |
| ---- | ------------------------ | ---------------------------------------- |
| 2014 |                          | [한국어 의미역 말뭉치 구축을 위한 반자동 태깅 도구 개발](http://www.dbpia.co.kr/Journal/ArticleDetail/NODE02444107) |



## Dataset

| Date      | Conference<br />/Journal | Paper                           |
| --------- | ------------------------ | ------------------------------- |
| 2017. 10. | HCLT                     | 식당 예약 대화 시스템 개발을 위한 한국어 데이터셋 구축 |

