# simple Docker Container for Echo Server
#Description
#Installing
open yout terminal window, enter the following commands
'''
git clone https://github.com/tul69453/lukedrobotics.git
'''

you may have to install docker-compose
'''
sudo apt install docker-compose -y
'''

If everything is successful, you can run
'''
docker-compose build
'''

# Execute code, open terminal 1
'''
docker run -it bionic-bai:latest
'''
open terminal 2
'''
docker-compose --profile echoserver up
'''
