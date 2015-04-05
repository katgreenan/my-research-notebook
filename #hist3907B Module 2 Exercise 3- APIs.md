##How I Almost Lost My Mind and Why This Entire Thing is Extremely Late
######Attempt 1

Well. This was... a thing. 

To start, the prompt given in the Programming Historian's instructions for installing HomeBrew didn't work, which led to my panicking, and then further panicking, and research into whether I actually wanted to deal with sudo. Apparently I did. 

I read through the instructions, I read through [Steve Marti's post "Canadiana in Context"](https://canzac.wordpress.com/2014/09/02/canadiana-in-context/); [Ian Milligan's original post on JSON](http://ianmilligan.ca/2014/01/07/historians-love-json-or-one-quick-example-of-why-it-rocks/); and attempted to learn how shell script works. 

Going through all of these things, I thought I understood what was going on. I thought that all I needed to do to make everything work was to substitute **my** JSON URL in for the one given in the example. I couldnt' imagine that given my illiteracy in all things related to coding, that I would be expected to change anything else. I continued to follow the instuctions. 

And then I proceeded to enter the command given: `sudo chmod 700 file.sh` ... This is one of the biggest areas where I've had difficulty - understanding that some of the instructions are simply guidlines for what I actually need to input. So after all was said and done, and a lot of trial and error, I discovered that the only command that gave me *something* was: `sudo chmod api-canadiana-ottawa-search.sh`.

Was this *something* what I wanted it to be? To be honest, I'm not really sure. I don't **_think_** so. I've included a screen shot in my notebook of my terminal after entering the above command, as well as the one that was supposedly supposed to 'run' the program: `./api-canadiana-ottawa-search.sh`. 

From the looks of things, it seems I might be close? I've quadruple checked to make sure that I have all the programs installed that I'm supposed to. I'm leaning towards the issue maybe being that I've goofed a bit on how to properly input my URL into where the example one was.  

For good measure, this was the search URL I was working with: http://search.canadiana.ca/search?q=Ottawa&field=&df=1800&dt=1900&fmt=json

Aaaaaand then. I went back, re-read some things. Decided to play around some more. I may now be stuck in an endless cycle of downloading all 56,249 results from the non-JSON URL... 

Aaaaand, we got to learnt he fun new command: `pkill -9 wget`
Managed to stop the downloading of what apparently is not helpful data. Sorry Canadiana! 

#####Final exercise: 

Followed the EXACT directons from [archive.org](http://blog.archive.org/2012/04/26/downloading-in-bulk-using-wget/) 

Result: "No URLs found in ../itemlist.txt.

On an altered runthrough, in which I copied the list from the original, save as from .cvs file into a brand new text file, I got a scramble of stuff that ultimately ended in: ![Imgur](http://i.imgur.com/dTQckuE.png)

Excited by something different, I tried again, for science...

"No URLs found in ./itemlist.txt."

I'm done for the day. I've been at this all evening. I can't do the next module until I actually manage to 'wrangle' some data.
