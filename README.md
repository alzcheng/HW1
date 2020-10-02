# HW1 - Code Refractor

##Description

A client has asked us to refractor their website HTML and CSS code.  The finished product must look very similar to their original site.  The original site looks like it is below: 

![Client finished website](/assets/images/01-html-css-git-homework-demo.png)

There's several issues with the code due to inefficient use of HTML5 semantics that made the code hard to read.  Furthermore, there are conslidation that can be made to the CSS code to make it much more efficient. 

##Summary of changes

Below are the summary of changes that were made from the original code: 

###For HTML code: 

* Made the Search Engine Optimization link work
* Class hero is basically an image, put the styling to CSS code 
* Class "content" is <article>, and those inside it are <segments> 
* Class "benefits" is <aside> and those inside it are <segments>
* Changed <div> to <header>
* Changed <div> to <footer>

###For CSS code: 

* Optimized stylings for header, a, p, img, and footer
* Consolidated for "content" 
  * Search-engin-optimization
  * Online-reputation-management
  * Social-media-marketing
* Consolidate for "benefits" 
  * Benefit-lead
  * Benefit-brand
  * Benefit-cost

##Learnings 

1. Learned how to consolidate and make css code more efficient 
2. Learned to add links within the webpage 
3. Learned to use HTML5 semantics 

