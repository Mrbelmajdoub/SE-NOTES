Markdown rules  
if Markdown processor accepts HTML use the HTML instead.  

you can use the / to escape any character like /# to note make it create a heading.  

  
heading level by number of #  like #this1 or ##this 2  

to emphasise, ** on each side of **bold** and * for *italic* and *** to use ***both*** at once.  for strike through use two ~ ~~between~~. use two = to ==highlight==. and ~ to ~subscript~. or ^ to ^superscript^. if HTML supported you can inderline by <ins> /<ins> text /</ins> </ins>.

for blockquotes start line by >, and for multiple paragraphs, add > on the blank lines, or >> for a nested blockquote, better keep a blank line before a blockquote.  

> example of a blockquote.  

to list in order use 1. then 2. or any other number, the outcome will be an ordered list from 1, to 2 etc. a sublist in order can be inserted through an indent for  the sublist item.  

unordered list can be done by - or * or + before the item instead of a number.

Code blocks are indented four spaces or one tab. if in a list double that. or use three ' or ~ on the lines before and after, then no need for any indent. next to the 's or ~s add the language of the code to highlight syntax if processor supports it.
	<html>
	 <head>
	  <title>test</title>
	 </head>  

to put an image, ![] for title followed directly by () leading to source.  

to denote a code add ' in 'between'. if it contains the backtick ''use 'double' backticks''.  

for horizontal rule use 3 or more of * or _ or -, and try putting blank line before and after.  

---

for a link use [] for title followed directly be () for [URL] and you can link to a heading in the same page by putting # followed by the heading in the url section . you can optionaly add a title for when you hover on link by adding it right after URL and space and enclosed in quotation ""(https://www.markdownguide.org/basic-syntax/#headings "title by quotationa"). 
to make link open in a new tab Markdown processor must support HTML, so it can accept the target value blank, "<a href="https://www.markdownguide.org" target="_blank">Learn Markdown!</a>". for reference style link you can use basic one to do the same thing.  to disable automatic URL linking use ' around the link,

turn URL or email adresses into links by enclosing in angle brackets like <belmajdoubsaad0@gmail.com>.  

table need three or more hyphens - to create each column's header and pipes | to separate each column. and you can alicgh text in column by adding column to left right or both as you want to center it.  
|:syntax | description:|
|---|---|
|:header:|title|

for task list use - then [ ] with space inbetween and insert x there if done.
-[x] done


