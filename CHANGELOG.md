## 0.1.1
- version change to 0.1.1
- implement -TO argument for takeout effekt
- implement possibility to configure takeout effekt

## 0.1.0
- version change to 0.1.0

## 2.0.0.b6

- just a short check update
- 

## 2.0.0.b5

- Changed changelog to main branch
- 

## 2.0.0.b4

- Implement Board Stop after Win Parameter
- 


## 1.5.0

- rename application to darts-wled


## 1.4.15

- switch to socketio-client


## 1.4.14

- fix ws bug


## 1.4.13

- add wss support


## 1.4.12

- hotfix messages


## 1.4.11

- add lobby-events (-PJ / --player_joined_effects & -PJ / --player_left_effects)


## 1.4.10

- add CHANGELOG
- add BACKLOG


## 0.0.0

- create receiver-endpoint
- support events with multiple effects that chosen randomly
- send events to wled-instance(s)
- Random Effect if user enters 'x' as argument value for effect-id
- add high-finish logic
- initial check is wled reachable download effect-names. (maybe turn on wled-installation(s) for 10 Seconds)
- let user choose between effect-index and effect-name in arguments
- support customizung effect-parameters
- support point-areas
- brightness configurable
- default effect when idle
- try to fix change-too-slow problem (WLED)
- support presets + playlists
- add wled-vars: speed, intensity, palette
- improve Readme: explain arguments, add example for starting app
- connect to data-feeder by websocket
- only process ws-msgs of first wled-endpoint