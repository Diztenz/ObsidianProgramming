Simple tool you can use to trouble shoot network activity.
Check to see if network i

ping ip address
ping domain name (yahoo.com)
ping utility sends 4 data packets and gets the reply
repies are called echo reply requests
tells you what's happening with the server we pinged.
if you don't get a reply could mean
* no network connectivity
* could be a firewall

If not all 4 data packets return it could mean:
* packet loss
* network congestion
* faulty hardware bad cables or wiring
* bad network card
* bad connections
* bad modem

Destination host unreachable:
* route to destination can not be found
* router has no information on how to route data to destination
* host server is down
* my computer not connected to network.

If someone tells me they have no internet connection:
* I would use ping utility
* before checking modem or router or cable connections
* simple ping test
* ping yahoo.com (pinging domain name also testing domain resolution issues)
* if ping is successful I know we are connected to the internet then the problem is software (browser) not hardware.
* only time you need to check hardware is if ping was not successful.
* you can also check to see if your network interface card is working correctly.
* use a loop back test ip address 127.0.0.1 or ping localhost (same thing)
* if you get a return that means your network card is working properly
* if not successful then it means there's a problem with your network interface card 

Ping command can also be used to test DNS by using domain name on the ping.

It also verifies DNS is working correctly.

Ping request could not find host yahoo.com. Please check the name and try again.  If you spelled everything correctly then it could mean a DNS issue.

Next thing to do is ping the ip address instead.

type in google's ip 8.8.8.8 if you get a return then it confirms it's a DNS issue.

you can try to flush your DNS by typing.
ipconfig /flushdns

ping command can also be combined with other subcommands called switches.
switches are used to alter the parameters of the ping utility

full list
ping /? for list of switches.