## NAME : IMRAN MAJEED

## ROLL NO : SU92-BSAIM-F24-212

### Import Pandas


```python
import pandas as pd
```

### Read CSV File


```python
 df = pd.read_csv("data.csv")
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductID</th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>10017413</td>
      <td>DKNY Unisex Black &amp; Grey Printed Medium Trolle...</td>
      <td>DKNY</td>
      <td>Unisex</td>
      <td>11745</td>
      <td>7</td>
      <td>Black and grey printed medium trolley bag, sec...</td>
      <td>Black</td>
    </tr>
    <tr>
      <th>1</th>
      <td>10016283</td>
      <td>EthnoVogue Women Beige &amp; Grey Made to Measure ...</td>
      <td>EthnoVogue</td>
      <td>Women</td>
      <td>5810</td>
      <td>7</td>
      <td>Beige &amp; Grey made to measure kurta with churid...</td>
      <td>Beige</td>
    </tr>
    <tr>
      <th>2</th>
      <td>10009781</td>
      <td>SPYKAR Women Pink Alexa Super Skinny Fit High-...</td>
      <td>SPYKAR</td>
      <td>Women</td>
      <td>899</td>
      <td>7</td>
      <td>Pink coloured wash 5-pocket high-rise cropped ...</td>
      <td>Pink</td>
    </tr>
    <tr>
      <th>3</th>
      <td>10015921</td>
      <td>Raymond Men Blue Self-Design Single-Breasted B...</td>
      <td>Raymond</td>
      <td>Men</td>
      <td>5599</td>
      <td>5</td>
      <td>Blue self-design bandhgala suitBlue self-desig...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>4</th>
      <td>10017833</td>
      <td>Parx Men Brown &amp; Off-White Slim Fit Printed Ca...</td>
      <td>Parx</td>
      <td>Men</td>
      <td>759</td>
      <td>5</td>
      <td>Brown and off-white printed casual shirt, has ...</td>
      <td>White</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>105</th>
      <td>10013703</td>
      <td>PARFAIT Plus Size Women Black  Red Printed Lac...</td>
      <td>PARFAIT</td>
      <td>Women</td>
      <td>899</td>
      <td>2</td>
      <td>Black and red printed low-rise hipster briefs ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>106</th>
      <td>10012713</td>
      <td>MIAH Decor Set Of 5 Handcrafted Ceramic Kulladhs</td>
      <td>MIAH Decor</td>
      <td>Unisex</td>
      <td>865</td>
      <td>4</td>
      <td>Set Of 5 Ceramic Kulladhs Pattern: PrintedFini...</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>107</th>
      <td>10012875</td>
      <td>JEWEL JUNCTION Gold-Toned Geometric Cufflinks</td>
      <td>JEWEL JUNCTION</td>
      <td>Men</td>
      <td>539</td>
      <td>5</td>
      <td>A pair of gold-toned geometric textured cuffli...</td>
      <td>Gold</td>
    </tr>
    <tr>
      <th>108</th>
      <td>10015997</td>
      <td>Tokyo Talkies Women Black &amp; Red Floral Print F...</td>
      <td>Tokyo Talkies</td>
      <td>Women</td>
      <td>499</td>
      <td>5</td>
      <td>Black and Red printed woven fit and flare %S, ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>109</th>
      <td>10012771</td>
      <td>SEJ by Nisha Gupta Set of 6 Printed Table Plac...</td>
      <td>SEJ by Nisha Gupta</td>
      <td>Unisex</td>
      <td>899</td>
      <td>4</td>
      <td>Set content: 6 table matsShape: RectangleColou...</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>110 rows × 8 columns</p>
</div>



### Deta Inspection


```python
df.head()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductID</th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>10017413</td>
      <td>DKNY Unisex Black &amp; Grey Printed Medium Trolle...</td>
      <td>DKNY</td>
      <td>Unisex</td>
      <td>11745</td>
      <td>7</td>
      <td>Black and grey printed medium trolley bag, sec...</td>
      <td>Black</td>
    </tr>
    <tr>
      <th>1</th>
      <td>10016283</td>
      <td>EthnoVogue Women Beige &amp; Grey Made to Measure ...</td>
      <td>EthnoVogue</td>
      <td>Women</td>
      <td>5810</td>
      <td>7</td>
      <td>Beige &amp; Grey made to measure kurta with churid...</td>
      <td>Beige</td>
    </tr>
    <tr>
      <th>2</th>
      <td>10009781</td>
      <td>SPYKAR Women Pink Alexa Super Skinny Fit High-...</td>
      <td>SPYKAR</td>
      <td>Women</td>
      <td>899</td>
      <td>7</td>
      <td>Pink coloured wash 5-pocket high-rise cropped ...</td>
      <td>Pink</td>
    </tr>
    <tr>
      <th>3</th>
      <td>10015921</td>
      <td>Raymond Men Blue Self-Design Single-Breasted B...</td>
      <td>Raymond</td>
      <td>Men</td>
      <td>5599</td>
      <td>5</td>
      <td>Blue self-design bandhgala suitBlue self-desig...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>4</th>
      <td>10017833</td>
      <td>Parx Men Brown &amp; Off-White Slim Fit Printed Ca...</td>
      <td>Parx</td>
      <td>Men</td>
      <td>759</td>
      <td>5</td>
      <td>Brown and off-white printed casual shirt, has ...</td>
      <td>White</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.tail()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductID</th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>105</th>
      <td>10013703</td>
      <td>PARFAIT Plus Size Women Black  Red Printed Lac...</td>
      <td>PARFAIT</td>
      <td>Women</td>
      <td>899</td>
      <td>2</td>
      <td>Black and red printed low-rise hipster briefs ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>106</th>
      <td>10012713</td>
      <td>MIAH Decor Set Of 5 Handcrafted Ceramic Kulladhs</td>
      <td>MIAH Decor</td>
      <td>Unisex</td>
      <td>865</td>
      <td>4</td>
      <td>Set Of 5 Ceramic Kulladhs Pattern: PrintedFini...</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>107</th>
      <td>10012875</td>
      <td>JEWEL JUNCTION Gold-Toned Geometric Cufflinks</td>
      <td>JEWEL JUNCTION</td>
      <td>Men</td>
      <td>539</td>
      <td>5</td>
      <td>A pair of gold-toned geometric textured cuffli...</td>
      <td>Gold</td>
    </tr>
    <tr>
      <th>108</th>
      <td>10015997</td>
      <td>Tokyo Talkies Women Black &amp; Red Floral Print F...</td>
      <td>Tokyo Talkies</td>
      <td>Women</td>
      <td>499</td>
      <td>5</td>
      <td>Black and Red printed woven fit and flare %S, ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>109</th>
      <td>10012771</td>
      <td>SEJ by Nisha Gupta Set of 6 Printed Table Plac...</td>
      <td>SEJ by Nisha Gupta</td>
      <td>Unisex</td>
      <td>899</td>
      <td>4</td>
      <td>Set content: 6 table matsShape: RectangleColou...</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.head(4)

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductID</th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>10017413</td>
      <td>DKNY Unisex Black &amp; Grey Printed Medium Trolle...</td>
      <td>DKNY</td>
      <td>Unisex</td>
      <td>11745</td>
      <td>7</td>
      <td>Black and grey printed medium trolley bag, sec...</td>
      <td>Black</td>
    </tr>
    <tr>
      <th>1</th>
      <td>10016283</td>
      <td>EthnoVogue Women Beige &amp; Grey Made to Measure ...</td>
      <td>EthnoVogue</td>
      <td>Women</td>
      <td>5810</td>
      <td>7</td>
      <td>Beige &amp; Grey made to measure kurta with churid...</td>
      <td>Beige</td>
    </tr>
    <tr>
      <th>2</th>
      <td>10009781</td>
      <td>SPYKAR Women Pink Alexa Super Skinny Fit High-...</td>
      <td>SPYKAR</td>
      <td>Women</td>
      <td>899</td>
      <td>7</td>
      <td>Pink coloured wash 5-pocket high-rise cropped ...</td>
      <td>Pink</td>
    </tr>
    <tr>
      <th>3</th>
      <td>10015921</td>
      <td>Raymond Men Blue Self-Design Single-Breasted B...</td>
      <td>Raymond</td>
      <td>Men</td>
      <td>5599</td>
      <td>5</td>
      <td>Blue self-design bandhgala suitBlue self-desig...</td>
      <td>Blue</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.tail(3)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductID</th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>107</th>
      <td>10012875</td>
      <td>JEWEL JUNCTION Gold-Toned Geometric Cufflinks</td>
      <td>JEWEL JUNCTION</td>
      <td>Men</td>
      <td>539</td>
      <td>5</td>
      <td>A pair of gold-toned geometric textured cuffli...</td>
      <td>Gold</td>
    </tr>
    <tr>
      <th>108</th>
      <td>10015997</td>
      <td>Tokyo Talkies Women Black &amp; Red Floral Print F...</td>
      <td>Tokyo Talkies</td>
      <td>Women</td>
      <td>499</td>
      <td>5</td>
      <td>Black and Red printed woven fit and flare %S, ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>109</th>
      <td>10012771</td>
      <td>SEJ by Nisha Gupta Set of 6 Printed Table Plac...</td>
      <td>SEJ by Nisha Gupta</td>
      <td>Unisex</td>
      <td>899</td>
      <td>4</td>
      <td>Set content: 6 table matsShape: RectangleColou...</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.sample(3)

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductID</th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>40</th>
      <td>10004151</td>
      <td>HIGHLANDER Men Navy Blue &amp; Maroon Slim Fit Che...</td>
      <td>HIGHLANDER</td>
      <td>Men</td>
      <td>699</td>
      <td>5</td>
      <td>Navy Blue and maroon checked casual shirt, has...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>21</th>
      <td>10004155</td>
      <td>HIGHLANDER Men Mustard &amp; Black Slim Fit Checke...</td>
      <td>HIGHLANDER</td>
      <td>Men</td>
      <td>699</td>
      <td>5</td>
      <td>Mustard and black checked casual shirt, has a ...</td>
      <td>Black</td>
    </tr>
    <tr>
      <th>20</th>
      <td>10001265</td>
      <td>Michael Kors Women Sexy Amber Eau de Parfum 100ml</td>
      <td>Michael Kors</td>
      <td>Women</td>
      <td>7920</td>
      <td>3</td>
      <td>Michael Kors Sexy Amber Eau de ParfumFragrance...</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.shape
