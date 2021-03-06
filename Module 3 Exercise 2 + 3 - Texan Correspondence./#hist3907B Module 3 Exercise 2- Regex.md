### Running the Exercise

I attempted to do as the [exercise](https://github.com/hist3907b-winter2015/module3-wranglingdata/blob/master/regexex.md) said, to use RegExr.com to test, but was unable to really understand how to use their interface. Instead, I just copied the entirety of the condensed document (mainly the names) into a separate text file within TextWrangler. 

####Step 1
After some confusion as to whether I was supposed to be doing the last few steps in succession or just the last one, I finally settled upon the following:
![Imgur](http://i.imgur.com/Xq65nRv.png) 
Followed by hitting "Replace All"

This resulted in what I believe is what I was aiming for. I'm continuing to do all work on the copy, and following the advice of saving each new addition to the legitimate data under a new name. From my trial and error figuring out the first step, it seems once you replace things (so pretty much everything having to do with RegEx, you cannot undo it)

####Step 2

For the first time I think since I completed the first module, I didn't have issues with this step. Huzzah! Building confidence. 

####Step 3
- /n is for escaped characters, or a line feed, as is /r 
	- Searches for a new line
- ^ Matches the beginning of a string, or line if the multiline flag(m) is enabled. Matches position, not character
	- so with my confused understanding of RegEx, the TextWrangler option (^\r) makes more sense to me. 

I got a little worried, as I've been checking each step before applying by hitting "find all" before replacing. This time, a lot of lines I wanted to remain were in the result. I was nervous. I searched around, and decided to bite the bullet - it's only the test file anyways, right?
And it worked, thank goodness. Onwards. 

####Step 4
Oh dear, see now, I have to come up with something on my own. This could be a struggle. Here's what I tried:
- ( [0-9]{4}) =This was unsuccessful. 
Looked at the intro to Regex on The Macroscope again
- /2 = also unsuccessful
- /2/ = likewise, unsuccessful
Kept reading through The Macroscope. Cheated a little. Glad I did. Because...
- \2 = success

I'm starting to feel like I used to in Math class, defeated because I could never figure out what I was doing wrong, only to have someone point out my simple error quite quickly once I am at my wits end. It's extremely frustrating, and has led to a lot of problems with me doing this course. 

####Conclusion
After some initial confusion, I overall was able to complete this exercise within a timely manner and feel quite happy with it!

