## Semester Overview

Over the course of the semester, I have learned the basics of database management, how to develop an advanced Flask project, proper documentation techniques, and finally unit testing. As this was my first semester in RCOS, I have throughly enjoyed my time working on Hedgehogs and I have definitely learned a lot from my time on the team.

1) I started by developing unit testing for xlsxDownloader.py. When I began, I started by creating unit tests for our web scraper (from sec.gov) and tested various parts of the web scraping and data conversion process in my test file. This allowed me to better understand the program flow and begin working on more advanced tasks as a result. Doing this allowed me to learn about proper testing and how we must reach a certain coverage in the code.
 
2) Created a initializion script for the PostgreSQL database (provisionSchema.py). This was my first "advanced" task for the project and I had to learn a lot as I have never worked with a database before. After I finished the script, it ultimately allowed for a schema to be created and each company to have its own table of the data in the schema. This update allowed the new data collector (using an API instead of scraping) to place data into the database.

3) Originally, the program had things such as database passwords, API keys and other secrets hardcoded into the program. I created a file parser (simpleParser.py) that assumes there exists a file that contains all the passwords and then all the other files in the program simply import simpleParser.py and call their respective method to get their keys/passwords. This made it so we didn't have any passwords/secrets on Github

4) As the entire program had next to no documentation, I took up the task of documenting the large majority of the program. I followed a unified documenting style (Google) and went through almost every script for the data collection and data storage and properly documented it. I believe this will tremendously help future developers of Hedgehogs. 

5) As the previous front-end was not fully functional and did not have any documentation, I chose to rewrite it entirely and learned Flask from scratch at the same time as well. This was the most challenging for me as I had a deadline (the presentation) and I was the only one working on the front-end. Thankfully, I got the website functioning with proper CSS (which took a long time) and got the stock data graphs to display on the website when the user inputs a company and chooses a data variation (low, high, close, open). I learned a lot from this task as I learned how to create a web app using Flask and also the basics of HTML and CSS (such as centering items and properly formatting items on the website to look clean). Even though this took some time, I had the most fun doing this as I really enjoyed working on the website and learning so much.

6) The last thing I did was the large majority of the user login system. I created the User class (making sure the passwords are hashed) and also implemented the majority of the code needed in the Flask app for the login and registration pages. The only thing holding me back is my knowledge on databases as the last hurdle is simply storing the Users in the database. Once that small task complete, the login system will be fully functional as I implemented the rest of the system. 

## Important Notes
During the semester, some of my commits randomly switched to my other GitHub account so my commits are under two accounts (srikanthtumati and arangetramvrl)