```




    (110, 8)




```python
df.size
```




    880




```python
df.info()
```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 110 entries, 0 to 109
    Data columns (total 8 columns):
     #   Column        Non-Null Count  Dtype 
    ---  ------        --------------  ----- 
     0   ProductID     110 non-null    int64 
     1   ProductName   110 non-null    object
     2   ProductBrand  110 non-null    object
     3   Gender        110 non-null    object
     4   Price (INR)   110 non-null    int64 
     5   NumImages     110 non-null    int64 
     6   Description   110 non-null    object
     7   PrimaryColor  103 non-null    object
    dtypes: int64(3), object(5)
    memory usage: 7.0+ KB



```python
df.describe()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductID</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>1.100000e+02</td>
      <td>110.000000</td>
      <td>110.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>9.846820e+06</td>
      <td>1748.754545</td>
      <td>4.727273</td>
    </tr>
    <tr>
      <th>std</th>
      <td>1.209320e+06</td>
      <td>2550.128636</td>
      <td>1.248185</td>
    </tr>
    <tr>
      <th>min</th>
      <td>1.000710e+06</td>
      <td>266.000000</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>1.000420e+07</td>
      <td>699.000000</td>
      <td>4.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>1.001277e+07</td>
      <td>946.500000</td>
      <td>5.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>1.001566e+07</td>
      <td>1577.750000</td>
      <td>5.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>1.001792e+07</td>
      <td>17360.000000</td>
      <td>7.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.columns
