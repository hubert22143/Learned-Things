# Blog? Treat this repository as something I use to say about the things i've learned.
In this repository, I will write the things I've learned, which doesn't contain any html, js, or any other files than txt. <br>
This repository is intented to help me to recap the most informations i've gathered at the end of the day. Though it might not be really helpfull and understandable for you, it is for me. <br>


8/18/2023   5:49PM
<br>
Today I've learned about emmet syntaxes as well as some usefull cheat sites
<br>
https://docs.emmet.io/cheat-sheet/
<br>
https://htmlcheatsheet.com/css/
<br>
I've learned that, we can improve our type speed in html drastically, by using emmet syntaxes. Emmet syntaxes are built-in extension, in the VS code, which allows us
<br>
to create the elements way faster.
<br>
The example for implementation emmet syntaxes is following if we wish to create div, which contains 3 p elements, with their own class:
<br>
syntax > is saying that, the p element is the child of div. So basically the div contains 3 p elements as we wish.
<br>
syntax $ describes the item numbering, from 1 to x
<br>
syntax * describe exactly what you think it's doing, it simply works as multiplier, we want it to contain 3 elements, so we're multyplying by 3.
<br>
div>p.class$*3
<hr>
8/18/2023   6:38
<br>
I've learned some info about what are svg's.
<br>
While I confidently don't know a larger part of what svg's are more in advanced meaning but I surely get them in their basic meaning.
<br>
The svg(Scalable Vector Graphics) itself is scalable image format, which means we can format them as we wish, and they won't lose of their quality.
<br>

SVG's are defined by xmls markup language, which gives us some benefits at the first step. Thankfully to that, they are formated by xml's,
<br>
they are human-readable and machine-readable as well,which means we can understand them, but they are kinda confusing at the first glance.
<br>
The svg format looks like:
<br>
The xmlns is a global format(svg standard rather should I said) for svg files, it let us knows, that basically this is the svg file. The value is the standard formula for the svg.
<br>
In the viewbox we've got four variables following indicating:
<br>
min-x="" dependly of our usage it will shift x units to the right, or to the left if the value is negative,
<br>
min-y="" same as above, it will shift x units, but this time vertically, to the up or bottom if the value is negative,
<br>
max-width="" defining the max width of the created box
<br>
max-height="" same as above, bud the height of created box.
<br>
"<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"></svg>"
<br>
By defining all those values, we are certain that the browsers and software, will correctly understand that the content is svg, and within the box will be created elements
<br>
dependingly of the given viewBox values.
<hr>
<br>
8/19/2023 2:08 PM
<br>
Today I've recapped some basic, but meaningfull things about creating the table in html.
<br>
The syntax for creating table is following:
<br>
This is a basic table structure. The "table" indicates that we are starting and ending the table.
<br>
The "caption" indicates what the table is writting about.
<br>
The "theader" is a thing which helps recognize the structure of table for screen readers even betters, we should indicate it always.
<br>
It also improves the readability and make it more accessible and comprehensible for all users. Overall it is recommended to always include those things in the 
<br>
table html property.
<br>
The thing with `tbody`, and `tfooter` is the same. In `tbody`, we're indicating the main data of our table, the footer is basically the last row in the table. 
<br>
It is also worth to mention, that whenever we apply the `tfooter`, no matter where the table row will sit, it will always be pushed to the down due to tfooter functionality.
<table>
  <caption>Table Caption</caption>
  <thead>
    <tr>
      <th>Column Header 1</th>
     <th>Column Header 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data Cell 1</td>
      <td>Data Cell 2</td>
    </tr>
    <!-- Additional rows and data cells go here -->
  </tbody>
  <tfoot>
    <tr>
      <td>Footer Cell 1</td>
      <td>Footer Cell 2</td>
   </tr>
  </tfoot>
</table>

<hr>
<br>
8/20/2023 2:26 PM

