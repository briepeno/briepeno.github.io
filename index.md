# Computer Science Portfolio

## Professional Self-Assessment

I am currently completing my Bachelor of Science in Computer Science with a concentration in Data Analytics. Throughout the program, I have been able to build on what I have learned from one course to the next and develop a better understanding of the different areas of computer science. 

## Code Review

I completed a code review of the artifacts selected for my ePortfolio. In the review, I discuss the original projects, areas for improvement, and the enhancements I planned to make.

[Watch My Code Review on YouTube](https://youtu.be/yNWTr3VL82Q?si=dhwXgj3HLGFskzEf)

## Software Design and Engineering

<a href="https://github.com/briepeno/briepeno.github.io/blob/main/WeightTrackingApplication_Original.zip">
  Original Artifact
</a>
The artifact I chose for the software design and engineering category is a weight tracking Android application. I first created it in February 2026 for CS 360 and enhanced it in September 2026 for CS 499. The original version let users create an account, add or delete weight entries, set a goal, view their history, and receive an SMS notification when they reached that goal. I built it in Java and used SQLite to store the application’s data.
I selected this artifact because it had a lot of room for improvement. The original app could store weight records, but it did not help the user understand what those records meant. I added a dashboard showing the starting, current, and goal weights along with total change, remaining weight, recent trends, and goal progress. A line chart now shows how the user’s weight changes over time. I strengthened the validation for weights, goals, phone numbers, passwords, and usernames as well. Behind the interface, I separated the validation, calculations, navigation, chart, and weight-record logic into their own classes. This cut down on repeated code and kept MainActivity from becoming responsible for everything. Tests were added for the calculations and validation rules.
My original plan connected this enhancement to Course Outcomes 3, 4, and 5, and those outcomes still fit the completed work. The progress calculations address Outcome 3 because they handle weight loss, weight gain, missing goals, and different amounts of weight history. Outcome 4 is covered through the way Java, Android, SQLite, RecyclerView, SharedPreferences, SMS notifications, and the chart work together. I decided to build the line chart myself instead of adding a library because the app only needed a basic visualization. For Outcome 5, I focused on checking user input before it reached the database and handling missing information without causing the app to crash. Passwords are still stored in plain text, so hashing remains an important security improvement for a future version.
The biggest lesson came from working with the same data in different ways. The history list needs the newest entries first, while the chart and progress calculations need them from oldest to newest. I also learned that refreshing a RecyclerView does not automatically reload its data. The adapter had to retrieve the updated records before the display could actually change. Moving the calculation logic out of MainActivity made those rules easier to test without involving the screen itself.
Navigation caused more trouble than I expected. Each screen needed to behave the same way, and at one point the Settings page would not open correctly. I also had to make sure the dashboard refreshed whenever I returned to it. Another decision involved password hashing. I know storing plain-text passwords would not be acceptable in a production application, but hashing was outside the scope of my original enhancement. Since this app is a prototype and I had limited time, I focused on the features I had already planned and left hashing as future work.
Cleaning up the repeated code was another challenge. At first, I thought condensing it would simply mean using fewer lines. Instead, I ended up moving navigation, validation, and calculations into separate classes and keeping the SMS logic in one place. Some parts became longer, but the overall project became easier to follow because each class had a clearer job.

<a href="https://github.com/briepeno/briepeno.github.io/blob/main/WeightTrackingApplication_Enhanced.zip">
  Enhanced Artifact
</a>

## Algorithms and Data Structures

Artifact information will be added here.

## Databases

Artifact information will be added here.
