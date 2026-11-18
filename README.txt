# Kali Terminal Simulator

A standalone, offline terminal-style website for Experiment No. 6:
Penetration Testing Using Kali Linux.

## Run
1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge, Firefox, or another browser.
3. Type a supported command and press Enter.
4. Use Up/Down arrow keys to navigate command history.

## Lab workflow
Type `help` in the terminal to see the same list.

1. `ip addr` — identify the local IP address
2. `nmap 127.0.0.1` — scan the local target
3. `nmap -sV 127.0.0.1` — identify services and versions
4. `nmap -sC -sV 127.0.0.1` — perform a detailed scan
5. `nikto -h http://127.0.0.1:3000` — scan the local web application
6. `zap` — simulate the OWASP ZAP scan and alerts
7. `report` — print the penetration testing report and result

## Other supported commands
`ip a`
`ifconfig`
`pwd`
`whoami`
`hostname`
`date`
`uname -a`
`ls`
`ls -la`
`help`
`clear`

Shortcuts: Up/Down browse history, Ctrl+L clears the screen.

## Important
This is a visual simulation only. It does not execute shell commands, start
Nmap/Nikto/ZAP, perform network scans, or contact any target. The displayed
scan output is sample demonstration data for the lab record.
