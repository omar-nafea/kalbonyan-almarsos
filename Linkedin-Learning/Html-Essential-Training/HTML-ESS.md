# web-html
## the web is made up of (HTML , CSS , JAVA SCRIPT )
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
___
### Element: opening tag: ```<-->``` + content + closing tag: ```</-->```
HTML elements can be nested inside of each other. acually, entire HTML document is a whole bunch of HTML elements all nested inside of each other.
* paragraph : ```<p> hello world </p>```
* headers  :``` <h1> according to the size and importance </h1>``` or ```<h6> according to the size and importance </h6>```
* bold : ```<b> it bold the text only </b>``` or ```<strong> it bold the text with a meaning of importance </strong>```
* italic : ```<i> it oblique the text only </i>``` or ```<em> it oblique the text with a meaning of importance </em>```
* lists 
	* ordered lists : ```<ol> include items -> <li> </li> </ol> >>> with order ```
	* unolrdered lists  : ```<ul> include items -> <li> </li> </ul> >>> bullet list ```
	* describtion lists : 
```html
<dl>
  <dt>Coffee</dt>
  <dd>Black hot drink</dd>
  <dt>Milk</dt>
  <dd>White cold drink</dd>
</dl>
```
* quotes 
	* inline quote : ```<p> bla <q> blablabla </q>  </p>  ```         
	* block quote : ```<blockquote> bla bla bla <cite>him</cite> </blockquote>```
* time (Date : YYYY-MM-DD): ```<time datetime = "2021-09-25"> sep 25 </time>```
* code : ```<code> print("hello world") </code>```
* line break : ```<p> my name is <br> omar nafea </p> ```         
* the same layout : ```<pre> yy  oo po  </pre>```
* subscipt : ```H<sub>2</sub>O = ```  H<sub>2</sub>O  
* superscript : ```2<sup>2</sup> = ``` 2<sup>2</sup>
* fine print : ```© for <small>  2019 </small>```© for <small>  2019 </small>
___
### global attibute
its an attibute to the tag that provide more things to do to this tag 
- (classes : it takes a name to modify it by this name on css or js )
- (ID : like class but it can use one time and not best in css work)
- (lang : spicify the language of this element)
- (dir : spicify the direction of this element)
- aria attribute is added to all HTML elements for clarification purpose (optimise accessibility)  
**HTML has entities to write these symbols (<>&) or non-breaking-space -> &nbsp;**
___
### link 
by anchor element ```<a href="https://--.com">click here</a>```
relative URL to call a file on your pc without https://
to make a navigation bar ```<nav role="navigation" aria-label="main menu"><ul><li><a></ul> </nav>```

### image
```html
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
```
#### image format
- JPG : files, used mostly for photos, will show their pixels as you make them larger.
- GIFs : are good for short animations, but get horribly pixelated when enlarged.
- PNG : files work well for non-photographic images, but get pixelated when scaled up.
- SVG : Scalable Vector Graphics can scale to massive sizes and still look neat, like they were built for it, complex photo.
#### Responsive images
[see Responsive images](Responsive%20images.HTML)

___
#### Audio settings
```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
```
___
#### Video settings
```html
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
```
**to embed a video from youtube through share and embed**
```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Gr1XSyxZy0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!-- from youtube , share , Embed Video -->
```
### important thigs in the beginning of html file 
```html
<!DOCTYPE html>
<html lang="en">
### head content
<meta charset="UTF-8"> (8-bit Unicode Transformation Format) 
<link href="main.css" rel="stylesheey">
<script></script>
```
### meta 
```html
<meta name="description" content="Free Web tutorials">
<meta name="keywords" content="HTML, CSS, JavaScript">
<meta name="author" content="John Doe">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="refresh" content="30">
<meta http-equiv="application-name" content="name">
<meta http-equiv="msapplication-titleimage" content="image">
<meta http-equiv="themecolor" content="#44253">
```
### body content
<!-- main element is used once per page to wrap around the main content on that page. -->
```html
<header></header>
<main>
<article>
<section></section>
</article>
<aside></aside>
</main>
<footer></footer>
```
___
### to make a form
The action attribute specifies where to send the form-data when a form is submitted.
```html
<form action="" method="POST">
    <label > name </label>
    <input name="name" type="text" >
    <button>sign up </button>
</form>
```
___
**to connect label with input**
```html
 <label for="niha"> name </label>
    <input id="niha" name="name" type="text" placeholder="enter name" required >
```
```html
 <label > name <input type="text" name="name" > </label>
``` 
___
**to make a button** 
```html
<label for="submit"></label>
<input id="submit" value="submit" type="submit" name="data">
```
```html
<button type="submit"> submit</button>
```
___
*value attribute is for including such data in the form.*
### types of forms

```html
<textarea name="" id="" cols="30" rows="10"></textarea>
<input id="" type="radio" value="" name="" checked="">
<input id="" type="password" value="" name="" required>
<input type="button"> <input type="checkbox"> 
<input type="color">
```
(**date** ,**email** ,**file** ,**hidden** ,**image** ,**month** ,**number** ,**range** ,**reset** ,**search** ,**url** ,**time**)
___
### Attributes
| Attributes | Value |
|------------|-------|
| accept |(image,media)
| alt | text |
| autocomplete | on , off |
|autofocus | autofocus | 
|checked	| checked |
|disabled | disabled |
|height | pixels	|
|max | number date |
|maxlength | number |
|min | number date |
|minlength | number |
|multiple | multiple |
|name | text |
|placeholder | text |
|readonly | readonly |
|required | required |
|size | number |
|src | URL |
|step | number any |
|value | text |
|width | pixels |
___
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
          <td > differentiation</td>
          <td >integration</td>
      </tr>
  </tbody>  
</table>

```
