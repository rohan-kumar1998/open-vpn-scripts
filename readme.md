Automate login and disconnecting of openvpen connections

TO SETUP
1 - Make sure you have expect installed 
  sudo apt-get install expect 
2 - modify the openvpn_login.exp with your login credentials 
save both files in home directory 
3 a - chmod +x openvpn_disconnect.sh
  b - chmod +x openvpn_login.exp 
4 - Done!! 


To RUN
$./openvpn_login.exp 
- to login 
- if you have 2 factor auth then, you only need to provide 2 factor auth 
$./openvpn_disconnect.exp
- to disconnect 

