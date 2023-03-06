# Hello!

My name's Peter, and I like to code and stuff.

A lot of my code isn't available publicly, but some of it is; links and description provided below.

## Programming languages

### Shell scripts

<details>
Most of the code I write is shell scripts. Why?
1. Faster to write
2. Less code
3. Most systems can run a portably-written shell script
4. If you can't write it, you can probably read it
5. Good enough for most tasks

But I'm not some crazy fanatic. There's obvious times when you shouldn't use a shell script, like:
1. When it would be better to write in a different language

I could write a book explaining when you should use what language for what purpose,
but nobody's paid me for that yet, and writing books is hard. So I haven't done that.

Instead I'll just say that the idea that *"if it's more than 100 lines of Shell, write it in Python"*
makes as much sense as *"if it's more than 100 lines of Python, write it in Lisp"*.

(*don't @ me, Lisp people.*)
</details>
 
#### My Shell Script Repos

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
 - **[junkdrawer](https://github.com/peterwwillis/junkdrawer)** - Smaller scripts and junk.
 
 
### Python scripts

<details>
The rest of the code I write is mostly Python. Why?
1. Everybody else can read/write it

Python is a terrible language made by terrible people. I only use it because if
I didn't, I probably wouldn't get hired. But on the scale of tragedies in my life,
this is one of the smaller ones, so I deal. I'm halfway decent at it, but I don't
get very fancy. When I see multiple lambdas and annotations in one function, I think
of all the people in my life who have given me grief over shell one-liners...
</details>

#### My Python Repos

 - **[dump-google-keep-notes](https://github.com/peterwwillis/dump-google-keep-notes)** - Dumps Google Keep to Markdown files with front matter for the metadata.
 - **[bump-version-yaml](https://github.com/peterwwillis/bump-version-yaml)** - Bump the version number in a YAML file, using a schema file to determine what part of the YAML gets updated, and how.
 - **[fix-atlassian-links](https://github.com/pwillis-els/fix-atlassian-links)** - Basically just search and replace on Confluence pages.
 - **[junkdrawer](https://github.com/peterwwillis/junkdrawer)** - Smaller scripts and junk.



### Perl scripts

<details>
I grew up with Perl, and I still love it. If I need to get something complex and
powerful done super quickly, and nobody at work needs to maintain it, Perl is my go-to.
 
I rarely use it now, but every now and then I find a use for it due to its incredible
simplicity at processing data.
 
Honestly, it's no worse than Python (I would argue much better), but it has a bad reputation
because people who never learned how to program - or even form coherent ideas - could still
string together Perl code that would actualy run. Personally I think that's a credit to Perl,
but good luck convincing anyone else of that.
</details>

#### My Perl Repos

 - **[junkdrawer](https://github.com/peterwwillis/junkdrawer)** - Smaller scripts and junk.


### C code

<details>
After I learned Perl, I learned C. I was never fantastic at it, but it served many purposes for me.
Mostly having the ability to write or modify patches for programs and debug them with gdb.
 
One of the first projects I created was an init replacement. I wanted a CD-bootable Linux distro
that would boot as fast as possible to bootstrap Beowulf clusters, so I wrote it in C. Later the
source code was taken by someone, modified, and put as a binary into their own distro, even though
my code was covered by GPL v2... I guess that's a compilement of sorts?? 
 
I've even written an entire CGI web frontend for a floppy disk Linux router in C.
I... don't recommend it.
</details>
 
#### My C Repos

 - **[etherdump](https://github.com/peterwwillis/etherdump)** - A tiny tcpdump, with no dynamic memory. Packet processing is built-in, not from libpcap. Useful on embedded machines, or just to learn about tcp/ip protocols.


<!--
**peterwwillis/peterwwillis** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
