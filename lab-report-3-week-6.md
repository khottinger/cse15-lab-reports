## LAB REPORT 3
---

## Streamlining ssh Configuration
---

# Creating `.ssh/config` file

The first step in streamlining my login was to create a `.ssh/config` file. I did not have one originally so I created one using Text Editor and input
all of my information. I did **not** have to add the `id_rsa` file, as the file I set-up worked the first time.

![Image](lr3.1.png) 


# Logging In!

With the simple command of `ssh ieng6` I was able to login without using my password. This saved me lots of time in my skill demo video!

![Image](lr3.png)

# Quick `scp` Demo

I `scp` over a random java `DemoSend.java` file to my server using my alias. I was not prompted for a password and upon logging in and hitting `ls` my file had 
been copied over successfully

![Image](lr3.4.png)