Today I've learned some about the responsive units.
<br>
It's mostly about using the rem or em to the font-size's of our's body.<br>
By basic, the default font-size on body is 16px(1rem/em === 16px). If you want to care about the user settings, and want your font-size to be responsive on the site then you shall use one of those.<br>
The em units works following: <br>
If we set font-size on the parent for 1em, the child will get font-size doubled from before so 2em, so the font-size is basically nesting through elements. <br>
That's why personally I choosed that, I will use the rem property, which doesn't nest through the elements. If the font size on the body equals 16, and you set for example on some element <br>
font size which equals to 0,875rem, it will equals 14px.

I've also been learning about some hard concept for me, which are viewports properties. <br>
While I certainly understand the usage of viewport heigth, which would be in case: <br>
We have declared the header, and footer, and both of their min-heigth equals to 60, if we would like to <br>
It is also worth of mentioning, we should always define the heigth of element using min-height, by doing so, <br>
we assure that the responsive styling will be applied, and overall it is recomended to use that value instead of basic heigth <br>
Make the body heigth to appear in the rest of available space(then we substract the header, and the footer heigth from the total viewport height, so total available - our usage from header and footer), we would just use calc(100vh - 120px) <br>
And that's the usage in case that I would use it.

I would rather not using vw 100% to declare the width of our elements, because of the unnecessary scroll showing at <br>
the bottom of the site. I know that I can esaily hide it by using overflow-x: hidden;, but still it doesn't appeal to me <br>
that's why I would stick with the default usage, of width 100%. But I can see the usage of this, in case we would need that <br>
flow-x, then it is certainly usefull in those scenarios.
<br>
<hr>
8/21/2023 8:01 PM
Today I've recapped some properties in css, such as: background shorthand, and the properties, margin,padding and the overflow aswell, and many other<br>
properties. I've also realized how important it is, to use header,sections and the footer itself as well. Very simple things, but how much important they are.<br.

<hr>
<br>
8/22/2023 4:34 PM<br>
Today i've worked on css properties, and done a lot of example exercises which are including properties like : [attribute="value"]($^properties), [last-child],[first-child],[nth-child], and others not included in the exercises like : [::selection] , [::marker] , [:link] , [:visited] , [:focus] , [:active]. <br>
Examples I am talking about you can see at the site: https://flukeout.github.io/

I've learned also about top element called :root, there we will place our global variables and properties such as box-sizing:border-box, which would mean that any border or padding will be included into the box, which will maintain prefered stylisation. So for example if you set width and heigth equal to 100px, it will be added to the actual width and heigth.

<br>
<hr>
7:25 PM 8/23/2023<br>
Today I was learning about complex selectors. While there the common way to refer to some element is setting them up class or id we can also do it other way.<br>
The descendant selector is the most common, it matches an indentified ancestor. For example:<br>
article h2{}, <br>
In this example only elements in article which include h2 element would be selected. <br>
The Direct Child Selector is a bit different. <br>
The syntax for it is following : article > p {}, <br>
It means that the every p element in the article will be selected, but it can't be nested. For example if there was article, and inside it div, and inside the div element p, it wouldn't be selected. <br>
The next thing is General Sibling selector, they are created by using the tilde character ~,<br>
For example : h2 ~ p {}, that means, the p selector will be selected, if they will share the same parent. <br>
Adjacent Sibling Selector, <br>
For Example : h2 + p, it will only work for the p element which is written after the h2. <br>
Attribute present selector, <br>
In order to use this one, we need to use square brackets, for example:<br>
html<br>
"<a href="#" target="_blank">...</a>"<br>
css<br>
"a[href="http://google.com/"] {...}"<br>

Attribute contains selector <br>
This one we use when we need to find element based on part of an attribute, <br>
The attributes we can use are : * , ^ , $ <br>
The * means, that it must appear, or be contained within attribute value, for example: <br>
"a[href*="login"] {...}"<br>
and html: <br>
"<a href="/login.php">...</a>" <br>
The ^ means, that it must start with stated value, <br>
And the $ means, that it must end with the certain value. <br>

