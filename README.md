# IP-Blocker
Auto block IPs from DDoS attacks automatically by parsing access log files or add your own IPs to block or allow


<h1>Install:</h1>  
<ol>
<li>sudo mkdir /opt/autoban</li>
<li>sudo cp autoban.sh /opt/autoban/</li>
<li>sudo chmod +x /opt/autoban/autoban.sh</li>
<li>sudo cp autoban-initd /etc/init.d/autoban</li>
<li>sudo /sbin/chkconfig autoban --add</li>
<li>sudo /sbin/chkconfig autoban on</li>
</ol>


<h1>Start service:</h1>
 <ul>
<li>sudo service autoban start</li>
</ul>
<h1>Stop service:</h1>
<ul>
<li>sudo service autoban stop</li>
</ul>
 
<h1>Restart service:</h1>
<ul>
<li>sudo service autoban restart</li>
</ul>