```




    Index(['ProductID', 'ProductName', 'ProductBrand', 'Gender', 'Price (INR)',
           'NumImages', 'Description', 'PrimaryColor'],
          dtype='object')




```python
df.describe(include='all')

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductID</th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>1.100000e+02</td>
      <td>110</td>
      <td>110</td>
      <td>110</td>
      <td>110.000000</td>
      <td>110.000000</td>
      <td>110</td>
      <td>103</td>
    </tr>
    <tr>
      <th>unique</th>
      <td>NaN</td>
      <td>104</td>
      <td>45</td>
      <td>5</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>108</td>
      <td>15</td>
    </tr>
    <tr>
      <th>top</th>
      <td>NaN</td>
      <td>Parx Men Blue Slim Fit Checked Casual Shirt</td>
      <td>Parx</td>
      <td>Men</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>Blue checked casual shirt, has a spread collar...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>freq</th>
      <td>NaN</td>
      <td>5</td>
      <td>13</td>
      <td>43</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>3</td>
      <td>38</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>9.846820e+06</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>1748.754545</td>
      <td>4.727273</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>std</th>
      <td>1.209320e+06</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2550.128636</td>
      <td>1.248185</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>min</th>
      <td>1.000710e+06</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>266.000000</td>
      <td>2.000000</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>1.000420e+07</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>699.000000</td>
      <td>4.000000</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>1.001277e+07</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>946.500000</td>
      <td>5.000000</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>1.001566e+07</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>1577.750000</td>
      <td>5.000000</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>max</th>
      <td>1.001792e+07</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>17360.000000</td>
      <td>7.000000</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.isnull()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductID</th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>1</th>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>3</th>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>105</th>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>106</th>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
    </tr>
    <tr>
      <th>107</th>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>108</th>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>109</th>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
