# Project Test #

### What is this repository for? ###

* A twitter clone

### How do I get set up?

* Clone this repo
* Run `npm i` and `composer install`
* Build project `npm run dev`
* Copy `.env-example` to `.env` for environment configuration
* Change `config/database.php` file - default value to `mysql` or any database you are using (I used pgsql just for heroku)
* Create database and update `DB_` configs in `.env`
* Create and Migrate database `php artisan migrate`
* Run `php artisan key:generate`
* Run `php artisan storage:link`
* Run php server `php artisan serve`
* To build for production, just run `npm run prod`

### Functionalities

* Register user with name, email, password and avatar.
* Login and Logout.
* Create, update, and delete own tweets.
* Create, update, and delete own comments in a tweet.
* Follow and unfollow users.
* Search tweets and users by text.
* View list of followers, following, and own tweets.
* Send and view messages from/to users.

### Who do I talk to? ###

* Mervin Villaceran
