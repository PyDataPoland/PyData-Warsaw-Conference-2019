#### [The Ethics of Artificial Intelligence - What developers should know](https://pydata.org/warsaw2019/schedule/presentation/22/ethics-artificial-intelligence-what-developers-should-know/) - Vince Madai
##### Description
In my talk I will explore the ethics of artificial intelligence. I will introduce morality and ethics and will give examples in which areas artificial intelligence - or better phrased machine learning - is leading and will lead to ethical challenges. I will focus in my talk especially on the developer´s perspective: What are special ethical challenges developers will be facing.
##### Abstract
In my talk I will explore the ethics of artificial intelligence. I will introduce morality and ethics and will give examples in which areas artificial intelligence - or better phrased machine learning - is leading and will lead to ethical challenges. I will focus in my talk especially on the developer´s perspective: What are special ethical challenges developers will be facing and how can they prepare? How can students and developers be trained to spot ethical challenges and how can they solve them?

#### [Trusted AI – Building Reproducible, Unbiased and Robust AI Pipelines using the python OpenSource sta](https://pydata.org/warsaw2019/schedule/presentation/23/trusted-ai-building-reproducible-unbiased-and-robust-ai-pipelines-using-the-python-opensource-sta/) - Romeo Kienzler
##### Description
Untrusted AI doesn’t make it into production. The concerns are just too high. In this talk we’ll show how data lineage, bias detection, adversarial robustness and model explainability can be achieved using an open source stack
##### Abstract
Untrusted AI doesn’t make it into production. The concerns are just too high. In this talk we’ll show how data lineage, bias detection, adversarial robustness and model explainability can be achieved using an open source stack

#### [Disease Modeling with Scipy and PyMC](https://pydata.org/warsaw2019/schedule/presentation/1/disease-modeling-scipy-and-pymc/) - Dean Langsam
##### Description
Programs which aim eradicate disease must rely on interpretable models. These models quickly become hard to solve, not to mention train on missing parameters. Scipy and PyMC come to our rescue for the heavy lifting.
##### Abstract
In 2018, Israel has seen the biggest outbreak of measles since the introduction of a vaccine in the late 1960s. Nowadays, vaccine policies are not only decided by laboratory tests. Those tests are complemented by a plethora of computational epidemiology simulations predicting the effects of various vaccination policies on the entire population. A population-level policy to eradicate disease must rely on Interpretable models. These models quickly become hard to solve, not to mention train on missing parameters. Using Scipy as a solver, and PyMC for Bayesian inference we are able to learn parameter distributions for missing natural parameters, such as the disease's "strength" or "infectiousness". We can then use the underlying distributions for these parameters in order to simulate possible outcomes for future policies.

#### [Transfer learning for image recognition in healthcare industry](https://pydata.org/warsaw2019/schedule/presentation/8/transfer-learning-image-recognition-healthcare-industry/) - Michał Kierzynka
##### Description
Transfer learning is a powerful technique to boost the performance of a deep learning model. However, the healthcare industry often has very specific image data sets that are dissimilar to the large-scale data sets used to pretrain the publicly available models. Therefore, are there any benefits of applying transfer learning in healthcare? Come and listen to find out.
##### Abstract
The idea of transfer learning is to reuse features learned on a related task to improve the performance of a model on a new task. The advantages of transfer learning are well known: faster training, less labeled data needed and higher accuracy of the final model. Therefore, the use of pretrained models became a de facto standard in many practical applications, among others in computer vision. This is all under the assumption that the features learned on the source task are generic enough to be reused on a target task. However, the healthcare industry often has very specific data sets that are rather dissimilar to the large-scale and publicly available data sets used to pretrain the models. The goal of the presentation is to show if there are any advantages of using pretrained models in such settings.  To find out, we have designed a dedicated experiment in which we compare the performance of various CNN architectures applied to different medical imaging data sets, both public and private. We initialize the models either randomly or with ImageNet pretrained parameters with various settings. We also compare the results to the performance of a small, custom designed CNN networks.  The presentation will have the following outline. First, the audience will be introduced to the transfer learning and its variants. Later, the design of the dedicated computational experiments will be presented, followed by the results and conclusions. The latter will be compared to the conclusions from the latest state of the art papers on the topic.  The participants will have a unique opportunity to learn about the benefits and pitfalls of applying transfer learning to imaging data sets that are much more specific than natural images from ImageNet.  Background knowledge required to understand the presentation: intermediate knowledge about machine learning, deep learning and CNNs.

#### [Geospatial analysis made easy with PostGIS and Geoalchemy](https://pydata.org/warsaw2019/schedule/presentation/16/geospatial-analysis-made-easy-postgis-and-geoalchemy/) - Nicolas Pierre
##### Description
Using geospatial data is easier than ever. Data can easily be found on open data portals or simply on Open Street Map. But how can we use this data? What kind of tools are there to store and analyse this data in an optimal manner? During this talk we will answer these questions. We will discuss particularly about PostGIS, an extension of PostgreSQL database, and GeoAlchemy, a Python library.
##### Abstract
Erik Brynjolfsson, a professor at MIT, once said that "Every time we invent something, we make it easier to invent something else". That is probably especially true in the digital space, given the pace at which technology is evolving. While working on a pricing model that is evaluating the price of apartments in Italy, based on information such as location, size or status, we realized that it would be very useful to have more information about the area where the apartments are located. This helped us discover that finding open geospatial data is not very difficult these days, but processing and storing it require some particular skills and tools. PostGis is an open source extension of the PostgreSQL Database Management system that allows users to store geospatial data as specific data types (geometries and geographies). In addition, it helps the user handle this data using some specific spatial functions such as distance, area, etc. SQLAlchemy is a SQL library of Python implementing an object-relational mapping concept. The advantage of this library is that developers no longer need to write SQL queries in their Python code when working with a database, but they can write Python classes instead that are translated to SQL statements. GeoAlchemy is an extension of SQLAlchemy that facilitates working with spatial databases, such as PostGIS. During this talk we will shortly talk about the use-case that required the use of the tools mentioned above and walk you though an example using data from Open Street Map, stored in geojson files. Our aim is to raise awareness in the audience about how geospatial data can be manipulated and stored using Python and open source database management systems. The talk is aimed at scientists and developers interested in working with geospatial data using Python. There are no advanced topics in the talk, but in order to get most of the talk you should have some knowledge of Python and SQL.

