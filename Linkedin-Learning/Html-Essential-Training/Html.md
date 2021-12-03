# web-html
# fundamentals from linked in learning
# the web is made up of (HTML , CSS , JAVA SCRIPT )
### HTML (HyperText Markup Language.):
marks up the content of a site. Basically it tells the user's computer what things are. 
HTML is what's called a declarative language. 
#### marks up :
which tells the browser what the text should look like, how its arranged , there can be  refferences
###  CSS (Cascading Style Sheets.):
provides visual styling and layout for everything on the web page.
### JavaScript is a programming language
that provides the ability to create more powerful interactivity. 
the reason it was invented. To provide a way for humanity to share content, even when our computers are different from each other.
### Element: opening tag: <--> + content + closing tag: </-->
HTML elements can be nested inside of each other. acually, entire HTML document is a whole bunch of HTML elements all nested inside of each other.
1- paragraph : <p> hello world </p>
2- headers  : <h1-h6> according to the size and importance </h1-h6>
3- bold : <b> it bold the text only </b> or <strong> it bold the text with a meaning of importance </strong>
4- italic : <i> it oblique the text only </i> or <em> it oblique the text with a meaning of importance </em>
5- lists 
(1) ordered lists : <ol> include items -> <li> </li> </ol> >>> with order 
(2) unolrdered lists  : <ul> include items -> <li> </li> </ul> >>> bullet list 
(3) describtion lists  : <dl> ininclude items -> <dt> these items include definetion items </dt> -> <dd>  </dd>  </dl>
6- quotes 
(1) inline quote : <p> bla <q> blablabla </q>  </p>           
(2) block quote : <blockquote> bla bla bla <cite>him</cite> </blockquote>
7- time (Date : YYYY-MM-DD): <time datetime = "2021-09-25"> sep 25 </time>
8- code : <code> print("hello world") </code>
9- line break : <p> my name is <br> omar nafea </p>           
10 - the same layout : <pre> |||__|||</pre>
11- subscipt : H<sub>2</sub>O    
12- superscript : 2<sup>2</sup> = 4
13- fine print : <small> © for 2019 </small>
### global attibute
its an attibute to the tag that provide more things to do to this tag 
(classes : it takes a name to modify it by this name on css or js )
(ID : like class but it can use one time and not best in css work)
(lang : spicify the language of this element)
(dir : spicify the direction of this element)
aria attribute is added to all HTML elements for clarification purpose (optimise accessibility)
HTML has entities to write these symbols (<>&) or non-breaking-space -> &nbsp;
### link 
by anchor element <a href="https://--.com">click here</a>
relative URL to call a file without https://
to make a navigation bar
<nav role="navigation" aria-label="main menu">
<ul><li><a></ul> </nav>
### image
<img src="" alt="" width="" height=""/>
#### image format
JPG : files, used mostly for photos, will show their pixels as you make them larger.
GIFs : are good for short animations, but get horribly pixelated when enlarged.
PNG : files work well for non-photographic images, but get pixelated when scaled up.
SVG : Scalable Vector Graphics can scale to massive sizes and still look neat, like they were built for it, complex photo.
#### Responsive images
follow html file
<!--   control attribute to has control on the media -->
<audio controls> 
  <!--   source of audio -->
  <source 
      src="http://example.com/birds.ogg" 
  		type="audio/ogg; codec=opus">
	<source 
      src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/birds.mp3" 
  		type="audio/mpeg">
  <!--   if the audio doesnt appear -->
  Sorry your browser doesn't not support audio.
  
</audio>
  
<video controls>
<!--   source of video -->
  <source src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/moonwalk.480p.vp9.webm" 
    type="video/webm">
  <source src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/moonwalk.480p.h264.mp4" 
    type="video/mp4">
  <!-- subtitles -->
  <track src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/moonwalk.vtt"
         kind="captions"
         label="English"
         srclang="en"
         default>
  
   <track src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/moonwalk.es-la.es.vtt"
         kind="subtitles"
         label="Español"
         srclang="es">
<!--   if the video doesnt appear -->
  <p>This would be a video of a moonwalk, if your device supported playing this video.</p>
