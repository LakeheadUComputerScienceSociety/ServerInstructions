Windows SSH Instructions
========================

Oh boy, here we go

You will need the following programs:

 - PuTTYgen
 - Pageant
 - PuTTY (you don't really need this but you will most likely need it to SSH into the server anyways)

You can get all these [here](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html)

####Generating Your SSH Keys

1.  Start PuTTYgen
2.  Make sure you have "SSH-2 RSA" selected near the bottom with 2048 bits being generated
3.  Click "Generate"
4.  WIGGLE LIKE YOUR LIFE DEPENDS ON IT
5.  Enter a nice name in the "Key Comment" field. IE "DannyLaptop"
6.  Enter a password you will remember in the "Key Passphrase" field and confirm it\
7.  Click save public key and save private key. Typically the default convention for these is id_rsa (no file extension) for the public key, and id_rsa.ppk for the private key. You will want to save these somewhere you will be able to find them. Personally I create a folder and save them in C:\Users\Danny\.ssh because it lines up with where they would be stored on a linux machine.
8. Either copy and paste your public key to Danny for server access, or send him the public file itself.

####Loading Your SSH Key

Once you have them saved. Run Pageant. The program will live in your system dock as a little computer with a spy hat. Right click it and select "Add Key". You will then navigate to your private key (.ppk file) and load that. Unfortunately, there is no way I know of to load these keys automatically on startup, I have pageant run at windows startup and then I add my keys manually from there. 

#### Connect Through SSH

Open up Putty and for the host enter `<your-username>@lucss.ca` and make sure the port is set to 22. You should automatically authenticate with the server.

