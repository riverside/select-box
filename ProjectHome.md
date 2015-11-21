# Introduction #
jQuery Selectbox plugin replace browser built-in select box form element with fancy high customizable one.



Version 0.2 add support of:
  * 'tabindex'
  * close on click outside
  * keyboard navigation (enter, escape, tab, arrows: left, down, right, up)

Version 0.1.3 add support of:
  * 'optgroup'
  * 'disabled' attribute on both 'option' and 'optgroup'
  * custom speed

# Screenshot #
![http://www.bulgaria-web-developers.com/blog/wp-content/uploads/2011/02/selectbox.png](http://www.bulgaria-web-developers.com/blog/wp-content/uploads/2011/02/selectbox.png)

# Usage #
Include (or [download](http://code.google.com/p/select-box/downloads/list))
```
<link href="http://select-box.googlecode.com/svn/tags/0.2/jquery.selectbox.css" type="text/css" rel="stylesheet" />
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.7.2/jquery.min.js"></script>
<script type="text/javascript" src="http://select-box.googlecode.com/svn/tags/0.2/jquery.selectbox-0.2.min.js"></script>
```

HTML code:
```
<select id="language">
    <option value="javascript">Javascript</option>
    <option value="objective-c">Objective C</option>
    <option value="python">Python</option>
</select>
```

Selectbox javascript call:
```
<script type="text/javascript">
$(function () {
    $("#language").selectbox();
});
</script>
```

# Demo #
[View demo](http://www.bulgaria-web-developers.com/projects/javascript/selectbox/)