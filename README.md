# IDDevelopment-Blog

Week 1 Blog

In this week, i learnt various html elements:
My Development blog
html-Defines the root of an html document
head-contains information for the document
body-includes the important information
h1 to h6 - heading sizes from biggest to smallest
p means paragraph
em means emphasis the text
img to include image
hr-horizontal rule
iframe means to include vidoes
a to include a hyperlink
div for parts of a document
ul means ordered list and li means each list element
span means a section of the code
table-to create tables using tr,th,td

Week 2

Name flies using lower-case
Name files with intent and meaning
Div element itself has no inherent meaning
Semantics is header, nav,article,section
header is for top page
articles used for news content, blog posts
nav used for navigation
css is to design the website
css rule selector{property;value;} for eg. p{ color: purple;}
inline element eg. p style ="text-align: left;, Just a sentence
can use font family
link element ro external style
id attribute #myElement
class attribute .myClass
pseudo classes eg.a:hover { /_ moused over link _/ color: green; }
Can use google fonts and add to the page to use them
we can adjust font size. font style and many more
Margin is for the pixel boundary outside the box
Padding is for the pixel boundary inside the box

week 3

-The form tag is used to send the url to send form data to and method is needed
-The input tag to need text,date, color and sometimes placeholders
-Labels needed to indicate username or password
-Vallidations are required to ensure the input is not empty by using "required"
-Some basic input categories are single line text, multiple line tezt and selection
-Input fields examples:email,Url, telephone,number,date,time
-Descendant selector example: section p{...} or .container h1{..} , hence used to identify certain parts of code
-Inheritance meaning css styles can be inherited from parent elememnts
-Specificity determines how browsers decide which css rule takes precedence
-Universal(\*), type(p), .class(.example), id(#example)

- Cascade: style declarations cascade and are read from top to bottom
  -!important keyword overrides source order and specificity and its added just before the end of rule declaration before semicolon;
  -General rule:
  selector{
  property:value;
  anotherProperty: value;
  }
- Background property can set a background
- Assign a unique name to HTML element as an id should not repeated
- Unlike id,classes can be reused over and over
- Media Query @media using min-width and max width
- Positioning:
  Relative- moves elements around around relative by nudging boxes around
  Absolute Position -offset is relative to the entire browser window instead of the original position of the element
  Fixed position- fixed elements do not scoll with the rest of the page
  z- index- lets you control the depth of elements on the page
  z-index- work ONLY on elements with a
  position property set to absolute, fixed,
  or relative
- Flexbox container is the parent of the flex item
- Wireframes are not visual design, typography, iconography or photography
- Wireframes can generate ideas, aids discussion and show content hierarchy and establish key functionality
- Static Wireframe usually quick to create and variety of tools and software but its not responsive
- Fidelity : The level of detail used to produce a wireframe
- Low fidelity wireframes can be created quickly , get out many ideas before committing to one direction, can be a simple sketch with pen and paper
  but might not have enough detail for every situation
- High fidelity wireframes contains more details than the low fidelity and closer representation of final layout but stakeholders might confuse with the designs
- Hyperlink: using this <a> and use target="\_blank" to open in new window or tab
- Image: use <img src > and alt attribute needs to be present and also can use title attribute to display a string of text upon mouse hover
- File names should be lower case and name files with intent and meaning

Week 4

Reasons for Responsive images

- Auto resize based on screen size
- Better Performance( Load higher resolution images only when needed)
- Provide better design control depending on device

(scale up and down)
Example:
.responsive-img(
width: 100%;
height: auto;
)

- To make images never larger than original size
  use (max-width: 100% property height auto)
- For different resolutions we use srcset
- To fit images to a box use (background-size: cover)
  -Flex wrap allows items to fit into a new row if there is not enough space
- I learnt how to use github and how to commit my work to github
  Important commands
  ??? git clone and git init: set up new repositories
  ??? git add, git status, and git commit: used when committing new
  versions of files
  ??? git log: view a list of old commits
  ??? git mv and git rm: move and remove files tracked by Git
  ??? git push and git pull: synchronize commits with remote repositories

- Wireframes are used to tell the flow of how a site is and the information flows

Week 5
Javascript
