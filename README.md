# Telescopes
Telescopes is a free standalone script that allows players to use telescopes all around the map. Currently, it allows the player to use /telescope, press E when close to one or to use either qTarget or qb-target as a 3rd eye solution.
I decided to release this to the public since I haven’t seen any other telescope scripts around. The script was made for fun, so the code might not be the greatest, feel free to improve upon it.


# Optional Dependencies
As previously stated the script allows for either qTarget or qb-target to be used. They are disabled by default but can be toggled in the config file.
The script also uses mythic notify to send notifications to the player, however, this can be changed. Native notifications are built-in if you would like to use those instead. This can be toggled in the config file.


# Optimization
The script runs at 0.1ms when idling if you have the help text thread (gets the distance to the telescope and displays some help text if close enough). It idles at 0.0 if you only use the command/3rd eye.
It runs at 0.4- 0.5ms when using a telescope.


# Known Issues
You can sometimes “flick” your way out of the restricted view angles on the two telescopes in the Senora National Park. This is not a big issue, but I might as well mention it.
