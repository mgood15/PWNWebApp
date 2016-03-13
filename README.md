PWNWebApp

The PWNWebApp repository holds the code used to create the PWN Service. This service was primarily invented due to my desire to learn Ruby as well as solidify/understand more programming concepts that I feel I do not currently grasp very well.

What is PWN?

If you know about Metasploit, then PWN may sound familiar. My goal is to actually create an interface, through a PWN service web portal, where users can request modules be run on their network to test systems. Currently, my first goal for the project is to achieve this with an SSH password bruteforcer and then launch from there as time goes on.

What capabilities does it have?

Well, so far, not a whole lot. My goal is to create an SSH password bruteforcer that uses Ruby’s multithreading to speed up the process. This bruteforcer can be accessed by a user through the web interface that I am creating. The user can then select an IP/hostname or a range of IPs to test the bruteforcer on. The user will be restricted to only the available IPs on their own network.

From there I plan to use the information from the user and call upon the Ruby script on the back-end. It will perform the bruteforce and dump the results into an email report that will then be emailed to the user at a specified email upon the conclusion of the test.

What is in this repository?

So far the front-end will be in this repository. Until I am ready to combine the front-end and the back-end, the Ruby code for the SSH module (and future modules) will be located in the PWN repository.
