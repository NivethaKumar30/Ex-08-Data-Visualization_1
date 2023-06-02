# Ex-09-Data-Visualization-

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
            multiple = "stack")![aa13](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/ff6e1922-5c88-4d0b-ad32-825f7fad5246)



# OUPUT

![aa](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/458e7416-ee58-42d3-93e7-44ebd4fb4c56)

![aa2](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/fa56fa81-d004-4bc6-91f1-8192868dd497)

![aa3](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/ff92d994-a136-4823-9ae1-ebf7fb1ef5b5)

![aa4](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/f55f1449-a7a0-41ff-b9bd-911a48d77a43)

![aa5](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/f78ff253-0ba0-4196-96fa-4d1f1a89935b)

![aa6](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/6d69f826-63bd-4193-8f44-6814f88b974e)

![aa7](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/bb3cd5a1-8013-4fa0-b5aa-e010120c84d3)

![aa8](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/4a070246-c4ec-4f26-b244-129a21b93285)

![aa9](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/40853bd3-ea3b-4b27-98ff-0585981e05df)

![aa10](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/32c4adca-4b29-49f0-857b-a329703bf598)

![aa11](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/4f9e1c9d-e729-46e5-8aa0-382cdeb6901e)

![aa12](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/4d1abf90-c420-4077-8697-37b137f59aa5)

![aa13](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/c4566771-9880-4981-bd5b-eafbfe083a8f)

![aa14](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/e35e2b37-d34c-4286-be23-4e64d205093a)

![aa15](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/74d7ee04-37ee-4396-b8ac-b44c1b21c804)

![aa16](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/9064157f-2db0-4d8f-a27d-f8ab83ddfd7e)
