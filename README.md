<h1>Installation and requierments:</h1>

<h5>you must have conky installed either from your package manager or from Github.
place the conky.conf in this path:
~/.config/conky/conky.conf </h5>

<h1>Autostarting</h1>

add it to your .xinitrc or use your DE's autostart function 
you can simply type conky in your terminal to launch it

<h1>Configuration</h1>
If you have less CPU cores than 12 this wont work properly until you either add or remove the lines about the extera cpu cores.
run nproc in a terminal to see how many cores you have (may need sudo)

this is a minimal conky config that I wrote for my bwm session. 
enjoy
