# Multiplayer Tic-tac-toe game

### Overview
A realtime multiplayer  tic-tac-toe game.


### Built Using:
Frontend:
- [Flutter:](https://docs.flutter.dev/get-started/codelab) Flutter documentation
- [Dart:](https://dart.dev/) Dart documentation

 Backend:
- [Node.js:](https://nodejs.org/docs/latest/api/) Node.js documentation
- [Socket.io:](https://socket.io/docs/v4/) Socket documentation
- [MongoDB](https://www.mongodb.com/docs/) MongoDb documentation



### How to use:
Step 1:
Download or clone this repository by using the link below:
```
https://github.com/Yogesh-03/MultiPlayer-Tic-tac-toe.git
```
Step 2: 
Open the project in an IDE and execute the following commands
```
cd frontend
```
To get required dependencies
```
flutter pub get
```
In frontend/lib/resources/socket_client.dart, change ${Credentials.myIp} to your current ip as
```
'http://yourIP:3000'
```
Step 3:
Now go to the root directory and execute following commands
```
cd backend
```
To start the server, run command
```
npm run dev
```
Step 4:
Now go to root folder and change directory to frontend
```
cd frontend
```
Run project by executing below code
```
flutter run
```
If the code shows no sound null safety error, run the below code:

```
flutter run --no-sound-null-safety
```
If the code still do not run\
Step 4:

```
flutter clean
```
Step 5:
```
flutter upgrade
```

