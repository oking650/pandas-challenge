# pandas-challenge
<<<<<<< HEAD
Repository containing Pandas Module 4 Code
=======

This report involved a student performance dataset from a school district containing 15 schools, ranging from District to Charter Schools. Within the Dataset, we have a collection of metrics ranging from Reading and Writing scores by Student, to School Budget and School type.

The analysis first required merging two data tables, the student table and school table, in order to best analyze and contextualize the impact of a school's environment (Size, Type, Budget, etc.) on a Student's reading and writing performance. Once the merged DataFrame was created, we first performed a high-level summary analysis on the key District metrics. This summary table is named "Image_District_Overview" in the Repository, and includes the number of schools, students, total budget of the district, average math and reading scores and percentages, and the overall passing rate of the district. Once we created this summary table, we then delved into the dataset more specifically, in order to determine trends or correlations within the data.

We then collected similar metrics on the school level, also including "Per Student Budget" as an additional metric ("Image_School_Overview"). By grouping these KPIs by School, we are able to begin comparing metrics across different School Types, Sizes, and Budgets to determine and relationship on Student performance. By filtering on the "% Overall Passing" metric, we can see a pattern emerge. When looking at the five best-performing schools, we observe that every school in the top five is a Charter school. In addition, only one of these five schools is considered a "large" school. This may be explained by the definition of a Charter School itself. While open to the public, Charter Schools are a "school of choice," meaning that parents need to decide to send their child to the school, rather than a public school, which is determined by where you live. This provides initiative for Charter Schools to demonstrate their value, and the best way to demonstrate this is by incentivizing and showing high test scores of their student population. We can clearly see the effect of this incentive in the table (Image_school_Highest_Performers).

Conversely, looking at the lowest performers (Image_School_Lowest_Performers) we see that all five schools are large, district schools. While the Per Student Budget is comparable, the sheer number of students imply that there is a higher student-teacher ratio, which limits learning opportunities and resources for each student.

We then looked at student scores by grade, for both reading and writing. Based on the two tables (Image_Grade_Math, Image_Grade_Reading), it is difficult to infer any conclusions from the data. While the data is consistent by school, there doesn't appear to be too strong of a relationship between a student's grade and their school performance.

Finally, we binned the schools into three categories: spend per student, school size, and school type. Spend per student showed that perhaps surprisingly, schools with lower spend per student had the highest test grades, and this trend maintained as spend increased by student (Image_School_Spending_Bins). For school size, we a similar trend, that smaller schools perform better, and we especially see the gap in performance from "Medium" sized schools to "Large" Schools. This further supports the idea that having more Teachers for the Student body provides Students with better teaching resources, support, and guidance in their education. For school type, it is clear the Charters schools vastly outperformed district schools across all KPI's, regardless of size or budget (Image_School_Type). This supports my hypothesis about Charter schools' incentive to demonstrate their quality and performance, and to do so, achieve high test scores with their student body.









>>>>>>> 60fe52a3472ed205b948fb3590ebb60b6ed1be33

