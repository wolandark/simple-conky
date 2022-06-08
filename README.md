<h1>Installation and requierments:</h1>

<h3>you must have conky installed either from your package manager or from Github.
place the conky.conf in this path:
~/.config/conky/conky.conf </h3>

<h1>Autostarting</h1>

<h3>add it to your .xinitrc or use your DE's autostart function.
you can simply type conky in your terminal to launch it </h3>

<h1>Configuration</h1>
<h3>If you have less CPU threads than 12 this wont work properly until you either add or remove the lines about the extera cpu threads.
run nproc in a terminal to see how many cores and threads you have (may need sudo)

this is a minimal conky config that I wrote for my DWM session. There is nothing fancy about it. It just monitors the system resources and reports in a simple visual manifestation. 
  
enjoy </h3>
![image](https://user-images.githubusercontent.com/89324173/168190166-cb1928b4-846f-4378-8893-cf2a6ca0d214.png)