#### [The NLU Orchestra](https://pydata.org/warsaw2019/schedule/presentation/2/nlu-orchestra/) - Amit Beka
##### Description
Building a NLU application like a chatbot seems easy nowadays, but getting it right architecturally is harder than expected. Let's dive into the problems I've encountered and an elegant-yet-simple solution to make it really work. We'll look at understanding conversation not as a pipeline, but as an orchestra of many components playing together towards a shared goal.
##### Abstract
For the last 6 years I've been working on a complex NLU system to understand human discourse, and have seen many approaches and promises to solve it "easily". This talk will unfold the journey of our architecture from a simple pipeline to more complex solutions, highlighting the difficulties of current approaches to tackle real conversations with real users.  Looking at the problem from a different angle, we'll develop an elegant structure of NLU applications as an orchestra of many components.  The proposed solution naturally handles many problems:

* Changing requirements, like new intents or entities  
* Non-linear dependencies between components  
* Using the full conversation as context

#### [keras-fsl: Fast model builder for production ready few shot learning algorithms](https://pydata.org/warsaw2019/schedule/presentation/10/keras-fsl-fast-model-builder-production-ready-few-shot-learning-algorithms/) - Dr. Clément Walter
##### Description
Few shot learning aims at leveraging huge database for training deep neural nets models to be used onto problems with very few data. Among other methods we will focus on metric learning algorithms because they allow for immediate adaptation of the model in production. To develop such model, fast experiment is key; we will present a versatile framework for their implementation in tf.keras.
##### Abstract
Most of the industrial cases we face do not have enough data to allow for a complete end-to-end training of common deep architecture. Furthermore research paper often do not address real test cases. In this context there is a need for easy benchmarking of usual and custom models onto ones particular datasets.  Furthermore best academic performers may not the preferred choice for production applications as simplicity, robustness and explicability are other factor of interest. Thus the need for a modularity in the implementation to be able to mix the best of them to improve practical results.  We will review some recent theoretical development in Few Shot learning and show their corresponding implementation in tf.keras. Finally I will showcase the keras_fsl package with public notebooks and key results on usual benchmarks.