<p>110 rows × 8 columns</p>
</div>




```python
df.loc[3]
```




    ProductID                                                10015921
    ProductName     Raymond Men Blue Self-Design Single-Breasted B...
    ProductBrand                                              Raymond
    Gender                                                        Men
    Price (INR)                                                  5599
    NumImages                                                       5
    Description     Blue self-design bandhgala suitBlue self-desig...
    PrimaryColor                                                 Blue
    Name: 3, dtype: object




```python
df.loc[15:20]
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductID</th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>15</th>
      <td>1000795</td>
      <td>Being Human Clothing Navy Printed Casual Slim ...</td>
      <td>Being Human</td>
      <td>Men</td>
      <td>1079</td>
      <td>6</td>
      <td>Navy blue printed casual shirt, has a spread c...</td>
      <td>Navy</td>
    </tr>
    <tr>
      <th>16</th>
      <td>10003803</td>
      <td>Homesake Gold-Toned &amp; White Solid Handcrafted ...</td>
      <td>Homesake</td>
      <td>Unisex</td>
      <td>1620</td>
      <td>5</td>
      <td>Type: Handcrafted Table Lamp with ShadeColour:...</td>
      <td>White</td>
    </tr>
    <tr>
      <th>17</th>
      <td>10012765</td>
      <td>SEJ by Nisha Gupta Set of 6 Mustard &amp; Blue Pri...</td>
      <td>SEJ by Nisha Gupta</td>
      <td>Unisex</td>
      <td>899</td>
      <td>4</td>
      <td>Set content: 6 table mats Shape: Rectangle Col...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>18</th>
      <td>10014413</td>
      <td>YAK YAK Men Camel Brown Solid Polo Collar T-shirt</td>
      <td>YAK YAK</td>
      <td>Men</td>
      <td>599</td>
      <td>5</td>
      <td>Camel brown solid T-shirt, has polo collar, sh...</td>
      <td>Brown</td>
    </tr>
    <tr>
      <th>19</th>
      <td>10013483</td>
      <td>PARFAIT Plus Size Black Striped Non-Wired Ligh...</td>
      <td>PARFAIT</td>
      <td>Women</td>
      <td>1749</td>
      <td>3</td>
      <td>Black striped medium-coverage T-shirt braLight...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>20</th>
      <td>10001265</td>
      <td>Michael Kors Women Sexy Amber Eau de Parfum 100ml</td>
      <td>Michael Kors</td>
      <td>Women</td>
      <td>7920</td>
      <td>3</td>
      <td>Michael Kors Sexy Amber Eau de ParfumFragrance...</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.iloc[1,3]
```




    'Women'




```python
df.iloc[-2,1]
```




    'Tokyo Talkies Women Black & Red Floral Print Fit and Flare Dress'




