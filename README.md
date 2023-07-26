# ICON code snippets
Code snippets I use for formatting in ICON

## Color Library  
#ba372a - red that passes accessibility on a white background  
#f5f5f5 - light gray used in code boxes  
#ffcd00 - Hawkeye gold  
black  
#ffcd00 - blue discussion instruction box  
#21577f - font color for blue insturction box - passes accessibility  
#ffcd00 - green disucssion instuction box  
#21577f - font color for green instruction box - passes accessibility  

#dbe7f7 - Microsoft information box color  
#efd9fd - Microsoft note box color  
#dff6dd - Microsoft green message box  
    
---
   
## Red text for messages like ***"Assignment details coming soon"***    
```  
<p>&nbsp;</p>  
<p style="padding-left: 40px;"><span style="color:#ba372a;font-size:14pt;"> <strong><em>Assignment details coming soon.</em></strong> </span></p>  
<p>&nbsp;</p>  
```
  
---
   
## Hawkeye gold header  
```  
<h2 style="background-color: #ffcd00; color: black;">&nbsp; Class</h2>  
``` 
  
---
   
## Gold horizontal rule  
```
<hr style="background-color: #ffcd00; height: 1px;" />  
```  
   
---
    
## Blue instruction box for discussion posts that require a reply from students    
```  
<hr style="background-color: #ffcd00; height: 1px;" />  
<div style="background-color: #e6f2f8; font-style: italic; color: #21577f; border-radius: 10px; padding: 10px 25px 25px;"> 
    <p>You should have two <span style="text-decoration: underline;">meaningful</span> contributions before <strong>Sunday at 11:59pm</strong>.</p> 
    <p><i><em><span data-preserver-spaces="true">To view the discussion board respondent rubric, click the three vertical dots in the upper right corner and select "Show Rubric."</span></em></i></p> 
    <p><i><em><span data-preserver-spaces="true">Leader's rubric can be found here: <a class="instructure_file_link instructure_scribd_file inline_disabled" style="color: #21577f;" title="BAIS6280_Cybersecurity_Leader rubric.pdf" href="https://uiowa.instructure.com/courses/207127/files/21718703?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://uiowa.instructure.com/api/v1/courses/207127/files/21718703" data-api-returntype="File">BAIS6280_Cybersecurity_Leader rubric.pdf</a></span></em></i></p> 
    <p><i><em><span data-preserver-spaces="true">Example discussion posts: <a class="instructure_file_link instructure_scribd_file inline_disabled" style="color: #21577f;" title="BAIS6280_Cybersecurity_Example discussion posts.pdf" href="https://uiowa.instructure.com/courses/207127/files/21704927?wrap=1" target="_blank" rel="noopener" data-api-endpoint="https://uiowa.instructure.com/api/v1/courses/207127/files/21704927" data-api-returntype="File">BAIS6280_Cybersecurity_Example discussion posts.pdf</a></span></em></i></p> 
</div>  
```  
   
---
   
## Green instruction box for discussion posts that do NOT require a reply.    
```  
<hr style="background-color: #ffcd00; height: 1px;" />  
<div style="background-color: #e2efda; font-style: italic; color: #21577f; border-radius: 10px; padding: 10px 25px 25px;">  
    <p>This is an individual response. You are <strong>expected to read</strong> other's posts. You are not required, but welcome, to reply to other posts.</p>  
    <p>You should have your reply posted before <strong>Sunday at 11:59pm</strong>.</p>  
</div>  
```  
   
---
    
## Gray box for blocks of code  
    
### Single line:
```  
<code>   </code>  
```  
  
### Multiline:
```  
<pre style="color: #e03e2d; font-family: Monaco, Menlo, Consolas, 'Courier New', monospace; border: 1px solid #C7CDD1; background: #f5f5f5; padding-left: 5px; padding-right: 5px; margin-left: 5px; margin-right: 2px;">  
  
  <!DOCTYPE html>  
  <html lang="en">  
  <head>  
      <meta charset="UTF-8">  
      <meta http-equiv="X-UA-Compatible" content="IE=edge">  
      <meta name="viewport" content="width=device-width, initial-scale=1.0">  
      <title>Document</title>  
  </head>  
  <body>  
    <! -- comments -->  
    Hello world!  
  </body>  
  </html>  
  
</pre>  
```  
       
