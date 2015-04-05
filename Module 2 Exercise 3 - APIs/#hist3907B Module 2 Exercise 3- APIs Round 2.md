###Day 2:

Well, after yesterday's epic fail and having a meltdown for most of the morning over how I am handing my assessment in late because, ya know, I didn't do anything for the entirety of the course. We're back. 

I was mighty panicked, as I had no idea how I was supposed to figure out what I did wrong. I thought I'd gone through everything! 

I looked at the [JSON Response Document](http://search.canadiana.ca/support/api_search_json). I hoped it would tell me what I'd done wrong. Or at least give me some idea. No such luck. 

I scrolled through the instructions again, including those for Windows. I found the conversation between Pickering and Dr. Graham. This finally did help me a bit. In previous attempts, I'd been inputting my own URL into line 28 of the code. Reading Dr. Graham's explanation, I realized that it was only  ines 9 and 20 that I needed to change. 

Full of joy and hopes that I had not, in fact, completely screwed myself over; I looked through my notes from yesterday again, as well as looking through the instructions again. 

I noticed that I had used the command sudo chmod api-canandiana-ottawa-search.sh. This had yielded me a weird mishmash of information that didn't really make sense. But the instructions say `sudo chmod **700** file.sh`. I did try to search the command to see what this means, but ultimately, I have no idea, but crossed my fingers, prayed to the technology gods; and typed:

`sudo chmod 700 api-ottawacanadiana.sh`

Pause. Breathe.

`Password:`

I'll admit, I screamed a little bit. And then shook my head at how over thinking things had led to me wasting *hours* on trying to figure things out. 

And now I wait. For this to stop:

![Imgur](http://i.imgur.com/NWKGdUM.png)