```python
df.rename(columns={"ProductID":"Product"},inplace=True)  
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Product</th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>10017413</td>
      <td>DKNY Unisex Black &amp; Grey Printed Medium Trolle...</td>
      <td>DKNY</td>
      <td>Unisex</td>
      <td>11745</td>
      <td>7</td>
      <td>Black and grey printed medium trolley bag, sec...</td>
      <td>Black</td>
    </tr>
    <tr>
      <th>1</th>
      <td>10016283</td>
      <td>EthnoVogue Women Beige &amp; Grey Made to Measure ...</td>
      <td>EthnoVogue</td>
      <td>Women</td>
      <td>5810</td>
      <td>7</td>
      <td>Beige &amp; Grey made to measure kurta with churid...</td>
      <td>Beige</td>
    </tr>
    <tr>
      <th>2</th>
      <td>10009781</td>
      <td>SPYKAR Women Pink Alexa Super Skinny Fit High-...</td>
      <td>SPYKAR</td>
      <td>Women</td>
      <td>899</td>
      <td>7</td>
      <td>Pink coloured wash 5-pocket high-rise cropped ...</td>
      <td>Pink</td>
    </tr>
    <tr>
      <th>3</th>
      <td>10015921</td>
      <td>Raymond Men Blue Self-Design Single-Breasted B...</td>
      <td>Raymond</td>
      <td>Men</td>
      <td>5599</td>
      <td>5</td>
      <td>Blue self-design bandhgala suitBlue self-desig...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>4</th>
      <td>10017833</td>
      <td>Parx Men Brown &amp; Off-White Slim Fit Printed Ca...</td>
      <td>Parx</td>
      <td>Men</td>
      <td>759</td>
      <td>5</td>
      <td>Brown and off-white printed casual shirt, has ...</td>
      <td>White</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>105</th>
      <td>10013703</td>
      <td>PARFAIT Plus Size Women Black  Red Printed Lac...</td>
      <td>PARFAIT</td>
      <td>Women</td>
      <td>899</td>
      <td>2</td>
      <td>Black and red printed low-rise hipster briefs ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>106</th>
      <td>10012713</td>
      <td>MIAH Decor Set Of 5 Handcrafted Ceramic Kulladhs</td>
      <td>MIAH Decor</td>
      <td>Unisex</td>
      <td>865</td>
      <td>4</td>
      <td>Set Of 5 Ceramic Kulladhs Pattern: PrintedFini...</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>107</th>
      <td>10012875</td>
      <td>JEWEL JUNCTION Gold-Toned Geometric Cufflinks</td>
      <td>JEWEL JUNCTION</td>
      <td>Men</td>
      <td>539</td>
      <td>5</td>
      <td>A pair of gold-toned geometric textured cuffli...</td>
      <td>Gold</td>
    </tr>
    <tr>
      <th>108</th>
      <td>10015997</td>
      <td>Tokyo Talkies Women Black &amp; Red Floral Print F...</td>
      <td>Tokyo Talkies</td>
      <td>Women</td>
      <td>499</td>
      <td>5</td>
      <td>Black and Red printed woven fit and flare %S, ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>109</th>
      <td>10012771</td>
      <td>SEJ by Nisha Gupta Set of 6 Printed Table Plac...</td>
      <td>SEJ by Nisha Gupta</td>
      <td>Unisex</td>
      <td>899</td>
      <td>4</td>
      <td>Set content: 6 table matsShape: RectangleColou...</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>110 rows × 8 columns</p>
</div>




```python
df.drop(columns=["Product"],inplace=True)  
df
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>DKNY Unisex Black &amp; Grey Printed Medium Trolle...</td>
      <td>DKNY</td>
      <td>Unisex</td>
      <td>11745</td>
      <td>7</td>
      <td>Black and grey printed medium trolley bag, sec...</td>
      <td>Black</td>
    </tr>
    <tr>
      <th>1</th>
      <td>EthnoVogue Women Beige &amp; Grey Made to Measure ...</td>
      <td>EthnoVogue</td>
      <td>Women</td>
      <td>5810</td>
      <td>7</td>
      <td>Beige &amp; Grey made to measure kurta with churid...</td>
      <td>Beige</td>
    </tr>
    <tr>
      <th>2</th>
      <td>SPYKAR Women Pink Alexa Super Skinny Fit High-...</td>
      <td>SPYKAR</td>
      <td>Women</td>
      <td>899</td>
      <td>7</td>
      <td>Pink coloured wash 5-pocket high-rise cropped ...</td>
      <td>Pink</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Raymond Men Blue Self-Design Single-Breasted B...</td>
      <td>Raymond</td>
      <td>Men</td>
      <td>5599</td>
      <td>5</td>
      <td>Blue self-design bandhgala suitBlue self-desig...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Parx Men Brown &amp; Off-White Slim Fit Printed Ca...</td>
      <td>Parx</td>
      <td>Men</td>
      <td>759</td>
      <td>5</td>
      <td>Brown and off-white printed casual shirt, has ...</td>
      <td>White</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>105</th>
      <td>PARFAIT Plus Size Women Black  Red Printed Lac...</td>
      <td>PARFAIT</td>
      <td>Women</td>
      <td>899</td>
      <td>2</td>
      <td>Black and red printed low-rise hipster briefs ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>106</th>
      <td>MIAH Decor Set Of 5 Handcrafted Ceramic Kulladhs</td>
      <td>MIAH Decor</td>
      <td>Unisex</td>
      <td>865</td>
      <td>4</td>
      <td>Set Of 5 Ceramic Kulladhs Pattern: PrintedFini...</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>107</th>
      <td>JEWEL JUNCTION Gold-Toned Geometric Cufflinks</td>
      <td>JEWEL JUNCTION</td>
      <td>Men</td>
      <td>539</td>
      <td>5</td>
      <td>A pair of gold-toned geometric textured cuffli...</td>
      <td>Gold</td>
    </tr>
    <tr>
      <th>108</th>
      <td>Tokyo Talkies Women Black &amp; Red Floral Print F...</td>
      <td>Tokyo Talkies</td>
      <td>Women</td>
      <td>499</td>
      <td>5</td>
      <td>Black and Red printed woven fit and flare %S, ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>109</th>
      <td>SEJ by Nisha Gupta Set of 6 Printed Table Plac...</td>
      <td>SEJ by Nisha Gupta</td>
      <td>Unisex</td>
      <td>899</td>
      <td>4</td>
      <td>Set content: 6 table matsShape: RectangleColou...</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>110 rows × 7 columns</p>
