# rsge_lookup
Project to use the Runescape GE API as per https://runescape.wiki/w/Grand_Exchange_Database instructions
  Quirk: database returns records in a json that is pagenated and categorized. In addeition, each page will return approx 12 items (strange)

Goal: provide a list of items above the threshold of 1m.
  As the information is not normally sorted, data will need to be stored locally
  Using python to handle requests and sqlite to store the data locally
  GUI will be provided seperately
  Database updates will be handled in the future

Need to know:
  How many API requests are allowed
 
 
Alternative:
* Scrape/query the RS Wiki database of items to download
* Create a wiki calculator to perform this instead of application



Checking git actions here
- Push from WSL Successful.
    - Editing in windows VS code.
    - Commiting from windows VS code.
