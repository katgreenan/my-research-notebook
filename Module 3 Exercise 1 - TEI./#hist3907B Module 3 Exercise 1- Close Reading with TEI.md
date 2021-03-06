####Vetting the Site

On first glance, this site seems trustworthy as a provider of historical texts. It just has that 'look' about it. Yes, you know the look. It's the one that for some reason, just screams "I'm educational even if I'm pretending to seem fun." 

Or maybe it just reminds me of Heritage Passages. Yeah, that's probably it. It seems I'm having HIST 2809 flashbacks. 

I think the big similarity is the large logos that litter the pages. The site in question has a [Heritage Lottery Fund](http://www.hlf.org.uk/looking-funding/our-grant-programmes) logo, as well as ... an anti-slavery logo?

Well then, those two things kind of counter each other then, don't they? 

The heritage lottery 'funded' (HLF) logo, lulls one into a sense of trusting. Why? Because well, they're accountable to [Parliament in the UK](http://www.hlf.org.uk/about-us/our-history). But A) While there's a logo, there's no link to the HLF - I had to search that myself. but B) you bet the [Anti-Slavery](http://www.antislavery.org/english/) one leads somewhere. 

And that 'somewhere' would be to their website. It turns out that they are the ['oldest international human rights organization.'](http://www.antislavery.org/english/who_we_are/default.aspx)

Now, this doesn't mean that the documents housed at [Recovered Histories](http://www.recoveredhistories.org) are useless. In fact, I'm sure they're quite helpful. But if one were using this for research, it would be advisable to also look elsewhere as well, as it is **very** likely that this collection is trying to tell a narrative, and it will be biased. 

####Encoding and Viewing Your Text

Well, that certainly was a... process. Though I did end up getting confused in the end, originally it was just time consuming! Transcribing, encoding, filling out everything - it took a while. Finally I finished. I was all excited, I tried to get it to work (be viewable); it was not.

- I checked the instructions, I changed browsers. Nada. 
- I saved as an .xsl, nooope.
- I compared against 1.xml in the module; I altered the code to deal with the ampersands in the geowiki links (Why did you make us use this in our file if it wasn't going to work properly? I'm assuming so that we could learn to work with entities)
- I used an online validator and changed my code once again to get rid of the duplicate (") at the end of every place name section; this also directed me to one of my citations, which was not reading properly because there was an extra set of (") within the original code. Got to use &quot; ... *Still* would not work!

Then I read through everything again - all the way to the end - did the extra bit at the end of the exercise... and proceeded to hit my head to the desk. 

The instructions only said "make sure your .xml and .xsl file are in the same folder." I took this to mean that I needed to duplicate my file and convert it into an .xsl... It was only after doing the 'more on transformations' section that I realized my file wasn't pointing anywhere! See, I didn't realize that the style sheet wasn't stored within my machine. So I scrolled through the files in the TEI Close Reading folder, copied 000style.xsl into TextWrangler, saved, and then tried again...

![Imgur](http://i.imgur.com/c0t1CTn.png)

It may be a simple thing, but with my rudimentary skills and knowledge prior to doing this, I was pleased as punch to see all my work end up looking so, well, good!

###More on transformations
- This file is looking for newspaper results. 
- It says exclude-result-prefixes; I'm not sure what that means though! 
- In order to get my XML file to point to it, I would have to change line 2.
	- Switch 000style.xsl to http://www.w3.org/1999/XSL/Transform"

