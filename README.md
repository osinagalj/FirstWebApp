# FirstWebApp
Stack MEAN

# 1. Download the proyect

# 2. Install node.js
	2.1 - npm install express mongose dotenv
	2.2 - npm install -D nodemon
	2.3 - npm init
	2.4 - npm install cors



# 2. Execute Backend
	npm run dev



# 3. Execute FrontEnd
	ng serve --o 


# Nota

	Si se corre en Ubuntu:
	```
	sudo gedit /etc/sysctl.conf
	```
	Add a line at the bottom
	```
	fs.inotify.max_user_watches=524288
	```
	Then save and exit!
	```
	sudo sysctl -p
	```
