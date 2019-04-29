1) docker-compose -f docker-compose.yml up

2) Login to graylog with opening http://127.0.0.1:9000/ in the browser
Username: admin
Password: admin

3) Configure inputs:
Go to System > Inputs
Add new "GELF UDP" configuration as global input using port 12201

4) Use nodejs-example application to send logs to graylog