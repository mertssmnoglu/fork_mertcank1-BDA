# **PYTHON İLE BÜYÜK VERİ ANALİZİ** 
<img src=https://raw.githubusercontent.com/mertcank1/BDA/refs/heads/main/animation-cartoons.gif alt="drawing" width="300"/>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;<img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" alt="drawing" width="200"/> 

$\textcolor{blue}{\textbf{Life is Blue}}$

Ders notlarına ve python kodlarına github'daki repos üzerinden erişebilirsiniz.

<img src="https://user-images.githubusercontent.com/74038190/216121964-513bdf95-3c8c-429a-82bc-7c770caca8fc.png" alt="drawing" width="200"/>


Derslerimize ilişkin Python uygulamaları [**colab**](https://colab.research.google.com/) üzerinden işlenmektedir. Daha önce Python üzerinden uygulama yapmadıysanız, buradan kolaylıkla uygulamalar yapabilirsiniz.

**Hadi Başlayalım !**

## KAYNAKÇA

<img src="https://raw.githubusercontent.com/mertcank1/BDA/refs/heads/main/BDA%20referance.jpg" alt="drawing" width="200"/>


import pyspark

from pyspark.sql import SparkSession

from pyspark.sql import SQLContext

#Create SparkSession

spark = SparkSession.builder.master("local[1]").appName("SparkByExamples.com").getOrCreate()

sc=spark.sparkContext

sqlc = SQLContext(sc)

#################################################3
from pyspark import SparkContext

from pyspark.sql import SQLContext

sc=spark.sparkContext

sqlc = SQLContext(sc)

from pyspark.sql import *

na_schema = Row("Name","Age")

row1 = na_schema("Ankit", 23)

row2 = na_schema("Tyler", 26)

row3 = na_schema("Preity", 36

na_list = [row1, row2, row3]

df_na = spark.createDataFrame(na_list)

type(df_na)

df_na.show()


## İletişim için aşağıdaki postaya tıklayın! :point_down:

[<img src=https://www.svgrepo.com/show/530453/mail-reception.svg alt="drawing" width="100"/>](mailto:amertcankose@ticaret.edu.tr)
