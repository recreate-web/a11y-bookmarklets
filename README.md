a11y-bookmarklets
=================

<a href="javascript:(function(){var newcss=":focus{outline:#afff00; background-color:red; display:block; z-index:999999999; outline: solid 3px red !important}";var tag=document.createElement('style');tag.type='text/css';document.getElementsByTagName('head')[0].appendChild(tag);tag[(typeof document.body.style.WebkitAppearance=='string')?'innerText':'innerHTML']=newcss})();">Visual Focus Bookmakrlet</a>
