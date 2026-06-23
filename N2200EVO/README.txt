23May2013
Resetting the N2200EVO

The manual says:
"
In case you changed the N2200 IP address and then forgot it, or forgot the
administration password, follow the steps below to reset to default settings:

1. Power on the N2200 and immediately press the Reset button for 5 seconds.
(The reset button is near the LAN connector)

2. This resets the N2200 to its default IP address and password settings.

Default IP: 192.168.1.100
Default admin password: admin
"
However, this didn't work for me.  I found a more-correct answer:

http://forum.thecus.com/viewtopic.php?f=20&t=4437#p26532

"
N2200 has reset button, please follow the step to reset:
1. Shut down NAS
2. Press the reset button then boot NAS, please do not release reset button until you hear beep after 30 secs.
"

That worked.  Hold reset button until it begins to beep.  Release button, then wait a further minute until it beeps again, and then it's reset to 192.168.1.100


Upgrading the firmware

It takes a lot longer than you'd think.  Several minutes. After all, it's around 35Mb !

When rebooting, when it says it takes around 100 seconds to reboot, it's not kidding.  I see around 95 seconds.

-- end
