# q4
Technical test.

Debugging

HTML errors : 

line 33 - missing closing h2 tag 

line 30 - missing closing p tag

line 37 - moved news section tag to the bottom and included the news script inside the tags.

line 39 - capital P tag instead of normal - not sure if this was a mistake but could be a problem wehn styling in css!

missing HTML tag at the end of document.

Footer :
Moved footer tags in html to above news and under panels and added equal padding to bottom and top.

Customizing:

The nav items were already centered i added some equal spacing by making the padding equal on the CSS file.

I changed the font style to italic and reduced the font size percentage to 82% to make the text a bit smaller.

I added the q4 logo to each release title by changing the path of thumb on the JSON file.

Reducing the news releases - this is where it go a bit sticky i wasn't sure if i was to make changes in the JS code to reurn the most recent items by date, but when i looked at the JSON file the date wasn't giving me any clues to which was the most recent and i was wondering whether if it was even something i was asked to do the e-mail said HTML and CSS only if i'm not mistaken. So after i changed the format of the date on the html i just picked out the 3 most recent and deleted the rest from the JSON file directly ! not sure if that was the right thing to do !

Another sticky bit shortening the body text ! Now at first i thought i would do something like add a hover effect over the release that displays the rest of the text. But then taking a closer look in the JS file i saw the truncate helper, eventually after adding the truncate expression into various places in the html i managed to make it look like how it does now. But i'm pretty sure it's not right i must be missing something.

Changed the Date format in the HTML file.

Responsive:
So initially i was going to add a media query with a max width of 768 px to make it responsive however when i checked the CSS code it was already there ? and it was responsive already. So i'm not sure if was missing something?


I tried to make it look as much as the corrected png as i could i think it looks pretty similar ! i may have gone the wrong way around some things though.

All in all this took about an hour - i spent the most time dealing with the truncation and trying to wrap my head around how i could call the most recent news releases.

I used the Handlebars docs to get some clarity on registering helpers and expressions.

Thank you in advance for reviewing this means a lot!
