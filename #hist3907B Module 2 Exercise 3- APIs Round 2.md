{\rtf1\ansi\ansicpg1252\cocoartf1344\cocoasubrtf720
\cocoascreenfonts1{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardirnatural

\f0\fs24 \cf0 ###Day 2:\
\
Well, after yesterday's epic fail and having a meltdown for most of the morning over how I am handing my assessment in late because, ya know, I didn't do anything for the entirety of the course. We're back. \
\pard\tx560\tx1120\tx1680\tx2240\tx2800\tx3360\tx3920\tx4480\tx5040\tx5600\tx6160\tx6720\pardirnatural
\cf0 \
I was mighty panicked, as I had no idea how I was supposed to figure out what I did wrong. I thought I'd gone through everything! \
\
I looked at the [JSON Response Document]({\field{\*\fldinst{HYPERLINK "http://search.canadiana.ca/support/api_search_json"}}{\fldrslt http://search.canadiana.ca/support/api_search_json}}). I hoped it would tell me what I'd done wrong. Or at least give me some idea. No such luck. \
\
I scrolled through the instructions again, including those for Windows. I found the conversation between Pickering and Dr. Graham. This finally did help me a bit. In previous attempts, I'd been inputting my own URL into line 28 of the code. Reading Dr. Graham's explaination, I realized that it was only  lines 9 and 20 that I needed to change. \
\
Full of joy and hopes that I had not, in fact, completely screwed myself over; I looked through my notes from yesterday again, as well as looking through the instructions again. \
\
I noticed that I had used the command sudo chmod {\field{\*\fldinst{HYPERLINK "http://api-canandiana-ottawa-search.sh"}}{\fldrslt api-canandiana-ottawa-search.sh}}. This had yielded me a weird mish mash of information that didn't really make sense. But the instructions say sudo chmod **700** {\field{\*\fldinst{HYPERLINK "http://file.sh"}}{\fldrslt file.sh}}. I did try to search the command to see what this means, but ultimately, I have no idea, but crossed my fingers, prayed to the technology gods; and typed:\
\
sudo chmod 700 {\field{\*\fldinst{HYPERLINK "http://api-ottawacanadiana.sh"}}{\fldrslt api-ottawacanadiana.sh}}\
\
Pause. Breathe.\
\
Password:\
\
I'll admit, I screamed a little bit. And then shook my head at how over thinking things had led to me wasting *hours* on trying to figure things out. \
\
And now I wait. For this to stop:\
\
![alt text]({\field{\*\fldinst{HYPERLINK "http://imgur.com/NWKGdUM"}}{\fldrslt http://imgur.com/NWKGdUM}})}