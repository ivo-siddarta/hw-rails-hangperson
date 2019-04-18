# Hangperson on Rails

https://hangperson-rails.herokuapp.com/

Available RESTful actions that the you can take, with the following routes:

* `GET  /new`-- default ("home") screen that allows player to start new game
* `POST /create` -- actually creates the new game
* `GET  /show` -- show current game status and let player enter a move
* `POST /guess` -- player submits a letter guess
* `GET  /win`   -- redirected here when `show` action detects game won
* `GET  /lose`  -- redirected here when `show` action detects game lost

