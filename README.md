# BHEH's TerminatorZ

<p align="center">
<a href="https://www.blackhatethicalhacking.com"><img src="https://pbs.twimg.com/profile_banners/770898848197795840/1650879597/1500x500" width="600px" alt="BHEH"></a>
</p>
<p align="center">
<a href="https://www.blackhatethicalhacking.com"><img src="https://www.blackhatethicalhacking.com/wp-content/uploads/2022/06/BHEH_logo.png" width="300px" alt="BHEH"></a>
</p>

<p align="center">
TerminatorZ is written by Chris "SaintDruG" Abou-Chabke from Black Hat Ethical Hacking with the help of #ChatGPT as an experimentation, with a lot of hours spent modifying the code generated by ChatGPT and is designed for Offensive Security attacks. 
</p>

# Description

TerminatorZ is a highly sophisticated and efficient web security tool that scans for potential vulnerabilities in your web applications. It uses a combination of advanced techniques, including using popular tools like waybackurls and curl, to scan your web applications and highlight any potential vulnerabilities. The results are displayed in an easy-to-read format in the terminal, and only vulnerable results are saved for further investigation. With its lightweight and fast nature, TerminatorZ is the perfect tool for any security professional who wants to keep their web applications secure.


# What Makes TerminatorZ Unique:

TerminatorZ is special because it's a highly sophisticated web security tool in bash, that uses a combination of cutting-edge technology and expert methodology to scan for various web application vulnerabilities. The tool leverages the power of curl and predefined known payloads to thoroughly test for vulnerabilities and validate their presence.

# The Flow & Methodology

The tool starts by asking the user to input the domain they wish to scan. It then creates a folder to store the results and starts the scan. The scan utilizes curl to make HTTP requests to the target domain and checks for various vulnerabilities by injecting known payloads. The tool then checks the responses for indicators of exploitation and validates the results to determine if the target is vulnerable.

The tool's methodology is carefully designed to ensure that each type of vulnerability is checked specifically and thoroughly. The tool employs a highly analytical and methodical approach to the scanning process, which results in the identification of even the most elusive vulnerabilities. The tool's logic is designed to be highly efficient and effective, making it the ultimate choice for red team security experts and web security professionals.

In conclusion, TerminatorZ is a game-changer in the world of web security. Its combination of technology, methodology, and expert logic makes it the ultimate tool for identifying and mitigating web application vulnerabilities.

# Features:

Scans for various web application vulnerabilities, including:

• SQL Injection (SQLi)

• Cross-Site Scripting (XSS)

• Cross-Site Request Forgery (CSRF)

• Remote Code Execution (RCE)

• Directory Traversal (DT)

• File Inclusion (FI)

• Sensitive Data Exposure (SDE)

• Server Side Request Forgery (SSRF)

• Shell Injection (SI)

• Broken Access Control (BAC)

• Generates Random Sun Tzu Quote for Red Teamers, Checks if you are connected to the Internet too!

• Utilizes tools such as waybackurls, curl, and others for comprehensive vulnerability assessments

• Lightweight and fast, delivering results in real-time directly to the terminal

• Only saves and reports vulnerabilities, making it easy to prioritize and remediate vulnerabilities in a timely manner

# Requirements:

• waybackurls: This tool can be installed by running go get github.com/tomnomnom/waybackurls

• cURL: This tool is commonly pre-installed on Kali Linux and Ubuntu, but can be installed by running apt-get install curl on Ubuntu or brew install curl on MacOS

• httpx: This tool is a fast and multi-purpose HTTP toolkit that allows running multiple probes using the retryablehttp library.

# Installation

`git clone https://github.com/blackhatethicalhacking/TerminatorZ.git`

`cd TerminatorZ`

`chmod +x TerminatorZ.sh`

`./TerminatorZ`

# Screenshot

**Main Menu**

<img width="958" alt="Screenshot 2023-02-01 at 7 36 42 PM" src="https://user-images.githubusercontent.com/13942386/216119836-2551058d-e69c-4590-b208-ed0cc996dae6.png">


# Compatibility: 

This tool has been tested on Kali Linux, Ubuntu and MacOS.

# To Do

A lot will be done and added to it, this is the starting point. If you want to contribute, send me a commit explaining what more / better you are doing, and will credit you if it fits the model of design in mind!

# Disclaimer

This tool is provided for educational and research purpose only. The author of this project are no way responsible for any misuse of this tool. 
We use it to test under NDA agreements with clients and their consents for pentesting purposes and we never encourage to misuse or take responsibility for any damage caused !

# Support

If you would like to support us, you can always buy us coffee(s)! :blush:

<a href="https://www.buymeacoffee.com/bheh" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>
