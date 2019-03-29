## Last Week's Accomplishments

Fixed a number of small bugs in provisionSchema that were preventing the program from properly running.
Pushed provisionSchema to production. I confirmed it was working (through external code) and can also confirm it works in the project at a later date once we have the super user password.
Now it is possible to store each company's data in a seperate table while at the same time, in the same schema. I believe write permissions for the schema could be a thing to look into.


## This Week's Plan

Now that provisionSchema is complete, it would be best to work on the program flow where provisionSchema runs immediately before the web scraper (so the proper schema/tables are intialized) and 
then we are able to process all the stock data and properly place it into the database.

Additionally, I would like to go back and document existing files to make working on them easier for the current team and any future members who are a part of the project in the future. I would like
to finish documenting the files in data-pipeline by the end of the week.

## Anything Blocking?

There is nothing blocking me.

## Notes

