# popup-window-in-php

<A  HREF=" " id="leadconst"   onClick="return popup(this //href link, 'const' //popup window name)"></A>

<SCRIPT TYPE="text/javascript"> 
    function popup(mylink, windowname,id)
    { 
         if (! window.focus)
            return true; 
        var href; 
        if (typeof(mylink) == 'string') href=mylink; 
        else href=mylink.href;
        window.open(href, windowname, 'width=400,height=200,scrollbars=yes'); 
        return false; } 
</SCRIPT>
