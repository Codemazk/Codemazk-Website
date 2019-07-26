# Codemazk-Website
## Read it!
We are using our own codes mostly while designing the website. Make the codes reusable. If a component is being designed, be specific on what the class name should be, ID should be, and everything you create should follow the [[1]][naming-guidelines].

###### Dont use
1. Bootstrap

###### Usables
1. jQuerry
2. CSS - (Media Queries)
3. Javascript
4. HTML

[naming-guidelines]: #naming-guidelines "naming guidlines"
##### Naming Guidelines
While creating a css class do not use _ (underscore)

###### Dont
`.content__wrapper--first`  - Avoid wrappers too
###### Do
`.content-first` - Make a simple class

If you&#39;re creating a banner with, image background, title, content, and button. Refer below;

**CSS**
```css
.banner{
	background-image: url('https://images.pexels.com/photos/459225/pexels-photo-459225.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500');
	background-repeat: no-repeat;
	height: -webkit-fill-available;
}
.banner .content{
	position: relative;
	top: 25px;
	left: 40px;
	background-color: #000000a6;
	padding: 10px 20px;
	width: fit-content;
}
.banner .content span{
	color:white;
}
.banner .content span.text{
	float:left;
	width:100%;
}
.banner .content .button{
	float: none;
	top: 2px;
	position: relative;
}
```
**HTML**
```html
<div class="banner">
	<div class="content">
		<span class="title"><h1>Hello</h1></span>
		<span class="text">This is some sample content. Please refer the code!</span>
		<button class="button">Click Here</button>
	</div>
</div>
```

#### Structure of Our main stylesheet
```css
/*
####################################################
M E D I A  Q U E R I E S
####################################################
*/
 
/*
::::::::::::::::::::::::::::::::::::::::::::::::::::
Bootstrap 4 breakpoints
*/
 
/* 
Extra small devices (portrait phones, less than 576px) 
No media query since this is the default in Bootstrap because it is "mobile first"
*/
 
 
/* Small devices (landscape phones, 576px and up) */
@media (min-width: 576px) {  
 
}
 
/* Medium devices (tablets, 768px and up) The navbar toggle appears at this breakpoint */
@media (min-width: 768px) {  
 
}
 
/* Large devices (desktops, 992px and up) */
@media (min-width: 992px) { 
 
}
 
/* Extra large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) {  
    
}
 
 
 
/*
::::::::::::::::::::::::::::::::::::::::::::::::::::
Custom media queries
*/
 
/* Set width to make card deck cards 100% width */
@media (max-width: 950px) { 
 
}
 
```
