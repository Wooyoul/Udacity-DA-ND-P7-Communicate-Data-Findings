# Udacity-DA-ND-P7-Communicate-Data-Findings  <br>  
<br>
Written by Wooyoul Na  <br>  
  <br>  

## Introduction   <br>   
  
This is 7th project of Udacity Data analyst Nanodegree program. In this project, the exploratory data analysis was performed using matplotlib and seaborn library in Python, and a presentation with explanatory visualizations was created to communicate findings during the exploration.   <br>   
 <br>   

## Dataset  <br>  

For proceeding this project, the PISA 2012 data have been used. the original dataset had been contains 485,490 cases and 635 features. Because the sample-size of original dataset was too large, Only the cases from OECD countries were used for this project. In addition, some features of interest were included for analysis.  <br>  
Through data cleaning process, Following cases and features have been included the final dataset, named `pisa2012_clean.csv`.  <br>  
If you want to see the entire data cleaning process, please see [here.](pisa2012_cleaning.ipynb).  <br>  
  <br>  

## Summary  <br>  

### Questions <br>  

Following questions have been focused for this project:

 - How about average Math achievement by OECD countries?  <br>  
   
   
 - How about the relationship between Economic, social and cultural status(ESCS) and Math achievement of students?  <br>  
   
   
 - How about relationships between Math achievement and 6 attitudes which are  related Math? What attitude is the strongest relationship with math achievement?  <br>  
   
   
 - How about relationship between ESCS and Math achievement by grade? Is there some interaction effect of grade and ESCS?  <br>  
   
   
 - How about relationship between Math achievement and 6 attitudes which arer related Math by grade? Is there some interaction effect of grade and 6 attitudes? <br>  
 <br>  


### Findings  <br>  

If you want to see the final explanatory slide, please see [explanatory_slide_deck.slides.html](explanatory_slide_deck.slides.html)  <br>  
  <br>  
#### How about average Math achievement by OECD countries?: <br>
 - Korea is the highest average math achievement in OECD countries.  <br>  
   
 - Mexico is the lowest average math achievement in OECD countries.  <br>  
   
 - Furthermore, Mexico is seemed to have a relatively high variability in math achievement.  <br>  
  <br>     
  
#### How about the relationship between Economic, social and cultural status(ESCS) and Math achievement of students?: <br>
 - Economic, social and cultural status of students and Math achievement are seemed to have a somewhat linear relationship.  <br>   
 - That is, It seems that students with higher ESCS tend to have higher math achievement.  <br>  
<br>  

#### How about relationships between Math achievement and 6 attitudes which are  related Math? What attitude is the strongest relationship with math achievement?: <br>  

 - Math selr-efficacy and math self-concept have a positive relationship with math achievement.  <br>   
 - On the other hand, Math anxiety has a negative relationship with math achievement. <br>   
 
 - Furthermore, The attitude which has the most strong linear relationship with math achievement is math self-efficacy. <br>   
 <br>    
 
 
#### How about relationship between ESCS and Math achievement by grade? Is there some interaction effect of grade and ESCS?: <br>  

 - the relationship between ESCS and math achievement is different by students' grade. <br>  
 - For example, There has no relationship between ESCS and math achievement in 7 grade. But, As the grade is higher, the strength of relationship between ESCS and math achievement increases more stronger.
 - As a reslut, There is some interaction between ESCS and students' grade. <br>
  <br>
 
#### How about relationship between Math achievement and 6 attitudes which arer related Math by grade? Is there some interaction effect of grade and 6 attitudes?: <br>
 - Like the case of ESCS, the relationship between each attitude and math achievement is also different by students' grade. <br>  
 - For example, There has no relationship between math self-efficacy and math achievement in 7 grade. But, When the grade is higher than 9, There has somewhat positive relationship between math self-efficacy and math achievement. <br>  
 - Likewise, There has no special relationship between math self-concept and math achievement in 7 grade. Byt, When the grade is higher than 9, there has somewhat positive relationship between math self-efficacy and math achievement. <br>   
 
 - As a reslut, There is some interaction between attitude and students' grade.