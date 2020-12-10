# security-testing
Security testing with different platforms

Security testing is a most important testing is current days. Now a days software quality assurance engineers are also need to test security for their project. 

Here i will add list of checking with suggested tools and demo report on hackerone.

| Sl|Name Of the test  | Tools  |  Demo report|
|--|--|--|--|
|1  |Open Redirect|An http parameter may contain a URL value and could cause the web application to redirect the request to the specified URL. By modifying the URL value to a malicious site, an attacker may successfully launch a phishing scam and steal user credentials. Because the server name in the modified link is identical to the original site, phishing attempts have a more trustworthy appearance. Tools https://github.com/stanislav-web/OpenDoor |https://hackerone.com/reports/504751 https://hackerone.com/reports/692154  https://hackerone.com/reports/683298 https://hackerone.com/reports/753399|
