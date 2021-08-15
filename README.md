# Voting System 1.0 - File Upload RCE (Authenticated Remote Code Execution)

The Voting System 1.0 (https://www.sourcecodester.com/php/12306/voting-system-using-php.html) allows PHP file uploads, which can lead to Remote Code Execution. This script is a fixed version of:

https://www.exploit-db.com/exploits/49445

You need credentials in order to use this exploit.

## Usage

Change host IP, attacker IP and port for the reverse shell and simply run it.

`git clone https://github.com/PenTestical/authenticatedRCE`

`cd authenticatedRCE && chmod +x quickRCE.py`

`python3 quickRCE.py`

