<div align="center">

# 🕵️‍♂️ DnsThief v0.1

> Fast and lightweight DNS subdomain brute-force tool for reconnaissance, built for speed with multithreading and customizable wordlists.  
> Ferramenta rápida e leve de brute-force de subdomínios DNS para reconhecimento, feita para alta performance com multithreading e wordlists customizáveis.

<img src="https://img.shields.io/badge/version-v0.1-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/python-3.x-green?style=for-the-badge">
<img src="https://img.shields.io/badge/status-active-success?style=for-the-badge">

---

<pre>
░░░░░░░░░░░░░░░▄▄▄▄▄▄▄▄░░░░░░░░░░░░░░
░▄█▀███▄▄████████████████████▄▄███▀█░
░█░░▀████████████████████████████░░█░
░░█▄░░▀████████████████████████░░░▄▀░
░░░▀█▄▄████▀▀▀░░░░██░░░▀▀▀█████▄▄█▀░░
░░░▄███▀▀░░░░░░░░░██░░░░░░░░░▀███▄░░░
░░▄██▀░░░░░▄▄▄██▄▄██░▄██▄▄▄░░░░░▀██▄░
▄██▀░░░▄▄▄███▄██████████▄███▄▄▄░░░▀█▄
▀██▄▄██████████▀░███▀▀▀█████████▄▄▄█▀
░░▀██████████▀░░░███░░░▀███████████▀░
░░░░▀▀▀██████░░░█████▄░░▀██████▀▀░░░░
░░░░░░░░░▀▀▀▀▄░░█████▀░▄█▀▀▀░░░░░░░░░
░░░░░░░░░░░░░░▀▀▄▄▄▄▄▀▀░░░░░░░░░░░░░░
</pre>

</div>

---

## ⚡ Installation & Usage

### 📥 Clone the repository
```bash
git clone https://github.com/yHunterDep/DNSThief/ dnsthief
cd dnsthief
```

### 🔐 Make it executable
```bash
chmod +x dnsthief
```

### 🚀 Run the tool
```bash
./dnsthief -d example.com
```

### 🧠 Advanced Usage

#### 📚 Using a custom wordlist
```bash
./dnsthief -d example.com -w wordlist.txt
```

#### ⚡ Increase concurrency (faster scans)
```bash
./dnsthief -d example.com -c 100
```

#### 🔇 Silent mode
```bash
./dnsthief -d example.com -s
```

#### 🔗 Pipe via stdin
```bash
cat domains.txt | ./dnsthief
```

### 🧪 Pro Tips
```bash
# Save results to file
./dnsthief -d example.com > subs.txt

# Fast recon workflow
cat domains.txt | ./dnsthief.py -c 50 -s | tee results.txt
```

### 🐧 Requirements
- Python 3.x
- Linux / macOS / WSL

### ⚠️ Notes
```bash
./dnsthief -d example.com
```

---

<div align="center">

### 🗿 Made by HunterDep

</div>
