Title: Horiseon: HTML, CSS, and Git: Code Refactor

Description:
This Homework required me to refactor the html and css code for Horiseon's services page to ensure that it includes semantic html and is compliant with accessibility requirements amongst other things.

I have listed the main changes that have been made to the original code:

HTML

1. Removed as many div tags as possible and replaced with semantic html;
2. Added nav tags to the header to comply with semantic html;
3. The Search Engine Optimisation link in the header was not clicking through  
   therefore added an id tag in the main section (line36);
4. Added figure tag (semantic html) around the main image;
5. Added main tag around the main content of the page;
6. In the main section, removed repetitive classes and added a singular class
   "services". This was also replaced in the css file with a single class. The other styling sections were changed to refer to the "services" class;
7. Added alt tags to the images in the three sections in main and aside;
8. Repeated the same process with the aside section i.e. replaced all the
   classes in section with one class "benefit-aside";
9. The footer H3 tag was changed to a H2 tag;
10. Added comments to show what each part contains;

CSS  
11. Moved up the Main section css to before the aside section; so it  
 corresponds with the HTML code. 12. As per 6 above, removed the repetitive css classes and replaced with
services class; 13. Followed the same process as per 11 and replaced all the aside classes with
the benefits-aside class. 14. Removed references to old css classes and replaced with new class names 15. Added comments to each part to show what each part contains.

Please note screen shots of working website:
Image 1 to show URL: ![hwimage1](./assets/images/hwimage1.png)

Image 2 to show full screen: ![hwimage2](./assets/images/hwimage2.png)

Link to deployed webpage: https://bkay1.github.io/Homework-Week-1/
