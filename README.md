# seaborn
flight dataset
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
a=sns.load_dataset("flights") # this dataset has been imported from github
sns.relplot(x="passengers",y="month",data=a) #using this command this dataset has been plotted in two dimension
![image](https://user-images.githubusercontent.com/77687280/118606029-8ce99480-b7d4-11eb-845e-93d67cb6d156.png)

a=sns.load_dataset("flights")
sns.relplot(x="passengers",y="month",hue="year",data=a) # using hue we can plot in three dimension
