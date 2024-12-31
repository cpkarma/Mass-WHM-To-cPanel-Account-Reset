## Mass WHM To cPanel Account Reset

**Tool Format:** https://domain.com:2087|user|pass

**Contact:** [@xnabob](https://t.me/xnabob)
**Channel:** [Telegram](https://t.me/cPanelKarma)

**Description:**
This Python script automates the process of resetting passwords for WHM cPanel accounts. It retrieves account information, generates strong random passwords, and updates the credentials via the WHM API. Results are saved immediately to a success.txt file.

**Features:**

 - Retrieves a list of accounts from WHM servers.
 - Generates strong, random passwords for each account.
 - Saves results (domain, username, new password) immediately to success.txt.
 - Error handling for connection issues, failed resets, and invalid responses.

**Dependencies:**

 - Python packages: requests, colorama.
 - WHM API credentials (username/password) and server list as input.

**Usage:**

 - Prepare a list of WHM servers in a text file (server_list.txt) with the format:
 - server_url|username|password
 - Run the script and provide the path to the server list file when prompted.
 - Monitor progress in the terminal and check success.txt for reset results.

**Notes:**

 - Use responsibly and secure any sensitive information.

**Tool Demo:**

![Image](https://raw.githubusercontent.com/cpkarma/img/refs/heads/main/whm-reset/Screenshot_1.png)

![Image](https://raw.githubusercontent.com/cpkarma/img/refs/heads/main/whm-reset/Screenshot_2.png)
