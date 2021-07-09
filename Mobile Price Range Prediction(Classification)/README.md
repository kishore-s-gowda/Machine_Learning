# Problem Formulation
Shiva has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.

He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.

Shiva wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs help to solve this problem.

In this problem you do not have to predict actual price but a price range indicating how high the price is.

### Data Source: (https://www.kaggle.com/iabhishekofficial/mobile-price-classification)

## The data definition is as follows:

**battery_power**-Total energy a battery can store in one time measured in mAh

**blue**-Has bluetooth or not

**clock_speed**-speed at which microprocessor executes instructions

**dual_sim**-Has dual sim support or not

**fc**-Front Camera mega pixels

**four_g**-Has 4G or not

**int_memory**-Internal Memory in Gigabytes

**m_dep**-Mobile Depth in cm

**mobile_wt**-Weight of mobile phone

**n_cores**-Number of cores of processor

**pc**-Primary Camera mega pixels

**px_height**-Pixel Resolution Height

**px_width**-Pixel Resolution Width

**ram**-Random Access Memory in Megabytes

**sc_h**-Screen Height of mobile in cm

**sc_w**-Screen Width of mobile in cm

**talk_time**-longest time that a single battery charge will last when you are

**three_g**-Has 3G or not

**touch_screen**-Has touch screen or not

**wifi**-Has wifi or not

### These are the results of diffrent algorithms used
<br/>
<p align="Left">
  <img src="https://github.com/kishore-s-gowda/kishore-s-gowda/blob/main/images/MobilePrice1.JPG"
     
</p>
  
 So we can see Logistic Regression is giving the best accuracy for our dataset. The difference between train and test accuracies are significantly minimum for that model also. XGBoost(Grid_search) and XGBoost_imp(Grid_search) are tuned properly because the train_accuracy and test_accuracy are almost equal. Other models are somewhat over-fitted. So we can conclude Logistic Regression or XGBoost_imp(Grid_search) as the final model.

### Confusion Matrix 
<br/>
<p align="Left">
  <img src="https://github.com/kishore-s-gowda/kishore-s-gowda/blob/main/images/MobilePrice2.JPG"
      
</p>

### Most important features which influences the mobile price
<br/>
<p align="Left">
  <img src="https://github.com/kishore-s-gowda/kishore-s-gowda/blob/main/images/MobilePrice3.JPG"
       width="1000" 
     height="500"/>
</p>
