 <h1>VoIP-Configration</h1>

<h1>Voip Configration and Two Servers Conection in FreeBSD</h1>



<h2>How to install</h2>

pkg search asterisk 

#after came the packages and select latest version and

pkg install "Latest package of asterisk name"

<h2>After Configure</h2>

service asterisk restart

asterisk -rx "core reload"

#after went to asterisk -rcv we have to type this command to reload the sip file

module load chan_sip.so
