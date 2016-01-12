Wireshark dissector for OSCAR (ICQ) Protocol
--------------------------------------------

The dissector follows the description of OSCAR protocol available at http://iserverd.khstu.ru/oscar/

* `flapp` - dissector for bunches of FLAP packets
* `flap` - dissector for FLAP protocol
* `snac` - dissector for SNAC protocol
* `icqsmsg` dissects messages transmitted from server to user
* `icqumsg` dissects messages transmitted from user to server

Messages text is decoded and shown in Wireshark, use `icqsmsg || icqumsg` filter to get messages text.

Installation
------------

* On Linux/Unix/OSX just put the file into `$HOME/.wireshark/plugins/`
* On Windows add to your `init.lua` script file `dofile("<path_to_your_file>\oscar.lua")`

Additional information about Lua in Wireshark can be found at https://wiki.wireshark.org/Lua
