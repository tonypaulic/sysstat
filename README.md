sysstat,sh

An xfce4-genmon-plugin that displays basic system operational information:
   - cpu - current cpu usage
   - mem - current memory usage
   - hd - current drive usage

On the panel itself 3 numbers are displayed: (cpu mem hd).

The tooltip displays the top 5 cpu and memory intensive processes (summed up per process so you don't have multiple entries for the same process),
  and the current usage of the main hard drve.

Feel free to edit the script for your specific configuration.

TODO: 
  - Consider more than one drive in the system.
  - Make number of processes displayed in tooltip conigurable.
