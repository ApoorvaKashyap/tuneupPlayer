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

The Music Player will be developed from scratch using Python. It will be web-based, i.e., it will have a  web server fropm where music will be downloaded and adde to the app's playlist. The player will search for a music track on demand and then play the music track if found. Otherwise, it download the track from the server.

Server: 

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

` P.S. - The App is still in development.The privacy of users is not an important priority at this stage. `