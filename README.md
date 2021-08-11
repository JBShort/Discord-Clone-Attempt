# Discord-Clone-Attempt

Attempted to replicate features noticed on Discord. Primarily text chat and voice calls.

Login and Registration condensed to a single page with custom CSS and animations to look a little more customized.

Socket.io used for sending messages back and forth as well as constantly updating a Message model in MongoDB
to keep all of the messages stored in a database in case the user closes one chat and re-opens that same chat
at a later date

Used WebRTC for voice calls as that seemed like an easy implementation at the time to hopefully connect each user 
through their userID upon creating a new account. Video calls could also be applied using webRTC but that functionality
wasn't implemented just yet.

Discord servers weren't implemented due to the time requirement needed to make things work properly0
