# ⚡️Google Dorks - Vulnerable Parameters ⚡️
## Google hacking/dork para achar parametros vulneraveis Bug Bounty/Pentest



### ⛔️XSS prone parameters:
```
inurl:q= | inurl:s= | inurl:search= | inurl:query= | inurl:keyword= | inurl:lang= inurl:& site:example[.]com
```
### ⛔️Open Redirect prone parameters
```
inurl:url= | inurl:return= | inurl:next= | inurl:redirect= | inurl:redir= | inurl:ret= | inurl:r2= | inurl:page= inurl:& inurl:http site:example[.]com
```
### ⛔️SQLi Prone Parameters
```
inurl:id= | inurl:pid= | inurl:category= | inurl:cat= | inurl:action= | inurl:sid= | inurl:dir= inurl:& site:example[.]com
```
### ⛔️SSRF Prone Parameters
```
inurl:http | inurl:url= | inurl:path= | inurl:dest= | inurl:html= | inurl:data= | inurl:domain=  | inurl:page= inurl:& site:example[.]com
```
### ⛔️LFI Prone Parameters
```
inurl:include | inurl:dir | inurl:detail= | inurl:file= | inurl:folder= | inurl:inc= | inurl:locate= | inurl:doc= | inurl:conf= inurl:& site:example[.]com
```

### ⛔️RCE Prone Parameters
```
inurl:cmd | inurl:exec= | inurl:query= | inurl:code= | inurl:do= | inurl:run= | inurl:read=  | inurl:ping= inurl:& site:example[.]com
```

### BY:Ivar satierf
Credit- Mike Takashi
