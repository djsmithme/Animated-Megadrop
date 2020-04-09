<h1>Animated Megadropdown</h1>

<p>An Animated Dropdown Mega Menu that uses Animate CSS/HoverIntent with CSS only fallback</p>
<p>Note: Wouldn't use this as is, needs tweaking</p>


<h2><a href="http://djsmithme.github.io/Animated-Megadrop/">Demo</a></h2>

<h2>Features</h2>

<ul>
<li>Javascript Based menu with CSS only fallback</li>
<li>Uses CSS3 animation when available (fallback to js)</li>
<li>Works in IE7+</li>
</ul>

<h2>Dependencies</h2>


Will work without however if you have them added this plugin can use the following:

<ul>
<li> <a href="http://daneden.github.io/animate.css/">Animate.css </a></li>
<li> <a href="https://github.com/briancherne/jquery-hoverIntent">HoverIntent<a></li>
<li> Compass</li> 
</ul>

<h2>Installation</h2>

<pre>

Inlude Animate.css or copy the relavent styles
"animate.css"

Load the CSS:
"Megadropdown.css"

Include js plugin:
"Megadropdown.js"

</pre>

<h2>Set up your HTML</h2>

Add the following classes to the menu UL:

```

.nav      // styles assigned to this class
.nojs     // contains the hover classes that will be removed if javascript is present                  

```



```

<nav class="navigation">
<ul class="nav shadow clearfix nojs" id="menu">
    <li><a href="#"><i class="fa fa-home"></i> Home</a></li>
    <li><a href="#">Megadrop</a>
            <div class="container-4">
                    <div class="col1">
                            <h3>Megadrop</h3>
                                <ul>
                                    <li><a href="">Item 1</a></li>
                                    <li><a href="">Item 2</a></li>
                                    <li><a href="">Item 3</a></li>
                                    <li><a href="">Item 4</a></li>
                                    <li><a href="">Item 5</a></li>
                                    <li><a href="">Item 6</a></li>
                                    <li><a href="">Item 7</a></li>
                                    <li><a href="">Item 8</a></li>


                                </ul>
                    </div>
                    <div class="col1">
                        <h3>&nbsp;</h3>
                                <ul>
                                    <li><a href="">Item 9</a></li>
                                    <li><a href="">Item 10</a></li>
                                    <li><a href="">Item 11</a></li>
                                    <li><a href="">Item 12</a></li>
                                    <li><a href="">Item 13</a></li>
                                    <li><a href="">Item 14</a></li>
                                    <li><a href="">Item 15</a></li>
                                </ul>
                    </div>
                    <div class="col1">
                        <h3>&nbsp;</h3>
                                <ul>
                                    <li><a href="">Item 16</a></li>
                                    <li><a href="">Item 17</a></li>
                                    <li><a href="">Item 18</a></li>
                                    <li><a href="">Item 19</a></li>
                                    <li><a href="">Item 20</a></li>

                                </ul>
                    </div>
                    <div class="col1">
                        <h3>&nbsp;</h3>
                                <ul>
                                     <li><a href="">Item 21</a></li>
                                      <li><a href="">Item 22</a></li>
                                       <li><a href="">Item 23</a></li>
                                        <li><a href="">Item 24</a></li>
                                         <li><a href="">Item 25</a></li>

                                </ul>
                    </div>
                    <div class="col4">
                        <a href='#'><h3>Subhead Link.</h3></a>
                    </div>
            </div>	
    </li>
    <li><a href="#">About</a>
                <div class="container-1">
                        <ul>
                            <li><a href="#">Who We Are</a></li>
                            <li><a href="#">Why We Care</a></li>
                            <li><a href="#">Some other page</a></li>
                            <li><a href="#">How We Work</a></li>
                        </ul>
                </div>
    </li>
    <li><a href="#">Link</a></li>
    <li><a href="#">Contact</a></li>
    <li class="nav-right"><a href="#">Request a Callback</a></li>   
</ul>     
</nav>


```


<h2>Call the plugin</h2>


```javascript

$('#menu').Megadropdown({
        activeClass: 'open',                                                                                   
        fadeInDuration: 250,
        fadeOutDuration: 'slow',
        openAnimation: 'fadeInUp',
        closeAnimation: 'fadeOutDown',
        hoverTimeout: 450
        });

```


<h2>Tested on</h2>
<ul>
<li>IE7+</li>
<li>Safari</li>
<li>Firefox </li>
<li>Chrome</li>
</ul>


<h2>License</h2>
<p>The MIT License (MIT)</p>