In case that, that the attribute is spaced, we need to use ~, and while it is hyphenated, we need to use =. <br>

Some infos about User Interface State Pseudo-Classes. <br>
Pseudo-Classes, are element state which include somewhich of those elements : :enabled, :disabled, :checked, :indeterminate, and some other which already mentioned in some other way.<br>
The element indeterminate, means the checkbox or radio button that has been not selected, or unselected. <br>
<br>
The important things to know about css, are also childs.<br>
:first-child , :last-child , :only-child <br>
:first-child - Selects the first child of an element, for example: li:first-child{}, will select the first child of li,<br>
:last-child - Will select the last child of an element,<br>
:only-child - div:only-child will lok for a division that is the single child of a parent element, without any other siblings. <br>
Childreens of parent are pretty helpfull, and it is aften used. But sometimes you need to select the first, last, or only child of a specific type of element, there are where those comes handfull: <br>
:first-of-type, :last-of-type, :only-of-type,
The main difference between them is that, we select the certain element of type, so for example<br>
When the :first-child would select the first child of some element, the :first-of-type, would select certain first type of element.<br>

The very handfull in styling comes also :nth-child(n) & :nth-last-child(n) <br>
Their usage comes very handfull, when we want to select certain elements in some group of for example li. <br>
Lets say we have ul, and inside we have 6 li. And we want to only select the third, and sixth li. <br>
In order to do that, we can use li:nth-child(3n){}, which means it will selects every third character of li. It works like that: 3x0 , 3x1 , 3x2 , ... <br>

We can also select the "base position" of which we want to come further, for example li:nth-child(2n+3){}, it means that, we will start from third li element, and keep adding 2 till there's no more li to stylize. <br>
We could also select the negative number for n, which would mean that we're starting from 0 position. So basically if I wrote like li:nth-child(-n+4), it would start from position 0, and add those four li which will be styled. <br>

The :nth-last-child(n) simply changes the direction of counting, so I won't give any examples for this, since it's just doing that, and the logic, and everything is the same, just from the back. <br>
We can also select it for types : :nth-of-type(n) & :nth-last-of-type(n) , the logic and everything stays the same. <br>

Pseudo-Classes: <br>
:target - In order to this property to work, we must give the id for section, and the same id for the hyperlink we want to refer the section with. <br>
:empty - It will select element which do not contain childreens, or text nodes to be selected. <br>
:not(x) - It will select every class, that does not contain the x(class) element.<br>

