# shatner-bot

## Introduction

The _package.json_ file within this repo can be used as a descriptor in [Hipchat](https://www.hipchat.com/) for the "Shatner" service, which uses the [shatner.pics](http://shatner.pics/) to return JPEG images of William Shatner, one of the greatest and most expressional actors ever, based on the _mood_ parameter provided by in the request.

## How does it work?

In Hipchat, the user gains access to the _/shatner_ command in a room that has this plugin enabled, for example if the user types _/shatner awesome_ the following image is loaded into the Hipchat room:

![](http://shatner.pics/mood/awesome.jpg)

The idea is that users of the Hipchat room can use "Shatners" to express their present mood, just for fun :-)

## How do I install it on Hipchat?

Firstly you need to have admin rights on the room.  Then carry out the following steps:

1. From the room menu, choose "Add integrations".
2. On the next screen, choose "Install an integration from a descriptor URL".
3. For "Descriptor URL" enter: _https://raw.githubusercontent.com/alphadevx/shatner-bot/master/package.json_, then click "Install".
4. Confirm the room to install Shatner to, and choose "Approve".
5. You should now test the _/shatner_ command in the room you have installed it to.
