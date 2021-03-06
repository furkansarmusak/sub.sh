# 🎯🕸📘 Multiprocessing(Parallel)Subdomain Detect Script [![CMD](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## ✨ 🔺Sub.sh but without API key 🔻

## https://github.com/cihanmehmet/sub.sh

## ‼️ [jq](https://stedolan.github.io/jq/download/) , [httprobe](https://github.com/tomnomnom/httprobe) and [parallel](https://www.gnu.org/software/parallel/parallel_tutorial.html) required 📌

## 📘 ✅ Used Services 
```diff
+ https://crt.sh
+ http://web.archive.org
+ https://dns.bufferover.run
+ https://www.threatcrowd.org
+ https://api.hackertarget.com
+ https://certspotter.com
+ https://jldc.me/
+ https://www.virustotal.com
+ https://otx.alienvault.com
+ https://urlscan.io
+ https://api.threatminer.org
+ https://ctsearch.entrust.com
+ https://riddler.io
+ https://dnsdumpster.com
+ https://rapiddns.io
[-] Removed service
- https://suip.biz (Amass,Subfinder,Findomain)
# 🔨 Used Passive Scan Tool
+ Findomain
+ Subfinder
+ Assetfinder
```
## 💢 USAGE 💡
### Script Usage 🎯

### Small Scan
```bash
./sub.sh -s webscantest.com
```
```bash
curl -sL https://git.io/JesKK | bash /dev/stdin -s webscantest.com
```
### All Scan
```bash
./sub.sh -a webscantest.com
```
![image](https://i.imgur.com/FuIh0wQ.png)

##  🔸 Required tool automatic install
```bash
./sub.sh -i
```
## Demo
Use this link to test Sub.sh directly in your browser:
###
[![Open in Cloud Shell](https://gstatic.com/cloudssh/images/open-btn.png)](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/cihanmehmet/sub.sh&tutorial=README.md)

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
## 🔑 📜 Subdomain Detect Terminal Shortcut Function
### nano ~/.zshrc
or
### nano ~/.bashrc

```bash
function subdomain() { curl -sL https://git.io/JesKK | bash /dev/stdin "$1" "$2" }
```
## 💡 Usage
```bash
subdomain webscantest.com
```
![image](https://i.imgur.com/L2sufiT.png)

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

## 🧵 Docker Usage
### https://github.com/cihanmehmet/sub.sh/issues/4

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 

<table>
  <tr>
    <th><center>CMD</center></th>
  </tr>
  <tr>
    <td>
    <p align="center"><img src="https://avatars0.githubusercontent.com/u/7144304?s=400&u=4f09aca07d60b9dc0825aa5d25615cbe3840621d&v=4" alt="Cihan Mehmet DOĞAN" width="200px"/></p>
    </td>
  </tr>
  <tr>
    <td>
      <div align="center">
        <a href="https://www.linkedin.com/in/cihanmehmet/">
          <img src="https://cdnjs.cloudflare.com/ajax/libs/foundicons/3.0.0/svgs/fi-social-linkedin.svg" alt="Linkedin" width="40px"/>
        </a>
        <a href="https://twitter.com/cihanmehmets">
          <img src="https://cdnjs.cloudflare.com/ajax/libs/foundicons/3.0.0/svgs/fi-social-twitter.svg" alt="Twitter" width="40px"/>
        </a>
        <a href="https://canyoupwn.me/author/cmd/">
          <img src="https://cdnjs.cloudflare.com/ajax/libs/foundicons/3.0.0/svgs/fi-web.svg" alt="Website" width="40px"/>
        </a>
      </div>
    </td>
  </tr>
</table>

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
## :triangular_flag_on_post: 💻 I am open to suggestions for improvement.
