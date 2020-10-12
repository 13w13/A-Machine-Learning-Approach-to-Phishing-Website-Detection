# A-Machine-Learning-Approach-to-Phishing-Website-Detection
Simon Weiss - 105366   
22/05/2020

https://13w13.github.io/A-Machine-Learning-Approach-to-Phishing-Website-Detection/

---

## 1.Introduction

### What is Phishing? 


As COVID-19 spreads around the world, it is clear that the use of the web and online services is accelerating, confirming the importance of this new technology in our modern world. 

In a March [letter on emergency preparedness in the context of Covid](https://www.bankingsupervision.europa.eu/press/letterstobanks/shared/pdf/2020/ssm.2020_letter_on_Contingency_preparedness_in_the_context_of_COVID-19.en.pdf?d1c8dc2780e2055243778bedf818efeb), the European Central Bank warns that the number of cyberthreats has increased dramatically and stresses that the time has come to "assessing risks of increased cyber security related fraud, aimed both to customers or to the institution via phishing mails, etc."

One of the most widely recognized online security dangers is **Phishing attack**. The purpose of this fraud is to **imitate a real website**, for example, internet banking, e-eCommerce, or social networking so as to acquire confidential data such as user-names, passwords, financial and health-related information from potential victims.

![What is Phishing ? ](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQ5FQAtr-KcCLCcfXOYZPuFHU7sawmLy4x73w&usqp=CAU)
   
***
  
### Website Phishing
Phishing sites are crafted to lure users into thinking they are on a legitimate website. The goal of a website Phishing is thus to appear as **credible as possible** so that it is indistinguishable from legitimate websites. 

The coarser website phishing will have a distinctive visual sign of the legitimate site as the example below of an Amazon login page. The most successful ones are only recognizable by other characteristics of their own web page, such as the url address, which will not correspond to the server of the legitimate site. 

***
    
    
### Uci Dataset

It is in this context that we will use the database built by professors Mohammad Rami, McCluskey T.L. of University of Huddersfield and Thabtah Fadi of the Canadian University of Duba and published on the famous [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Phishing+Websites).    
The database is a collection of website URLs for 11055 websites.    
Each sample has 30 website parameters (features) that have proved to be sound and effective in predicting phishing websites and a Result label(target) identifying it as a phishing website or not (respectively -1 or 1).

***
### Problem description
Our problem is thus a **supervised binary classification problem**. We will divide our dataset into a train and a test samples so as to train models on the dataset and find which models will give us simply  the best accuracy score in detecting if a website is a phishing one or not. 

***

### Description of the features in dataset


The categories features in our database are divided into **4 main groups**.    

* Address Bar based Features
* Abnormal Based Features
* HTML and JavaScript based Features
* Domain based Features


***

### Overview of the project

In order to address the problem described in point 1.4,, I have implemented 3 main types classification algorithms(Trees Classifier, Logistic Regression, Neural Networks).  First, we will process the data and do some EDA. Then we will create models and tun our hyperparamter and then we will assess our models and compare it in order to find the best models. From all the models developed , Boosted Tree model has highest accuracy and is  followed by Random Forest Classifier and Logistic Regression. So, according to our project, boosted tree would best predict if a website is a phishing website or not.

Have a good reading ! 

