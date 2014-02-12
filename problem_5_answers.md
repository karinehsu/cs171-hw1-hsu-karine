1. What's missing? Is this bar chart usable in its current form?

The title, labels, and scale are missing. The bar chart is not usable in its current form because we have no idea what data the bars are referring to. 

2. What is the role of each of the three nested levels of g elements? (keep in mind you'll be adding a title to the chart)

A g element is used for grouping elements for the chart. The first g element sets the margins and translates the origin over according to the margins. The second g element puts all the text into a group, and the last g element creates a group for the bars in the bar chart. 

3. Complete the implementation section below. Is there any consequence if you add the text elements before or after the rect elements? Why?

If I add the text elements before the rect elements, the rectangles will be laid out on top of the text elements. If the text elements are added after the rect elements, the rectangles are laid out first, and then the text is laid out on top of it. 