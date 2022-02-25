# Wordle Duel

Wordle duel is a multiplayer game, based on Wordle. Two players can competitively play wordle against each other using numerous game formats. Game formats are as follows:
 - Correspondence
   - Start a correspondence match with a user and send them a word to guess - once they've guessed, they send you one back
   - The number of attempts to guess the word will be tallied and a running score will be kept
   - Correspondence games can end based on number of words, number of days, or not expire at all
 - Real-time
   - Compete with another player real-time, guessing the same word
   - Games can be best of x words

**Features**
 - Users
   - Users can add and remove friends
   - Friends online/offline status can be shown
 - Each game will have a chat room
 - Users can give their email address to be notified when it's their turn
 - Users or anonymous players can match up in random online matchmaking

# Development Spec

The web stack will be run on a linux VM.

**Components and Requirements**
 - Web server
   - Lightweight
   - Simple to setup and maintain
   - Can serve static files as well as javascript+html
 - REST API
   - Create matches between players
   - Letter/word validation in games
     - Prevents the player from looking into the javascript code to see the word
   - Manage user accounts
   - Send messages
 - Client-side javascript
   - UI
 - Database 
   - Store user information
