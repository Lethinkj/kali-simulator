# Kali Terminal Simulator

A standalone, offline terminal-style website for demonstrating Experiment No. 6.

## Run
1. Extract the ZIP file.
2. Open `index.html` in Chrome, Edge, Firefox, or another browser.
3. Type a supported command and press Enter.
4. Use Up/Down arrow keys to navigate command history.

## Supported simulated commands
- `help`
- `ip addr`
- `ip a`
- `ifconfig`
- `pwd`
- `whoami`
- `hostname`
- `date`
- `uname -a`
- `ls`
- `ls -la`
- `nmap 127.0.0.1`
- `nmap -sV 127.0.0.1`
- `nmap -sC -sV 127.0.0.1`
- `nmap -sV -p 3000 127.0.0.1`
- `nikto -h http://127.0.0.1:3000`
- `zap`
- `clear`

## Important
This is a visual simulation only. It does not execute shell commands, perform network scans, or contact any target. The displayed scan output is sample demonstration data.