---
   
## Generic Week Page
```  
<h2 style="background-color: #ffcd00; color: black;">&nbsp;This Week</h2>  
<h3 style="padding-left: 40px;"><strong>Overview:</strong></h3>  
<p style="padding-left: 80px;">... weekly overview ...</p>  
<p>&nbsp;</p>  
<hr style="background-color: #ffcd00; height: 1px;" />  
<h3 style="padding-left: 40px;"><strong>Objectives:</strong></h3>  
<span style="font-size: 14pt;">By the end of this module you should be able to...</span>  
<ul>  
    <li style="list-style-type: none;">  
        <ul>  
            <li style="list-style-type: none;">  
                <ul>  
                    <li>... list of objectives ...</li>  
                    <li>... list of objectives ...</li>  
                    <li>... list of objectives ...</li>  
                </ul>  
            </li>  
        </ul>  
    </li>  
</ul>  
<p>&nbsp;</p>  
<hr style="background-color: #ffcd00; height: 1px;" />  
<h3 style="padding-left: 40px;"><strong>Things to do this week:</strong><strong></strong></h3>  
<p style="padding-left: 80px;">... list of things required this week ...</p>  
<p>&nbsp;</p>  
<hr style="background-color: #ffcd00; height: 1px;" />  
<h3 style="padding-left: 40px;"><strong>Lecture Resources:</strong></h3>  
<p style="padding-left: 80px;">... list of things used in lecture this week ...</p>  
<p>&nbsp;</p>  
<hr style="background-color: #ffcd00; height: 1px;" />  
<h3 style="padding-left: 40px;"><strong>Lab Resources:</strong></h3>  
<p style="padding-left: 80px;">... list of things used in lab this week ...</p>  
<p>&nbsp;</p>  
<hr style="background-color: #ffcd00; height: 1px;" />  
<h3 style="padding-left: 40px;"><strong><em>Optional</em> Resources:</strong></h3>  
<p style="padding-left: 80px;">... list of things you might be interested in this week ...</p>  
<p>&nbsp;</p>  
```  
       
---
   
## Side-by-side DIVs
```  
<div>
<div style="width: 75%; float: left;">
<p style="padding-left: 40px;"><strong>swirl </strong>is a package that allows users to run and create R programming tutorials and courses (<a href="https://swirlstats.com/">https://swirlstats.com/</a>). swirl runs interactively in the R Console.</p>
</div>
<img id="21765169" src="https://uiowa.instructure.com/courses/204077/files/21765169/preview" alt="swirl logo" width="200" height="65" data-api-endpoint="https://uiowa.instructure.com/api/v1/courses/204077/files/21765169" data-api-returntype="File" />
</div>
<div>&nbsp;</div>
```
       
---
   
## Keyboard blocks
```  
<span style="
    display: inline-block;
    margin: 0 0.1em;
    padding: 0.1em 0.6em;
    font-size: 1rem;
    background-color:#EEEEEE;
    color:black;
    font-family:Consolas,Monaco,Lucida Console,Liberation Mono,DejaVu Sans Mono,Bitstream Vera Sans Mono,Courier New;
    border: 1px solid var(--black-300);
    border-radius: 3px;
    box-shadow: 0 1px 1px hsla(210, 8%, 5%, 0.15), inset 0 1px 0 0 var(--white);
    white-space: nowrap;
"> CTRL </span
```
       
---
  

   ## Combining classes or sections
   (i.e. BAIS:3400 & BAIS:6400)
   1. Go to the primary section (BAIS:3400). In the URL, note the 6 digit course number --> https://uiowa.instructure.com/courses/**209983**
   2. Go to the course you want merged (BAIS:6400). Settings --> Sections
   3. Click on the hyperlink for the course --> Cross-list this Section
   4. Enter the course ID of from step 1 & choose Cross-list this Section
   5. Go to primary course (BAIS:3400). Settings --> Sections. You should now see both courses appear.
   7. From the primary course, go to Settings --> People and you should see student enrollments from both courses.
      
---
      
