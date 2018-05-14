# Personal Resume

## Basic html, css and js resume

Deployed live site: http://sophie-chhoeu.ml/


### Cheatsheet for deployment on heroku

- Add a file called composer.json to the root directory by running touch composer.json
- Add a file called index.php to the root directory by running touch index.php
- Rename the homepage (e.g. index.html) to home.html
- In index.php, add the following line: <?php include_once("home.html"); ?>
- In composer.json, add the following line: {}
- git add and commit files
- Run git push heroku master
- Done! Visit your deployed single-page website, hosted by Heroku (as a fake PHP app ☺).
