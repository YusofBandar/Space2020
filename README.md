# Space2020
Space202 is a multiplayer game that allows users to control a first-person astronaut to explore the crash site of two space-ships on the moon.

Players can explore the crash site through exploration, the players can receive information via the Twilio API. 

In addition, there is implemented AI that will listen to commands being said over a microphone and uses voice recognition to detect speech, and based on fixed list answers the players' questions. Each player can explore the game at its own pace and trigger events simultaneously.

# Twilio
The Twilio API is used to send information to the players mobile, simulating real communication. When a player explores the crash site a message will be sent, the message could contain vital information aiding the players throughout the game. 

One situation, the Twilio API is used is at the start, when heading towards one of the space-ships the player will receive a "distress signal". The "distress signal" will contain information about the space-ship and crew.

# Speech AI
Throughout the game, each player is accompanied by an AI called "Blue". Blue is not very clever and has a hard time understanding humans but holds a massive amount of information. When the player either needs help or requires more information, "T" can be pressed to ask Blue a question, Blue will attempt to respond with the correct information.

For example, the player could need more information about a certain ship. If "More information on the Vanguard" is asked to Blue, Blue will respond with extra information.  
