----------------------------------------------------------------------------------------------------------------------------------

https://overthewire.org/wargames/bandit/


SSH Information
Host: bandit.labs.overthewire.org
Port: 2220


-------------------------------------------------Bandit0----------------------------------------------------------------------

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

//Bu seviyenin amacı ssh ile login olman. Bağlanıcağın host bandit.labs.overthewire.org ve buraya 2220 portundan bağlıcaksın. Kullanıcı adı bandit0 ve şifre bandit0. Bağlandığında level 1 sayfasına giderek level 1'i nasıl geçilebileceği bul. 

pass: bandit0


--Kullanıan kodlar ve Açıklamalar

ssh bandit0@bandit.labs.overthewire.org -p 2220 // secure shell bağlantısı atmaya ayrayan kod.

ssh kullanıcı_adi@hedef_site/ip -p <port>

SSH değiştirlmediği sürece bir sistemde 22 numaralı portta çalışır. Eğer farklı bir portta çalışıyor ise "-p" parametresi ile belirtilmesi gerekir.