</div>




```python
df.isnull().sum()
```




    ProductName     0
    ProductBrand    0
    Gender          0
    Price (INR)     0
    NumImages       0
    Description     0
    PrimaryColor    7
    dtype: int64




```python
df.dropna()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>DKNY Unisex Black &amp; Grey Printed Medium Trolle...</td>
      <td>DKNY</td>
      <td>Unisex</td>
      <td>11745</td>
      <td>7</td>
      <td>Black and grey printed medium trolley bag, sec...</td>
      <td>Black</td>
    </tr>
    <tr>
      <th>1</th>
      <td>EthnoVogue Women Beige &amp; Grey Made to Measure ...</td>
      <td>EthnoVogue</td>
      <td>Women</td>
      <td>5810</td>
      <td>7</td>
      <td>Beige &amp; Grey made to measure kurta with churid...</td>
      <td>Beige</td>
    </tr>
    <tr>
      <th>2</th>
      <td>SPYKAR Women Pink Alexa Super Skinny Fit High-...</td>
      <td>SPYKAR</td>
      <td>Women</td>
      <td>899</td>
      <td>7</td>
      <td>Pink coloured wash 5-pocket high-rise cropped ...</td>
      <td>Pink</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Raymond Men Blue Self-Design Single-Breasted B...</td>
      <td>Raymond</td>
      <td>Men</td>
      <td>5599</td>
      <td>5</td>
      <td>Blue self-design bandhgala suitBlue self-desig...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Parx Men Brown &amp; Off-White Slim Fit Printed Ca...</td>
      <td>Parx</td>
      <td>Men</td>
      <td>759</td>
      <td>5</td>
      <td>Brown and off-white printed casual shirt, has ...</td>
      <td>White</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>103</th>
      <td>ID Men Tan Brown Formal Leather Oxfords</td>
      <td>ID</td>
      <td>Men</td>
      <td>1432</td>
      <td>5</td>
      <td>A pair of tan brown square-toed formal oxfords...</td>
      <td>Brown</td>
    </tr>
    <tr>
      <th>104</th>
      <td>Stylo Bug Girls Turquoise Blue A-Line Dress</td>
      <td>Stylo Bug</td>
      <td>Girls</td>
      <td>698</td>
      <td>7</td>
      <td>Turquoise Blue printed woven A-line dress, has...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>105</th>
      <td>PARFAIT Plus Size Women Black  Red Printed Lac...</td>
      <td>PARFAIT</td>
      <td>Women</td>
      <td>899</td>
      <td>2</td>
      <td>Black and red printed low-rise hipster briefs ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>107</th>
      <td>JEWEL JUNCTION Gold-Toned Geometric Cufflinks</td>
      <td>JEWEL JUNCTION</td>
      <td>Men</td>
      <td>539</td>
      <td>5</td>
      <td>A pair of gold-toned geometric textured cuffli...</td>
      <td>Gold</td>
    </tr>
    <tr>
      <th>108</th>
      <td>Tokyo Talkies Women Black &amp; Red Floral Print F...</td>
      <td>Tokyo Talkies</td>
      <td>Women</td>
      <td>499</td>
      <td>5</td>
      <td>Black and Red printed woven fit and flare %S, ...</td>
      <td>Red</td>
    </tr>
  </tbody>
</table>
<p>103 rows × 7 columns</p>
</div>




```python
df.fillna(0)
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>DKNY Unisex Black &amp; Grey Printed Medium Trolle...</td>
      <td>DKNY</td>
      <td>Unisex</td>
      <td>11745</td>
      <td>7</td>
      <td>Black and grey printed medium trolley bag, sec...</td>
      <td>Black</td>
    </tr>
    <tr>
      <th>1</th>
      <td>EthnoVogue Women Beige &amp; Grey Made to Measure ...</td>
      <td>EthnoVogue</td>
      <td>Women</td>
      <td>5810</td>
      <td>7</td>
      <td>Beige &amp; Grey made to measure kurta with churid...</td>
      <td>Beige</td>
    </tr>
    <tr>
      <th>2</th>
      <td>SPYKAR Women Pink Alexa Super Skinny Fit High-...</td>
      <td>SPYKAR</td>
      <td>Women</td>
      <td>899</td>
      <td>7</td>
      <td>Pink coloured wash 5-pocket high-rise cropped ...</td>
      <td>Pink</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Raymond Men Blue Self-Design Single-Breasted B...</td>
      <td>Raymond</td>
      <td>Men</td>
      <td>5599</td>
      <td>5</td>
      <td>Blue self-design bandhgala suitBlue self-desig...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Parx Men Brown &amp; Off-White Slim Fit Printed Ca...</td>
      <td>Parx</td>
      <td>Men</td>
      <td>759</td>
      <td>5</td>
      <td>Brown and off-white printed casual shirt, has ...</td>
      <td>White</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>105</th>
      <td>PARFAIT Plus Size Women Black  Red Printed Lac...</td>
      <td>PARFAIT</td>
      <td>Women</td>
      <td>899</td>
      <td>2</td>
      <td>Black and red printed low-rise hipster briefs ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>106</th>
      <td>MIAH Decor Set Of 5 Handcrafted Ceramic Kulladhs</td>
      <td>MIAH Decor</td>
      <td>Unisex</td>
      <td>865</td>
      <td>4</td>
      <td>Set Of 5 Ceramic Kulladhs Pattern: PrintedFini...</td>
      <td>0</td>
    </tr>
    <tr>
      <th>107</th>
      <td>JEWEL JUNCTION Gold-Toned Geometric Cufflinks</td>
      <td>JEWEL JUNCTION</td>
      <td>Men</td>
      <td>539</td>
      <td>5</td>
      <td>A pair of gold-toned geometric textured cuffli...</td>
      <td>Gold</td>
    </tr>
    <tr>
      <th>108</th>
      <td>Tokyo Talkies Women Black &amp; Red Floral Print F...</td>
      <td>Tokyo Talkies</td>
      <td>Women</td>
      <td>499</td>
      <td>5</td>
      <td>Black and Red printed woven fit and flare %S, ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>109</th>
      <td>SEJ by Nisha Gupta Set of 6 Printed Table Plac...</td>
      <td>SEJ by Nisha Gupta</td>
      <td>Unisex</td>
      <td>899</td>
      <td>4</td>
      <td>Set content: 6 table matsShape: RectangleColou...</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>110 rows × 7 columns</p>
