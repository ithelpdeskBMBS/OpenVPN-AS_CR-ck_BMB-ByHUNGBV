# OpenVPN-AS_2.14.3-Py3.12.3
Cr4ck
After installation is complete, copy the " pyovpn-2.0-py3.12.egg" file to the following path: /usr/local/openvpn_as/lib/python/
UPDATE: openvpn-as 3.1.0 & 2.14.3
Then run the following command to reinstall the server.
git clone https://github.com/ithelpdeskBMBS/OpenVPN-AS_2.14.3-Py3.12.3.git
cp "/root/OpenVPN-AS_2.14.3-Py3.12.3/Cr4ck/openvpn-as3.1.0-Py3.12/pyovpn-2.0-py3.12.egg" "/usr/local/openvpn_as/lib/python"
rm -rf /usr/local/openvpn_as/lib/python/_\_pycache_\_/*
systemctl restart openvpnas
Done
Change your password if you forget your OpenVPN (administrator) password.
sudo /usr/local/openvpn_as/scripts/sacli --user openvpn --new_pass 'Admin@2026' SetLocalPassword


