# USHA-2048

## About
USHA-2048 is a 2048-bit hashing algorithm created by AK/werdane. This is designed to help corporations, small businesses and individual users to keep their
databases safe from unauthorized users. Many people have their passwords floating out there on the internet due to companies and businesses not having a strong encryption for their user's personal information such as emails, billing, passwords, etc.

I also designed the algorithm because I literally have too much free time on my hands. I hope this is good enough to protect your or your consumers' passwords.

## Usage
Run commands in terminal.
```bash
git clone https://github.com/werdane/USHA-2048
cd USHA-2048
```

Create a new python file
```py
from usha import usha2048

print(usha2048("password1234"))
```
## Extra security measures
To make it even harder for hackers to crack these hashes, you can try salting the passwords, salting is a technique in which you add random letters to the passwords
before passing them through a hashing algorithm, this makes it harder for a password hash to be cracked via brute force or dictionary attacks. 

Please, I don't need irresponsible companies ruining my operational security.

**Created by AK / Werdane**
