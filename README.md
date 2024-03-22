![Psychadelic Gardening Simulation](https://raw.githubusercontent.com/cmlaidlaw/waaah/master/screenshot.png)

# WE ARE ALL ANGELS HERE

Psychadelic Gardening Simulation / Meditation Aid

## Running

WebAudio will fail to initialize if you attempt to load index.html as a file, so you will need to run a web server in the root of this project. The easiest way to do that is probably by running the following command and then visiting http://localhost:8000/:

    python3 -m http.server

## Requirements

+   Screen size >= 1024x640
+   Browser that supports the Canvas and Web Audio APIs

## Fun (?) Facts

I built this in the winter of 2013, before I had ever worked as a professional software engineer. If I recall correctly the coding style was roughly based on John Carmack's coding style for id Software, adapted for JavaScript.

I fundamentally misunderstood audio synthesis at the time, and got something working by creating new oscillators every time I wanted to play a chord. There is a better way to do this, which I learned in depth as I started to build a Eurorack synthesizer about a decade later.

I was still feeling interested in and optimistic about BitCoin at the time (I don't recall there being many other cryptocurrencies back then) so I decided to experiment with treating this as a coin-operated game. I received 0.0 BTC over the course of the few years that I had this online (which can be verified by looking at the transaction history for the wallet address).
