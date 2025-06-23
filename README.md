# creation-a-dataframe-with-indexing-like-name-age-city-and-insert-the-values

import pandas as pd

data={"Name":["alice","bob","charlie","david","eve"],

"Age":[14,15,16,17,18],

"City":["hyd","ben","kol","che","mum"]}

df=pd.DataFrame(data)

print(df)

O/P:

Name Age City

0 alice 14 hyd

1 bob 15 ben

2 charlie 16 kol

3 david 17 che

4 eve 18 mum
