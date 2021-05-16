# Analysis of Players for Spanish futbol League: La Liga (season 17-18) 

Visualization of players 'La liga' Season 17-18

I'll detail the steps to get some analytics of players from 'La Liga', season 17-18

Using: 
Get URL from chrome 
Postman - to get the request code
Atom IDE to mimic the request from the website, and create the DB
Python Pandas - To analyze the data ad get some visuals


1. Get database from www.whoscored.com.
for this example will use the DB from players from 'La Liga' in the season 17-18.
Link to webpage:
https://www.whoscored.com/Regions/206/Tournaments/4/Seasons/6960/Stages/15375/PlayerStatistics/Spain-LaLiga-2017-2018

2. get the DB url from the website:
inspect -> Network -> XHR and 'copy as cURL (bash)' the Name that starts with 'GetPlayerstat...'

3. Get the python request code:
Enter to Postman (www.postman.com), download and create an account, then import:
Import -> raw text -> copy the cURL -> CodeSnippet -> Python-Requests
Copy the Python request

4.  Mimic the request in your IDE
Copy the python request in your IDE (I use Atom), and run to create the DB in CSV format

5. Work the DB
Use Jupyter IDE and Pandas to create some visualization of the DB created.