[Slides](https://docs.google.com/presentation/d/12wExXxVqFm6oR3PNf8wvRAmRZKQsYJj1IiIGCd8Kd-4/edit?usp=sharing)

#### [How to structure PySpark application](https://pydata.org/warsaw2019/schedule/presentation/9/how-structure-pyspark-application/) - Przemek Chrabka
##### Description
A lot of the Data Scientists and Engineers don’t come from Software Engineering background and even they have an experience with writing spark code they might luck the knowledge about application structure principals. This talk is designed to help them write better and more readable code.
##### Abstract
PySpark has become really popular for last couple of years and is now a go-to tool for building and managing data-heavy applications. One of the most common ways how Spark is used is moving some data around by writing ETL/ELT jobs. Doing that your code should be manageable and understandable to others. In this talk I will try to introduce good practice how to structure PySpark application and write jobs and also some naming conventions.  I will start this talk with an example of bad way of writing PySpark job and during the course of it we will gradually improve it so at the end our application is going to be production ready, easy to manage and share with other developers.  During this talk I will try to answer this questions: - How to structure PySpark ETL application - How to write ETL job - How to package your code and dependencies - What are some coding and naming conventions

#### [Reproducible Machine Learning](https://pydata.org/warsaw2019/schedule/presentation/3/reproducible-machine-learning/) - Mateusz Opala
##### Description
Reproducibility is a cornerstone of scientific methods. Especially in production Machine Learning it's crucial to ensure that hidden source of randomness is not a real reason for a model performance improvement. In my talk I will elaborate on importance of reproducibility and show how we build reproducible machine learning pipelines at Netguru.
##### Abstract
Reproducibility is a cornerstone of scientific methods. Especially in production Machine Learning it's crucial to ensure that hidden source of randomness is not a real reason for a model performance improvement. Although, reproducibility in building machine learning papers seems to be must-have, it's still not a standard.  Outline of talk:
1. Definitions:
   * reproducibility
   * replicability
   * generalisability
2. Motivation for achieving reproducibility
3. Full reproducibility == Continuous Delivery for ML
4. Changes in ML development process 
   * code
   * data
   * models   
5. How we managing change in ML development process?   
6. Data versioning
   * Quilt Data   
7. Experiments management
   * MLFlow / Polyaxon   
8. Summary

#### [How to numerically represent semi-structured log data for anomaly detection?](https://pydata.org/warsaw2019/schedule/presentation/11/how-numerically-represent-semi-structured-log-data-anomaly-detection/) - Marcin Kowiel
##### Description
Representation of text data from semi-structured log records is a challenging problem that is crucial for the quality of anomaly detection engines. In the presentation, I will show a pipeline to create vector embeddings and normalization rules on semi-structured, text data that could be used in anomaly detection problems.
##### Abstract
Semi-structured data such as server logs or system activity metadata is key to detect cybersecurity threats or security breaches. At F-Secure, we apply a variety of machine learning methods to detect anomalies in the stream of semi- structured text-based events to protect our customers. However, many advanced techniques require a numerical representation of text data (file paths, program names, command line arguments, registry records). The most popular methods (one-hot-encoding and simple embeddings) do not capture the specific context and semantics of log data. Typically, when processing the log data, the vocabulary is much bigger than in natural languages. Moreover, we need to identify and normalize randomly generated paths, temporary files, software versions or command-line arguments.  I will present a pipeline to create vector embeddings and normalization rules on semi-structured data using the popular natural language processing (NLP) Word2Vec model. At the end I will show a simple anomaly detection engine that uses the embeddings to find potentially malicious activity. If you are interested in cybersecurity, NLP or log processing you should find it appealing.

#### [Modern Machine Learning flow with Quilt and Polyaxon](https://pydata.org/warsaw2019/schedule/presentation/17/modern-machine-learning-flow-quilt-and-polyaxon/) - Robert Kostrzewski
##### Description
Presentation of development flow dedicated to Machine Learning internal and external projects including datasets storage and versioning via Quilt (as an alternative to DVC), experiments scheduling and infrastructure maintenance via Polyaxon, continuous Integration using CircleCI and Configuration & deployment using Docker.
##### Abstract
The talk is about presenting a development flow dedicated to Machine Learning internal and external projects, practiced in our company (Netguru). The flow includes following parts:   
* Machine Learning datasets storage and versioning via Quilt (as an alternative to DVC)  
* Experiments scheduling and infrastructure maintenance via Polyaxon  
* Continuous Integration using CircleCI  
* Configuration and deployment using Docker.  Presentation describes of all components and explains how to put it together. Given Machine Learning flow impacted on on our projects' success stories. Further part of the talk would explain why it was so crucial to build and maintain it.

#### [TrashAsistant: A kivy App, which uses Deep Neural Networks, for helping trash segregation](https://pydata.org/warsaw2019/schedule/presentation/28/trashasistant-kivy-app-which-uses-deep-neural-networks-helping-trash-segregation/) - Olgun AYDIN
##### Description
We have developed a mobile application using kivy framework. It uses Deep Neural Networks to help segregating trashes. Thanks to this app, before throwing trash to specific bin, you will know which trash bin you should throw to. Only thing you will do is just taking a photo of the trash via the app.
##### Abstract
Municipality in Gdansk started to be really strict about segregating trash last year. They are checking segregating performance of residential buildings and providing opportunity to pay less tax to those people who live in the buildings which have better segregation performance. Also, they are fining companies which don't follow the segregation instructions. Even though, instructions are well defined still sometimes people are confused to decide which trash bin they should use. For example, empty carton of milk seems like it should go to the bin for paper, but actually it should go to the bin for plastic and metals.  We have realized that having a mobile app which will guide people about this purpose would be very helpful. We have developed deep neural networks(DNN) using transfer learning. DNNs have been trained by using keras Python library. After having good performed model, kivy app has been developed.  In this speech, we would like to talk about transfer learning, Python keras library, kivy framework, obstacles we had and future plans about additional features to the application.

#### [Sound Modelling - parametric methods and deep learning representations to create and shape audio](https://pydata.org/warsaw2019/schedule/presentation/12/sound-modelling-parametric-methods-and-deep-learning-representations-create-and-shape-audio/) - Pawel Cyrta
##### Description
Sound in digital form for years is in the loop of steps: record, mix, edit, playback and listen. Some creative ones did create synthetic speech and music with affordable tools. Now both computation and data resources available made synthesis and sound shaping possible using parametric, physical methods or with the latest deep learning representation models. Discover the theory and code to do it.
##### Abstract
Sound in digital form for years is in the loop of steps: record, mix, edit, playback and listen. Some creative ones did create synthetic speech and music with affordable tools. Now both computation and data resources available made synthesis and sound shaping possible using parametric, physical methods or with the latest deep learning representation models. Discover the theory and code to do it.  Techniques like deep learning can now create a whole set of basic audio processing functions - filtering, equalization, compression - are becoming available to model too. They can also extract latent representation and make it be controlled to produce real sound. One can create his own replica for specific guitar amplifier sound or try to find parameters that produces unique audio for film or game sound effects.  We will take a quest to find out how to model sound by exploring and running experiments with python code. The experiment consists of three main parts:
1. Exploration how to get audio data and represent it using equations and recent deep learning models.
2. Analysis by visualization, clustering.
3. Mimicking real vibrations by approximation using parametric physical models .
4. Grab DNN models to make them speak, play and sing.

In addition, I will describe the model used, present the code the results that perform audio out of the model.  In summary, at the end of this talk you will have learned (I hope) how deal with sound signals and that it may be combined to create music or just bizarre, wacky sounds

#### [Automation: Build A Training Pipeline](https://pydata.org/warsaw2019/schedule/presentation/18/automation-build-training-pipeline/) - Varun Kochar
##### Description
Many of us knows how to train & deploy ML models in cloud, but doing so have we become redundant. Running multiple experiments in single machine & waiting for tasks to complete cannot be time-efficient for big datasets. Hence, we need an automation which can take over repetitive manual tasks & spare us the time to do other important stuff. Aim is to show how to deploy ML architecture in 60 SECONDS
##### Abstract
ML pipeline consists of many manual tasks such as Data collection, Data cleaning, training environment setup, training configuration, monitoring progress or model evaluation gig, all these components should be automated & what you should be left with is just a single CONFIGURATION document with information of different set of experiments.

#### [Posterior Collapse in Deep Generative models](https://pydata.org/warsaw2019/schedule/presentation/5/posterior-collapse-deep-generative-models/) - Michał Jamroż
##### Description
Generative models are powerful Machine Learning models useful at extracting information from high-dimensional data, but they sometimes suffer from the problem called "posterior collapse" which prevents them from learning representation having practical value. I am going to show why and when it happens, also how to deal with it.
##### Abstract
**Why**  Deep generative models like Variational AutoEncoders (VAEs) and Generative Adversarial Networks (GANs) turned out to be very successful in real-world applications of machine learning, including: natural image modelling, data compression, audio synthesis and many more. Unfortunately, it appears that models belonging to VAEs family - under some conditions may suffer from an undesired phenomenon called "posterior collapse" which causes them to learn poor data representation. The talk's purpose is to present this problem and its practical implications.  **What**  The presentation will comprise following elements:   
* Short introduction of basic Variational AutoEncoder model  
* Introducing the "posterior collapse" problem  
* How posterior collapse affects learning from data - natural images examples  
* Some research on dealing with posterior collapse  

**Audience**  Being familiarised with the topic of generative modelling will be helpful for anyone attending the talk, but it's not required. In fact, everyone having basic understanding of neural networks, representation learning and probability can gain useful information. Presentation won't be overloaded with mathematical formulas, I will do my best to present math-related aspects in an intuitive form.

#### [Generative Text Modelling: Scratching the surface](https://pydata.org/warsaw2019/schedule/presentation/13/generative-text-modelling-scratching-surface/) - Tomasz Dziopa
##### Description
Recent progress in generating natural language text catches media attention. Are we about to get flooded by autogenerated fake news? Let's learn about approaches to machine-generated text. Get a high level idea of how can you apply basic approaches like N-grams, HMMs as well as advanced ones such as RNNs and VAEs. We'll apply those methods to real-world datasets of Polish articles from Wikipedia.
##### Abstract
Recent progress in generating natural language text sparks controversy and catches global media attention. Are we about to get flooded by machine- generated fake news? Are we on the edge of a completely new level of troll farms about to emerge? In this talk I will go over approaches to machine- generated text. You will get a high level idea of how can you apply basic approaches like N-grams, Hidden Markov Model as well as advanced ones such as RNNs and Variational Autoencoders. We will cover the main challenges like methods of evaluation, and potential use cases. We will also have fun applying aforementioned methods into real world datasets of Polish articles from Wikipedia.

#### [ML model from an idea to production with the help of Python](https://pydata.org/warsaw2019/schedule/presentation/19/ml-model-idea-production-help-python/) - Martyna Urbanek-Trzeciak
##### Description
We will talk about how Python can be helpful in the machine learning projects on every step of the process starting with the idea where data-driven predictions can be helpful, through data preparation, data modelling, communication of the results using various visualizations and implementation on production including monitoring of model performance.
##### Abstract
We will talk about how Python can be helpful in the machine learning projects. We will consider every step of the process starting with the idea where data- driven predictions can be helpful, through data preparation, data modelling, communication of the results using various visualizations and implementation on production including monitoring of model performance. I will mention various Python libraries that can be of use on each step and consider real use cases to dive deeper into some of the mentioned steps. During the talk I will also mention open source Python library for easy data access that we develop in Fandom.

#### [Learning to rank with the Transformer](https://pydata.org/warsaw2019/schedule/presentation/6/learning-rank-transformer/) - Tomasz Bartczak, Radosław Białobrzeski
##### Description
Learning to Rank (LTR) is concerned with optimising the global ordering of a list of items, according to their utility to the users. In this talk, we present the results of ongoing research at Allegro.pl into applying the Transformer architecture known from Neural Machine Translation literature to the LTR setting and introduce allRank, an open-source, Pytorch based framework for LTR.
##### Abstract
Self-attention based architectures fuelled recent breakthroughs in many NLP tasks. Models like The Transformer, GPT-2 or BERT pushed the boundaries of what's possible in NLP and made headlines along the way. Self-attention mechanism can be seen as an encoder for an unordered set of objects, taking into account interactions between items in the set. This property makes self- attention mechanism an attractive choice for Learning to Rank (LTR) models, which usually struggle with modelling inter-item dependencies.  In this talk, we present the results of ongoing research in applying self- attention based architectures to LTR. Our proposed model is a modification of the popular Transformer architecture, adapted to the LTR task. We guide the audience into both the setting of LTR and its most popular algorithms as well the details of self-attention mechanism and the Transformer architecture. We present results on both proprietary data of Allegro's clickthrough logs and most popular LTR dataset, WEB30K. We demonstrate considerable performance gains of self-attention based models over MLP baselines across popular pointwise, pairwise and listwise losses. Finally, we present allRank, an open- source, Pytorch based framework for neural ranking models. After the talk, the audience will have a good understanding of the basics of LTR and its importance to the industry, as well as will see how to get started in training state-of-the-art neural network models for learning to rank using allRank.

#### [In the service of the history. AI in archivistics.](https://pydata.org/warsaw2019/schedule/presentation/14/service-history-ai-archivistics/) - Adrian Boguszewski
##### Description
A trillions of old photos are a valuable source of information about the past. Unfortunately most of them are not described sufficiently or at all. Imagine Artificial Intelligence as a friend of the archivist of the 21st century. This is the end of unlabeled photos epoch.
##### Abstract
1839 is a data generally accepted as the birth year of practical photography. Since then mankind produced about 10 quadrillions of photos including 1 quadrillion only last year. This huge amount of unlabeled an undescribed data is a problem, if we want to obtain important information quickly and efficiently. Old photos are extremely valuable, because they contain a lot of data about the past. However some expertise and experience is needed to properly describe such images. What if we include all this knowledge into neural networks? Can AI become a friend of the 21st century archivist? Let’s talk about automatic image tagging and faces recognition in old photos.

#### [TDD shouldn't be TDDious](https://pydata.org/warsaw2019/schedule/presentation/20/tdd-shouldnt-be-tddious/) - Chris Sidebottom
##### Description
An introduction to applying TDD in a Data world. Taking the experience of traditional TDD from a Web Development background and translating it into useful techniques for Data Scientists. Hopefully by the end of this talk TDD will be far less of a buzzword and you'll enjoy applying it more yourself!
##### Abstract
Beginning by introducing how I learnt TDD (Test Driven Development) from Web Development. I’ll walk through how the traditional way of using TDD sometimes doesn’t apply to Data Science. By exploring examples of data-oriented TDD, I’ll show that even though TDD is a rigorous practice, it can also be fun. And how TDD can provide you with more space to explore how to build software.  Building upon the data testing, we’ll look at how to apply TDD to machine learning models and why it’s tricky to build deterministic tests for them. Then we’ll bring it altogether with pipeline testing, how it can be difficult and ways to create tests that proxy it. I'll also cover when not to use TDD, as that can ruin the fun.  By the end of the talk, you should have ideas for implementing TDD in your workflow with data. And ways to convince people to play along with you!

#### [Analysing Russian Troll Tweets data with Python](https://pydata.org/warsaw2019/schedule/presentation/7/analysing-russian-troll-tweets-data-python/) - Mia Polovina
##### Description
This talk focuses on the insights gathered from analysis of Russian Troll Tweets, a dataset created by researchers at Clemson University and released on Github by FiveThirtyEight.
##### Abstract
Social media sites are increasingly used for propagation of misinformation. Recent efforts include sophisticated campaigns run on Facebook and Twitter which aimed to interfere in the 2016 US elections and politics. This talk will focus on a campaign that saw trolls engaged in such efforts on Twitter. Insights obtained with Exploratory Data Analysis (EDA) and text analysis of Russian Troll Tweets dataset will be presented. The talk will also highlight the importance of combating misinformation and computational propaganda.

#### [What's coming in Apache Airflow 2.0](https://pydata.org/warsaw2019/schedule/presentation/15/whats-coming-apache-airflow-20/) - Jarek Potiuk
##### Description
Apache Airflow is one of the most popular Data processing orchestration engines. After a long line of 1.10.x releases in December we wil be quickly approaching 2.0 release. The release is not backwards compatible and it will contain many improvement and changes. This talk will outline the most important changes coming in Apache Airflow 2.0.
##### Abstract
Jarek - as an Apache Airflow PMC member and one of the more active members of Apache Airflow community will talk about what is coming in Apache Airflow 2.0. The Apache Airflow 2.0 is not backwards compatible and the community puts a lot of effort into cleaning up, refactoring and improving the code and building functionaliities that are going to make life easier for the users of this - one of the most popular - orchestration engine for Data and Machine Learning processing jobs. Some of the most long-standing requests from the community, such as DAG serialisation to database and stateles webserver are only scratching the surface of what's coming in Airflow 2.0.  This talk will be targeted mainly for Apache Airflow users who would like to learn what can they do with the upcoming Airflow 2.0 as well as how to migrate to Apache 2.0 i painlessly. It will also be a unique opportunity to provide feedback on early versions of Apache 2.0 that will be available by then and discuss your proposals and questions with an Apache Airflow Commiter, so there will be plenty of time for questions - during and after the talk.

#### [Unsupervised learning for news summarisation](https://pydata.org/warsaw2019/schedule/presentation/21/unsupervised-learning-news-summarisation/) - Jakub Kubajek
##### Description
With hundreds of articles published every day, it is hard to keep track of the main issues in the media. However, the unsupervised learning may help to identify the most relevant information.
##### Abstract
Why should we read news sites if we can automatically extract the most important information?  During the talk, I will present how to identify and summarise the most important topics appearing on news sites. I will cover theoretical and practical aspects of LexRank and other unsupervised methods that may be used to identify key topics in media on a particular day.

#### [Transfer Learning - Entering a new era in NLP](https://pydata.org/warsaw2019/schedule/presentation/24/transfer-learning-entering-new-era-nlp/) - Malte Pietsch
##### Description
Transfer learning has been changing the NLP landscape tremendously since the release of BERT one year ago. Transformers of all kinds have emerged, dominate most research leaderboards and have made their way into industrial applications. In this talk we will dissect the paradigm of transfer learning and its effects on pipelines, modelling and the engineers mindset.
##### Abstract
Sufficient training data is often a bottleneck for real-world machine learning applications. The computer vision community mitigated this problem by pretraining models on ImageNet and transferring knowledge to the desired task. Thanks to an emerging new class of deep language models, transfer learning has also become the new standard in NLP. In this talk we will share strategies, tips & tricks along all model phases: Pretraining a language model from scratch, adjusting it for domain specific language and fine-tuning it for the desired down-stream task. We will demonstrate the practical implications by showing how models like BERT caused major breakthroughs for the task of Question Answering.

#### [Machine Learning can't do the thinking](https://pydata.org/warsaw2019/schedule/presentation/25/machine-learning-cant-do-thinking/) - Inga Strumke
##### Description
Inga is going to share her most serious as well as most recent thoughts on AI in today’s world and the future, namely why we (unfortunately) should not worry about AGI, but definitely should think hard about data and AI ethics.
##### Abstract
Inga is going to share her most serious as well as most recent thoughts on AI in today’s world and the future, including why we will probably not have the privilege to worry about AGI in the near future, how to achieve world domination using data like the Medici family used numbers, why we should be inspired by containers in the shipping industry, and how to code our way to tomorrow’s ethics - assuming that the world is a closed system. This is a talk to be inspired and discuss!

#### [Anyone can Build Great Deep Learning Applications - Deep Numpy](https://pydata.org/warsaw2019/schedule/presentation/44/anyone-can-build-great-deep-learning-applications-deep-numpy/) - Cyrus Vahid
##### Description
As deep learning becoming prevalent in adoption of practical AI, it is important to lower barrier to entry for DL adoption for the developer community. This can be done by 1) retaining and reusing existing and popular libraries as much as possible and employing them in development of DL applications, and 2) Automating model development as much as possible though usage open source AutoML tools.
##### Abstract
Deep Numpy enhances Numpy by adding GPU support and parallel processing to it, while aspiring to remain 100% numpy compatible. It enables easy-to-use and easy-to-extend AutoML with a focus on deep learning, and making AutoML deploy in real-world applications.  In this talk, we focus on the use of Deep Numpy and AutoGluon for rapid development of DL models.

