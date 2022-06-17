<h4>Installation and requierments:</h4>

<p>you must have conky installed either from your package manager or from Github. You should also have a compositor like picom for the transparency
  effect. Otherwise it will be plain black!
  
place the conky.conf in this path:
~/.config/conky/conky.conf </p>

<h4>Autostarting</h4>

<p>add it to your .xinitrc or use your DE's autostart function.
you can simply type conky in your terminal to launch it </p>

<h4>Configuration</h4>
<p>If you have less CPU threads than 12 this wont work properly until you either add or remove the lines about the extera cpu threads.
run nproc in a terminal to see how many cores and threads you have (may need sudo)

this is a minimal conky config that I wrote for my DWM session. There is nothing fancy about it. It just monitors the system resources and reports in a simple visual manifestation. 
  
enjoy </p>
![image](https://github.com/wolandark/simple-conky/blob/main/conky.png)
![image](https://user-images.githubusercontent.com/89324173/168190166-cb1928b4-846f-4378-8893-cf2a6ca0d214.png)
