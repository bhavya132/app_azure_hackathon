# Hariyali App
## Submission for Microsoft Azure Hackathon 2022


Remember the craze, when the Pokemon Go first launched for our mobiles. We spend our days all around catching pokemons and earning points. Keeping the craze alive we launch our all new Hariyali where instead of catching pokemons we need to capture new plant species ( which you do by planting them). The more you plant the more points you get. Let the plantation drive begins!! .


## Features

- 🪴 **Plantation Drive:** Capture yourself with the plant you have just planted and get points based on species and whether you have planted a new species or not, it has an integrated face authentication that authenticates your face as well, so that we know it's you planting it.

- 🌱**Species recognition:** Not sure what's the plant species name you are going to plant   no worries check it on our app

- ♻️**RecycleTeller:**   Came across some garbage while on your little discover tour and cannot identify whether this garbage comes under recyclable or non-recyclable check it here and extend your little help in saving the environment 

## Tech

The tech stack for the complete project:

- [Flutter] - awesome UI software development kit 
- [Visual Studio] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Dart] - the needed programming language for flutter
- [FastAPI] - web framework for building APIs with Python 3.6+
- [Microsoft Azure] - fast public cloud computing platform


## Installation

The app requires [Flutter] and [Python] to run.

### Backend

```sh
cd backend
cd venv
Scripts/activate
uvicorn main:app --reload --host 0.0.0.0
```

To get the local ip of the backend: (To run on your mobile)
```sh
ipconfig
```
Select IPv4 address under Wireless LAN adapter Wi-Fi and copy it.
New address is: <ip>:8000
Then replace the url with the new address in URI.parse statements in Flutter to run the application in your device.
Connect the mobile to laptop hotspot.
Run the frontend.

### Frontend
Install the dependencies and devDependencies and start the server.
(While starting the devices, select only android device since the frontend written is compatible with android only not web)
```sh
cd frontend
flutter pub get
flutter devices
flutter run -d android
```


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [flutter]:<https://flutter.dev/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Visual Studio]: <https://visualstudio.microsoft.com/>
   [FastAPI]: <https://fastapi.tiangolo.com/>
   [Dart]: <https://dart.dev/>
   [Microsoft Azure]: <https://azure.microsoft.com/en-in/>
