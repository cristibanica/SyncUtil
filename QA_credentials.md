# QA Server Credentials

### ## # Serverele sunt majoritatea fie pe portainer.sync.ro, fie pe esxi1.sync.ro.



### Sharepoint Credentials

https://syncrosoftcv.sharepoint.com/


User/Pass: Test@syncrosoftcv.onmicrosoft.com	Oxygen18
User/Pass: Test2@syncrosoftcv.onmicrosoft.com	Oxygen18


### Bitbucket Server

http://bitbucket.sync.ro:7990/


User/Pass: test 	gh678j
User/Pass: qa	    gh678j


### Perforce Server

portainer.sync.ro:1666


User/Pass: test	    t35t_gh678j
User/Pass: p4admin	t35t_gh678j


### Alfresco 

http://alfresco.sync.ro:8080/alfresco/cmisatom

_Este o masina virtuala pe esxi1.sync.ro cu numele "Cristian's Dedicated Alfresco CE Server"._


User/Pass: test	gh_678j
User/Pass: user	gh_678j


### Filenet

AtomPub Endpoint http://10.0.0.99:9080/fncmis/resources/Service


User/Pass: P8Admin	Stil00
User/Pass: tester	Stil00

_Note: Pentru accesarea server-ului de Filenet, in cazul in care acesta este oprit, se deschide client-ul de vSphere la IP-ul: 10.0.0.4, username: test, pass: gh_678j, apoi se acceseaza masina IBM FileNet P8, se introduce username: P8Admin, Pass: Stil00, si odata ajunsi la desktop folder, se porneste server-ul din primul script: Start P8 Platform._


### Portainer

http://portainer.sync.ro:9000/ - Adresa URL Web


Portainer (Web login)

User/Pass: test	gh678j


Portainer (SSH)

User/Pass: test	    gh678j
User/Pass: syncro	gh678j


### Selenium Grid Edge Node Machine
Pass: Passw0rd!



### Linux based OS'es


CentOS 7
User/Pass: syncro	gh_678jgh_678j

RedHat	
User/Pass: syncro	Administratorroot


### Ubuntu ipV6 only machine Cristi Banica



User/Pass: syncro	syncro


_Cristian's Ubuntu 22.10 GUI - Clean TESTipV6 - can be found in esxi1.sync.ro

The direct ip for SSH connection is : fe80::20c:29ff:fe9e:ac4c_



### Android VM

Pe **ws5.sync.ro** avem un o masina virtuala cu Android9, "Android9-x64".

Se poate accesa direct din browser de aici cu userul "**user**" si parola "**ws5gh678j**" sau chiar din vSphere Client.

_Daca intra in sleep trebuie dat restart._


### Mac Machine to test cross-browser problems
Conexiunea se face prin TightVNC cu parola: **gh678j**
**Hostname**
macos13-vm.sync.ro
**User**
Developer
**Pass**
devel0per

### Man-in-the-Middle Proxy (MITM)
Serverul proxyul MITM ruleaza intr-un container Docker si poate fi folosit setand ca proxy server **test-services.sync.ro**, pe portul **3328**.


### Bitbucket account: 
  user: test@sync.ro
  pass: _oxy_sync_00
  username: sync_test







