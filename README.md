# Web_X
Web_X Is very best script for find site directory and admin page finder  
Coder : Farid Ghulami
for help msg me for linkedin ðŸ‘‡
linkedin : Farid Ghulami Cyber security expert


# Web_X
A script to find admin login pages and EAR vulnerabilites.

#### Features
- [x] Multi-threading on demand
- [x] Big path list (482 paths)
- [x] Supports php, asp and html extensions
- [x] Checks for potential EAR vulnerabilites
- [x] Checks for robots.txt
- [x] Support for custom patns

### Usages

 Work in :
Kali linux 
Termux
Windows

Install :

git clone https://github.com/faridghulami/Web_X.git

cd Web_X

python3 Web_X.py


- Check all paths with php extension
```
python3 Web_X.py -u example.com --type php
```
- Check all paths with php extension with threads
```
python3 Web_X.py -u example.com --type php --fast
```
- Check all paths without threads
```
python3 Web_X.py -u example.com
```
- Adding a custom path. For example if you want all paths to start with /data (example.com/data/...) you can do this:
```
python3 Web_X.py -u example.com --path /data
```
<b>Note: </b> When you specify an extension using <b>--type</b> option, Web_X includes paths of that extension as well as paths with no extensions like <b>/admin/login</b>

