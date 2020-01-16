Speeding up Linux disk encryption
=================================================

* Speaker   : **Ignat Korchagin**
* Available : **any day**
* Length    : **60 minutes**
* Language  : **English**

Description
-----------

Encrypting data at rest is a must-have nowadays. And if you use Linux, LUKS/dm-crypt is the usual go-to solution. However, as the storage becomes faster, the IO latency, introduced by dm-crypt becomes noticeable.

One might blame encryption being expensive, but if you look into dm-crypt source, there is a lot of other code, which might contribute to the problem. By removing some code we were able to speed up the IO speed from an encrypted device by 200%-300% depending on the block size.

Speaker Bio
-----------

Ignat is a security engineer at Cloudflare working mostly on platform and hardware security. Ignat’s interests are cryptography, hacking, and low-level programming. Before Cloudflare, Ignat worked as a senior security engineer for Samsung Electronics’ Mobile Communications Division. His solutions may be found in many older Samsung smart phones and tablets. Ignat started his career as a security researcher in the Ukrainian government’s communications services.

Links
-----

* Blog: https://pqsec.org/
* Company: https://www.cloudflare.com/
* GitHub: https://github.com/ignatk
* Photo: https://hacktivity.com/wp-content/uploads/2019/07/ignat_profile-390x390.jpg

Extra Information
-----------------

Some talks:

* Go as a scripting language in Linux: https://youtu.be/k7oosn5HrKk
* Live-Patching Weak Crypto with OpenSSL Engines: https://youtu.be/QJtiOhPEjtU
* The Definitive Guide to Make Software Fail on ARM64: https://youtu.be/ZhIxQY-WwgQ
* Exploiting USB/IP: https://youtu.be/EjYKF-xG_VY
