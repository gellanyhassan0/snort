# snort

<code>apt-get install snort</code><br>

<code>sudo snort -T -c /etc/snort/snort.conf</code><br>

<code>apt-get install leafpad</code><br>

<code>wget https://raw.githubusercontent.com/bhdresh/SnortRules/master/Exploit/all.rules</code><br>

<code>cp -r all.rules /etc/snort/rules</code><br>

<code>snort -r 2017-05-18-WannaCry-ransomware-using-EnternalBlue-exploit.pcap -v -c /etc/snort/snort.conf -l /var/log/snort</code><br>

<code>leafpad /var/log/snort/snort.alert.fast</code><br>

<code>cat /var/log/snort/snort.log</code><br>

<code>cat /var/log/snort/snort.log|grep -aoE '.{20,100}'</code><br>

#<code>echo "" > /var/log/snort/snort.alert.fast</code><br>

