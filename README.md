# @cuartetodnosbot 🎵🤖

This is the code used to run the [@cuartetodnosbot](https://twitter.com/cuartetodnosbot) bot account in Twitter.

The [`phrases.json`](https://github.com/omirete/babotsonicos/blob/master/phrases.json) file contains a list of songs (w/ lyrics) from [Cuarteto de nos](https://www.cuartetodenos.com/) (an uruguayan music group).

## 🤖 What does the bot do?
It tweets a random lyric phrase from the Cuarteto de nos band every three hours.

## 🤔 What does this code do?
The magic happens in the `main.py` script, and it just does three steps:
1. It picks a random song from `phrases.json`.
2. It picks a random phrase from the chosen song.
3. It tweets the chosen phrase from the [@cuartetodnosbot](https://twitter.com/cuartetodnosbot) twitter account.

## 👀 How does it run? And the server?
This bot requires no traditional server because it just relies on GitHub actions.

You can find a workflow in this repository that triggers every three hours and runs the `main.py` script (see [`/.github/workflows/manual.yml`](https://github.com/retrixuy/cuartetodebots/blob/master/.github/workflows/manual.yml)).

There is really not more to it than that.
