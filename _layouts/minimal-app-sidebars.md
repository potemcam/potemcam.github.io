<!DOCTYPE html>
<html class="no-js" lang="en">

<head>
	
<title>Welcome to {{ page.companyname }}.</title>
	
<style>
html { font-size: 12pt; }	
h1 { font-size: 1.50em; }
h2 { font-size: 1.25em; }
h3 { font-size: 1.1em; }
h4 { font-size: 1.05em; }
h5 { font-size: .83em; }
h6 { font-size: .75em; }
a, u {text-decoration: none; color:#0d47a1}  
a:hover {
background-color: #f9fbfd; color #4285F4;
}
.header, .footer {
background: white;
text-align: center;
}
.main {
background: white;
text-align: left;
}
.aside-1 {
background: white;
}
.aside-2 {
background: white;
}
</style>
    
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1"/>
<meta name="robots" content="index, follow" />
<meta charset="utf-8" />
<meta http-equiv="x-ua-compatible" content="ie=edge" />
<meta name="description" content="" />
<meta name="viewport" content="width=device-width, initial-scale=1" />



<link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">

<!-- ========================= CSS here ========================= -->
<link rel="stylesheet" href="/assets/css/bootstrap.min.css" />
<link rel="stylesheet" href="/assets/css/LineIcons.2.0.css" />
<link rel="stylesheet" href="/assets/css/animate.css" />
<link rel="stylesheet" href="/assets/css/tiny-slider.css" />
<link rel="stylesheet" href="/assets/css/glightbox.min.css" />
<link rel="stylesheet" href="/assets/css/main.css" />

<!-- okta -->
<link rel="stylesheet" type="text/css" href="/css/main.css" />
<!-- link rel="stylesheet" href="https://cdn.auth0.com/js/auth0-samples-theme/1.0/css/auth0-theme.min.css" /-->
	
</head>

<body style="padding:0">

{% include minimal-nav.html %} 

<section id="download" class="app-download style2 section-blue3">

        <div class="container">
            <div class="row ">
                <div class="col-lg-8 offset-lg-2 col-md-12 col-12">
                    <div class="download-content">
                        <h2 class="wow fadeInUp" data-wow-delay=".2s" style="visibility: visible; animation-delay: 0.2s; animation-name: fadeInUp;">&nbsp;
                        </h2>

                    </div>
                </div>
            </div>
        </div>
    </section>	

    <!-- Start App Screenshort Area -->
    <section class="app-screenshorts style2 section-blue mt-3 mb-0">
	<div class="container">
            <div class="row">
			
			
			
<div style="" class="main col col-12 col-sm-12 col-md-9 col-lg-8 order-1 order-sm-2 order-lg-1 mb-5 mt-1">

{{ content }}


</div>

<div style="" class="main col col-12 col-sm-12 col-md-3 col-lg-4 order-2 order-sm-2 order-lg-2 mb-5 mt-1">

<div>
  <div class="App">
    <div class="container">
	
	
      
      <div class="card mt-3">
        <div class="card-header d-flex justify-content-between" ><font color="silver">Create Jira Ticket</font></div>
        <div class="card-body">
          {% include jira-ticket-form.html %}
			<!-- <font color="silver" size="2">If you find a bug, please file a Jira ticket.</font> -->
			<!-- img src="/assets/exam-is-coming.jpg" alt="AWS Study Guide" class="img-fluid mx-auto d-block img-thumbnail rounded "-->

         </div>
      </div>
	  
	  <div class="card mt-3">
        <div class="card-header d-flex justify-content-between" ><font color="silver">Related Tickets</font></div>

          <div class="card-body">
		  <font color="silver" size="2">Here is a list of Jira tickets related to this app.</font>
			<!-- img src="/assets/louder-uipath-exam-dump.jpg" alt="AWS Braindump Policy" class="img-fluid mx-auto d-block img-thumbnail rounded "-->
          </div>

      </div>
	  
	  <div class="card mt-3">
        <div class="card-header d-flex justify-content-between" ><font color="silver">Update App</font></div>
        <div class="card-body">
			<font color="silver" size="2">Upload the latest version of your app as a ZIP file.</font>
			<!-- img src="/assets/exam-is-coming.jpg" alt="AWS Study Guide" class="img-fluid mx-auto d-block img-thumbnail rounded "-->
			<input type="text"/>

         </div>
      </div>
	  
	  	  
	  <div class="card mt-3">
        <div class="card-header d-flex justify-content-between" ><font color="silver">Stages</font></div>
        <div class="card-body">
			<font color="silver" size="2">View this app in the following build stages:
			<ul><li><a href="#">Prod</a></li><li><a href="#">QA</a></li><li><a href="#">Dev</a></li><li><a href="/apps/flashcards/unauth.html">Unauthenticated</a></li></ul>
			
			</font>
			<!-- img src="/assets/exam-is-coming.jpg" alt="AWS Study Guide" class="img-fluid mx-auto d-block img-thumbnail rounded "-->

         </div>
      </div>
      

      
    </div>
  </div>
</div>


</div>



            </div>
        </div>
		</div>
    </section>
    <!-- End App Screenshort Area -->
	
	
	


    <!-- ========================= JS here ========================= -->
    <script src="/assets/js/bootstrap.min.js"></script>
    <script src="/assets/js/count-up.min.js"></script>
    <script src="/assets/js/wow.min.js"></script>
    <script src="/assets/js/tiny-slider.js"></script>
    <script src="/assets/js/glightbox.min.js"></script>
    <script src="/assets/js/imagesloaded.min.js"></script>
    <script src="/assets/js/isotope.min.js"></script>
    <script src="/assets/js/main.js"></script>
   
<!-- okta -->
<script src="https://cdn.auth0.com/js/auth0-spa-js/2.0/auth0-spa-js.production.js"></script>
<script src="/js/ui.js"></script>
<script src="/js/app.js"></script>
	
<script>!function(c){function e(e){for(var r,t,n=e[0],o=e[1],u=e[2],i=0,a=[];i<n.length;i++)t=n[i],f[t]&&a.push(f[t][0]),f[t]=0;for(r in o)Object.prototype.hasOwnProperty.call(o,r)&&(c[r]=o[r]);for(d&&d(e);a.length;)a.shift()();return p.push.apply(p,u||[]),l()}function l(){for(var e,r=0;r<p.length;r++){for(var t=p[r],n=!0,o=1;o<t.length;o++){var u=t[o];0!==f[u]&&(n=!1)}n&&(p.splice(r--,1),e=s(s.s=t[0]))}return e}var t={},f={1:0},p=[];function s(e){if(t[e])return t[e].exports;var r=t[e]={i:e,l:!1,exports:{}};return c[e].call(r.exports,r,r.exports,s),r.l=!0,r.exports}s.e=function(u){var e=[],t=f[u];if(0!==t)if(t)e.push(t[2]);else{var r=new Promise(function(e,r){t=f[u]=[e,r]});e.push(t[2]=r);var n,i=document.createElement("script");i.charset="utf-8",i.timeout=120,s.nc&&i.setAttribute("nonce",s.nc),i.src=s.p+"static/js/"+({}[u]||u)+"."+{3:"38e0e305"}[u]+".chunk.js",n=function(e){i.onerror=i.onload=null,clearTimeout(a);var r=f[u];if(0!==r){if(r){var t=e&&("load"===e.type?"missing":e.type),n=e&&e.target&&e.target.src,o=new Error("Loading chunk "+u+" failed.\n("+t+": "+n+")");o.type=t,o.request=n,r[1](o)}f[u]=void 0}};var a=setTimeout(function(){n({type:"timeout",target:i})},12e4);i.onerror=i.onload=n,document.head.appendChild(i)}return Promise.all(e)},s.m=c,s.c=t,s.d=function(e,r,t){s.o(e,r)||Object.defineProperty(e,r,{enumerable:!0,get:t})},s.r=function(e){"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(e,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(e,"__esModule",{value:!0})},s.t=function(r,e){if(1&e&&(r=s(r)),8&e)return r;if(4&e&&"object"==typeof r&&r&&r.__esModule)return r;var t=Object.create(null);if(s.r(t),Object.defineProperty(t,"default",{enumerable:!0,value:r}),2&e&&"string"!=typeof r)for(var n in r)s.d(t,n,function(e){return r[e]}.bind(null,n));return t},s.n=function(e){var r=e&&e.__esModule?function(){return e.default}:function(){return e};return s.d(r,"a",r),r},s.o=function(e,r){return Object.prototype.hasOwnProperty.call(e,r)},s.p="/exam/",s.oe=function(e){throw console.error(e),e};var r=window.webpackJsonp=window.webpackJsonp||[],n=r.push.bind(r);r.push=e,r=r.slice();for(var o=0;o<r.length;o++)e(r[o]);var d=n;l()}([])</script>


</body></html>
