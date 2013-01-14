########################## README FILE WITH SAMEBRICK FLASH GAME BY SUNNEFA ##############################

Please note that currently in the game the highscores are being loaded from an online file. I've included the actual PHP file responsible for handling the highscores and you can use that if you want to but please be aware that that file must reside on a server and it needs access to MySQL. I've also included a backup of my online highscores database which you can import on your local server. Please note that the MySQL username, database name and password in the PHP file will have to be changed for that to work.
To change the path to the highscores file, open Static.as, scroll down to the bottom and change the return value of the get scoreURL function. It is the last function in the file.

If you wish to see my game online:
http://dev.playdesigncode.com/samebricks