</div>




```python
df.drop_duplicates()
```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>ProductName</th>
      <th>ProductBrand</th>
      <th>Gender</th>
      <th>Price (INR)</th>
      <th>NumImages</th>
      <th>Description</th>
      <th>PrimaryColor</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>DKNY Unisex Black &amp; Grey Printed Medium Trolle...</td>
      <td>DKNY</td>
      <td>Unisex</td>
      <td>11745</td>
      <td>7</td>
      <td>Black and grey printed medium trolley bag, sec...</td>
      <td>Black</td>
    </tr>
    <tr>
      <th>1</th>
      <td>EthnoVogue Women Beige &amp; Grey Made to Measure ...</td>
      <td>EthnoVogue</td>
      <td>Women</td>
      <td>5810</td>
      <td>7</td>
      <td>Beige &amp; Grey made to measure kurta with churid...</td>
      <td>Beige</td>
    </tr>
    <tr>
      <th>2</th>
      <td>SPYKAR Women Pink Alexa Super Skinny Fit High-...</td>
      <td>SPYKAR</td>
      <td>Women</td>
      <td>899</td>
      <td>7</td>
      <td>Pink coloured wash 5-pocket high-rise cropped ...</td>
      <td>Pink</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Raymond Men Blue Self-Design Single-Breasted B...</td>
      <td>Raymond</td>
      <td>Men</td>
      <td>5599</td>
      <td>5</td>
      <td>Blue self-design bandhgala suitBlue self-desig...</td>
      <td>Blue</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Parx Men Brown &amp; Off-White Slim Fit Printed Ca...</td>
      <td>Parx</td>
      <td>Men</td>
      <td>759</td>
      <td>5</td>
      <td>Brown and off-white printed casual shirt, has ...</td>
      <td>White</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>105</th>
      <td>PARFAIT Plus Size Women Black  Red Printed Lac...</td>
      <td>PARFAIT</td>
      <td>Women</td>
      <td>899</td>
      <td>2</td>
      <td>Black and red printed low-rise hipster briefs ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>106</th>
      <td>MIAH Decor Set Of 5 Handcrafted Ceramic Kulladhs</td>
      <td>MIAH Decor</td>
      <td>Unisex</td>
      <td>865</td>
      <td>4</td>
      <td>Set Of 5 Ceramic Kulladhs Pattern: PrintedFini...</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>107</th>
      <td>JEWEL JUNCTION Gold-Toned Geometric Cufflinks</td>
      <td>JEWEL JUNCTION</td>
      <td>Men</td>
      <td>539</td>
      <td>5</td>
      <td>A pair of gold-toned geometric textured cuffli...</td>
      <td>Gold</td>
    </tr>
    <tr>
      <th>108</th>
      <td>Tokyo Talkies Women Black &amp; Red Floral Print F...</td>
      <td>Tokyo Talkies</td>
      <td>Women</td>
      <td>499</td>
      <td>5</td>
      <td>Black and Red printed woven fit and flare %S, ...</td>
      <td>Red</td>
    </tr>
    <tr>
      <th>109</th>
      <td>SEJ by Nisha Gupta Set of 6 Printed Table Plac...</td>
      <td>SEJ by Nisha Gupta</td>
      <td>Unisex</td>
      <td>899</td>
      <td>4</td>
      <td>Set content: 6 table matsShape: RectangleColou...</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>110 rows × 7 columns</p>
</div>




```python
df["Gender"].value_counts().plot(kind='bar')
```




    <Axes: xlabel='Gender'>




    
![png](output_28_1.png)
    



```python
df["ProductName"].value_counts().plot(kind="kde")
```




    <Axes: ylabel='Density'>




    
![png](output_29_1.png)
    



```python
df["Gender"].value_counts().plot(kind="pie")
```




    <Axes: ylabel='count'>




    
![png](output_30_1.png)
    