#### [Command line language – where NLP and cyber security meets](https://pydata.org/warsaw2019/schedule/presentation/30/command-line-language-where-nlp-and-cyber-security-meets/) - Zuzanna Kunik
##### Description
In the cyber security world, analysis of command line logs is important for breach detection, but it is one of the most challenging problems. To simplify this process, we propose a framework called CMDLang – command line language, which has features of natural language. I will present results of successful POS and NER training using popular NLP algorithms and demonstrate a real use case of CMDLang
##### Abstract
At F-Secure, in order to protect our customers, we use streams of command line logs coming from their systems to detect breaches and anomalies. Analysis of such data is one of the most challenging problems in the cyber security world. It requires domain knowledge and is hard to encapsulate in sets of rules.  What if we treat command lines logs as semi-structured text data? They follow a set of grammar rules and have semantics. Therefore, we propose the framework of CMDLang – command line language, which has features of natural language. We performed successful trainings of part of speech (POS) tagger and named entities recognition (NER) models. Using CMDLang along with NLP methods enables normalization of logs, parsing and their categorization. With a defined language framework, we are able to analyze huge streams of data faster, which improves our detection capabilities.  During the talk, I will present results of the CMDLang creation using popular, open-source NLP algorithms. I will give a walkthrough of the process and define the main ideas behind this language. At the end I will demonstrate usage of CMDLang in a real use case.  This talk will be interesting for every NLP enthusiast, as well for people working with (semi-)structured text data or log processing. During the presentation, I will explain any cyber security terminology used.

