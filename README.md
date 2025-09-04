# LEMON NODES DEPLOY BOT
`git clone https://github.com/username5642/LEMON-VPS`
# CD THE REPO
`cd LEMON-VPS`

# INSTALL REQUIREMENTS
` apt update && apt upgrade -y && apt install pip -y && apt remove containerd.io -y && apt install docker.io -y && apt install python3 && apt install nano -y `

# INSTALL BOT REQUIREMENTS
`pip install -r requirements.txt`

# NOW SET PROPERTIES
` nano env.properties `

# NOW RENAME FILE
`mv env.properties .env`

# RUN THE BOT
`python3 bot.py `
