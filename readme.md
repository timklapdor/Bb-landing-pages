# Updates to Work

Now available in [release notes](release-notes.md)

# Using the Elements

## 1. Start with the container DIV

```html
<div class="content" style="font-size: 17px; color: #1A1A1A; text-align: left; width: 85%; margin: 0 auto; padding: 1em 0 0; border: 0;" align="left"></div>
```

## 2.  Add in your headings

Choose from Heading 1 

```html
<h1 style="font-size: 68px; line-height: 1em; font-family: sans-serif; font-weight: 400; color: #E31B23; margin: 0px 0px 0.37em; padding: 0px 10px; clear: both;">Change this Text</h1>
```

Or Heading 2

```html
<h2 style="font-size: 42px; line-height: 1.2em; font-family: sans-serif; font-weight: normal; margin: 0px 0px 0.5em; padding: 0px 10px; border-color: #F47B20; border-style: solid; border-width: 0px 0px 2px; clear: both;">Heading Two</h2>
```

Or Heading 3

```html
<h3 style="font-size: 28px; line-height: 1.4em; font-family: sans-serif; text-transform: uppercase; margin: 0px 0px 0.5em; padding: 0px 10px; clear: both;">Heading Three</h3>
```

## 3. Breaking up content

To break up the page or create a new section use the Heading 4's

```html
<h4 style="font-family: sans-serif; text-transform: uppercase; font-weight: 600; margin: 12px 0px; padding: 0.5em 10px; clear: both;">A plain fourth level heading</h4>
```

You can choose from a variety of colours including:

Red

```html
<h4 class="red" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #E31B23; margin: 12px 0px; padding: 0.5em 10px; clear: both;">A Red fourth level heading</h4>
```

Blue

```html
<h4 class="blue" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #00AFD8; margin: 12px 0px; padding: 0.5em 10px; clear: both;">A Blue fourth level heading</h4>
```

Green

```html
<h4 class="green" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #7AB800; margin: 12px 0px; padding: 0.5em 10px; clear: both;">A fourth level heading</h4>
```

Grey

```html
<h4 class="grey" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #666666; margin: 12px 0px; padding: 0.5em 10px; clear: both;">A fourth level heading</h4>  
```

Orange

```html
<h4 class="orange" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #F47B20; margin: 12px 0px; padding: 0.5em 10px; clear: both;">A fourth level heading</h4>
```

Purple

```html
<h4 class="purple" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #6E267B; margin: 12px 0px; padding: 0.5em 10px; clear: both;">A fourth level heading</h4>
```

Or use a Heading 5

```html
<h5 style="font-size: 1.1em; font-family: sans-serif; font-style: normal; font-weight: 600; margin: 0px 0px 10px; padding: 0.5em 10px; clear: both;">A fifth level heading</h5>
```

## 4. Text Types

The intro text is good for a lead content like an introductory paragraph of text 

```html
<p class="intro" style="font-family: sans-serif; color: word-wrap: break-word; font-size: 20px; line-height: 1.3em; margin: 0px 0px 1.5em; padding: 0 0 0.5em;">An introductory paragraph is a great way to summarise the content before the reader really digs into the detail of your story.</p>
```

The blockquote is perfect to highlight a small section of text - like a pull quote often used in magazines.

```html
<blockquote class="pull-quote" style="text-align: center; border-top-style: solid; border-bottom-style: solid; color: #F47B20; font-style: normal; font-variant: normal; font-weight: 400; font-size: 27px; line-height: 1.3em; font-family: serif; margin: 1.2em 0; padding: 1em; border-color: #CCCCCC; border-width: 1px 0;" align="center">There are dozens of simple, fascinating experiments that may be performed with this kind of electricity on Snow 22nd October 2014</blockquote>
```

You can also add in a byline or caption using this style.

```html
<p class="byline" style="font-family: sans-serif; color: #666666; text-align: center; word-wrap: break-word; font-style: italic; font-weight: 400; font-size: 16px; line-height: 1.2em; font-family: serif; margin: 0px 0px 1.5em; padding: 0 0 0.5em; border: 0;" align="center">Developed by Christian Surname</p>
```

