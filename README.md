## Heroku + private_pub ##

### Background ###

Faye ([github](http://github.com/faye/faye)) is a rack-based messaging system that allows web clients to communicate. 

Ryan Bates created private_pub ([github](http://github.com/ryanb/private_pub)) to easily add Faye to Rails projects. There is a Railscast for that [here](http://railscasts.com/episodes/316-private-pub).

This project is a barebones private_pub deployment that runs as a separate app. It uses foreman export for running as daemon on server.
