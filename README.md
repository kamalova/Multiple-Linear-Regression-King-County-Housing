

![banner](https://github.com/kamalova/Multiple-Linear-Regression-King-County-Housing/blob/main/images/banner.jpg)



## Multiple Linear Regression Analysis of King County Housing 
**Author:** Nurgul Kurbanali kyzy

### Project Overview

For the purpose of this project was used multiple linear regression modeling for inference to study the relationship between the price and other variables present in the dataset between 2014-2105 in King County with the hope of helping potential home seller understand housing market. The highly correlated predictors were dropped from the dataset. All assumptions of the linear regression were checked, and an optimal final model was achieved by keeping the most influential features only.Based on the multiple linear regression model grade, view, floor levels, square footage of the living area, and basement were found to be important features that drive the overall sale price of a house in King County.

### Business Problem

The stakeholders of this project are a real estate agency that helps homeowners buy and/or sell homes. The business problem is to provide advice to homeowners on which aspects of the house features they should invest in, in order to increase the estimated values of their homes, and by what amount.

### Data Understanding

The dataset includes 21 assessment parameters which describes every aspect of homes in King County. These variables focus on the quality and quantity of the physical attributes of a property. The dataset and variable descriptions can be found on [here](https://github.com/kamalova/Multiple-Linear-Regression-King-County-Housing/blob/main/data/column_names.md)

### Methods

We started with inspecting, and cleaning the datasets from outliers following by checking for the completeness of data and missing values. Further conducted Exploratory Data Analysis (EDA) and  removed nonimportant features based on EDA. Then built multiple linear regression models in OLS statsmodels to determine our strongest correlations. We evaluated each model  by checking multicollinearity among different features and then returned to the data to see what could to be changed, or removed to achieve a more successful model. 


### Results
 ![Model3_summary](https://github.com/kamalova/Multiple-Linear-Regression-King-County-Housing/blob/main/images/Mode3_summary.png)<p>
An optimal final multople linear regression model was achieved by keeping the most influential predictors only. Thus grade, view, floor levels, square footage of the living area, and basement were found to be important features that drive the overall sale price of a house in King County. The coefficient of determination: R-squared is 0.546 meaning that  54% of the variance in the target variable can be explained by the features. All feature variables have p-values less than 0.05, meaning all these features are statistically significant and  there is no correlation between the independent and the dependent variables.<p>
 Lets interpret the coefficients of final model individually:
 
![grade_price](https://github.com/kamalova/Multiple-Linear-Regression-King-County-Housing/blob/main/images/grade_price.png)<p>
 One unit change in #grade can increase house price at 18.77% <p>
![view_price](https://github.com/kamalova/Multiple-Linear-Regression-King-County-Housing/blob/main/images/view_price.png)<p>
 One unit change in #view can increase house price at 9.20%<p>
![floor_price](https://github.com/kamalova/Multiple-Linear-Regression-King-County-Housing/blob/main/images/floor_price.png)<p>
 One unit change in #floor(level) up to 2.5 increase house price at 4.64% <p>
 ![sqft_living_base_price](https://github.com/kamalova/Multiple-Linear-Regression-King-County-Housing/blob/main/images/sqft_living_base_price.png)<p>
One unit change in #sqft_living can increase house price at 0.02%<p>
One unit change in #sqft_basement can increase house price at 0.01% <p>
 

#### Recommendations:
Based on our analysis, we can give the following suggestions:<p>
- Trying to get at least grade *8* which is an average in construction and design according to the King County Department of Assessment. It can be achieved by using better materials in both the exterior and interior finishes. As grade increases, the house price tends to be grow.
- The quality of the view is one of the most important things to assess when it comes to investing in a home with resale value. Homes with a partial view may be a good investment because often trimming a few trees or building addition will turn the view from partial to full. Keep in mind that a home with a partial view is still superior, in terms of resale value, to a home without a view at all. The best view you can ask for is panoramic, meaning that there is a wide, unobstructed view of an entire surrounding area. Whether this is offered from a living room window, or from an outside deck or patio it's a priceless accent to any home.
- Most ideal and preferable house floor(level) is around 2.5 . Houses with floors(levels) between 3-3.5 are not desirable since prices getting  sharply decreasing
- Increasing the square footage of the living area along with the square footage of the basement will also tend positively effects the price increase
 
 #### Future Considerations
Based on the adjusted R-squared we got  more than 45% of the variance in housing prices cannot be explained by the selected principal components. Given that some of the variables needed to be log-transformed  and scaled to satisfy regression assumptions. Other models like logistic regression, decision trees can be constructed and compared by results. Future analysis should include other predictors such house locations, demographics , security of a neighborhood etc.
 
### For More Information
Full analysis can be reviewed in the [Jupyter Notebook](https://github.com/kamalova/Multiple-Linear-Regression-King-County-Housing/blob/main/notebook.ipynb) or   [presentation](https://github.com/kamalova/Multiple-Linear-Regression-King-County-Housing/blob/main/presentation.pdf) <p> 
For inquiries about this project, please feel free to contact: 
 Nurgul Kurbanali kyzy at nurkamalova@gmail.com
  
 ### Repository Structure
  







