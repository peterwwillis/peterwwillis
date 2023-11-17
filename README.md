👋 Hello! My name is Peter, and I write code.

I've been involved in open-source development for about 20 years.
In that time I've written custom software, started open-source projects,
and contributed to Linux distributions and other FOSS projects.
I've also created and maintained thousands of FOSS software packages
for corporate Linux distributions.

🔭 I’m currently working on ...
 - [Terraformsh](https://github.com/pwillis-els/terraformsh)
 - [Palvella](https://github.com/peterwwillis/palvella)

---

Some of my projects have been lost to time, and some are closed-source,
but below is some of the FOSS stuff I could still find.

## Programming languages

### Shell
 - **[Terraformsh](https://github.com/pwillis-els/terraformsh)** - This is a wrapper for Terraform. Yes, we've all written one of these. But this one is probably the best wrapper for Terraform you'll ever use. It's written to be a useful systems admin tool, unlike Terraform, and it's simple and DRY, unlike Terragrunt.
 - **[jenkins-bootstrap.sh](https://github.com/pwillis-els/jenkins-bootstrap.sh)** - Have you ever needed to set up Jenkins before? This script will do it for you - but, like, the way it **should** be set up, from the start. I hate Jenkins so much. Hopefully this saves you some time and stress.
 - **[packersh](https://github.com/pwillis-els/packersh)** - Like the Terraform wrapper, but for Packer.
 - **[attach_ebs.sh](https://github.com/pwillis-els/attach_ebs.sh)** - Ever needed to attach an EBS volume to an EC2 instance? Here's a better way.
 - **[patch-solr-log4j](https://github.com/pwillis-els/patch-solr-log4j)** - <s>If</s> When Log4j comes back, patch it quickly.
 - **[jenkins-plugin-manager](https://github.com/pwillis-els/jenkins-plugin-manager)** - Jenkins is so braindead, its "new" plugin manager can't resolve dependencies properly. This will help you manage Jenkins plugins better.
 - **[newrelic_api_cli](https://github.com/pwillis-els/newrelic_api_cli)** - Back when I was forced to use New Relic *((shudder))*, they didn't support their whole API in Terraform, so you still had to script stuff directly with their API just to create alerts triggered by two locations. I threw this together so I could script more stuff with their API.
 - **[direnvsh](https://github.com/peterwwillis/direnvsh)** - Ever wanted to run a command while inheriting environment variables recursively from a reverse hierarchy? Well now you can!
 - **[bashdag](https://github.com/peterwwillis/bashdag)** - A directed acyclic graph in Bash. (It doesn't work, because I suck at algorithms)
 - **[clinst](https://github.com/peterwwillis/clinst)** - Download and install statically-compiled programs, and then select specific versions of them to run from different directories. This is intentionally horrible to read/write, please don't read the source code.
 - **[test.sh](https://github.com/peterwwillis/test.sh)** - A minimal test framework in Shell.
 - **[shell distributed system](https://github.com/peterwwillis/shell-distributed-system)** - A toy that is unfinished. The intent is to basically rewrite Kubernetes in Shell, but this time make it not suck. Intended to showcase how to design and implement distributed systems.
 - **[repeat.sh](https://github.com/peterwwillis/repeat.sh)** - Ever wanted to run a couple commands over and over again with some added features? Now it's easier!
 - **[twoman.sh](https://github.com/psypete/public-bin/blob/public-bin/src/security/twoman.sh)** - An example of a two-man authentication file crypto system.
 - **[junkdrawer](https://github.com/peterwwillis/junkdrawer)** - Smaller scripts and junk.
 
 
### Python
 - **[dump-google-keep-notes](https://github.com/peterwwillis/dump-google-keep-notes)** - Dumps Google Keep to Markdown files with front matter for the metadata.
 - **[bump-version-yaml](https://github.com/peterwwillis/bump-version-yaml)** - Bump the version number in a YAML file, using a schema file to determine what part of the YAML gets updated, and how.
 - **[fix-atlassian-links](https://github.com/pwillis-els/fix-atlassian-links)** - Basically just search and replace on Confluence pages.
 - **[junkdrawer](https://github.com/peterwwillis/junkdrawer)** - Smaller scripts and junk.


### Perl
 - **[create-dvd](https://github.com/psypete/public-bin/blob/public-bin/src/create-dvd)** - Command-line wrapper to make it easier to burn a video DVD
 - **[findphonewords.pl](https://github.com/psypete/public-bin/blob/public-bin/src/findphonewords.pl)** - Find English words in phone numbers
 - **[ldapcachder.pl](https://github.com/psypete/public-bin/blob/public-bin/src/networking/ldapcacher.pl)** - A rudimentary LDAP proxy. Caches and pools connections to an LDAP server so you don't hit connection limits.
 - **[print_network_map.pl](https://github.com/psypete/public-bin/blob/public-bin/src/networking/print_network_map.pl)** - Given an NMAP XML file, print a list of all the routes and hosts found.
 - **[pop3download.pl](https://github.com/psypete/public-bin/blob/public-bin/src/pop3download/pop3download-0.8.pl)** - A POP3 and IMAPv4 mail fetcher. Like Fetchmail, but less buggy.
 - **[user_login.pl](https://github.com/psypete/public-bin/blob/public-bin/src/system/auth_login.pl)** - User authentication for OpenVPN.
 - **[bluelock.pl](https://github.com/psypete/public-bin/blob/public-bin/src/system/bluelock.pl)** - Lock a desktop when a Bluetooth device goes out of range.
 - **[deldupes.pl](https://github.com/psypete/public-bin/blob/public-bin/src/system/deldupes.pl)** - Delete duplicate files
 - **[dumpfd.pl](https://github.com/psypete/public-bin/blob/public-bin/src/system/dumpfd.pl)** - Dump the file descriptors of a running process
 - **[encsh.pl](https://github.com/psypete/public-bin/blob/public-bin/src/system/encsh.pl)** - Turn any interpreted script into an encrypted program that never stores its source code on disk
 - **[meminfo.pl](https://github.com/psypete/public-bin/blob/public-bin/src/system/meminfo.pl)** - Summarize memory use of Linux processes
 - **[piratespeak.pl](https://github.com/psypete/public-bin/blob/public-bin/src/system/piratespeak.pl)** - Substitute words and phrases with pirate speak
 - **[dynamic-dnsmasq.pl](https://github.com/liquidm/dnsmasq/blob/master/contrib/dynamic-dnsmasq/dynamic-dnsmasq.pl)** - A Dynamic DNS HTTP API backend. It allows dnsmasq to be updated via a Dynamic DNS client. One of the first pieces of OSS code I wrote.
 - **[junkdrawer](https://github.com/peterwwillis/junkdrawer)** - Smaller scripts and junk.


### C code
 - **[etherdump](https://github.com/peterwwillis/etherdump)** - A tiny tcpdump, with no dynamic memory. Packet processing is built-in, not from libpcap. Useful on embedded machines, or just to learn about tcp/ip protocols.
 - **[ddnsu](https://sourceforge.net/projects/psydev/files/ddnsu/0.3.5/)** - A Dynamic DNS update client supporting No-IP and DynDNS. Pretty small, suitable for embedded environments.
 - **[eject](https://github.com/mirror/busybox/blob/master/util-linux/eject.c)** - The eject applet for Busybox
