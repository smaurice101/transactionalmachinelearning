# Transactional Machine Learning
*Transactional Machine Learning (TML) using Data Streams and AutoML is a platform for building and streaming cloud native solutions using Apache Kafka as the data backbone running on Confluent, AWS, GCP, AZURE,* for advanced machine learning solutions using transactional data to learn from, and provide insights, quickly and continuously to any number of devices and humans in any format!

**TML Is Based On the Belief that "_Fast data requires fast machine learning for fast decision-making_"**. TML gives rise in the industy to a **_Data Stream Scientist_** versus a **_Data Scientist_** in conventional machine learning (CML). 

**TML Book Details Found on** [Publisher's site](https://www.apress.com/us/book/9781484270226)

Apply auto machine learning to data streams and create transactional machine learning (TML) solutions that are:
 
 **1. frictionless**: require minimal to no human intervention 
 
 **2. elastic**: machine learning solutions that can scale up or down by controlling the number of data streams, algorithms (or machine learning models), and users of the insights

TML is ideal when data are highly erratic (nonlinear) and you want the machine to learn from the **latest** dataset by creating sliding windows of training datasets and auto creating **micro-machine learning models** quickly, that can be easily scaled, managed and the insights used immediately from any device!  **There are many TML use cases such as:**

**1. IoT**: Capture real-time, fast, data, and building custom **micro-machine learning models** for every IoT device specific to the environment that the device operates in and predict failures, optimize device settings, and more.

**2. Banking/Finance Fraud Detect**: Detect fraud using unsupervised learning on data streams and process millions of transactions for fraud - see the [LinkedIn blog](https://www.linkedin.com/pulse/bank-fraud-detection-data-streams-kafka-google-cloud-maurice-ph-d-/?trackingId=HEyDMUFIS0C4smYhwuUBfg%3D%3D)

**3. Financial Trading**: Use TML to analyse stock prices and predict **sub-second** stock prices!

**4. Pricing**: Use TML to build optimal pricing of products at scale.

**5. Oil/Gas**: Use TML to optimize oil drilling operations **sub-second** and drill oil wells faster and cheaper with minimal downtime

**6. SO MUCH MORE...** 

**The above usecases are not possible with conventional machine learning methods that require frequent human interventions that create lots of friction, and not very elastic.**

**By using Apache Kafka On-Premise many advanced, and large, TML usecases are 80-90% cheapers than cloud-native usecase, mainly because storage, compute, Egress/Ingress are localized.  Given Compute and Storage are extremely low-cost On-Premise solutions with TML are on the rise.**

Strengthen your knowledge of the inner workings of TML solutions using data streams with auto machine learning integrated with Apache Kafka.  **You will be at the forefront of an exciting area of machine learning that is focused on speed of data and algorithm creation, scale, and automation.**

---

**Create Your First TML Solution with Kafka by Downloading the Technologies Below**

[WATCH The TML Instructional Video: Setup, Configuration, Execution, Visualization](https://youtu.be/b1fuIeC7d-8)

1) **_MAADS-VIPER:_** https://www.confluent.io/hub/oticsinc/maads-viper (Official Kafka connector for TML - Linux version).  **Latest** Linux/Windows/MAC version can be found here: https://github.com/smaurice101/maads-viper)
2) **_MAADS-VIPERviz:_** https://github.com/smaurice101/MAADS-VIPERviz (Streaming Visualization for Windows/Linux/MAC versions)
3) **_MAADS-HPDE:_** https://github.com/smaurice101/MAADS-HPDE (Windows/Linux/MAC versions available)
4) **_MAADS-Python Library:_** https://pypi.org/project/maadstml/ (NOTE: You need Python IDE installed: tested with Python up to v.3.8)
5) **_Create a Kafka Cluster at Confluent Cloud:_** https://www.confluent.io/confluent-cloud
6) Users can also, **directly**, use MAADS-VIPER and Kafka services on Amazon AWS, Microsoft Azure, and Google (GCP)

* VIPER, VIPERviz, and HPDE fall under the Software Licence from OTICS Advanced Analytics Inc.: http://www.otics.ca/maadsweb/maads-viper/license/Software-License-VIPER-HPDE.pdf
* For Advanced users who want to integrate TML with MAADS DEEP LEARNING technology should email info@otics.ca*

**Contact**: 

For any help and additional information, or if your token has expired you can e-mail: info@otics.ca or goto http://www.otics.ca, and we would be happy to help you! OTICS will provide 1 hour free developer session on TML if needed.

