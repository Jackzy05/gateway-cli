# Netconfig
Netconfig is a collection of tools for my CLI to configure my network fast and simple. Some examples of its usage are on the picture below.
<img src="netconfig.png">

## Installation
If you'd like to setup netconfig for your local machine you can follow these steps:

1. Install [Python](https://www.python.org/downloads/) including the `pip` package manager. Make sure to check the "Add to PATH" checkbox as well.
2. Install all needed modules -> `pip install bs4`, `pip install requests` and others if needed.
3. Add the python extension (.PY) to the [PATHTEXT](https://www.msftnext.com/what-is-the-pathext-environment-variable-in-windows-10/) in the system environment variables
4. Add the `config.json` file to [path](https://www.maketecheasier.com/what-is-the-windows-path/).
5. Get your default gateway IP from the CLI using the `ipconfig` command. Paste that IP into your browser and explore API endpoints using [devtools](https://developer.chrome.com/docs/extensions/reference/devtools_network/).
6. Change the default gateway as well as the endpoints located in `netconfig.py`.
