# Selfberry
Make animated Gif file from a raspberry pi's camera, share them on social networks.
Ideal for events.
Created by Bruce Lane

Follow instructions here to setup openFrameworks for raspberry pi: http://openframeworks.cc/setup/raspberrypi/raspberry-pi-getting-started/

Then 
```
cd /home/pi/openFrameworks/apps/
mkdir SophiaDigitalArt
cd SophiaDigitalArt
git clone https://github.com/SophiaDigitalArt/selfberry/
cd selfberry
./clone_addons.sh
make
./bin/selfberry
```

For the website, setup nodejs then:
```
/home/pi/openFrameworks/apps/SophiaDigitalArt/selfberry-web
npm install -g live-server
live-server
```

Once compiled, launch directly from command line 
```
./home/pi/openFrameworks/apps/SophiaDigitalArt/selfberry-cpp/bin/selfberry
```

Keyboard shortcuts:
`enter` to record,
`up` or `down` arrow to choose shader

Warning: if launched at startup with init.d, keyboard does work, not the buttons

Some samples on 
https://videodromm.com/selfberry/