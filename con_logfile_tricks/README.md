While a bunch of these got fixed after my reports, there are still a few possible advantages to be gained, by parsing a console logfile while playing.

In short you make an autohotkey that spams a button while ingame, binds the button to something like net_dumpeventstats. Then with a con_logfile set, continually parse the logfile waiting for events. The net_dumpeventstats allows to make an accurate external bomb timer for example. The most useful commands were fixed though, but there's probably more if you look properly.