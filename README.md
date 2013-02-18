css-questions
=============

CSS Interview Questions

Q. 
   1. Explain the w3c box-model. 
   2. How does the IE box model differ? 
   3. Is there a way to make them behave the same?

A. 
   1. When declaring the width of a block level element, the width property defines the width of the content. The border and padding, if any, are added to that width. If you declare a box to be 100px wide, and you have 20px of padding and 10px of border, your element will be 160px wide.
   left border + left padding + width + right padding + right border = actual width of element in the w3c box model. The issue is if a box has a width of 100% and you add padding or border, the element will take up more than 100%.
   2. The IE box model puts the padding inside the box, so the 100% width element will not go beyond its parent's borders.
   3. The box-sizing: border-box; property/value pair can be used to make IE8+ and all other modern browsers use the IE box model. This property is still prefixed in Firefox. 

Q. For generated content, are there any required properties? And, if so, what are they?

A. The only required property is 'content'.