#### [How we personalized onet.pl with multi-armed bandits](https://pydata.org/warsaw2019/schedule/presentation/35/how-we-personalized-onetpl-multi-armed-bandits/) - Artur Bujak
##### Description
Imagine you need to choose ten articles out of hundreds in a way that maximizes your profit. It's not as easy as it seems. In this talk, we will explain how we prepare recommendations on the onet.pl home page for millions of users with the use of a multi-armed bandit algorithm.
##### Abstract
Multi-armed bandits are a powerful solution for a diversity of optimization problems that demand a balance between using existing knowledge about item performance and acquiring new one. That's why we would like to focus on the intuition behind the multi-armed bandit approach and its application in recommender systems on the example of onet.pl home page. Also, we will introduce E-greedy, UCB and Thompson Sampling bandits, discuss their pros and cons and show how to tune them in a simulated environment.

#### [How to manage data-related projects and not fail (too often)?](https://pydata.org/warsaw2019/schedule/presentation/26/how-manage-data-related-projects-and-not-fail-too-often/) - Jakub Nowacki
##### Description
Up to 85% of data-related projects fail. Most of that is due to ill management of these projects, and no one-size-fits-all solution (not even agile), can solve the problem. I want to share what I learned so far: from experience but also from good books and articles, start and promote a wider discussion on the data-related project and people management, and how we can help ourselves.
##### Abstract
Depending on estimates between 60% and 85% of Big Data projects fail; we see similar numbers for AI/ML projects. Why is that? Have you ever been on a good- looking project that didn't deliver or was abruptly closed? A lot of that has to do with management, and if you think product based on software development was hard, data-related projects are even harder. In this talk I will combine my experience of being a part of or running teams in a few data-related projects, spanning from big data engineering to machine learning engineering in organization of a different size. I will tell you about my successes and failures, how I feel the data-related projects are perceived by the business and what can we do about this. The ideas and experience are backed by a number of books, articles and methods circulating around in the community. You will learn not only what you can do as a manager, but also as a team member. Also, that Agile is good, but is also not one-size-fits-all solution, and what is better to pass. By no means I feel as a know-it-all person in management, I just want to share what I learned so far, start and promote a wider discussion on the data-related project and people management, and how we can help ourselves.

