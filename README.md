# XSpear Tool

### This script uses XSpear, Waybackurls, and Bhedak to scan multiple domains for XSS vulnerabilities.

#### To run this script, you need to install XSpear, Waybackurls and Bhedak:
```
## For XSpear installation, use the install.sh script or otherwise use this commands:
$ gem install XSpear

## For libraries, use this commands:
$ gem install colorize
$ gem install selenium-webdriver
$ gem install terminal-table
$ gem install progress_bar

## For Waybackurls installation, use this command:
$ go install github.com/tomnomnom/waybackurls@latest

## For Bhedak installation, use this command:
$ pip3 install bhedak
```
### Usage XSpear script:
```
# Clone this repo
$ git clone https://github.com/hackerhijeck/XSpear.git
# Go to the Directory
$ chmod +x XSpear.sh
# Usage
$ ./XSpear.sh domains.txt
(domains.txt= list of domains)
```

<a href="https://github.com/hahwul/XSpear">Official XSpear Github Link</a>
