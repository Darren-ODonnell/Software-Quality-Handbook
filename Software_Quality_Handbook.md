**Testing**

Testing is vital within software engineering for ensuring a program fulfils its’ intended purpose. Testing enables the programmer to have confidence that his future changes have not caused issues with work prior. 

Some general guidelines for ensuring code quality through testing are as follows:

\-     Test one thing at a time. Tests should be as granular as possible. This ensures that what you are testing will not be disrupted by other methods which are the cause of error. Testing should begin with the most granular section, with the least dependencies. 

<img src="images/TheTestingPyramid.png"     alt="The Testing Pyramid"     style="float: left; margin-right: 10px;" />

 

\-     Be diligent towards testing edge cases: This is done because edge cases are the most common culprit resulting in errors. An example of an edge case is having an exam result where if <= 40 would result in a fail and the provided result was 40, declaring the grade as a pass.

 

\-     Ensure that all developers involved in the feature being tested are aware of the full scope of how this feature needs to work and how it will integrate with the wider system. This provides greater frame of references for people to debug future issues arising as a result of any unsuspected errors resulting from this feature.

 

\-     Make sure to do quick sanity checks before kicking off a long-winded regression test. These should also be done at night so they don’t eat into your working hours.

 

Testing granularity: https://www.headspin.io/blog/the-testing-pyramid-simplified-for-one-and-all

 https://martinfowler.com/articles/practical-test-pyramid.html

Edge Cases: https://www.mindfulqa.com/edge-cases/

Team Cohesion: https://www.indeed.com/career-advice/career-development/team-cohesiveness

Sanity testing vs Regression Testing:

https://www.testgrid.io/blog/sanity-testing-vs-regression-testing/

https://www.geeksforgeeks.org/difference-between-sanity-testing-and-regression-testing/




**Task Estimation in Scrum**

Task estimation is a crucial Scrum procedure that aids the team in efficiently planning and monitoring their work. It involves teams estimating how much time tasks will need to be completed and divides the larger tasks into smaller ones. Task estimation aids in the team's development of a realistic Sprint plan, early detection of potential obstacles or dependencies, and transparency regarding the work that needs to be done.

https://www.tothenew.com/blog/how-to-estimate-story-points-in-agile/

Planning Poker

Planning poker is a collaborative technique used in agile software development to estimate the effort and complexity required for each task or user story. The main purpose of this is to promote collaboration between team members and provide more accurate estimations. 

The general steps to follow to use Planning Poker effectively include: 

-	Inviting all teams members to participate during the scrum meeting
-	Use a deck of playing cards with corresponding values.
-	Each team member chooses a card that corresponds to their estimation.
-	Talk about and resolve any discrepancies in estimations.
-	Continue until a decision is reached.

Some of the main challenges involved in Planning Poker are allowing team members to dominate the discussion and rushing the final descion and not taking the time to reconcile different estimates. 

https://blog.moove-it.com/asynchronous-planning-poker-estimations/

Benefits and Limitations

Benefits

Improved Decision Making – breaks down work items into smaller tasks, allowing the team to develop a realistic strategy for the sprint, make appropriate plans, and have a clear understanding of the amount of work to be done.

Increased Transparency - provides visibility into the work required for each job in the Sprint Backlog, enabling the team to identify potential obstacles and dependencies early and take proactive measures to overcome them.

Other Benefits Include:
-	Enhanced collaboration
-	Improved productivity
-	Better Risk Management
-	More accurate forecasting

Limitations

Inaccuracy: Task estimation in Scrum is subject to inaccuracy due to various factors such as unforeseen obstacles, unexpected delays, or changes in requirements, leading to a potential mismatch between planned and actual work completed during a Sprint.

Inflexibility: It may also result in inflexibility when it becomes difficult to adjust an estimate due to unexpected complexities or changes, leading to a lack of adaptability to changing circumstances.

Other Limitations include:
-	Focus on time instead of value
-	Time-consuming
-	Over-reliance on estimation
-	One Sit All Estimation

https://www.netsolutions.com/insights/how-to-estimate-projects-in-agile/

https://doasync.com/blog/8-agile-estimation-mistakes-to-avoid/

https://core.ac.uk/download/pdf/84071282.pdf


**Code Review**

Code review is when peers review others' code to improve quality, help developers learn and detect bugs. These code reviews are important as they offer both the developer and the reviewer a chance to learn. It can let them learn from their mistakes and also keep the code of the project consistent with what is already in the codebase.

A good code review can be helpful for many reasons.If there are high standards of coding in the development team, it can allow developers to reuse code. This code reuse can be highly productive as it can save time allowing developers to focus on other aspects.

A code review should also have a checklist. This checklist should cover a variety of different topics such as, does it meet the requirements or is there documentation or is the code maintainable. This checklist makes it so all aspects are looked at in the code review

Having a good tool allows code reviews to be done easier and allows the same techniques to be used each time. An example of a tool would be GitHub.

You can use pull requests that have to be reviewed and approved by a team member where they can provide feedback on your code. It also allows the developer to write a document outlining what exactly the code does, what the changes are and what outcome should happen from these changes.

One of the most important things about code reviews is about fixing the issues that come up during it. These issues could range from small issues such as formatting code the wrong way to having to redo the entire process again. 

It's important that from this the developer is shown why these mistakes happened and try to help them avoid this in the future. Setting up meetings to go over these issues in further detail is a good idea to help paint a clear picture for the developer.

https://www.codereviewchecklist.com/
https://www.brightspot.com/cms-resources/technology-insights/5-reasons-why-the-code-review-process-is-critical-for-developers
https://blog.jetbrains.com/space/2021/12/15/best-code-review-tools/

