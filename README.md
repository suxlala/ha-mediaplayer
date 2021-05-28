# Fully customizable mediaplayer card with extra features

Alternative mediaplayer design, built on custom [lovelace button card](https://github.com/custom-cards/button-card) and [mini media player](https://github.com/kalkih/mini-media-player). 

Every aspect of the card and all elements can be customized.

![all](examples/all.gif)

## Features:

- custom background, icons and colors
- display lyrics of the current song
- add current track to a Spotify playlist
- display HA media browser

## Components needed

- [custom button card](https://github.com/custom-cards/button-card)
- [mini media player](https://github.com/kalkih/mini-media-player) card
- [genius lyrics](https://github.com/robert-alfaro/genius-lyrics) to fetch song lyrics into a sensor
- [IFTTT integration](https://www.home-assistant.io/integrations/ifttt/) to [trigger Spotify add-to-playlist applet](https://community.home-assistant.io/t/save-currently-playing-song-to-spotify-playlist/48513)
- [lovelace card-mod](https://github.com/thomasloven/lovelace-card-mod) to add CSS styles to the card

## Usage

- copy the content of the *mediaplayer.yaml* into a new manual card
- replace the *entity:* in line #2 with your own mediaplayer entity
- replace the *entity:* in line #102, #131, #132 and #134 with your Genius lyrics sensor
- add the URL of your HA instance in line #247
- add the content of the *script.yaml* to your scripts in your configuration.yaml or script.yaml

