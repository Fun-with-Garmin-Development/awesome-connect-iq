
[OpenWeatherMapWidget](https://github.com/desyat/OpenWeatherMapWidget) App store: https://apps.garmin.com/en-US/apps/1f3f2d10-ac05-4a9b-a8fa-bdeac8775793 ; 
This is a good example of how background processes work. Feel free to give me suggestions on improving the code.
There is also an example of Glance View for widgets.


[Tkadla-GSG/garmin](https://github.com/Tkadla-GSG/garmin)
I am not sure if this was shared before, but here it goes: 
3 simple games, including Flappy Bird (It's the only one I've tested on the simulator, it works).
The source code is clean and easy to read (and learn). This guy has even some unit tests!

[IQ Meteo for vivoactive HR](https://github.com/antirez/iqmeteo)
Main features of this widget:
Uses the GPS to get the user position, in order to fetch Yahoo weather information for the exact location.
Caching of the GPS position. It is only re-fetched if the user long presses the vivoactive HR right button.
Programmatically generated icons: fast and small.
Auto switch of temperature unit based on device configuration.
Single view current condition and forecasts.
Easy with CPU and battery. It caches the latest condition in order to just render it immediately, while performign the new query. Does not query again if less than 30 seconds elapsed since the latest query.


[Garmin Battery Guesstimate](https://github.com/individual-it/BatteryGuesstimate/)
Shows the battery consumption over time and estimates how long the battery would last (better than the build-in estimation).
Not sure if there is yet anything to learn from (as I'm still very confused myself), but I published my first app also on GitHub https://github.com/individual-it/BatteryGuesstimate/
It's a small app that remembers the status of the battery, shows a graph and estimates how long it might last if the discharge is similar like in the past x minutes/hours

[OPN-MonkeyC](https://gitlab.com/waterkip/opn-monkeyc) - was mantioned in develepers forum, but it is not clear what it is

[Atom Fast Dosimeter Application](https://github.com/newenclave/AtomAppGN)
The application doesn't turn your watch into a dosimeter. It uses an Atom Fast device to read and show the data.

[barrels from garmin](https://github.com/garmin/connectiq-apps/tree/master/barrels)
Monkey Barrels are a way for developers to create custom Monkey C libraries containing source code and resource information that can be easily shared across Connect IQ Projects. To find out more about Monkey Barrels, please see the Shareable Libraries chapter in the Programmer's Guide.

[Horizontal-speedo-rep](https://github.com/dazey77/Horizontal-speedo-rep)
Its a horizontal speedo app for the GPSMAP 66 series (specifically 66SR).  Designed to allow huge display and to override the 1 frame per second refresh limit of the Garmin GPS.  Button pushes allow control of day/night, backlight on/off, selection of 3 speed ranges, trip 1 & 2 reset and FPS adjust between 2&10 FPS.

[Badminton Score Tracker](https://apps.garmin.com/pl-PL/apps/51606451-57e2-4f99-9420-2ba5a80b5df6) [GitHub - matco/badminton at dev](https://github.com/matco/badminton/tree/dev.) May be good. Quite fresh. "- "Save matches as Garmin Connect activities" - could be good example for saving custom activities.

[GitHub - rgibert/garmin-podcasts: Garmin Podcasts is a Garmin Connect IQ podcast app powered by Podcast Index. No external service or subscription required: all you need is you watch!](https://github.com/rgibert/garmin-podcasts) 
An example of audio content provider app. Look very solid. Good user's docs.

[GitHub - xehpuk/parkrun-barcode-garmin-connect-iq: Never forget your barcode again!](https://github.com/xehpuk/parkrun-barcode-garmin-connect-iq) 
Doesn't do much, but it looks nice. Contains a glance view.

[GitHub - danielsiwiec/timebomb: Timebomb game for garmin](https://github.com/danielsiwiec/timebomb). Looks like a game. Had not run it yet. The code seems clean. There is even a model passd to the delegate. Don't expect sofisticated mechanics/techniques, though.

[andryuha49/GarminTrexGame](https://github.com/andryuha49/GarminTrexGame) Quite fresh (2020), good readme. Game from google chrome. (A bit slow, judging from the demo video. Not sure if coding/techniques are good.)

[https://github.com/hansiglaser/ConnectIQ](https://github.com/hansiglaser/ConnectIQ) Collection of Garmin Connect IQ apps. SimpleWaF (watch face) is a very simple watch face, just a finger exercise. ShowAllInfos (widget) retrieves all available information (e.g., screen size, heart rate, ...) and displays it. SensorViz (app) interactively visualizes the readings of the accelerometer and the magnetometer in 3D.

[Contrast Shower](https://github.com/aiMonster/Garmin-Contrast-Shower)
https://apps.garmin.com/en-US/apps/9499ec2c-d424-4135-a62d-130956bc1a6f
A watch application that helps you to take a contrast shower every day and keep your health in great shape. It will notify you with vibration on every cycle end, so you don't miss to switch the water. The application allows you to configure the number of cycles and their duration. Also, it allows you to record activity, so you could track your progress.

[Garmin 3D Benchmark](https://github.com/tomasslavicek/garmin3D) App Store: https://apps.garmin.com/en-US/apps/c39b8b25-7ac8-4481-b8be-8899ef12facc
 This is a 3D game engine benchmark to test how fast is your device.
All positions of objects are calculated in 3D coordinates, multiplied by View and Projective matrices. You can press Up and Down buttons to rotate with the scene. Whole screen is redrawn every frame, you can see the number of frames per second on the top


## example/project collections

Likenttt/garmin-connectiq-samples-brief-explanations: Garmin development sample programs, a collection of topical problems. Samples collection for Garmin connect IQ development.: https://github.com/Likenttt/garmin-connectiq-samples-brief-explanations

koulik / examples — Bitbucket: https://bitbucket.org/koulik/examples/src/master/

admsteck/ConnectIQ: Garmin ConnectIQ projects: https://github.com/admsteck/ConnectIQ

dorindanciu/ConnectIQ: Monkey C Playground: https://github.com/dorindanciu/ConnectIQ

douglasr/connectiq-samples: Connect IQ sample apps, libraries and code snippets: https://github.com/douglasr/connectiq-samples

ekutter/CIQTest: Garmin CIQ test projects: https://github.com/ekutter/CIQTest

jstringer1/garmin-connectiq: Bits a pieces of monkeyc written for my garmin fenix 5 plus.: https://github.com/jstringer1/garmin-connectiq

joergsteinkamp/Simplog: Simple Garmin Connect IQ watch face for Fenix 3 HR: https://github.com/joergsteinkamp/Simplog

rustycoopes/projects: https://github.com/rustycoopes/projects

## Watchfaces

30WedgeSwagginNumerals: A simple, bare bones, colorful digitalroman-numeral watch face.: https://github.com/30Wedge/SwagginNumerals

cy384/copernicus: the Copernicus watchface for Garmin devices: https://github.com/cy384/copernicus

psjo/darktimes: Watch face for Garmin fenix 3 HR +, connect iq sdk: https://github.com/psjo/darktimes

joakim-ribier/ftw-garmin: FTW - Watch Faces for Garmin: https://github.com/joakim-ribier/ftw-garmin

https://bitbucket.org/koulik/examples/src/master/Interceptor/
This looks interesting. Nice image in the resources (Star Wars interceptor). A watch face.

## Demo/example/test

sunpazed/garmin-waketest: https://github.com/sunpazed/garmin-waketest

abs0/GarminWebRequestTest: Simple app to demonstrate makeWebRequest() regression in Garmin ConnectIQ 2.3.X SDK \*nix simulator: https://github.com/abs0/GarminWebRequestTest

## controlling/iot

alanfischer/hassiq: Home Assistant interface for Garmin's Connect IQ Platform: https://github.com/alanfischer/hassiq

blaskovicz/garmin-nest-camera-control: Control and visualize the state of your Nest Cameras from your Garmin Wearable.: https://github.com/blaskovicz/garmin-nest-camera-control

blaskovicz/garmin-tplink-cloud-control: Control and visualize the state of your TPLink Cloud / Kasa devices from your Garmin Wearable.: https://github.com/blaskovicz/garmin-tplink-cloud-control

breber/nest-iq: ConnectIQ app to control Nest thermostat: https://github.com/breber/nest-iq

zmullett/connectiq-sonos: A Garmin Connect IQ watch widget that controls Sonos speaker groups.: https://github.com/zmullett/connectiq-sonos

## not decided yet

arquicanedo/barbecueboss: Barbecue ConnectIQ App for Garmin Devices: https://github.com/arquicanedo/barbecueboss

BodyFatControl/garmin-connectiq-linux: https://github.com/BodyFatControl/garmin-connectiq-linux

danielsiwiec/tabataTimer: A tabata timer for garmin watches: https://github.com/danielsiwiec/tabataTimer

dkappler/kraken: garmin forerunner 235 app for heart rate tracking: https://github.com/dkappler/kraken

electrofloat/BPTransport-Garmin: https://github.com/electrofloat/BPTransport-Garmin

fjbenitog/bike-simulator: Bike simulator for Garmin App: https://github.com/fjbenitog/bike-simulator

Cougargriff/SensorTriggerIQ: Companion watch app for Sensor Triggers: https://github.com/Cougargriff/SensorTriggerIQ

IrishMarineInstitute/connectiq-ido: An Integrated Digital Ocean app on the ConnectIQ platform: https://github.com/IrishMarineInstitute/connectiq-ido

jravey7/CIQChecklist: Create executable checklists for Garmin smart watches using your phone: https://github.com/jravey7/CIQChecklist

mauriciogior/garmin-hackathon: https://github.com/mauriciogior/garmin-hackathon

mikkosh/AntAssetTracker: AntAssetTracker ConnectIQ module for communicating with devices supporting Ant Asset Tracker profile such as Garmin Astro or other Dog trackers.: https://github.com/mikkosh/AntAssetTracker

mikkosh/Ballistics: Ballistics is a bullet ballistic calculator application built with Connect IQ for Garmin devices: https://github.com/mikkosh/Ballistics

noln/doughnuts-burnt: A simple Garmin Connect IQ app for the Fenix 5X fitness GPS watch that shows the number of doughnuts burnt so far today.: https://github.com/noln/doughnuts-burnt

Tamarpe/CatFacts: A garmin widget that generates cat facts to your watch: https://github.com/Tamarpe/CatFacts

ToryStark/connect-iq: https://github.com/ToryStark/connect-iq

vovan-/swimmer-datafiled-garmin: Swimmer datafiled for Garmin Connect IQ store.: https://github.com/vovan-/swimmer-datafiled-garmin

## Tutorials

### Connect IQ - Getting Started Pt. 1: Setup
https://www.youtube.com/watch?v=2CJiVXboLws&t=1022s
This tutorial (2019) walks new users through getting set up in the Eclipse IDE, installing the Connect IQ Plugin, and building your first watchface.

### Connect IQ - Getting Started Pt. 2: Hello World
https://www.youtube.com/watch?v=RVLnrrBM4fY&t=229s
This brief tutorial (2019) introduces developers to monkey c with a very simple "Hello World" program that prints to the console and displays on a watchface in place of the time. (Uses Eclipse tooling.)

### Connect IQ - Uploading to the App Store
https://www.youtube.com/watch?v=uK9ccEroFMo&t=5s
This youtube video (2019) shows how to upload you app to the Conncect IQ Store. (Uses Eclipse tooling.)

### How to create a Garmin Watch application - Part 1
https://www.youtube.com/watch?v=_sHBqQKpIZg
This tutorial (2022), shows how to configure Monkey C development environment based on Visual Studio Code on Mac OS X.

### Connect IQ Tutorial - Watchface with custom font
https://www.youtube.com/watch?v=PRQyA4BeqqE
This 2016 youtube video shows how to use custom font for a Garmin App.
(Uses Eclipse tooling.)


### Barcode Wallet (1D/2D) : An app to manage barcodes and other 2D codes like QR codes
App : apps.garmin.com/.../6840e507-b9fb-4d31-b990-2a711353ce00
Widget : apps.garmin.com/.../ad2ef902-b229-4ab8-bd0e-86c102529f93
Sources : github.com/.../Barcode-Wallet
Backend sources : gitlab.com/.../qrcode-data-manager-server

### Daylight : A minimalist watchface
watchface : apps.garmin.com/.../4cdedf60-deef-4a1e-8206-7c42745097f4
sources : github.com/.../DaylightWF
docs : github.com/.../wiki

### WHatch4Me
Implements a method of  calculating and displaying a step goal streak based on  the limited history that  the watchface can see from the step history. 
Garmin IQ :  https://apps.garmin.com/en-US/apps/b38aec7e-8719-4aaa-9e2b-b89e5633e3d4
Source Code: https://github.com/WHalford/WHatch4Me

### STEPS EMTB Data
Created a data field that uses BLE to connect to a Shimano STEPS e-bike:
App store: https://apps.garmin.com/en-US/apps/461743f9-b350-486f-bd87-613c7b0bab90#0
Source code: https://github.com/markdotai/emtb
This project is a simple data field for Garmin watches, built using Garmin Connect IQ (CIQ).

It allows your watch to connect to a a Shimano STEPS e-bike using Bluetooth Low Energy (BLE) 
and display useful information (like battery percentage, assist mode, gear number).
