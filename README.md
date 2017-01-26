# RPiOpenBox

This is a better OpenBox configuration than the default. (OpenBox is the default window manager that comes with LXDE desktop environment, as used by Raspbian, Lubuntu, etc.)

    mv $HOME/.config/openbox/lxde-pi-rc.xml $HOME/.config/openbox/lxde-pi-rc.old
    cp lxde-pi-rc.xml $HOME/.config/openbox/

Look at diff.xml to see what I did. There's some squirly things in the default that just had to go, and I added what anyone would expect: 

    Super + Left Arrow to snap left
    Super + Right Arrow to snap right
    Super + Up Arrow to toggle maximize

And other good stuff.

.for_reference_only is for refernce only from another LXDE desktop I had
