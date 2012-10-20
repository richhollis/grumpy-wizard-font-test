Webfonts don't render correctly in Webkit
====================================

This is an HTML example related to a reply I made at Stack Overflow:
http://stackoverflow.com/questions/12506207/font-face-rendering-issue-on-paragraph-tag-chrome-android-4/12988386#12988386


> I noticed that whilst I had this problem with a site I was working on that some pages seemed to work better than others. So I spent some time to try and work out why this was and if any sort of "workaround" could be used in the meantime.
>
> I personally had problems getting Webfonts to render correctly on Chrome in Android - Nexus S and Nexus 7.
>
> I've found that if you play with the width of your elements it appears to be possible to workaround the bug to some extent and still get web fonts under 18px to render correctly.
> 
> In the sample code attached it seems everything works on a max width of 88.8%. You can have a wider first DIV but then it breaks the ones underneath. Everything only seems to work at that magic percentage. It might be an ok workaround for some people. Your mileage may vary and you may need to play with the percentages - I needed to tweak the percentage up slightly in a responsive layout (gridpak) but I suspect it probably still conforms to the same sort of logic in overall percentage terms. After all the behaviour of this bug is strange but this does seem to sort of stabilise it into some usable pattern and maybe this helps you out.
> 
> Somebody else might understand a bit deeper what is at play here and maybe offer some more advice/explanation.
