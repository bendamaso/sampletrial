## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/bendamaso/sampletrial/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/bendamaso/sampletrial/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


<script type="text/javascript">

/***********************************************
* Conveyor belt slideshow script- © Dynamic Drive DHTML code library (www.dynamicdrive.com)
* This notice MUST stay intact for legal use
* Visit Dynamic Drive at http://www.dynamicdrive.com/ for full source code
***********************************************/


//Specify the slider's width (in pixels)
var sliderwidth="730px"
//Specify the slider's height
var sliderheight="180px"
//Specify the slider's slide speed (larger is faster 1-10)
var slidespeed=2
//configure background color:
slidebgcolor="#FFFFFF"

//Specify the slider's images
var leftrightslide=new Array()
var finalslide=''
leftrightslide[0]='<a href="http://digitalshorts.weebly.com/animated-figures.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/adventure.png" border=1></a>'
leftrightslide[1]='<a href="http://digitalshorts.weebly.com/hollys.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/prank.png" border=1></a>'
leftrightslide[2]='<a href="http://digitalshorts.weebly.com/joel.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/pivot.png" border=1></a>'
leftrightslide[3]='<a href="http://digitalshorts.weebly.com/miscellaneous-works.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/works1.png" border=1></a>'
leftrightslide[4]='<a href="http://digitalshorts.weebly.com/stop-motion-animation.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/normalday.png" border=1></a>'
leftrightslide[5]='<a href="http://digitalshorts.weebly.com/tim-anna-pieter--luan.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/walk.png" border=1></a>'
leftrightslide[6]='<a href="http://digitalshorts.weebly.com/sofia-aidan-n--jasper.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/paintball.png" border=1></a>'
leftrightslide[7]='<a href="http://digitalshorts.weebly.com/miscellaneous-works1.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/works2.png" border=1></a>'
leftrightslide[8]='<a href="http://digitalshorts.weebly.com/photo-narration.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/themepark.png" border=1></a>'
leftrightslide[9]='<a href="http://digitalshorts.weebly.com/joeniel.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/dive.png" border=1></a>'
leftrightslide[10]='<a href="http://digitalshorts.weebly.com/daniela.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/sleep.png" border=1></a>'
leftrightslide[11]='<a href="http://digitalshorts.weebly.com/aidan-h.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/mask.png" border=1></a>'
leftrightslide[12]='<a href="http://digitalshorts.weebly.com/diego.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/clouds.png" border=1></a>'
leftrightslide[13]='<a href="http://digitalshorts.weebly.com/bernardo.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/panic.png" border=1></a>'
leftrightslide[14]='<a href="http://digitalshorts.weebly.com/yashal.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/hacker.png" border=1></a>'
leftrightslide[15]='<a href="http://digitalshorts.weebly.com/kenza.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/lost.png" border=1></a>'

leftrightslide[16]='<a href="http://digitalshorts.weebly.com/miscellaneous-works2.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/works3.png" border=1></a>'
leftrightslide[17]='<a href="http://digitalshorts.weebly.com/comic-strips.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/steven.png" border=1></a>'
leftrightslide[18]='<a href="http://digitalshorts.weebly.com/melissa.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/secret.png" border=1></a>'
leftrightslide[19]='<a href="http://digitalshorts.weebly.com/brandon.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/penelope.png" border=1></a>'
leftrightslide[20]='<a href="http://digitalshorts.weebly.com/miscellaneous.html"><img src="http://i1298.photobucket.com/albums/ag57/aismtech/works4.png" border=1></a>'
//Specify gap between each image (use HTML):
var imagegap=" "

//Specify pixels gap between each slideshow rotation (use integer):
var slideshowgap=5


////NO NEED TO EDIT BELOW THIS LINE////////////

var copyspeed=slidespeed
leftrightslide='<nobr>'+leftrightslide.join(imagegap)+'</nobr>'
var iedom=document.all||document.getElementById
if (iedom)
document.write('<span id="temp" style="visibility:hidden;position:absolute;top:-100px;left:-9000px">'+leftrightslide+'</span>')
var actualwidth=''
var cross_slide, ns_slide

function fillup(){
if (iedom){
cross_slide=document.getElementById? document.getElementById("test2") : document.all.test2
cross_slide2=document.getElementById? document.getElementById("test3") : document.all.test3
cross_slide.innerHTML=cross_slide2.innerHTML=leftrightslide
actualwidth=document.all? cross_slide.offsetWidth : document.getElementById("temp").offsetWidth
cross_slide2.style.left=actualwidth+slideshowgap+"px"
}
else if (document.layers){
ns_slide=document.ns_slidemenu.document.ns_slidemenu2
ns_slide2=document.ns_slidemenu.document.ns_slidemenu3
ns_slide.document.write(leftrightslide)
ns_slide.document.close()
actualwidth=ns_slide.document.width
ns_slide2.left=actualwidth+slideshowgap
ns_slide2.document.write(leftrightslide)
ns_slide2.document.close()
}
lefttime=setInterval("slideleft()",30)
}
window.onload=fillup

function slideleft(){
if (iedom){
if (parseInt(cross_slide.style.left)>(actualwidth*(-1)+8))
cross_slide.style.left=parseInt(cross_slide.style.left)-copyspeed+"px"
else
cross_slide.style.left=parseInt(cross_slide2.style.left)+actualwidth+slideshowgap+"px"

if (parseInt(cross_slide2.style.left)>(actualwidth*(-1)+8))
cross_slide2.style.left=parseInt(cross_slide2.style.left)-copyspeed+"px"
else
cross_slide2.style.left=parseInt(cross_slide.style.left)+actualwidth+slideshowgap+"px"

}
else if (document.layers){
if (ns_slide.left>(actualwidth*(-1)+8))
ns_slide.left-=copyspeed
else
ns_slide.left=ns_slide2.left+actualwidth+slideshowgap

if (ns_slide2.left>(actualwidth*(-1)+8))
ns_slide2.left-=copyspeed
else
ns_slide2.left=ns_slide.left+actualwidth+slideshowgap
}
}


if (iedom||document.layers){
with (document){
document.write('<table border="0" cellspacing="0" cellpadding="0"><td>')
if (iedom){
write('<div style="position:relative;width:'+sliderwidth+';height:'+sliderheight+';overflow:hidden">')
write('<div style="position:absolute;width:'+sliderwidth+';height:'+sliderheight+';background-color:'+slidebgcolor+'" onMouseover="copyspeed=0" onMouseout="copyspeed=slidespeed">')
write('<div id="test2" style="position:absolute;left:0px;top:0px"></div>')
write('<div id="test3" style="position:absolute;left:-1000px;top:0px"></div>')
write('</div></div>')
}
else if (document.layers){
write('<ilayer width='+sliderwidth+' height='+sliderheight+' name="ns_slidemenu" bgColor='+slidebgcolor+'>')
write('<layer name="ns_slidemenu2" left=0 top=0 onMouseover="copyspeed=0" onMouseout="copyspeed=slidespeed"></layer>')
write('<layer name="ns_slidemenu3" left=0 top=0 onMouseover="copyspeed=0" onMouseout="copyspeed=slidespeed"></layer>')
write('</ilayer>')
}
document.write('</td></table>')
}
}
</script>
