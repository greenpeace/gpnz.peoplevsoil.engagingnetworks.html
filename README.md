# gpnz.peoplevsoil.engagingnetworks.html
Header / Footer template

## EN page builder instructions

*Note: responsiveness is not fluid. When page loads the template code will apply style based on the the screen size.*

### Setup

Create a template

Paste Header / Footer code

Create a new petition 

This is what you should see

![Screen Shot new petition](
https://github.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/blob/screen-shots/Screen%20Shot%20new%20petition.png?raw=true)

## Page 1

#### Structure
1. Advanced row - fixed header - left column
2. Single column row - right column form (added by default when new page created)
3. Advanced row - footer

### 1. Add row Custom Layout 1 column (remove column 2)

* GP logo: add text block - paste HTML in source editor
 
 `<p><img id="gp-logo-header" src="https://www.peoplevsoil.org/assets/peoplevsoil2018/img/greenpeace-black.svg" /></p>`

edit text block style: Custom class names: `header-sticky`

* PVO logo: add text block - paste HTML in source editor

`<p><img id="pvo-logo" src="https://www.peoplevsoil.org/assets/peoplevsoil2018/img/peoplevoil.svg" /></p>`

edit text block style: Custom class names: `pvo-logo-heading`

* Heading: add text block - paste HTML in source editor

`<h1 id="mainHeading" style="color: #FFFFFF; box-sizing: inherit; font-size: 78px; margin: 40px 0px 21.375px; font-family: Anton, Helvetica, Arial, serif; line-height: 78px;">LET&#39;S<br style="box-sizing: inherit;">MAKE<br />
OIL HISTORY</h1>`

add paragraph text

![Screen Shot advanced row 1](https://raw.githubusercontent.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/screen-shots/Screen-Shot-advanced-row-1.png)

![Screen Shot PVO logo position](https://raw.githubusercontent.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/screen-shots/Screen-Shot-PVO-logo-position.png)

### 2. right side content (row One column was already added by default)

* add text component above form: 

add class `copy-toggle` - to enable show/hide
  
* add form blocks for each field 
  
add class 'form-toggle' to name & phone fields - to enable show/hide

### 3. Add row Custom Layout 1 column (remove column 2)
### Custom class names `footer-custom`

* add code block: paste HTML

`<div id="footer-logos">`

`<img class="footer-logos-left" height="25" src="https://www.peoplevsoil.org/assets/peoplevsoil2018/img/peoplevoil.svg" />`
	
	`<ul class="footer-social-media">`
	
		'<li><a href="https://twitter.com/"><i class="fa fa-twitter fa-2x"></i></a></li>`
		'<li><a href="https://www.facebook.com/"><i class="fa fa-facebook-official fa-2x"></i></a></li>`
		'<li><a href="https://www.youtube.com/"><i class="fa fa-youtube-play fa-2x"></i></a></li>`
		'<li><a href="https://www.instagram.com/"><i class="fa fa-instagram fa-2x"></i></a></li>`
	
	`</ul>`

	'<img class="footer-logos-right" height="25" src="https://www.peoplevsoil.org/assets/peoplevsoil2018/img/greenpeace-black.svg" />'
	
`</div>`

* add text block paste HTML in source editor

`<p style="text-align: center;"><span style="color: rgb(176, 176, 176); font-family: Amiko, Helvetica, Arial, serif; font-size: 12.8px; letter-spacing: -0.3px; text-align: center;">&copy;2019 - Greenpeace | All rights reserved</span></p>`

![Screen Shot footer logos](https://raw.githubusercontent.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/screen-shots/Screen%20Shot%20footer%20logos.png)

![Screen Shot footer advanced row](
https://raw.githubusercontent.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/screen-shots/Screen%20Shot%20footer%20advanced%20row.png)

## Page 2

### Add row One column

* Thank you: add text block

* Share buttons: add from Social Details tools (sidebar)

* Donate button: add text block paste HTML in source editor (select text then select  donate campaign link from text format buttons to chain campaign)

`<div class="share-button donate" id="donate-button"><a class="donate-button"  href="link to chained donate page" target="_blank">donate now</a></div>`

![Screen Shot campaign link](https://raw.githubusercontent.com/greenpeace/gpnz.peoplevsoil.engagingnetworks.html/screen-shots/Screen%20Shot%20campaign%20link.jpg)


