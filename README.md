<h1 align=center> School District Analysis </h1>

<h2> Overview </h2>
<p> For this project we were tasked with using Pandas to assess records from a school district once it was found out that one of the schools faked a small number of grades </p>
<h2> Results </h2>

***
* How is the district summary affected?
  * The faked grades had a very small effect at the district level only dropping the overall passing rate by .1% 
***
![Screenshot 2022-11-02 062341](https://user-images.githubusercontent.com/106105597/199465930-2e2cc397-03e7-4a75-b807-25566126a456.png)
![Screenshot 2022-11-02 062417](https://user-images.githubusercontent.com/106105597/199465975-3cfa8004-1bb7-4dfc-81b3-961a83be602b.png)

***
* How is the school summary affected?
  * Thomas High School only dropped a small percent in overall passing. The faked grades only accounted for .3% of their their grades
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * The faked grades did not change Thomas High School's position as the second best school by overall passing %
***
![Screenshot 2022-11-02 063512](https://user-images.githubusercontent.com/106105597/199468159-b73c6bb8-67c7-4626-b65f-e9d234b57b56.png)
![Screenshot 2022-11-02 063442](https://user-images.githubusercontent.com/106105597/199468085-d49b0732-d0a4-4ee1-aab9-6a5f770cedb0.png)

***
* How does replacing the ninth-grade scores affect math and reading scores by grade
  * The ninth-grade scores for math and reading were replaced by nan values for Thomas High School so they were just taken out of the equation. The other grades were unaffected

***
* How does replacing the ninth-grade scores affect scores by school spending
  * The by budget summary was unaffected
***
![Screenshot 2022-11-02 064020](https://user-images.githubusercontent.com/106105597/199469127-53c23ad3-4aa5-49f7-9146-e2c507e6269c.png)
![Screenshot 2022-11-02 063839](https://user-images.githubusercontent.com/106105597/199468801-8e6cfda4-3d09-43e4-9993-5f35efe321f0.png)

***
* How does replacing the ninth-grade scores affect scores by school size
  * The by size summary was unaffected
***
![Screenshot 2022-11-02 064223](https://user-images.githubusercontent.com/106105597/199469589-6f0f194f-1697-4ae1-940d-3c9d83c92b35.png)
![Screenshot 2022-11-02 064153](https://user-images.githubusercontent.com/106105597/199469454-b161f93e-f8f8-4113-8884-6dd9f54c73b7.png)

***
* How does replacing the ninth-grade scores affect scores by school type
  * The by school type summary was unaffected
***
![Screenshot 2022-11-02 064303](https://user-images.githubusercontent.com/106105597/199469704-028d5b8f-9453-451c-8c06-20dd6a54ce8f.png)
![Screenshot 2022-11-02 064319](https://user-images.githubusercontent.com/106105597/199469762-cae59208-624d-414f-9fec-1fbe4cb8d471.png)

<h2> Summary </h2>
<p> While it was wrong to do ultimately very little was affected by the faked grades. The following came out of it: </p>

***
* The district dropped .1% in overall testing scores
* The school dropped .3% in overall testing scores
* The 9th grade reading scores were taken out of the records
* the 9th grade math scores were taken out of the records
***