</video>
<!--   to embed a video from youtube through share and embed -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Gr1XSyxZy0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
### important thigs in html file 
<!DOCTYPE html>
<html lang="en">
### head content
<meta charset="UTF-8"> (8-bit Unicode Transformation Format) 
<link href="main.css" rel="stylesheey">
<script></script>
### meta 
  <meta name="description" content="Free Web tutorials">
  <meta name="keywords" content="HTML, CSS, JavaScript">
  <meta name="author" content="John Doe">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="refresh" content="30">
  <meta http-equiv="application-name" content="name">
  <meta http-equiv="msapplication-titleimage" content="image">
  <meta http-equiv="themecolor" content="#44253">
### body content
main element is used once per page to wrap around the main content on that page.
header
footer
article
section
aside 
main
article
### to make a form
The action attribute specifies where to send the form-data when a form is submitted.
<form action="" method="POST">
    <label > name </label>
    <input name="name" type="text" >
    <button>sign up </button>
</form>
to connect label with input
1- <label for="niha"> name </label>
    <input id="niha" name="name" type="text" placeholder="enter name" required >
2-  <label > name <input type="text" name="name" > </label>
to make a button 
1-
<label for="submit"></label>
<input id="submit" value="submit" type="submit" name="data">
2- <button type="submit"> submit</button>
value attribute is for including such data in the form.
### types of forms
1- <textarea name="" id="" cols="30" rows="10"></textarea>
2- <input id="" type="radio" value="" name="" checked="">
3- <input id="" type="password" value="" name="" required>
<input type="button">
<input type="checkbox">
<input type="color">
<input type="date">
<input type="datetime-local">
<input type="email">
<input type="file" accept="image/*" multiple >
<input type="hidden">
<input type="image">
<input type="month">
<input type="number">
<input type="range">
<input type="reset">
<input type="search">
<input type="tel">
<input type="time">
<input type="url">
<input type="week">
### Attributes (Attribute - Value - Description)
accept - file_extension (audio/* ,video/* ,image/* ,media_type)
- Specifies a filter for what file types the user can pick from the file input dialog box (only for type="file")
alt - text - Specifies an alternate text for images (only for type="image")
autocomplete - on , off - Specifies whether an <input> element should have autocomplete enabled
autofocus - autofocus - Specifies that an <input> element should automatically get focus when the page loads
checked	- checked - Specifies that an <input> element should be pre-selected when the page loads (for type="checkbox" or type="radio")
dirname - inputname.dir - Specifies that the text direction will be submitted
disabled - disabled - Specifies that an <input> element should be disabled
form - form_id	- Specifies the form the <input> element belongs to
formtarget - _blank _self _parent _top framename
- Specifies where to display the response that is received after submitting the form(for type="submit" and type="image")
height - pixels	- Specifies the height of an <input> element (only for type="image")
max - number date - Specifies the maximum value for an <input> element
maxlength - number - Specifies the maximum number of characters allowed in an <input> element
min - number date - Specifies a minimum value for an <input> element	
minlength - number - Specifies the minimum number of characters required in an <input> element
multiple - multiple -Specifies that a user can enter more than one value in an <input> element
name - text - Specifies the name of an <input> element
pattern	- regexp - Specifies a regular expression that an <input> element's value is checked against
placeholder - text - Specifies a short hint that describes the expected value of an <input> element
readonly - readonly - Specifies that an input field is read-only
required - required - Specifies that an input field must be filled out before submitting the form
size - number - Specifies the width, in characters, of an <input> element
src - URL - Specifies the URL of the image to use as a submit button (only for type="image")
step - number any - Specifies the interval between legal numbers in an input field
value - text - Specifies the value of an <input> element
 
width - pixels - Specifies the width of an <input> element (only for type="image")
### table
<table border="2" width="400">
                    <caption> The main branches of mathematics </caption>
                    <thead>
                        <tr>
                            <th>major</th>
                            <th colspan="2">subjects</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>algebra</td>
                            <td>equations</td>
                            <td>functions</td>
                        </tr>
                        <tr>
                            <th>geometry</th>
                            <td>shapes</td>
                            <td>trigonometry</td>
                        </tr>
                        <tr>
                            <td>calculus</td>
                            <td rowspan="2"> differentiation</td>
                            <td rowspan="2">integration</td>
                        </tr>

                        <tr>
                            <td>focus on</td>
                        </tr>
                    </tbody>
                </table>
