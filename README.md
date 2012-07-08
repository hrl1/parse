parsing
=====

First change config.json to whatever options you prefer, and then

	npm install

packages. Then run 

	node dict_to_db.js

to fill the database. (client currently doesn't close the connection so do it manually after a few seconds. sorry).
To test sentences, you can change the "query" string in test.js, then run 

	node test.js

