# dns-config
<p align="center">
<img src="https://imgur.com/jbehg2S.png" alt="dns overview"/>
</p>

<h1>DNS - Prerequisites and Installation</h1>
This tutorial outlines the installation of A DNS on domain controller.<br />

<h2>Installation Steps</h2>

<p>
<img src="https://imgur.com/jcdb4RX.png" height="80%" width="80%" alt="Steps 1"/>
</p>
<p>
Were first gonna use our cilent vm to see if "mainframe" will ping which it wont so then we try "nslookup" and nothing appears.
</p>
<br />

<p>
<img src="https://imgur.com/zbEzARQ.png" height="80%" width="80%" alt="Disk Sanitization Steps 2"/>
</p>
<p>
In order to get "mainfram" to pop up we have to search the DNS application in windows and create a DNS called mainframe for it which it will be private IP address of the DC.
</p>
<br />

<p>
<img src="https://imgur.com/N6EYRqM.png" height="80%" width="80%" alt="Disk Sanitization Steps 3"/>
</p>
<p>
Going back to the cilent computer we ping and do nslookup to see if main frame pops up and it does !
</p>
<br />

<p>
<img src="https://imgur.com/kA2B308.png" height="80%" width="80%" alt="Steps 7 "/>
</p>
<p>
Now lets create CNAME(www.google.com) which we will use "search" instead of mainframe.
</p>
<br />

<p>
<img src="https://imgur.com/lA3KDQY.png" height="80%" width="80%" alt="Steps 7 "/>
</p>
<p>
ping "search" and we will see google.com pop up !
</p>
<br />
