# DecisionTree-in-python
import pandas as pd
import warnings
warnings.filterwarnings("ignore",category=UserWarning)
df=pd.read_csv("C:\\Users\\kriti\\Downloads\\salaries.csv")
df.head()
inputs=df.drop('salary_more_then_100k',axis='columns')
