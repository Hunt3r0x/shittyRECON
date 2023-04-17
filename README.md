# I,M COOKING IT....
## shittyRECON

shittyRECON is a Python-based bug bounty reconnaissance automation tool that helps you automate various aspects of your recon process, including subdomain enumeration, directory enumeration, port scanning, vulnerability scanning, JavaScript analysis, link discovery, URL enumeration, archived URL retrieval, DNS enumeration, fuzzing, XSS hunting, SQL injection testing, XXE injection testing, SSRF vulnerability detection, Git repository enumeration, Git secrets scanning, race condition testing, CORS testing, screenshot capture, and parameter enumeration.

## Installation

To install shittyRECON, you need to have Python 3.x installed on your system. You can download Python from the [official website](https://www.python.org/downloads/).

Once you have Python installed, you can clone the shittyRECON repository from GitHub:

git clone https://github.com/Hunt3rox/shittyRECON.git


After cloning the repository, you can install the required Python packages by running the following command in the shittyRECON directory:

pip install -r requirements.txt


## Usage

To use shittyRECON, you need to provide the target domain as a command-line argument:

python shittyRECON.py -d example.com


This will run all the available reconnaissance modules in shittyRECON against the target domain.

You can also run specific modules by commenting out the ones you don't want to run in the `shittyRECON.py` file.

## Modules

Here are the modules that are currently available in shittyRECON:

- **Subdomain Enumeration:** Uses subfinder and Sublist3r to enumerate subdomains for the target domain.
- **Directory Enumeration:** Uses dirsearch and FFuF to enumerate directories for the target domain.
- **Port Scanning:** Uses nmap and MassDNS to scan for open ports on the target domain.
- **Vulnerability Scanning:** Uses vulners to scan for vulnerabilities on the target domain.
- **JavaScript Analysis:** Uses GetJS to analyze JavaScript files for the target domain.
- **Link Discovery:** Uses GoLinkFinder to discover links for the target domain.
- **URL Enumeration:** Uses getallurls to enumerate URLs for the target domain.
- **Archived URL Retrieval:** Uses WayBackUrls to retrieve archived URLs for the target domain.
- **DNS Enumeration:** Uses MassDNS to enumerate DNS records for the target domain.
- **Fuzzing:** Uses FFuF to fuzz the target domain for hidden files and directories.
- **XSS Hunting:** Uses XSSHunter to hunt for XSS vulnerabilities on the target domain.
- **SQL Injection Testing:** Uses SQLMap to test for SQL injection vulnerabilities on the target domain.
- **XXE Injection Testing:** Uses XXEInjector to test for XXE injection vulnerabilities on the target domain.
- **SSRF Vulnerability Detection:** Uses SSRFDetector to detect SSRF vulnerabilities on the target domain.
- **Git Repository Enumeration:** Uses GitTools to enumerate Git repositories for the target domain.
- **Git Secrets Scanning:** Uses gitallsecrets to scan for secrets in Git repositories for the target domain.
- **Race Condition Testing:** Uses RaceTheWeb to test for race conditions on the target domain.
- **CORS Testing:** Uses CORStest to test for CORS vulnerabilities on the target domain.
- **Screenshot Capture:** Uses EyeWitness to capture screenshots of the target domain.
- **Parameter Enumeration:** Uses parameth to enumerate parameters for the target domain.

## Disclaimer

This tool is intended for educational and research purposes only. Please use it responsibly and at your own risk. The author is not responsible for any illegal or unethical activities done using this tool.
