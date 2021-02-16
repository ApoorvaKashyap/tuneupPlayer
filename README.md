# Web Based MP3 Player

## Programming Languages Course *(BSc Programme, NRTI)*

### Professor: Amey Karkare

***Language: Python***

***Type: Mini Project***

---

## Instructions

The PRL course has a mini project component. A mini project will be a moderate-sized python application that performs some useful task. It has to be implemented in a team of up to five students.

### Requirements of the Project

1. The project must use a reasonable data set as input. This data set must come from a persistent storage or generated automatically by another program. Some examples example, a Web site, XL sheet, CSV file, SQL or similar database, Output generated by some process  such as a video, apache server etc. Some minor inputs (such as tuning parameters, value to search etc.) can be taken as input from the user.

2. User Interface: The application must have an easy to use user interface (UI). While a browser based UI is preferred, you can also use other options, like Tkinter. Do not spend too much time on fancy stuff though. You can explore Flask, Bottle etc.

---

## Chosen Project: Web Based MP3 Player

The Music Player will be developed from scratch using Python. It will be web-based, i.e., it will have a  web server fropm where music will be downloaded and adde to the app's playlist. The player will search for a music track on demand and then play the music track if found. Otherwise, it downloads the track from the server.

Server: [Youtube](www.youtube.com) 

### Functionalities

1. Play a track already downloaded through the app.
2. If the demanded track is unavailable, then download it from the server.
3. Have the Play/Pause, Forward Seek and Backward Seek Buttons.

### Libraries Used

1. OS - To work with directories and filesystems.
2. PyTube - To access songs from Youtube.
3. URLLib - To access the html codes of webpages.
4. Re - To find the matching expressions in the search results.
5. MoviePy - To convert the downloaded file into .mp3 format.
6. PyGame - To control the Music Playback.
7. PIL - To insert image into Tkinter Labels

---

## Group Members

1. Apoorva Kashyap ***(191023)***
2. Keshav Swami ***(191046)***
3. Tarun Yadav ***(191076)***
4. Sahil Kaushal ***(191077)***
5. Saksham Gaur ***(192094)***

---

## How to Use

1. The Input Bar at the top takes the name of the track. The Search Button beside it launches the search function. If the track is already present, it says so, else tries to download the track.
2. The List at the right side contains a list of the already present tracks. Selecting the track and pressing the Play/Pause Button plays the track.
3. The Volume Slider is at the bottom of the screen. It needs to be set to a certain value when the first song is run.
4. The Forward Seek and Backward Seek button jump to the nearest multiple of 15th second in their respective directions.

---
The code is also hosted on [Repl.it](https://repl.it/join/wehiiasq-apoorvakashyap).

` P.S. - The App is still in development.There are some known bugs in the project. `
