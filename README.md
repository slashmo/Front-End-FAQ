# Front-End-FAQ
A place to anonymously ask questions and receive answers from the dev community. <br /> <br />

## How It Works
The premise is simple: Ask the questions you've always had about Front-End Development but were too afraid to ask for fear of criticism, then wait for a response! <br /> <br />

## How Do I Ask A Question?
Send me a DM over on [Twitter](https://twitter.com/EmmaWedekind)! <br /> <br />

## How Do I Answer A Question?
Feel free to open a PR on this repo! <br /> <br />

## How Is This Different Than Stack Overflow?
It's true that Stack Overflow is meant for knowledge sharing. That being said, as a beginner I know I had a ton of questions about HTML, CSS, and JavaScript that I wanted answered, but anonymously. Stack Overflow requires you to be logged in. Yes, you can change your name, but that's a hastle and has a 30-day waiting period to re-change. I want to remove the hastle of asking and answering questions.

Front-End FAQ will be the one place you can go to for all your Front-end questions, while remaining anonymous.  Plus, it's a great way to contribute to open-source. <br /> <br />

# Table Of Contents
[HTML](#html)  
[CSS](#css)  
[JavaScript](#javascript) 
[Performance](#performance)  
[Accessibility](#accessibility)  
[Node](#node)

 <br/> <br/> <br/>

# HTML   
**What are `<div>` and `<span>`?  Why would you use them?**  
_Waiting for response_

<br/><br/><br/>


# CSS  

**What is the difference between absolute and fixed positioning?**  
_Waiting for response_


**What is the best/most performant way to include media queries? Is it better to put them all in one CSS file or split them up into different CSS files per component or page?**  
_Waiting for response_
<br/><br/><br/>



# JavaScript   

**What is a Promise and how do you use it?**  
_Waiting for response_

<br/><br/><br/>




# Performance   

**What is the best way to reduce my image file size?** 

>At minimum: use [ImageOptim](https://imageoptim.com/). It can significantly reduce the size of images while preserving visual quality. Windows and Linux [alternatives](https://imageoptim.com/versions.html) are also available.

>More specifically: run your JPEGs through [MozJPEG](https://github.com/mozilla/mozjpeg0) (q=80 or lower is fine for web content) and consider [Progressive JPEG](http://cloudinary.com/blog/progressive_jpegs_and_green_martians) support, PNGs through [pngquant](https://pngquant.org/) and SVGs through [SVGO](https://github.com/svg/svgo). Explicitly strip out metadata (--strip for pngquant) to avoid bloat. Instead of crazy huge animated GIFs, deliver [H.264](https://en.wikipedia.org/wiki/H.264/MPEG-4_AVC) videos (or [WebM](https://www.webmproject.org/) for Chrome, Firefox and Opera)! If you can’t at least use [Giflossy](https://github.com/pornel/giflossy). If you can spare the extra CPU cycles, need higher-than-web-average quality and are okay with slow encode times: try [Guetzli](https://research.googleblog.com/2017/03/announcing-guetzli-new-open-source-jpeg.html).

From the excellent [images.guide](https://images.guide/). <br/><br/>

**What is the best format for performant images? PNG? JPG? SVG?**  
_Waiting for response_

<br/><br/><br/>




# Accessibility   

**Do I need to make my app accessible?**  
_Waiting for response_

**How do I make my app accessible?**  
_Waiting for response_

<br/><br/><br/>


# Node  
**Where do I find other people's Node.js code for small projects? GitHub doesn't seem to display it?**  
_Waiting for response_
