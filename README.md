# MissionToMars

Mission to Mars is a practice exercise for web scrapping. 
Using programs and databases like SPlinter, Flask, and MongoDB, I created a Bootstrap Website to display some images and facts about Mars.

At the top of the page, a button prompts the user to find new data. 
This launches a script that goes to multiple websites, including Twitter and official NASA pages, to get up-to-date images and facts.
The script is littered with extra sleep timers to ensure all website HTML/CSS was loaded and readable. 
This means that the process of updating the site takes approximately 2 minutes to repopulate.
If I wasn't worried about sites locking me out when they realize the bot I created, I would make the application much faster.

My favorite part about this aplication is the updating of the current temperature on Mars.
