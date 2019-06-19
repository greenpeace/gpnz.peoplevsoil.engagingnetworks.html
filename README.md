# gpnz.peoplevsoil.engagingnetworks.html
Header / Footer template

## EN page builder instructions

### Setup

Create a template

Paste Header / Footer code

Create a new petition 

## Page 1

#### Structure
1. Advanced row - fixed header - left column
2. Single row - right column form
3. Advanced row - footer

### Add advanced row width 1 column for left side content

* add GP logo HTML to text block
 
 `<p><img id="gp-logo-header" src="https://www.peoplevsoil.org/assets/peoplevsoil2018/img/greenpeace-black.svg" /></p>`

edit text block style: Custom class names: `header-sticky`

* add PVO logo HTML to text block

`<p><img height="30" src="https://www.peoplevsoil.org/assets/peoplevsoil2018/img/peoplevoil.svg" /></p>`

edit text block style: Custom class names: `pvo-logo-heading`

* add HTML to main text block

`<h1 id="mainHeading" style="color: #FFFFFF; box-sizing: inherit; font-size: 78px; margin: 40px 0px 21.375px; font-family: Anton, Helvetica, Arial, serif; line-height: 78px;">LET&#39;S<br style="box-sizing: inherit;">MAKE<br />
OIL HISTORY</h1>`

add paragraph text below heading

![Screen Shot advanced row 1](https://raw.githubusercontent.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/master/Screen-Shot-advanced-row-1.png)

![Screen Shot PVO logo position](https://raw.githubusercontent.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/master/Screen-Shot-PVO-logo-position.png)

### Add single row for right side content

* add text component above form: 

add class `copy-toggle` - to enable show/hide
  
* add form blocks for each field 
  
add class 'form-toggle' to name & phone fields - to enable show/hide

### Add advanced row for footer content set class `footer-custom`

* add HTML to code block

`<div id="footer-logos">`

`<img class="footer-logos-left" height="25" src="https://www.peoplevsoil.org/assets/peoplevsoil2018/img/peoplevoil.svg" />`
	
	`<ul class="footer-social-media">
		<li><a href="https://twitter.com/"><i class="fa fa-twitter fa-2x"></i></a></li>
		<li><a href="https://www.facebook.com/"><i class="fa fa-facebook-official fa-2x"></i></a></li>
		<li><a href="https://www.youtube.com/"><i class="fa fa-youtube-play fa-2x"></i></a></li>
		<li><a href="https://www.instagram.com/"><i class="fa fa-instagram fa-2x"></i></a></li>
	</ul>`

	`<img class="footer-logos-right" height="25" src="https://www.peoplevsoil.org/assets/peoplevsoil2018/img/greenpeace-black.svg" />`
`</div>`

* add HTML to text block

`<p style="text-align: center;"><span style="color: rgb(176, 176, 176); font-family: Amiko, Helvetica, Arial, serif; font-size: 12.8px; letter-spacing: -0.3px; text-align: center;">&copy;2019 - Greenpeace | All rights reserved</span></p>`

![Screen Shot footer logos](https://github.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/blob/master/Screen%20Shot%20footer%20logos.png)

![Screen Shot footer advanced row](
https://raw.githubusercontent.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/master/Screen%20Shot%20footer%20advanced%20row.png)

## Page 2

* Thank you: add text block

* Share buttons: add from Social Details tools (sidebar)

* Donate button: add text block paste HTML in source editor (select text then select  donate campaign link from text format buttons to chain campaign)

`<div class="share-button donate" id="donate-button"><a class="donate-button"  href="link to chained donate page" target="_blank">donate now</a></div>`

![Screen Shot campaign link](https://raw.githubusercontent.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/master/Screen%20Shot%20campaign%20link.jpg)


