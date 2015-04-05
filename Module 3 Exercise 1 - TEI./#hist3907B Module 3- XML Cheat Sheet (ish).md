###Quick References for Writing in XML

- XML is *not* a stream of characters. 
	- It may appear this way, but it is a hierarchical tree
		- Everything must 'nest' within every other element properly
			- So basically, all the tags have to open in close in the same order.
- XML documents **must** be well formed
	- So they have a single root element that contains the others
		- Like the shopping list and paragraph examples
		
- Certain characters cannot be used in XML documents because they are used in order to markup the document.
	- They must be replaced by *entities*, which begin with an ampersand and end in a semicolon. In between them, you identify the character you wish to use.
		- They are: the left angle bracket ("<") and the ampersand ("&")
			- In their place, use: &lt; ("less than") and &amp;
	- In addition, the usage of (">"), (" "), and (' ') are often limited
		- In their place, use: &gt; (for ">"), &quot; (for " "), and &apos; (for ' ').

Taken from [What is XML and Why Should Humanists Care?](http://dh.obdurodon.org/what-is-xml.xhtml) by David Birnbaum.
