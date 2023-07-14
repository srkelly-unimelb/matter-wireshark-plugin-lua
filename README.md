# About

matter.lua is a Wireshark Plugin (tested with Wireshark v4.0.4)

This plugin was created as part of a research project with a focus on analysing the Matter protocol for the purposes of fuzz testing.

Other Wireshark plugins will have better ongoing support for Matter such as https://github.com/wireshark!

# Setup

Adding Lua plugin: In wireshark go to 'Help->About Wireshark', select 'Folders' tab, and navigate to 'Personal Lua Plugins' folder.
Simply add file 'matter.lua' into the lua plugins folder and restart Wireshark (or use hotkey ctrl+shift+L to refresh)

Sample .pcap provided of device commissioning and operation (with encryption and message integrity disabled!)