***
[**Watch University of Calgary Lecture on TML to Software Engineering Graduate Students**](https://lnkd.in/gxMw6Da)

[**Read Confluent blog**](https://www.confluent.io/blog/transactional-machine-learning-with-maads-viper-and-apache-kafka/)

[**Read Medium blog**](https://sebastian-maurice.medium.com/transactional-machine-learning-with-data-streams-for-real-time-predictions-and-optimization-using-eb12c4df597c)

[**Read Fast Big Data Visualization blog**](https://www.linkedin.com/pulse/fast-visualization-big-data-streams-using-sliding-maurice-ph-d-/?trackingId=OFDLTUUUSGqsgYTC0srzdw%3D%3D)

***

***
**EXAMPLE TML PYTHON CODE**: You can literally build extremely powerful, distributed, and scalable cloud-based machine learning solutions with the code below for your business use case of any size with low-code and low-cost!

**CODE SET 1:** This set of programs will go through an example of predicting and optimizing Foot Traffic at ~11,000 Walmart Stores. 

**Step 1:**

[**Produce Walmart Data to Kafka Cluster** (Let this run for 5 minutes or so THEN run the Machine Learning code next)](https://github.com/smaurice101/produce_data_to_kafka)

**Step 2:**

[**Walmart Foot Traffic TML** (Let this run for 5 minutes or so THEN run the Prediction/Optimization  code next)](https://github.com/smaurice101/Walmart-Foot-Traffic-Transactional-Machine-Learning)

**Step 3:**

[**Perform Walmart Foot Traffic Prediction and Optimization**](https://github.com/smaurice101/Walmart-Predict-and-Optimize-Foot-Traffic) 

**Step 4:**

To Visualize the results in Step 3 you need to run MAADS-VIPER Visualization (VIPERviz) and then enter the following URL For:

**_Visualize Predictions:_**
https://127.0.0.1:8003/prediction.html?topic=otics-tmlbook-walmartretail-foottrafic-prediction-results-output&offset=-1&groupid=&rollbackoffset=10&topictype=prediction&append=0&secure=1&consumerid=[Enter Consumer ID for Topic=otics-tmlbook-walmartretail-foottrafic-prediction-results-output]&vipertoken=hivmg1TMR1zS1ZHVqF4s83Zq1rDtsZKh9pEULHnLR0BXPlaPEMZBEAyC7TY0

**_Visualize Optimization:_**
https://127.0.0.1:8003/optimization.html?topic=otics-tmlbook-walmartretail-foottrafic-optimization-results-output&offset=-1&groupid=&rollbackoffset=10&topictype=optimization&secure=1&append=0&consumerid=[Enter Consumer ID for Topic=otics-tmlbook-walmartretail-foottrafic-prediction-results-output]&vipertoken=hivmg1TMR1zS1ZHVqF4s83Zq1rDtsZKh9pEULHnLR0BXPlaPEMZBEAyC7TY0


The Above Assumes:
1) You have created a Kafka cluster in Confluent Cloud (Or AWS, Microsoft or Google Cloud)
2) You have MAADSViz running on IP: 127.0.0.1 and listening on Port: 8003
3) You downloaded views zip and extracted contents to **viperviz/views folder**
4) You added the consumer id for Topic=otics-tmlbook-walmartretail-foottrafic-prediction-results-output and Topic=otics-tmlbook-walmartretail-foottrafic-optimization-results-output
5) This Consumer IDs are printed out for you in the Python Program in Step 1 c)

**CODE SET 2:** This set of program will perform Bank Fraud detection in 50 Bank accounts and 5 fields in each transaction.  It will detect fraud in real-time. 

**Step 1:**

[**Produce Bank Account Data to Kafka Cluster** (Let this run for 5 minutes or so THEN run the Anomaly Detection code next)](https://github.com/smaurice101/Produce-Bank-Fraud-Data-to-Kafka)

**Step 2:**

[**Perform Transactional Bank Fraud Detection on Streaming Data** This will use multi-threading in Python](https://github.com/smaurice101/Predict-Bank-Fraud)

**Step 3:**

**_Visualize Anomalies:_**

https://127.0.0.1:8003/anomaly.html?topic=otics-tmlbook-anomalydataresults&offset=-1&rollbackoffset=20&append=0&topictype=anomaly&secure=1&groupid=&consumerid=[Enter your Consumer ID for otics-tmlbook-anomalydataresults]&vipertoken=hivmg1TMR1zS1ZHVqF4s83Zq1rDtsZKh9pEULHnLR0BXPlaPEMZBEAyC7TY0

The Above Assumes:
1) You have created a Kafka cluster in Confluent Cloud (Or AWS, Microsoft or Google Cloud)
2) You have MAADSViz running on IP: 127.0.0.1 and listening on Port: 8003
3) You downloaded views zip and extracted contents to **viperviz/views folder**
4) You added the consumer id for Topic=otics-tmlbook-anomalydataresults
5) This Consumer IDs are printed out for you in the Python Program in Step 2 b)

**_NOTE:_** Please monitor your Cloud Billing/Payments - DELETE YOUR CLUSTER WHEN YOU ARE DONE.  DO NOT LET YOUR CLUSTER RUN IF YOU ARE NOT USING IT.  The above programs will auto create all data very quickly. So you can DELETE your cluster immediately.  Confluent will give you $200 free cloud credits.  The above programs will consume a low fraction of this free $$.
***
