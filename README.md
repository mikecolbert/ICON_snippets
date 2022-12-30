# ICON code snippets
Code snippets I use for formatting in ICON

## Color Library  
#e03e2d - red that passes accessibility on a white background  
#f5f5f5 - light gray used in code boxes  
#ffcd00 - Hawkeye gold  
black  
#ffcd00 - blue discussion instruction box  
#21577f - font color for blue insturction box - passes accessibility  
#ffcd00 - green disucssion instuction box  
#21577f - font color for green instruction box - passes accessibility  
  
---
   
## Red text for messages like ***"Assignment details coming soon"***    
```  
<span style="color: #e03e2d; font-size: 14pt;"> 
  <strong><em style="color: #db3322;">Assignment details coming soon.</em></strong> 
</span> 
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
   
