.. title: Setting up multiple laptops
.. slug: setting-up-multiple-laptops
.. date: 2019-04-23 11:52:26 UTC+10:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text

I need to be able to run multiple laptops so that I can switch between them fairly seamlessly. This is for everyday reasons (I can use a small laptop when I'm moving around a lot; a larger one to do research work)  and for less-everyday ones - I can easily run up a new laptop with little overhead; can do major upgrades etc.

Right now, scorpius (a Dell Precision with ubuntu preinstalled) is not doing wireless, and I suspect that an upgrade broke it. I need to do a factory reinstall and then upgrade from there to see what happens. So I need another laptop running email at least!

I have a couple of old small laptops available - an oldish HP dm1 and an old Thinkpad X201. I want to get one or both of them up and running. Possible distros are vanilla Ubuntu, KDE Neon (ie Ubuntu LTS with KDE Plasma desktop), Lubuntu, BunsenLabs ...

to do email:
IMAP: thunderbird talking to all IMAP accounts, including Gmail and Fastmail
thunderbird's local storage needs to be synced - this is currently done with SpiderOak, but I find spideroak a bit opaque, so it's hard to be absolutely sure it's working. It would be better to run my own sync mechanism with nextcloud (?), but this is a todo. So for now, spideroak is needed.
Local email storage can be copied from one machine to another by sneakernet, and then synced through spideroak, to save having to download everything!
Exchange: Hiri works well to talk to my westernsydney.edu.au work email. Well enough that I'll pay for it! It doesn't really do local storage in an easily-accessible way.
VPN: scem.westernsydney.edu.au email requires openVPN to send email - install and test

todo list:
- transfer local email storage
- spideroak; sync local email
- thunderbird; set up accounts including local storage
- hiri
- openvpn; test email send from scem
  

