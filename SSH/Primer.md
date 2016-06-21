SSH Primer
==========

> **Disclaimer**
> 
> I (Danny Kivi) am not an expert in SSH keys. At all. I have a
> functional knowledge of them and it has been enough to get me by. This
> is a quick blurb to introduce those unfamiliar with the concept of SSH
> keys.

-------

Everyone is familiar with the concepts of passwords and most are familiar with the pains of managing many secure passwords and the struggles of keeping them secure through data leaks of popular websites. A better way to handle authentication is with SSH keys. And in this case, it is the only way to handle authentication since I have turned off passwords on the server.

SSH keys work in a pair: a private key, and a public key. They are basically really long strings that tell each other that you are the person you say you are, and that you can have access. Your public key sits on the server and is associated with your user account, and when you attempt to access the server through SSH, it will compare the private key sitting on your computer with the public keys on the server and will use that to determine who you are. 

If you are interested in learning more about SSH Keys, [here](https://help.ubuntu.com/community/SSH/OpenSSH/Keys) is a great resource with a lot of easy to follow information and some instructions on setting it up on a linux machine

For my tutorials, see below:

[Windows Instructions](/SSH/Windows.md)
[Unix/OSX Instructions](/SSH/Unix.md)