If you have a quote, highlight it with this style

```html
<p class="quote" style="color: #666666; text-align: left; border-left-style: solid; word-wrap: break-word; font-style: italic; font-weight: 400; font-size: 27px; line-height: 1.3em; font-family: serif; margin: 1.2em 0px; padding: 0.5em; border-color: #CCCCCC; border-width: 0 0 0 8px;" align="left">“You should be able to see, hear, and feel these sparks, especially when the air is dry and you are in a dark room.”</p>
```

There's also unordered lists that are "dot-points"

```html
<ul style="font-family: sans-serif; list-style-type: square; margin: 10px 20px; padding: 10px 20px;">
<li>The first item in an unordered list</li>
<li>Second item right here</li>
<li>This is the third item in the list</li>
</ul>
```
    
As well as ordered lists that appear as numbered lists

```html
<ol style="font-family: sans-serif; list-style-type: decimal; margin: 10px 20px; padding: 10px 20px;">
<li>Item number one of three</li>
<li>The second place item</li>
<li>Last but not least in an ordered list</li>
</ol>
```

## 5. Images

The Hero image will be full width - but will shrink to fit the width of the content window (set at 85%)

```html
<img class="hero" src="replace.this.text.with.the.image.url" style="max-width: 100%; display: block; height: auto;">
```

You can also "float" images within the text on the page:

Left 50%

```html
<img class="img-float-left-50" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="width: 50%; display: block; height: auto; float:left;">    
```

Right 50%

```html
<img class="img-float-right-50" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="width: 50%; display: block; height: auto; float:right;">
```

Left 30%

```html
<img class="img-float-left-30" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="width: 30%; display: block; height: auto; float:left;">    
```

Right 30%

```html
<img class="img-float-right-30" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="width: 30%; display: block; height: auto; float:right;">     
```

You can also use the following snippets to resize images inside of columns so they are not 100% width. This means you can make image fit better if they are different aspet ratios. Images will be centred within the DIV they are contained in.

80% Width
```html
<img class="ind-80" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="max-width: 80%; display: block; height: auto; margin: auto; padding: 10px;">
```

70% Width
```html
<img class="ind-70" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="max-width: 70%; display: block; height: auto; margin: auto; padding: 10px;">
```

60% Width
```html
<img class="ind-60" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="max-width: 60%; display: block; height: auto; margin: auto; padding: 10px;">
```

50% Width
```html
<img class="ind-50" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="max-width: 50%; display: block; height: auto; margin: auto; padding: 10px;"> 
```

40% Width
```html
<img class="ind-40" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="max-width: 40%; display: block; height: auto; margin: auto; padding: 10px;">   
```


You can set up a three column image galley using this code. Simply swap out the image src URLs with your image. Make sure that images have the same height and width for the best effect.

```html
<div class="three-col-gallery" align="center">
      <img class="three-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="width: 31%; float: left; max-width: 100%; margin: 1%;">
      <img class="three-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="width: 31%; float: left; max-width: 100%; margin: 1%;">
      <img class="three-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="width: 31%; float: left; max-width: 100%; margin: 1%;">
</div>
```

Code for a four column image gallery

```html
<div class="four-col-gallery" align="center">  
     <img class="four-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="max-width: 100%; width: 22.7%; margin: 1%;" align="left">
     <img class="four-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="max-width: 100%; width: 22.7%; margin: 1%;" align="left">
     <img class="four-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="max-width: 100%; width: 22.7%; margin: 1%;" align="left">
     <img class="four-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="max-width: 100%; width: 22.7%; margin: 1%;" align="left">
</div> 
```

If you have an odd number of images you can use this code that includes an "offset" DIV to space the odd number. 

```html
<div class="five-col-gallery" align="center">
      <img class="three-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="width: 31%; float: left; max-width: 100%; margin: 1%;">
      <img class="three-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="width: 31%; float: left; max-width: 100%; margin: 1%;">
      <img class="three-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="width: 31%; float: left; max-width: 100%; margin: 1%;">
    <div class="offset-third" style="float: left; width: 16.65%; text-align: left; margin: 0; padding-right: 10px; -webkit-box-sizing: border-box;
	 -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible;">&nbsp;</div>
      <img class="three-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="width: 31%; float: left; max-width: 100%; margin: 1%;">
      <img class="three-col-img" src="https://dl.dropboxusercontent.com/u/2706309/Images/uImagine-sq.png" style="width: 31%; float: left; max-width: 100%; margin: 1%;">                             
</div> 
```

