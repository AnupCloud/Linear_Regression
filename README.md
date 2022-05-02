## 1. The Problem statement :
The goal here is to find the chance of admission of a candidate based on his/her GRE Score 
(out of 340), TOEFL Score (out of 120), rating of the University (out of 5) in which he/she 
is trying to get admission, Strength of the SOP (out of 5), strength of the Letter Of 
Recommendation (out of 5), CGPA (out of 10) and the research experience (0 or 1).

## 2. Application Design :
![Web capture_3-5-2022_03549_](https://user-images.githubusercontent.com/52250527/166309450-bb3ab2bb-97f4-4e63-8926-6399b5465fd8.jpeg)

## 3. The Testing Pipeline :
![image](https://user-images.githubusercontent.com/52250527/166309833-cbc0de95-b04f-4e5e-8def-7ced91760648.png)

## 4. Flask App :
As we’ll expose the created model as a web API to be consumed by the client/client APIs, 
we’d do it using the flask framework.

The flow of our flask app will be :


![new](https://user-images.githubusercontent.com/52250527/166314231-c6aa1ff1-2e7a-4bef-b439-ca2747836779.png)

## 5. SETUP
a. Create Environment :-
$ conda create -n admission python=3.6 -y
$ conda activate admission

b. Run requirements.txt
$ pip install -r requirements.txt

c. Run app
$ python main.py

## 6. Deployment to G-cloud :
-------Refer to Gcloud.txt-----------<https://github.com/AnupCloud/Linear_Regression/blob/master/Gcloud.txt>
