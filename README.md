NEO and Truly Ergonomic keyboard
--------------------------------

This is an adaption of the German **NEO** layout for the **Truly Ergonomic
Computer Keyboard (TECK)**, using the X Keyboard Extension (XKB, see
next section).

Activate the layout with `setxkbmap de neo -option truly:neo`.  DIP
switch 1 of the keyboard *must be off*.

Additionally, the left space key can act as Tab with `setxkbmap de neo
-option truly:neo,truly:leftspace_tab`.  DIP switch 3 of the keyboard
*must be off*.  This option can also be used with other (non-NEO) layouts.

Details can be found in the `DESIGN.md` file (in German).


X Keyboard Extension
--------------------

The X Keyboard Extension essentially replaces the core protocol definition of
keyboard. The extension makes possible to clearly and explicitly specify most
aspects of keyboard behaviour on per-key basis and to more closely track the
logical and physical state of the keyboard. It also includes a number of
keyboard controls designed to make keyboards more accessible to people with
physical impairments.

There are five types of components in the server database corresponding to five
xkb symbolic names: symbols, geometry, keycodes, compat and types which
determine the keyboard behaviour. These five components can combined together
into a resulting keyboard mapping using the 'rules' component.

The complete specification can be found on
http://xfree86.org/current/XKBproto.pdf

For XKB configuration information see `docs/README.config` file.

For information how to further enhance XKB configuration see `docs/README.enhancing`
file.

For information how to replace existing XKB configuration database with
XKeyboardConfig see `docs/HOWTO.transition` file.

Contribution guidelines are described at
http://www.freedesktop.org/wiki/Software/XKeyboardConfig/Rules