## 6. Videos

The code below will create a full width responsive YouTube video. To use it swap out the ```src=""``` address in the iFrame code with the src for your video. To find this in YouTube click on **Share** tab, **Embed** and copy the ```src""`` code there

![](https://dl.dropboxusercontent.com/u/2706309/Images/youtube-src.png)

```html
<div class="video-container" style="position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden;"><iframe width="560" height="315" src="https://www.youtube.com/embed/977AYjapws0?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
</div>
```

You can also float the videos at 50% of the width to the left

```html
<div class="half" style="display: block; float: left; width: 50%; overflow: visible; margin: 0; padding: 10px;">
    <div class="video-container" style="position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden;"><iframe width="560" height="315" src="https://www.youtube.com/embed/977AYjapws0?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>
    <p class="caption" style="font-family: sans-serif; color: #666666; text-align: center; word-wrap: break-word; font-style: italic; font-weight: 400; font-size: 1em; line-height: 1.2em; font-family: serif; margin: 0px;" align="center">Developed by Christian Surname</p>
</div> 
```

Or to the right

```html
<div class="half" style="display: block; float: right; width: 50%; overflow: visible; margin: 0; padding: 10px; border: 0;">
    <div class="video-container" style="position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden;"><iframe width="560" height="315" src="https://www.youtube.com/embed/977AYjapws0?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>
    <p class="caption" style="font-family: sans-serif; color: #666666; text-align: center; word-wrap: break-word; font-style: italic; font-weight: 400; font-size: 1em; line-height: 1.2em; font-family: serif; margin: 0px;" align="center">Developed by Christian Surname</p>
</div>
```

Videos can also be placed in thirds based columns - so you can provide a description or other information next to the video. For a large video on the right:

```html
<div class="thirds">
      <div class="third" style="display: block; float: left; width: 33.33%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 10px 0 0; border: 0;">
        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em;">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
      <div class="two-third" style="float: left; width: 66.66%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; border-left-color: #eee; border-left-style: solid; padding: 0 10px; border-width: 0 0 0 1px;">
          <div class="video-container" style="position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden;"><iframe width="560" height="315" src="https://www.youtube.com/embed/977AYjapws0?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>
        <p class="byline" style="font-family: sans-serif; color: #666666; text-align: center; word-wrap: break-word; font-style: italic; font-weight: 400; font-size: 16px; line-height: 1.2em; font-family: serif; margin: 0px 0px 1.5em; padding: 0 0 0.5em; border: 0;" align="center">Developed by Christian Surname</p> 
      </div>
</div>  
```

Or small on the left

```html
<div class="thirds">
      <div class="third" style="display: block; float: left; width: 33.33%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 10px 0 0; border: 0;">
        <div class="video-container" style="position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden;"><iframe width="560" height="315" src="https://www.youtube.com/embed/977AYjapws0?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>    
        <p class="byline" style="font-family: sans-serif; color: #666666; text-align: center; word-wrap: break-word; font-style: italic; font-weight: 400; font-size: 16px; line-height: 1.2em; font-family: serif; margin: 0px 0px 1.5em; padding: 0 0 0.5em; border: 0;" align="center">Developed by Christian Surname</p>
      </div>
      <div class="two-third" style="float: left; width: 66.66%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; border-left-color: #eee; border-left-style: solid; padding: 0 10px; border-width: 0 0 0 1px;">
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em;">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
</div>  
```
## 7. Clear

Some styles may "leak" into the next section. If that happens try inserting this line break:

```html
<p style="clear:both">&nbsp;</p>
```

## 8. Profiles

Single Profile:

```html
<div class="single-profile" style="font-size: normal; line-height: normal; font-style: normal; font-weight: normal; font-variant: normal; vertical-align: baseline; width: auto; text-align: left; margin: 0 auto; padding: 0; border: 0; clear:both" align="left">

    <img class="profile-left" src="http://timklapdor.github.io/Bb-landing-pages/assets/squareprofile.jpg" style="width: 200px; -webkit-box-shadow: 10px 10px 15px -4px rgba(41,41,41,0.35); -moz-box-shadow: 10px 10px 15px -4px rgba(41,41,41,0.35); box-shadow: 10px 10px 15px -4px rgba(41,41,41,0.35); margin: -10px 15px 15px 0; padding: 0; border: 3px solid #fff;" align="left">

    <h4 class="blue" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #00AFD8; margin: 12px 0px 12px 0px; padding: 0.5em 10px;">Christian Surname</h4>

    <h6 style="font-family: sans-serif; font-size: 1.2em;  font-style: italic; font-weight: 400; font-variant: normal; vertical-align: baseline; margin: 0; padding: 0 0 0 10px;">Job Title</h6>

    <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0.2em 0 0em 0"><span style="font-weight: bold;">Contact:</span> email@some.com</p>

    <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0.2em 0 0em 0"><span style="font-weight: bold;">Twitter:</span> @someone</p>
    
    <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0.5em 0 0.5em;">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>

