# mqtt-http bridge
Easily access mqtt topics over http


Dir break down
----------
 - /src/store   => store all the messages to db
 - /src/send    => send receiving http message to broker by publishing
 - /lib/parson  => json library to parse the config https://github.com/kgabis/parson

Requirements
----------
 - Mogodb
