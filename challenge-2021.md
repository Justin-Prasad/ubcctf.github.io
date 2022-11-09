--- 
layout: default
title: 2021 Beginner Challenges | CTF @ UBC 
---

Maple Bacon Beginner Practice
---

**NOTE**: All flags will begin with either the prefix `maple{` or `flag{`.

**NOTE**: These are **practice** challenges and are **not part of mapleCTF**! However they are good practice for challenges you might see during the competition

# Reversing

x86 binary

```
8b64240844464c614731db4331fd6681ff676c751d31fe81fd541840
1a7513c1ef106681ff6167750981fe1c1f165475014b31c040cd8090
```

# Pwn

- [Source exe](https://drive.google.com/file/d/15mBjhZ2czhF4d0cTBkW4ZAHd5_lVp4pw/view?usp=sharing)

- [Source code](https://drive.google.com/file/d/1op6YplcAflHZzy3bIugVVoJJOachG4fd/view?usp=sharing)

# Crypto

Stack exchange says everyone uses AES-GCM, but I don't need the tag so I'll just use CTR

- [gen.py](/assets/challenges/beginner-crypto/gen_no_comments.py)
- [secret.enc](/assets/challenges/beginner-crypto/secret.enc)

For complete newcomers, I would recommend giving this [companion guide](/2021/08/beginner-crypto/) a read, it covers some background and gives you the gist of how this challenge is solved

# Forensics

There's nothing here... or is there?
<!-- Hey, you're close! But there's nothing in the HTML comments either... maybe there are other comments you can find? -->

[//]: <> (Nice! flag{M@pl3Syrup} )
