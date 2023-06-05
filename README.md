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
```

#OUTPUT:

![aa](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/decf64e0-ee75-4669-8be3-eb37764461fb)

![aa2](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/e22907d2-77b9-4f34-98cc-e95719ce4215)

![aa3](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/174acc73-4dde-4339-92e8-b63d3c237193)

![aa4](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/495faaa8-0c6c-455e-bb93-84bf16a21a7e)

![aa5](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/922e3d72-8196-453c-8716-89a4f871371f)

![aa6](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/290c11aa-118a-491e-a136-1f6c6d5f539c)

![aa7](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/bce37b45-254b-4f76-bced-a5456964a99b)

![aa8](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/02f70fd6-b447-4717-b1ac-932e7955daa6)

![aa9](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/eb05a92c-e4c3-406d-a88f-69ec62378b43)

![aa10](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/a8b11d08-bed9-4bd2-92e6-6b18c418e3ae)

![aa11](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/dd7895d8-572b-43b3-a494-d551cf43053f)

![aa12](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/c075cfdf-3172-4259-8f2c-e5cad6cfcb75)

![aa13](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/56b2699f-0938-47cd-8a16-3b41361273fd)

![aa14](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/ad48a162-269e-45ea-a5da-5b4a8797f4b6)

![aaa](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/5ef03488-fa87-4f3e-8623-f0397b5c513f)

![aa16](https://github.com/NivethaKumar30/Ex-08-Data-Visualization_1/assets/119559844/0670bb5b-1daa-4aa0-8680-14e6ee426f97)

#RESULT:





