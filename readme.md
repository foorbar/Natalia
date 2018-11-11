# Natalia, a Telegram Administrative assistant bot by @whalepoolbtc - https://whalepool.io   

A simple telegram bot to help with the moderation of the telegram channels utilizing [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)


### Requirements
1) Mongodb  
2) Install pip requirements `sudo pip3.6 install -r requirements.pip`    

### Setup config
`cp test2.sample.yaml test2.yaml`  
Edit the test2.yaml file accordingly  
You will have to edit/set some of the rooms under `natalia.py` for your room id's and feed room ids etc  

### Run
To run:  
`python3.6 test2.py`

For more info join [@whalepoolbtc](https://t.me/whalepoolbtc) on telegram   

![Profile pic](http://i.imgur.com/iIUSRDG.jpg)



 
### TODO

Escape users names when writing messages to them `helpers.escape_markdown(` 


Auto delete direct file 
	Unless posted or forwarded by a mod 

If mod replys to message: - Filters.reply(message

	ban 					bot.kick_chat_member(chat_id, user_id, until_date=None)
	unban					bot.unban_chat_member(chat_id, user_id):  					chat_id/channelusername, user_id, 
	readonly				bot.restrict_chat_member(chat_id, user_id, until_date=None)
	nogifs 					bot.restrict_chat_member(chat_id, user_id, until_date=None, can_send_messages=True)
		global/ None
		duration

	autodelete				




	timestamp, messageid, chatid, userid, username, type( command, sticker, gif, join, leave, video, pinned_message, message ), data 

	request
		- pm/group
		- text
	
	sticker
		- stickerid
		- stickerpackname 
		- fileid
		- path
		- filename
		- emoji
		- width
		- height
		

	gif 
		- file_id	
		- path
		- file_name		
		- width
		- height
		- duration
		- thumb
		- mime_type
		

	
	join	
		-
	
	
	leave 
		- 

	video 
		- file_id	
		- path
		- file_name		
		- width
		- height
		- duration
		- thumb
		- mime_type

	
	delete_chat_photo/ message

		- forward_from_data
			- user_id
			- username
			- chat_id	
			- chat_type
			- chat_title
			- chat_username
			- forward_from_message_id
		- reply_to_message_id
		- text
		- entities
		
			
		
		
		
