The Dataset contains 2000 rows and the following columns.

id	

first\_name

last\_name

email

gender

part\_time\_job

absence\_days

extracurricular\_activities

weekly\_self\_study\_hours

career\_aspiration

math\_score

history\_score

physics\_score

chemistry\_score

biology\_score

english\_score

geography\_score



Summary:

Firstly, I have created a new columns named "Total\_Score" that clubs together all the scores for simpler data analysis. In my Analysis I found the following statistical data for the numerical columns present in our data



||absence\_days|weekly\_self\_study\_hours|math\_score|history\_score|physics\_score|chemistry\_score|biology\_score|english\_score|geography\_score|Total\_Score|
|-|-|-|-|-|-|-|-|-|-|-|
|mean|3.6655|17.755|83.452|80.332|81.3365|79.995|79.5815|81.2775|80.888|566.8625|
|median|3|18|87|82|83|81|81|83|81|567|
|mode|0 2|0 3 1 4|0 99|0 88|0 96|0 94 1 96|0 100|0 90|0 88|0 574|
|std|2.629|12.12|13.22|12.73|12.53|12.77|13.7221|12.027|11.637|42.29|





As we can see the scores are multi modal for the most part. Also, for the most part the data varies a lot from the mean as implied by the standard deviation and all the mean, median are nearly equal except for math\_score. This implies most follow a nearly normal distribution in terms of the spread of numbers.





Now let's look at one more analysis. Comparison of scores between students that work a part\_time\_job(True) and that don't(False).



In this I have seen the following data



||False|True|
|-|-|-|
|Mean|570.39|548.03|
|Median|570.0|552.0|
|Mode|574|554|
|Std|40.623150|45.9708|





As we can see the students that don't work tend to score a little higher than students that do a part time job on average. Medians for the respective groups also tend to lie near the mean implying a normal distribution of Values in the groups. With a single mode for the groups. The scores also tend to vary more in student that go to a part time job.



THis helps us see how a tiny activity can cause a hit to the scores of the student.





Then in our outlier analysis we have see many lower values implying some student's performance being lower than optimal. This can be seen through our Box plot in the Visualization Folder of this repository.

