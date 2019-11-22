# Kali Setup Script

Modified the awesome blacklanternsecurity setup script a bit and added tools from the dcarlin kali install script

Prepares Kali for a pentest by enabling session logging, installing tools, and making common configuration changes

## One-liner:
(don't forget to reboot after the script finishes :)
~~~
curl -k -s https://raw.githubusercontent.com/tylersp7/kali-setup-script/master/kali-setup-script.sh | bash
~~~

## Full feature list:

1. Saves record of terminal sessions
	- Including ALL OUTPUT (saved to ~/Logs)
1. Installs the following:
	1. CrackMapExec (from GitHub)
	1. Impacket (from GitHub)
	1. Bloodhound (from GitHub)
	1. patator (network brute-force tool)
	1. bettercap
	1. docker
	1. Firefox (official non-ESR version)
	1. golang (plus environment)
	1. zmap
	1. htop
	1. Remmina
	1. gnome-screenshot
	1. realtek-rtl88xxau-dkms (ALFA wireless drivers)
	1. i3 + Gnome desktop environment
1. Updates system
1. Removes gnome-software
1. Disables animations
1. Disables auto-lock
1. Enables tap-to-click
1. Initializes Metasploit database
1. Cleans up favorites menu
