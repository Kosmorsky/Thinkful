Challenge: Evaluate an experiment analysis

__Now it's time to flex your critical evaluation skills. Read the following descriptions of an experiment and its analysis, identify the flaws in each, and describe what you would do to correct them.__

__The Sith Lords are concerned that their recruiting slogan, "Give In to Your Anger," isn't very effective. Darth Vader develops an alternative slogan, "Together We Can Rule the Galaxy." They compare the slogans on two groups of 50 captured droids each. In one group, Emperor Palpatine delivers the "Anger" slogan. In the other, Darth Vader presents the "Together" slogan. 20 droids convert to the Dark Side after hearing Palpatine's slogan, while only 5 droids convert after hearing Vader's. The Sith's data scientist concludes that "Anger" is a more effective slogan and should continue to be used.__

A few things could be wrong here. Are they all the same type of droids? If not, they should be evenly split up by type.
Even then, there is a possibility that ALL droids will respond better to Vader's slogan. In that case, other races should be tested besides droids.
There is also a chance that the droids are responding better to either Palpatine himself or his delivery of the slogan.
In this case, both slogans should be presented by the same person to avoid this bias.

__In the past, the Jedi have had difficulty with public relations. They send two envoys, Jar Jar Binks and Mace Windu, to four friendly and four unfriendly planets respectively, with the goal of promoting favorable feelings toward the Jedi. Upon their return, the envoys learn that Jar Jar was much more effective than Windu: Over 75% of the people surveyed said their attitudes had become more favorable after speaking with Jar Jar, while only 65% said their attitudes had become more favorable after speaking with Windu. This makes Windu angry, because he is sure that he had a better success rate than Jar Jar on every planet. The Jedi choose Jar Jar to be their representative in the future.__

This is a case of Simpson's paradox. It's possible that Jar Jar had a better overall success rate even though Mace had better success per group, due to differing group sizes.
To solve this, group size should be taken into account when speaking to inhabitants to ensure a more fair comparison.
NOTE: Regardless, Jar Jar should absolutely not be chosen as a representative over Mace Windu for obvious reasons.

__A company with work sites in five different countries has sent you data on employee satisfaction rates for workers in Human Resources and workers in Information Technology. Most HR workers are concentrated in three of the countries, while IT workers are equally distributed across worksites. The company requests a report on satisfaction for each job type. You calculate average job satisfaction for HR and for IT and present the report.__

The country/location could be a factor in employee satisfaction in addition to job type, skewing the data.
The total satisfaction should not be calculated. Instead, satisfaction averages per job should be taken from each location.

__When people install the Happy Days Fitness Tracker app, they are asked to "opt in" to a data collection scheme where their level of physical activity data is automatically sent to the company for product research purposes. During your interview with the company, they tell you that the app is very effective because after installing the app, the data show that people's activity levels rise steadily.__

While the rise in physical activity could be a result of the effectiveness of the app itself, it could have nothing to do with it.
If a user installs a fitness app, they are likely doing so because they are planning on getting to shape, as opposed to getting in shape because they are installing a fitness app.
In order to accurately guage the effectiveness of their fitness app, the company would need to compare their app's results to a control or (better yet) another fitness app.

__To prevent cheating, a teacher writes three versions of a test. She stacks the three versions together, first all copies of Version A, then all copies of Version B, then all copies of Version C. As students arrive for the exam, each student takes a test. When grading the test, the teacher finds that students who took Version B scored higher than students who took either Version A or Version C. She concludes from this that Version B is easier, and discards it.__

While this may be the result of test B being easier, the teacher did not consider the intelligence of each student taking the exam.
Since the exams were essentially randomly distributed to the students, there is a chance that more of the smarter students recieved exam B, skewing the data.
Another note, students who study together often arrive to exams together, so a group of kids who studied well would likely all get the same exam since they are all stacked in order. If they showed up in the middle of the pack they would get exam B.
A way to eliminate this possibility would be to alternate every exam (A,B,C) when handing them out to students.