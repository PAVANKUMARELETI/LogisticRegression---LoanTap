# LogisticRegression---LoanTap

## 🔹ABOUT:

* Jamboree is a renowned educational institution that has successfully assisted numerous students in gaining admission to top colleges abroad. With their proven problem-solving methods, they have helped students achieve exceptional scores on exams like GMAT, GRE, and SAT with minimal effort.

* To further support students, Jamboree has recently introduced a new feature on their website. This feature enables students to assess their probability of admission to Ivy League colleges, considering the unique perspective of Indian applicants.

* By conducting a thorough analysis, we can assist Jamboree in understanding the crucial factors impacting graduate admissions and their interrelationships. Additionally, we can provide predictive insights to determine an individual's admission chances based on various variables.


## 🔹Why this Case study?

* Solving this business case holds immense importance for aspiring data scientists and ML engineers.

* Building predictive models using machine learning is widely popular among the data scientists/ML engineers. By working through this case study, individuals gain hands-on experience and practical skills in the field.

* Additionally, it will enhance one's ability to communicate with the stakeholders involved in data-related projects and help the organization take better, data-driven decisions.


### 🤞Work that has to be done:

> As a data scientist/ML engineer hired by Jamboree, your primary objective is toanalyze the given dataset and derive valuable insights from it. Additionally, utilize the dataset to construct a predictive model capable of estimating an applicant's likelihood of admission based on the available features.

----

### 📃 Features of the dataset:

> Column Profiling:

| Feature | Description |
|:--------|:------------|
|Serial No.| This column represents the unique row identifier for each applicant in the dataset.|
|GRE Scores| This column contains the GRE (Graduate Record Examination) scores of the applicants, which are measured on a scale of 0 to 340.|
|TOEFL Scores| This column includes the TOEFL (Test of English as a Foreign Language) scores of the applicants, which are measured on a scale of 0 to 120.|
|University Rating| This column indicates the rating or reputation of the university that the applicants are associated with , & The rating is based on a scale of 0 to 5, with 5 representing the highest rating.|
|SOP|This column represents the strength of the applicant's statement of purpose, rated on a scale of 0 to 5, with 5 indicating a strong and compelling SOP.|
|LOR| This column represents the strength of the applicant's letter of recommendation, rated on a scale of 0 to 5, with 5 indicating a strong and compelling LOR.|
|CGPA| This column contains the undergraduate Grade Point Average (GPA) of the applicants, which is measured on a scale of 0 to 10.|
|Research| This column indicates whether the applicant has research experience (1) or not (0).|
|Chance of Admit| This column represents the estimated probability or chance of admission for each applicant, ranging from 0 to 1.|


These columns provide relevant information about the applicants' academic qualifications, testscores, university ratings, and other factors that may influence their chances of admission.

---

## 🤔💭📣<span style="color:seagreen"><strong>Regression Analysis Summary:</strong></span>📣💭🤔

> * Upon conducting regression analysis, it's evident that CGPA emerges as the most influential feature in predicting admission chances.

> * Additionally, GRE and TOEFL scores also exhibit significant importance in the predictive model.

> * Following the initial regression model, a thorough check for multicollinearity was performed, revealing VIF scores consistently below 5, indicative of low multicollinearity among predictors.

> * Despite the absence of high multicollinearity, it's noteworthy that the residuals do not conform perfectly to a normal distribution. Furthermore, the residual plots indicate some level of heteroscedasticity.

> * Subsequent exploration involving regularized models such as Ridge and Lasso regression showcased comparable results to the Linear Regression Model.

> * Moreover, employing ElasticNet (L1+L2) regression yielded results consistent with the other regression models, further reinforcing the predictive capabilities of the features under consideration.


---

## ✴️⚡<span style="color:mediumseagreen"><strong>Business Insights & Recommendations</strong></span>⚡✴️

### <span style="color:seagreen"><strong>Insights:</strong></span>

> <span style="color:lawngreen"><strong>Model Predictors:</strong></span>   
- Our analysis identified several key predictors strongly correlated with admission chances. Notably, **GRE score, TOEFL score, and CGPA** emerged as significant factors influencing admission probabilities.

> <span style="color:lawngreen"><strong>Multicollinearity Check:</strong></span>  
- Assessing multicollinearity revealed no significant issues, indicating the robustness of our model despite high correlations among predictors.

> <span style="color:lawngreen"><strong>Model Performance:</strong></span> 
- Both Linear Regression and Ridge Regression models exhibited promising performance, capturing up to 82% of the variance in admission probabilities.

> <span style="color:lawngreen"><strong>Data Distribution:</strong></span> 
- Exploratory data analysis uncovered left-skewed distributions in admission probabilities and strong positive correlations between exam scores and admission chances.


### <span style="color:seagreen"><strong>Recommendations:</strong></span>

> <span style="color:lawngreen"><strong>Feature Enhancement:</strong></span> 
- Encourage students to focus on improving GRE scores, CGPA, and the quality of Letters of Recommendation (LOR), as these factors significantly influence admission chances.

> <span style="color:lawngreen"><strong>Data Augmentation:</strong></span> 
- Collect a wider range of data beyond academic metrics to capture applicants' holistic profiles, including extracurricular achievements, personal statements, and diversity factors.


> <span style="color:lawngreen"><strong>Additional Features:</strong></span> 
- Given the strong correlation among CGPA, we can enrich the predictive model with additional diverse features such as Research, work experience, internships, or extracurricular activities.


By implementing these recommendations, we can further enhance our admissions process, providing valuable insights and support to both applicants and educational institutions.

-----
