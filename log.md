# 100 Days Of Code - Log

### Day 0: December 21, 2020

**Today's Progress**: I've read an email from freeCodeCamp and stumble across a challenge called 100 Days Of Code, I decided to join it.

**Thoughts:** I'm a bit curious about the challenge and decided to check it out. Well, turns out it's a great challenge and i think it'll be good if i committed to the challenge. About my learning progress, today i learned Postgre sql and run through the installation and environment setup, i've also learned postgreSQL data types. Turns out it's not so different from MySQL for the query, but i notice that Postgre has another data types like point, line and circle which MySQL doesn't have; 

**Link to work:** it's on my local environment so yeah, no links;

### Day 1: December 22, 2020

**Today's Progress**: Fixed one of my Discord Bot command, i've also continue my learning progress on Postgresql.

**Thoughts:** I've been working on a discord bot for a while now. So this morning i noticed a bug on one command, it's called covid-country command which returns an information aboutcovid-19 cases in specific country. I had fixed it, but then another bug were surfaced, the requested data for China is not right and data for United States  did not returned at all. After i checked the API request on Postman app, i realized that China and US have a different JSON format. Then i checked the API documentation and i change the api request slug with a proper one. But there's another problem, now it's coming from the API, my former request slug includes Country Code on it json response while the later still had the Country Code key but all of it's value is empty string. I had to do a workaround for that by creating a new function which used to find country code from different api request. I've also changed a section of my code to asynchronous behaviour in order to get the function work properly. Before this moment i don't really care about asynchronous programming since i never put it to good use, but today i feel the power of magic word Async Await, it's damn cool!.

**Link to work:** https://github.com/altf4m88/HistoBot;



### Day 2: December 23, 2020

**Today's Progress**: Added new fun command to Histobot.

**Thoughts:** Today i created a new command for my discord bot, btw his name is HistoBot. The new command is a |joke command that returns a random joke. I've created the .js file and wrote the main code, i've also updated the command handler, url constant list and help.js command list. But i haven't tested nor debug it yet because my connection is painfully slow. I can't even login to Discord and i can't access my Bot on hosting environment, so i wrote the command on my local environment and certainly going to test it tomorrow. Then i'm going to push the commit to my github repo and finally pull the update on the hosting environment.

**Link to work:** https://github.com/altf4m88/HistoBot;

### Day 3: December 24, 2020

**Today's Progress**: Tested the discord joke command.

**Thoughts:** I'm finally able to test my new bot command, and it work without errors. I've also updated the message embed style so it looks simpler. I'm looking forward to add more commands but haven't come up with a decent idea yet, maybe i'll work on another project for a while. Today i've also helped some friends to solve errors on their postgresql, i'm glad to help but there's one with different problem though. The error seems related to the microsoft account or something, it said "cannot no mapping between accounts and security id was done" when installing postgresql. I've scoured the internet trying to find the answer and haven't found that one solution to crack the egg, maybe i'll try again tomorrow.

**Link to work:** https://github.com/altf4m88/HistoBot;

### Day 4: December 25, 2020

**Today's Progress**: Going through some responsive web design challenge on freeCodeCamp.

**Thoughts:** I decided to go back to the basic, the good ol' html and css. I've planned to finish the Responsive Web Design certifications by January 2021, or faster would be better.

**Link to work:** https://www.freecodecamp.org/fcc5e017f9a-8e51-468e-a97d-e7fdc24d36d4;

### Day 5: December 26, 2020

**Today's Progress**: Going through another wave of challenge on FCC.

**Thoughts:** The rate of progress is great, but this is not a 'real' challenge yet. I'm looking forward to start the first responsive project ASAP.

**Link to work:** https://www.freecodecamp.org/fcc5e017f9a-8e51-468e-a97d-e7fdc24d36d4;

### Day 6: December 27, 2020

**Today's Progress**: Started my 'first' freeCodeCamp responsive web design project.

**Thoughts:** Today i've laid up the groundwork for the project, i wrote all the element that required to pass the test, 8 out of 10 passed. I just have to style it now and make it responsive. I'm going to complete it tomorrow

**Link to work:** https://codepen.io/altf4m88/pen/mdrqYve;
