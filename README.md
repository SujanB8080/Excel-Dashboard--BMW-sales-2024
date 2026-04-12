# BMW Sales Dashboard 2024

&#x20;

Excel Skills are Important for Data Analysis this repository is intend to showcase basic excel skills.

I have created excel dashboard "BMW sales dashboard 2024" from the data that i have taken from the kaggale dataset "BMW sales(2010-2024)" which focuses on 2024 data and gives the answer to the questions prepared by me. 

This excel dashboard will answer the questions as follows:

1\) what is the sales volume of each model in 2024?

2\) BMW sales volume by each continent 2024?

3\) which models are lowest and highest sold in 2024?

4\) Costliest models ?

5\) BMW most sold colour of highest sold models 2024?

6\) BMW most sold fuel type of most sold car 2024



##### Procedures followed



###### 1.Data Collection

Used BMW sales dataset (2010-2024) CSV file from Kaggle

###### 

###### 2.Data Cleaning and Transformation

* In excel new worksheet Under Data Tab in ribbon **Get Data** section **"from file text/csv"** select the CSV file and load data
* CSV Dataset with **50,000** was loaded successfully.
* Used **Power Query** Editor to get the required amount of data.
* Removed unwanted column , shuffled the price column ,selected only 2024 year under year column and loaded the cleaned data.
* sampled the dataset taking only 2024 data containing **3,427 rows** from original data.



###### 3.Data Analysis

* Used "Descriptive statistics" to get idea about the data on "Price column".
* created pivot tables, charts and slicers that are required to analyse the data 



###### 4.Dashboard 2024

Dashboard contains pivot tables and charts which analyzes and answers the questions as follows

1. The sales of each model can be seen in 'sales by model pivot chart and table' ;it is telling that there is significant sales of "X6, Series 3,Series 5, and Series 7 " models.

2. We can tell that there has been more sales in Asia then the rest of the continents.

3. The least sold model is "M3" with 7.54% and the one which sold highest is "X6" with 10.48%.

4. The Costliest model in 2024 is "i8" model ; Though there is less price range between models (I have taken max price of all models during creation of pivot table through **value field settings**.)

5. The most sold **colours** of highest sold model can be viewed in "**Most sold colours by models**" chart. Example if select X6 model in **slicer** we can see that ther is a 20% sales in Blue colour signifies that customers prefered "Blue" in X6 model.

6. The most sold **fule type** of highest sold model can be viewed in "**Sales by fuel type**" chart. Example if select X6 model in slicer we can see that ther is a 20% sales in Blue colour signifies that customers prefered "Diesel" configuration X6 model.





&#x20;     