#### [How to effectively extract image features – let’s play with OpenCV API!](https://pydata.org/warsaw2019/schedule/presentation/31/how-to-effectively-extract-image-features-lets-play-with-opencv-api/) - Filip Geppert
##### Description
Talk is an introduction to OpenCV 4+ pythonic API. We are going to go through most popular methods that are used in image processing and computer vision apps. We will also explore new methods that have been added in the newest release of the package. No prior OpenCV knowledge is required to participate.
##### Abstract
######Intro & added value

Image processing and computer vision are gaining huge interest nowadays. Modern machine learning models very often take advantage of features calculated on images. The talk is an introduction to the most popular pythonic image processing package → OpenCV.  You will learn the most important concepts in computer vision, and see how these are applied on images. After this talk you will be ready to start your first computer vision project!  
###### Topic a.k.a. come if you:

The talk is addressed to Data Scientists, Python Developers and Data Engineers that would like to see what OpenCV package offers and if it’s the right tool to learn. I will provide a lot of examples explaining how image/video processing and feature extraction can be done in OpenCV.  
###### The type of talk  

All code examples will be shared afterwards through GitHub repository. During the talk, presentation will be either done with the help of Jupyter Notebook or interactive slides (to simulate the programming process).  

###### What you will learn
1. Intro to key image processing methods, such as: 
   * thresholding techniques
   * colorspace conversion
   * contour detection
   * image filtering
   * morphological transformations
   * arithmetic with images
   * color histograms
   * shape detection
   * template matching
   * new methods that have been added since the release of 4.0 version.   
2. How these methods are applied with the use of OpenCV 4+ api.
3. Tips&tricks to speed up image processing and feature extraction development time.

