<div align="center">

## Expanding and contracting HTML using JavaScript


</div>

### Description

Using JavaScript, you can very easily make content expand and contact, like with a folding tree. I'll show you how.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Super Mario](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/super-mario.md)
**Level**          |Intermediate
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |
**Category**       |[Controls/ Forms/ Graphics/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-graphics-menus__2-59.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/super-mario-expanding-and-contracting-html-using-javascript__2-4128/archive/master.zip)





### Source Code

```
Using JavaScript, you can very easily make content expand and contact, like with
a folding tree. The key is the CSS property &quot;display.&quot; I use it below to create
a header that expands/contacts when clicked on: </p>
<pre>&lt;script type=&quot;text/javascript&quot;&gt;
function foldinout(theid){
var theid=document.getElementById(theid)
theid.style.display=(theid.style.display==&quot;block&quot;)? &quot;none&quot; : &quot;block&quot;
}
&lt;/script&gt;
&lt;div onClick=&quot;foldinout('thelinks')&quot;&gt;&lt;b&gt;Categories&lt;/b&gt;&lt;/div&gt;
&lt;div id=&quot;thelinks&quot; style=&quot;display:block&quot;&gt;
-Games
-Entertainment
-Movies
&lt;/div&gt;</pre>
<p>I love this &quot;Switch Menu&quot; script from Dynamic Drive, which makes excellent
use of this idea: http://www.dynamicdrive.com/dynamicindex1/switchmenu.htm</p>
```

