# WHAT IS THIS? #
As you know, the output of iwlist is not well printed and difficult to read. This parser will help re-structure the output of iwlist and print it nicely in a table.

This modified version produce more output than the original version, written by _Hugo Chargois_.

# HOW TO USE? #
This receives output from stdout from iwlist, so use it as follow:
(Assume that the file iwlistparse2.py is in your current working folder: ./)
  1. Open Terminal
  1. Type: **`sudo iwlist wlan0 scan | ./iwlistparse2.py`**
  1. or type: **`sudo iwlist wlan0 scan | ./iwlistparse2.py | egrep "Name|Address|Quality|Signal|Frequency|Ch|Mode|Encryption|Last Beacon|Bit Rates|*"`** to have column titles colored.

Change _**wlan0**_ to your wireless card, and change _**./**_ to point to the directory where _iwlistparse2.py_ is saved.

# COPYRIGHT #
Please see the code for copyright notice.

### Thank you. ###