Todo
=====

* [ ] Fix sound issue
  * I've attempted to see what happens when a sound is played during the game. It does not play the sounds as one long piece of sound, it plays it incrementally so that is why I see sound of the game turning on and off sometimes. This would be fine in smaller games where not a lot of sound is played at once, homever in this game there are often times when >2 sounds play at once.
  * For example, an opponent with a laser weapon (e.g. a Djinn) fires at you. This now creates three sounds at once: the background music + the laser hitting you + the explosion it causes afterwards.
  * It is even worse with multiple players.
  * [ ] Use a different library for sound?
    * SFML?
    * OpenAL?
  * I was slightly confused about the sounds in the game as there are no sound files present. 
* [ ] Remove explosion animation (and possibly replace it with a simpler version)
* [ ] Add mute functionality to sound options
* [ ] Add some more ships for fun!
* Fix spinning for:
  * [ ] Starbase (off-center)
  * [ ] Gaia (odd flashing)
* [ ] Network support would be nice but it will probably be hard to implement. 
* [ ] Make the GUI look nicer
 * [ ]Change font
 * [ ] Add in/remove unfinished text boxes