</div>
```

Larger Single Profile:

```html
<div class="larger-profile" style="clear:both;">

    <div class="third" style="display: block; float: left; width: 33.33%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 10px 0 0;">

        <img src="http://timklapdor.github.io/Bb-landing-pages/assets/squareprofile.jpg" style="max-width: 100%;">


        <h4 style="font-family: sans-serif; text-transform: uppercase; font-weight: 600; margin: 12px 0px 0px 0px; padding: 0.5em 10px;">Christian Surname</h4>

        <h6 style="font-family: sans-serif; font-size: 1.2em;  font-style: italic; font-weight: 400; font-variant: normal; margin: 0; padding: 0 0 0.5em 0.5em;">Job Title</h6>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold;">Contact:</span> email@some.com</p>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold; ">Twitter:</span> @someone</p>
   
    </div>
    
    <div class="two-third" style="display: block; float: left; width: 66.66%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; border-left-color: #eee; border-left-style: solid; margin: 0; padding: 0 10px; border-width: 0 0 0 1px;">

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em;">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
        
        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em;">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
  
        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em;">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
  
        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em;">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
</div>
</div> 
```

Or two side by side

```html
<div class="halves" style="clear:both;">
      <div class="half" style="display: block; float: left; width: 50%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; border-left-color: #eee; border-left-style: solid; margin: 0; padding: 0 5px 10 0; border-width: 0 1px 0 0;">
        
        <h4 class="blue" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #00AFD8; margin: 12px 0px 0px 0px; padding: 0.5em 10px;">Christian Surname</h4>
          
        <img src="http://timklapdor.github.io/Bb-landing-pages/assets/squareprofile.jpg" style="max-width: 70%; display: block; height: auto; margin: auto; padding: 10px;">

        <h6 style="font-family: sans-serif; font-size: 1.2em;  font-style: italic; font-weight: 400; font-variant: normal; margin: 0; padding: 0.5em 0 0 0.5em;">Job Title</h6>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold;">Contact:</span> email@some.com</p>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold; ">Twitter:</span> @someone</p>
      </div>
      <div class="half" style="display: block; float: left; width: 50%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; border-left-color: #eee; border-left-style: solid; margin: 0; padding: 0 0 10px 5px; border-width: 0 0 0 1px;">
        
        <h4 class="blue" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #00AFD8; margin: 12px 0px 0px 0px; padding: 0.5em 10px;">Christian Surname</h4>
          
        <img src="http://timklapdor.github.io/Bb-landing-pages/assets/squareprofile.jpg" style="max-width: 70%; display: block; height: auto; margin: auto; padding: 10px;">

        <h6 style="font-family: sans-serif; font-size: 1.2em;  font-style: italic; font-weight: 400; font-variant: normal; margin: 0; padding: 0.5em 0 0 0.5em;">Job Title</h6>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold;">Contact:</span> email@some.com</p>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold; ">Twitter:</span> @someone</p>
          
      </div>

