# Splunk Fundamentals

## Setup: Choose your splunk implementation:
1. You can request a free eval splunk instance at https://www.splunk.com/en_us/download/splunk-cloud.html

2. Or you can run splunk in a Docker container (if you have docker on your machine): docker run -d -p 8000:8000 -e "SPLUNK_START_ARGS=--accept-license" --platform linux/amd64 -e "SPLUNK_PASSWORD=password" --name splunk splunk/splunk:latest
