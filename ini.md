- GPS data of single person

- any token/password

- personal information? (name in real life, birthday, hometown,...)

list goes on...

Please comment anything you have and make suggestions.

The security issue to all casduer is the most important thing.


# 我们可以做什么
please encrypt your sensitive information before uploading them to the cloud use some end-2-end encrypted message application

For non-expert users, usability is very important. Try:

## Olvid / Signal for encrypted message

- what is [end-to-end](https://en.wikipedia.org/wiki/End-to-end_principle) encrypted?

- Keybase for both message and encrypted storage (like git)

For experts, you can try:

- [git crypt](https://www.agwa.name/projects/git-crypt/)
- [GPG tools](https://gnupg.org/)

  https://gnupg.org/faq/gnupg-faq.html#whats_gnupg
  
# talk with ParaView expert

https://discourse.paraview.org/t/pvserver-security-risk/3582/9

yes, it’s not end-to-end encryption.

I know the most secure messaging app in the world: https://olvid.io/en/

if you want to the higest security help, contact Prof. Michel Abdalla,


> I don’t consider myself an expert in security, so take my statements with a grain of salt. It’s my understanding that the real risk of sending data unencrypted over a network (particularly a WAN), is that it is impossible to control what equipment the data go through, so someone could be snooping the data at any point in the network.

> Even on the local machine, pvserver is pretty vulnerable before the socket connection is made, which is the whole point of the connect-id conversation we have been having on this thread. However, once the connection is made (let’s say local process to local process for the purpose of this discussion) then the OS itself should protect your program’s memory and the memory that goes between the two processes that you own from anyone with a different account (assuming they don’t have root access). If an adversary has managed to breach the OS’s protections to get to this information, then they already “own” your computer, and getting access to a pvserver is the least of your problems.

# Ref:

https://github.com/discourse/discourse/blob/master/docs/SECURITY.md

https://cryptobib.di.ens.fr/

https://www.hacker101.com/resources#2

https://github.com/Hacker0x01/hacker101

