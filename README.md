# Subdomaindive
Subdomaindive is a tool that helps you find subdomains. It helps you discover subdomains under a given target domain. The script is written in Bash, making it a lightweight and versatile tool. A bug bounty hunter or penetration tester can easily find sub-domains on their target website with this tool.

# Features 
*  Crt.sh
*  Baidu
*  Yahoo
*  Google
*  Bing
*  Ask
*  Netcraft
*  DNSdumpster
*  ThreatCrowd
*  SSL Certificates
*  PassiveDNS
*  Subfinder
*  Amaas


# Requirments 
1. sudo apt install subfinder
2. sudo apt install amaas
3. sudo apt install assetfinder

# Install

```
sudo su
git clone https://github.com/b0mk35h/Subdomaindive.git
cd Subdomaindive
chmod +x subdomaindive
cp subdomaindive /usr/local/bin/
```

# Use 
<pre>
b0mk35h㉿kali:~$ subdomaindive -h
 ____        _     ____                        _       ____  _           
/ ___| _   _| |__ |  _ \  ___  _ __ ___   __ _(_)_ __ |  _ \(_)_   _____ 
\___ \| | | | '_ \| | | |/ _ \| '_ ` _ \ / _` | | '_ \| | | | \ \ / / _ \
 ___) | |_| | |_) | |_| | (_) | | | | | | (_| | | | | | |_| | |\ V /  __/
|____/ \__,_|_.__/|____/ \___/|_| |_| |_|\__,_|_|_| |_|\____/|_| \_/ \___|

                                                       
            🗲  Automated Subdomain Gathering Tool   🗲
                 Developed By b0mk35h
         

Usage:
$ subdomaindive [flags]

Flags:
INPUT:
  -d, -domain string  domains to find subdomains for

OUTPUT:
  -o, -output string  file to write output to

HELP:
  -h, -help       find help

VERSION:
  -v, -version    display version information
  
UPDATE:
  -u, -update     check for updates and update if available
  
Sample command:  
b0mk35h㉿kali:~$ subdomaindive -d example.com -o output.txt

</pre>
