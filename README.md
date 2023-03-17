## About the Dataset
This is a large stocks dataset of about 400MB which contained will be loaded onto **HDFS** and transformed into a Scala DataFrame using Spark. 

## Tools
Instead of running the **Spark engine** in the GCP VM engine, it was intiated in **Zeppelin Notebook** due to its user-friendly interface and ability to handle error with ease. 

## Analysis
### Loading the stocks dataset into a directory in **Hadoop**

![image](https://user-images.githubusercontent.com/121362860/226058484-7aa58738-5d9a-4541-a98e-97f11f68cf1b.png)

### Creating the **SPARK** schema in **Zeppelin Notebook**

![image](https://user-images.githubusercontent.com/121362860/226058607-4b6b0988-f3a3-48f6-a97b-0b42452ca328.png)

Commands were written to answer below questions about the dataset.
+ Stocks with an average daily volume greater than 1 million shares.

![image](https://user-images.githubusercontent.com/121362860/226059997-7f9a4340-2d11-408f-8656-7546cd9fadf9.png)

- Top 3 stocks by volume for the year 2004

![image](https://user-images.githubusercontent.com/121362860/226059794-fc8892ce-bb54-4618-889a-6f2ba5a69d2c.png)

+ Top 3 stocks by volume whose symbol starts with “G”

![image](https://user-images.githubusercontent.com/121362860/226059700-63ceffa2-cb95-4ef2-8984-94f344665364.png)

* Symbols whose closing price are larger than my age

![image](https://user-images.githubusercontent.com/121362860/226059670-9c9e0ec3-7e92-41ca-962c-d1fb5511c105.png)

- Top 10 stocks with the largest intraday price change

![image](https://user-images.githubusercontent.com/121362860/226059641-9f2ac73e-ce1f-44e7-8243-7e33f31c8518.png)




