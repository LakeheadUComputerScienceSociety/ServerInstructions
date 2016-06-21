Requesting Access
=================

Right now access is manually granted. All you will need to do to request acces in to provide Danny Kivi with your SSH Public Key and he will add you as a developer on the server. 

If you aren't sure what SSH Keys are, click [here](/SSH/Primer.md) for a quick primer on how it works.

If you aren't sure how to generate an SSH key, click on the appropriate instructions below

[Windows Instructions](/SSH/Windows.md)
[Unix/OSX Instructions](/SSH/Unix.md)

Connecting
==========

Once you have sent Danny your Public SSH Key and he has confirmed your account is set up. You can access the server in the following ways:

**Windows**

Use an SHH client and as the host enter `<your-username>@lucss.ca` and you will be using port 22. I recommend [Putty](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html) to do this.

**OSX and UNIX**

Simply run `ssh <your-username>@lucss.ca` and you should be good to go!