</div> 
```

Or three!

```html
<div class="third" style="text-align: center;">
      <div class="third" style="display: block; float: left; width: 33.33%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 10px 10px 0; border: 0;">
        
        <h4 class="blue" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #00AFD8; margin: 12px 0px; padding: 0.5em 10px;">Christian Surname</h4>
          
        <img src="http://timklapdor.github.io/Bb-landing-pages/assets/squareprofile.jpg" style="max-width: 70%; display: block; height: auto; margin: auto;">

        <h6 style="font-family: sans-serif; font-size: 1.2em;  font-style: italic; font-weight: 400; font-variant: normal; margin: 0; padding: 0.5em 0 0 0.5em;">Job Title</h6>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold;">Contact:</span> email@some.com</p>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold; ">Twitter:</span> @someone</p>
      </div>
      <div class="third" style="display: block; float: left; width: 33.33%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 10px 10px 0; border: 0;">
        
        <h4 class="blue" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #00AFD8; margin: 12px 0px; padding: 0.5em 10px;">Christian Surname</h4>
          
        <img src="http://timklapdor.github.io/Bb-landing-pages/assets/squareprofile.jpg" style="max-width: 70%; display: block; height: auto; margin: auto;">

        <h6 style="font-family: sans-serif; font-size: 1.2em;  font-style: italic; font-weight: 400; font-variant: normal; margin: 0; padding: 0.5em 0 0 0.5em;">Job Title</h6>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold;">Contact:</span> email@some.com</p>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold; ">Twitter:</span> @someone</p>
          
      </div>
        
      <div class="third" style="display: block; float: left; width: 33.33%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 10px 10px 0; border: 0;">
        
        <h4 class="blue" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #00AFD8; margin: 12px 0px; padding: 0.5em 10px;">Christian Surname</h4>
          
        <img src="http://timklapdor.github.io/Bb-landing-pages/assets/squareprofile.jpg" style="max-width: 70%; display: block; height: auto; margin: auto;">

        <h6 style="font-family: sans-serif; font-size: 1.2em;  font-style: italic; font-weight: 400; font-variant: normal; margin: 0; padding: 0.5em 0 0 0.5em;">Job Title</h6>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold;">Contact:</span> email@some.com</p>

        <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0 0.5em;"><span style="font-weight: bold; ">Twitter:</span> @someone</p>
          
      </div>
</div>
```

## Columns

The code below provides a number of premade column and content configurations:

Halves - Heading & Text

```html
<div class="halves" style="clear:both;">
      <div class="two-third" style="float: left; width: 50%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; padding: 0px 5px 0 0;">
          <h4 class="green" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #7AB800; margin: 12px 0px; padding: 0.5em 10px;">A fourth level heading</h4>
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em; line-height: 1.3em">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
      <div class="third" style="display: block; float: left; width: 50%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 0 0 5px; border-left: 1px solid #eee;">
        <h4 class="green" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #7AB800; margin: 12px 0px; padding: 0.5em 10px;">A fourth level heading</h4>
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em; line-height: 1.3em">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
</div>
```

Halves - Image Left + Heading & Text

```html
<div class="halves" style="clear:both;">
      <div class="two-third" style="float: left; width: 50%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; padding: 0px 5px 0 0;">
          <img class="ind-80" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="max-width: 80%; display: block; height: auto; margin: auto; padding: 10px;">    

      </div>
      <div class="third" style="display: block; float: left; width: 50%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 0 0 5px; border-left: 1px solid #eee;">
        <h4 class="green" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #7AB800; margin: 12px 0px; padding: 0.5em 10px;">A fourth level heading</h4>
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em; line-height: 1.3em">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
</div>  
```

Halves - Image Right + Heading & Text

```html
<div class="halves" style="clear:both;">
      <div class="two-third" style="float: left; width: 50%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; padding: 0px 5px 0 0;">
          <h4 class="green" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #7AB800; margin: 12px 0px; padding: 0.5em 10px;">A fourth level heading</h4>
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em; line-height: 1.3em">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
      <div class="third" style="display: block; float: left; width: 50%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 0 0 5px; border-left: 1px solid #eee;">
        <img class="ind-80" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="max-width: 80%; display: block; height: auto; margin: auto; padding: 10px;">    
      </div>
