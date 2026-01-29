All images have custom IP address configurations and custom services which run on boot. They are equipped with minimal debian with the following packages: PREEMPT-RT, SuperCollider(with the instrument listed in the images' name), PTP and alsa-utils.

# Installation guide
1. Pick the image that has the correct instrument in the file name and download.
2. Use an imager of your choice and write the image to the desired hard drive/SSD.
3. Plug the hard drive into the soon-to-be node.
4. Boot it up! The username is the hostname of the node and the password is 31_10_25 for all modules.
5. Configure PTP, the configuration varies for the interface name and the NICs that support hardware PTP and NICs that do not. It is only one command.
