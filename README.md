# OpenVPN-AS_2.14.3-Py3.12.3 <br>
Cr4ck UPDATE: openvpn-as 3.1.0 & 2.14.3 <br>
After installation is complete, copy the " pyovpn-2.0-py3.12.egg" file to the following path: /usr/local/openvpn_as/lib/python/ <br>
Then run the following command to reinstall the server. <br>
git clone https://github.com/ithelpdeskBMBS/OpenVPN-AS_2.14.3-Py3.12.3.git <br>
cp "/root/OpenVPN-AS_2.14.3-Py3.12.3/Cr4ck/openvpn-as3.1.0-Py3.12/pyovpn-2.0-py3.12.egg" "/usr/local/openvpn_as/lib/python" <br>
rm -rf /usr/local/openvpn_as/lib/python/_\_pycache_\_/* <br>
systemctl restart openvpnas <br>
Done <br>
Change your password if you forget your OpenVPN (administrator) password. <br>
sudo /usr/local/openvpn_as/scripts/sacli --user openvpn --new_pass 'Admin@2026' SetLocalPassword <br>

![Illustrative image](https://github.com/ithelpdeskBMBS/OpenVPN-AS_2.14.3-Py3.12.3/blob/main/Screenshot%202026-02-13%20142437.png)

