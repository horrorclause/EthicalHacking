# Ethical Hacking #

Resources for learning more about ethical hacking.

<ul>
  <li><a href="https://github.com/Hack-with-Github/Awesome-Hacking">Awesome-Hacking: A Massive Repo With Hundreds of Resources</a></li>
</ul>

### BlackHat 2022 Slides and Presentations:

<li>https://t.co/ljdzCJRHB7</li>

<br />

## :books: Resources for Learning More ##

<ul>
  <li><a href="https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf">NIST SP 800-53 (Security and Privacy Controls for Information Systems and Organizations)</a></li>
  <li><a href="https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-115.pdf">NIST SP 800-115 (Techinical Guide to Information Security Testing and Assessment)</a></li>
  <li><a href="https://csrc.nist.gov/publications/sp">NIST Computer Security Resource Center</a></li>
  <li><a href="https://pauljerimy.com/security-certification-roadmap/">Security Certification Roadmap</a></li>
  <li><a href="https://nmap.org/book/toc.html">NMAP Network Scanning Guide</a></li>
  <li><a href="https://www.ipaddressguide.com/cidr">CIDR to IPv4 Conversion</a></li>
  <li><a href="https://attack.mitre.org/">MITRE ATT&CK</a></li>
  <li><a href="https://www.lockheedmartin.com/en-us/capabilities/cyber/cyber-kill-chain.html">Lockheed Martin's Cyber Kill Chain</a></li>
  <li><a href="https://tryhackme.com">TryHackMe - Excellent Learning Paths and CTFs</a></li>
  <li><a href="https://portswigger.net/web-security">PortSwigger Academy - Learn all about BurpSuite and Web Attacks</a></li>
  <li><a href="https://pentesterlab.com/exercises?dir=desc&only=free&sort=published_at#">PentesterLab- Exercises</a></li>
  <li><a href="https://crackmes.one/">Crackmes - Practice Reverse Engineering</a></li>
  <li><a href="https://owasp.org/www-project-top-ten/">OWASP Top Ten Web App Security Risks</a></li>
  <li><a href="https://manpages.ubuntu.com/manpages/bionic/man1/crunch.1.html">Crunch - Make Custom Wordlists (w/Examples)</a></li>
</ul>

<br />

## :robot: Solve The Challenges ##

<ul>
  <li><a href="https://overthewire.org/wargames/">OverTheWire: Wargames</a></li>
  <li><a href="https://picoctf.org/">picoCTF Challenges</a></li>
  <li><a href="https://www.hackthebox.com/">Hack The Box: Hacking Training</a></li>
  <li><a href="https://hackthissite.org/">Hack This Site - Free and Legal Hacking Training Ground</a></li>
  <li><a href="https://www.hackerone.com/">HackerOne</a></li>
  <li><a href="https://www.hackerrank.com/dashboard">HackerRank</a></li>
</ul>

<br />

## :pencil2: Handy Online Tools ##

<ul>
  <li><a href="https://www.hackers-arise.com/ultimate-list-of-meterpreter-command">Ultimate List of Meterpreter Commands</a></li>
  <li><a href="https://www.tutorialspoint.com/bypass-anti-virus-using-veil-framework">ByPass Antivirus Using Veil Framework</a></li>
  <li><a href="https://crackstation.net/">Crackstation - Online Password Cracking</a></li>
  <li><a href="https://www.boxentriq.com/code-breaking/cipher-identifier">Cipher Identifier</a></li>
  <li><a href="http://rumkin.com/tools/cipher/">Multiple Cipher Tools & Crackers</a></li>
  <li><a href="https://gchq.github.io/CyberChef/">CyberChef</a></li>
  <li><a href="https://www.base64decode.org/">Base64Decode - Base64 Decoder/Encoder</a></li>
  <li><a href="https://stylesuxx.github.io/steganography/">Online Steganography Tool</a></li>
  <li><a href="https://md5decrypt.net/en/">MD5 Online Encrypt/Decrypt Tool</a></li>
</ul>

<br />

## :lying_face: Social Engineering is The Way To Go ##

<ul>
  <li><a href="https://thispersondoesnotexist.com/">This Person Does Not Exist - AI Generated Portraits</a></li>
  <li><a href="https://www.fakenamegenerator.com/">FakeNameGenerator - Create a Fake Identity</a></li>
  <li><a href="https://thisresumedoesnotexist.com/">This Resume Does Not Exist - AI Generated Resume</a></li>
  <li><a href="https://10minutemail.net/">10 Minute Mail - Email Address That Lasts 10 Minutes</a></li>
  <li><a href="https://www.ssn-verify.com/generate">SSN Generator</a></li>
  <li><a href="https://thisxdoesnotexist.com/">This X Does Not Exist</a></li>
</ul>

<br />

## :mag_right: OSINT All Day Everyday ##

<ul>
  <li><a href="https://pimeyes.com/en">PimEyes - Powerful Reverse Image Search</a></li>
  <li><a href="https://wigle.net/index">WiGLE - Wireless Network Mapping</a></li>
  <li><a href="https://www.shodan.io/">Shodan - Search Engine for Network Connected Devices</a></li>
  <li><a href="https://whois.domaintools.com/">WhoIs Lookup</a></li>
  <li><a href="https://hunter.io/">Hunter - Find Email Addresses and Their Spelling Format</a></li>
  <li><a href="https://phonebook.cz/">PhoneBook.cz - Search Domains, Email Addresses, URLs in Leaks</a></li>
  <li><a href="https://intelx.io/">IntelX - Search Leaks</a></li>
  <li><a href="https://map.snapchat.com/">SnapMap - Geographic Map of SnapChat Activity</a></li>
  <li><a href="https://www.geocreepy.com/">GeoCreepy - Geolocation OSINT Tool</a></li>
  
</ul>

<br />

## :pushpin:Helpful Hints ##

### Create Great Looking HTML Reports of Your Nmap Scans ###

Output your nmap scans as nice looking reports by outputting the scan results as xml, and then converting it to html.

Run your scan, and make sure you use the "Output to XML" flag "-oX" followed by the filename:

```
nmap -vv -sS -A -T3 -oX scanResults 172.16.1.4
```

Next, make sure you are in the same directory as the xml file, and use "xsltproc" to make to conversion to html:

```
xsltproc scanResults -o scanResults.html
```

<br />

If you open up the folder where the file is located you can see the xml and html files there:

![image](https://user-images.githubusercontent.com/10188810/178209896-16027624-ea66-4781-8a3e-7f139cfafa0a.png)

<br />

Double-click the html file, and it will open your report in your browser:

![image](https://user-images.githubusercontent.com/10188810/178210058-b135c85a-01cc-48ce-8501-7ee4e776d5f1.png)

<br />
