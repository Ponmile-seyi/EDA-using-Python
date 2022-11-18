In this project, you will find me use Python Pandas and Seaborn library to show a few key points in the dataset under study.

I started by importing the following libraries;
- Numpy
- Pandas
- Seaborn
- Matplotlib

Then I used the Pandas read_csv keyword to move the dataset from my C: drive to my Jupyter Notebook, and the head() keyword to show the first 5 records in the dataset.

The exploratory data analysis started by using the shape() and describe() keywords where the former is used to show the number of rows and columns that make up the dataset, while the latter gives a quick overview of the quantitative series present in the dataset. I also then used the nunique() keyword to get an idea of how widely distributed the entries in each columns are.

Cleaning the data was a ride in the park, actually, I did not have to do anything. I used the isnull().sum() to know the total number of null values in each columns but it turns out there is none. Next thing I did was to remove some columns that I was not going to use in my analysis. Two of such columns were removed using the drop() keyword.

After all these, I decided to prove my understanding of the Seaborn library by deploying it in visualizing the relationships that existed between the variables in the dataset.

I started the relationship analysis by doing a correlation analysis using the corr() keyword and subsequently plotting using seaborn's heatmap plot. This analysis shows that there is a strong positive relationship between all scores obtained in the three exams. The relationship between the Reading and Writing was the highest and this suggests that students who did well in reading also did very well in the writing exam.

I used more seaborn plots like the catplot(), distplot(), pairplot() to show relationship that exist in my dataset, but of all of these, the most insightful is the relplot() which showed a scatterplot relationship between the math scores and reading scores obtained by both genders. From this scatter plot, we can deduce that most of the females had their best scores in reading exams.

I totally enjoyed doing this as it has helped me develop my data analysis skills using Python.
