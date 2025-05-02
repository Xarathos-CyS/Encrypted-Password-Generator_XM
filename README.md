# Xarathos MONOCHROME - EPG; An Encrypted Password Generator

Hello! This is a preview of what XM-EPG is. This is a closed source program and is not intended for public distrubution.
This Repository is merely a preview page for if you want information about the program. It will not contain any helpful information but is simply a gallery for screenshots of the program.

∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞

Most often than not, people use weak passwords for the services they sign up with (Google, Discord, Instagram, etc.)
and it is very easy to crack these passwords causing a lot of harm, personal data is leaked, accounts get hacked, and so on and so forth.

That is the purpose of XM-EPG; it is a simple Python written CLI based program but under the hood uses sophisticated methods to encrypt the your weak passwords with a combination of it and a passphrase, turning them from `password123` to `@iH0)=kB38*02jM-5H3o9hy58T8rpo40-dlkjcHKJjk` (not an actual demo) in less than a minute!

∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞

This program has been bundled and compiled to a .exe for extra obscurity and security:

![image](https://github.com/user-attachments/assets/fa4d43b2-729d-49ed-8123-e891f245d5f9)

To ensure a plug-and-play experience to the user! you dont need to install the libraries, pip, or even python to run this program!

∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞

Functionality was prioritized over the looks and UI, and since it is CLI based there isnt much that can be done, yet i've done my best to make the experience smooth and consistent by adding a splash screen:

![image](https://github.com/user-attachments/assets/cce1e244-43a8-412d-8010-fe5ad1907cf4)

and dynamic headers throughout the different screens:

![image](https://github.com/user-attachments/assets/dea9c027-9016-4c45-942f-26415e301ec7)

![image](https://github.com/user-attachments/assets/e07115b5-be07-4e70-ba0c-4529750f6a5b)

∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞

As you can see, not many features meet the eye from first glance, however there's a lot going on under the hood. to clear it up, here's a minimal list of features as of v1.0.0:

- Encryption & Scrambling of passwords using three modes:

  a. XES-Calypso

  b. XES-Dione

  c. XES-Hyas


![image](https://github.com/user-attachments/assets/c4d5a005-7cd1-4ca0-b043-783a4ef3dac9)


  XES (Xarathos Encryption System) is a proprietary base encoder + encryption algorithm i have invented since IETF standards did not match my use case; i needed extra obfuscation that RFC 4648 could not provide, and extra flexibility that b85 could not either. And with that XES was created.
  v1.0.0 was only an encoder but was later upgraded to actually encrypt and use a better algorithm for scrambling in v2.0.0

- Full customization of the final password's charset - this was the original purpose of XES, outputting different combinations of ASCII supported charsets.
- Decryption of passwords using any of the three modes.
- Exporting QR codes for moving the encrypted passwords across devices.
- Generating, saving and loading scramble tables - both for viewing and possible recovery in case of a lost passphrase.

∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞

Heres a demo of the encrypted password screen:

![image](https://github.com/user-attachments/assets/462fc63c-05a7-42db-adc7-78802d2780cf)

You can try decrypting that, goodluck, because you can't. i have spent nearly a week crafting the algorithm to turn it to what you see in the screenshot. I am fully confident in this program's capabilities as well as mine and am very comfortable sharing that screenshot as i know nobody will be able to figure out what it does to give that output during our lifetimes.

This is because of the proprietary methods this program uses, you can generate random passwords from any website you like, but you will never be able to replicate this algorithm, and thats for good reason! consider having this program in your hands a million steps further in staying secure, thats what my programs aim to do!

∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞

That is about all i can share about this program. Again, this is a closed source program that may never be shared except for a few select of people for the purpose of security. the code is already encrypted and obfuscated so that even the user can never be able to view what the code really does, this may create a lot of suspicion which is the reason behind this program being closed source, i only share it to people who i can trust and ones who can trust me.

If you personally know me or just want a copy of this program for yourself, contact me through `xarathos.business@gmail.com`.

Thank you for reading!

~ Xarathos

∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞∞

