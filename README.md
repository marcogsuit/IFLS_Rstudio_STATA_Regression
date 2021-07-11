# IFLS (Indonesian Family Life Survey) Data Regression
Comparing regression result between Rstudio and STATA, Also as a proove that R-studio can process .dta file

**Table Of Contents**
*   **Introduction**
*   **About the Dataset**
*   **Regression Model & Dataset**
*   **Regression Result**
*   **Conclusion**

**1. Introduction**
        
  **IFLS** or the Indonesian Family Life Survey is an ongoing longitudinal survey in Indonesia. The sample is representative of about 83% of the Indonesian population and contains over 30,000 individuals living in 13 of the 27 provinces in the country. 
  
  **IFLS Data Type** If you want to download the dataset, the dataset is consists of 2 donwloadable format, which is STATA format (.dta) and SAS format (.sas).
  
  **Disclaimer**
        Since this project is only to see is there any slight difference between the regression result, so I won't add the classical assumption test and the regression interpretation.
  
 
 **2.About the Dataset**

  **The Dataset** I used in this part is from IFLS 5 survey. I already edit and prepare the dataset using STATA, because this dataset is my old research project.
  
  
  **3.Regression Model & Variables**
       
  **Regression Model** The Regression Model is taken from Clement(2009) Economic Model to predict what motives that moves household to give (donor) and receive (beneficiary) transfers (both money & material). So if we write the economic model it would be like this:
  
  **Transfer Beneficiary Model**
  
  TB = f(Y,A,M,SEX,G,O,E)
  
  **Transfer Donor Model**
  
  TD = f(Y,A,M,SEX,G,O,E)
  
  **Variables**
  
  TB    = Transfer Beneficiary (Indonesian Rupiah)
  
  TD    = Transfer Donor (Indonesian Rupiah)
  
  Y     = Household Income (Indonesian Rupiah)
  
  A     = Age (Year)
  
  M     = Marriage Status (Binary)
  
  Sex   = Sex of the Head of Family (Binary)
  
  G     = Geographical Location (Urban/Rural) (Binary)
  
  O     = Occupation Status     (Binary)
  
  E     = Education Taken by Head of Family (Years)
  
  
**4. Regression Result**

**Transfer Beneficiary Model R-Studio Result**


![rstudio model tb](https://user-images.githubusercontent.com/85789365/125198172-0b215f00-e28b-11eb-999e-1d2c93d4b452.PNG)


**Transfer Beneficiary Model STATA Result**
 
 
 ![stata model tb](https://user-images.githubusercontent.com/85789365/125199430-5d18b380-e290-11eb-81b4-6347d0765431.PNG)



**Transfer Donor Model R-Studio Result**


![rstudio model td](https://user-images.githubusercontent.com/85789365/125198177-0c528c00-e28b-11eb-855b-d73c8dfe569d.PNG)


**Transfer Donor Model STATA Result**
![stata model td](https://user-images.githubusercontent.com/85789365/125199434-5e49e080-e290-11eb-84e2-72a455158806.PNG)


**5. Conclusion**

**After seeing the result (both R and STATA) we can conclude that, there is no slight difference between the calculation from R-studio and STATA.**

**Also what I want to say is, this proove that R-studio is an universal tool that can calculate / processing different file type.**
