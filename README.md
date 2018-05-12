<p align="center">
<img align="middle" src="https://github.com/YusofBandar/Space2020/blob/master/Images/Title.png" width="" height="" />
 </p>


Space202 is a multiplayer game that allows users to control a first-person astronaut to explore the crash site of two space ships on the moon.

Players can explore the crash site through exploration; the players can receive information via the Twilio API.

<p align="center">
<img align="middle" src="https://github.com/YusofBandar/Space2020/blob/master/Images/StartGif.gif" width="" height="" />
 </p>

In addition, there is implemented AI that will listen to commands being said over a microphone and uses voice recognition to detect speech, and based on fixed list answers the players' questions. Each player can explore the game at its own pace and trigger events simultaneously.

# Play Canvas
The game was built using a Game Engine called [Play canvas](https://playcanvas.com/). PlayCanvas is a WebGL engine, built in JavaScript, thus our game runs 100% in the web. As well as running on the web, players with different devices such as tablet and a computer will still be able to play with each other.

The server was built using Node and Socket.IO, the server updated each client on player movements and actions as well as analysing the speech of each player.

# Twilio
The Twilio API is used to send information to a player mobile, simulating real communication. When a player explores the crash site a message is sent, the message could contain vital information aiding the players throughout the game. 


<p align="center">
<img align="middle" src="https://github.com/YusofBandar/Space2020/blob/master/Images/TwilioAPI.PNG" width="" height="" />
 </p>


One situation, the Twilio API is used is at the start, when heading towards one of the space ships the player will receive a "distress signal". The "distress signal" will contain information about the space ship and crew.

# Speech AI
Throughout the game, an AI called “Blue” accompanies each player. Blue is not very clever and has a hard time understanding humans but holds a massive amount of information. When the player either needs help or requires more information, "T" can be pressed to ask Blue a question, Blue will attempt to respond with the correct information.


<p align="center">
<img align="middle" src="https://github.com/YusofBandar/Space2020/blob/master/Images/SpeechAI.PNG" width="" height="" />
 </p>


For example, the player could need more information about a certain ship. If "More information on the Vanguard" is asked to Blue, Blue will respond with extra information.  
