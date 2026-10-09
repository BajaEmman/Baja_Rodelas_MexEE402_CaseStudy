# Baja_Rodelas_MexEE402_CaseStudy
# MexEE 402: Data Preprocessing Case Study

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## Members

| Name | Student Number | Section |
|---|---|---|
| Baja, Alessandro Emmanuel | 22-02799 | MEXE-4103 |
| Rodelas, Micah Nicolette V. | 22-09809 | MEXE-4103 |

## Notebook links

| Chapter | Member 1 | Member 2 |
|---|---|---|
| Ch1_2_3 | [link](https://colab.research.google.com/drive/12ljgN4Mh8o-4-7vRpY83FBe5rNkRmmBF?usp=sharing) | [link](https://colab.research.google.com/drive/1BJ0q-GGVSQzH0UF0zf81FExTsaY6_H30?usp=sharing) |
| Ch4 | [link](https://colab.research.google.com/drive/1XGAYWmoQBC4WSze-kV2jNnazMGmid1Hs?usp=sharing) | [link](https://colab.research.google.com/drive/19-Bp1pnxt6XgYzhgEjYSdcBN5buR_BKG?usp=sharing) |
| Ch5 | [link](https://colab.research.google.com/drive/1DLbQPYTfUg1tUnsoKJzVqVwF-htqIsj1?usp=sharing) | [link](https://colab.research.google.com/drive/100U7mHagTOv5EiiU3JunlGQGcHDva3Ta?usp=sharing) |
| Ch6 | [link](https://colab.research.google.com/drive/1IUycKeWbfTAvS0p0CeashfOyx4Pl2BeS?usp=sharing) | [link](https://colab.research.google.com/drive/1CkfcwHw_5Q7-8EOHWS7EE3j1akWUo4V7?usp=sharing) |
| Ch7 | [link](https://colab.research.google.com/drive/1vHVo3pS3BrNwe2xnB0DO4wT10wHLunI_?usp=sharing) | [link](https://colab.research.google.com/drive/1r6e7mq3LivNEW9DnsvZwkCzHytBDwdZi?usp=sharing) |
| Ch8 | [link](https://colab.research.google.com/drive/1Smqqs2LpQ3CBcPfNEOUJoDkQJOHux148?usp=sharing) | [link](https://colab.research.google.com/drive/1CSVwYXXuuFvszBsrVEp4kFkCsavHdgA5?usp=sharing) |
| Ch9 | [link](https://colab.research.google.com/drive/1dajaJFgADqw8FV10KRkl_EshQxu4gASs?usp=sharing) | [link](https://colab.research.google.com/drive/19eCEGq9R3ESB_7X_bXnIefOns7Hf0Li-?usp=sharing) |

## What we learned ❓💡

Chapter 1_2_3:
  
  I learned that Data Pre-processing is important. Since raw data is sometimes messy and incomplete, it is better to re-arrange or pre-process it so that we can save resources such as time and effort later on. This chapter also gave me a brief insight about head, info, and describe. Head gives out the first five rows of the dataset. Info gives a brief overview of the dataset. Describe gives a statistical summary of the dataset.

Chapter 4:

  In this chapter, I learned how to convert numerical data into categorized data. I learned what's the difference between One-hot encoding and Ordinal Encoding. One-hot encoding assigns 1 = True and 0 = False while Ordinal encoding follows an order. I remember the examples used as something like small, medium, and lots while the other is sunny, cloudy, and rainy. The major difference in this is that small, medium, and lots are in order while the other is in no order since there is no factual evidence to prove that cloudy happens after sunny and vice versa.

Chapter 5:

  During this chapter, I learned how Data Scaling works. It basically scales the data closer to 0 and 1 so that it can be easier to compare. Scaling also ensures that both of the data given contributes fairly to the model. I remember in this chapter the example given is the grades and their study hours. Specifically for this example, scaling would be used. But not all times scaling has to be used, it just depends on the nature of the data. 

 Chapter 6:
 
   I became aware of what is an outliers. I learned how to identify outliers with the Z-score and IQR methods, and notice it differences while simulating the code. The outliers found using these two methods can be different. I also learned about capping and flooring, some for log transformation and removing outliers when appropriate and needed.

Chapter 7:

  I learned that feature selection can reduce irrelevant features and simplify a model. I also learned that different feature-selection methods can choose different features because they evaluate feature importance in different ways. How LassoCV method is taking the absolute value of the coefficient. How RFECV worsks, step by step and how it works to get and select the best feature set. I notice the many writings while running it and ask for help with AI to learn and to prevent it, and somehow I learned that changing and selecting the number of folds affect the output but doesn't mean that the code itself is wrong. 
  
Chapter 8:

  I learned from this chapter that Pipeline can combine preprocessing steps and make them run in the correct order. From SimpleImputer and StandardScaler, I learned how to handle missing values and scale numerical data. From ColumnTransformer, I learned how to apply specific preprocessing to selected columns. This makes the preprocessing process more organized, consistent, and easier to reuse.
  
Chapter 9:

  I discovered that numerical and categorical columns have different pre-processing methods. Numerical data can be imputed and scaled, and categorical data can be imputed and one-hot encoded. I also had to learn about discretization,a process of turning a continuous value into a set of distinct, labeled groups. Like how Age was divided into Child, Adult, and Elderly tomake patterns easier to interpret. Most importantly, verification and checking is a must, don't assume.


## Errors we found ⚠️🚫

List any mistake you found in the original notebooks, and the correct version.
There are real ones in there. Finding them earns points.

## Note on AI tools 📋🤖

Emman used ChatGPT for better understanding of what was happening at Ch5.
Micah used ChatGPT to understand more the code running in Chapter 6 and Chapter 9.

## References 🔍📚

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.
