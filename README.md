# my-files
import pandas as pd
df = pd.read_csv('1.txt')
pd.options.display.max_rows = 1
print(df.info()) 
strr = df.to_string()
print(strr)
