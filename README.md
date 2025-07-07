## ⚠️ Disclaimer

# SSH Brute Forcer (For Educational Use Only)

Do not use it on systems you do not have explicit permission to test.

# 🔐 SSH Brute Forcer (Python + Paramiko)

This is a simple Python script that brute-forces SSH login using a custom wordlist and the `paramiko` library.
  
Do not use it on systems you do not have explicit permission to test.

---

## 🛠️ Requirements

- Python 3
- Paramiko 
  Install it with:

```bash
pip install paramiko
🚀 Usage
python3 ssh-brute.py <target-ip> <username> <wordlist.txt>
✅ Example
python3 ssh-brute.py 10.10.1.100 alex wordlist.txt
📁 Output
If the script finds a valid password, it will print:
[+] Success: Found password 'letmein'
Otherwise, it will continue until the end of the wordlist.
# SSH_Brute
