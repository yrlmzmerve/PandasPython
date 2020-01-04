# PANDAS

**Pandas yüksek performanslı, kullanımı kolay veri yapıları ve veri analizi araçları sağlar.** 

 - Veri setlerinin esnek şekilde yeniden şekillendirilmesi ve döndürülmesini
 - Veri setlerinde yüksek performans birleştirmeyi
 - Diğer Python ve NumPy veri yapılarındaki düzensiz, farklı indeksli verilerin DataFrame nesnelerine dönüştürülmesini kolaylaştırır.
 
 Pandas ile veri analizi yapılırken kullanılan temel veri yapıları Seriler ve DataFrame’lerdir.
 
 Pandas kütüphanesinin import edilmesi
```
 import pandas as pd
```
 
 Pandas Veri Yapıları
 ```
  - Series
  - DataFrames
 ```
 
  **1) Seriler**
  
  Tek boyutlu Numpy dizilerine çok benzerler.
  Serilerin genel kullanımı aşağıdaki gibidir. 
  ```
  my_series = pd.Series(data,index)
  ```
  Data parametresi sabit bir değer, liste, Numpy dizisi ya da dictionary olabilir.
  Numpy dizisinden farklı olarak serilerde index sütunu da bulunur.
  
  **2) DataFrame**
  
  DataFrame’ler farklı tipteki sütunlara ve satırlara sahip bir SQL tablosu olarak düşünülebilinir.   
  DataFrame’ler veriyi daha kolay işleyebilmemizi sağlar.
  
  DataFrame'lerin genel kullanımı aşağıdaki gibidir. 
  ```
  my_dataframe = pd.DataFrame(data,index)
  ```
  Data parametresi Dictionary’lerden, serilerden veya listelerden oluşan bir dictionary, olabilir. 2  boyutlu numpy dizisi ya da başka bir DataFrame olabilir.
  
  
  ##Pandas ile veri seçme 
  DataFrame nesneleri satır ve sütun adlarına sahip olduğu için Numpy’ dan farklı olarak bu satır ve sütun adlarıyla istediğimiz veriyi seçebiliriz. Seçme işlemleri için “.loc[]” kullanılabilir. 
  Genel kullanımı aşağıdaki gibidir.
  ```
  df.loc[row, column]
  ```
  
  
 <a href="http://fvcproductions.com"><img src="https://pandas.pydata.org/_static/pandas_logo.png" title="FVCproductions" alt="FVCproductions"></a>
