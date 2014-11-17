pslb
====

Simple JS lightbox clone, jQuery is required.

* Add between the ```<HEAD>``` and ```</HEAD>``` this code:

```
<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.0.2/jquery.min.js"></script>
<script src="psimplebox.js"></script>
```

* Then wrap image links like this:

```
<div id="imageSet">

<a href="http://link.to.image" class="simplebox">    
<img src="http://link.to.thumbnail" class="thumb" /></a>
    
<a href="http://link.to.another.image" class="simplebox">    
<img src="link.to.another.thumbnail" class="thumb" /></a>

[...]

</div>
```
* Done.
