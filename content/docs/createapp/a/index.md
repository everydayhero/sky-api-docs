---
layout: layout-base
name: Create an Application
description: Learn how to successfully create an application with SKY API.
order: 600
published: true     
showInNav: false
back_to_top: true
title: Create an Application Tutorial
---
<div class="container">
<section class="section-padding bg-tutorial">
<div class="row text-center">
<h1 class="tutorial"> {{ name }} with {{ stache.config.product_name_short }}</h1>

<p class="lead">To successfully create an application with {{ stache.config.product_name_short }}, follow this step-by-step guide.</p>


<p class="lead">Before you begin, be sure to complete the <a href="{{ stache.config.guide_getting_started }}">Getting Started</a> guide, where you'll get your  Blackbaud developer account, a subscription key, and learn how to explore the <a href="{{ stache.config.portal_endpoints }}" target="_blank">Endpoint Reference</a>.</p>
<br />
<ul class="slide-container">
 <li class="slide">
<h1>Register your application</h1>
<br />
{{ include 'includes/tutorials/createapp/registerapp.md' }}
</li>
 
 <li class="slide slide-animate">
 <div class="row" >
<h1>Review your application credentials</h1>
<br />
{{ include 'includes/tutorials/createapp/credentials.md' }}
 </li>
 
 <li class="slide slide-animate">
<div class="row">
<h1>Activate your application in a tenant</h1>
<br />
{{ include 'includes/tutorials/createapp/activateapp.md' }}
</li>

<li class="slide slide-animate">
 <div class="row" >
 <h1>Request authorization</h1>
<br />
{{ include 'includes/tutorials/createapp/requestauth.md' }}
</li>



<li class="slide slide-animate">
 <h1>... and you're done!</h1>
<br />
{{ include 'includes/tutorials/createapp/done.md' }}
</li></ul>


<h1>Now that you've built and tested your application, here are a few things you should know.</h1>
<br />
        <div class="row">
       
          <div class="col-sm-4 tutorial-button">
            <a href="{{ stache.config.skyux }}" target="_blank" class="btn-fa-link">
              <span class="fa-stack fa-4x">
                <i class="fa fa-circle fa-stack-2x"></i>
                <i class="fa fa-code fa-stack-1x text-primary"></i>
              </span> 
            </a> 
            <h3>SKY UX</h3>
            <p>SKY UX is Blackbaud’s next-generation user-experience framework. You can use it to bring the same consistent experience as Blackbaud products to your customizations and applications.</p>
          </div> 
          
             <div class="col-sm-4 tutorial-button">
            <a href="{{ stache.config.support_community }}" target="_blank" class="btn-fa-link">
              <span class="fa-stack fa-4x">
                <i class="fa fa-circle fa-stack-2x"></i>
                <i class="fa fa-users fa-stack-1x text-primary"></i>
              </span> 
            </a> 
            <h3>Blackbaud Developer Community</h3>
            <p>Participate and learn from other developers on how they are using the {{ stache.config.product_name_short }}.</p></div> 
          
          <div class="col-sm-4 tutorial-button">
            <a href="{{ stache.config.partner_program}}" target="_blank" class="btn-fa-link">
              <span class="fa-stack fa-4x">
                <i class="fa fa-circle fa-stack-2x"></i>
                <i class="fa fa-cloud fa-stack-1x text-primary"></i>
              </span>  
            </a> 
            <h3>Blackbaud Partner Network</h3>
            <p>Learn how to be a part of our Blackbaud Partner Network.</p>
          </div>  
            
        </div>  

</div></section></div>