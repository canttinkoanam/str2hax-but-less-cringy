# str2hax but less cringy
A less cringy version of Fullmetal5's str2hax, an exploit for the Wii that allows it to run the [HackMii Installer](https://bootmii.org/download) without neither an SD card nor the Internet Channel.
If you're wondering why it's less cringy... well, the official version by Fullmetal5 shows a picture of Rainbow Dash, a character from My Little Pony \*vomiting sounds\* while this version replaces that image with the BootMii logo. And the background is white. That's it. Everything else is the same.
## Building
From [Fullmetal5's GBATemp Post](https://gbatemp.net/threads/a-channel-less-sd-less-entry-point-str2hax.523210/#post-8377477):

1\. Copy your payload (MUST BE VERY SMALL, you should probably just use the [network loader](https://github.com/Fullmetal5/WiiNetworkLoader)) into the payload folder

2\. Run ./make_is.sh YOUR_PAYLOAD.elf

This will give you a payload.png

3\. Run ./create.sh in the main directory

4\. It will create a site.zip file with everything you need. (Apache is required for the redirects)

5\. To test this you will need to setup a dns server (dnsmasq works great) and redirect cfh.wapp.wii.com to your site.

## NOTE
This is not meant to insult Fullmetal5. It's just a version of str2hax without the Rainbow Dash image. That's literally it.
