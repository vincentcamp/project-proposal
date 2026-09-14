# QueueNYU

## What and why?

QueueNYU is a mobile web application designed to help NYU students understand how busy different locations around campus are before they actually go there. The basic problem is that NYU's campus is spread throughout the city, and students frequently have to make decisions about where to study, eat, exercise, or spend time without knowing whether a particular location is overcrowded.

For example, a student might walk to Bobst looking for somewhere to study only to find that most of the desirable spaces are full, or go to a dining hall between classes and encounter a long line. At that point, going somewhere else can require another 10 or 15 minute walk, which may not be practical between classes. While students often communicate this information informally through friends and group chats, there is no centralized way to quickly see what different locations are currently like.

QueueNYU would essentially create a real-time, crowdsourced map of NYU. Students could look at a location and see its current estimated level of activity, recent reports from other students, and historical trends showing when that location tends to be busiest. The goal is not necessarily to predict exactly how many people are somewhere, but rather to give students enough information to make a better decision about where to go.

## For whom?

The primary users would be NYU students, particularly students who regularly use campus facilities such as Bobst Library, dining halls, gyms, lounges, and other study spaces.

The initial users would be NYU students that we already have direct access to through our classes, friends, and other student communities. This makes it relatively easy to speak directly with potential users throughout development and understand which locations and information would actually be useful to them.

The application could eventually be useful for other universities as well, particularly schools with large urban campuses, but the initial product would deliberately focus on NYU so that the application can be designed and tested around a specific group of real users.

## How?

When opening QueueNYU, users would see a mobile-friendly interface containing nearby or commonly used NYU locations. They could either browse these locations as a list or view them geographically on a map.

Each location would have a page displaying its current estimated crowd level, such as "Quiet," "Moderate," "Busy," or "Very Busy." This estimate would be based primarily on recent reports submitted by students.

Students who are currently at a location could quickly submit an update about its current conditions. Reporting would intentionally require very little effort so that students actually have an incentive to contribute. For example, a student at Bobst could select the floor they are on, indicate how crowded it is, and submit the report in a few seconds.

Recent reports could also include useful information specific to the type of location. At a dining hall, students might report the approximate wait time. At a study space, they could report whether finding an open seat is easy or difficult. At a gym, they could indicate how crowded the facility currently is.

The application would aggregate recent reports to produce an overall estimate rather than relying entirely on a single person's submission. Reports would become less important as they get older so that information from several hours ago does not incorrectly represent current conditions.

Users would also be able to view historical information for each location. For example, someone could see that a particular dining hall is usually busiest around 12:30 PM or that a certain study space tends to become crowded in the evening. This would allow QueueNYU to remain useful even when there are not enough recent user reports to confidently describe the current situation.

Users could create accounts and save locations they frequently visit as favorites. Their home screen could then immediately show current conditions at those locations. A student who regularly uses Bobst, Palladium, and Kimmel, for example, would be able to quickly compare all three.

Another potential feature would be notifications. A user could ask to be notified when a particular location becomes less crowded, rather than repeatedly checking the application themselves.

The application could also include a basic contribution or reputation system to encourage participation. Users who regularly provide useful reports could receive points or other indicators of their contribution. Reports could also be confirmed by other students, helping prevent inaccurate information from having too much influence on the overall estimate.

## Scope

I believe QueueNYU has an appropriate scope for a team of approximately 4–6 programmers working over one semester because the fundamental application is relatively straightforward, while still containing several distinct components that require meaningful development.

The core product would require user authentication and profiles, a database of NYU locations, a mobile-friendly interface, map and location functionality, user-submitted reports, aggregation of those reports into current crowd estimates, and historical data visualization. Additional functionality such as favorites, notifications, reputation, and location-specific reporting would provide further work once the core system is functioning.

At the same time, the project does not depend on solving an unrealistic technical problem. A useful initial version could be built using crowdsourced reports and historical information without requiring specialized hardware or perfect real-time occupancy detection. This also makes the project relatively modular: the team could establish a functional core application early in the semester and then progressively improve the accuracy of estimates and add more advanced features.

The result should therefore be substantial enough to divide among several developers while still being realistic to build, test with actual NYU students, and deploy within one semester.