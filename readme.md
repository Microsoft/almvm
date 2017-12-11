---
layout: homepage
title: Microsoft ALM VM
keywords: ALM VM homepage
tags: [overview]
permalink: /default.html
comments: true
redirect_from:
summary: 
---
        
 <!--<img src="http://vsalmvm.azurewebsites.net/wp-content/uploads/2015/09/ALM-VM-banner-0915.png" width="760" height="177" />-->

<br>
<span class="introText">
The Microsoft ALM/DevOps Hands-On-Labs is a set of self-placed labs that will give you experience and help you get started with all the ALM/DevOps Capabilities that Microsoft Visual Studio Team Foundation Server/Visual Studio Team Services provides. 
</span>
<br />
<br />
 
<div class="row">
    <div class="lab-item col-md-4" align="center">
          <span class="headnews"> <b> <a href="labs/tfs" class="labmain">Visual Studio & Team Foundation Server Labs</a></b></span><br />
             <a href="labs/tfs"><img style="margin: 10px;" src="images/vside.png"/></a><br />
           <!--span class="mainPageText"> Access the Microsoft ALM VM and TFS Hands-on-Labs</span><br /><br /-->
           <a href="labs/tfs" class="c-glyph"><span class="lab-details">View Details</span></a>
    </div>
    <div class="lab-item col-md-4" align="center">
         <span class="headnews"> <b><a href="labs/vsts" class="labmain"> Visual Studio Team Services Labs</a></b></span><br /><br />
        <a href="labs/vsts"><img style="margin: 10px;" src="images/vstslogo.png"/></a><br />
       <!--span class="mainPageText"> Follow the Visual Studio Team Services Hands-on-Labs</span><br /><br /-->
       <a href="labs/vsts" class="c-glyph"><span class="lab-details">View Details</span></a>
    </div>
     <div class="lab-item col-md-4" align="center">
         <span class="headnews"> <b><a href="labs/java" class="labmain"> DevOps with Visual Studio Team Services for Java Labs</a></b></span><br />
        <a href="labs/java"><img style="margin: 10px;" src="images/java.png"/></a><br />
       <!--span class="mainPageText"> DevOps with Visual Studio Team Services for Java</span><br /><br /-->
       <a href="labs/java" class="c-glyph"><span class="lab-details">View Details</span></a>
    </div>
</div>
 
 <div class="clear"></div>

<br />

<h2> Recent News </h2>
 {% for post in site.posts limit:10 %}
<div class="headline">

<span class="headnews">
<a href="{{ post.pageurl | prepend: site.baseurl| prepend: site.url }}">{{ post.title | xml_escape }}</a>
</span> 
<p>
{{ post.content }}
</p>
<div class="newsitem">
<span class="newsfooter">
<span class="glyphicon glyphicon-time"></span> &nbsp;{{ post.pubdate }}  &nbsp;&nbsp;&nbsp; <span class="glyphicon glyphicon-user"></span> &nbsp; {{ post.Author }}   &nbsp;&nbsp;&nbsp; <span class="glyphicon glyphicon-link"></span>&nbsp;<a href="{{ post.pageurl | prepend: site.baseurl| prepend: site.url }}">   Link</a>
</span>
</div>
</div>

{% endfor %}


 








