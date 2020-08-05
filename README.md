# GamourDevelopment
[See Live](https://kabi4.github.io/GamourDevelopment/)
First Turn make navigation as the lower sibling of all the sections then in each section in css but this code.
&:target ~ .navigation .navigation__background {
        transform: scale(0);
    }
    &:target ~ .navigation .navigation__nav {
        width: 0;
        opacity: 0;
    }
Also in nav replace the checkbox with a anchor and in anchor put this id="navigationbar".

Then in Nav CSS replae all the :checked class with this.
    &:target

for refrence go to _turn_nav file
