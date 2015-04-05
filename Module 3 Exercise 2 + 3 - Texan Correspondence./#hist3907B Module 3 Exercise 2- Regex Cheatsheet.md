Regex is used for finding and manipulating text.

##Cheat sheet

- | = Or
- \< = Beginning of the word 
	- But so does \b **(This is how to do it in TextWrangler!)**
- \> = End of the line
	- Again, use \b in TextWrangler
- Variations on spellings
	- Instead of gray | grey
		- Use gr (a | e) y
	- Parentheses signify a group, like in BEDMAS, brackets first
- Period (.) directs the search to find any character
	- eg. d.g would turn up "dig", "dog, "dug", etc
- The plus (+) sign instructs it to find any number of the previous character
	- So do+g would turn up anything looking likw "dog", "doog", "dooog," etc. 
		- Adding parentheses before the + will search for repetitions of whatever is in them

Combining these two characters can be powerful
- A search for d.+g may turn up "dried fruits are g" b/c the string begins with "d" and ends with "g"


