<div align="center">
   <img src="https://github.com/user-attachments/assets/c35a4b8f-c08a-47c6-b5d9-66cbc884175e" hight="100" width="200" align="center"/>
</div>


<br>
<br>
<br>

<div align="center">
   
|Loxs|Multi Vulnerability Scanner|for web application|
|----------------|--------------|-------------|
| `L`| `=`| `Local File Inclusion (LFI)`|
| `O`| `=`| `Open Redirection (OR)`|
| `X`| `=`| `Cross Site Scripting (XSS)`|
| `S`| `=`| `Structured Query Language Injection (SQLi)`|
</div>
   
----
> **Loxs** is an easy-to-use tool that finds web issues like `LFI` - `OR` - `SQLi` - `XSS`. <br><br> *`Made by`* - [`AnonKryptiQuz`](https://github.com/AnonKryptiQuz) x [`Coffinxp`](https://github.com/coffinxp) x [`HexShad0w`](https://github.com/HexShad0w) x [`Naho`](https://github.com/Naho666) x [`1hehaq`](https://github.com/1hehaq)!
----

## Features

- **LFI Scanner**: Detect Local File Inclusion vulnerabilities.
- **OR Scanner**: Identify Open Redirect vulnerabilities.
- **SQL Scanner**: Detect SQL Injection vulnerabilities.
- **XSS Scanner**: Identify Cross-Site Scripting vulnerabilities.
- **Multi-threaded scanning**: Improved performance through multi-threading.
- **Customizable payloads**: Adjust payloads to suit specific targets.
- **Success criteria**: Modify success detection criteria for specific use cases.
- **User-friendly command-line interface**: Simple and intuitive.
- **Save vulnerable URLs**: Option to save the results of vulnerable URLs to a file.
- **HTML Report Generation**: Generates a detailed HTML report about the found vulnerabilities.
- **Share HTML Report via Telegram**: Send the HTML vulnerability report through telegram.


## Requirements

- **Python 3.x**
- `webdriver_manager`
- `selenium`
- `aiohttp`
- `beautifulsoup4`
- `colorama`
- `rich`
- `requests`
- `gitpython`
- `prompt_toolkit`
- `pyyaml`
- `Flask`
- `html`
- `telegram`

## Installation

### Clone the repository

```bash
git clone https://github.com/1hehaq/loxs.git
cd loxs
```
## Running the Script

To run the script, use the following command:

```bash
python loxs.py
```
to update the tool to the latest version
```bash
just edit the config.yml file with your tool directory
after pressing 5 and exiting from the tool run the tool again it will run with an updated version
```
## Input Information:

- **Input URL/File**: You can provide a single URL or an input file containing a list of URLs to scan.
- **Payload File**: Select or provide a custom payload file for the type of vulnerability you want to scan for.
- **Success Criteria:**:  Define the patterns or strings that indicate a successful exploitation attempt.
- **Concurrent Threads:**: Set the number of threads for multi-threaded scanning.
- **View and Save Results:**: Results will be displayed in real-time as the scan progresses.
After the scan completes, you will have the option to save the URLs found to be vulnerable to a file for future reference.

## Customization

Lostxlso allows for various levels of customization to fit your specific testing needs:
- **Custom Payloads:**: Create or modify payload files to suit specific vulnerability types or applications. Payloads should be tailored to the vulnerability being tested.
- **Success Criteria:**: Adjust the success criteria patterns in the tool to identify successful exploitation attempts more accurately. For example, you can modify the tool to check for specific error messages or unique responses.
- **Concurrent Threads:**:  Control the number of concurrent threads used during the scan to optimize performance based on system resources.

## Chrome Installation Instructions

1. Launch Terminal.

2. Download the Google Chrome .deb file: wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

3. Install the downloaded Google Chrome .deb file: sudo dpkg -i google-chrome-stable_current_amd64.deb

4. Enter your Ubuntu/kali user password.

5. If you come across some errors during the install, use the following command and flag:

   sudo apt -f install

   after this again enter this sudo dpkg -i google-chrome-stable_current_amd64.de

   Done

## Disclaimer

Lostxlso is intended for educational and ethical hacking purposes only. It should only be used to test systems you own or have explicit permission to test. Unauthorized use of third-party websites or systems without consent is illegal and unethical.
