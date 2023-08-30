## Description
We implemented the known game 'hangman',
where the player has to guess a word by guessing letters. <br>
All the web pages are secured and restricted to logged-in users only. <br>
We have 2 types of users: admin and regular user. <br>
The admin can add new entries (categories + words) to the game, and delete existing entries. <br>
The regular user can play the game and submit his score to the highscores board.

## Credentials
There are 3 users:
* admin (password: 1234):
can add new entries (categories + words) to the game, and delete existing entries in the admin page.<br>
The admin page is available by clicking on the settings icon in the navbar (it is shown only if the admin is logged-in).

* ranel (password: 1234)
* idan (password: 1234) <br>
regular players, can play the game and submit their score to the highscores board. 


## Installation
We already inserted some words to the db in the listener,
but you can also add more words and categories in the admin page, or delete existing ones.

![hangman](\src\main\resources\static\images\hangman.JPG)
![admin](\src\main\resources\static\images\admin_page.JPG)

<br><br>
Made by @idanc7596 and me.