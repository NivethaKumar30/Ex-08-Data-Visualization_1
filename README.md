# Ex-08-Data-Visualization-

## AIM
To Perform Data Visualization on a complex dataset and save the data to a file. 

# Explanation
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# ALGORITHM
### STEP 1
Read the given Data
### STEP 2
Clean the Data Set using Data Cleaning Process
### STEP 3
Apply Feature generation and selection techniques to all the features of the data set
### STEP 4
Apply data visualization techniques to identify the patterns of the data.


# CODE
```
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
tips = sns.load_dataset("tips")
import pandas as pd 
import seaborn as sns
import matplotlib.pyplot as plt

tips_df = sns.load_dataset("tips")
print(tips_df)
sns.relplot(data=tips,x="total_bill",y="tip",hue="day")
sns.relplot(
    data=tips,
    x="total_bill",y="tip",hue="smoker",style="smoker"
        
)
sns.relplot(
    data=tips,
    x="total_bill",y="tip",hue="smoker",style="time",
)
sns.relplot(
    data=tips,x="total_bill",y="tip",hue="size",
)
sns.relplot(data=tips,x="total_bill",y="tip",size="size")
sns.relplot(data=tips,x="total_bill",y="tip",size="size")
sns.lineplot(x="total_bill",y="tip",data=tips_df,hue="sex",
             style="sex",
             
             markers = ["o", "<"],  legend="auto")
             flowers_df=sns.load_dataset("iris")
flowers_df
sns.scatterplot(x=flowers_df.sepal_length,y=flowers_df.sepal_width)
sns.scatterplot(x=flowers_df.sepal_length,y=flowers_df.sepal_width,hue=flowers_df.species,s=70):
plt.figure(figsize=(12,6))
plt.title("Sepal Dimensions")

sns.scatterplot(x=flowers_df.sepal_length,
                y=flowers_df.sepal_width,
                hue=flowers_df.species,
                s=100);
                tips=sns.load_dataset("tips")
sns.displot(tips,x="size")
sns.displot(x="total_bill",data = tips_df,hue="sex",alpha=0.5)
sns.displot(x="total_bill",data=tips_df,hue="sex",
            multiple = "stack")



# OUPUT
