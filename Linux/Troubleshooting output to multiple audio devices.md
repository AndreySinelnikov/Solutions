CONTEXT:

A person walks into a Manjaro distro, and the audio settings are acting up!

SOLUTION:

There are actually two layers of audio settings here.

The underlying audio settings are reached via _alsamixer_ terminal command. 
**M** key mutes/unmutes various audio channels 
("oo" indicates that a channel is on, "MM" indicates that it's muted).

The high-level mixer (Pulse Audio) is reached via _pavucontrol_.
if a device does not play any sound, you might want to fiddle with
Configuration tab.
