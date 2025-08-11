# Splunk Fundamentals

## Setup: Choose your splunk implementation:
1. Request a free eval splunk instance at https://www.splunk.com/en_us/download/splunk-cloud.html

### Note: When there have been issues in the signup process, some users have created a temporary gmail account to use to get around it.

2. Or you can run splunk in a Docker container (if you have docker on your machine): docker run -d -p 8000:8000 -e "SPLUNK_START_ARGS=--accept-license" --platform linux/amd64 -e "SPLUNK_PASSWORD=password" --name splunk splunk/splunk:latest

3. docker run -d -p 8000:8000 -e SPLUNK_GENERAL_TERMS=--accept-sgt-current-at-splunk-com -e SPLUNK_START_ARGS=--accept-license --platform linux/amd64 -e "SPLUNK_PASSWORD=password" --name splunk splunk/splunk:latest 
