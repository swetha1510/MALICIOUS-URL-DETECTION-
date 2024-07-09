# MALICIOUS-URL-DETECTION-
# ABSTRACT:
Malicious URL detection is a critical aspect of cybersecurity, aimed at preventing cyberattacks and protecting sensitive information. Traditional methods of URL detection often rely on blacklists, which can be easily circumvented and do not adapt well to new, evolving threats. This paper explores the application of machine learning techniques to enhance the accuracy and efficiency of malicious URL detection. By leveraging supervised learning algorithms and feature engineering, we propose a robust model that identifies malicious URLs based on various characteristics such as lexical analysis, host-based features, and URL metadata. Our experimental results demonstrate that the machine learning approach significantly outperforms traditional methods, offering higher detection rates and lower false positives. The model's adaptability to new threats is showcased through continuous learning from new data, ensuring its effectiveness in real-time applications. This study highlights the potential of machine learning in fortifying cybersecurity measures and provides a foundation for future advancements in automated threat detection systems.

# INTRODUCTION:


# PROBLEM STATEMENT:
In this case study, we address the detection of malicious URLs as a multi-class classification problem. In this case study, we classify the raw URLs into different class types such as benign or safe URL, phishing URL, malware URL, or defacement URL.
As we know machine learning algorithms only support numeric inputs so we will create lexical numeric features from input URLs. So the input to machine learning algorithms will be the numeric lexical features rather than actual raw URLs.
So, in this case study, we will be using three well-known boosting machine learning classifiers namely XGBoost, Light GBM, Gradient Boosting Machines.

# ABOUT DATA:
For training and testing machine learning algorithms, we have used a huge dataset of 651,191 URLs, out of which 428103 benign or safe URLs, 96457 defacement URLs, 94111 phishing URLs, and 32520 malware URLs. Figure 2 depicts their distribution in terms of percentage. As we know one of the most crucial tasks is to curate the dataset for a machine learning project. We have curated this dataset from five different sources.


