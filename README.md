# VoIP-Configration

#Voip Configration and Two Servers Conection in FreeBSD




service asterisk restart

asterisk -rx "core reload"

#after went to asterisk -rcv we have to type this command to reload the sip file

module load chan_sip.so