Pseudo-Elements: <br>
:first-letter - As you think, it select the first letter of certain element <br>
:first-line : As you think, it selects the first line of an element. <br>
:before - it creates some not signitificant content to our element before the text,<br>
:after - Same as upper, but after the text.<br>
::selection - Have you ever played with tab on some site? The selection is exactly for that to style the selected the part of document, or highlitghted by tab action. <br>
<hr>
<br>
7:11 PM 8/24/2023
Today I've learned about Positioning. There are a few positioning of elements which are very usefull, and worth of mentioning, they includes: <br>
- position: static - That positioning is by default on every element, the rules about it is very simple, you simply can not use top, bot, right, and left properties, they won't affect your element. <br>
- position: absolute - This positioning is pretty usefull if we want to put the element to stay in the same position even when other element might occur, and move it, it simply won't because of that. For example,<br>
if we want to put position absolute, within the parent, we need to use position:relative for the parent, in other case the element we've used absolute on, will move to the full up,bottom,right or left due to default position static for the parent container, overall it is very usefull position, but we should avoid it in cases we are creating the layouts - it isn't made for that. <br>
- position: relative - This positioning is often misussed, the main reason why you would use it, is that it simply allows you to use the properties top, right, bot and left. <br>
- position: sticky - This positioning is working like relative by default, once you scroll down, it will act as fixed so it will appear dependingly of which properties we set, the thing worth of mentioning is that, it won't act as fixed once it passes it's parent heigth <br>
- position: fixed - This is very usefull for nav section, it helps our nav to stay at the top of the site, and provide fast accesibility to it. 
<br>
<hr>
7:15 PM 8/25/2023 
Today I've learned about four really important properties for making our website responsive. <br>
We use those properties in order to make our site fluid and responsive. <br>
clamp(min,preffered,max) - This property is used mostly to font-sizes, it takes the preffered value as default, and while u shrink the page it won't get narrower than the min value, also it won't get wider than max value. <br>
calc(1rem + 2vh) - We can use this property in case to calculate something with different units. <br>
width: min(300px,50%) - We specify the two values, by default it's gonna be the 300px, but if we go shrinker that that, then it will become the 50%<br>
width: max(300px,50%) - We specify the two values, then we basically set the width to 50%, unless the available space drops to 300px. <br>
<hr>
<br>
12:21 PM 8/26/2023
Today I've learned about custom properties. <br>
A custom properties is, a custom, choosen by the user wishen property. The syntax from custom property is following : --name:value; <br>
We should define the custom properties in the :root of html, which is the highest available level. This allows us to have access to the custom property on every level of html, root has more significance than html. <br>
To access the custom property we write following syntax, for example: background-color: var(--name); where --name equals the --name of custom property described in our root level. <br>
This approach simplifi the management of consistent values throughout your stylesheets, enancing maintainability and making it easier to apply changes across multiple elements. <br>
<hr>
<br>
Today I've learned the importance of compatibility on various browsers. The most important thing to remember while working on your project is to check if every, or most of browsers are compatible with the new features. We also should give special meaning to Ios browser which is safari. Though the users are available to install other browsers, it's all running by safari engine, due to 'security reasons', we certainly want to check if user get it's designed output on most of browsers. 
<br>
<hr>
<br>
1:58 PM 8/28/2023 <br>
Today I've learned about Preprocessors and Frameworks. <br>
The framework itself is some packed content itself ready to use. A proper examply of this would be for example BootStrap,Foundation,Tailwind. The most advantages of why would you like to use the framework, mostly would be because of responsive-design, as well as it makes easier to build things on site. They are also usefullness, because of the community. If you comes to happen a error due to some framework, you can easily find a solution of network. It also made your work a lot faster, instead of building site of stratch, you can use some already pre-built elements like nav, buttons, etc. The disadvantage of frameworks like BootStrap, is that they made look sites very similar. Personally, as a user I wouldn't enjoy entering a two sites, and see that the two site's are almost designed the same way. Sometimes it can make it very hard to make a custom implementation, it can be really challenging to deviate from estabilished patterns and components provided by the framework. Due to it's patterns, you can sometimes across in some not wished behaviour on styling output from framework. 
<br>
Overall, there are a lot od advantages, and disadvantages of using frameworks while working on some project. Personally, at my level, I see no advantages to trying learn any framework, because I still lack the basics, and it's brackless to rush more advanced things without even knowing about the basics firsts. The choice if I use them will most probabely depend on my future employer.
<br>
The preprocessors are tools which make write our css way faster. They extend our basic vanilla css, adding some functions, variables, nesting. They also make our css more readable, more-well organized, and allows us to not repeat code. The examples of currently used preprocessors are: Sass,Scss,Less,Stylus. <br>
I won't be writing in details about every of them, since I dont know them that well, but I will give a basic differences between them. <br>
The main things which they differ on are syntaxes. For example, While on Sass, you must avoid the semicolons, and bracket's, on Scss you must have them provided. There also are other ways of variable syntax, while on Scss and Sass we define it by using : <br>
$font-color #333 while scss, and $font-color: #333: while sass, the Less actually would use @ syntax for defining those. <br>
The main choice of choosing between them differ's on your, or employer needs. The most hard thing would be learning about the syntaxes, I mean while the syntaxes on Sass aren't the main problem, as you can see the main problem becomes the bad-readability, so we have to have in mind about the basics while wishing to choose any between them. It's also worth to have in mind, that the Sass is currently the most used preprocessor.
<hr>
<br>
8/29/2023<br>
Today I've recapped some informations about creating form. <br>
We use the form, in case we're submitting something, where interactive buttons comes in the way.
The form itself needs two default value's, action which processes the form submission, and the method. There are two main method values POST and GET. The biggest difference between them is that, when you set GET value, the data which you apply, lets say for example when you register a account, then after clicking button apply, all data you've written will appear in the link message. It is very insecure in usage for that cases. It also allows the user to write some script and make weird thing's happen. Overall when we want to use GET, we should know what we're doing we would use it for example for searching purposes. The most value which we will using will be POST, because it is secure, it doesn't allow to write some script and apply it to the site.
<br>
Now, the form contains input values, in order to make things readable for various devices, such as a screen reader and so on, we should use label. We use that basically for saying what's the input there is for, and to improve the user experience on such a devices. 
<br>
We can also use some placeholder on some input, so user will know even better what this input is for. <br>
In order we want to group all related unit's into one, we can use the Fieldset which will create a nice border, in order to improve it even more, we can use the legend, which will go into the border.
<br>
<hr>
<br>
12:05 PM 8/31/2023 <br>
Today I've learned some forms attributes, <br>
required - This validation make a certain input neccessary to write/check, if we try to submit the form without making that input, "please field this field" output will show. <br>
minlength / maxlength - Those validations have usage in the inputs for the min/max length <br>
min/max - Those validations have usage of type number for the min / max quantity <br>
pattern - We can use this validation for make certain pattern for example zip-code pattern="^(\d{2}(-)\d{3}$)" <br>
:focus , :valid , :invalid , :hover, ::placeholder, - some pseudoclasses to style in css <br>

