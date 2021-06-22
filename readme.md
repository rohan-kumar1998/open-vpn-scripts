# Automate login and disconnecting of openvpn connections

## TO SETUP

<ol>
<li>Make sure you have expect installed 
  <ol>
<li>sudo apt-get install expect</li>
</ol>
</li>
<li>modify the openvpn_login.exp with your login credentials</li>
<li>save both files in home directory</li>
<li>Grant the following permissions
<ol>
<li>chmod +x openvpn_disconnect.sh</li>
<li>chmod +x openvpn_login.exp</li>
</ol></li>
<li> Done!! </li>
</ol> 

## To RUN
### $./openvpn_login.exp
- to login 
- if you have 2 factor auth then, you only need to provide 2 factor auth<br> 
### $./openvpn_disconnect.exp
- to disconnect 

