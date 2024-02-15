Python ASN Lookup Script
Overview
This Python script provides a command-line interface for querying ASN information based on IP addresses, neighbor ASNs, and historical neighbor ASNs using the RIPE Stat API. It offers users the ability to:

Look up the ASN and organization name associated with a specific IP address.
Fetch current neighbor ASNs for a given ASN.
Fetch historical neighbor ASNs for a given ASN.

Prerequisites
Python 3.x
requests library

Installation

Ensure Python 3 is installed on your system. You can download it from python.org.

Install the requests library, if it's not already installed, using pip:

pip install requests

Download the script asnlookup.py to your local machine.

Usage

To use the script, open a terminal or command prompt, navigate to the directory containing asnlookup.py, and run:

python asnlookup.py

Follow the on-screen prompts to select one of the available options:


Look up ASN and organization name by IP address: Enter an IP address when prompted to retrieve its associated ASN and organization name.

Fetch neighbor ASNs for a given ASN: Enter an ASN to find its current neighbor ASNs.

Fetch historical neighbor ASNs for a given ASN: Enter an ASN to find its historical neighbor ASNs.


Additional Notes
This script uses the RIPE Stat API to fetch data. Ensure you have a stable internet connection while using the script.
The accuracy and availability of data depend on the RIPE Stat API's current status and data coverage.
An IP prefix may have multiple associated ASN's (for a variety of reasons) you can use my RPKI checker to get other ASN's https://github.com/chrisjchandler/RPKI_check_tool

Contributing
Contributions to this script are welcome. If you have suggestions for improvements or bug fixes, please feel free to fork the repository, make your changes, and submit a pull request.

License

This script is released under the MIT License. See the LICENSE file in the repository for full details.
