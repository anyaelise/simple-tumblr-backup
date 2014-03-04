simple-tumblr-backup
====================

##Description
Simple backup script for Tumblr posts and likes, using Python and MongoD

##Dependencies
pytumblr, pymongo

##Instructions
* Create a .json file in the root directory with the format:
```
{
	"blog":"xxx",
	"consumer_key":"xxx",
	"consumer_secret":"xxx",
	"oauth_token":"xxx",
	"oauth_token_secret":"xxx"
}
```
* Execute backup.py

