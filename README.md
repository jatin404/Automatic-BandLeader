# Automatic-BandLeader
It's basically a python web scraper which introduces the reader to using Python to control headless web browsers. Specifically, bandleader.py lets you play music from bandcamp through your Python shell!
To play around with bandleader.py, run something like:

>>> from bandleader import BandLeader



>>> bl = BandLeader('myhistory.csv')


>>> bl.play()            # should start playing a track

>>> bl.play(3)           # plays the third track in the listing

>>> bl.play_next()       # advances the track
 
>>> bl.more_tracks()     # see more music to play with

>>> bl.browser.quit()    # close the webdriver instance
