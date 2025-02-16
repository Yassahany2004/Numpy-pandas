# Numpy-pandas
Accessing DataFrame Rows
import pandas as pd
df = pd.DataFrame([
['Ali', 90,'pass'],
['Ahmed',85,'pass'],
['Yassa',65,'fail'],
['Mohamed',80,'pass']
],columns=['Student','Grade',"Pass_Fail"])
print("Row at index 1:\n",df.iloc[1],"\n")
filtered_df = df[df['Pass_Fail']=='pass']
print("Filtered DataFrame:\n", filtered_df)
