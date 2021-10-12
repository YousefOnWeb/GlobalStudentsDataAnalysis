# Programme for International Student Assessment | [PISA](https://www.oecd.org/pisa/) <br>2012 Survey Results Exploration

## by Yousef Abdrabo

## Dataset

> The Programme for International Student Assessment is a worldwide study 
> by the Organisation for Economic Co-operation and Development ([OECD](https://www.oecd.org/))
>  intended to evaluate educational systems by measuring 15-year-old 
> school pupils' scholastic performance on mathematics, science, and 
> reading in form of a survey, this exploration makes use of the dataset 
> of the survey's results to gather to answer some related questions.
> 
> ### Dataset Structure
> 
> > - **Data Form:** Tabular
> > 
> > - **Data Container:** CSV file
> > 
> > - **Size:** 2.8 Gigabytes
> > 
> > - **Columns:** 636
> > 
> > - **Rows:** 485490
> 
> ### Main Points of Interest in The Dataset
> 
> > **1.** Student's Diversity in Everyday-Experieneces  
> > **2.** Differences in different students' subjects of focus  
> > **3.** Student's family existance conditon  
> > **4.** Student's Integration and Satisfaction towards Education  
> > **5.** Age of starting education  
> > **6.** Student encouraged towards critical thinking or not  
> > **7.** Student teaching himself freely with his preffered techniques  
> > **8.** Student-teacher relation  
> > **9.** Student learning maths interactively and visually  
> > **10.** Student's language
> 
> ### Features in The Dataset Supporting the Investigation Into The Above Points of Interest:
> 
> #### 1. Student's Diversity in Everyday-Experieneces:Student's distance between multiple experienced cultures (CULTDIST)
> 
> > - Student plays chess? (column ST49Q06)
> > - Student familiar with computer programming? (column ST49Q07)
> > - Student has game console? (column IC01Q05)
> > - Student has internet connection (column IC01Q04)
> > - Student plays single player games out of school? (IC08Q01)
> > - Student uses email out of school? (IC08Q03)
> > - Student chats online? (IC08Q04)
> > - Student on social networks? (IC08Q05)
> > - Student browses internet for fun? (IC08Q06)
> > - Student reads news? (IC08Q07)
> > - Student obtains practical information from the internet? (IC08Q08)
> > - Student streams music? (IC08Q09)
> > - Student uploads content? (IC08Q11)
> > - Student classifies as using ICT for entertainment? (ENTUSE)
> > - Student Student limits use of computers as a tool for only schooling? (ICTATTNEG)
> > - Student has ICT availability at home? (ICTHOME)
> > - Student owns a computer? (ST26Q04)
> 
> #### 2. Differences in Different Students' Subjects of Focus
> 
> > - Student age (AGE)
> > - Student gender (ST04Q01)
> > - Student into maths or language courses after school? (ST48Q01)
> > - Student into maths or science courses after school? (ST48Q02)
> > - Student studies harder in maths vs language? (ST48Q03)
> > - Student takes more maths or science classes? (ST48Q04)
> > - Student into career of maths vs science? (ST48Q05)
> > - Student open for problem solving? (OPENPS)
> 
> #### 3. Student's Family Existance Conditon
> 
> > - Student mother at home? (ST11Q01)
> > - Student father at home? (ST11Q02)
> > - Student brothers at home? (ST11Q03)
> > - Student sisters at home? (ST11Q04)
> > - Student grandparents at home? (ST11Q05)
> 
> #### 4. Student's Integration and Satisfaction towards Education
> 
> > - Student claims performing poorly regardless? (ST43Q06)
> > - Student claims teacher not explaining well? (ST44Q03)
> > - Student claims material is too hard? (ST44Q05)
> > - Student claims teacher didn't get students interested? (ST44Q07)
> > - Student pays attention in classes? (ST46Q06)
> > - Student claims teacher provides extra help? (ST77Q02)
> > - Student claims teacher provides help in general? (ST77Q04)
> 
> #### 5. Age of starting education
> 
> > - Student age at Grade ISCED 1 (primary education) (ST06Q01)
> 
> #### 6. Student Encouraged Towards Critical Thinking or Not
> 
> > - Student's teacher encourages expresssing opinions? (ST77Q06)
> > - Student's teacher encourages reasoning? (ST79Q02)
> > - Student's teacher gives problems requiring thinking? (ST80Q04)
> > - Studen't teacher asks to use own procedures? (ST80Q05)
> > - Studen't teacher presents problems with no abvious solutions (ST80Q06)
> 
> #### 7. Student Teaches Himself Freely with His Preffered Techniques
> 
> > - Out-of-school computer study time (ST57Q06)
> 
> #### 8. Student-teacher Relation
> 
> > - Student get along with teachers (ST86Q01)
> > - Student's teacher is interested (ST86Q02)
> > - Student's teacher listens to questions (ST86Q03)
> > - Student's teacher gives help (ST86Q04)
> > - Student's teacher treats students fair (ST86Q05)
> 
> #### 9. Student Learning Maths Interactively and Visually
> 
> > - Student draws graphs? (IC11Q01)
> > - Student practices? (IC11Q02)
> > - Student experiences geometric figures? (IC11Q03)
> > - Student experiences spreadsheets? (IC11Q04)
> > - Student experiences histograms? (IC11Q06)
> > - Student changes in graphs? (IC11Q07)
> 
> #### 10. Student Language
> 
> > - Student's language at home (LANGN)
> 
> ### Features Used Only to Assist Wrangling
> 
> #### To Help Specify Duplicates and Uniques
> 
> > - Student Identification Code (STIDSTD)
> > - School Identification Code (SCHOOLID)

<br>

## Summary of Findings

> * The average age for a student took part in the survey resulting in the dataset appears to be almost 16 years, distributed like a uniform distribution that's a skewed as reaching the age limits of 15.2 and 16.3.
>   
>   <img title="age histogram" src="/Images/index.png" alt="age histogram" width="397" data-align="inline">
>   <br>
>   <hr>
> 
> * Distribution of age of starting grade ISCED 1 (starting primary education), there are some outliers staring education at the age of 8 and above, but they are not removed as they can unlock interesting findings not found in the mainstream of students data.
>   
>   <img src="/Images/index2.png" title="Text to show on mouseover" alt="alt text for screen readers" width="397">
>   <br><hr>
> 
> * On a global scale (talking about all countries combined), female students are 4638 more than male students in the dataset, which is nearly 0.0001 percent, so they are almost equal in count when neglecting each country's individual biological sex gap.
>   
>   <img src="/Images/index3.png" title="Text to show on mouseover" alt="alt text for screen readers" width="397">
>   <br><hr>
> 
> * Most students are either moderate or extreme about using ICT for entertainment, which means, only very few students use ICT for entertainment by a factor between moderate and extreme, and the majority of students are either moderate or extreme.
>   When comparing moderate to extreme entertainment use of ICT, moderate is proven to be way more frequent, with the change in frequency being exponential.
>   
>   <img src="/Images/index4.png" title="Text to show on mouseover" alt="alt text for screen readers" width="397">
>   <br><hr>
> 
> * Spanish, English, Portuguese, Italian, and Arabic are the top 5 languages spoken at home respectively in the observation.
>   
>   <img src="/Images/index5.png" title="Text to show on mouseover" alt="alt text for screen readers" width="586">
>   <br><hr>
> 
> * As the out-of-school computer study time increases uniformly, the amount of students decrease exponentially.
>   
>   <img src="/Images/index6.png" title="Text to show on mouseover" alt="alt text for screen readers" width="395">
>   <br><hr>
> 
> * ICT avalibily factor among students is distributed normally and at the same time a little bit left skewed, in other words, students that have extremely high ICT availability are a little bit more than students having extremely low ICT availability, while ICT availability remaining distributed normally around moderate.
>   
>   <img src="/Images/index8.png" title="hist" alt="hist" width="395">
>   <br><hr>
> 
> * Students' problem solving skills factor is distributed normally and at the same time left skewed, which mean, students that have extremely high problem solving skills are more frequent than students having extremely low problem solving skills, while problem solving skills remaining distributed normally around moderate.
>   
>   <img src="/Images/index9.png" title="prob solv hist" alt="prob solv hist" width="395">
>   <br><hr>
> 
> * **A.** Students not being playing chess makes the gap bigger by 79% between students familiar and not familiar with programming, with not familiar with programming being less, which is a concerning gap change precentage.<br>
>   **B.** Students not being exposed to video games makes the gap bigger by 15% between students familiar and not familiar with programming, with not familiar with programming being less, which is a gap change precentage that can be reasonable.
>   ![fig](/Images/index10.png "fig")
>   Which is also proven when using the variable: (Problem-solver factor)
>   ![fig](/Images/index11.png "fig")
>   <br><hr>
> 
> * Students being exposed to video games makes the gap bigger by 14% between students preferring maths and language, with students preferring maths being more.
>   ![life experience vs fav subj](/Images/index12.png "life experience vs fav subj")
>   <br><hr>
> 
> * Students not being exposed to video games makes the gap bigger by 15% between students preferring maths and science, with students preferring science being more.
>   ![live vs fav subj](/Images/index13.png "live vs fav subj")
>   <br><hr>
> 
> * **A.** Students being playing chess makes the gap bigger by 40% between female and male students, with male students being more.<br>
>   **B.** Students not being exposed to video games makes the gap bigger by 46% between female and male students, with male students being less.<br>
>   **C.** Students not reading news makes the gap bigger by 14% between female and male students, with male students being less.
>   ![life vs bio. sex](/Images/index14.png "life vs bio. sex")
>   <br><hr>
> 
> * **A.** Students preferring language courses (rather than maths) makes the gap bigger by 16% between female and male students, with male students being less.<br>
>   **B.** Students preferring to study language (rather than maths) also makes the gap bigger by 16% between female and male students, with male students being less.
>   ![subj vs bio. sex](/Images/index16.png "subj vs bio. sex")
>   <br><hr>
> 
> * **A.** Teacher providing help made gap increase by 16% between students who say they do poorly regardless and who don't, with less students saying they do poorly regardless.<br>
>   **B.** Teacher being fair made gap increase by 20% between students who say they do poorly regardless and who don't, with less students saying they do poorly regardless.
>   ![student-teacher relation vs educational performance](/Images/index18.png "student-teacher relation vs educational performance")
>   <br><hr>
> 
> * Teacher allowing expressing opinions made gap increase by 18% between students who pay attention in class and those who don't, with more students paying attention.
>   ![crit vs edu](/Images/index20.png "crit vs edu")
>   <br><hr>
> 
> * **A.** Father being at home made gap increase by 14% between students who say they do poorly regardless and who don't, with less students saying they do poorly regardless.<br>
>   **B.** Mother being at home made gap increase by 31% between students who say they do poorly regardless and who don't, with less students saying they do poorly regardless.
>   ![family exist vs edu. performance](/Images/index21.png "family exist vs edu. performance")
>   <br><hr>
> 
> * Student having a computer made gap increase by 18% between students who have they fathers at home and those who don't, with students having their father being more, which possibly can be the reason for the previous finding, because of financial reasons.
>   
>   <img src="/Images/index22.png" title="father at home vs tech access" alt="father at home vs tech access" width="693">
>   <br><hr>
> 
> * When ICT availability at home increases its use for entertainment also increases, which is the  strongest linearly-related pair of quantitive variables in the data sample
>   ![corr. coffs](/Images/index23.png "corr coffs") <br>
>   Which is also proven by the following binned scatterplot:
>   ![scatter](/Images/index24.png "scatter") <br>
>   And also by the following 2d histogram: <br>
>   ![2D hist](/Images/index25.png "2D hist")
>   <br><hr>
> 
> * Whenever out-of-school computer study time increases, the age of starting education decreases, and vice versa; which means, students of the highest education starting age that are also studying on computer alot barely exist.
>   
>   <img src="/Images/index26.png" title="scatters1" alt="scatters 1" width="687">
>   <br><hr>
> 
> * **A.** It's clear more male students are using ICT for fun.<br>
>   **B.** Students starting education at older ages are way more moderate about using ICT for Fun, which means, they neither use ICT for maximum fun nor for minimum fun.<br>
>   **C.** The Exact same for students studying on computer out of school alot, they are more moderate about using ICT for fun, which means, they neither use ICT for maximum fun nor for minimum fun.
>   ![scatters 2](/Images/index28.png "scatters 2")
>   <br><hr>
> 
> * **The first plot on the left:** As reaching the bottom right of the plot, the amount of students decrease, and the opposite when reaching the top left, which means, most students are **(both starting education at a younger age and using computers only for education)** and less students are **(both starting education at older age and NOT using computers only for education)**.  
>   In other words, as the age of starting education increases and computer education only use decreases (at the same time), the amount of students decrease.
>   ![scatters 3](/Images/index30.png "scatters 3")
>   <br><hr>
> 
> * **The plot in the middle:** As the out-of-school computer study time increases, student being a problem solver becomes more moderate, instead of being low or extreme.
>   ![scatters 4](/Images/index31.png "scatters 4")
>   <br><hr>
> 
> * **A.** Most students who are having a very high problem-solver factor are male students.
>   
>   **B.** More male students use computer for school, but not way more.
>   ![hist 2d pair 1](/Images/index32.png "Text to show on mouseover")
>   <br><hr>
> 
> * **A.** Students preferring maths are more condenced in the area of being problem solvers
>   
>   **B.** Students preferring language are more condenced in the area of being less of a problem solver
>   
>   **C.** Students classifying as having extreme problem-solver factor are way more frquent when student prefers maths.
>   ![hist 2d pair 2](/Images/index33.png "hist 2d pair 2")
>   <br><hr>
