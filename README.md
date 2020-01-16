<p align="center">
  <a href="" target="_blank">
    <img src="https://user-images.githubusercontent.com/6529619/71329888-7e238300-24f7-11ea-8bbf-550181e164aa.png?style=centerme"
    width="500px">
  </a>
  <p align="center">
    An open source alternative for pay-to-win MMO strategy games.
    <br>
    <a href="https://docs.google.com/document/d/1-0B6tDCrB43ZTyw8Gof0TYjc9zldjr5Jk7s5rZohKWI/edit?usp=sharing" target="_blank"><strong>Documentation</strong></a>
    ·
    <a href="" target="_blank"><strong>Feature Request</strong></a>
  </p>
</p>

## Introduction
Open Conquest is being developed as an open-source alternative to pay-to-win mobile MMO strategy games. Players control a city and can work with their allies to use their military, economic, and political power to build great prosperous empires. But, other players are not the only obstacles. Powerful creatures existed long before humans and have been responsible for the rise and fall of empires.


## Modules
This repository contains all of the git modules associated with the Open Conquest project.
|Module|Description|
|---|---|
|open-conquest-auth| Authentication & authorization microservice responsible for issusing JWTs with OAuth |
|open-conquest-ios| iOS Client |
|open-conquest-world-server| WebSocket server responsible for managing a single world|

## Installation
1. Clone the repos
```
git clone --recursive https://github.com/Open-Conquest/open-conquest.git
```
2. Start the game server and database containers
```
cd open-conquest/open-conquest-world-server
docker-compose -f dockerfiles/docker-compose.yml up --build
```
3. Open the iOS client in Xcode
```
cd ../open-conquest-ios
open Open\ Conquest.xcworkspace
```
4. Build and run the client on any device



## Contributions From
<a target="_blank" href="https://github.com/zachwildd">Zach Wild</a>
 · 
<a target="_blank" href="https://github.com/sadclownwars">Nicole Savir</a>
 ·
<a target="_blank" href="https://github.com/DonIsaac">Don Isaac</a>
 ·
<a target="_blank" href="https://github.com/eric-robertson">Eric Robertson</a>
 ·
<a target="_blank" href="https://github.com/Aycion">Emery Bacon</a>
 ·
<a target="_blank" href="https://github.com/RyanSchweiz">Ryan Schweizer</a>
 ·
<a target="_blank" href="https://berniesanders.com/">Kagan Karakaya</a>