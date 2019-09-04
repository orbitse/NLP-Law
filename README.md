# NLP-Law
This repository highlights recent natural language processing (NLP) work in the legal field. Applying NLP techniques to publicly accessible legal text to improve both, access to and understanding of, the law is especially important.  

## Data Science and Law
The intersection between machine learning and the law has many names, _e.g._ computational law, legal analytics, legal informatics, or empirical legal studies. AI automation can help improve many aspects of the law. Programs can review contracts to identify risks and problematic language, assist with discovery, make predictions about the outcomes of legal proceedings, and help law enforcement identify criminal behavior. Lawyer-bots can even answer simple questions like in Joshua Browder's [DoNotPay app](https://itunes.apple.com/us/app/donotpay/id1427999657). But, in order to apply probabilistic models to the law, you need to understand legal language. Although, applying machine learning to the law is still quite new, it will likely become a disruptive force in the legal service industry.  

#### Repository Outline ####
  - [Relevant Projects](https://github.com/orbitse/Awesome-Law-NLP-Research-Work#relevant-projects)
  - [Example Companies](https://github.com/orbitse/Awesome-Law-NLP-Research-Work#relevant-companies)
  - [Recent Papers](https://github.com/orbitse/Awesome-Law-NLP-Research-Work#relevant-papers)
  - [Current Project](https://github.com/orbitse/Awesome-Law-NLP-Research-Work#current-project)  
  - [Future Work](https://github.com/orbitse/Awesome-Law-NLP-Research-Work#future-work)

----------

### Relevant Projects  

The European Union funds research projects to improve computational legal analysis for the public good. For example, the [MIREL](http://www.mirelproject.eu): MIning and REasoning with Legal texts addresses issues like legal interpretation in mining and reasoning, how to handle big legal data, and regulatory compliance.  

The Stanford Law School supports several [computational law](http://logic.stanford.edu/complaw/complaw.html) projects through [CodeX](https://law.stanford.edu/codex-the-stanford-center-for-legal-informatics/codex-projects/#slsnav-current-codex-projects). CodeX's research and development focuses on the automation and mechanization of legal analysis in hopes of improving legal efficiency, transparency, and access to legal systems around the world.  

The [Stanford Legal Design Lab](https://law.stanford.edu/organizations/pages/legal-design-lab/) and [Suffolk Law School’s Legal Innovation and Technology Lab](https://suffolklitlab.org) created a machine learning labeling game called [Learned Hands](https://learnedhands.law.stanford.edu). Players read people’s legal stories and spot legal issues. The game-play generates labeled data for training Access to Justice AI models to automatically identify people’s legal problems.  

The [American Constitution Society for Law and Policy](https://www.acslaw.org) created the [State Bench Database](https://gavelgap.org) with 10,000+ judges on state courts of general jurisdiction in all 50 states. Using this data, they compared the gender, racial, and ethnic composition of state courts with the general population in each state. They found that courts are not representative of the people whom they serve; this disparity is [The Gavel Gap](https://gavelgap.org).  

The [Legislative Explorer](http://www.legex.org/index.html) from the [Center for American Politics and Public Policy](http://cappp.org) at the University of Washington is an "interactive visualization that allows anyone to explore actual patterns of lawmaking in Congress." The congressional bill data comes from the [Congeessional Bills Project](http://congressionalbills.org).  

[California Civic Data Coalition](http://cjlab.stanford.edu/projects/california-civic-data-coalition/) is a partnership between the Los Angeles Times Data Desk, the San Francisco Chronicle, The Center for Investigative Reporting and Stanford’s Computational Journalism Lab. The Coalition's purpose is to "create software that makes California's public data easier to analyze." To that end, the Coalition makes open-source software and campaign finance data available at https://www.californiacivicdata.org. The data comes from the California Secretary of State's non-user friendly CAL-ACCESS database, consisting of 80 database tables.   

### Example Companies  

[Bloomberg Law](https://pro.bloomberglaw.com/ai-analytics/) provides several AI tools along with 13+ million published and unpublished state and federal court opinions. With "Litigation Analytics," users can search by company, law firm, attorney, and judge, then "[v]isualize trends, predict outcomes, and develop an informed strategy." "Points of Law" applies machine learning to case law research so users can "[q]uickly find the leading case, the essence of a court’s holding, and the best language to support your legal argument."  

[Ravel](https://home.ravellaw.com) uses data visualization to show how the case law evolved and how legal topics cluster. Before Ravel was purchased by LexisNexus, it was a Codex Affiliate Project.  

[Wevorce](https://www.wevorce.com) provides a self-guided online divorce for a fraction of the cost of a typical divorce settlement. Along with some support from real people, an AI-powered machine guides couples through the critical decisions in their particular circumstances; like TurboTax for divorces.

### Recent Papers ###

#### &nbsp;&nbsp;&nbsp;2019 ####

- **Chat Analysis Triage Tool: Differentiating contact-driven vs. fantasy-driven child sex offenders** (2019), Kathryn C Seigfried-Spellar et al. Forensic Science International (Online); DOI:10.1016/j.forsciint.2019.02.028  
From Abstract: The Chat Analysis Triage Tool (CATT) is an investigative tool based on natural language processing methods, for analyzing and comparing chats between minors and contact-driven vs. non-contract driven offenders. Using an SVM classifier, classes were differentiated based on character trigrams. The algorithms provide an identification of an offender’s risk level based on the likelihood of contact offending as inferred from the model, which assists law enforcement in the triage and prioritization of cases involving the sexual solicitation of minors.  

- **CLAUDETTE: an automated detector of potentially unfair clauses in online terms of service** (2019), Marco Lippi et al. Artificial Intelligence and Law; Dordrecht Vol. 27, Iss. 2, pp. 117-139. [[PDF]](https://arxiv.org/pdf/1805.01217.pdf)  
From Abstract: Terms of service of on-line platforms often contain clauses that are potentially unfair to the consumer. This paper describes an experimental study where machine learning is employed to automatically detect such potentially unfair clauses. Results show that the proposed system could provide a valuable tool for lawyers and consumers.  

- **Deep learning in law: early adaptation and legal word embeddings trained on large corpora** (2019), Ilias Chalkidis et al., 27: 171. https://doi.org/10.1007/s10506-018-9238-9 [[Citation](https://link.springer.com/article/10.1007/s10506-018-9238-9)]  
From Abstract: The early adaptation of Deep Learning in legal analytics focusing on three main fields: text classification, information extraction, and information retrieval. We focus on the semantic feature representations, a key instrument for the successful application of deep learning in natural language processing. Additionally, we share pre-trained legal word embeddings using the word2vec model over large corpora, comprised legislations from UK, EU, Canada, Australia, USA, and Japan.  

- **Semi-automatic knowledge population in a legal document management system** (2019), Guido Boella et al. Artificial Intelligence and Law; Dordrecht Vol. 27, Iss. 2, pp. 227-251. DOI:10.1007/s10506-018-9239-8  [[PDF]](https://scholar.google.com/scholar?hl=en&lr=&q=Recurrent%20neural%20network-based%20models%20for%20recognizing%20requisite%20and%20effectuation%20parts%20in%20legal%20texts+author%3ANguyen)  
From Abstract: This paper proposes several recurrent neural network-based models for recognizing requisite and effectuation (RE) parts in legal text. Recognizing requisite and effectuation parts, called the RRE task, can be modeled as a sequence labeling problem. They propose a modification of the Bidirectional Long Short-Term Memory-Conditional Random Fields model (BiLSTM-CRF) to include the use of external features to improve the performance of deep learning models in case a large annotated corpora is not available.  

#### &nbsp;&nbsp;&nbsp;2018 ####

- **Automatic judgment prediction via legal reading comprehension** (2018), Shangbang Long et al. [[PDF](https://arxiv.org/pdf/1809.06537.pdf)]  

- **Automatic semantic edge labeling over legal citation graphs** (2018), Ali Sadeghian et al., Artificial Intelligence and Law; Dordrecht Vol. 26, Iss. 2, pp. 127-144. DOI:10.1007/s10506-018-9217-1 

- **CAIL2018 \[Chinese AI & Law Challenge]: A Large-Scale Legal Dataset for Judgment Prediction** (2018), Chaojun Xiao et al. [[PDF](https://arxiv.org/pdf/1807.02478.pdf)]  

- **CAIL2018: legal judgment prediction competition** (2018), Haoxi Zhong et al. [[PDF](https://arxiv.org/pdf/1810.05851.pdf)]   [[Code](https://github.com/thunlp/CAIL)]  

- **Few-shot charge prediction with discriminative legal attributes** (2018), Zikun Hu et al. [[PDF](http://aclweb.org/anthology/C18-1041)] [[Code](https://github.com/thunlp/attribute_charge)]  

- **Interpretable rationale augmented charge prediction system** (2018), Xin Jiang et al. [[PDF](http://aclweb.org/anthology/C18-2032)]  

- **Interpretable Charge Predictions for Criminal Cases: Learning to Generate Court Views from Fact Descriptions** (2018), Hai Ye et al. [[PDF](https://arxiv.org/pdf/1802.08504.pdf)] [[Code](https://github.com/oceanypt/Court-View-Gen)]  

- **Law text classification using semi-supervised convolutional neural networks** (2018), Penghua Li et al., 2018 Chinese Control And Decision Conference (CCDC), pp 309-313 [[PDF on IEEE](https://ieeexplore.ieee.org/abstract/document/8407150)]  

- **Legal judgment prediction via topological learning** (2018), Haoxi Zhong et al. [[PDF](http://www.aclweb.org/anthology/D18-1390)] [[Code](https://github.com/thunlp/TopJudge)]  

- **A Markov Logic Networks Based Method to Predict Judicial Decisions of Divorce Cases** (2018), Jiajing Li et al. [[PDF](https://ieeexplore.ieee.org/abstract/document/8513727)]  

- **A Methodology for a Criminal Law and Procedure Ontology for Legal Question Answering** (2018), Biralatei Fawei et al. [[PDF](https://link.springer.com/chapter/10.1007/978-3-030-04284-4_14)]  

- **NLP Based Latent Semantic Analysis for Legal Text Summarization** (2018), Kaiz Merchant et al. [[PDF on IEEE](https://ieeexplore.ieee.org/abstract/document/8554831)]  

- **Recurrent neural network-based models for recognizing requisite and effectuation parts in legal texts** (2018), N. Truong-Son et al., Artificial Intelligence and Law, vol. 26, (2), pp. 169-199 [[PDF](https://www.researchgate.net/publication/323989221_Recurrent_neural_network-based_models_for_recognizing_requisite_and_effectuation_parts_in_legal_texts)]  

- **Research and Design on Cognitive Computing Framework for Predicting Judicial Decisions** (2018), Jiajing Li et al. [[PDF](https://link.springer.com/article/10.1007/s11265-018-1429-9)]  

- **SECaps: A Sequence Enhanced Capsule Model for Charge Prediction** (2018), Congqing He et al. [[PDF](https://arxiv.org/pdf/1810.04465.pdf)]  

#### &nbsp;&nbsp;&nbsp;2017 ####

- **Applying Deep Neural Network to Retrieve Relevant Civil Law Articles** (2017), Anh Hang Nga Tran et al. [[PDF](https://aclanthology.info/papers/R17-2007/r17-2007)]  

- **A Convolutional Neural Network in Legal Question Answering** (2017), Mi-Young Kim et al., DOI: 10.1007/978-3-319-50953-2_20 [[PDF]](https://arxiv.org/pdf/1703.05320.pdf) 

- **Exploring the use of text classification in the legal domain** (2017), Octavia-Maria Sulea et al. [[PDF](https://arxiv.org/pdf/1710.09306.pdf)]  

- **Extracting Contract Elements** (2017), Ilias Chalkidis et al. [[PDF]](http://www2.aueb.gr/users/ion/docs/icail2017.pdf)

- **Legal Information Retrieval Using Topic Clustering and Neural Networks** (2017), Nanda1, Rohan et al. [[PDF]](https://www.easychair.org/publications/open/RC)  

- **Legal NLP Introduction** (2017), Adeline Nazarenko et al. [[PDF](http://www.atala.org/sites/default/files/1-%20TAL-58-2-legal%20NLP-introduction.pdf)]  

- **Legal Question Answering using Ranking SVM and Deep Convolutional Neural Network** (2017), P. Do et al. abs/1703.05320 [[PDF]](https://arxiv.org/abs/1703.05320)  

- **Learning to predict charges for criminal cases with legal basis** (2017), Bingfeng Luo et al. [[PDF](http://aclweb.org/anthology/D17-1289)]  [[Blog](https://bamtercelboo.github.io/2018/07/19/Learning-to-Predict-Charges-for-Criminal-Cases-with-Legal-Basis/)] 

- **Mining Legal Data: Collecting and Analyzing 21st Century Gold** (2017), K. A. Grady, Journal of Internet Law, vol. 20, (7), pp. 1-21.[[Citation]](https://www.researchgate.net/publication/313745865_Mining_Legal_Data_Collecting_and_Analyzing_21st_Century_Gold)  

- **Multi-Task CNN for Classification of Chinese Legal Questions** (2017), Guangyi Xiao et al. [[PDF on IEEE](https://ieeexplore.ieee.org/abstract/document/8119134)]  

- **An Ontological Chinese Legal Consultation System** (2017), Ni Zhang et al. [[PDF on IEEE](https://ieeexplore.ieee.org/abstract/document/8016577)]  

- **Predicting the Law Area and Decisions of French Supreme Court Cases** (2017), Octavia-Maria Sulea et al. [[PDF](https://arxiv.org/pdf/1708.01681.pdf)]

- **Text summarization from legal documents: a survey** (2017), Ambedkar Kanapala et al. [[PDF](https://link.springer.com/article/10.1007/s10462-017-9566-2)]  

#### &nbsp;&nbsp;&nbsp;2016 ####

- **Lexical-Morphological Modeling for Legal Text Analysis** (2016), Danilo S. Carvalhol et al., DOI: 10.1007/978-3-319-50953-2 [[PDF]](https://www.researchgate.net/publication/305400373_Lexical-Morphological_Modeling_for_Legal_Text_Analysis)  

- **Matching law cases and reference law provision with a neural attention model** (2016) G Tang et al., IBM China Research, Beijing [[PDF](https://scholar.google.com/scholar_lookup?title=Matching%20law%20cases%20and%20reference%20law%20provision%20with%20a%20neural%20attention%20model&author=G.%20Tang&author=H.%20Guo&author=Z.%20Guo&author=S.%20Xu&publication_year=2016)]  
From Abstract: Due to the semantic complexity of law provisions and law cases, traditional methods cannot precisely characterize the deep semantic distribution of legal cases. In this paper, we propose a neural attention model for automatically matching reference law provisions. In this proposed model, a word by word attention mechanism is used to calculate pairwise comparisons between cases and law provisions, and then an output LSTM layer is used to summarize the comparisons and output the labels.  

#### &nbsp;&nbsp;&nbsp;2014 ####

- __Machine Learning and Law__ (2014). Harry Surden, Washington Law Review, Vol. 89, No. 1, (March 26, 2014). [[PDF](https://ssrn.com/abstract=2417415)]  
From Abstract: This Article explores the application of machine learning techniques within the practice of law. Broadly speaking “machine learning” refers to computer algorithms that have the ability to “learn” or improve in performance over time on some task. In general, machine learning algorithms are designed to detect patterns in data and then apply these patterns going forward to new data in order to automate particular tasks. If performing well, machine learning algorithms can produce automated results that approximate those that would have been made by a similarly situated person.  

----------
### Current Project ###

My current work employs NLP techniques to classify and compare text in Washington state's statutes, the Revised Code of Washington (RCW), and opinions from the Washington State Supreme Court.  

Project details to be updated.  

### Future Work ###
Possible areas of future study:  
- improving access to annotated versions of statutes, ordinances, and regulations
- augmenting legal text with definitions and summaries available on demand as the user reads the text
- merging related laws together to provide a more thorough summary of the applicable laws on demand in response to a user's question