#### [How to efficiently model learner’s knowledge with recurrent neural networks](https://pydata.org/warsaw2019/schedule/presentation/36/how-to-efficiently-model-learners-knowledge-with-recurrent-neural-networks/) - Mateusz Otmianowski
##### Description
During our presentation we will share the results and experiences connected with implementing state-of-the-art techniques for modelling learners knowledge using Recurrent Neural Networks (Deep Knowledge Tracing).
##### Abstract
Knowledge Tracing (KT) is one of the most important research areas in personalized education nowadays. It allows us to trace learners’ knowledge over time so that we can accurately predict how they will perform in the future. By improving the quality of such models we can better adjust the adaptive learning experience to the needs of particular students. In recent years the idea of using recurrent neural networks for learners knowledge tracing (Deep Knowledge Tracing, DKT) gained a lot of attention, as it has been shown that it generally outperforms traditional methods. During our presentations we will share the results and experiences connected with implementing this method in one of the Pearson personalized learning products. We will focus on challenges that we have encountered during the model development process related to the framework we’ve used (TensorFlow), training performance, experiment tracking and having multiple people working simultaneously on the same model. We’ll also share the results and compare them with the state of the art results from other papers.

#### [Visual Search @ allegro.pl](https://pydata.org/warsaw2019/schedule/presentation/27/visual-search-allegropl/) - Marcin Tuszyński
##### Description
During this talk, I will share my experience gathered during the development of Allegro's visual search engine. I will present our entire journey from the plain idea through different modelling approaches up to its current solution. Finally, I will provide some tips and tricks that we have learned along the way and show a lot of images - after all, that's what you're looking for!
##### Abstract
How can one effectively find a recently seen t-shirt on an e-commerce platform such as Allegro? Or maybe an unusual set of cups, that is used by the coffee shop downstairs? One could try to describe them, but a picture is worth a thousand words - what if that one picture or actually a photo was enough? With over 100 million offers and with multiple photos for every product, this seems nearly impossible. Especially given how similar some products are. During this talk, I will share how we make it possible by introducing a visual search model. I will focus on our machine learning model and its evolution over time but also cover some technical aspects of our approach.

#### [Predicting flight compensation - a case study](https://pydata.org/warsaw2019/schedule/presentation/32/predicting-flight-compensation-case-study/) - Adam Witkowski
##### Description
Under EU law, airplane passengers have the right to be compensated if their flight is sufficiently delayed. GIVT helps passengers file such claims. Every claim needs to be verified as there are various conditions that can invalidate it: extreme weather, strikes, bird hit, etc. In this talk, I will describe a machine learning system which replaces manual verification of claims.
##### Abstract
This talk describes the process of implementing a machine learning model in production. I will talk about various problems that we encountered and how we solved them.  First, I will describe the problem: verification if the airline should compensate the passenger for the flight. This depends on many factors, some of which are easy to define (is the flight delayed more than 180 minutes? is the airline from EU?) and some are not (is the weather bad enough to invalidate the claim? is there a strike?). Of course, with perfect data, those questions would be very easy, but in practice we do not have the luxury of working with ideal data. For example, the weather reports are not available in real time and we know they are available for the airports, not the whole route of the flight. I will tell you what data we had and what features we extracted from it.  Then I will briefly describe the algorithms we used and why, unsurprisingly, we ended up using GBM. After the model was ready, we ran it in parallel to manual verification for several weeks so the predictions of the model could be compared to human work. One important aspect of running the model in production is explaining the model decisions to the verification team (and end users). I will talk about techniques that can be used to 'explain' the model's decision, for example, SHAP.  The main value of my talk will be practical lessons for solving a real business problem with machine learning.

#### [Sentiment analysis of tweets in Polish language using deep learning](https://pydata.org/warsaw2019/schedule/presentation/37/sentiment-analysis-tweets-polish-language-using-deep-learning/) - Joanna Piwko
##### Description
Sentiment analysis in texts is a problem that can be solved using Artificial Intelligence. The talk's goal is to present how to make detect five emotions (happiness, anger, sadness, fear, disgust) for tweets in Polish language using open source tools. During the presentation, the process from data collecting to creating a deep neural network will be shown.
##### Abstract
Sentiment analysis is one of the problems which can be solved using Artificial Intelligence. Most research related to the analysis of emotions in Polish texts from social media, (especially from Twitter) focus only on classification as positive, negative or neutral. In my pitch, I would like to concentrate on detecting 5 emotions like happiness, sadness, anger, disgust and fear.  During the presentation I will show how the whole process from data collecting, preprocessing and labelling to training model and presenting results looks like. The implementation was done using Python.  First, text data from Twitter was cleaned from links, emojis and unknown symbols, which are unnecessary for the analysis. For input to the model, texts were converted to numeric representation in vectors. This representation was generated using pretrained Word2vec model for the Polish language.  For labelling data, words were transformed to lemmas (dictionary form) using Morfeusz 2 package, which is an inflectional analyser. This operation was necessary to generate vectors of the numeric representation of emotions. For every word a vector with the numeric representation of 5 emotions using Necki Affective Word List was created. This list contains numeric information of emotions about words in lemma grammar form.  The model used for the sentiment analysis was LSTM network. The first layer of the model was the embedding layer which takes weights for every word from Word2vec model. Then were LSTM and dense layers.  At the end of presentation, I will show the results with examples of good classification and misclassification.

#### [Evaluation Metrics for Binary Classification: The Ultimate Guide](https://pydata.org/warsaw2019/schedule/presentation/4/evaluation-metrics-binary-classification-ultimate-guide/) - Jakub Czakon
##### Description
Choosing a proper metric is a crucial yet difficult part of the machine learning project. In this talk, you will learn about a number of common and lesser-known metrics and performance charts as well as typical decisions when it comes to choosing one for your project. Hopefully, with all that knowledge you will be fully equipped to deal with metric-related problems in your future projects!
##### Abstract
Choosing a proper metric is a crucial yet difficult part of the machine learning project. In this talk, you will learn about a number of common and lesser-known metrics and performance charts as well as typical decisions when it comes to choosing one for your project.  For every metric or chart I will talk about: - What is the definition and intuition behind it, - The non-technical explanation for business stakeholders, - How to calculate/plot it, - When should you use it.  Hopefully, with all that knowledge you will be fully equipped to deal with metric-related problems in your future projects!