<hr>
7:43 PM 9/7/2023 <br>
Today I've started learning about grid <br>
The main things with what grid comes in, is two dimensional layout. It means that, instead of working like on flex - one dimensional layout row or column, we can work on both on grid, which grant us access to modify their width, height, location, as we would like to. In order to access column / row layout in grid, we need to use those properties <br>
  grid-template-columns <br>
  grid-template-rows <br>
  But we can use as well the shortcut: <br> 
grid-template: 50px 50px / 50px 50px 50p - Where before the slash / we're indicating the row, and after the column.
<br>
<hr>
Today I continued learning about grid. <br>
How can we set the gaps between columns / row : <br>
grid-column-gap: 10px; / grid-row-gap: 10px; <br>
How can we set the implict grid value? <br>
grid-auto-rows: 50px // grid-auto-columns: 50px // - It will set 50px row value, and 50px column value, which will be used for every next content which haven't been defined in the grid-template. <br>
The most wished value to use for track size is fractional unit, for example: <br>
grid-template: 1fr 2fr / 3fr 1fr  -- It will make the second row have 2 times more space than the first row, and 3 times more column space than second column space <br>
Let's say we have .container which is grid box, and the .item -a, which is grid item: <br>
.item-a {<br>
  grid-column-start: 2;<br>
  grid-column-end: five;<br>
  grid-row-start: row1-start;<br>
  grid-row-end: 3;<br>
}<br>
Though, we haven't defined any row / collumn, the following thing are going to happen with -item-a. <br>
It's going to be positioned at second column,(the website will automatically create as much as provided example need rows/columns) and the positioning will end at column five, it will start from the first row and goes untill third row.
<br>
We can also define explicitly the name of the lines, for example: <br>
.container {<br>
  grid-template-columns: [first] 40px [line2] 50px [line3] auto [col4-start] 50px [five] 40px [end];<br>
  grid-template-rows: [row1-start] 25% [row1-end] 100px [third-line] auto [last-line];<br>
}<br>
There, we define that the first column is named first, and has width of 40px, and heigth of 25%, the first row is called row-1started, followed by row1-end. Then we have defined the line2 column which has 50px, line3 column which has auto property it means that the free space, that the container has will be filled by line3 to col4-start. We would like to achieve this behaviour, in order to make it more readable, in case the user is debugging, and looking for some error in chrome developer view for example.<br>
There is also one usefull property we could want to use, which is repeat(), <br>
the repeat function takes 3 values, ((number of times we like to repeat,(value of chosen grid-template), [and the name we would like to add every next line]) for example:<br>
grid-template-columns: repeat(3, 20px [col-start]); which would be equivalent to <br>
 grid-template-columns: 20px [col-start] 20px [col-start] 20px [col-start]; <br>
<hr>
Today I was learning about javascript object and object constructors. <br>
    The simplest form of an object is created like this:<br>
javascript<br>
myobj = { age: 16, ... };<br>
You can access the value of age using dot notation:<br>
javascript<br>
console.log(myobj.age);<br>
    An example of an object constructor is as follows:<br>
javascript<br>
function Person(name, age) {<br>
    this.name = name;<br>
    this.age = age;<br>
}<br>
You don't need to explicitly return the object in the constructor unless you are creating an instance using the new keyword. For example:<br>
javascript<br>
const Adrian = new Person('Adrian', 12);<br>
If you want to create an object without using the new keyword, you can return the object explicitly within the constructor. <br>
<hr>
<br>
Learning About Objects, Prototypes, and the this Keyword in JavaScript<br>
Today, I continued my journey into the world of JavaScript objects. I began by solidifying my understanding of the basics. Now, I'm ready to explain how the inheritance of prototypes works and what the prototype property is, as well as shed some light on the mysterious this keyword.<br>
Prototypes and Their Role<br>

Let's start with prototypes. Every object in JavaScript has a prototype. To illustrate this, consider the following function:<br>
javascript<br>
function Player(name, surname) {<br>
    this.name = name;<br>
    this.surname = surname;<br>
}<br>

When we create the Player function, it automatically creates its own prototype. We can extend this prototype by adding as many methods as we need, like this:<br>

javascript<br>

Player.prototype.fullname = function() {<br>
    console.log(`Your full name is ${this.name} ${this.surname}`);<br>
};<br>

Here, we've added a method called fullname to the prototype. This method can be accessed by any instance of the Player object via the .fullname property. It simply returns the full name.<br>

To create an instance, we need to invoke the constructor function, like so:<br>

javascript<br>

const playerOne = new Player("Hubert", "Baciak");<br>

Now, playerOne has the name set to "Hubert" and the surname set to "Baciak." This instance can already use the prototype method fullname because of inheritance. By doing this, we effectively link the playerOne object to the Player prototype chain. We could also add prototype methods specific to playerOne, but we won't do that here.<br>
Checking the Prototype Chain<br>

To confirm that playerOne is indeed linked to the Player prototype, we can perform the following checks:<br>

Using Object.getPrototypeOf:<br>

javascript<br>

if (Object.getPrototypeOf(playerOne) === Player.prototype) {<br>
    console.log("playerOne is attached to the Player prototype.");<br>
} else {<br>
    console.log("playerOne is not attached to the Player prototype.");<br>
}<br>

Or, using the instanceof operator:<br>

javascript<br>

if (playerOne instanceof Player) {<br>
    console.log("playerOne is an instance of Player.");<br>
} else {<br>
    console.log("playerOne is not an instance of Player.");<br>
}<br>

Both methods confirm the connection between playerOne and the Player prototype.<br>
Modifying the Prototype Chain<br>

We can also set the prototype chain to link to another prototype using Object.setPrototypeOf. For example:<br>

javascript<br>

Object.setPrototypeOf(playerOne.prototype, Player.prototype);<br>

This line of code makes playerOne inherit all its methods from Player.<br>
Understanding this in Constructors<br>

As for the this keyword in object constructors, it's rather straightforward. In the context of an object constructor, this refers to the object created via method invocation. Consider this example:<br>

javascript<br>

function Foo() {<br>
    // Here, `this` refers to `fooInstance`<br>
    this.property = 'Default Value';<br>
}<br>

// Constructor invocation<br>
const fooInstance = new Foo();<br>
console.log(fooInstance.property); // Outputs: 'Default Value'<br>

In this case, fooInstance inherits the .property from Foo because that's simply how inheritance and this work in constructor invocation.<br>
<hr>
<br>
Today, I began learning about factory functions and the module pattern in JavaScript. The primary distinction between factory functions and constructors is that factory functions return objects immediately without using the 'new' keyword.<br>
<br>
The Immediately Invoked Function Expression (IIFE) enables us to execute a function immediately after defining it, example: <br>
(function() {<br>
  let message = "Hello, IIFE with 'let'!"; // 'message' is scoped to the IIFE block.<br>
  <br>
  console.log(message);<br>
  It will immediately return console.log message.
})();<br>
<br>
<hr>
Today I continued learning on factory function. <br>
The main difference between factory function, and constructor is that, the factory function does not use the new keyword to create an object which can lead to many bugs. <br>
Factory function allows us to avoid the namespace purity, there won't be issues with instances, as there may appear on constructor functions. <br>
It enchances code maintability, since we're writing the private, and public functions in factory function. <br>
Overall, using facotry function over constructors, can lead to more maintability code, and free from bugs code. <br>
<br>
<hr>
<br>
Today I've started on learning Node Pack Manager. 
The reason why node pack manager is necessary, is that because it allows us to freely share our code with developers with no perpexlity about the version of the project. It allows us to continue some work from certain point of production, which is usefull for organization co-operation work. The npm after initialization is creating one important file which is package.jsonm,, which contains all metadata, about packages,used version etc.

The second important terminology are bundlers. They work along with the npm. It is used for management for the code, increased readability, more comfortable way of writing the code, essentially it allows you to keep everything up to date.
Bundler's are working following way, the first thing they have to contain is the entry file, which is generally your main file. This process is called Dependency Resolution. The way it works, it's looking for dependencies in order to determine the dependencies of other dependencies, and sort it dependingly. The main reason why that's important is that, it automaticaly enable the modules to construct a dependency order, and wait for browser request for data. It also prevent the naming conflicts, it also detects all unnecessary files and removing it. After that is done, the stage Packing appears. During this process, everything basically get packed into one file, and is ready to be loaded by site. 

The most popular bundler is Webpack, which I will also stick to use. The way webpack works is: At the first stage it looks for entry [12/22/2023] which should be our main file dependingly on our structure, module.exports = {  entry: './app/index.js',  };,
we should also write destination of the output usually it's directory named dist const path = require('path');  module.exports = {  entry: './app/index.js',  output: {  path: path.resolve(__dirname, 'dist'),  filename: 'webpack-app.bundle.js',  },  };
Loader point which allow webpack to transform, and bundle non-js files, Plugins which simply let us do some nice resource optimization and management, Mode which allows webpack to configure it's configurations or development mode dynamically.
After doing that, it's creating one file which is transformed, with executed all those things I've writed, and that's basically it. Worth of mentioning is that we're simply running it by using npm i webpack.
The pros of using webpack are: 
- It has a rich plugin ecosystem which allow us to bundle almost everything
- Due to a lot of customization settings webpack is most definitely chosen most of the times as being the best bundler available
- Efficient error debugging process that makes your work easier
- Solid third party ecosystem
  However, though it's the best webpack, it's not bug-free software, and it's much more complex when we're learning it deeply, it's a double edged sword.

Now some info about ES6 modules. The ES6 modules is constructed with two statements which are import and export.By using that, we no more need module pattern. Module pattern allowed us to return the function's which we wish to be returned, with es6 module used, we're clearly stating which functions are we interesting in exporting, and it allows us to freely import the code in different file of js following the convention: 
// a file called myModule.js
const functionOne = () => 'ONE';
const functionTwo = () => 'TWO';
export {
  functionOne,
  functionTwo
};
// index.js in /src folder
import {functionOne, functionTwo} from './myModule';

It simply allows us to make it a little bit easier than in module patterns.
///
Keys in React. They work as an unique identificator for chosen type from data for example in list of items. 
//




