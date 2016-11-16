---
layout: post
comments: true
title:  "About precompile CSS"
date:   2016-11-13 16:16:16
categories: precompile css
---

`I have to be honest, the pre-compiling of the CSS got in to my nerves a bit at the beginning but the variables and mixins won me over fast!`

It is easy to forget how rigid and cumbersome CSS can be, many lines that need to be exactly the same in different places,
identical color values that need
to be copied in different elements, the naming of every tag to get to a link in a unordered list or the
 extra compatibility rules that need to be added every single time you get a bit frisky and use radial
gradient or box shadow. CSS preprocessors help with all that and much more.

In this specific assignment I used `Sass`. It made the changes of color so much smoother, just change the value in one variable and voila! All done.
`Variables` are easily my favorite part of it. No need to repeat the same information over and over again and no need to start a witch hunt
on the hundreds of lines of css rules every time you think a color scheme was not a good choice.

`Nesting` was also very useful. You get to write all css rules that affect an element in different states in just one area, it is
 easier to read than conventional CSS and you do not need to repeat tag paths for each state. Very handy.

I also used the `mixins` feature and found it extremely convenient. I used it mostly for not having to write and rewrite the extra
 rules needed to make sure gradients, shadows etc. are compatible with older browsers.

This project also used the import feature to include scss files containing rules for specific areas and operators to adapt sizes
 and color shades.

Overall I do think Sass makes the creation of CSS a lot smoother and in some cases faster. The `downside` is that you do have to learn it.
 You have to install it properly, read documentation, experiment, fail, get mad, to eventually get a better hang of it.

 The other thing is creation time, in this particular case
 for example it took a lot longer for me to do what I did before with non pre-compiled CSS. But I cannot judge that fully until
 I feel as comfortable with Sass as I feel with traditional CSS. Compilation time as well can be an issue as in some cases it can take
 longer and then you have to wait for it to finish in order to see what you have just added.

 Other people are also concerned about debugging issues as the code lines
 don't match with the source files but this can be solved at this moment by using source maps.