#### [Machine Learning on big data in security applications](https://pydata.org/warsaw2019/schedule/presentation/33/machine-learning-big-data-security-applications/) - Yury Kasimov
##### Description
In this talk, we describe how Python in combination with Apache Spark helps Avast to fight bad guys. We demonstrate different use cases how we apply machine learning to a wide range of security applications from anomaly detection on time series to clustering of malicious files.
##### Abstract
Avast is dedicated to creating a world that provides safety and privacy for all. Every month we stop over 1.5 billion attacks and analyze 30 million new executable files. Robust big data pipelines are crucial for us to ensure the safety of our customers. We use Apache Spark and machine learning frameworks, including TensorFlow, in different areas such as network security and malware detection and classification.  In the first part of the presentation, we describe our cluster environment and talk about how we analyze, cluster, and build classification models for malicious files. Clustering by itself is widely used for different security applications, and Spark enables us with a fast way of conducting our experiments. The pipeline is useful for the research on new algorithms and the evaluation of the production ones.  In the second part, we show the application of anomaly detection on time series. As an antivirus company, we receive thousands of different incident reports daily. We help malware experts to analyze threats by notifying them about sudden changes. We will walk you through our streaming application with parallel training and serving of multiple TensorFlow models.

#### [Machine Learning Spacecraft Designing for Cybersecurity](https://pydata.org/warsaw2019/schedule/presentation/38/machine-learning-spacecraft-designing-cybersecurity/) - Marina Volkova
##### Description
Making the world a safer place is not rocket science, it's data science.
##### Abstract
In the field of cybersecurity, data scientists use computational methods to develop more effective ways to find security threats hidden in data flows of IT network communications. This talk, focused on data scientists, will provide a moderately technical representation of how machine learning and data science solve real-life problems, demonstrating how threat detection is enriched and improved through machine learning and data science.  I will address:   
* The ups and downs of AI and ML in this application: What’s so complicated about cybersecurity anyway?
* Machine Learning taxonomy: classification, clustering, anomaly detection   
* When is an anomaly an anomaly, and when is it not an anomaly?   
* How we built Machine Learning spaceships to identify one of the oldest and most persistent attack vectors (i.e. SQL Injections): Big, Bigger, and the Biggest versions.   
* Trade-off with accuracy and complexity: Do we need to destroy a planet to get rid of SQL injections?

#### [Football video analysis using Deep Learning](https://pydata.org/warsaw2019/schedule/presentation/29/football-video-analysis-using-deep-learning/) - Jacek Komorowski
##### Description
The talk will present how to combine classical computer vision techniques with deep learning methods to automate analysis of football videos. It'll cover efficient methods for ball and player detection and recognition in long shot video coverage of football games.
##### Abstract
I'll present how to combine classical computer vision techniques with deep learning methods to build a solution to automate football video analysis. The talk will cover using deep convolutional neural networks for ball and player detection, application of multi-view stereo methods for 3D ball position recovery and using Spatial Transformer Networks to boost accuracy of jersey number recognition classifier. I'll discuss practical problems arising during long shot video analysis of football games. Problems, that make apparently simple tasks, like ball detection, really challenging.

#### [Adding Narrative to BI Dashboards with Natural Language Generation](https://pydata.org/warsaw2019/schedule/presentation/34/adding-narrative-bi-dashboards-natural-language-generation/) - Žygimantas Medelis
##### Description
Data visualizations are not always sufficient in understanding important aspects of data. People have to interpret charts and build narratives about it. Natural language generation technology can be used to greatly improve the communicative power of the data. In this talk I will introduce NLG and will present a case through the use of two open source tools: Accelerate Text (NLG) and Metabase (BI)
##### Abstract
BI tools excel at visually organizing data in various dashboards. Yet data visualizations are not always sufficient in understanding important aspects of data. People have to interpret charts and build narratives about data on their own. Furthermore, different groups of people often need different narratives about the same data. For example, a story about the same sales data is different for a CFO and for an Order Fulfillment Manager.  Natural language generation technology (NLG) can be used to greatly improve the communicative power of a BI dashboards. With the use of NLG we can produce different descriptions of the same data adopted to the needs of each person reading it.  The integration between BI and NLG will be demonstrated through the use of two open source products: (a) TokenMill's open source NLG tool called Accelerated Text (https://github.com/tokenmill/acceleratedtext), to illustrate how natural language can be generated using data; (b) and the BI platform Metabase (https://github.com/metabase/metabase), to provide analytical dashboards which will include both data visualizations and automatically generated natural language.

#### [Detection of solar panels based on aerial images of the city of Poznań using deep neural networks](https://pydata.org/warsaw2019/schedule/presentation/39/detection-solar-panels-based-aerial-images-city-poznan-using-deep-neural-networks/) - Michel Voss
##### Description
The main goal of the article is to present the results of a study on the use of deep learning networks to detect solar panels based on aerial images of Poznan. In addition, the main motivation is to obtain more detailed information about the use of solar energy in Poland drawing on big data sources, which until now have not been used for this purpose.
##### Abstract
The data was acquired from the Management Board of Geodesy and Municipal Cadastre GEOPOZ in Poznań and included orthophotomaps for 2016 and the layer of buildings and plots of lands. We extracted buildings from the images using R statistical software and the sf package. To detect solar panels we used the Turi Create library written in Python which re-implements the YOLO (You Only Look Once) library.  The object recognition algorithm was trained on a sample of images that included annotations (bounding boxes) about the exact location of solar panels. The results indicate a very high recognition efficiency at the level of 96-99% on the test sample. Based on this procedure we found that around 2% of residential buildings in Poznań in 2016 had solar panels mounted on roofs.  As far as we know, this is the first use of deep learning to detect solar panels in Poland. Currently, similar studies are being carried out by for instance Statistics Netherlands as part of the DeepSolaris project. The study exemplifies a trend involving the use of aerial and satellite images for statistical purposes thanks to advanced machine learning algorithms and open source software.

