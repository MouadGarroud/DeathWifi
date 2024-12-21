# DeathWifi
This script is intended for educational purposes and penetration testing. Unauthorized use of this script on networks you do not own is illegal. Always seek permission before conducting any tests.

This script scans for available Wi-Fi networks and allows you to perform deauthentication attacks on selected networks.

## Requirements

- Python 3.x
- Required Python packages: `pandas`, `tabulate`
- Tools: `airmon-ng`, `airodump-ng`, `aireplay-ng` (must be installed and accessible)

## Usage

1. Run the script with root privileges.
2. The script will list available Wi-Fi networks.
3. Select networks to attack by entering their N°.
4. The script will start a deauthentication attack on the selected networks.

**Disclaimer:** Use this script only on networks you own or have explicit permission to test.
