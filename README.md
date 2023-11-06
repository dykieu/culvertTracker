# culvertTracker

A Maplestroy discord bot to help display the stats from Culvert (GPQ).




## Description

This bot was mainly intented to be used in Maplestory and is centered around pulling data entered on a Google Excel sheet.
It is primarily used to display information from a Google excel sheet in a neat and concise way.

## Getting Started

### Dependencies

* Requirements: Docker
  * If you want to compile and/or modify the code, you will need NodeJS installed.

### Installing and Executing

* Clone the repo `git clone https://github.com/Awu05/culvertTracker.git`
* Go into the repo you just cloned `cd culvertTracker`
* Modify the docker-compose2.yaml file and fill in the missing fields: "TOKEN" and "CLIENT_ID". You will also need to rename the docker-compose2.yaml file to `docker-compose.yaml`
  * You can find the token and client_id by creating a discord developer account and then creating a new bot.
* Once you have updated the docker-compose file, you can run the docker-compose with `docker-compose up -d` to start the docker container.