</div>
```

Thirds Left - Heading & Text

```html
<div class="thirds" style="clear:both;">
      <div class="third" style="display: block; float: left; width: 33.33%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 10px 0 0; border: 0;">
        <h4 class="green" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #7AB800; margin: 12px 0px; padding: 0.5em 10px;">A fourth level heading</h4>
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em; line-height: 1.3em">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
      <div class="two-third" style="float: left; width: 66.66%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; border-left-color: #eee; border-left-style: solid; padding: 0 10px; border-width: 0 0 0 1px;">
          <h4 class="green" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #7AB800; margin: 12px 0px; padding: 0.5em 10px;">A fourth level heading</h4>
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em; line-height: 1.3em">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
</div>
```

Thirds Right - Heading & Text

```html
<div class="thirds" style="clear:both;">
      <div class="two-third" style="float: left; width: 66.66%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; padding: 0px 10px 0 0;">
          <h4 class="green" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #7AB800; margin: 12px 0px; padding: 0.5em 10px;">A fourth level heading</h4>
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em; line-height: 1.3em">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
      <div class="third" style="display: block; float: left; width: 33.33%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 10px; border-left: 1px solid #eee;">
        <h4 class="green" style="font-family: sans-serif; color: #fff; text-transform: uppercase; font-weight: 600; background-color: #7AB800; margin: 12px 0px; padding: 0.5em 10px;">A fourth level heading</h4>
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em; line-height: 1.3em">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
</div>
```

Thirds - Heading & Text + Video

```html
<div class="thirds" style="clear:both;">
      <div class="third" style="display: block; float: left; width: 33.33%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 10px 0 0; border: 0;">
        <div class="video-container" style="position: relative; padding-bottom: 56.25%; padding-top: 30px; height: 0; overflow: hidden;"><iframe width="560" height="315" src="https://www.youtube.com/embed/977AYjapws0?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>
        
        <p class="byline" style="font-family: sans-serif; color: #666666; text-align: center; word-wrap: break-word; font-style: italic; font-weight: 400; font-size: 16px; line-height: 1.2em; font-family: serif; margin: 0px 0px 1.5em; padding: 0 0 0.5em; border: 0;" align="center">Developed by Christian Surname</p>
      </div>
      <div class="two-third" style="float: left; width: 66.66%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; border-left-color: #eee; border-left-style: solid; padding: 0 10px; border-width: 0 0 0 1px;">
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em;">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
</div> 
```

Thirds - Image + Heading & Text

```html
<div class="thirds" style="clear:both;">
      <div class="third" style="display: block; float: left; width: 33.33%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; margin: 0; padding: 0 10px 0 0; border: 0;">
        <img class="ind-100" src="https://dl.dropboxusercontent.com/u/2706309/Images/flower.jpg" style="max-width: 100%; display: block; height: auto; margin: auto; padding: 10px;">

        
        <p class="byline" style="font-family: sans-serif; color: #666666; text-align: center; word-wrap: break-word; font-style: italic; font-weight: 400; font-size: 16px; line-height: 1.2em; font-family: serif; margin: 0px 0px 1.5em; padding: 0 0 0.5em; border: 0;" align="center">Developed by Christian Surname</p>
      </div>
      <div class="two-third" style="float: left; width: 66.66%; text-align: left; -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; overflow: visible; border-left-color: #eee; border-left-style: solid; padding: 0 10px; border-width: 0 0 0 1px;">
          <p style="font-family: sans-serif; color: #1A1A1A; word-wrap: break-word; line-height: 1.2em; margin: 0px; padding: 0 0 0.5em;">Spent several months developing shaving cream in West Palm Beach, FL. Lead a team buying and selling catfish in Libya. Spent 2001-2005 getting my feet wet with fried chicken in Deltona, FL. Managed a small team working on cigarettes in Cuba. Spent 2001-2007 investing in toy planes in Minneapolis, MN. Garnered an industry award while getting to know junk food in Jacksonville, FL.</p>
      </div>
</div> 
```
