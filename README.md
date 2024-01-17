
## Real time chat
 A simple chat applications using raw websockets in Node.js that supports the following features - 

 - Allows an admin to create a new chat session/room. Admin is allowed to set the following properties on the room 
  - Name
  - start_time
  - is_open 
  - cool_down_time
 - Allows a users to join the room and  send messages
 - Allows users to upvote chat messages.
 - If chat messages reach more than 3 upvotes, move them over to a saparate section.
 - If chat messages reach more than 10 upvotes, alert the admin to answer.
