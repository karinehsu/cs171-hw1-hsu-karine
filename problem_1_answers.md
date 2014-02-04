1. What does the colspan="3" attribute of the <th> node do?

The colspan attribute makes the table's header cells (<th>) span 3 columns.

2. List all the styles (e.g. border width, text alignment, etc.) applied to the th element containing "Rank". For each, state whether they are set as an HTML attribute or a CSS style and describe them in a few words. Include only styles directly applied to the element, not styles inherited/cascading from parent elements or styles from the default user agent stylesheet. Exclude overwritten styles. For HTML attributes, state the CSS equivalent.

<th align="center"> HTML attribute that centers the text in the table header. 

CSS style
padding: 3px;
font-weight: bold;
text-align: -webkit-center;
display: table-cell;
vertical-align: inherit;


FINISH THIS

3. What differences do you notice between the DOM inspector and the HTML source? Why would you use the DOM inspector? Why is the HTML source useful?

The DOM inspector allows me to inspect specific elements and make local changes in my browser line by line. The HTML source just shows the entire HTML code without allowing me to make realtime changes. Additionally, the DOM inspector allows me to see the CSS style applied for a specific element, whereas the HTML source does not. The HTML source might be helpful if we want to just copy the entire code and build something off the existing code.
